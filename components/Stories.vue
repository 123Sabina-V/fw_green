<template>
    <div>
        <h2 class="title_stor">our stories</h2>
        <p class="subtitle_stor">check out our reports on Convallis tortor, mattis mauris<br /> viverra viverra elit a venenatis lectus nulla fringilla </p>
        <div class="grid_stories">
            <div class="first_block">
                <p class="desc_fb">one planet,<img class="stars" src="../assets/img/stars.svg" alt=""><br />one experiment</p>
                <img class="fw_logo" src="../assets/img/fwgreenlogo.svg" alt="">
            </div>
             
            <div class="second_block">
                <img  src="../assets/img/img9.png" alt="">
                <a href="#"><img class="btn_ss" src="../assets/img/btn_sec_artc7.svg" /></a>
                <a href="#"><img class="btn_s7" src="../assets/img/btn_sec_artc3.svg" /></a>
                <a href="#"><p class="descs_article">Lorem ipsum dolor sit amet, consectetur adipiscing</p></a>
            </div>

            <div class="second_block">
                <img  src="../assets/img/img10.png" alt="">
                <a href="#"><img class="btn_ss10" src="../assets/img/btn_sec_artc7.svg" /></a>
                <a href="#"><img class="btn_s10" src="../assets/img/btn_sec_artc3.svg" /></a>
                <a href="#"><img class="btn_s10a" src="../assets/img/btn_sec_artc.svg" /></a>
                <a href="#"><p class="descs_article">Praesent habitasse ac, aliquam luctus vitae ornare egestas mollis enim</p></a>
            </div>

            <div class="second_block">
                <img  src="../assets/img/img11.png" alt="">
                <a href="#"><img class="btn_ss11" src="../assets/img/btn_sec_artc7.svg" /></a>
                <a href="#"><img class="btn_s11" src="../assets/img/btn_sec_artc.svg" /></a>
                <a href="#"><p class="descs_article">Libero cras lectus eu viverra urna dignissim volutpat nibh</p></a>
            </div>
        </div>
        <div class="grid_stor">
            <div>
                <a href="#"><img  src="../assets/img/img12.png" alt=""></a> 
                <a href="#"><img class="btn_gs" src="../assets/img/btn_sec_artc7.svg" /></a>
                <a href="#"><img class="btn_gs7" src="../assets/img/btn_sec_artc3.svg" /></a>
                <a href="#"><p class="descsg_article">Eget consequat vel quis eleifend tortor luctus morbi integer hendrerit eros nunc</p></a>
            </div>
            <div class="fifth_block">
                <div class="grid_bf">
                <p class="desc_fb">use<br />your<br />own<br />bag</p>
                <img class="starsf" src="../assets/img/stars.svg" alt="">
                </div>
                <img class="fw_logos" src="../assets/img/fwgreenlogo.svg" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped>
    .starsf{
        margin-top: 30px;
    }
    .grid_bf{
        display: grid;
        grid-template-columns: 202px 17.96px;
    }
    .fw_logos{
        width: 45px;
        height: 25px;
        left: 180px;
        
        margin-top: 270px;
        margin-left: 30px;
    }
    .fifth_block{
        width: 250px;
        height: 430px;
        left: 900px;
        top: 1060px;

        background: #FF4632;
        border-radius: 20px;
    }
    .descsg_article{
        margin-top: 15px;
        width: 700px;
        height: 26px;
        left: 150px;
        top: 1505px;
        font-family: Cormorant;
        font-style: normal;
        font-size: 20px;
        line-height: 26px;
        color: #0F0F0F;
    }
    .btn_gs7{
        position: absolute;
        margin-top: 391px;
        left: 297px;
    }
    .btn_gs{
        position: absolute;
        margin-top: 391px;
        left: 210px;
    
    }
    .grid_stor{
        display: grid;
        grid-template-columns: 750px 250px;
        margin-left: 200px;
        margin-top: 130px;
    }
    .btn_s10a{
     
            position: absolute;
            margin-top: 391px;
            left: 1091px;   
    }
    .btn_s11{
            position: absolute;
             margin-top: 391px;
            left: 1347px;
        }
    .btn_s10{
            position: absolute;
            margin-top: 391px;
            left: 1047px;
        }
    .btn_ss11{
        position: absolute;
        margin-top: 391px;
        left: 1260px;
    }
    .btn_ss10{
        position: absolute;
        margin-top: 391px;
        left: 960px;
    }
    .descs_article{
        width: 250px;
        height: 52px;
        left: 600px;
        margin-top: 15px;

        font-family: 'Cormorant', serif;
        font-style: normal;
        font-size: 20px;
        line-height: 26px;
        /* or 130% */


        /* black */

        color: #0F0F0F;
    }
    

    .btn_s7{
        position: absolute;
        margin-top: 391px;
        left: 747px;
    }
    .btn_ss{
        position: absolute;
        margin-top: 391px;
        left: 660px;
    
    }
    .img_ss{
        margin-left: 50px;
        
        
    }
    .fw_logo{
        width: 45px;
        height: 25px;
        left: 180px;
        top: 665px;
        margin-top: 90px;
        margin-left: 30px;
    }
    .stars{
        width: 17.96px;
        height: 15.56px;
        margin-top: 5px;
        margin-left: 82px;
    }
    .desc_fb{
        
        width: 340px;
        height: 90px;
        margin-left: 30px;
        margin-top: 25px;
        font-family: FLURO;
        font-style: normal;
        font-weight: bold;
        font-size: 43px;
        line-height: 45px;
        color: #FFFFFF;
    }
    .first_block{
        width: 400px;
        height: 250px;
        left: 150px;
        top: 460px;

        background: #509BF5;
        border-radius: 20px;
    }
    .grid_stories{
        margin-top: 150px;
        display:grid;
        grid-template-columns: 450px 300px 300px 300px;
        margin-left: 200px;
    }
    .title_stor{
        margin-top: 100px;;
        height: 110px;
        left: 439px;
        

        font-family: FLURO;
        font-style: normal;
        font-weight: bold;
        font-size: 106px;
        line-height: 110px;
        /* identical to box height, or 104% */

        text-align: center;
        text-transform: uppercase;

        color: #0F0F0F;
    }

    .subtitle_stor{
        height: 90px;
        left: 227px;
        top: 220px;

        font-family: Cormorant;
        font-style: normal;
        font-weight: 500;
        font-size: 34px;
        line-height: 45px;
        /* or 132% */

        text-align: center;
        letter-spacing: 0.02em;
        text-transform: uppercase;

        color: #0F0F0F;

    }

      @font-face {

    font-family: "FLURO"; 
    src: url("../assets/font/FLURO-Bold.otf") format("truetype"); 
    font-style: bold; 
    font-weight: normal; 
    } 

    @import url('https://fonts.googleapis.com/css2?family=Cormorant:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap');
</style>