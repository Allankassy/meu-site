<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Exclusive Store</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- AVISO +18 -->
    <div class="age-screen" id="ageScreen">
        <div class="age-box">
            <h1>+18</h1>
            <h2>Conteúdo exclusivo para adultos</h2>
            <p>Você confirma que possui 18 anos ou mais?</p>

            <button onclick="entrar()">ENTRAR</button>
        </div>
    </div>


    <!-- SITE -->
    <div id="site">

        <header>
            <div class="logo">EXCLUSIVE</div>

            <button class="menu-btn" onclick="abrirMenu()">☰</button>
        </header>


        <main>

            <section class="hero">

                <span>CONTEÚDO DIGITAL</span>

                <h1>Conteúdo exclusivo<br>para maiores de 18</h1>

                <p>
                    Escolha seu pacote e acesse conteúdos
                    digitais autorizados.
                </p>

                <button class="hero-btn">
                    VER CONTEÚDOS
                </button>

            </section>


            <!-- FAIXA DE IMAGENS -->
            <section class="marquee">

                <div class="marquee-content">

                    <img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b">
                    <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb">
                    <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1">
                    <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f">

                    <img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b">
                    <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb">

                </div>

            </section>


            <!-- PRODUTOS -->
            <section class="products">

                <h2>Conteúdos disponíveis</h2>

                <div class="grid">


                    <div class="card">

                        <div class="card-image">
                            <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f">
                        </div>

                        <div class="card-content">

                            <h3>Pacote Exclusive</h3>

                            <p>
                                Conteúdo digital exclusivo para adultos.
                            </p>

                            <strong>R$ 37</strong>

                            <button onclick="comprar('Pacote Exclusive')">
                                COMPRAR
                            </button>

                        </div>

                    </div>


                    <div class="card">

                        <div class="card-image">
                            <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1">
                        </div>

                        <div class="card-content">

                            <h3>Premium Pack</h3>

                            <p>
                                Conteúdo exclusivo e autorizado.
                            </p>

                            <strong>R$ 57</strong>

                            <button onclick="comprar('Premium Pack')">
                                COMPRAR
                            </button>

                        </div>

                    </div>


                    <div class="card">

                        <div class="card-image">
                            <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb">
                        </div>

                        <div class="card-content">

                            <h3>VIP Collection</h3>

                            <p>
                                Coleção digital para maiores de 18.
                            </p>

                            <strong>R$ 100</strong>

                            <button onclick="comprar('VIP Collection')">
                                COMPRAR
                            </button>

                        </div>

                    </div>


                    <div class="card">

                        <div class="card-image">
                            <img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b">
                        </div>

                        <div class="card-content">

                            <h3>Ultimate Pack</h3>

                            <p>
                                Coleção premium exclusiva.
                            </p>

                            <strong>R$ 150</strong>

                            <button onclick="comprar('Ultimate Pack')">
                                COMPRAR
                            </button>

                        </div>

                    </div>

                </div>

            </section>


            <!-- PAGAMENTO -->
            <section class="payments">

                <h2>Formas de pagamento</h2>

                <div class="payment-list">

                    <span>PIX</span>
                    <span>Cartão</span>
                    <span>Mercado Pago</span>
                    <span>PayPal</span>

                </div>

            </section>

        </main>


        <footer>

            <h3>EXCLUSIVE</h3>

            <p>Conteúdo digital para maiores de 18 anos.</p>

            <div class="footer-links">
                <a href="#">Termos</a>
                <a href="#">Privacidade</a>
                <a href="#">Contato</a>
            </div>

            <small>
                © 2026 Exclusive Store
            </small>

        </footer>

    </div>


    <script src="script.js"></script>

</body>
</html>
