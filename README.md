<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>United Boys F.C. - Officiële Website</title>
    <style>
        :root {
            --primary-color: #1a3d7c;
            --secondary-color: #d52b1e;
            --accent-color: #ffd700;
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }
        body { background: #f5f5f5; color: #333; line-height: 1.6; }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        
        header { background: var(--primary-color); color: white; padding: 20px 0; }
        .logo { text-align: center; }
        .logo h1 { font-size: 2.5rem; margin-bottom: 10px; }
        nav { text-align: center; margin-top: 15px; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        
        .hero { 
            background: linear-gradient(rgba(26, 61, 124, 0.8), rgba(26, 61, 124, 0.9));
            color: white; padding: 100px 0; text-align: center;
        }
        .hero h2 { font-size: 3rem; margin-bottom: 20px; }
        .btn { 
            background: var(--secondary-color); color: white; padding: 15px 35px;
            text-decoration: none; border-radius: 30px; display: inline-block; 
            margin-top: 20px; font-weight: bold; font-size: 1.1rem;
        }
        
        section { padding: 80px 0; }
        .section-title { text-align: center; margin-bottom: 50px; }
        .section-title h2 { 
            color: var(--primary-color); font-size: 2.5rem; 
            position: relative; display: inline-block; padding-bottom: 15px;
        }
        .section-title h2:after {
            content: ''; position: absolute; bottom: 0; left: 50%; 
            transform: translateX(-50%); width: 80px; height: 4px;
            background: var(--secondary-color);
        }
        
        .teams-grid { 
            display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); 
            gap: 30px; 
        }
        .team-card { 
            background: white; padding: 30px; border-radius: 10px; 
            box-shadow: 0 5px 15px rgba(0,0,0,0.1); text-align: center;
        }
        .team-card h3 { color: var(--primary-color); margin-bottom: 15px; font-size: 1.5rem; }
        
        footer { background: #222; color: white; padding: 50px 0 20px; text-align: center; }
        .contact-info { margin-bottom: 30px; }
        .contact-info h3 { margin-bottom: 20px; color: var(--accent-color); }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>United Boys F.C.</h1>
                <p>⚽ Jeugdvoetbal met passie sinds 1990 ⚽</p>
            </div>
            <nav>
                <a href="#home">Home</a>
                <a href="#teams">Teams</a>
                <a href="#wedstrijden">Wedstrijden</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <section class="hero" id="home">
        <div class="container">
            <h2>Welkom bij United Boys F.C.</h2>
            <p>De trots van de regio! Al 30+ jaar dé jeugdvoetbalclub voor jongens van 6-18 jaar.</p>
            <a href="#contact" class="btn">Word lid van ons team!</a>
        </div>
    </section>

    <section id="teams">
        <div class="container">
            <div class="section-title">
                <h2>Onze Teams</h2>
            </div>
            <div class="teams-grid">
                <div class="team-card">
                    <h3>Pupillen (6-8 jaar)</h3>
                    <p><strong>Training:</strong> Dinsdag 16:30-17:30</p>
                    <p><strong>Coach:</strong> Jan de Vries</p>
                    <p>Kennismaking met voetbal en veel plezier!</p>
                </div>
                <div class="team-card">
                    <h3>Junioren (9-12 jaar)</h3>
                    <p><strong>Training:</strong> Woensdag 17:00-18:30</p>
                    <p><strong>Coach:</strong> Mohamed El Amrani</p>
                    <p>Techniek ontwikkeling en eerste competitie</p>
                </div>
                <div class="team-card">
                    <h3>Aspiranten (13-16 jaar)</h3>
                    <p><strong>Training:</strong> Donderdag 18:30-20:00</p>
                    <p><strong>Coach:</strong> Thomas Jansen</p>
                    <p>Voetbal op hoger niveau met tactiek</p>
                </div>
            </div>
        </div>
    </section>

    <section id="wedstrijden" style="background: #f8f9fa;">
        <div class="container">
            <div class="section-title">
                <h2>Komende Wedstrijden</h2>
            </div>
            <div class="teams-grid">
                <div class="team-card">
                    <h3>Za 15 Juni - 10:30u</h3>
                    <p><strong>United Boys JO11</strong> vs. SV Rijswijk</p>
                    <p>📍 Sportpark De Biezen, Velden</p>
                </div>
                <div class="team-card">
                    <h3>Za 15 Juni - 13:00u</h3>
                    <p><strong>United Boys JO15</strong> vs. VV Susteren</p>
                    <p>📍 Sportpark De Biezen, Velden</p>
                </div>
                <div class="team-card">
                    <h3>Zo 16 Juni - 14:30u</h3>
                    <p><strong>United Boys MO17</strong> vs. RKSV Minor</p>
                    <p>📍 Sportpark Minor, Nijmegen</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact</h2>
            </div>
            <div class="contact-info">
                <h3>📞 06-12345678</h3>
                <h3>✉️ info@unitedboysfc.nl</h3>
                <h3>📍 Sportpark De Biezen, Voetbalstraat 12, Velden</h3>
                <a href="mailto:info@unitedboysfc.nl" class="btn">Stuur ons een e-mail</a>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 United Boys F.C. - Alle rechten voorbehouden</p>
            <p style="margin-top: 10px; color: #ccc;">Samen sterk, samen United!</p>
        </div>
    </footer>
</body>
</html>
