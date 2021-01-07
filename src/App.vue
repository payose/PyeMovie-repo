<template>
   <header>
     <router-link to="/">
      <h1><span>Dao</span>Movies</h1>
     </router-link>
   </header>

  <main>
    <router-view/>
  </main>
</template>

<style lang="scss">
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
  font-family:'Fira Sans', sans-serif;

  &::selection{
    background: transparentize(#c6ea0c, 0.6);
  }
}

body{
  background-color: #339621;
}

a{
  text-decoration: none;
}

header{
  display:flex;
  align-items: center;
  justify-content: center;
  padding: 10px 16px;
  background-color: rgba(17, 16, 15, 0.966);
  box-shadow: 0px 0px 6px rgba(40, 85, 3, 0.938);

  h1{
    color: #fbfcfa;
    font-size: 28px;

    span{
      color: #185808;
    }
  }
}


</style>
