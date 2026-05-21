<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One Thread | Our Story</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
        body { color: #333; background-color: #fcfbf9; line-height: 1.6; }
        header { display: flex; justify-content: space-between; padding: 20px 10%; background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.05); position: sticky; top: 0; z-index: 100; }
        .logo { font-size: 24px; font-weight: 700; text-transform: uppercase; letter-spacing: 2px; }
        .logo span { color: #8c7662; }
        
        .section { padding: 80px 10%; text-align: center; }
        h2 { font-size: 32px; margin-bottom: 40px; color: #111; }

        /* Family Section Layout */
        .family-container { display: flex; flex-wrap: wrap; justify-content: center; gap: 30px; }
        .family-card { background: white; padding: 20px; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.05); width: 280px; }
        .family-photo { width: 100%; height: 300px; background-color: #eee; border-radius: 4px; object-fit: cover; margin-bottom: 15px; }
        .family-card h3 { color: #8c7662; margin-bottom: 5px; }
        .family-card p { font-size: 14px; color: #777; }

        footer { background: #111; color: #fff; text-align: center; padding: 30px; margin-top: 50px; }
    </style>
</head>
<body>

    <header>
        <div class="logo">One <span>Thread</span></div>
    </header>

    <section class="section">
        <h2>The Hearts Behind One Thread</h2>
        <div class="family-container">
            
            <div class="family-card">
                <img src="YOUR_PHOTO_URL" alt="Raghvan Koli" class="family-photo">
                <h3>Raghvan Koli</h3>
                <p>Founder & Visionary</p>
            </div>

            <div class="family-card">
                <img src="FATHER_PHOTO_URL" alt="Raghunath koli" class="family-photo">
                <h3>[Father's Name]</h3>
                <p>The Inspiration</p>
            </div>

            <div class="family-card">
                <img src="MOTHER_PHOTO_URL" alt="Sunita Koli" class="family-photo">
                <h3>[Mother's Name]</h3>
                <p>The Strength</p>
            </div>

        </div>
    </section>

    <footer>
        <p>&copy; 2026 One Thread. A Family Legacy.</p>
    </footer>

</body>
</html>
