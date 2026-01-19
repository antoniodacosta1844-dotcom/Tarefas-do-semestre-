# Tarefas-do-semestre-
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <title>Lista de Tarefas</title>

    <!-- CSS INTERNO -->
    <style>
        body {
            António Da Costa
        }

        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background-color: #555;
            padding: 10px;
        }

        nav a {
            color: white;
            margin-right: 15px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
            background-color: white;
            margin: 15px;
            border-radius: 5px;
        }

        h2 {
            color: #333;
        }
    </style>
</head>

<body>

<header>
    <h1>Programa de Tarefas</h1>
</header>

<nav>
    <a href="#t1">T1</a>
    <a href="#t2">T2</a>
    <a href="#t3">T3</a>
    <a href="#t4">T4</a>
    <a href="#t5">T5</a>
</nav>

<!-- T1 -->
<section id="t1">
    <h2>T1 – Introdução ao CSS</h2>

    <p><strong>CSS</strong> (Cascading Style Sheets) é usado para dar estilo às páginas HTML,
    como cores, tamanhos, fontes e layout.</p>

    <h3>Tipos de CSS</h3>

    <h4>1. CSS Inline</h4>
    <p style="color: blue;">
        Este texto usa CSS inline (dentro da própria tag).
    </p>

    <h4>2. CSS Interno</h4>
    <p>
        O CSS interno fica dentro da tag <code>&lt;style&gt;</code> no cabeçalho do HTML.
    </p>

    <h4>3. CSS Externo</h4>
    <p>
        O CSS externo fica num arquivo separado (.css) e é ligado ao HTML.
    </p>

    <p>Exemplo de ligação:</p>
    <code>
        &lt;link rel="stylesheet" href="estilo.css"&gt;
    </code>
</section>

<!-- T2 -->
<section id="t2">
    <h2>T2</h2>
    <p>Conteúdo da tarefa T2.</p>
</section>

<!-- T3 -->
<section id="t3">
    <h2>T3</h2>
    <p>Conteúdo da tarefa T3.</p>
</section>

<!-- T4 -->
<section id="t4">
    <h2>T4</h2>
    <p>Conteúdo da tarefa T4.</p>
</section>

<!-- T5 -->
<section id="t5">
    <h2>T5</h2>
    <p>Conteúdo da tarefa T5.</p>
</section>

</body>
</html>