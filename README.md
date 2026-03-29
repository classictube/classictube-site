<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClassicTube | Digital Restoration & TITAN Project</title>
    <style>
        :root {
            --primary-red: #FF0000;
            --dark-bg: #0a0a0a;
            --card-bg: #161616;
            --text-white: #ffffff;
            --text-gray: #b0b0b0;
        }

        /* Strict Design Rule: No Rounded Corners */
        * { margin: 0; padding: 0; box-sizing: border-box; border-radius: 0 !important; }

        body { background-color: var(--dark-bg); color: var(--text-white); font-family: 'Segoe UI', Tahoma, sans-serif; line-height: 1.6; overflow-x: hidden; }

        .container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }

        /* Navigation */
        nav { padding: 30px 0; display: flex; align-items: center; border-bottom: 1px solid #222; justify-content: space-between; }
        .logo-group { display: flex; align-items: center; }
        .logo-box { width: 45px; height: 45px; background: var(--primary-red); display: flex; align-items: center; justify-content: center; font-weight: bold; font-size: 28px; margin-right: 15px; }

        /* Hero Section */
        .hero { padding: 100px 0; text-align: center; border-bottom: 1px solid #222; background: radial-gradient(circle at center, #1a0000 0%, #0a0a0a 100%); }
        .hero h1 { font-size: 4rem; letter-spacing: -2px; margin-bottom: 10px; text-transform: uppercase; font-weight: 900; }
        .hero .sub-text { font-style: italic; color: var(--primary-red); font-size: 1.2rem; margin-bottom: 25px; display: block; }
        .hero .slogan { font-size: 1.4rem; font-weight: bold; margin-bottom: 30px; border: 1px solid var(--primary-red); display: inline-block; padding: 10px 20px; }

        /* Features Section */
        .section-label { color: var(--primary-red); font-weight: bold; text-transform: uppercase; letter-spacing: 2px; margin-bottom: 40px; text-align: center; display: block; }
        .features { padding: 80px 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 20px; }
        .feature-card { background: var(--card-bg); padding: 40px; border: 1px solid #222; transition: all 0.3s; position: relative; }
        .feature-card:hover { border-color: var(--primary-red); background: #1a1a1a; }
        .feature-card h3 { color: var(--primary-red); margin-bottom: 15px; font-size: 1rem; text-transform: uppercase; letter-spacing: 1px; }

        /* TITAN Project Section */
        .titan { padding: 100px 60px; background: #000; border: 2px dashed #333; margin: 60px 0; position: relative; }
        .titan h2 { font-size: 3rem; margin-bottom: 25px; text-transform: uppercase; }
        .titan .vision-quote { color: var(--primary-red); font-weight: bold; margin-bottom: 30px; font-size: 1.3rem; border-left: 4px solid var(--primary-red); padding-left: 20px; }
        .titan-content { color: var(--text-gray); max-width: 850px; font-size: 1.1rem; }
        .character-names { margin-top: 30px; color: var(--white); font-weight: bold; letter-spacing: 1px; }

        /* Support / Donate Section */
        .donate { padding: 100px 0; text-align: center; border: 1px solid var(--primary-red); background: linear-gradient(45deg, #0a0a0a 0%, #1a0000 100%); margin-bottom: 60px; }
        .donate h3 { font-size: 2rem; text-transform: uppercase; margin-bottom: 20px; }
        .donate-btn { 
            display: inline-block; background: var(--primary-red); color: white; padding: 25px 60px; 
            text-decoration: none; font-weight: bold; font-size: 1.3rem; margin-top: 40px; 
            transition: 0.3s; text-transform: uppercase; border: 2px solid var(--primary-red);
        }
        .donate-btn:hover { background: transparent; color: var(--primary-red); }

        /* Footer */
        footer { padding: 60px 0; text-align: center; border-top: 1px solid #222; color: #555; }
        .contact-mail { color: var(--primary-red); text-decoration: none; font-weight: bold; }
    </style>
</head>
<body>

<div class="container">
    <nav>
        <div class="logo-group">
            <div class="logo-box">C</div>
            <h2>ClassicTube v1.0</h2>
        </div>
        <div style="font-size: 0.8rem; letter-spacing: 1px; color: #666;">EST. 2026 | BURIGAGARIN</div>
    </nav>

    <section class="hero">
        <span class="sub-text">"Simplicity is the ultimate sophistication."</span>
        <h1>Digital Restoration</h1>
        <div class="slogan">THE 2000s YOUTUBE EXPERIENCE</div>
        <p style="max-width: 750px; margin: 20px auto; color: var(--text-gray); font-size: 1.1rem;">
            Silencing the chaotic noise of today's internet to bring back focus to a pure viewing experience. 
            Restoring the aesthetic codes of the early 2000s—built for the speed of tomorrow.
        </p>
    </section>

    <span class="section-label">// System Features</span>
    <div class="features">
        <div class="feature-card">
            <h3>Shorts Purge</h3>
            <p>Automatically removes all Shorts videos, tabs, and shelves from your digital environment.</p>
        </div>
        <div class="feature-card">
            <h3>Zero Distraction</h3>
            <p>Live chat windows and cluttered sidebars are hidden to preserve your focus.</p>
        </div>
        <div class="feature-card">
            <h3>Sharp Edge UI</h3>
            <p>Modern rounded corners are eliminated. Experience the raw, sharp-edged interface of the golden age.</p>
        </div>
        <div class="feature-card">
            <h3>Algorithm Cleanse</h3>
            <p>Purges irrelevant category chips (Gaming, Live, etc.) for a truly arınmış (arundırılmış) feed.</p>
        </div>
    </div>

    <section class="titan">
        <p class="vision-quote">"The past is not gone; it is simply waiting to be redesigned."</p>
        <h2>TITAN Project: Rebuilding 2599</h2>
        <div class="titan-content">
            <p>I am <strong>burigagarin</strong>. My journey as a <strong>DIT</strong> (Digital Imaging Technician) in modern cinema has led me to a vision that extends far beyond the horizon.</p>
            <br>
            <p>TITAN is more than a manga animation project; it is a cinematic exploration where ancient spirits meet futuristic technology. In the year 2599, above the clouds of a rebuilt world, humanity and machines exist in a delicate balance.</p>
            <p class="character-names">JD // GESAR // ELLON // MANAS</p>
        </div>
    </section>

    <section class="donate">
        <h3>Support the Rise of Titan</h3>
        <p>ClassicTube is 100% free and ad-free. It is a bridge to the future.</p>
        <p style="color: var(--text-gray); margin-top: 10px;">Every contribution fuels the visual research and production of the 2599 universe.</p>
        
        <a href="YOUR_PAYTR_LINK" class="donate-btn">Support the Project for $1</a>
    </section>

    <footer>
        <p>Technical Support & Inquiries: <a href="mailto:support@classictube.io" class="contact-mail">support@classictube.io</a></p>
        <p style="margin-top: 25px; font-size: 0.7rem; text-transform: uppercase; letter-spacing: 2px;">
            &copy; 2026 ClassicTube & TITAN Project. Rebuilding the past to feed the future.
        </p>
    </footer>
</div>

</body>
</html>
