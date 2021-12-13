<template>
    <section class="main">
        <div class="left">
            <div>
            <img src="../assets/manonphone.jpg" alt="">
            </div>
        </div>
        <div class="right">
            <h3 class='chance'>You have <span class="zero">zero</span> chances of not being replied. </h3>
            <div class="send">Sending a DM should no more be an issue of shooting your shot or trying your luck. You’re paying, so you’re definitely going to get a response, and not just a response, but a conversation.</div>
        </div>
    </section>
</template>


<style scoped>
.main{
    display: flex;
    padding: 120px 100px 0 100px;
    gap: 100px;
}
.chance{
    font-size: 40pt;
    margin-top: 80px;
}
.send{
    font-size: 18px;
    line-height: 185.6%;
    letter-spacing: -0.03em;
    color: #8E8E95;
    width: 72%;
    margin-top: 26px;
}
.zero{
    color: green;
    font-style: italic;
}
@media screen and (max-width: 745px){
    .main{
        flex-wrap: wrap-reverse;
        padding: 50px 20px 0 20px;
        gap: 50px;
    }
    .chance{
        font-size: 25px;
        text-align: center;
        margin: auto;
        width: 80%;
    }
    .send{
        width: 100%;
        font-size: 16px;
        text-align: center;
    }
    .left{
        width: 100%;
        display: flex;
        justify-content: center;
    }
    .left div{
        width: 280px;
        height: 295px;
        
    }
    .left div img{
        width: 100%;
        height: 100%;
    }
}
</style>