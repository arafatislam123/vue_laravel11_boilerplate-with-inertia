


<template>
<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <Link class="nav-link active" aria-current="page" href="/">Home</Link>
                <Link class="nav-link active" aria-current="page" href="/profile">profile</Link>
        <a class="nav-link" href="#">Profile</a>

      </div>
    </div>
  </div>
</nav>
</template>
<script setup>
import { Link } from '@inertiajs/vue3'
</script>


