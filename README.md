<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Formulário Modelo</title>

    <style>
        /* =========================
           VARIÁVEIS DE CORES
        ========================== */

        :root {
            --cor-principal: #6a0dad;
            --cor-secundaria: #9c27b0;
            --cor-destaque: #d8b4fe;

            --cor-fundo: #f5efff;
            --cor-card: #ffffff;

            --cor-texto: #2d163b;
            --cor-texto-claro: #ffffff;

            --cor-borda: #c4a7d7;

            --sombra: 0 4px 15px rgba(80, 20, 120, 0.15);
        }

        /* =========================
           CONFIGURAÇÃO GERAL
        ========================== */

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;

            background-color: var(--cor-fundo);
            color: var(--cor-texto);
        }

        /* =========================
           HEADER
        ========================== */

        header {
            background-color: var(--cor-principal);
            color: var(--cor-texto-claro);

            padding: 30px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        header p {
            margin-bottom: 0;
        }

        /* =========================
           MENU
        ========================== */

        nav {
            background-color: var(--cor-secundaria);

            padding: 15px;
            text-align: center;
        }

        nav a {
            color: var(--cor-texto-claro);

            text-decoration: none;

            margin: 0 15px;

            font-weight: bold;
        }

        nav a:hover {
            color: var(--cor-destaque);
        }

        /* =========================
           CONTEÚDO PRINCIPAL
        ========================== */

        main {
            max-width: 900px;

            margin: 30px auto;
            padding: 20px;
        }

        /* =========================
           FORMULÁRIO
        ========================== */

        form {
            background-color: var(--cor-card);

            padding: 30px;

            border-radius: 12px;

            box-shadow: var(--sombra);
        }

        .campo {
            margin-bottom: 20px;
        }

        label {
            display: block;

            font-weight: bold;

            margin-bottom: 7px;
        }

        input {
            width: 100%;

            padding: 10px;

            border: 1px solid var(--cor-borda);

            border-radius: 6px;

            font-size: 16px;
        }

        button {
            background-color: var(--cor-principal);
            color: white;

            border: none;

            padding: 12px 25px;

            font-weight: bold;

            cursor: pointer;

            border-radius: 6px;
        }

        button:hover {
            opacity: 0.8;
        }

        /* =========================
           FOOTER
        ========================== */

        footer {
            background-color: var(--cor-principal);

            color: var(--cor-texto-claro);

            text-align: center;

            padding: 20px;

            margin-top: 40px;
        }
    </style>

</head>

<body>

    <!-- =========================
         CABEÇALHO
    ========================== -->

    <header id="inicio">

        <h1>Reclame de sua vila</h1>

        <p>Denuncie algum vizinho que está varzeando sua vila</p>

    </header>


    <!-- =========================
         MENU
    ========================== -->

    <nav>

        <a href="#inicio">Início</a>

        <a href="#formulario">Formulário</a>

        <a href="#contato">Contato</a>

    </nav>


    <!-- =========================
         CONTEÚDO PRINCIPAL
    ========================== -->

    <main>

        <form id="formulario">

            <div class="campo">

                <label>Nome</label>

                <input type="text">

            </div>


            <div class="campo">

                <label>CPF</label>

                <input type="mumber">

            </div>


            <div class="campo">

                <label>idade</label>

                <input type="number">

            </div>


            <div class="campo">

                <label>Cidade </label>

                <input type="string">

            </div>


            <div class="campo">

                <label>Rua</label>

                <input type="text">

            </div>


            <div class="campo">

                <label>Telefone</label>

                <input type="tel">

            </div>


            <div class="campo">

                <label>Nivel de gravidade que odeia o seu vizinho </label>

                <input type="range">

            </div>


            <div class="campo">

                <label>foto da casa do seu vizinho</label>

                <input type="file">

            </div>


            <button type="submit">

                Enviar

            </button>

        </form>

    </main>


    <!-- =========================
         RODAPÉ
    ========================== -->

    <footer id="contato">

        <p>
            Exemplo de formulário HTML
        </p>

        <p>
            Desenvolvido para fins educacionais
        </p>

    </footer>

</body>

</html>






