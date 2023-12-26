<template>
    <header>
        <h1 :style="{ color: color}"> {{ title }} </h1>
        <button @click="handleClick()" :style="{ backgroundColor: bgColor}"> {{ action }} </button>
    </header>
</template>

<script>
    export default {
        name: 'Header',
        props: {
            title: String,
            action: String,
            color: String,
            bgColor: String
        },
        methods: {
            handleClick() {
                console.log("button clicked")
            }
        }
    }
</script>

<style>
    button {
        padding: 10px 20px;
        font-size: 15px;
        background-color: brown;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }
</style>