<template>
  <footer id="footer">
    <p>make your burger &copy; 2022</p>
  </footer>
</template>
<script>
export default {
  name: 'Footer',
  components: {

  }
}
</script>
<style scoped>
footer{
  display: flex;
  align-items: flex-end;
}
  #footer{
    height: 200px;
    background-color: #222;
    border-top: 4px solid #111;
    color: #fcba03;
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;

    
  }
</style>