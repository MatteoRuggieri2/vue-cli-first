<template>
    <div>
        <div class="jumbotron">
            <h3>Hey! Questo è un jumbotron!</h3>
        </div>
    </div>
</template>

<script>
export default {
  name: "Hero"
};
</script>

<style scoped>
h3 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 25px;
  padding: 30px 100px;
  background-color: rgba(255, 255, 255, 0.39);
}

.jumbotron {
    background-image: url("../assets/img/aerial_drone.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>