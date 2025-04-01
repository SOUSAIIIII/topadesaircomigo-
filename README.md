<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muito obrigando por aparecer na minha vida amiga!</title>
        
    <style>
       body{
        background-color: red;
        text-align: center;
    
    }
        .painel{
        padding-top: 20px;
        margin: auto;
        width: 500px;
        height: 570px;
        background-color: white;
        border-radius: 20px;
        
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    
    h1{
      font-size: 500;

    }
    
    #sim{
        
        width: 80px;
        height: 60px;
        border-radius: 10px;
        background-color: red;
        color: bisque;
        font-size: 25px;
        margin-left: -90px;
        
        
    }
    #nao{
        position: absolute;
        width: 80px;
        height: 60px;
        border-radius: 10px;
        background-color: red;
        color: bisque;
        font-size: 25px;
        margin-left: 10px;
        
    }


    </style>

</head>
<body>

    <div class="painel">
        <h1>De Faço Um Convite Diferenciando!</h1>
        <img src="https://i.pinimg.com/474x/80/ff/38/80ff38c9f84d53c38651f55d5474ff41.jpg ">
        <h2>Topa de sair comigo Kaori no dia 6 no domingo assitir um filme comigo no Cinema?</h2>


    <a href="https://www.youtube.com/watch?v=XQmpVHUi-0A&list=PL8Z19zAeALxu6yGi1u2bRc2iZvxK-0A_o&index=2"><button id="sim"> Sim! </button></a>
    <button onmouseover= "fuja()" id="nao"> Não! </button>


</div>
<script>

    function fuja(){
        var botaoNao = document.getElementById("nao")
        
        var larguraJanela = window.innerWidth;
        var alturaJanela = window.innerHeight;

        var maxX = larguraJanela - botaoNao.offsetWidth;
        var maxY = alturaJanela - botaoNao.offsetHeight;

        var aleatorioX = Math.floor(Math.random() * maxX);
        var aleatorioY = Math.floor(Math.random() * maxY);

        botaoNao.style.left = aleatorioX + "px";
        botaoNao.style.top = aleatorioY + "px";
    }
</script>

</body>
</html>
