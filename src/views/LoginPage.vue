<template>

   <form class="" @submit.prevent>
    <div>
        <label for ="Username" class="">Username</label>
        <input id="username" v-model="username" type ="text" placeholder="Username">
     </div>
        <div>
        <label for="password" class="">Password</label>
        <input id="password" v-model="password" type="password" placeholder="Password">
    </div>

    <button @click="logUserIn" class=""></button>
   </form>
</template>

<script setup>
</script>