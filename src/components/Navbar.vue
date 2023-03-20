<script>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
        <nav class="navbar navbar-expand-lg bg-light p-0">
                <div class="container-fluid">
                        <a class="navbar-brand" href="#"><img alt="Arbracats logo" class="logo" src="@/assets/logo2.png"
                                        width="100" /></a>
                        <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                                aria-expanded="false" aria-label="Toggle navigation">
                                <span class="navbar-toggler-icon"></span>
                        </button>
                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                                        <li class="nav-item">
                                                        <RouterLink class="nav-link text-dark fw-bold pt-4" to="/">Home</RouterLink>
                                        </li>
                                        <li class="nav-item">
                                                        <RouterLink class="nav-link text-dark fw-bold pt-4" to="/about">About</RouterLink>
                                        </li>
                                        <li class="nav-item">
                                                        <RouterLink class="nav-link text-dark fw-bold pt-4" to="/products">Products</RouterLink>
                                        </li>
                                </ul>
                                <form class="d-flex" role="search">
                                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                                        <button class="btn btn-outline-success" type="submit">Search</button>
                                </form>
                        </div>
                </div>
</nav></template>