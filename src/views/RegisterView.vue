<template>
  <div id="Register">
    <TopNavigation />
    <div class="w-full p-6 flex justify-center items-center">
      <div class="w-full max-w-xs">
        <div class="bg-black p-8 shadow rounded mb-6">
          <h1 class="mb-6 text-lg text-gray-100 font-thin">Let's get rocking!</h1>

          <div class="mb-4">
            <TextInput
                label="Email"
                :labelColor="false"
                placeholder="john.doe@m.com"
                inputType="text"
            />
          </div>

          <div class="mb-4">
            <TextInput
                label="Password"
                :labelColor="false"
                placeholder="password123?"
                inputType="password"
            />
          </div>

          <button
              class="
                            block
                            w-full
                            bg-green-500
                            text-white
                            rounded-sm
                            py-3
                            text-sm
                            tracking-wide
                        "
              type="submit"
              @click="login"
          >
            Login
          </button>

        </div>

        <p class="text-center text-md text-gray-900">
          Don't have an account yet?
          <router-link to="login" class="text-blue-500 no-underline hover:underline">
            Register
          </router-link>
        </p>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>

</style>