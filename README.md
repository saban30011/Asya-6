# Asya-6
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asya Ülkeleri Bilgi Kitabı</title>

    <style>
        body {
            font-family: sans-serif;
            line-height: 1.6;
            margin: 30px;
            background-color: #f4f4f4; /* Hafif gri arka plan */
            color: #333;
        }

        .container {
            max-width: 800px; /* İçerik genişliği */
            margin: 0 auto; /* Ortala */
            background-color: #fff; /* Beyaz içerik alanı */
            padding: 20px 30px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }

        h1 {
            text-align: center;
            color: #444;
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
            margin-bottom: 30px;
        }

        .country-section {
            margin-bottom: 40px; /* Ülkeler arası boşluk */
            padding-bottom: 20px;
            border-bottom: 1px solid #eee; /* Ülkeleri ayır */
        }

        .country-section:last-child {
            border-bottom: none; /* Son ülkenin alt çizgisini kaldır */
        }

        h2 {
            color: #0056b3; /* Ülke ismi rengi */
            margin-bottom: 15px;
        }

        .country-info p {
            margin: 8px 0;
        }

        .country-info strong {
            display: inline-block;
            min-width: 130px;
            color: #555;
        }

         .country-info ul {
            list-style: disc;
            margin-left: 150px; /* Madde imlerini hizala */
            padding-left: 0;
            margin-top: -10px; /* Paragrafla boşluğu ayarla */
        }
         .country-info li {
             margin-bottom: 3px;
         }

        .country-map img {
            max-width: 100%; /* Resmin taşmasını engelle */
            height: auto; /* Oranı koru */
            display: block; /* Ortalamak için */
            margin: 15px auto 10px auto; /* Üst/alt boşluk, sağ/sol otomatik ortalama */
            border: 1px solid #ddd;
            padding: 3px;
            background-color: #fff;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
            max-height: 250px; /* Resimlerin çok büyük olmasını engelle (isteğe bağlı) */
        }

        /* İçindekiler Kısmı (Opsiyonel) */
        #toc {
            margin-bottom: 30px;
            padding: 15px;
            background-color: #e9ecef;
            border-radius: 5px;
        }
        #toc h3 {
            margin-top: 0;
            margin-bottom: 10px;
        }
        #toc ul {
            list-style: none;
            padding: 0;
            margin: 0;
            column-count: 2; /* İki sütunlu liste (isteğe bağlı) */
        }
        #toc li {
            margin-bottom: 5px;
        }
        #toc a {
            text-decoration: none;
            color: #0056b3;
        }
        #toc a:hover {
            text-decoration: underline;
        }

         /* Küçük ekranlar için */
         @media (max-width: 600px) {
            body { margin: 15px; }
            .container { padding: 15px 20px; }
            h1 { font-size: 1.8em; }
            h2 { font-size: 1.3em; }
            .country-info strong { min-width: 100px; }
            .country-info ul { margin-left: 110px; }
            #toc ul { column-count: 1; } /* Tek sütun */
         }

    </style>
