<template>
    <nav class="navbar navbar-expand-md navbar-light bg-dark">
    <div class="container">
    <a class="navbar-brand text-light" href="#">Portofolio Website</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
    aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav me-auto mb-2 mb-lg-0 ">
    <li class="nav-item">
    <a class="nav-link active text-light" aria-current="page" href="#"><router-link to="/">Home</router-link></a>
    </li>
    <li class="nav-item">
    <a class="nav-link active text-light" aria-current="page" href="#"><router-link to="About">About</router-link></a>
    </li>
    <li class="nav-item">
    <a class="nav-link active text-light" aria-current="page" href="#"><router-link to="Contact">Contact</router-link></a>
    </li>
    </ul>
    </div>
    </div>
    </nav>
    </template>
    <style scoped>
    a{
        text-decoration: none;
        color: white;
    }
    a:hover{
        color: red;
    }
</style>