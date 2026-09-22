<script setup>
import { RouterView } from 'vue-router';
import AppNavbar from './AppNavbar.vue';
import AppSidebar from './AppSidebar.vue';
</script>

<template>
    <AppNavbar/>
    <div class="container-fluid">
        <div class="row">
            <asside class="col-md-3">
              <i class="fa-solid fa-circle"></i>
            </asside>
        </div>
    </div>
</template>