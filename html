# iuma
iuma app
<!DOCTYPE html>

<html lang="ms">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>I-Ummah | Waktu Solat Harian</title>

    <style>

        body {

            font-family: 'Segoe UI', sans-serif;

            background: linear-gradient(to bottom right, #eef2f3, #dfe6e9);

            color: #2d3436;

            text-align: center;

            padding: 40px;

        }

        img.logo {

            width: 160px;

            margin-bottom: 20px;

        }

        h2 {

            color: #0984e3;

        }

        #prayer-times, #quran-hadith {

            background: #ffffff;

            padding: 20px;

            border-radius: 12px;

            box-shadow: 0 4px 12px rgba(0,0,0,0.1);

            display: inline-block;

            text-align: left;

            margin-top: 20px;

            max-width: 500px;

        }

        ul {

            list-style-type: none;

            padding-left: 0;

        }

        li {

            margin: 8px 0;

            font-size: 16px;

        }

        .loading {

            font-style: italic;

            color: #636e72;

        }

    </style>

</head>

<body>

 

    <!-- Gantikan nama fail logo jika berbeza -->

    <img src="logo-iummah.png" alt="Logo I-Ummah" class="logo">

 

    <h2>Waktu Solat Hari Ini</h2>

    <div id="prayer-times" class="loading">Memuatkan waktu solat berdasarkan lokasi anda...</div>

 

    <h2>Firman Allah & Sabda Rasulullah ﷺ</h2>

    <div id="quran-hadith" class="loading">Memuatkan...</div>

 

    <script>

        // Ambil waktu solat berdasarkan lokasi pengguna

        navigator.geolocation.getCurrentPosition(function(position) {

            const lat = position.coords.latitude;

            const lon = position.coords.longitude;

            const apiURL = `https://api.aladhan.com/v1/timings?latitude=${lat}&longitude=${lon}&method=3`;

 

            fetch(apiURL)

                .then(response => response.json())

                .then(data => {

                    const timings = data.data.timings;

                    let html = '<ul>';

                    const orderedKeys = ['Fajr', 'Dhuhr', 'Asr', 'Maghrib', 'Isha'];

                    orderedKeys.forEach(prayer => {

                        html += `<li><strong>${prayer}</strong>: ${timings[prayer]}</li>`;

                    });

                    html += '</ul>';

                    document.getElementById('prayer-times').innerHTML = html;

                })

                .catch(error => {

                    document.getElementById('prayer-times').innerText = 'Gagal memuatkan waktu solat.';

                    console.error(error);

                });

        }, function(error) {

            document.getElementById('prayer-times').innerText = 'Lokasi tidak dibenarkan atau tidak tersedia.';

        });

 

        // Teks ayat Al-Quran & Hadis

        const quotes = [

            "“Sesungguhnya solat itu adalah fardhu yang ditentukan waktunya atas orang-orang yang beriman.” (An-Nisa' 4:103)",

            "“Dan dirikanlah solat untuk mengingati-Ku.” (Taha 20:14)",

            "“Mintalah pertolongan dengan sabar dan solat...” (Al-Baqarah 2:45)",

            "“Solat adalah tiang agama. Sesiapa yang mendirikannya, maka dia telah menegakkan agama.” (HR al-Baihaqi)",

            "“Yang pertama sekali akan dihisab oleh Allah dari amal hamba-Nya pada hari kiamat ialah solat.” (HR Abu Daud)",

            "“Perbezaan antara seorang Muslim dan orang kafir adalah meninggalkan solat.” (HR Muslim)"

        ];

 

        let currentIndex = 0;

        const quoteDiv = document.getElementById('quran-hadith');

 

        function showNextQuote() {

            quoteDiv.innerHTML = quotes[currentIndex];

            currentIndex = (currentIndex + 1) % quotes.length;

        }

 

        showNextQuote();

        setInterval(showNextQuote, 15000); // tukar setiap 15 saat

    </script>

 

</body>

</html>
