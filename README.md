
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Mercadinho Sousa</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f0ff;
            color: #003366;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            text-align: center;
            margin: 20px;
        }

        section {
            padding: 20px;
        }

        .product-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .product {
            background-color: white;
            border: 1px solid #ccc;
            padding: 10px;
            width: 200px;
            text-align: center;
        }

        .product img {
            max-width: 100%;
            height: 150px;
            object-fit: contain;
        }

        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .chat-buttons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }

        .chat-buttons a {
            text-decoration: none;
            padding: 10px 15px;
            color: white;
            background-color: #007BFF;
            border-radius: 5px;
        }

        iframe {
            border: none;
        }

        .email-form {
            margin-top: 20px;
            text-align: center;
        }

        .email-form input {
            padding: 10px;
            margin: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Mercadinho Sousa</h1>
    <p>Rua Cinco N°40, Bairro Popular Nova, Exu - PE</p>
</header>

<nav>
    <div id="google_translate_element"></div>
</nav>

<section>
    <h2>Lista de Produtos</h2>
    <div class="product-grid">
        <!-- Exemplo de produto -->
        <div class="product">
            <img src="https://arrozurbano.com/200x150?text=Arroz" alt="Arroz">
            <h3>ArrozUrbano</h3>
            <p>R$ 25,00</p>
        </div>
        <div class="product">
            <img src="https://feijaocariocanarcizio.com/200x150?text=Feijão" alt="Feijão">
        <h3>Feijão Carioca Narcizio</h3>
            <p>R$ 10,00</p>
        </div>
        <div class="product">
            <img src="https://açucarcamponesa.com/200x150?text=Açúcar" alt="Açúcar">
      <h3>Açúcar Campones</h3>
            <p>R$ 4,50</p>
        </div>
        <div class="product">
            <img src="https://marata.com/200x150?text=Café" alt="Café">
         <h3>Café Marata</h3>
            <p>R$ 7,00</p>
        </div>
        <div class="product">
            <img src="https://richester.com/200x150?text=Biscoitos" alt="Biscoitos">
    <h3>Biscoitos Richester</h3>
            <p>R$ 3,50</p>
        </div>
        <div class="product">
            <img src="https://petim.com/200x150?text=Leite+Integral" alt="Leite Integral">
   <h3>Leite Integral Petim</h3>
            <p>R$ 6,00</p>
        </div>
        <div class="product">
            <img src="https://kibom.com/200x150?text=Sorvetes" alt="Sorvetes">
     <h3>Sorvetes Kibom</h3>
            <p>R$ 5,00</p>
        </div>
        <div class="product">
            <img src="https://kibom.com/200x150?text=Picolés" alt="Picolés">
       <h3>Picolés Kibom</h3>
            <p>R$ 2,00</p>
        </div>
        <div class="product">
            <img src="https://sabaojua.com/200x150?text=Sabão" alt="Sabão">
          <h3>Sabão Jua</h3>
            <p>R$ 3,00</p>
        </div>
        <!-- Adicione mais produtos aqui -->
    </div>
</section>

<section>
    <h2>Localização</h2>
    <iframe
        src="https://www.google.com/maps?q=Rua+Cinco+40,+Bairro+Popular+Nova,+Exu,+PE&output=embed"
        width="100%" height="300"></iframe>
</section>

<section>
    <h2>Entre em Contato</h2>
    <div class="chat-buttons">
        <a href="#" target="_blank">Chat de Atendimento</a>
        <a href="https://wa.me/5587996349673" target="_blank">WhatsApp</a>
        <a href="https://www.instagram.com/seuusuario" target="_blank">Instagram</a>
        <a href="https://www.facebook.com/seupagina" target="_blank">Facebook</a>
        <a href="https://twitter.com/seuusuario" target="_blank">Twitter</a>
    </div>

    <div class="email-form">
        <h3>Cadastre seu e-mail para promoções:</h3>
        <form action="#" method="post">
            <input type="email" placeholder="Seu e-mail" required>
            <input type="submit" value="Cadastrar">
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2025 Mercadinho Sousa. Todos os direitos reservados.</p>
</footer>

<!-- Google Tradutor -->
<script type="text/javascript">
    function googleTranslateElementInit() {
        new google.translate.TranslateElement({
            pageLanguage: 'pt',
            includedLanguages: 'pt,en,es,fr',
            layout: google.translate.TranslateElement.InlineLayout.SIMPLE
        }, 'google_translate_element');
    }
</script>
<script type="text/javascript"
    src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit">
</script>

</body>
</html>
