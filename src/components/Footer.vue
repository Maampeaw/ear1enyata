<template>
    <div class="main">
        <div class="left">
            <div class="logo"><img src="../assets/ear1.png" alt="" class="ear1"></div>
            <div class="copyright"><div><img src="../assets/gg_copyright.png" alt="" class="symbol"></div><div class='date'> 2020 ear1Social</div></div>
            <div class="privacy">Privacy policy  |  Terms of service</div>
        </div>
        <div class="right">
            <div class="company">
                <ul class=comp>
                    <li class='head'>Company</li>
                    <li class='sub'>About us</li>
                    <li class='sub'>FAQ's</li>
                    <li class='sub'>Contact us</li>
                </ul>
            </div>

            <div class="intouch">
                <div class="head get-in">Get in touch</div>
                <div class='sub quest'>Questions or feedback?, we would love to hear from you.</div>
                <div class="socials">
                    <div class="fb"><img src="../assets/fb.svg" alt="" class="facebook"></div>
                    <div class="twitter"><img src="../assets/twitter.svg" alt="" class="tter"></div>
                    <div class="instagram"><img src="../assets/instagram.svg" alt="" class="insta"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.main{
    background-color: #39393F;
    padding: 100px;
    display: flex;
    justify-content: space-between;
}
.logo{
    margin-bottom: 20px;
}
.date{
    font-size: 20px;
    line-height: 84.6%;
    letter-spacing: -0.03em;
    color: #FCFCFC;
}
.copyright{
    display: flex;
    gap: 10px;
    height: 50px;
    align-items: center;
}
.privacy{
    font-size: 16px;
    line-height: 84.6%;
    letter-spacing: -0.03em;
    color: #BBBBBB;
    margin-top: 16px;
}
ul{
    list-style-type: none;
}
.head{
    font-size: 20px;
    line-height: 84.6%;
    letter-spacing: -0.03em;
    color: #FCFCFC;
    font-weight: bold;
}
.sub{
    font-size: 18px;
    line-height: 128.6%;
    letter-spacing: -0.03em;
    color: #BBBBBB;
}
li{
    margin-bottom: 16px;
}
.right{
    display: flex;
    gap: 200px;
}
.quest{
    width: 50%;
}
.get-in{
    margin-bottom: 20px;
}
.socials{
    display: flex;
    gap: 30px;
    margin-top: 8px;
    height: 50px;
    align-items: center;
}
@media screen and (max-width: 745px){
    .main, .right{
        flex-wrap: wrap;
        
    }
    .main{
        padding: 32px;
    }
    .right{
        gap: 50px;
    }
    .comp{
        margin-top: 50px;
    }
    .quest{
        width: 100%;
    }
}
</style>