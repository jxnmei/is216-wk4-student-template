<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array 
    const message = ref("Choose your favourite fruit : ")
    const fruits = ref(["apple", "orange","peach"])

    const fruit1 = fruits.value[0]
    const fruit2 = fruits.value[1]
    const fruit3 = fruits.value[2]
    
</script>

<template>
    {{ message }} 
   
    <label for=""> <input type="radio" name="fruit"> {{ fruit1 }} </label> 
    <label for=""> <input type="radio" name="fruit"> {{ fruit2 }} </label> 
    <label for=""><input type="radio" name="fruit"> {{ fruit3 }} </label> 
    
</template>

<style scoped>
</style>
