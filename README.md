# octocat.github.io <!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Minha Loja Online</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f5f5;
}

header{
    background:#0066cc;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    background:#004c99;
    padding:10px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

.banner{
    background:#ddd;
    text-align:center;
    padding:60px 20px;
}

.banner h1{
    margin-bottom:10px;
}

.produtos{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    padding:30px;
}

.produto{
    background:white;
    width:300px;
    margin:15px;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.produto img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.produto-info{
    padding:15px;
}

.preco{
    color:green;
    font-size:24px;
    margin:10px 0;
}

.botao{
    display:block;
    text-align:center;
    background:#28a745;
    color:white;
    padding:12px;
    text-decoration:none;
    border-radius:5px;
}

.contato{
    background:white;
    padding:30px;
    text-align:center;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<header>
    <h1>MINHA LOJA ONLINE</h1>
    <p>Os melhores produtos para você</p>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#">Promoções</a>
    <a href="#">Contato</a>
</nav>

<section class="banner">
    <h1>SUPER PROMOÇÃO</h1>
    <p>Aproveite nossos descontos exclusivos!</p>
</section>

<section class="produtos">

    <div class="produto">
        <img src="https://via.placeholder.com/300x220" alt="Produto">
        <div class="produto-info">
            <h2>Produto 1</h2>
            <p>Descrição do produto.</p>
            <div class="preco">R$ 99,90</div>
            <a class="botao" href="#">Comprar</a>
        </div>
    </div>

    <div class="produto">
        <img src="https://via.placeholder.com/300x220" alt="Produto">
        <div class="produto-info">
            <h2>Produto 2</h2>
            <p>Descrição do produto.</p>
            <div class="preco">R$ 149,90</div>
            <a class="botao" href="#">Comprar</a>
        </div>
    </div>

    <div class="produto">
        <img src="https://via.placeholder.com/300x220" alt="Produto">
        <div class="produto-info">
            <h2>Produto 3</h2>
            <p>Descrição do produto.</p>
            <div class="preco">R$ 199,90</div>
            <a class="botao" href="#">Comprar</a>
        </div>
    </div>

</section>

<section class="contato">
    <h2>Contato</h2>
    <p>WhatsApp: (11) 99999-9999</p>
    <p>Email: contato@minhaloja.com</p>
</section>

<footer>
    © 2026 Minha Loja Online - Todos os direitos reservados.
</footer>

</body>
</html><a class="botao"
href="https://wa.me/5511999999999">
Comprar via WhatsApp
</a>
