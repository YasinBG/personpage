<template>
  <div class=" w-4/7 text-center mx-auto my-4 px-2">
    
    <h3 class="font-semibold text-2xl text-gray-800 text-center mx-auto ">
        <slot name="title"></slot>
    </h3>
    <p class="text-center text-gray-600 mx-auto w-3/5">
        <slot name="content"></slot>
    </p>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>