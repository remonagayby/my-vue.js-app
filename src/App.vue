<template>
    <div class="container">
        <Header title="My Vue App" action="Get Started" color="lightblue" bgColor="blue"></Header>
    </div>

    <div class="container">
        <Header title="Todo List" action="Add Task"></Header>
    </div>
</template>

<script>
    import Header from './Header.vue'
    export default {
        name: 'App',
        components: {
            Header
        }
    }
</script>

<style>
    #app {
    text-align: center;
    color: chocolate;
    margin-top: 60px;
    }

    .container {
        border: 1px solid steelblue;
        padding: 30px;
        max-width: 500px;
        margin: 20px auto;
    }

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