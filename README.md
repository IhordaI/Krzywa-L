<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Analiza Symulatora Krzywych Lissajous</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f0f0f0;
            color: #333;
        }

        h1, h2 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
        }

        .section {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        ul {
            padding-left: 30px;
        }

        li {
            margin: 10px 0;
        }

        .code {
            font-family: 'Courier New', monospace;
            background: #f8f9fa;
            padding: 2px 5px;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <h1>Analiza Symulatora Krzywych Lissajous</h1>

    <div class="section">
        <h2>O czym jest strona?</h2>
        <p>Interaktywny symulator krzywych Lissajous - figur powstających w wyniku złożenia dwóch drgań harmonicznych prostopadłych. Symuluje ruch układu dwóch sprężyn z kulą, tworząc charakterystyczne wzory.</p>
    </div>

    <div class="section">
        <h2>Możliwości strony</h2>
        <h3>Główne funkcje:</h3>
        <ul>
            <li>Symulacja ruchu harmonicznego w 2D</li>
            <li>Wizualizacja krzywych Lissajous w czasie rzeczywistym</li>
            <li>Interaktywne wykresy energii i przestrzeni fazowej</li>
            <li>Pełna kontrola parametrów fizycznych układu</li>
        </ul>

        <h3>Elementy interfejsu:</h3>
        <ul>
            <li>Panel kontrolny z suwakami</li>
            <li>Główna wizualizacja z animacją</li>
            <li>Wykres energii całkowitej, kinetycznej i potencjalnej</li>
            <li>Wykresy przestrzeni fazowej dla obu osi</li>
        </ul>
    </div>

    <div class="section">
        <h2>Konfigurowalne parametry</h2>
        <h3>Parametry ruchu:</h3>
        <ul>
            <li>Amplituda X (A): <span class="code">0-300</span></li>
            <li>Amplituda Y (B): <span class="code">0-300</span></li>
            <li>Częstotliwość X (a): <span class="code">1-10</span> (z wartościami √2 i √7)</li>
            <li>Częstotliwość Y (b): <span class="code">1-10</span> (z wartościami √2 i √7)</li>
            <li>Przesunięcie fazowe (δ): <span class="code">0-6.28</span></li>
            <li>Tłumienie: <span class="code">0-1</span></li>
            <li>Masa (m): <span class="code">0.01-0.2</span></li>
        </ul>

        <h3>Parametry wizualizacji:</h3>
        <ul>
            <li>Długość śladu: <span class="code">50-1000</span></li>
        </ul>
    </div>

    <div class="section">
        <h2>Obserwowalne elementy</h2>
        <ul>
            <li>Animacja ruchu kulki i sprężyn</li>
            <li>Ewolucja kształtu krzywej Lissajous</li>
            <li>Wykresy energii w czasie rzeczywistym</li>
            <li>Przestrzeń fazowa dla obu osi</li>
            <li>Bieżące współrzędne kulki</li>
        </ul>
    </div>

    <div class="section">
        <h2>Dodatkowe funkcje</h2>
        <ul>
            <li>Przycisk resetowania ustawień</li>
            <li>Zoom na wykresie energii (rolka myszy)</li>
            <li>Specjalne wartości częstotliwości (√2, √7)</li>
            <li>Efekty wizualne: gradienty, cienie, animowane tło</li>
            <li>Neonowy motyw z ciemnym interfejsem</li>
        </ul>
    </div>

    <div class="section">
        <h2>Struktura techniczna</h2>
        <ul>
            <li>Zbudowana w czystym HTML/CSS/JavaScript</li>
            <li>Wykorzystuje Canvas do renderowania</li>
            <li>Animacja oparta na <span class="code">requestAnimationFrame</span></li>
            <li>Responsywny układ z gridem CSS</li>
            <li>Zaawansowane efekty CSS: gradienty, cienie, animacje</li>
            <li>Integracja z czcionką Orbitron z Google Fonts</li>
        </ul>
    </div>
</body>
</html>
