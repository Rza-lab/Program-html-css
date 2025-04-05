<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Belajar CSS Position Sederhana</title>
    <link rel="stylesheet" href="style-sederhana.css">
</head>
<body>
    <h1>Belajar CSS Position Sederhana</h1>

    <div class="container">
        <div class="box static">Static</div>
        <div class="box relative">Relative</div>
        <div class="container-absolute">
            <div class="box absolute">Absolute</div>
        </div>
        <div class="box fixed">Fixed</div>
        <div class="container-sticky">
            <div class="box sticky">Sticky</div>
            <p>Scroll ke bawah...</p>
            <p>Scroll ke bawah...</p>
            <p>Scroll ke bawah...</p>
            <p>Scroll ke bawah...</p>
            <p>Scroll ke bawah...</p>
        </div>
    </div>

    <div class="explanation">
        <h2>Penjelasan:</h2>
        <p>Perhatikan bagaimana setiap kotak diposisikan:</p>
        <ul>
            <li><strong>Static:</strong> Mengalir seperti biasa.</li>
            <li><strong>Relative:</strong> Sedikit bergeser dari posisi normalnya.</li>
            <li><strong>Absolute:</strong> Berada di pojok kanan atas dari kotak berwarna biru di sekitarnya.</li>
            <li><strong>Fixed:</strong> Selalu berada di pojok kanan bawah layar.</li>
            <li><strong>Sticky:</strong> Awalnya seperti biasa, tapi akan menempel di atas saat Anda scroll ke bawah.</li>
        </ul>
    </div>
</body>
</html>
