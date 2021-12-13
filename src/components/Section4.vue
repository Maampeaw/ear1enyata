<template>
    <section class="main">
        <h3 class='better-way'>There’s no <span>better</span> way of reaching out to those who inspires you</h3>
        <div class="ear1"><p class='text'>Ear1 lets influencers charge you a small fee to have a conversation with them. Being required to pay filters out all the unserious people so your favourite influencers can respond to you faster.</p></div>
        <div class="happyman"><img src="../assets/happyman.jpg" alt="" class="happy"></div>
    </section>
</template>


<style scoped>

.main{
    padding: 120px 0 0 0;
}
.better-way{
    font-size: 40px;
    line-height: 47px;
    text-align: center;
    letter-spacing: -0.05em;
    color: #39393F;
    margin: auto;
    width: 40%;
    margin-bottom: 26px;
}
span{
    color: green;
    font-style: italic;
}
.ear1{
    font-size: 18px;
    line-height: 185.6%;
     text-align: center; 
    letter-spacing: -0.03em;
    color: #8E8E95;
    margin: auto;
    width: 60%;
    margin-bottom: 50px;

}
.happyman{
    text-align: center;
}

@media screen and (max-width: 745px){
    .better-way{
        width: 80%;
        font-size: 25px;
    }
    .ear1{
        width: 100%;
        font-size: 16px;
    }
    .main{
        padding: 50px 20px 0 20px;
    }
    .happyman img{
        width: 280px;
        height: 256px;
    }
}

</style>