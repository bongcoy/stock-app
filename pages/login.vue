<template>
  <div class="flex items-center justify-center min-h-screen bg-gray-100">
    <div class="p-6 bg-white rounded shadow-md w-80">
      <div class="flex justify-center mb-6">
        <div class="w-12 h-12 bg-gray-300"></div>
      </div>
      <h1 class="mb-4 text-2xl font-bold text-center">Application Name</h1>
      <form>
        <div class="mb-4">
          <label class="block mb-2 text-sm font-bold" for="username"
            >Username</label
          >
          <input
            class="w-full px-3 py-2 border rounded"
            id="username"
            type="text"
          />
        </div>
        <div class="mb-6">
          <label class="block mb-2 text-sm font-bold" for="password"
            >Password</label
          >
          <input
            class="w-full px-3 py-2 border rounded"
            id="password"
            type="password"
          />
        </div>
        <button
          class="w-full px-4 py-2 text-white bg-blue-500 rounded hover:bg-blue-700"
          type="submit"
        >
          Login
        </button>
      </form>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style></style>
