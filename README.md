# IsabellePillarPortfolio<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio | Isabelle Pilar</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: #f0f0f0; /* Cor de fundo da borda fora do design */
            font-family: sans-serif;
        }
        .container {
            max-width: 1200px; /* Limita a largura em telas muito grandes */
            margin: 0 auto;
            background: #fff;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }
        /* Ajuste para esconder o link de rodapé do Canva se desejar */
        .canva-link {
            display: block;
            text-align: center;
            padding: 10px;
            font-size: 12px;
            color: #666;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <div class="container">
        <div style="position: relative; width: 100%; height: 0; padding-top: 1161.8594%;
        padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 0; margin-bottom: 0; overflow: hidden;
        border-radius: 0; will-change: transform;">
        <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
            src="https://www.canva.com/design/DAG--J4t4nQ/QbAuE6S20zhaThpR8ZJhpQ/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
        </iframe>
        </div>
        </div>

    <a href="https://www.canva.com/design/DAG--J4t4nQ/QbAuE6S20zhaThpR8ZJhpQ/view" target="_blank" rel="noopener" class="canva-link">
        Abrir Portfólio em Tela Cheia
    </a>
/* --- RESET E BÁSICO --- */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    /* Fonte maior por padrão para facilitar leitura */
    font-family: 'Lato', sans-serif;
    font-size: 18px; 
    line-height: 1.6;
    color: #333;
    background-color: #fdfdfd;
    overflow-x: hidden; /* Evita rolagem lateral indesejada */
}

/* --- TIPOGRAFIA RESPONSIVA --- */
h1, h2, h3, .logo {
    font-family: 'Playfair Display', serif;
    color: #2c2c2c;
}

h1 { font-size: 3rem; line-height: 1.2; }
h2 { font-size: 2.2rem; margin-bottom: 25px; }
h3 { font-size: 1.5rem; }
p { margin-bottom: 1.5em; }

/* --- NAVEGAÇÃO --- */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 5%;
    background: #fff;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo { font-size: 1.2rem; font-weight: bold; text-transform: uppercase; }

.menu { display: flex; list-style: none; gap: 20px; }
.menu a { text-decoration: none; color: #555; font-size: 1rem; }

/* --- HEADER / HERO --- */
header {
    min-height: 80vh; /* Altura mínima flexível */
    padding: 60px 20px;
    background: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

/* --- SEÇÕES --- */
section { 
    padding: 60px 20px; /* Espaçamento interno padrão */
}

.container { 
    max-width: 1000px; 
    margin: 0 auto; 
}

/* --- GRID DE PROJETOS --- */
.grid {
    display: grid;
    /* Isso faz os itens se adaptarem sozinhos: 1 coluna no celular, 2 ou 3 no PC */
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

.card {
    background: #fff;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
}

.foto-placeholder {
    width: 100%;
    height: 220px;
    background-color: #e0e0e0;
    border-radius: 8px;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #888;
}

/* --- BOTÕES --- */
.btn {
    display: inline-block;
    padding: 15px 35px; /* Botão maior para toque */
    background: #2c2c2c;
    color: #fff;
    text-decoration: none;
    border-radius: 50px;
    font-weight: bold;
    margin-top: 10px;
}

/* =========================================
   OTIMIZAÇÃO EXCLUSIVA PARA CELULAR (MOBILE)
   ========================================= */
@media (max-width: 768px) {
    
    body {
        font-size: 16px; /* Tamanho base ideal para leitura em tela pequena */
    }

    /* Ajuste do Menu para não quebrar */
    nav {
        flex-direction: column;
        padding: 15px;
    }
    .menu {
        margin-top: 15px;
        gap: 15px;
        font-size: 0.9rem;
        flex-wrap: wrap; /* Permite que os links desçam se faltar espaço */
        justify-content: center;
    }

    /* Títulos ficam grandes, mas não gigantes */
    header h1 {
        font-size: 2.2rem; 
    }
    
    /* Aproveita melhor a largura da tela */
    section {
        padding: 40px 5%; /* Menos borda lateral para o texto caber mais */
    }

    /* Aumenta a legibilidade dos textos longos */
    p {
        text-align: left; /* Texto justificado ou esquerda é melhor que centralizado no mobile */
        line-height: 1.7; /* Mais espaço entre linhas para não embaralhar */
    }

    /* Botões ocupam a largura total para facilitar o clique com o dedo */
    .btn {
        width: 100%;
        text-align: center;
        padding: 18px;
    }

    /* Ajuste dos Cards de projeto */
    .grid {
        grid-template-columns: 1fr; /* Força 1 coluna única */
    }
}
</body>
</html>