<script setup>
import { containerMaxW } from '@/config.js'
import BaseLevel from '@/components/BaseLevel.vue'

const year = new Date().getFullYear()
</script>

<template>
  <footer class="py-2 px-6" :class="containerMaxW">
    <BaseLevel>
      <div class="text-center md:text-left">
        <b>&copy;{{ year }}, <a href="https://med-tu.org/techno" target="_blank">Education Technology at Faculty
            of Medicine, Thammasat
            University</a>.</b>
      </div>
      <div class="md:py-2">
        <a href="https://sanookdev.github.io/profile" target="_blank">
          Developed by Mr.Warat Supaporn
        </a>
      </div>
    </BaseLevel>
  </footer>
</template>
