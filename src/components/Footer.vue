<template>
  <div class="footer_main">
      <div class="footer_wrap container">
          <div class="footer_logo">
              <h3 class="footer_logo_title">
                  yasmin
              </h3>
          </div>
          <div class="footer_list">
              <ul class="footer_list_ul">
                  <li class="footer_list_li">Home</li>
                  <li class="footer_list_li">Contact</li>
                  <li class="footer_list_li">About Us</li>
              </ul>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style scoped>
.footer_main {
    width: 100%;
    height: 100px;
    background: rgb(39, 39, 39);
    color: #fff;
    padding-top: 36px;
    border-bottom: 1px solid #fff;
}
.footer_wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 60px;
}
.footer_logo_title {
    text-transform: uppercase;
    font-family: 'Shippori Antique B1', sans-serif;
    margin: 0;
    font-weight: bold;
    letter-spacing: 3px;
}
.footer_list_ul {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}
.footer_list_li {
    list-style: none;
    margin-left: 20px;
    color: #949494;
}
.footer_list_li:hover, .footer_list_li:active, .footer_list_li:focus {
    color: #fff;
    cursor: pointer;
} 
</style>