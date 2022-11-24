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
            <li><a href="#">COMICS</a></li>
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
  padding: 20px 10px;
  display: flex;
  justify-content: space-between;
  .main-nav{
    display: flex;
    align-items: center;
    ul{
      display: flex;
      list-style: none;
      align-items: center;
      a{
        font-size: 13px;
        height: 100%;
        font-weight: bold;
        display: inline-block;
        padding: 0 15px;
        text-decoration: none;
        color: #000;
      }
    }
  }
}

// header {
//     text-align: center;
//     .main-nav {
//         ul {
//             display: flex;
//             list-style: none;
//             justify-content: center;

//             a {
//                 display: inline-block;
//                 padding: 15px 25px;
//                 text-decoration: none;
//                 color: #000;

//                 &.active {
//                     background-color: var(--secondary-color);
//                 }
//             }
//         }
//     }
// }
</style>
