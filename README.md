# Prototipo-1.0
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ellie Williams - The Last of Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #000; /* Fundo preto */
            color: #fff; /* Texto branco para melhor contraste */
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh; /* Altura total da janela */
        }

        header {
            background: url('https://getwallpapers.com/wallpaper/full/e/7/5/1293132-free-stars-hd-wallpapers-1920x1080-laptop.jpg') no-repeat center center; /* Imagem de banner */
            background-size: cover;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            width: 100%;
            position: fixed;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: rgba(0, 0, 0, 0.6); /* Fundo translúcido para o menu */
            margin: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        .container {
            max-width: 900px;
            width: 100%;
            background-color: #1e1e1e; /* Cor de fundo do conteúdo */
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            border-radius: 10px; /* Bordas arredondadas */
            margin: 150px auto 20px auto; /* Espaço para o menu fixo e separação do rodapé */
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            width: 100%;
            position: fixed;
            bottom: 0;
        }

        .content {
            display: flex;
            gap: 20px; /* Espaçamento entre imagem e texto */
            flex-direction: row; /* Garante que imagem e texto fiquem lado a lado */
            align-items: flex-start; /* Alinha o texto e a imagem no topo */
        }

        .image-container {
            flex: 0 0 30%; /* A imagem ocupa 30% da largura do container */
            text-align: center;
        }

        .image-container img {
            max-width: 100%; /* Ajusta a imagem para caber dentro do container */
            height: auto;
            border-radius: 10px; /* Bordas arredondadas */
        }

        .info-details {
            margin-top: 10px; /* Espaçamento entre a imagem e as informações adicionais */
            text-align: center;
        }

        .text-container {
            flex: 1;
        }

        .text-container h2 {
            margin-top: 0;
        }

        .text-container p {
            text-align: justify; /* Alinha o texto de forma que fique justificado */
            line-height: 1.6; /* Melhora a legibilidade aumentando o espaçamento entre linhas */
            margin: 0 0 20px 0; /* Adiciona espaço abaixo do parágrafo */
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
            align-items: center;
        }

        form label {
            font-weight: bold;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
        }

        form input[type="submit"] {
            width: auto;
            background-color: #444;
            color: #fff;
            border: none;
            cursor: pointer;
            padding: 10px 20px;
        }

        .author-list {
            list-style-type: none;
            padding: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ellie Williams - The Last of Us</h1>
    </header>
    <div class="container">
        <main>
            <section id="home" class="content">
                <div class="image-container">
                    <img src="https://i.pinimg.com/736x/6c/f0/89/6cf089effa29ceeb8e7bbe4df6d47d40.jpg" alt="Ellie Williams">
                    <div class="info-details">
                        <p><strong>Data de Nascimento:</strong> [Data de Nascimento]</p>
                        <p><strong>Altura:</strong> [Altura]</p>
                    </div>
                </div>
                <div class="text-container">
                    <h2>Ellie Williams</h2>
                    <h1>“</h1>
                    <p> Uma corajosa garota de quatorze anos, Ellie cresceu neste mundo rígido, sendo a rigidez a palavra que a define. Ela é uma órfã que se sobressaiu numa escola militar, cujo exército a comanda nas fronteiras de zona de quarentena. Interessada no mundo lá fora, ela é sábia diante desses anos e altamente capaz de cuidar de si própria e daqueles no entorno. Adoradora de livros, CDs e outras fontes da cultura popular, sua base de sabedoria é repleta pelo restante de um mundo que já não existe.</p>
                      <p>— Descrição oficial</p>
                    <h1>”</h1>
                </div>
            </section>

            <section id="personagens" class="content">
                <h2>enredo</h2>
                <ul>
                    <li>Ellie Williams</li>
                    <div class="text-container">
                    <p>Ellie Williams é a personagem central da série The Last of Us. Ela atua como a protagonista de The Last of Us: American Dreams,

                        sta jogável de The Last of Us, e a protagonista jogável de The Last of Us: Left Behind e The Last of Us Part II.
                        
                        Ellie cresceu órfã na zona de quarentena de Boston e frequentou uma escola militar preparatória, onde conheceu e fez amizade com Riley Abel. Quando Ellie tinha quatorze anos, a dupla foi infectada com a infecção cerebral por Cordyceps, onde Ellie descobriu que era imune. Uma amiga de sua mãe e líder dos Vaga-lumes, Marlene, acreditava que ela era a chave para a engenharia reversa de uma vacina. Marlene encarregou Joel Miller, um contrabandista, de escoltar Ellie para fora do QZ. O simples desembarque se transformou em uma jornada de um ano pela América, e os dois eventualmente formaram um vínculo estreito.
                        
                        Ao chegar aos Vagalumes em Salt Lake City, Joel aprendeu que apenas matando Ellie poderia criar a cura. Recusando-se a permitir isso, ele matou o cirurgião-chefe e escapou com Ellie para se estabelecer em Jackson, a comunidade de seu irmão em Wyoming . Nos quatro anos seguintes, Ellie ficou ressentida com Joel por salvar sua vida. Em 2038, Abby Anderson, uma ex-Vagalume e filha do cirurgião, encontrou e matou Joel. Ellie jurou vingança e perseguiu Abby até Seattle . Seus esforços foram infrutíferos, levando-a a se aposentar em uma fazenda com sua namorada Dina e seu filho JJ. Incapaz de perdoar Abby, Ellie abandonou sua família e a perseguiu mais uma vez até Santa Bárbara , apenas para poupar Abby no final. Ela voltou para Jackson mais uma vez, aceitando a morte de Joel e sua decisão de salvar sua vida.</p>
                    </div>
                </ul>
            </section>

            <section id="contato" class="content">
                <h2>Contato</h2>
                <form action="/submit_form" method="POST">
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome" required>
                    
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                    
                    <label for="mensagem">Mensagem:</label>
                    <textarea id="mensagem" name="mensagem" required></textarea>
                    
                    <input type="submit" value="Enviar">
                </form>
            </section>

            <section id="autores" class="content">
                <h2>Autores</h2>
                <p>Este site foi criado por fãs de Ellie Williams.</p>
                <ul class="author-list">
                    <li>Autor 1: Especialista em desenvolvimento web</li>
                    <li>Autor 2: Fã de "The Last of Us"</li>
                </ul>
            </section>
        </main>
    </div>
    <footer>
        <p>&copy; 2024 Ellie Williams Fan Site</p>
    </footer>
</body>
</html>
