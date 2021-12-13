<template>
    <section class="main">
        <div class="content-wrapper">
            <div class="left">
                <h5 class='build'>Build great relationships with those you admire.</h5>
                <div class="dm">With ear1, replies to your DMs are guaranteed!</div>
            </div>
            <div class="right">
                <div class="buttons">
                    <div class="bt1"><img src="../assets/appstore1.png" alt="" class="appstore"></div>
                    <div class="bt2"><img src="../assets/playstore1.png" alt="" class="playstore"></div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.main{
 
    padding: 100px 100px 100px 100px;
}
.content-wrapper{
    background-color: #00BF69;
    border-radius: 30px;
    display: flex;
    justify-content: space-evenly;
    padding: 70px;
}
.build{
    font-size: 35px;
    line-height: 115.3%;
    letter-spacing: -0.05em;
    color: #FFFFFF;
    width: 70%;
    margin-bottom: 26px;
}
.dm{
    font-size: 18px;
    line-height: 185.6%;
    letter-spacing: -0.03em;
    color: #FFFFFF;

}
.buttons{
    display: flex;
    gap: 30px;
    margin-top: 40px;
}
@media  screen and (max-width: 765px){
    .main{
        padding: 50px 20px 
    }
    .content-wrapper, .buttons{
        flex-wrap: wrap;
    }
    .content-wrapper{
       padding: 30px;
    }
    .build{
        width: 100%;
        font-size:23px;
        text-align: center;
    }
    .dm{
        font-size: 16px;
        text-align: center;
        margin: auto;
        width: 90%;
    }
    .buttons{
      
        justify-content: center;
    }
    .bt1, .bt2{
        width: 172px;
        height: 70px;
    }
    .bt1 img, .bt2 img{
        width: 100%;
        height: 100%;
    }

}
</style>