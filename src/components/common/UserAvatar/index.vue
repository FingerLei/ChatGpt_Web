<script setup lang='ts'>
import { GithubSite } from '@/components/custom'
</script>

<template>
  <div class="flex items-center">
    <div class="w-10 h-10 overflow-hidden rounded-full">
      <img class="object-cover" src="@/assets/acg.jpg" alt="avatar">
      <!--avatar.jpg-->
    </div>
    <div class="ml-2">
      <h2 class="font-bold text-md">
        FingerLei
      </h2>
      <p class="text-xs text-gray-500">
        <GithubSite />
      </p>
    </div>
  </div>
</template>
