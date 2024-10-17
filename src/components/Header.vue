<script setup>
defineProps({
    brand:String,
    location:String
})

</script>

<template>
    <div class="container">
        <h1>{{ brand }} @ {{ location }}</h1>
    </div>
</template>

<style scoped>
.container{
    display:flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    padding:20px;
    color: white;
}

</style>