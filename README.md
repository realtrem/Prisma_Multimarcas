<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prisma Multimarcas</title>
    <style>
        /* ====== Reset básico ====== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #111; /* Preto */
            color: #fff;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* ====== Cabeçalho ====== */
        header {
            background-color: #FF0000; /* Vermelho */
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 2em;
            letter-spacing: 2px;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            margin: 0 15px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            opacity: 0.7;
        }

        /* ====== Banner ====== */
        .banner {
            background-color: #222;
            text-align: center;
            padding: 60px 20px;
        }

        .banner h2 {
            font-size: 2.5em;
            color: #FF0000;
        }

        .banner p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        /* ====== Seção de produtos ====== */
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            padding: 40px 20px;
        }

        .product {
            background-color: #222;
            padding: 15px;
            border: 2px solid #FF0000;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product:hover {
            transform: scale(1.05);
            box-shadow: 0 0 10px #FF0000;
        }

        .product img {
            width: 100%;
            border-radius: 8px;
        }

        .product h3 {
            margin: 10px 0 5px 0;
            color: #FF0000;
        }

        .product p {
            font-size: 0.9em;
            margin-bottom: 10px;
        }

        .product button {
            background-color: #FF0000;
            color: #fff;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
            font-weight: bold;
            transition: 0.3s;
        }

        .product button:hover {
            background-color: #cc0000;
        }

        /* ====== Footer ====== */
        footer {
            background-color: #111;
            text-align: center;
            padding: 20px;
            border-top: 2px solid #FF0000;
            margin-top: 40px;
        }

        footer a {
            margin: 0 10px;
            color: #FF0000;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- Cabeçalho -->
    <header>
        <h1>Prisma Multimarcas</h1>
        <nav>
            <a href="#masculino">Masculino</a>
            <a href="#feminino">Feminino</a>
            <a href="#eletronicos">Eletrônicos</a>
            <a href="#casa">Casa & Decoração</a>
        </nav>
    </header>

    <!-- Banner -->
    <section class="banner">
        <h2>Moda & Produtos para Todos!</h2>
        <p>Roupas, acessórios, gadgets e muito mais.</p>
    </section>

    <!-- Produtos Masculinos -->
    <section id="masculino" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300x300.png?text=Camiseta+Masculina" alt="Camiseta Masculina">
            <h3>Camiseta Masculina</h3>
            <p>Estilo e conforto para o dia a dia.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x300.png?text=Calça+Masculina" alt="Calça Masculina">
            <h3>Calça Masculina</h3>
            <p>Elegância e qualidade.</p>
            <button>Comprar</button>
        </div>
    </section>

    <!-- Produtos Femininos -->
    <section id="feminino" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300x300.png?text=Vestido+Feminino" alt="Vestido Feminino">
            <h3>Vestido Feminino</h3>
            <p>Moda que valoriza seu estilo.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x300.png?text=Bolsa+Feminina" alt="Bolsa Feminina">
            <h3>Bolsa Feminina</h3>
            <p>Praticidade e charme.</p>
            <button>Comprar</button>
        </div>
    </section>

    <!-- Eletrônicos -->
    <section id="eletronicos" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300x300.png?text=Fone+Bluetooth" alt="Fone Bluetooth">
            <h3>Fone Bluetooth</h3>
            <p>Som de qualidade e sem fio.</p>
            <button>Comprar</button>
        </div>
    </section>

    <!-- Casa & Decoração -->
    <section id="casa" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300x300.png?text=Vaso+Decorativo" alt="Vaso Decorativo">
            <h3>Vaso Decorativo</h3>
            <p>Deixe sua casa mais elegante.</p>
            <button>Comprar</button>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Siga-nos nas redes sociais:</p>
        <a href="#">Instagram</a> | <a href="#">WhatsApp</a>
        <p>© 2025 Prisma Multimarcas</p>
    </footer>

</body>
</html>
