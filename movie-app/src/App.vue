<script setup>

</script>

<template>
<header>
<router-link to="/">
<h1><span>Nova</span>Movies</h1>

</router-link>

</header>
<main>
  <RouterView />
</main>

</template>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;

  &::selection{
    background: transparentsize(#428883);
  }
}

body{
  background-color: #35495E;
}

a {
  text-decoration: none;
}

header{
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px 16px;
  background-color: #2C3D4E;
  box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.1);

  h1{
    color: #FFF;
    font-size: 28px;

    span{
      color: #428883;
    }
  }
}

</style>
