<template>
    <div class="projetos">
        <hi class="title">Projetos</hi>
        <RouterView></RouterView>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'Projetos'
})
</script>

<style scoped>
.projetos {
    padding: 1.25rem;
}
</style>