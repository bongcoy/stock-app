<template>
  <div class="flex min-h-screen">
    <!-- Sidebar -->
    <div class="w-64 bg-gray-800">
      <div class="px-4 py-6">
        <h2 class="text-2xl font-bold text-white">Application Name</h2>
        <nav class="mt-6">
          <a
            href="#"
            class="block px-4 py-2 mt-2 text-sm font-semibold text-white rounded hover:bg-gray-700"
            >Home</a
          >
          <a
            href="#"
            class="block px-4 py-2 mt-2 text-sm font-semibold text-white rounded hover:bg-gray-700"
            >Product</a
          >
        </nav>
      </div>
    </div>
    <!-- Main Content -->
    <div class="flex-1 p-6 bg-gray-100">
      <div class="flex justify-between items-center mb-6">
        <h1 class="text-2xl font-bold">Product</h1>
        <button
          class="px-4 py-2 text-white bg-blue-500 rounded hover:bg-blue-700"
        >
          + New product
        </button>
      </div>
      <table class="w-full bg-white rounded shadow">
        <thead>
          <tr class="border-b">
            <th class="px-4 py-2 text-left">Title</th>
            <th class="px-4 py-2 text-left">Description</th>
            <th class="px-4 py-2 text-left">Category</th>
            <th class="px-4 py-2 text-left">Price</th>
            <th class="px-4 py-2 text-left">Stock</th>
            <th class="px-4 py-2 text-left">Edit</th>
            <th class="px-4 py-2 text-left">Delete</th>
          </tr>
        </thead>
        <tbody>
          <tr class="border-b">
            <td class="px-4 py-2">Sample Title</td>
            <td class="px-4 py-2">Sample Description</td>
            <td class="px-4 py-2">Category</td>
            <td class="px-4 py-2">$100</td>
            <td class="px-4 py-2">20</td>
            <td class="px-4 py-2">
              <button
                class="px-2 py-1 text-white bg-yellow-500 rounded hover:bg-yellow-700"
              >
                Edit
              </button>
            </td>
            <td class="px-4 py-2">
              <button
                class="px-2 py-1 text-white bg-red-500 rounded hover:bg-red-700"
              >
                Delete
              </button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script lang="ts" setup></script>

<style></style>
