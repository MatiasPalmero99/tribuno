<template lang="">
    <div>
        <!-- NAVBAR SECTION -->
        <nav id="navbar-1" class="navbar navbar-expand-lg fixed-top bg-body-tertiary rounded text-uppercase mb-5 fw-bold" aria-label="Eleventh navbar example" data-aos="fade-down">
            <div class="container">
            <router-link to="/" class="navbar-brand fs-4">
                <!-- <img src="./img/content/logo.svg" class="img-fluid " alt="" width="50px"> -->
                <span class="text-second">Mati</span><span class="text-prim">DEV</span>
            </router-link>
            <!-- <a class="navbar-brand text-prim fs-4" href="#">&#60; <span class="font-code font-monospace">MatiDEV</span> &#47;&#62;</a> -->
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            
            <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                <router-link to="/" class="nav-link px-lg-4 rounded">INICIO</router-link>
                <router-link to="/about" class="nav-link px-lg-4 rounded">ABOUT</router-link>
                <router-link to="/posts" class="nav-link px-lg-4 rounded">POSTS</router-link>
                </div>
            </div>
            </div>
        </nav>
        <!-- END NAVBAR SECTION -->
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>