<template>
    <div>
        <h1>About</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas saepe voluptates repudiandae error sint culpa doloribus eveniet. Beatae cum, non sint aliquid, eius consectetur quas harum ab perspiciatis, unde excepturi.</p>
        {{ data }}
    </div>
    
</template>

<script setup>
const {data} = await useFetch('/api/currency/GBP')

</script>

<style scoped>

h1{
    margin-bottom: 40px;
    font-size: 36px;
}

p{
    margin:20px 0px;
}
</style>