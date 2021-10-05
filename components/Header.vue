<template>
    <div>
        <p class="title_header">we are</p>
        <div class="grid_header">
            <p class="title_fw">fluidweb</p>
            <img class="logo" src="../assets/img/fwgreenlogo.svg" alt="">
            <p class="green_text">green</p>
        </div>
        <p class="desc_header">Here we want you to introduce to...</p>
    </div>
</template>

<style scoped>
    .title_fw{
        width: 417px;
        height: 84px;
        left: 382px;
        top: 358px;

        font-family: FLURO;
        font-style: normal;
        font-weight: bold;
        font-size: 80px;
        line-height: 84px;
        /* identical to box height */

        text-transform: uppercase;

        color: #000000;

    }
    .logo{
        height: 68.99999237060547px;
        width: 124.1998291015625px;
        

    }
    .grid_header{
        display: grid;
        grid-template-columns: 447px 154.2px 235px ;
        /* margin-left: 150px; */
        justify-content: center;

    }
    .desc_header{
        font-family: 'Cormorant', serif;
        font-style: normal;
        font-weight: 600;
        font-size: 26px;
        line-height: 32px;
        color: #0F0F0F;
        text-align: center;
        margin-top: 96px;
    }
    .green_text{
        
        font-family: 'Cormorant', serif;;
        font-style: normal;
        font-weight: 500;
        font-size: 112px;
        line-height: 66px;
        letter-spacing: -0.01em;
        color: #000000;
    }
    
    .title_l{
        margin-left: 150px;
        display:grid;
        grid-template-columns: 799px 184.2px 235px;
    }
    .title_header{
        margin-top: 175px;
        text-align: center;
        margin-bottom: 49px;
        font-family: 'Montserrat', sans-serif;;
        font-style: normal;
        font-weight: normal;
        font-size: 48px;
        line-height: 59px;
        text-transform: uppercase;
        color: #000000;
    }

    .subtitle_header{
        /* height: 84px; */
        width: 417px;
        left: 382px;
        margin-top: 20px;
/* border-radius: nullpx; */

    }
@import url('https://fonts.googleapis.com/css2?family=Cormorant:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap');
/* @font-face{

font-family: 'FLURO';

src: url('../fonts/FLURO-Bold.otf');
font-weight: bold;

font-style: normal;

} */
@font-face {

font-family: "FLURO"; 
src: url("../assets/font/FLURO-Bold.otf") format("truetype"); 
font-style: bold; 
font-weight: normal; 
} 
</style>