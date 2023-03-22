<template>
<<<<<<< HEAD
  <hello-world />
</template>

<script lang="ts">
=======
  <HelloWorld />
</template>

<script>
>>>>>>> correccion inicio
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
  },
});
</script>
