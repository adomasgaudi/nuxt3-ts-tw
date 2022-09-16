<script setup lang="ts">
const { t } = useI18n()

// const toggleLocales = () => {
//   // change to some real logic
//   const locales = availableLocales
//   locale.value = locales[(locales.indexOf(locale.value) + 1) % locales.length]
// }
</script>

<template>
  <div>
    {{ t('oh-hi-mark') }}
  </div>
</template>
