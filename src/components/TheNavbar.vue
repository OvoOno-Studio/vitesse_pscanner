<script setup lang="ts">
/* global useI18n */
/* eslint no-undef: "error" */
const { t } = useI18n()
//  const menuOpen: Ref<boolean> = ref(false);
//  Scroll to section function
//   const scrollToSection = (sectionId: string) => {
//     const element = document.getElementById(sectionId);
//     if (element) {
//       element.scrollIntoView({
//         behavior: 'smooth',
//         block: 'start',
//       });
//     }
//   };
</script>

<template>
  <nav mx-auto items-center px-6 py-1 text-xl container md:flex md:items-center md:justify-between>
    <div flex items-center justify-between>
      <RouterLink flex gap-1 text-xl font-bold md:text-2xl to="/" :title="t('button.home')">
        <!-- <img class="logo" :src="logo" w-15 sm:w-20 alt="HaHa Hyenas Logo" /> -->
        Logo
      </RouterLink>
    </div>
  </nav>
</template>
