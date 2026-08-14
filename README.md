<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AmethystSMP Store</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0f0c1b;
            color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            padding: 40px 20px;
        }

        header {
            text-align: center;
            margin-bottom: 50px;
        }

        h1 {
            font-size: 3.5rem;
            color: #b19cd9;
            text-shadow: 0 0 20px rgba(177, 156, 217, 0.6);
            letter-spacing: 2px;
        }

        .store-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 25px;
            width: 100%;
            max-width: 1000px;
        }

        .store-card {
            background: linear-gradient(135deg, #1f1835 0%, #130f24 100%);
            border: 2px solid #52397d;
            border-radius: 12px;
            padding: 30px 20px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.4);
        }

        .store-card:hover {
            transform: translateY(-5px);
            border-color: #b19cd9;
            box-shadow: 0 6px 25px rgba(177, 156, 217, 0.3);
        }

        .store-card h2 {
            color: #e0d1ff;
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .store-card p {
            color: #a399bd;
            font-size: 0.95rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>AMETHYSTSMP STORE</h1>
    </header>

    <div class="store-container">
        <div class="store-card">
            <h2>Rank</h2>
            <p>Obține avantaje și kit-uri exclusive</p>
        </div>
        <div class="store-card">
            <h2>Shards</h2>
            <p>Monedă valoroasă pentru magazin</p>
        </div>
        <div class="store-card">
            <h2>Key</h2>
            <p>Chei pentru cufere misterioase</p>
        </div>
        <div class="store-card">
            <h2>Spawner</h2>
            <p>Spawner-e pentru ferma ta</
