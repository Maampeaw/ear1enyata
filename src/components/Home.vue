<template>
    <div class="hero">
        <nav class="header">
            <div class="logo">
                <img src="../assets/logo green + black.png" alt="" class="logo1">
            </div>
            <div class="navlist">
                <div>About</div>
                <div>FAQs</div>
                <div>Contact us</div>
            </div>
            <div class="menu-bars" ><img src="../assets/menu.png" alt="" class="bars"></div>
        </nav>

        <section class='herosection'>
            <div class="hero1">
            <h1 class='connect'>Connect with Professionals in your field without getting aired</h1>
            <div class=wrapper>
            <div class="fee">For a small fee, ear1 allows you to get in touch with professionals in your field and build quality relationships with them. </div>
            <div class="getit">
                <div class="appstore"><img src="../assets/appstore.png" alt="" class="appst"></div>
                <div class="playstore"><img src="../assets/playstore.png" alt="" class="playst"></div>
            </div>
            </div>
            <div class="davido"><img src="../assets/Davido.jpg" alt="" class="dpic"></div>
            <div class="prosper"><img src="../assets/Propser.jpg" alt="" class="ppic"></div>
            <div class="shola"><img src="../assets/Shola.jpg" alt="" class="boy"></div>
            <div class="moe"><img src="../assets/Moe.jpg" alt="" class="girl"></div>
            
            
            </div>
        </section>
    </div>
</template>


<style scoped>
/* .hero{
    height: 750px;
} */
.header{
    display: flex;
    justify-content: space-between;
    margin: auto;
    width: 80%;
    height: 100px;
    align-items: center;
}
.navlist{
    display: flex;
    gap: 50px;
}
.navlist div{
    font-size: 1.2em;
    line-height: 19px;
    color: gray;
}
.herosection{
    margin-top: 120px;
}
.hero1{
    position: relative;
    margin: auto;
    width: 80%;
    height: 420px;
    /* border: 1px solid black; */
    
}
.connect{
    text-align: center;
    font-size: 3em;
    margin: auto;
    width: 70%;
    margin-bottom: 40px;
    
}
.davido, .prosper, .moe, .shola{
    position: absolute;
}
.davido{
    top: 50px;
}
.prosper{
    right: 0;
    top: 0;
}

.moe{
    right: 100px;
    bottom: 20px;
}
.shola{
    left: 100px;
    bottom: 0;
}
.fee{
    margin: auto;
    width: 50%;
    text-align: center;
    color: #6A6A70;
    
}
.logo{
    width: 80px;
    height: 30px;
}
.logo img{
    width: 100%;
    height: 100%;
}
.getit{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    margin: auto;
    width: 30%;
    margin-top: 65px;
    /* border: 1px solid black; */
}
.appstore{
    width: 180px;
    height: 62px;
}
.appstore img{
    width: 100%;
    height: 100%;
}
.menu-bars{
    display: none;
}

@media  screen and (max-width: 765px) {
    .connect{
        font-size: 30px;
        margin: 0, 0, 0, 0;
        width: 315px;
        /* position: absolute;
        top: 50px; */
    }
    .navlist{
        display: none;
    }
    .davido{
        top: -55px; 
    }
    .prosper{
        top: -60px;
    }
    .hero1{
        width: 90%;
        height: 480px;
    }
    .herosection{
        margin-bottom: 100px;
    }
    .shola{
        left:0;
        bottom: -65px;

    }
    .moe{
        right:0;
        bottom:-60px;
    }
    .davido, .shola, .prosper, .moe{
        width: 51px;
        height: 51px;
    }
    .davido img, .shola img, .prosper img, .moe img{
        width: 100%;
        height: 100%;
    }
    .fee{
        width: 90%;
        font-size: 18px;
    }
    .getit{
        justify-content: center;
        direction: block;
        gap: 30px;
        width: 100%;
        margin-bottom: 50px;
    }
    .appstore, .playstore{
        width: 172px;
    }
    .herosection{
        height: 500px;
    }
    .menu-bars{
        display: block;
    }
   
}
</style>