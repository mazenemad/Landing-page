<template>
    <div class="Header ">
    <img class="cloud1" src="~/public/imgs/cloud3.png" />
    <h1 >I'm Mazen</h1>
    <h2>a <span>pro</span>grammer</h2>
    <img class="cloud2" src="~/public/imgs/cloud3.png" />
    </div>
    </template>
    <style scoped>
    .Header{
        background-image: url(~/public/imgs/back-ground.jpg);
        background-repeat: no-repeat;
        background-size: 100% 150%;
        background-position: 20%;
        text-align: center;
    }
    h1{
        margin-top: 5%;
        font-size: 60px;
        font-family: 'Pacifico', cursive;
    }
    h2{
        font-size: 40px;
        font-family: 'Pacifico', cursive;
    }
    span{
        text-decoration: underline;
    }
    .cloud1,
    .cloud2{
        margin-left: 50%;
        max-width: 150px;
        max-height: 150px;
    }
    .cloud2{
        margin-left: 0;
        margin-right: 50%;
    }
    .mountain{
    display: block;
    margin-left: auto;
    margin-right: auto;
    }
    
    </style>
