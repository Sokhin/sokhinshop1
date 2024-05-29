<template>
  <div class="footer">
    <p>Tel: 060901779</p>
    <p>Facebook: Sing Sokhin</p>
    <p>Email: sokhinsing@gmail.com</p>
    <p class="me">Made by me</p>
  </div>
</template>

<script>
export default {
  name: "FooterPage",
};
</script>

<style scoped>
@media (max-width: 600px) {
  .footer {
    margin-top: 40px;
    width: 100%;
    padding: 20px 10px;
    height: fit-content;
    border-radius: 10px 10px;
    background-color: rgb(79, 66, 122);
    color: white;
    text-align: center;
  }
  .me {
    margin-top: 10px;
    color: rgb(193, 182, 182);
  }
}
</style>
