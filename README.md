<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bar e Restaurante Tempero do Nordeste</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }
        header {
            background-color: #ff9800;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #ff5722;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ff9800;
        }
        .section {
            padding: 20px;
        }
        .cardapio-item {
            border: 1px solid #ddd;
            margin-bottom: 10px;
            padding: 10px;
        }
        .gallery img {
            width: 100%;
            height: auto;
        }
        footer {
            background-color: #ff5722;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bar e Restaurante Tempero do Nordeste</h1>
        <p>Culinária típica brasileira no coração do Rio de Janeiro</p>
    </header>
    <nav>
        <a href="#sobre">Sobre Nós</a>
        <a href="#cardapio">Cardápio</a>
        <a href="#reservas">Reservas</a>
        <a href="#contato">Contato</a>
        <a href="#localizacao">Localização</a>
        <a href="#galeria">Galeria de Fotos</a>
        <a href="#avaliacoes">Avaliações de Clientes</a>
    </nav>
    <div class="section" id="sobre">
        <h2>Sobre Nós</h2>
        <p>Bem-vindo ao Bar e Restaurante Tempero do Nordeste, onde você encontra o melhor da culinária brasileira em um ambiente acolhedor e familiar. Localizado no centro do Rio de Janeiro, nosso restaurante é o lugar perfeito para desfrutar de pratos deliciosos e autênticos.</p>
    </div>
    <div class="section" id="cardapio">
        <h2>Cardápio</h2>
        <div class="cardapio-item">
            <h3>Picanha</h3>
            <p>Suculenta picanha grelhada servida com acompanhamentos.</p>
        </div>
        <div class="cardapio-item">
            <h3>Contra Filé</h3>
            <p>Contra filé macio e saboroso com guarnições.</p>
        </div>
        <div class="cardapio-item">
            <h3>Filé de Frango</h3>
            <p>Filé de frango grelhado com opções de molhos.</p>
        </div>
        <div class="cardapio-item">
            <h3>Peixes</h3>
            <p>Peixes frescos preparados com temperos especiais.</p>
        </div>
        <div class="cardapio-item">
            <h3>Sopas e Caldos</h3>
            <p>Variedade de sopas e caldos nutritivos.</p>
        </div>
        <div class="cardapio-item">
            <h3>Petiscos</h3>
            <p>Petiscos variados para compartilhar.</p>
        </div>
        <div class="cardapio-item">
            <h3>Espetinhos</h3>
            <p>Espetinhos de carne, frango e vegetais.</p>
        </div>
        <div class="cardapio-item">
            <h3>Pastéis</h3>
            <p>Pastéis recheados com sabores diversos.</p>
        </div>
    </div>
    <div class="section" id="reservas">
        <h2>Reservas</h2>
        <p>Para reservar uma mesa, por favor entre em contato conosco através do formulário abaixo ou ligue para (21) 1234-5678.</p>
        <form>
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name" required><br>
            <label for="date">Data:</label><br>
            <input type="date" id="date" name="date" required><br>
            <label for="time">Hora:</label><br>
            <input type="time" id="time" name="time" required><br>
            <label for="people">Número de pessoas:</label><br>
            <input type="number" id="people" name="people" required><br><br>
            <input type="submit" value="Reservar">
        </form>
    </div>
    <div class="section" id="contato">
        <h2>Contato</h2>
        <p>Para mais informações, entre em contato conosco:</p>
        <p>Telefone: (21) 1234-5678</p>
        <p>Email: contato@temperodonordeste.com</p>
        <form>
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>
            <label for="message">Mensagem:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <input type="submit" value="Enviar">
        </form>
    </div>
    <div class="section" id="localizacao">
        <h2>Localização</h2>
        <p>Estamos localizados na Av. Nossa Sra. de Fátima, 86 - Centro, Rio de Janeiro - RJ, 20240-030.</p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3675.9655251513185!2d-43.194764284486274!3d-22.906846885008364!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x997f5fca233e6b%3A0x8e4a0c4e6b9f8df5!2sAv.%20Nossa%20Sra.%20de%20F%C3%A1tima%2C%2086%20-%20Centro%2C%20Rio%20de%20Janeiro%20-%20RJ%2C%2020240-030%2C%20Brazil!5e0!3m2!1sen!2sus!4v1594616256810!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
    </div>
    <div class="section" id="galeria">
        <h2>Galeria de Fotos</h2>
        <div class="gallery">
            <img src="foto1.jpg" alt="Foto do restaurante">
            <img src="foto2.jpg" alt="Prato de comida">
            <img src="foto3.jpg" alt="Interior do restaurante">
        </div>
    </div>
    <div class="section" id="avaliacoes">
        <h2>Avaliações de Clientes</h2>
        <p>"Comida excelente e atendimento impecável! Recomendo a todos." - João Silva</p>
        <p>"Melhor restaurante de comida brasileira que já fui. Ambiente muito agradável." - Maria Souza</p>
    </div>
    <footer>
        <p>&copy; 2024 Bar e Restaurante Tempero do Nordeste. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