</head>
<body>

    <div class="container">
        <h1>Asya Ülkeleri Bilgi Kitabı</h1>

        <!-- İçindekiler (Opsiyonel ama kullanışlı) -->
        <nav id="toc">
            <h3>İçindekiler</h3>
            <ul>
                <li><a href="#turkey">Türkiye</a></li>
                <li><a href="#japan">Japonya</a></li>
                <li><a href="#china">Çin Halk Cumhuriyeti</a></li>
                <li><a href="#india">Hindistan</a></li>
                <li><a href="#southkorea">Güney Kore</a></li>
                <li><a href="#indonesia">Endonezya</a></li>
                <li><a href="#saudiarabia">Suudi Arabistan</a></li>
                <!-- Buraya eklediğin her yeni ülke için bir link ekle -->
            </ul>
        </nav>

        <!-- Ülke Bilgileri Bölümleri -->

        <section class="country-section" id="turkey">
            <h2>Türkiye</h2>
            <div class="country-map">
                <!-- BU ALANA TÜRKİYE'NİN DÜNYA HARİTASINDAKİ YERİNİ GÖSTEREN RESMİN URL'SİNİ EKLE -->
                <img src="img/turkey_map.png" alt="Türkiye'nin Dünya Haritasındaki Yeri">
                <!-- Örnek: Eğer resmi img klasörüne turkey_map.png olarak kaydettiysen src="img/turkey_map.png" -->
                <!-- Veya internetteki bir resim: src="https://example.com/turkey_location.jpg" -->
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Ankara</p>
                <p><strong>Nüfus:</strong> 85 Milyon+</p>
                <p><strong>Kuruluş:</strong> 1923</p>
                <p><strong>Yüzölçümü:</strong> 783,356 km²</p>
                <p><strong>Para Birimi:</strong> Türk Lirası (TRY)</p>
                <p><strong>İklim:</strong> Akdeniz, Karasal, Karadeniz</p>
                <p><strong>Önemli Kaynaklar:</strong></p>
                <ul>
                    <li>Bor</li>
                    <li>Krom</li>
                    <li>Kömür</li>
                    <li>Mermer</li>
                    <li>Bakır</li>
                    <li>Turizm</li>
                </ul>
            </div>
        </section>

        <section class="country-section" id="japan">
            <h2>Japonya</h2>
            <div class="country-map">
                <!-- BU ALANA JAPONYA'NIN DÜNYA HARİTASINDAKİ YERİNİ GÖSTEREN RESMİN URL'SİNİ EKLE -->
                <img src="img/japan_map.png" alt="Japonya'nın Dünya Haritasındaki Yeri">
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Tokyo</p>
                <p><strong>Nüfus:</strong> 125 Milyon+</p>
                <p><strong>Kuruluş:</strong> MÖ 660 (Efsanevi)</p>
                <p><strong>Yüzölçümü:</strong> 377,975 km²</p>
                <p><strong>Para Birimi:</strong> Japon Yeni (JPY)</p>
                <p><strong>İklim:</strong> Ilıman, Muson, Kuzeyde Soğuk</p>
                <p><strong>Önemli Kaynaklar:</strong></p>
                <ul>
                    <li>Balıkçılık</li>
                    <li>Elektronik</li>
                    <li>Otomotiv</li>
                    <li>Robotik</li>
                </ul>
            </div>
        </section>

        <section class="country-section" id="china">
            <h2>Çin Halk Cumhuriyeti</h2>
            <div class="country-map">
                 <!-- BU ALANA ÇİN'İN DÜNYA HARİTASINDAKİ YERİNİ GÖSTEREN RESMİN URL'SİNİ EKLE -->
                <img src="img/china_map.png" alt="Çin'in Dünya Haritasındaki Yeri">
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Pekin</p>
                <p><strong>Nüfus:</strong> 1.4 Milyar+</p>
                <p><strong>Kuruluş:</strong> 1949 (Halk Cumhuriyeti)</p>
                <p><strong>Yüzölçümü:</strong> 9,596,961 km²</p>
                <p><strong>Para Birimi:</strong> Çin Yuanı (CNY)</p>
                <p><strong>İklim:</strong> Çok çeşitli (Muson, Karasal, Subtropikal, Alp)</p>
                <p><strong>Önemli Kaynaklar:</strong></p>
                 <ul>
                    <li>Kömür</li>
                    <li>Demir</li>
                    <li>Petrol</li>
                    <li>Doğal Gaz</li>
                    <li>Nadir Toprak Elementleri</li>
                    <li>İmalat</li>
                 </ul>
            </div>
        </section>

        <section class="country-section" id="india">
            <h2>Hindistan</h2>
            <div class="country-map">
                <!-- BU ALANA HİNDİSTAN'IN DÜNYA HARİTASINDAKİ YERİNİ GÖSTEREN RESMİN URL'SİNİ EKLE -->
                <img src="img/india_map.png" alt="Hindistan'ın Dünya Haritasındaki Yeri">
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Yeni Delhi</p>
                <p><strong>Nüfus:</strong> 1.4 Milyar+</p>
                <p><strong>Kuruluş:</strong> 1947 (Bağımsızlık)</p>
                <p><strong>Yüzölçümü:</strong> 3,287,590 km²</p>
                <p><strong>Para Birimi:</strong> Hint Rupisi (INR)</p>
                <p><strong>İklim:</strong> Tropikal Muson, Çöl, Alp</p>
                <p><strong>Önemli Kaynaklar:</strong></p>
                 <ul>
                    <li>Kömür</li>
                    <li>Demir Cevheri</li>
                    <li>Manganez</li>
                    <li>Mika</li>
                    <li>Tekstil</li>
                    <li>Yazılım Hizmetleri</li>
                 </ul>
            </div>
        </section>

        <section class="country-section" id="southkorea">
            <h2>Güney Kore</h2>
            <div class="country-map">
                 <!-- BU ALANA GÜNEY KORE'NİN DÜNYA HARİTASINDAKİ YERİNİ GÖSTEREN RESMİN URL'SİNİ EKLE -->
                <img src="img/skorea_map.png" alt="Güney Kore'nin Dünya Haritasındaki Yeri">
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Seul</p>
                <p><strong>Nüfus:</strong> 51 Milyon+</p>
                <p><strong>Kuruluş:</strong> 1948</p>
                <p><strong>Yüzölçümü:</strong> 100,363 km²</p>
                <p><strong>Para Birimi:</strong> Güney Kore Wonu (KRW)</p>
                <p><strong>İklim:</strong> Ilıman, Dört Mevsim Belirgin</p>
                <p><strong>Önemli Kaynaklar:</strong></p>
                <ul>
                    <li>Elektronik</li>
                    <li>Otomotiv</li>
                    <li>Yarı İletkenler</li>
                    <li>Gemi İnşaatı</li>
                    <li>Çelik</li>
                </ul>
            </div>
        </section>

         <section class="country-section" id="indonesia">
            <h2>Endonezya</h2>
            <div class="country-map">
                 <!-- BU ALANA ENDONEZYA'NIN DÜNYA HARİTASINDAKİ YERİNİ GÖSTEREN RESMİN URL'SİNİ EKLE -->
                <img src="img/indonesia_map.png" alt="Endonezya'nın Dünya Haritasındaki Yeri">
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Cakarta</p>
                <p><strong>Nüfus:</strong> 275 Milyon+</p>
                <p><strong>Kuruluş:</strong> 1945 (Bağımsızlık İlanı)</p>
                <p><strong>Yüzölçümü:</strong> 1,904,569 km²</p>
                <p><strong>Para Birimi:</strong> Endonezya Rupiahı (IDR)</p>
                <p><strong>İklim:</strong> Tropikal Yağmur Ormanı</p>
                <p><strong>Önemli Kaynaklar:</strong></p>
                <ul>
                    <li>Petrol</li>
                    <li>Doğal Gaz</li>
                    <li>Kalay</li>
                    <li>Nikel</li>
                    <li>Kereste</li>
                    <li>Palmiye Yağı</li>
                </ul>
            </div>
        </section>

         <section class="country-section" id="saudiarabia">
            <h2>Suudi Arabistan</h2>
            <div class="country-map">
                 <!-- BU ALANA SUUDİ ARABİSTAN'IN DÜNYA HARİTASINDAKİ YERİNİ GÖSTEREN RESMİN URL'SİNİ EKLE -->
                <img src="img/saudi_map.png" alt="Suudi Arabistan'ın Dünya Haritasındaki Yeri">
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Riyad</p>
                <p><strong>Nüfus:</strong> 36 Milyon+</p>
                <p><strong>Kuruluş:</strong> 1932</p>
                <p><strong>Yüzölçümü:</strong> 2,149,690 km²</p>
                <p><strong>Para Birimi:</strong> Suudi Riyali (SAR)</p>
                <p><strong>İklim:</strong> Sıcak Çöl</p>
                <p><strong>Önemli Kaynaklar:</strong></p>
                <ul>
                    <li>Petrol (Dünyanın en büyük rezervlerinden)</li>
                    <li>Doğal Gaz</li>
                    <li>Demir Cevheri</li>
                    <li>Altın</li>
                </ul>
            </div>
        </section>

        <!-- --- YENİ ÜLKELERİ BURAYA EKLEYİN --- -->
        <!-- Yeni bir ülke eklemek için yukarıdaki <section>...</section> bloğunu kopyalayıp, -->
        <!-- içeriğini yeni ülkenin bilgileriyle değiştirin. -->
        <!-- section etiketine benzersiz bir id verin (örn: id="yen ülkeadı") -->
        <!-- ve yukarıdaki İçindekiler listesine de linkini eklemeyi unutmayın. -->
        <!-- Örnek Yeni Ülke:
        <section class="country-section" id="vietnam">
            <h2>Vietnam</h2>
            <div class="country-map">
                <img src="img/vietnam_map.png" alt="Vietnam'ın Dünya Haritasındaki Yeri">
            </div>
            <div class="country-info">
                <p><strong>Başkent:</strong> Hanoi</p>
                ...diğer bilgiler...
            </div>
        </section>
        -->
        <!-- --- YENİ ÜLKELERİ BURAYA EKLEYİN --- -->


    </div> <!-- /container -->

</body>
</html>
