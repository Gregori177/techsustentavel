# techsustentavel
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Tecnologia e Sustentabilidade | TechSustentável</title>

    <link rel="stylesheet" href="../CSS/style.css">
</head>

<body>

    <header>
        <h1> TechSustentável</h1>
        <p>Tecnologia ajudando a construir um futuro melhor</p>
    </header>

    <nav>
        <a href="index.html">Início</a>
        <a href="tecnologia.html">Tecnologia</a>
        <a href="projetos.html">Projetos</a>
        <a href="acoes.html">Ações Sustentáveis</a>
    </nav>

    <main>

        <section class="introducao">
            <h2>Tecnologia e Sustentabilidade</h2>

            <p>
                A tecnologia pode ser uma grande aliada na preservação
                do meio ambiente. Novas soluções permitem economizar
                recursos, produzir energia limpa e reduzir impactos
                ambientais.
            </p>

            <p>
                Conheça algumas tecnologias que contribuem para um
                futuro mais sustentável.
            </p>
        </section>

        <section class="tecnologias">

            <article class="card">
                <div class="icone"></div>

                <h2>Energia Solar</h2>

                <p>
                    Os painéis solares transformam a luz do Sol em
                    energia elétrica. Essa tecnologia utiliza uma
                    fonte renovável de energia e ajuda a reduzir
                    impactos ambientais.
                </p>
            </article>

            <article class="card">
                <div class="icone"></div>

                <h2>Internet das Coisas (IoT)</h2>

                <p>
                    Sensores e dispositivos inteligentes podem
                    controlar iluminação, temperatura e consumo de
                    energia, evitando desperdícios em casas, escolas
                    e empresas.
                </p>
            </article>

            <article class="card">
                <div class="icone"></div>

                <h2>Inteligência Artificial</h2>

                <p>
                    A inteligência artificial pode analisar informações
                    para identificar desperdícios e melhorar o uso de
                    água, energia e outros recursos naturais.
                </p>
            </article>

        </section>

    </main>

    <footer>
        <p>
            TechSustentável — Ideias Digitais para um Futuro Melhor 
        </p>
    </footer>

</body>

</html>



#CSS#
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f8f5;
    color: #333;
    line-height: 1.6;
}

/* Cabeçalho */

header {
    background-color: #1b5e20;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

header h1 {
    margin-bottom: 10px;
}

/* Menu */

nav {
    background-color: #2e7d32;
    text-align: center;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

/* Conteúdo principal */

main {
    max-width: 1000px;
    margin: 30px auto;
    padding: 20px;
}

.introducao {
    text-align: center;
    margin-bottom: 30px;
}

.introducao h2 {
    color: #1b5e20;
    margin-bottom: 15px;
}

.introducao p {
    margin-bottom: 10px;
}

/* Tecnologias */

.tecnologias {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

/* Cards */

.card {
    background-color: white;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.card:hover {
    transform: translateY(-5px);
    transition: 0.3s;
}

.card h2 {
    color: #2e7d32;
    margin-bottom: 10px;
}

.icone {
    font-size: 50px;
    margin-bottom: 15px;
}

/* Rodapé */

footer {
    background-color: #1b5e20;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}
