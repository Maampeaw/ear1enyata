<template>
    <section class="belowhero">
        <div class="left">
        <h5 class='get-in-touch'>Get in touch with those that <span class="inspire">inspire</span>  you.</h5>
        <div class="ear">ear1 provides a more efficient and faster way for you to reach out to those who inspires you, either in your career, or any other field of interest, and build great relationships with them.</div>
        </div>

        <div class="right">
            <div class='pocket'>
            <img src="../assets/pocketman.png" alt="" class="pockettedman">
            </div>
        </div>

    </section>
</template>


<style scoped>
.belowhero{
    display: flex;
    padding: 150px 100px 0 100px;
    justify-content: space-evenly;
}
.get-in-touch{
    font-size: 40pt;
    margin-top: 80px;
}
.inspire{
    color: green;
    font-style: italic;
}
.ear{
    font-size: 18px;
    line-height: 185.6%;
    letter-spacing: -0.03em;
    color: #8E8E95;
    width: 64%;
    margin-top: 26px;
}
@media screen and (max-width: 745px){
.belowhero{
    flex-wrap: wrap;
    padding: 50px 20px 0 20px;
}
.get-in-touch{
    width: 80%;
    font-size: 25px;
    text-align: center;
    margin: auto;
}
.ear{
    width: 100%;
    font-size: 16px;
}
.right{
    text-align: center;
}
.right div{
    width: 280px;
    height: 275px;
    margin-top: 30px;
}
.right div img{
    width: 100%;
    height: 100%;
}
}
</style>