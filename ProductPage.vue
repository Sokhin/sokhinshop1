<template>
  <div class="product">
    <div class="title">
      <div class="standline"></div>
      <h3>Products</h3>
    </div>
    <hr />
    <div class="product1">
      <!--line1-->
      <div class="order">
        <img src="@/assets/mango.jpg" />
        <p class="name">Mango</p>
        <p class="price">10$</p>
        <div class="button">
          <a href="#" class="info">Info</a>
          <a href="#" class="buy">Buy</a>
        </div>
      </div>

      <div class="order">
        <img src="@/assets/mango.jpg" />
        <p class="name">Mango</p>
        <p class="price">10$</p>
        <div class="button">
          <a href="#" class="info">Info</a>
          <a href="#" class="buy">Buy</a>
        </div>
      </div>
    </div>
    <div class="product2">
      <div class="order">
        <img src="@/assets/laptop.jpg" />
        <p class="name">Mac Book</p>
        <p class="price">1200$</p>
        <div class="button">
          <a href="#" class="info">Info</a>
          <a href="#" class="buy">Buy</a>
        </div>
      </div>
      <div class="order">
        <img src="@/assets/laptop.jpg" />
        <p class="name">Mac Book</p>
        <p class="price">1200$</p>
        <div class="button">
          <a href="#" class="info">Info</a>
          <a href="#" class="buy">Buy</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProductPage",
};
</script>

<style scoped>
.title {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 5px;
  padding: 0 25px;
}
.standline {
  width: 5px;
  height: 13px;
  margin-left: 5px;

  background-color: rgb(223, 52, 214);
}
hr {
  background-color: rgb(190, 183, 183);
  width: 85%;
  margin-left: 30px;
  align-items: center;
}
.product {
  margin-top: 40px;
  background-color: white;
  padding: 20px 0;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
}
.order {
  background-color: rgb(255, 255, 255);
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 8px 16px rgba(0, 0, 0, 0.1);
}
.name {
  text-align: center;
}
.price {
  text-align: center;
  color: red;
}
.button {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
}
.button a {
  color: white;
  padding: 1px 5px;
  border-radius: 4px;
  text-decoration: none;
}
.info {
  background-color: green;
}
.buy {
  background-color: orange;
}
img {
  width: 100px;
  align-content: center;
}
.product1 {
  display: flex;
  justify-content: center;
  gap: 50px;
  padding: 40px 0;
}
.product2 {
  display: flex;
  justify-content: center;
  gap: 50px;
}
</style>
