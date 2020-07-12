<template>
  <div>
    <div class="text-center">

      <i class="fas fa-user-secret fa-3x text-danger"></i><br />
      <router-link class="btn   btn-link" to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

 