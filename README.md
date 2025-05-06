<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apartamento 33m²para  Alugar</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Apartamento 33m² Empreedimento Quadra Butantã </h1>
    </header>
    <section class="gallery">
        <img src="Imagem Quadra.jpg" alt="Imagem do apartamento" />
        <img src=" "foto1.jpg", "foto2.jpg", "foto7.jpg", "foto4.jpg", "foto5.jpg","foto6.jpg",
        let indiceAtual = 0;

        function nextImage() {
        indiceAtual = (indiceAtual + 1) % imagens.length; // Avança para a próxima imagem
        document.getElementById("foto").src = imagens[indiceAtual];
        }

        function prevImage() {
        indiceAtual = (indiceAtual - 1 + imagens.length) % imagens.length; // Volta para a imagem anterior
        document.getElementById("foto").src = imagens[indiceAtual];
        }

    </section>
    <section class="info">
        <h2>Detalhes do Imóvel</h2>
        <p>Localização: São Paulo, SP Bairro Butantã</p>
        <p>Raul Saddi n°88</p>
        <p>Próximo a USP</p>
        <p>Próximo o metrô linha amarela Butantã</p>
        <p>Apartamento Mobiliado</p>
        <p>Quartos: 2</p>
        <p>Banheiros: 1</p>
        <p>Condominio Completo area de lazer, academia, piscina, sala de massagem, biblioteca, briquedoteca, area pet, bicicletário, Lavanderia compartilhada.</p>
        <p>Apartamento com vaga para moto</p>

        <p>Valor: R$ 4.400,00/mês </p>
        <p> Valor Incluso Condomínio, gás, IPTU e Internet Vivo 500Megas</p>
        <button onclick="contato()">Entre em Contato</button>
    </section>
    <script src="script.js"></script>
    Contato: (11)97888-3636
    "Entre em contato pelo telefone: (11) 97888-3636";
    <a href="fotos.html">Ver Fotos</a>
    <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Fotos </title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Galeria de Fotos 
        Atenção: Fotos Desatualizadas, apartamento está mobiliado, marque a sua visita ou tira suas dúvidas no contato:11 97888-3636</h1>
    </header>
    <section class="gallery">
        <button onclick="prevImage()">&#10094;</button>
        <img id="foto" src="foto1.jpg" ; alt="Imagem do apartamento">
        <img id="foto" src="foto2.jpg" ; alt="Imageem do apartamento" />
        <img id="foto" src="foto3.jpg" ; alt="Imagem do apartamento" />
        <img id=" foto" src="foto4,jpg" ; alt="Imagem do apartamento" />
        <img id="foto" src="foto5.jpg" ; alt="Imagem do apartamento" />
        <img id="foto" src="foto6.jpg" ; alt="Imagem do apartamento" />
        <img id="=foto" src="foto7.jpg" ; alt="Imagem do apartamento" />
        <button onclick="nextImage()">&#10095;</button>
    </section>
    <script src="script.js"></script>
    <a href="Pagina inicial.html">Voltar à Página Inicial</button>

</body>
</html>

</body>
</html>
