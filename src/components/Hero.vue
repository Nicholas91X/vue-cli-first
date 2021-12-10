<template>
    <div id="hero">
        <div id="prev">&larr;</div>
        <div id="next">&rarr;</div>
        <div class="title">Rocky shore with rocks on water under blue sky during sunset</div>
    </div>
</template>

<script>
    export default {
        name: "Hero"
    }
</script>

<style scoped>
    #hero {
        margin-top: 25px;
        height: 452px;
        background-image: url(https://images.unsplash.com/photo-1589656145650-1077299da3e6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=876&q=80);
        background-repeat: no-repeat;
        background-size: cover;
        background-position-y: 20%;
        display: flex;
        justify-content: flex-start;
        align-items: flex-end;
        position: relative;
    }
    .title {
        width: 200px;
        padding: 10px;
        margin: 15px;
        color: white;
        text-align: left;
        font-size: 18px;
        font-weight: 700;
    }
    #prev,
    #next {
        width: 25px;
        height: 25px;
        background-color: white;
        border-radius: 50%;
        position: absolute;
        top: 50%;
        margin: 0 20px;
        transform: translateY(-50%);
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 22px;
        font-weight: bold;
    }
    #next {
        right: 0;
    }
</style>
