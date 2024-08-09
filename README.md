<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Serralheria Artesanal</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <img src="img/logo.png" alt="logo">
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#serralheria">Serralheria</a></li>
                <li><a href="#portfolio">Portfólio</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
            <div class="social-icons">
                <a href="https://www.instagram.com/serralheria.rochasolucoes/" target="_blank">
                    <i class="fab fa-instagram"></i>
                </a>
                <a href="https://wa.me/553191021312" target="_blank">
                    <i class="fab fa-whatsapp"></i>
                </a>
            </div>
        </nav>
    </header>

    <section id="Sobre">
        <h1><br/><br/> Sobre</h1>
        <p><br/> Nossa serralheria é arte. Aqui, transformamos suas ideias em peças únicas, feitas com precisão e estilo. De portões a estruturas complexas, entregamos qualidade e durabilidade em cada detalhe. Aqui somos  movido pela paixão e experiência, sempre buscando superar expectativas. Seja qual for o projeto, estamos prontos para criar soluções metálicas que fazem a diferença no seu espaço. Vem com a gente e veja o que podemos fazer juntos.</p>
    </section>

    <section id="serralheria">
        <h1>Serralheria</h1>
        <p>Especializamos em esquadrias metálicas em geral, oferecendo produtos personalizados que atendem às suas necessidades específicas. Nossa equipe é experiente e dedicada, garantindo sempre os melhores resultados.</p>
    </section>

    <section id="portfolio">
        <h1>Portfólio</h1>
        <div class="gallery">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTu1sN-xwpE8KX1odO9-NrXqFTuk8NM8BUCUw&s" alt="Trabalho 1">
            <img src="https://delaclos.com.br/wp-content/uploads/2021/09/serralheria-delaclos-6.jpeg" alt="Trabalho 2">
            <img src="https://www.crolserralheria.com.br/wp-content/uploads/2020/04/escada-de-Ferro.jpg" alt="Trabalho 3">
            <img src="https://serralheriak-m.com.br/wp-content/uploads/2022/02/SERRALHERIA-Portoes-basculantes-EM-Tatuquara-Curitiba-15.jpg" alt="Trabalho 4">
            <img src="https://www.fabricadeportao.com.br/imagens/serralheria-grades-de-ferro-preco.jpg" alt="Trabalho 5">
            <img src="https://www.serralheriasns.com.br/imagens/servicos-de-serralheria-ferro.jpg" alt="Trabalho 6">
            <img src="https://serralheriak-m.com.br/wp-content/uploads/2022/02/SERRALHERIA-Portoes-de-aco-EM-Tatuquara-Curitiba-4.jpg" alt="Trabalho 7">
            <img src="https://cercamentoscattoni.com.br/wp-content/uploads/2023/10/Grade-de-janela-2.jpg" alt="Trabalho 8">
            <img src="https://armazemoficinas.com.br/wp-content/uploads/2019/11/SERRALHERIA-ARTESANAL-DO-ARMAZ%C3%89M-DAS-OFICINAS-32.jpg" alt="Trabalho 9">
            <img src="https://serralheirosp.com.br/wp-content/uploads/2022/03/estruturas-metalicas-3.jpeg" alt="Trabalho 10">
            <img src="https://serralherialucasegilberto.com.br/admin/mod_galeria_eventoscont/arquivos/8311c67ff5be4e3d9f713e6f7e54abf8.jpg" alt="Trabalho 11">
            <img src="https://serralherialucasegilberto.com.br/admin/mod_galeria_eventoscont/arquivos/502bf62007a7fb1975621525cb7f60c4.JPG" alt="Trabalho 12">
            
            
            
        </div>
    </section>

    <section id="contato">
        <h1>Contato</h1>
        <form>
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name">
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            
            <label for="message">Mensagem:</label>
            <textarea id="message" name="message"></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Serralheria Artesanal. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>




/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    overflow-x: hidden;
}

/* Header */
header {
    background-color: #333;
    color: white;
    padding: 1em 0;
    text-align: center;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

header img {
    height: 150px; /* Aumenta o tamanho da logo */
    vertical-align: middle;
}

nav {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap; /* Adicionado para responsividade */
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    flex-wrap: wrap; /* Adicionado para responsividade */
}

nav ul li {
    margin: 0 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2em;
}

.social-icons {
    display: flex;
    align-items: center;
    margin-left: auto;
}

.social-icons a {
    color: white;
    margin: 0 0.5em;
    font-size: 1.5em;
}

/* Section Styles */
section {
    padding: 8em 2em 2em; /* Adicionado padding-top extra para evitar o cabeçalho */
    text-align: center;
}

h1 {
    color: #333;
    font-size: 2em;
    font-weight: bold;
}

p {
    font-size: 1.2em;
    font-weight: bold;
}

/* Gallery Styles */
.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
}

.gallery img {
    width: 100%;
    max-width: 200px;
    height: auto;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Footer */
footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 1em 0;
    opacity: 0.7; /* Torna o footer transparente */
    font-size: 0.8em; /* Torna o texto menor */
}

/* Form Styles */
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

form label {
    margin: 0.5em 0 0.2em;
    font-size: 1.2em;
    font-weight: bold;
}

form input, form textarea {
    width: 80%;
    max-width: 400px;
    padding: 0.5em;
    margin-bottom: 1em;
    font-size: 1.2em;
    font-weight: bold;
}

form button {
    padding: 0.5em 2em;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 1.2em;
    font-weight: bold;
}

form button:hover {
    background-color: #555;
}

/* Responsive Styles */
@media (max-width: 768px) {
    header, footer {
        text-align: center;
    }

    nav ul {
        flex-direction: column;
    }

    nav ul li {
        margin: 0.5em 0;
    }

    .gallery img {
        max-width: 150px;
    }
}

@media (max-width: 480px) {
    nav ul li a {
        font-size: 1em;
    }

    .gallery img {
        max-width: 100px;
    }

    form input, form textarea {
        width: 90%;
    }


// Smooth scroll
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();

        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});


    form button {
        width: 90%;
        padding: 0.5em;
    }
}
