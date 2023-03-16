<template>
    <!-- <div class="containerr">
        <div class="roww">

            <ul class="r-header">
                <li>
                    <p>
                        We have a 95% Successful Pass Rate!
                    </p>
                </li>
                <li>
                    
                    <p>
                        <i class="fa-solid fa-phone"></i>
                        
                        Give us a call to boook your tuition! 1-800-555-555                        
                    </p>
                </li>
            </ul>

        </div>

    </div> -->
     
     <!-- SECONDA SEZIONE HEADER -->

     <div class="container2">
        <div class="roww">
            <ul class="ul-header">
                <li>
                    <figure>
                        <img src="../assets/img/avada-drivers-logo-1x.png" alt="">
                    </figure>
                </li>
                <li class="gap">
                    <a href="">HOME</a>
                    <a href="">ABOUT</a>
                    <a href="">PRICES</a>
                    <a href="">COURSES <span class="new">NEW</span></a>
                    <a href="">LOCATIONS</a>
                    <a href="">BLOG</a>
                    <a class="book-now" href="">BOOK NOW</a>
                    
                </li>
            </ul>


        </div>
     </div>
</template>

<script>
   export default {
    name: 'AppHeader'
   }
</script>

<style scoped>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }

img {
    max-width: 100%;
}

a {
    text-decoration: none;
    color: currentColor;
    margin-right: 35px;
    color: white;

}

a:hover{
    color: #56b835;
}


.containerr {
    background-color: #333333;
   
}

ul {
   list-style-type: none;
}

.r-header {
    display: flex;
    justify-content: space-around;
    color: #7F9EA8;
    padding: 20px;    
    
}

.container2 {
    background-color: rgba(34, 34, 34, 0.2);;
    padding: 30px 100px;
    position: absolute;
    width: 100%;
    
    
}

.ul-header{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.book-now{
    background-color: #56b835;
    padding: 15px;
    border-radius: 999px;
    
}

.book-now:hover{
    color: white;
    background-color:  #62c342 ;
}

.new{
    background-color: #56b835;
    padding: 8px;
    border-radius: 10px;
    font-size: 10px;
    color: white;
}


</style>