<template>
  <div class="Contents">
    <div class="title">
      <div class="standline"></div>
      <h3>Contents</h3>
    </div>
    <hr />
    <div class="Contents1">
      <div class="Phone">
        <img src="@/assets/phonelogo.jpg" />
      </div>
      <div class="Laptop">
        <img src="@/assets/laptoplogo.jpg" />
      </div>
      <div class="Book">
        <img src="@/assets/Booklogo.jpg" />
      </div>
      <div class="Moto">
        <img src="@/assets/Motologo.jpg" />
      </div>
    </div>
    <div class="Contents2">
      <div class="Vegetable">
        <img src="@/assets/Vegetable.jpg" />
      </div>
      <div class="Food">
        <img src="@/assets/Foodlogo.jpg" />
      </div>
      <div class="Shirt">
        <img src="@/assets/shirtlogo.jpg" />
      </div>
      <div class="Drink">
        <img src="@/assets/Drinklogo.jpg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentsPage",
};
</script>

<style scoped>
@media (max-width: 600px) {
  .title {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 5px;
  }
  .standline {
    width: 5px;
    height: 13px;
    background-color: rgb(223, 52, 214);
  }
  hr {
    background-color: rgb(190, 183, 183);
    margin-top: -40px;
  }
  .Contents {
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 40px;
    padding: 30px;
    background-color: white;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  .Contents1 {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 40px;
  }
  .Contents2 {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 40px;
  }
  .Phone {
    /*transition: box-shadow 0.3s ease;*/
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  /*.Phone:hover {
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2), 0 16px 32px rgba(0, 0, 0, 0.2);
  }*/
  .Laptop {
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  .Book {
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  .Moto {
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  .Food {
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  .Vegetable {
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  .Shirt {
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  .Drink {
    align-content: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
  }
  img {
    width: 40px;
    flex: 1 1 80px;
  }
}
</style>
