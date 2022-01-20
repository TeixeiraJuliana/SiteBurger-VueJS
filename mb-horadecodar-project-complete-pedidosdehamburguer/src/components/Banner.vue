<template>
    <div id="main-banner">
        <h1>Make you burger</h1>
    </div>
</template>

<script>

export default {
  name: 'Banner',
  components: {

  }
}
</script>
<style scoped>
#main-banner{
    background-image: url('../assets//img/burger.jpg');
    background-position:0 -250px;
    background-size: cover;
    background-repeat: no-repeat;
    height: 500px;
    display: flex;
    align-items: center;
}
#main-banner h1{
    color: #fff;
    padding: 20px 30px;
    margin-left: 50px;
}

</style>

