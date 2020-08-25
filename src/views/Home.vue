<template>
    <div class="home">
        <img alt="Vue logo"
             class="mx-auto mb-4"
             src="../assets/logo.png"
        >
        <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
    name       : 'Home',
    components : {
        HelloWorld
    }
}
</script>
