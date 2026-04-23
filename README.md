<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KAFÉ-ART ALGERIE</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Tajawal', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #fef9f0;
            color: #3e2a1f;
            line-height: 1.6;
        }
        header {
            background: #2c1a0e;
            color: #f5e2c5;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            border-bottom: 4px solid #c9a87b;
        }
        .logo h1 { font-size: 1.8rem; letter-spacing: 1px; }
        .logo p { font-size: 0.8rem; color: #e0c8a8; }
        nav a {
            color: #f5e2c5;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover { color: #e0b07f; }
        .hero {
            background: linear-gradient(rgba(44, 26, 14, 0.8), rgba(44, 26, 14, 0.8)), url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?ixlib=rb-4.0.3&auto=format&fit=crop&w=1170&q=80');
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 4rem 2rem;
            color: white;
        }
        .hero h2 { font-size: 2.5rem; margin-bottom: 1rem; }
        .hero p { font-size: 1.2rem; max-width: 700px; margin: 0 auto 2rem auto; }
        .btn {
            background: #c9a87b;
            color: #2c1a0e;
            padding: 0.8rem 1.8rem;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            transition: 0.3s;
            display: inline-block;
        }
        .btn:hover { background: #b58b58; transform: scale(1.02); }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 3rem 2rem;
            background: #fff6ed;
            gap: 2rem;
        }
        .card {
            background: white;
            border-radius: 20px;
            padding: 1.8rem;
            text-align: center;
            flex: 1;
            min-width: 220px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: 0.3s;
        }
        .card i {
            font-size: 2.5rem;
            color: #a5713c;
            margin-bottom: 1rem;
        }
        .card h3 { margin-bottom: 0.8rem; }
        .pack {
            background: #e7d9cb;
            padding: 2rem;
            text-align: center;
            margin: 2rem;
            border-radius: 30px;
        }
        .pack .price {
            font-size: 2rem;
            font-weight: bold;
            color: #2c1a0e;
            background: #f5e2c5;
            display: inline-block;
            padding: 0.3rem 1.2rem;
            border-radius: 40px;
            margin: 1rem 0;
        }
        .contact-info {
            background: #2c1a0e;
            color: #f5e2c5;
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }
        .contact-info a {
            color: #e0b07f;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.2rem;
        }
        footer {
            background: #1f1209;
            color: #c2a071;
            text-align: center;
            padding: 1rem;
            font-size: 0.8rem;
        }
        @media (max-width: 700px) {
            header { flex-direction: column; text-align: center; }
            nav { margin-top: 1rem; }
            .hero h2 { font-size: 1.8rem; }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>☕ KAFÉ-ART ALGERIE</h1>
            <p>قهوة مختصة ✦ حرف يدوية جزائرية</p>
        </div>
        <nav>
            <a href="#">Accueil</a>
            <a href="#">Nos Cafés</a>
            <a href="#">Artisans</a>
            <a href="#">Boutique</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>✨ Sélection Premium ✨</h2>
        <p>Torréfaction locale, arômes authentiques • Artisanat unique: vaisselle & décoration du terroir</p>
        <a href="#" class="btn">📦 Commander maintenant</a>
        <p style="margin-top: 1rem;">🚚 Livraison express — 48 Wilayas</p>
    </section>

    <section class="features">
        <div class="card">
            <i class="fas fa-mug-hot"></i>
            <h3>Qualité & Authenticité</h3>
            <p>Grains sélectionnés, torréfiés localement pour une fraîcheur incomparable.</p>
        </div>
        <div class="card">
            <i class="fas fa-shopping-cart"></i>
            <h3>Commande En Ligne Facile</h3>
            <p>Paiement sécurisé et suivi en temps réel.</p>
        </div>
        <div class="card">
            <i class="fas fa-users"></i>
            <h3>Communauté de Kafé-Art</h3>
            <p>Rejoignez une communauté à travers 48 Wilayas.</p>
        </div>
    </section>

    <section class="pack">
        <h2>☕ Pack « Initiation »</h2>
        <p>Café de spécialité fraîchement torréfié + 1 tasse en céramique peinte à la main par des artisans algériens.</p>
        <div class="price">2 500 DZD</div>
        <p><small>Livraison incluse (Constantine, Alger, Oran et toutes les wilayas).</small></p>
        <a href="#" class="btn" style="background: #2c1a0e; color: #f5e2c5;">S'abonner mensuellement</a>
    </section>

    <section class="contact-info">
        <h3><i class="fas fa-envelope"></i> Contactez-nous</h3>
        <p>📧 <a href="mailto:kafe-art@example.com">kafe-art@example.com</a></p>
        <p>📞 <a href="tel:+213551234567">+213 5 51 23 45 67</a> (WhatsApp & Appels)</p>
        <p>📍 Bureau d'exploitation : Constantine / Alger / Oran</p>
        <p style="margin-top: 1rem;"><i class="fas fa-user-circle"></i> Propriétaire: <strong>Douâa Abbès</strong> – L3 Entrepreneurial</p>
    </section>

    <footer>
        <p>© 2026 KAFÉ-ART ALGERIE — L'alliance unique du café fraîchement torréfié et de l'artisanat local.</p>
        <p>Ceci est une démo informative | site vitrine temporaire</p>
    </footer>
</body>
</html>
