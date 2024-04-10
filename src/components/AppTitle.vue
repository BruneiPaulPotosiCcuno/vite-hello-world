<script>

    export default {
        name: 'AppTitle'
    }
</script>

<template>
    <div class="box">
        <h1>La mia prima app con Vite!</h1>
    </div>
        

</template>

<style>
    h1{
        color: aqua;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        display: flex;
        justify-content: center;
        font-size: 60px;
        background-color: #f3ec78;
        background-image: linear-gradient(45deg, #f3ec78, #af4261);
        background-size: 100%;
        -webkit-background-clip: text;
        -moz-background-clip: text;
        -webkit-text-fill-color: transparent; 
        -moz-text-fill-color: transparent;
        margin-top: 200px;
        
    }
    
    .box{
        background-image: url("https://t3.ftcdn.net/jpg/06/46/43/08/240_F_646430823_6jX5e6MTJgsYUw4sBKp8fkiuXyvVfc77.jpg");
        background-repeat: repeat;
        height: 200px;
        
    }
</style>