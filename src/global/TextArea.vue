<template>
  <label
      class="
            block
            uppercase
            tracking-wide
            text-gray-900
            text-xs
            font-bold
            mb-2
        "
  >

  </label>
  <textarea
      class="
            appearance-none
            block
            w-full
            bg-white
            text-gray-700
            border
            border-gray-400
            rounded
            py-3
            px-4
            leading-tight
            focus:outline-none
            focus:bg-white
            focus:border-gray-500
        "
      v-model="descriptionComputed"
      :placeholder="placeholder"
      cols="30"
      rows="10"
  >
    </textarea>
  <span class="text-red-500">

    </span>
</template>


<style scoped>

</style>