<script lang="ts">
export default {
  data(){
    return {
      showNav: true
    }
  },
  methods:{
    updateShowNav(){
      this.showNav = !this.showNav
      console.log(this.showNav)
    }
  }
}
</script>

<template>
  <nav class="flex flex-col sm:flex-row justify-between px-2 py-4 my-2">
    <div class="flex justify-between flex-row mx-4 my-4">
      <a href="" class="font-bold">Name</a>
      <button class="sm:hidden" @click="updateShowNav()">
        <i class="fa-solid fa-bars"></i>
      </button>
    </div>

    <ul class="flex flex-col sm:flex-row" v-if="showNav">
      <li class="mx-4 my-2"><button class="font-bold">Connect Wallet</button></li>
      <li class="mx-4 my-2"><button class="font-bold">Telegram</button></li>
      <li class="mx-4 my-2"><button class="font-bold">Discord</button></li>
    </ul>
  </nav>
</template>