<script>
import { RouterLink } from 'vue-router';

export default {
    methods: {

    },
};
</script>

<template>
    <!-- <div class="foot-container w-100">
        <div class="icon"></div>
        <div class="nav-group">
            <a href="" class="footer-btn">文章</a>
            <a href="" class="footer-btn">關於我</a>
            <a href="" class="footer-btn">聯絡方式</a>
        </div>
    </div> -->
    <footer class="py-5 px-4 my-footer">
        <div class="row">
            <div class="col-12 col-md">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" stroke="currentColor"
                    stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="d-block mb-2" role="img"
                    viewBox="0 0 24 24">
                    <title>Product</title>
                    <circle cx="12" cy="12" r="10"></circle>
                    <path
                        d="M14.31 8l5.74 9.94M9.69 8h11.48M7.38 12l5.74-9.94M9.69 16L3.95 6.06M14.31 16H2.83m13.79-4l-5.74 9.94">
                    </path>
                </svg>
                <small class="d-block mb-3 text-body-secondary">© 2017–2024</small>
            </div>
            <div class="col-6 col-md">
                <h5>Features</h5>
                <ul class="list-unstyled text-small">
                    <li><a class="link-secondary text-decoration-none" href="#">Cool stuff</a></li>
                    <!-- <li><a class="link-secondary text-decoration-none" href="#">Random feature</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Team feature</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Stuff for developers</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Another one</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Last time</a></li> -->
                </ul>
            </div>
            <div class="col-6 col-md">
                <h5>文章</h5>
                <ul class="list-unstyled text-small">
                    <li>
                        <router-link class="link-secondary text-decoration-none" to="/vue-basic">Vue基礎</router-link></li>
                </ul>
            </div>
            <div class="col-6 col-md">
                <h5>關於我</h5>
                <ul class="list-unstyled text-small">
                    <li><a class="link-secondary text-decoration-none" href="#">Business</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Education</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Government</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Gaming</a></li>
                </ul>
            </div>
            <div class="col-6 col-md">
                <h5>聯絡方式</h5>
                <ul class="list-unstyled text-small">
                    <li><a class="link-secondary text-decoration-none" href="#">Team</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Locations</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Privacy</a></li>
                    <li><a class="link-secondary text-decoration-none" href="#">Terms</a></li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<style scoped>

body {
    margin: 0;
    box-sizing: border-box;
}

::before,
::after {
    box-sizing: border-box;
}

.my-footer{
    background-color: rgb(232, 239, 246);
}


</style>
