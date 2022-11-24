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

 </footer>
</template>

<style lang="scss" scoped>
footer{
  
  background-image: url("../assets/footer-bg.jpg");
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
  align-items: end;
  display: flex;

}

.logo-footer {
  background-size: cover;
  object-fit: cover;
  img{
    width:400px;
  }
  
}

ul li a{
  font-size: 12px;
  text-decoration: none;
  color:gray;
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
</style>
