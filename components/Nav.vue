<template>
  <nav
    class="navbar navbar-expand-lg bg-dark border-bottom border-body"
    data-bs-theme="dark"
  >
    <div class="container-fluid">
      <NuxtLink class="navbar-brand" to="/">Restaurantly</NuxtLink>

      <div class="collapse navbar-collapse" id="navbarScroll">
        <ul
          class="navbar-nav ms-auto my-2 my-lg-0 navbar-nav-scroll"
          style="--bs-scroll-height: 100px"
        >
          <li class="nav-item">
            <NuxtLink
              to="/"
              class="nav-link"
              activeClass="active"
              aria-current="page"
              >Home</NuxtLink
            >
          </li>
          <li class="nav-item">
            <NuxtLink to="/restaurants" class="nav-link" activeClass="active"
              >Restaurants</NuxtLink
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script></script>

<style></style>
