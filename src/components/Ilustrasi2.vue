<!-- filepath: d:\Image_Compressor\src\components\Ilustrasi.vue -->
<template>
  <img
    src="@/assets/abstract2.png"
    alt="Abstract"
    class="abstract-img"
    data-aos="slide-left"
    data-aos-duration="1000"
    data-aos-delay="10"
  />
</template>

<script setup></script>

<style scoped>
.abstract-img {
  position: absolute;
  right: 3px;
  top: 10px;
  width: 650px;
  height: auto;
  z-index: 1;
  pointer-events: none;
  overflow: hidden;
  user-select: none;
}
</style>
