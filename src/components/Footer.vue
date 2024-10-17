<script setup>
    defineProps({
        brand:String,
        location:{
            type:String,
            default:"Worldwide"}
    })
</script>

<template>
    <div class="container"><p>{{ brand }} @ {{ location }}</p>
        </div>

</template>

<style scoped>
.container{
    display:flex;
    justify-content: center;
    align-items: center;
    background-color: #333;
    padding:20px;
    color: white;
}
</style>