<template>
<div class="skillsection ">
    <h2>My Skills.</h2>
    <section class="skills">
    <img src="~/public/imgs/code.png"/>
    <article>
    <h3>Design & Development</h3>
    <p>I started learning to code when I was 12 years old because I wanted to make my own video games. Over time, I have gained a wealth of experience designing and developing mobile and web applications.</p>
    </article>
    </section>
    <section class="hwc">
    <article>
    <h3 class="hwc">Swimming & Sports</h3>
    <p>But my best skill is actually in swimming. I am the undisputed king of swimming challenges. In any place and any circumstances, I like to take risks</p>
    </article>
    <img src="~/public/imgs/swim.png"/>
    </section>
    <div class="dots">
    <span class="dot"></span>
    <span class="dot"></span>
    <span class="dot"></span>
    <span class="dot"></span>
    <span class="dot"></span>
</div>
</div>
</template>
<style scoped>
    section{
        font-family:Georgia, 'Times New Roman', Times, serif;
        display: flex;
        justify-content: center;
        margin-bottom: 5%;
    }
   
    article{
        width: 400px;
        max-width: calc(100% - 100px);
    }
    img{
        margin-right: 2%;
        margin-left: 2%;
        max-width: 150px;
        max-height: 150px;
    }
    h2{
    font-size: 40px;
    color:white;
    text-align: center;
    }
    h3{
       color: #95c9be;
    }
    P{
    color: #40514E;
    font-weight: bold;
    line-height: 23px;
   
    }
    .dots{
        text-align: center;
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
