<script setup>
const props = defineProps({
  classIn: String,
  classOut: String,
  type: String,
});
// export const H800p3 = base(Contain,
const sds = {
  classOut: "min-h-[800px]",
  pad: "",
  classIn: "  ",
};

// const makeComp = () => {
//   return `(
//     <div>
//       <h1>Hello world</h1>
//       <div>{{ this.msg }}</div>
//     </div>
//   )`
// };
// }
// const HelloWorld = Vue.component("hello-world", {
//   props: ["msg"],
//   template: `<div>
//     <h1>Hello world</h1>
//     <div>{{ this.msg }}</div>
//   </div>`,
// });
// export const H0p3 = base(Contain, {
// classOut: "", pad: "px-2 md:px-[%]", classIn: " flex ", });
// export const
// Brilliant = base(Contain, { classOut: "", pad: "px-2 sm:px-[15%] md:px-[20%]
// lg:px-[22%] xl:px-[24%]", classIn: " flex flex-wrap ", });
// export const ContainX
// = { H800p3, H0p3, Brilliant, }
// export default {
//   components: {
//     HelloWorld,
//   },
// };
</script>

<template>
  <main
    :class="`flex justify-center min-h-[800px] px-2 md:px-[3%] ${
      classOut ?? ' '
    }`"
  >
    <div :class="'container xl:max-w-[1124] '">
      <div :class="classIn ?? 'flex flex-col bg-gray-900 text-white p-4'">
        <slot />{{ classOut }}
      </div>
    </div>
  </main>
</template>

<!-- variations: minheight, padding, flex-wrap -->
<!-- container cannot be  -->
<!-- pad: add room for the container, not content inside  -->
<!-- classIn: inner classes -->

<style></style>
