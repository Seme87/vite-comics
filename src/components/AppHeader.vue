<script>


export default {
  name: 'AppHeader',
  
}
</script>

<template>
    <header class="container">
        <div class="logo">
            <img src="../assets/dc-logo.png" alt="Logo-header">
        </div>
        <nav class="main-nav">
          <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li ><a class="active" href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLUES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>
          </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
header{
  display: flex;
  justify-content: space-between;
  .main-nav{
    display: flex;
    align-items: center;
    
  }
}
ul{
  display: flex;
  height: 100%;
  li{
    display: flex;
    align-items: center;
    padding: 0 10px;
    list-style: none;
  }
}

li a{
  display: flex;
  align-items: center;
  height: 100%;
  text-decoration: none;
  color: #000;
  font-size: 13px;
  font-weight: bold;
}

.active{
  color: var(--primary-color);
  border-bottom: 2px solid var(--primary-color);
}

.logo{
  padding: 20px 0;
}
</style>
