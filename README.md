# KELUARGA-KECIL-XI-IPA
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keluarga Kecil XI-IPA</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0 0 60px 0; /* Tambahan padding bawah untuk menghindari overlap dengan footer fixed */
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
            overflow-x: hidden;
        }
        header {
            padding: 50px 20px;
            background: rgba(0, 0, 0, 0.3);
            border-bottom: 2px solid rgba(255, 255, 255, 0.5);
        }
        h1 {
            font-size: 3em;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            animation: fadeIn 2s ease-in-out;
        }
        .description {
            font-size: 1.2em;
            margin: 20px 0;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.6;
            animation: slideUp 2s ease-in-out 0.5s both;
        }
        .members {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 40px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }
        .member {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: fadeInUp 1s ease-in-out both;
        }
        .member:nth-child(odd) {
            animation-delay: 0.1s;
        }
        .member:nth-child(even) {
            animation-delay: 0.2s;
        }
        .member:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        }
        .member-name {
            font-size: 1.2em;
            margin-top: 10px;
            text-decoration: none;
            color: white;
            transition: color 0.3s ease;
        }
        .member-name:hover {
            color: #ffd700;
        }
        .memorial {
            padding: 40px 20px;
            text-align: center;
        }
        .memorial a {
            display: inline-block;
            background-color: red;
            color: white;
            padding: 15px 30px;
            border-radius: 10px;
            text-decoration: none;
            font-size: 1.5em;
            font-weight: bold;
            transition: background-color 0.3s ease, transform 0.3s ease;
            animation: fadeInUp 1s ease-in-out 1s both;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        .memorial a:hover {
            background-color: darkred;
            transform: scale(1.05);
        }
        .memorial a .icon {
            margin-right: 10px;
            font-size: 1.2em;
        }
        footer {
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            font-size: 0.8em;
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes fadeInUp {
            from { transform: translateY(30px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>KELUARGA KECIL XI-IPA</h1>
        <p class="description">
            Bergabunglah dengan KELUARGA KECIL XI-IPA, komunitas penuh energi di mana ilmu, kreativitas, dan persahabatan bersatu! Kami adalah pionir muda yang siap menaklukkan dunia dengan semangat tak terbendung. Jelajahi petualangan kami dan temukan inspirasi di setiap langkah – karena bersama, kami bukan sekadar keluarga, tapi kekuatan yang tak terhentikan!
        </p>
    </header>
    <section class="members">
        <div class="member">
            <a href="https://wa.me/6282185307034" class="member-name">ALVIN</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6282161408473" class="member-name">ANDIKA</a> <!-- Asumsi "dika" adalah ANDIKA -->
        </div>
        <div class="member">
            <a href="https://wa.me/6283897761639" class="member-name">ANDRA</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6285762048845" class="member-name">DIJA</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6288804099234" class="member-name">IKA</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6283862483657" class="member-name">NAFIZA</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6283185721531" class="member-name">NELSA</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6282160368072" class="member-name">PUSPA</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6289502519151" class="member-name">SAMUEL</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6285720461735" class="member-name">SYAFIQAH</a>
        </div>
        <div class="member">
            <a href="https://wa.me/6285372377490" class="member-name">SYANDI</a>
        </div>
    </section>
    <section class="memorial">
        <a href="https://videy.co/v/?id=2HnJUCep1" target="_blank">
            <span class="icon">▶️</span>OUR MEMORIAL VIDEO
        </a>
    </section>
    <footer>
        INSTAGRAM @andraicikiwirr
    </footer>
</body>
</html>
