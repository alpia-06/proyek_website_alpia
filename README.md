<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Peluang</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        /* Mengatur desain global */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }

        /* Mengatur lebar konten utama */
        .container {
            max-width: 900px;
            width: 100%;
            margin: 0 auto;
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 10px;
        }

        h1 {
            font-size: 22px;
            color: #1757fa;
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }

        /* Section konten utama */
        h2 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #111111;
            border-bottom: 2px solid #a05c04e7;
            padding-bottom: 5px;
        }

        h3 {
            font-size: 18px;
            margin-bottom: 10px;
            color: #2c1c07e7;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 10px;
            text-align: justify;
            color: #000000;
        }

        ul {
            margin-left: 20px;
            margin-bottom: 20px;
        }

        li {
            font-size: 16px;
            margin-bottom: 5px;
            color: #000000;
        }

        /* Membuat iframe responsif */
        iframe {
            width: 100%;
            height: 300px;
            border: none;
            margin-bottom: 20px;
            border-radius: 8px;
        }

        /* Responsif untuk tampilan mobile */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }

            h1 {
                font-size: 20px;
            }

            h2 {
                font-size: 18px;
            }

            h3 {
                font-size: 16px;
            }

            p,
            li {
                font-size: 14px;
            }

            .container {
                padding: 10px;
            }

            iframe {
                height: 250px;
            }
        }

        /* Footer diatur dengan flexbox agar selalu di tengah halaman */
        footer {
            text-align: center;
            margin: 20px auto;
            font-size: 14px;
            color: #000;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-shrink: 0;
        }
    </style>
</head>

<body>
    <!-- Navbar Responsif dengan warna biru -->
    <nav class="navbar navbar-expand-lg bg-primary w-100">
        <div class="container-fluid">
            <a class="navbar-brand" href="cobaweb22.html">ALPIA</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="cobaweb22.html">MATERI</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="lembar_kerja.html">LEMBAR KERJA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="tugasweb.html">TUGAS</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
        <h1>1. Peluang </h1>
        <h1>Tonton Video Berikut</h1>
        <iframe src="https://www.youtube.com/embed/3mnvcG8os_s?si=GzOkAl_tSaAsxDn-" title="YouTube video player"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>

        <iframe title="PELUANG"
            src="https://www.geogebra.org/material/iframe/id/tsnrhrqm/width/1341/height/548/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false"></iframe>

        <div class="container">
            <h1>Materi Peluang</h1>
            <p>Peluang adalah cabang dari matematika yang mempelajari kemungkinan terjadinya suatu kejadian.
                Peluang sering digunakan dalam kehidupan sehari-hari, misalnya dalam permainan dadu, koin,
                ataupun lotre.</p>

            <h2>1. Pengertian Peluang</h2>
            <p>Peluang adalah ukuran kemungkinan terjadinya suatu kejadian dalam suatu percobaan acak. Nilai
                peluang berkisar antara 0 dan 1. Jika peluang suatu kejadian adalah 0, berarti kejadian tersebut
                pasti tidak terjadi, dan jika peluang suatu kejadian adalah 1, maka kejadian tersebut pasti
                terjadi.</p>

            <h2>2. Rumus Peluang</h2>
            <div class="formula">
                <strong>Peluang suatu kejadian:</strong> <br>
                P(A) = <i>n(A)</i> / <i>n(S)</i>
                <p>Di mana:</p>
                <ul>
                    <li><i>P(A)</i> = peluang terjadinya kejadian A</li>
                    <li><i>n(A)</i> = banyaknya kejadian A</li>
                    <li><i>n(S)</i> = banyaknya ruang sampel</li>
                </ul>
            </div>

            <h2>3. Contoh Kasus</h2>
            <p>Sebuah dadu dilempar satu kali. Berapakah peluang munculnya angka 3?</p>
            <div class="example">
                <strong>Penyelesaian:</strong> <br>
                Ruang sampel (S) = {1, 2, 3, 4, 5, 6} <br>
                Kejadian muncul angka 3 (A) = {3} <br>
                Peluang muncul angka 3 adalah:
                <p>P(A) = <i>n(A)</i> / <i>n(S)</i> = 1 / 6</p>
            </div>

            <h2>4. Frekuensi Relatif</h2>
            <p>Frekuensi relatif adalah perbandingan antara frekuensi kejadian dengan jumlah percobaan yang
                dilakukan. Semakin sering suatu percobaan dilakukan, maka frekuensi relatif akan semakin
                mendekati nilai peluang teoretisnya.</p>
            <div class="example">
                <strong>Contoh:</strong> <br>
                Jika sebuah koin dilempar 100 kali dan muncul gambar sebanyak 48 kali, maka frekuensi relatif
                muncul gambar adalah:
                <p>Frekuensi relatif = 48 / 100 = 0,48</p>
            </div>

            <h2>5. Peluang Komplemen</h2>
            <p>Peluang komplemen dari suatu kejadian A adalah peluang kejadian yang tidak termasuk A. Jika
                peluang kejadian A adalah P(A), maka peluang komplemen A adalah:</p>
            <div class="formula">
                P(A') = 1 -
