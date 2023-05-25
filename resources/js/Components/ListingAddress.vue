<template>
    <div>
      {{ listing.city }}
    </div>
  </template>
      
  <script setup>
  defineProps({
    listing: Object
  })
  </script>