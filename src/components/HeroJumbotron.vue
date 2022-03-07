<template>
    <div class="jumbotron">
        <img src="../assets/logo.png" alt="">
        <h2>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptatum, autem.
        </h2>
    </div>
</template>

<script>
export default {
  name: 'TitleVueCli',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbotron{
    flex-grow: 1;
    border: 5px solid #41B883;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

img{
    height: 200px;
    width: 200px;
    margin-bottom: 20px;
}
</style>