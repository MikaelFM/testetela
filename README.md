<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Aulas</title>
        <link rel="shortcut icon" href="icon2.png" type="image/x-icon">
        <style>
            .black {
    margin: 0;
    background: #070707;
    }
    
.white {
    margin: 0;
    background: #ffffff;
}
    .black p2 {
        color: rgb(0, 255, 13);
    }
    .white p2 {
        color: #005713;
    }
    .black #p {
        text-align: center;
        margin-left: auto;
        color: rgb(255, 255, 255);
        font-size: xx-large;
        font-family: Open Sans;
        font-weight: bold;
    }
    .white #p {
        text-align: center;
        margin-left: auto;
        color: rgb(0, 0, 0);
        font-size: xx-large;
        font-family: Open Sans;
        font-weight: bold;
    }
    .black #container-imagem {
        position: relative;
        height: 100vh;
        width: 100vw;
        background: url('background1.png');
        background-size:auto;
    }
    .white #container-imagem {
        position: relative;
        height: 100vh;
        width: 100vw;
        background: url('white.png');
        background-size: cover;
    }

    img {
        align-self: center;
        display: block;
        margin-left: auto;
        margin-right: auto;
        padding-top: 10%;
        width: 994px;
        height: 337px;
    }
    #p {
        text-align: center;
        margin-left: auto;
        color: white;
        font-size: xx-large;
        font-family: Open Sans;
        font-weight: bold;
    }
    .black #dia{
        background-color: #070707;
        align-self: center;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 400px;
    }
    .white #dia{
        background-color: #070707;
        align-self: center;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 400px;
    }
    #p2 {
        text-align: center;
        color: rgb(255, 255, 255);
        font-size: 200%;
        font-family: Open Sans;
        font-weight: bold;
        padding: 10px;
    }
    .black #pc {
        color: rgb(0, 255, 13);
        font-size: 200%;
        font-family: Open Sans;
        position: relative;
    }
    .white #pc {
        color: #005713;
        font-size: 200%;
        font-family: Open Sans;
        position: relative;
    }
    .container {
        align-items: center;
        position: relative;
        width: 50%;
        margin-left: auto;
        margin-right: auto;
    }
    .container .skill {
        position: relative;
        display: flex;
        margin: 24px 0;
        padding: 24px 10px 18px;
    }
    .container .skill:before{
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 50%;

    }
    .container .skill .percent {
        position: relative;
        width: calc(100% - 90px);
        height: 5px;
        margin: 0 10px;
        border-radius: 10px;
        background: white;
        overflow: hidden;
    }
    .white .container .skill .percent .progress {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 10px;
        background: #005713;
        animation: animate 3s ease-in-out forwards;
    }
    .black .container .skill .percent .progress {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border-radius: 10px;
        background: rgb(0, 255, 13);
        animation: animate 3s ease-in-out forwards;
    }
    .black .value {
        bottom: 5px;
        color: rgb(0, 255, 13);
        font-size: 100%;
        font-family: Open Sans;
        position: relative;
    }
    .white .value {
        font-weight: bold;
        bottom: 5px;
        color: #005713;
        font-size: 100%;
        font-family: Open Sans;
        position: relative;
    }
    @keyframes animate {
        from {
            width: 0;
        }
    }
    @media screen and (max-width: 1722px){
        body {
            background-color: red;
        }
        .black #p {
            text-align: center;
            margin-left: auto;
        }
        .white #p {
            text-align: center;
            margin-left: auto;
        }
    }
    @media screen and (max-width: 1436px){
        body {
            background-color: green;
        }
        .black #p {
            text-align: center;
            margin-left: auto;
        }
        .white #p {
            text-align: center;
            margin-left: auto;
        }
    }
    @media screen and (max-width: 1217px){
        body {
            background-color: yellow;
        }
        .black #p {
            text-align: center;
            margin-left: auto;
        }
        .white #p {
            text-align: center;
            margin-left: auto;
        }
    }
    @media screen and (max-width: 1090px){
        body {
            background-color: blue;
        }
    }
    @media screen and (max-width: 993px){
         body {
            background-color: orange;
        }
        img {
            width: 850px;
            height: 289px;
        }
    }
    @media screen and (max-width: 850px){
        #container-imagem {
            background: url('brilho+.png');
        }
         body {
            background-color: white;
        }
        img {
            width: 700px;
            height: 238px;
        }
        .black #p {
            font-size: 25px;
        }
        .white #p {
            font-size: 25px;
        }
        #p2 {
            font-size: 25px;
        }
        .white #dia {
            width: 280px;
        }
        .black #dia {
            width: 280px;
        }
        .container {
            align-items: center;
            position: relative;
            width: 90%;
            margin-left: auto;
            margin-right: auto;
        }
    }
    @media screen and (max-width: 700px){
         body {
            background-color: lime;
        }
        img {
            width: 580px;
            height: 197px;
        }
        .black #p {
            font-size: 20px;
        }
        .white #p {
            font-size: 20px;
        }
        #p2 {
            font-size: 20px;
        }
        .white #dia {
            width: 230px;
        }
        .black #dia {
            width: 230px;
        }
        .container {
            align-items: center;
            position: relative;
            width: 130%;
            margin-left: auto;
            margin-right: auto;
        }
    }
    @media screen and (max-width: 580px){
         body {
            background-color: gray;
        }
        img {
            width: 400px;
            height: 136px;
        }
        .black #p {
            font-size: 15px;
        }
        .white #p {
            font-size: 15px;
        }
        #p2 {
            font-size: 15px;
        }
        #dia {
            width: 230px;
        }
        .container {
            align-items: center;
            position: relative;
            width: 90%;
            margin-left: auto;
            margin-right: auto;
        }
        .container .skill .percent {
            height: 2.5px; 
        }
        .value {
            font-size: 10px;
        }
    }
    @media screen and (max-width: 505px){
         body {
            background-color: red;
        }
        #container-image img {
            width: 370px;
            height: 126px;
        }
        img {
            width: 370px;
            height: 126px;
        }
        .white #dia {
            width: 230px;
        }
        .black #dia {
            width: 230px;
        }
        .container {
            align-items: center;
            position: relative;
            width: 90%;
            margin-left: auto;
            margin-right: auto;
        }
        .container .skill .percent {
            height: 2.5px; 
        }
        .value {
            font-size: 10px;
        }
    }
    @media screen and (max-width: 400px){
         body {
            background-color: moccasin;
        }
        img {
            width: 300px;
            height: 102px;
        }
        #container-image img {
            width: 300px;
            height: 102px;
        }
        .black #p {
            font-size: 11px;
        }
        .white #p {
            font-size: 11px;
        }
        #p2 {
            font-size: 11px;
        }
        .white #dia {
            width: 190px;
        }
        .black #dia {
            width: 190px;
        }
        .container {
            align-items: center;
            position: relative;
            width: 90%;
            margin-left: auto;
            margin-right: auto;
        }
        .container .skill .percent {
            height: 2.5px; 
        }
        .value {
            font-size: 10px;
        }
    }
    @media screen and (max-width: 305px){
         body {
            background-color: black;
        }
        img {
            width: 200px;
            height: 68px;
        }
        #container-image img {
            width: 200px;
            height: 68px;
            
        }
        .black #p {
            font-size: 8px;
        }
        .white #p {
            font-size: 8px;
        }
        #p2 {
            font-size: 11px;
        }
        .black #dia {
            width: 240px;
        }
        .white #dia {
         width: 240px;
        }
        .container {
            align-items: center;
            position: relative;
            width: 90%;
            margin-left: auto;
            margin-right: auto;
        }
        .container .skill .percent {
            height: 2.5px; 
        }
        .value {
            font-size: 10px;
        }
    }
    @media screen and (max-width: 205px){
        body {
           background-color: black;
       }
       img {
           width: 120px;;
           height: 41px;
       }
       #container-image img {
           width: 120px;
           height: 41px;
           
       }
       .black #p {
           font-size: 8px;
       }
       .white #p {
           font-size: 8px;
       }
       #p2 {
           font-size: 11px;
       }
       .black #dia {
           width: 150px;
       }
       .white #dia {
        width: 150px;
    }
       .container {
           align-items: center;
           position: relative;
           width: 90%;
           margin-left: auto;
           margin-right: auto;
       }
       .container .skill .percent {
           height: 2.5px; 
       }
       .value {
           font-size: 10px;
       }
   }


        </style>
    </head>
    </style>
</html>
