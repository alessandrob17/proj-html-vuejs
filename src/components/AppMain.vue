<template>
    <!-- SECTION1 -->

    <section>
        <div class="s1-container">

            <div class="container-h">
                <h1>
                Drive with Avada
            </h1>

            <h3 class="h3-hero">
                We offer the finest driving tuition money can buy
            </h3>

            </div>
        </div>
    </section>

    <!-- SECTION2 -->

    <section>
        <div class="container-s2">
            <div>
                <ul class="s2-ul">
                    <li>
                        <h1>Get Behind The Wheel</h1>
                    </li>
                    <li>
                        <h4>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A assumenda alias laboriosam, eos ex numquam amet atque non molestias?</h4>
                    </li>
                    <li>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque eaque repellendus vel cupiditate harum ex adipisci odio magnam placeat necessitatibus perferendis, deleniti neque? Porro explicabo optio saepe? Molestiae necessitatibus laboriosam sapiente ad doloribus quis blanditiis recusandae, labore debitis. Assumenda rerum quaerat, dicta perspiciatis sint sed?</p>
                    </li>
                </ul>



            </div>
        </div>
    </section>
    
</template>

<script>
    export default {
        name: 'AppMain'
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
}
.s1-container{
    background-image: url('../assets/img/homepage-hero-background.jpg');
    height: 550px;
   background-size: cover;
   margin-top: -10px;
   
}

.container-h {
    color: white;
    font-size: 35px;
    padding-top: 240px;
    padding-left: 200px;
    
}

.h3-hero {
    font-size: 25px;
    padding-top: 10px;
}

.s2-ul {
    width: 450px;

    row-gap: 20px;
}

</style>