<script>
import { RouterLink } from 'vue-router';

export default {
    methods: {

    },
};
</script>

<template>
    <div class="nav">
        <div class="icon"></div>
        <div class="nav-group d-flex">
            <div class="nav-btn">
                <a href="" class="nav-text">文章</a>
            </div>
            <div class="nav-btn">
                <a href="" class="nav-text">關於我</a>
            </div>
            <div class="nav-btn">
                <a href="" class="nav-text">聯絡方式</a>
            </div>
        </div>
    </div>
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

.nav {
    width: 100%;
    height: 80px;
    /* background-color: rgb(14, 126, 217); */
    background: linear-gradient(to right,rgb(29, 29, 173),rgb(14, 126, 217));
    padding: 10px;
    display: flex;
    justify-content: space-between;
    position: fixed;

}

.icon {
    width: 100px;
    height: 100%;
    background-color: rgb(58, 196, 58);
}

.nav-btn {
    font-size: 20px;
    width: 33%;
    /* padding: 30px; */
    text-align: center;
    
    line-height: 60px;
    
}

.nav-text{
    text-decoration: none;
    color: white;
}

.nav-group{
    width: 40%;
}


</style>
