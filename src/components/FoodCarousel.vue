<template>
  <div class="carousel_food">
    <div class="wrap_carousel container">
      <div class="food_left foods">
        <i class="fa-solid fa-angle-left"></i>
      </div>
      <div class="food_1 foods">
        <div class="food_1_name">Pizza</div>
      </div>
      <div class="food_2 foods">
        <div class="food_1_name">Fast Food</div>
      </div>
      <div class="food_3 foods">
        <div class="food_1_name">Natsional</div>
      </div>
      <div class="food_4 foods">
        <div class="food_1_name">Dessert</div>
      </div>
      <div class="food_5 foods">
        <div class="food_1_name">European</div>
      </div>
      <div class="food_6 foods">
        <div class="food_1_name">Ice Cream</div>
      </div>
      <div class="food_right foods"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FoodCarousel',
}
</script>

<style scoped>
.carousel_food {
  width: 100%;
  height: 262px;
  margin-top: 62px;
}
.wrap_carousel {
  display: flex;
  justify-content: space-between;
  height: 100%;
  align-items: center;
  padding-top: 50px;
}
.foods {
  width: 150px;
  height: 160px;
  border: none;
  border-radius: 20px;
  cursor: pointer;
  padding-top: 132px;
  text-align: center;
  font-weight: bold;
  font-size: 18px;
  margin-right: 5px;
  transition: 0.5s all;
  color: #5f5621;
}
.foods:hover, .foods:active, .foods:focus {
  background-color: #968735;
}
.food_left {
  width: 40px;
  height: 80px;
  margin: 0;
  padding: 0;
  background-image: url('@/assets/left.png');
  background-repeat: no-repeat;
  background-size: 100%;
  background-position: center;
  border: none;
  transition: .3s all;
}
.food_left:hover, .food_left:active, .food_left:focus {
  background-color: rgb(253, 200, 84);
  background-image: url('@/assets/left.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
}
.food_right {
  width: 40px;
  height: 80px;
  margin: 0;
  padding: 0;
  background-image: url('@/assets/right.png');
  background-repeat: no-repeat;
  background-size: 100%;
  background-position: center;
  border: none;
  transition: .3s all;
}
.food_right:hover, .food_right:active, .food_right:focus {
  background-color: rgb(253, 200, 84);
  background-image: url('@/assets/right.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
}
.food_1 {
  background-image: url('@/assets/pizza_for_carousel.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
  background-repeat: no-repeat;
  background-size: 70%, 100%;
  background-position: center;
}
.food_2 {
  background-image: url('@/assets/hamburger_for_carousel.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
  background-repeat: no-repeat;
  background-size: 100%;
  background-position: center;
}
.food_3 {
  background-image: url('@/assets/natsional_for_carousel.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
  background-repeat: no-repeat;
  background-size: 80%, 100%;
  background-position: center;
}
.food_4 {
  background-image: url('@/assets/dessert_for_carousel.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
  background-repeat: no-repeat;
  background-size: 100%, 100%;
  background-position: center;
}
.food_5 {
  background-image: url('@/assets/european_for_carousel.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
  background-repeat: no-repeat;
  background-size: 75%, 100%;
  background-position: center;
}
.food_6 {
  background-image: url('@/assets/icecream_for_carousel.png'),
                    linear-gradient(to top, rgba(255, 174, 0, 0.829), rgba(255, 174, 0, 0));
  background-repeat: no-repeat;
  background-size: 80%, 100%;
  background-position: center;
  margin-right: 0;
}
</style>