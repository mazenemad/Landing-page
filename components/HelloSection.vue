<template>
    <div class="HelloSection ">
        <img class="angelaphoto" src="~/public/imgs/me-min.png" width="200" height="200" />
        <h2>Hello.</h2>
        <p>I am an iOS and Web Developer. I'm the founder and CTO of The App ascialpus. I ❤️ coffee and brew my own tea.</p>
        <span class="dot"></span>
        <span class="dot"></span>
        <span class="dot"></span>
        <span class="dot"></span>
        <span class="dot"></span>
    </div>
    </template>
    <style scoped>
    .HelloSection{
        margin: 0;
        margin-top: 5%;
        text-align: center;
        justify-content: center;
        max-width: calc(100%-100px);

    }
    .angelaphoto{
    display: block;
    margin-left: auto;
    margin-right: auto;
    }
    h2{
    font-size: 40px;
    color:white;
    font-family:Georgia, 'Times New Roman', Times, serif;
    }
    p{
    color: #40514E;
    font-weight: bold;
    }
    .dot {
    color:#EAF6F6;
    margin-top: 5%;
    margin-bottom: 5%;
    height: 6px;
    width: 6px;
    background-color: #bbb;
    border-radius: 50%;
    display: inline-block;
    margin-left: 8px;
}
    </style>
