<template>
    <div class="contact">
        <h2>Get In Touch</h2>
        <h3>If you love hot wings as much as I do.</h3>
        <p>Love hot wings as much as I do? Let's talk about how awesome they are! We can code while we eat hot wings!</p>
        <a href="https://www.freecodecamp.org/">
            <button>CONTACT ME</button>
        </a> 
        
    </div>
</template>
<style scoped>
    .contact{
        text-align: center;
        align-items: center;
        display: flex;
        flex-direction: column;
        font-family:Georgia, 'Times New Roman', Times, serif;
    }
    h2{
    font-size: 40px;
    color:white;
    }
    h3{
    color: #95c9be;
    }
    p{
        font-weight: 600;
        color: #40514E;
        width: 680px;
        max-width: calc(100% - 10px);
    }
    a,
    button{
        cursor: pointer;
        margin-top: 3%;
        margin-bottom: 5%;
        color: black;
        font-size: 20px;
        font-weight: 100;
        border: none;
        border-radius: 8px;
        width: 170px;
        height: 40px;
        background-color:white ;
    }
</style>
