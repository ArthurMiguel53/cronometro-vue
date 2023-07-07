<template>
 
  <nav><!--menu de navegação--></nav>
  <aside><!--conteudo secundário ou lateral--></aside>
  <main>
    bah meu
    <!--conteudo principal-->
    <!--3. utilizar o componente-->
    <contador/>
    <contador/>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
// import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

//1 importar o componente

import contador from '@/components/contador.vue';

export default defineComponent({
  name: 'MainView',
  // 2. listar os componentes que vão ser utilizados
  components: {
    contador
  }
});



</script>

<style scoped>

</style>