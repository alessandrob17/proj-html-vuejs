<template>
    <!-- SECTION1 -->
    <section>
        <div class="bg-footer d-flex justify-content-center">
            <div class="d-flex container-footer pt-5 mt-4 ">
                <div>
                    <figure>
                        <img src="../assets/img/avada-drivers-logo-2x-200x39.png" alt="">
                    </figure>
                    <p class="text-white">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. <br> Doloremque ipsum aperiam ad
                        voluptatem dolores <br> perferendis aliquid sit non numquam omnis, quia <br> expedita repudiandae
                        modi quidem quasi soluta ab fuga nesciunt.
                    </p>
                </div>

                <div class="ms-3 text-white">
                    <h5>
                        CONTACT DETAILS
                    </h5>
                    <div>
                        <i class="fa-solid fa-house me-2 mt-2"></i>
                        <span>12345 North Main Street.</span>
                    </div>
                    <div>
                        <i class="fa-solid fa-phone me-2 mt-2"></i>
                        <span>1-800-555-555</span>
                    </div>
                    <div>
                        <i class="fa-solid fa-envelope me-2 mt-2"></i>
                        <span>info@gmail.com</span>
                    </div>
                    <div>
                        <i class="fa-solid fa-link me-2 mt-2"></i>
                        <span>Theme-Fusion.com</span>
                    </div>
                </div>

                <div class="ms-3 ">
                    <h5 class="text-white">
                        COURSES
                    </h5>
                    <div class="text-success">

                        <div>
                            <i class="fa-regular fa-circle-right me-2"></i>
                            <span>Pass Plus</span>
                        </div>
                        <div>
                            <i class="fa-regular fa-circle-right me-2"></i>
                            <span>Intensive Course</span>
                        </div>
                        <div>
                            <i class="fa-regular fa-circle-right me-2"></i>
                            <span>Automatic</span>
                        </div>
                        <div>
                            <i class="fa-regular fa-circle-right me-2"></i>
                            <span>Instructor Training</span>
                        </div>
                    </div>
                </div>

                <div class="ms-4">
                    <figure>
                        <img src="../assets/img/footer-ad-grid-200x178.png" alt="">
                        <a href="#" class="btn btn-success px-4 ms-4 mt-2">BOOK NOW!</a>
                    </figure>
                </div>




            </div>

        </div>
    </section>

    <!-- SECTION2 -->
    <section>
         <div class="bg-section2-footer">
            <div class="d-flex justify-content-center justify-content-around pt-5 pb-4">

                <div class="text-light">
                    <p>Lorem ipsum dolor sit amet, <span class="text-success">consectetur</span> adipisicing elit. Provident <span class="text-success">maxime</span>  porro a!</p>
                </div>

                <div class="text-white">
                    <i class="fa-brands fa-facebook pe-4"></i>
                    <i class="fa-brands fa-twitter pe-4"></i>
                    <i class="fa-brands fa-youtube pe-4"></i>
                    <i class="fa-brands fa-instagram pe-4"></i>

                </div>



            </div>
         </div>
    </section>
</template>

<script>
export default {
    name: 'AppFooter'
}
</script>

<style lang="scss" scoped>
.bg-footer {
    background-image: url('../assets/img/footer-background-color.jpg');
    height: 350px;
    background-size: cover;
}

.container-footer {
    width: 1200px;
}

.bg-section2-footer{
    background-color: #1C1D1E;
}
</style>