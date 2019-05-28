# Site do João da Silva (Em desenvolvimento)#



<html lang="pt-br"><head>
    <meta charset="UTF-8">
    <title>Biografia</title>
    <link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Crimson+Text:400,400italic,600">
    <link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Open+Sans+Condensed:700">
    <link rel="stylesheet" href="index.css">
    <style>
		.titulo-principal{
    font-family: 'Open Sans Condensed', sans-serif;
    text-align: center;
    font-size: 30px;
    text-transform: uppercase;
    border: 1px solid black;
    background-color: #851944;
    color: #ffffff;
    border-bottom: 10px solid black;
}

.container{
    border: 1px solid black;
    margin-top: 50px;
    font-family: 'Crimson Text', serif;
    font-size: 19px;
    line-height: 1.5;
    width: 55%;
    text-align: justify;
    margin-left: 5%;
}

body{
    background-color: #F2FFFC;
}

.subtitulos{
    font-family: 'Open Sans Condensed', sans-serif;

}

.fiat{
    border: 10px solid #C2CCCA;
    background-color: #D9E5E3;
    width: 35%;
    text-align: justify;
    padding-bottom: 30px;
    float: right;
    margin-left: 7%;
    margin-right: 5%;
}

.petrobras{
    border: 10px solid #C2CCCA;
    background-color: #D9E5E3;
    width: 35%;
    text-align: justify;
    float: left;
    margin-right: 7%;
    margin-left: 5%;
}

cite{
    float: right;
    line-height: 1;
    padding-top: 20px;
}

.conteudo-principal{
    border: 1px solid black;
}

footer{
    background-color: black;
    color: #fff;
    font-size: 18px;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 20px;
    position: fixed;
}

.foto-joaodasilva{
    border: 1px solid black;
    border-bottom: 10px solid black;
    border-left:  10px solid black;
    box-sizing: border-box;
    float: right;
}

.itens-navegacao{
    font-family: 'Open Sans Condensed', sans-serif;
    color: #F2FFFC;
    background-color: #3C1D3D;
    position: relative; 
    top: 311px;
    left: 310px;
    border-left: 10px solid black;
    float: right;
    clear: left;
    width: 15%;
    text-align: center;
    padding-bottom: 20px;
    border-bottom: 10px solid black;
}

.itens-navegacao h1{
    font-size: 30px;
}

.itens-navegacao li{
    list-style: none;
    font-size: 20px;
}

.itens-navegacao a{
    margin-top: 20px;
    text-indent: -99999px;
    display: inline-block;
    width: 40px;
    height: 40px;;
}

.github{
    background-image: url(https://github.com/fredsonchaves07/site-joaodasilva/blob/master/img/github.png?raw=true);
}

.twitter{
    background-image: url(https://github.com/fredsonchaves07/site-joaodasilva/blob/master/img/twitter.png?raw=true);
}

.linkedin{
    background-image: url(https://github.com/fredsonchaves07/site-joaodasilva/blob/master/img/linkedin.png?raw=true);
}

.strong{
    font-weight: bold;
}
.footerfixed {
background-color: #ccc;height: auto;width: 100%;bottom:0;display:block;position:fixed;text-align: center;
}        
</style>
</head>
<body>
    
    <main>
        <img class="foto-joaodasilva" src="https://github.com/fredsonchaves07/site-joaodasilva/blob/master/img/eu.jpg?raw=true" alt="Foto do João da Silva">
        <ul>
            <div class="itens-navegacao">
                <h1>João da Silva</h1>
                <li>home</li>
                <li>portfolio</li>
                <li>sobre mim</li>
                <li>contato</li>
                <a class="github" href="https://github.com/joaodasilva">GitHub</a>
                <a class="twitter" href="https://twitter.com/joaodasilva">Twitter</a>
                <a class="linkedin" href="https://linkedin.com/joaodasilva">Linkedin</a>
            </div>
        </ul>
        <div class="titulo-principal">
            <h1>Sobre mim</h1>
        </div>
        <div class="container">
                <div>
                    <p>Moro em São Paulo mas atendo clientes do mundo todo. Sou conhecido por fazer produtos de <em>qualidade, durabilidade</em> e que <em>agregam valor</em> para meus clientes.</p>
                    <p>Trabalho usando a web como plataforma, ou seja, respiro HTML5, CSS3 e JavaScript (ou melhor: ECMASCript). Crio sites para todos, seguindo as principais diretivas de acessibilidade, responsividade e web semântica, sem descuidar da qualidade de código.</p>
                </div>
                    <h2 class="subtitulos">Como trabalho</h2>   
                <div class="fiat">
                    <blockquote>
                        João é o melhor desenvolvedor front-end com quem já trabalhei. Muito eficiente e muito capaz. Recomendo sem dúvidas!<br>
                        <cite>José Souza, Fiat</cite>
                    </blockquote>
                </div>
                
                <div class="conteudo-principal">
                    <p>Satisfazer meus clientes é prioridade. Para isso, garanto um processo de desenvolvimento altamente interativo, baseado em feedback contínuo. <strong>Não trabalho com escopo fechado:</strong> o cliente é que decide quando o produto está pronto.</p>
                    
                    <p>Também não trabalho com prazos fechados: <strong>qualidade é importante demais para ser sacrificada.</strong></p>
                </div>
                <h2 class="subtitulos">Experiência</h2>
                <div class="petrobras">
                    <blockquote>
                        João domina as tecnologias como ninguém. Eu apresentava um problema, ele tinha na ponta da língua a solução mais adequada com as tecnologias mais recentes.<br>
                        <cite>Manoel Santos, Petrobrás</cite>
                    </blockquote>
                </div>
                <div class="conteudo-principal">
                    <p>Já desenvolvi projetos para grandes empresas como <a href="www.bmw.com">BMW</a> <a href="www.uol.com.br">UOL</a> e <a href="www.ibm.com">IBM</a>. Neles, o foco principal era entregar uma experiência imersiva e impactante para o usuário final sem descuidar do desempenho e da acessibilidade da página.</p>
                    <p>Também já fui contratado para transformar grandes portais, como <a href="www.terra.com.br">Terra</a> e <a href="www.g1.com">G1</a>, em páginas responsivas. Fui responsável por renovar o layout, reorganizar o conteúdo e re-escrever o código de forma mais reaproveitável.</p>
                </div>
                <h2 class="subtitulos">Comunidade</h2>
                <div class="conteudo-principal">
                    Procuro repassar meu conhecimento para a comunidade. Para isso, já dei <a href="portfolio.html">diversas palestras</a>  e mantenho um blog.
                </div>
        </div>
<div class="footerfixed">Rodapé da Pagina</div>
    </main>
    <footer>
        <p>© João da Silva 2018</p>
    </footer>


</body></html>
