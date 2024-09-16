<template>
    <div class="nav">
      <div class="icon"></div>
      <div class="nav-group d-flex">
        <div class="nav-btn dropdown">
          <a href="#" class="nav-text dropdown-toggle" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            文章
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">選項 1</a></li>
            <li><a class="dropdown-item" href="#">選項 2</a></li>
            <li><a class="dropdown-item" href="#">選項 3</a></li>
          </ul>
        </div>
        <div class="nav-btn">
          <RouterLink to="/about" class="nav-text">關於我</RouterLink>
        </div>
        <div class="nav-btn">
          <RouterLink to="/contact" class="nav-text">聯絡方式</RouterLink>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  import { RouterLink } from 'vue-router';
  </script>
  
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
    background: linear-gradient(to right, rgb(29, 29, 173), rgb(14, 126, 217));
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
    text-align: center;
    line-height: 60px;
  }
  
  .nav-text {
    text-decoration: none;
    color: white;
  }
  
  .nav-group {
    width: 40%;
  }
  
  .dropdown-menu {
    background-color: rgb(14, 126, 217);
  }
  </style>
  