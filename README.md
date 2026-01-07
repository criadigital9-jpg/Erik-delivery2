<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Depósito Prime</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #0d0d0d;
    color: #fff;
}

header {
    background: linear-gradient(135deg, #000, #111);
    padding: 20px;
    display: flex;
    align-items: center;
    gap: 15px;
}

header img {
    height: 50px;
}

header div {
    line-height: 1.2;
}

header p {
    font-size: 14px;
    color: #aaa;
}

.catalogo {
    padding: 20px;
}

.categoria {
    font-size: 22px;
    margin: 20px 0 10px;
    border-left: 4px solid #00ff88;
    padding-left: 10px;
}

.produto {
    display: flex;
    background: #161616;
    border-radius: 12px;
    overflow: hidden;
    margin-bottom: 15px;
}

.produto img {
    width: 120px;
    object-fit: cover;
}

.info {
    padding: 12px;
    flex: 1;
}

.info h3 {
    margin: 0;
}

.info p {
    font-size: 14px;
    color: #aaa;
    margin: 5px 0;
}

.preco {
    font-size: 20px;
    color: #00ff88;
    margin: 8px 0;
}

.whatsapp {
    display: inline-block;
    background: #25D366;
    color: #fff;
    padding: 10px 14px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
    font-size: 14px;
}

footer {
    text-align: center;
    padding: 15px;
    background: #000;
    font-size: 13px;
    color: #777;
}
</style>
</head>

<body>

<header>
    <img src="logo.svg" alt="Logo Depósito Prime">
    <div>
        <strong>Depósito Prime</strong>
        <p>Catálogo • Pedido direto no WhatsApp</p>
    </div>
</header>

<section class="catalogo">

    <div class="categoria">🍺 Cervejas</div>

    <div class="produto">
        <img src="https://images.unsplash.com/photo-1608270586620-248524c67de9">
        <div class="info">
            <h3>Heineken 600ml</h3>
            <p>Gelada • Retornável</p>
            <div class="preco">R$ 12,00</div>
            <a class="whatsapp" href="https://wa.me/5521979058213?text=Quero%20Heineken%20600ml">Pedir no WhatsApp</a>
        </div>
    </div>

    <div class="produto">
        <img src="https://images.unsplash.com/photo-1622482182252-42c4b16a3b52">
        <div class="info">
            <h3>Skol Lata 350ml</h3>
            <p>Clássica</p>
            <div class="preco">R$ 4,50</div>
            <a class="whatsapp" href="https://wa.me/5521979058213?text=Quero%20Skol%20350ml">Pedir no WhatsApp</a>
        </div>
    </div>

    <div class="categoria">🥃 Destilados</div>

    <div class="produto">
        <img src="https://images.unsplash.com/photo-1587017539504-67cfbddac569">
        <div class="info">
            <h3>Vodka Smirnoff 1L</h3>
            <p>Original</p>
            <div class="preco">R$ 45,00</div>
            <a class="whatsapp" href="https://wa.me/5521979058213?text=Quero%20Vodka%20Smirnoff%201L">Pedir no WhatsApp</a>
        </div>
    </div>

</section>

<footer>
    © 2026 • Depósito Prime • Delivery rápido
</footer>

</body>
</html>
