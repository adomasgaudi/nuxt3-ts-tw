<script></script>

<template>
  <main :class="`flex justify-center ${classOut ?? ' '}`">
    <div :class="'container xl:w-[1124]'">
      <div :class="pad ?? ' '">
        <div :class="classIn ?? ' '"><slot /></div>
      </div>
    </div>
  </main>
</template>
<style></style>
