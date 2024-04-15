# site.ccm2
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com"&gt;
    <link rel="preconnect" href="https://fonts.gstatic.com&quot; crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap&quot; rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>CCM Edite Cordeiro Marques</title>
</head>
<body>
    <header class="cabecalho">
        <img class="cabecalho-imagem" src="ccmedite.jpg" alt="logo da alura start">
        <ul class="cabecalho-lista">
            <li class="cabecalho-lista-item">Escola</li>
            <li class="cabecalho-lista-item">Estudante</li>
        </ul>
    </header>
    <section class="escola">
        <div class="escola-div-conteudo">
            <h2 class="escola-titulo">Sobre a Escola</h2>
            <p class="escola-texto-um">Os antecedentes históricos do Colégio Estadual Edite Cordeiro Marques – Ensino de 1º e 2º Graus, inicia-se aproximadamente em 1932, com classe de alfabetização em casa particular de Frida Rickli Naiverth; em 1938/39, criou-se a Escola Pública Municipal do Rio Turvo, com professores Municipais e Estaduais; em 26/05/71, através do Decreto nº 408, criou-se o Grupo Escolar do Distrito de Turvo.</p>
            <p class="escola-texto-dois">Endereço: Av. Nossa Sra. Aparecida, s/n, Centro, Turvo  - PR, 85150-000  Telefone:(42) 3642-1210 </p>
        </div>
        <img class="escola-imagem" src="ccm edite.jpg" alt="colégio">
    </section>
    <section class="estudante">
        <h2 class="estudante-titulo">Quem são nossos estudantes?</h2>
        <div class="estudante-todos">
        <span></span>
        <div class="estudante-div">
            <img class="estudante-imagem" src="Marcelo.jpeg" alt="foto do marcelo">
            <h3 class="estudante-nome">Marcelo</h3>
            <a href="https://github.com/marcelopaludetto"><img class="estudante-icone" src="github.png" alt="icone github"></a>
            <a href="https://instagram.com/marcelopaludetto"><img class="estudante-icone" src="instagram.png" alt="icone instagram"></a>
        </div>
        <div class="estudante-div">
            <img class="estudante-imagem" src="" alt="foto do aluno">
            <h3 class="estudante-nome">Marcelo</h3>
            <a href=""><img class="estudante-icone" src="github.png" alt="icone github"></a>
            <a href=""><img class="estudante-icone" src="instagram.png" alt="icone instagram"></a>
        </div>
       
    </div>
    </section>
 <footer class="rodape">
        <img class="rodape-imagem"src="alurastart logo.png" alt="logo da alura start">
    </footer>
</body>
</html>



e o style.css ficou assim:
* {
    margin: 0;
    padding: 0;
}

.cabecalho {
    background-color: #4d805d;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 24px 0;
}

.cabecalho-imagem{
    width: 15%;
}

.cabecalho-lista-item{
    display: inline-block;
    margin: 0 16px;
    font-size: 20px;
}

.escola-imagem{
    width: 25%;
}

.escola{
    background-image: linear-gradient(#64c095,#2c744a);
    color:white;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 24px 0;
}

.escola-div-conteudo{
    width: 35%;
}
.escola-titulo{
    padding: 24px 0;
}

.estudante{
    padding: 24px 0;
}
.estudante-imagem{
    width: 120px;
}

.estudante-icone{
    width: 24px;
    padding: 4px 8px;
}

.estudante-div{
    text-align: center;
    padding: 16px 0;
}
.rodape{
    background-color: black;
    text-align: center;
}

.rodape-imagem{
    height: 60px;
    padding: 12px 0;
   
}
