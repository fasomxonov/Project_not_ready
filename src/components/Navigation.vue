<template>
  <div class="main_nav">
    <div class="wrap_navigation">
      <div class="container">
        <div class="navigation">
          <div class="navigation_titles">
            <div class="nav_title_left">
              <h1 class="nav_title_first">YASMIN</h1>
              <h2 class="nav_title_second">restaurant</h2>
            </div>
            <div class="nav_title_right">
              <div class="nav_map"></div>
              <div class="nav_user">User name</div>
            </div>
          </div>
          <div class="search_nav">
            <input type="text" class="nav_input form-control" placeholder="name, cuisine or dish">
            <button class="btn search_btn">Search</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navigation',
  components: {},
  data() {
    return {
    }
  },
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&family=Shippori+Antique+B1&display=swap');
.main_nav {
  width: 100%;
  height: 340px;
  margin: 0 auto;
}
.container {
  width: 100%;
}
.wrap_navigation {
  background-image: linear-gradient(to top, rgba(0,0,0,.45), rgba(0,0,0,.50)),
                    url('@/assets/food_bg_img.png');
  background-size: 100%;
  background-repeat: no-repeat;
  background-position: center;
  padding-bottom: 70px;
  height: 400px;
}
.navigation {
  padding-top: 6%;
  margin: 0 auto;
  width: 100%;
  height: 100%;
}
.navigation_titles {
  display: flex;
  justify-content: space-between;
}
.nav_title_left {
  margin-bottom: 60px;
}
.nav_title_first {
  position: relative;
  letter-spacing: 10px;
  font-size: 70px;
  text-shadow: 2px 2px 10px rgb(255, 0, 0);
  color: rgba(165, 255, 46, 0.842);
  font-weight: bold;
  font-family: 'Shippori Antique B1', sans-serif;
}
.nav_title_second {
  letter-spacing: 5px;
  font-size: 35px;
  font-family: 'Shippori Antique B1', sans-serif;
  font-weight: 900;
  text-shadow: 2px 2px 15px rgb(255, 0, 0);
  color: rgb(196, 255, 118);
}
.nav_title_right {
  display: flex;
  justify-content: space-between;
  padding-top: 3%;
}
.nav_map {
  width: 50px;
  height: 45px;
  background-color: rgb(209, 168, 81);
  border-radius: 5px;
  border: 1px solid rgba(223, 250, 205, 0.363);
  background-image: url('@/assets/map.png');
  background-repeat: no-repeat;
  background-size: 73%;
  background-position: center;
  cursor: pointer;
  box-shadow: -20px 30px 2px 0px rgba(46, 44, 44, 0.774);
}
.nav_user {
  width: 180px;
  height: 45px;
  background-color: rgb(209, 168, 81);
  border-radius: 5px;
  border: 1px solid rgba(223, 250, 205, 0.699);
  margin-left: 10%;
  padding-left: 20px;
  text-align: center;
  padding-top: 10px;
  color: aliceblue;
  background-image: url('@/assets/user.png');
  background-repeat: no-repeat;
  background-size: contain;
  background-position: left;
  cursor: pointer;
  box-shadow: -20px 30px 2px 0px rgba(46, 44, 44, 0.774);
}
.search_nav {
  display: flex;
  justify-content: space-between;
}
.nav_input {
  font-family: sans-serif;
  box-shadow: 0px, 0px, 5px, 5px, red;
  border: 1px solid rgb(94, 255, 0);
  background: rgba(2, 32, 1, 0.527);
  color: aliceblue;
}
.search_btn {
  border: 1px solid rgb(94, 255, 0);
  background: rgba(2, 32, 1, 0.527);
  color: aliceblue;
  font-family: sans-serif;
} 
.search_btn:hover {
  background: rgba(18, 82, 16, 0.801);
}
</style>