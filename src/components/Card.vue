<script setup>
const {img, title, text} = defineProps(['img', 'title', 'text']);
</script>

<template>
    <div>
        <div class="card mb-3">
            <img :src="img" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">{{ title }}</h5>
                <p class="card-text">{{ text }}</p>
                <a href="#" class="btn btn-primary">Go somewhere</a>
            </div>
        </div>
    </div>
</template>

<style scoped>

</style>