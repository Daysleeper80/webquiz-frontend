<script setup>
defineProps({
  pageTitle: {
    type: String,
    required: true,
  },
});

</script>


<template>
    <div class="navigation">
        <h1 class="title">{{ pageTitle }}</h1>
        <button class="login" type="button">LOGIN</button>
    </div>
</template>

<style>

.navigation{
    background-color: rgb(163, 56, 56);
    width: 1000px;
    padding: 10px;
    color: white;
    border-radius: 5px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.login{
    background-color: rgb(38, 124, 38);
    border-radius: 5px;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
.login:hover{
    background-color: greenyellow;
    color: black;
}

</style>