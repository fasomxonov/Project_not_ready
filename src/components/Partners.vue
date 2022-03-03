<template>
  <div class="partners_cards_wrap">
      <h1 class="partners_title container">Partners</h1>
      <div class="cards_wrap_1 container">
          <div class="p_card p_card_1">
            <div class="p_card_img p_card_img_1"></div>
            <h4 class="p_card_title">Mehmon</h4>
            <p class="p_card_desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, temporibus, <span class="p_card_more"><a href="https://www.google.com" class="p_card_more_link">more...</a></span></p>
          </div>
          <div class="p_card p_card_1">
            <div class="p_card_img p_card_img_2"></div>
            <h4 class="p_card_title">Mezbon</h4>
            <p class="p_card_desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, temporibus, <span class="p_card_more"><a href="https://www.google.com" class="p_card_more_link">more...</a></span></p>
          </div>
          <div class="p_card p_card_1">
            <div class="p_card_img p_card_img_3"></div>
            <h4 class="p_card_title">Max Way</h4>
            <p class="p_card_desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, temporibus, <span class="p_card_more"><a href="https://www.google.com" class="p_card_more_link">more...</a></span></p>
          </div>
      </div>
      <div class="cards_wrap_2 container">
          <div class="p_card p_card_2">
            <div class="p_card_img p_card_img_4"></div>
            <h4 class="p_card_title">KFC</h4>
            <p class="p_card_desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, temporibus, <span class="p_card_more"><a href="https://www.google.com" class="p_card_more_link">more...</a></span></p>
          </div>
          <div class="p_card p_card_2">
            <div class="p_card_img p_card_img_5"></div>
            <h4 class="p_card_title">Mc Donald's</h4>
            <p class="p_card_desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, temporibus, <span class="p_card_more"><a href="https://www.google.com" class="p_card_more_link">more...</a></span></p>
          </div>
          <div class="p_card p_card_2">
            <div class="p_card_img p_card_img_6"></div>
            <h4 class="p_card_title">Evos</h4>
            <p class="p_card_desc">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, temporibus, <span class="p_card_more"><a href="https://www.google.com" class="p_card_more_link">more...</a></span></p>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Partners',
}
</script>

<style scoped>
.partners_cards_wrap {
    width: 100%;
}
.partners_title {
    position: relative;
    margin-top: 30px;
}
.partners_title:before {
    position: absolute;
    content: '';
    width: 180px;
    top: 50px;
    border: 1px solid rgb(107, 107, 107);
}
.cards_wrap_1 {
    display: flex;
    justify-content: space-between;
}
.cards_wrap_2 {
    display: flex;
    justify-content: space-between;
}
.p_card {
    width: 350px;
    height: 290px;
    margin: 20px 0;
    border-radius: 15px;
    border: 1px solid #c2c2c273;
    box-shadow: 2px 2px 10px 2px #c2c2c273;
    overflow: hidden;
}
.p_card_1 {
    margin-top: 30px;
}
.p_card_2 {
    margin-bottom: 50px;
}
.p_card_img {
    width: 100%;
    height: 190px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    box-shadow: 2px 2px 10px 5px #adadad;
}
.p_card_img_1 {
    background-image: url('@/assets/mehmon.jpg');
}
.p_card_img_2 {
    background-image: url('@/assets/mezbon.jpg');
}
.p_card_img_3 {
    background-image: url('@/assets/max_way.jpg');
}
.p_card_img_4 {
    background-image: url('@/assets/kfc.jpg');
}
.p_card_img_5 {
    background-image: url('@/assets/mc_donalds.jpg');
}
.p_card_img_6 {
    background-image: url('@/assets/evos.jpg');
}
.p_card_title {
    font-weight: bold;
    font-size: 22px;
    margin: 12px 10px 5px 10px;
}
.p_card_desc {
    margin: 0 10px 0 10px;
    font-size: 15px;
    color: #8d8d8d;
}
.p_card_more {
    color: rgb(41, 98, 255);
}
.p_card_more_link {
    text-decoration: none;
}
</style>