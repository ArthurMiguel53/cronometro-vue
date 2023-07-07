<template>
    <button>{{ texto }}</button>
</template>

<script lang="ts">
    import { defineComponent, PropType } from 'vue';

    export default defineComponent({
        name: 'botao',
        props: {
            texto: {
                type: String as PropType<string>,
                required: true
            }

        }
    });
</script>

<style scoped>
    button{
        border-radius: 10px;
        height: 50px;
        width: 100px;
    }
</style>