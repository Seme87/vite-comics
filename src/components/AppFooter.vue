<script>
export default {
  name: 'AppFooter',
}
</script>

<template>
 <footer>

  <div class="footer-top container">
    

    <div class="row">

      <div class="item-row-left">
      
        <div class="col">
          <h4>DC COMICS</h4>
      
          <ul>
            <li><a href="#">Chaarachters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>

          <div class=" link">
            <h4>DC</h4>
          
            <ul>
              <li><a href="#">Chaarachters</a></li>
              <li><a href="#">Comics</a></li>
          
            </ul>
          </div>
        </div>

        <div class="col">
          <h4>DC COMICS</h4>
        
          <ul>
            <li><a href="#">Chaarachters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </div>

        <div class="col">
          <h4>DC COMICS</h4>
        
          <ul>
            <li><a href="#">Chaarachters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </div>

        
      
      </div>
      
      <div class="item-row-right">

        <div class="logo-footer">
          <img src="../assets/dc-logo-bg.png" alt="">
        </div>

      </div>

    </div>
    
    

  </div>

  <div class="footer-bottom">
    <div class="section container">
      <div class="section-left">
        <button class="btn">SH0P NOW</button>
      </div>
      <div class="section-right">
        <ul>
          <li><a href="#"><h3>FOLLOW US</h3></a></li>
          <li><a href="#"><img src="../assets/footer-facebook.png" alt="#"></a></li>
          <li><a href="#"><img src="../assets/footer-twitter.png" alt="#"></a></li>
          <li><a href="#"><img src="../assets/footer-youtube.png" alt="#"></a></li>
          <li><a href="#"><img src="../assets/footer-pinterest.png" alt="#"></a></li>
          <li><a href="#"><img src="../assets/footer-periscope.png" alt="#"></a></li>
        </ul>
      </div>
    </div>
  </div>

 </footer>
</template>

<style lang="scss" scoped>
footer{
  
  background-image: url("../assets/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}

.row{
  display: flex;
  justify-content: space-between;
  height: 370px;
 
}

.item-row-left{
  padding: 50px 0;
  display: flex;
  flex-wrap: wrap;
  width: 40%;

}

.item-row-right{
 
  width: 100%;
  justify-content: flex-end;
  align-items: center;
  display: flex;
  overflow: hidden;

}

ul li a{
  font-size: 12px;
  text-decoration: none;
  color:gray;
}

ul li {
  list-style: none;
}

h4{
  margin-bottom: 10px;
  color: white;
}

.col{
  padding-bottom: 10px;
  width: calc(100% / 3);
}

.link{
  padding-top: 10px;
}

.footer-bottom{
  background-color: #303030;
  padding: 20px 0;
  
}

.section{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.section-left, .section-right{
  display: flex;
  align-items: center;
}
.section-right{
  ul{
    display: flex;
    align-items: center;
  }
  li{
    list-style: none;
    padding: 0 10px;
  }
}

.btn{
  color: white;
  background-color: inherit;
  border: 2px solid var(--primary-color);
  padding: 10px 40px;
}
</style>
