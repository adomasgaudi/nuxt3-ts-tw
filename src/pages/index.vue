<script setup lang="ts">
const { t } = useI18n()

// const toggleLocales = () => {
//   // change to some real logic
//   const locales = availableLocales
//   locale.value = locales[(locales.indexOf(locale.value) + 1) % locales.length]
// }

const gogo = {
    classOut: "px-[30%]",
    classIn: "flex p-10",
  };
</script>

<template>
    <Contain :="gogo">
        <h1 class="text-6xl">  {{ t('oh-hi-mark') }}</h1>
        <p class="text-sm">
          oh hi Lorem ipsum dolor sit, amet consectetur adi optio consectetur
          iusto error vero nostrum distinctio aliquid rem nemo incidunt
          perspiciatis quaerat quod harum tempore similique explicabo doloremque
          animi aut sit, aperiam dolore. Quis, optio odit et tenetur veniam earum,
          voluptate eius fugit sunt, commodi aliquam rerum? Ullam molestias harum
          amet. Nulla fugiat corrupti cupiditate eum molestiae adipisci ex quae.
          Quas, ratione. Commodi repellendus dicta placeat reiciendis fugit quis
          quod nihil earum qui officipariatur sint odio iste tenetur doloremque
          voluptatem neque vitae at porro. Dolorem culpa odio ut, doloremque
          commodi et ducimus quas impedit itaque ipsam delectus quibusdam.
          Voluptatibus, molestiae ratione minus autem deserunt ut ullam et aut
          sint porro impedit labore.
        </p>
        <Button>hihih</Button>
        <NuxtLink to="examples/landing"> Nuxt website++ </NuxtLink>
      </Contain>
</template>
