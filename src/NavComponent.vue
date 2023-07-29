<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
      <img src="../public/image/logo.png" height="65" width="65">
     <b> <h2 class="me-aut text-white" style="margin-left:-590%; margin-bottom: 10%;">Porthub</h2></b>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>Home</NavbarLink>
          <NavbarLink>Tentang</NavbarLink>
          <NavbarLink>Contoh Projek</NavbarLink>
          <NavbarLink>Media Sosial</NavbarLink>
        </NavbarCollapse>
      </template>
      <template #menu-icon>
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path></svg>
      </template>
    </Navbar>
</template>
