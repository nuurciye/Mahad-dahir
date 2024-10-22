<!DOCTYPE html>
<html lang="so">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Amana International Logistics Co</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        section {
            padding: 20px;
        }
        .services {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .services div {
            border: 1px solid #ccc;
            padding: 10px;
            width: 22%;
            text-align: center;
            background-color: #f9f9f9;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Amana International Logistics Co</h1>
        <p>Waxaan Bixinaa Xalalka Saadka Iyo Gaadiidka Adduunka</p>
    </header>

    <!-- Navigation Menu -->
    <nav>
        <a href="#home">Bogga Hore</a>
        <a href="#about">Nagu Saabsan</a>
        <a href="#services">Adeegyada</a>
        <a href="#contact">Nala Soo Xiriir</a>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <h2>Kusoo Dhawoow Amana International Logistics Co</h2>
        <p>
            Waxaan u heellanahay bixinta xalal saadka oo habsami leh, waxtar leh, oo la habeeyay si ay ugu habboonaadaan baahiyahaaga ganacsi. Haddii aad u baahan tahay hawada, badda, ama dhulka rarida, waan ku dabooli doonaa.
        </p>
    </section>

    <!-- About Us Section -->
    <section id="about">
        <h2>Nagu Saabsan</h2>
        <p>
            Amana International Logistics Co waa shirkad lagu kalsoon yahay oo bixisa xalalka saadka iyo silsiladda sahayda. Waxaan leenahay khibrad sannado badan oo ku saabsan gaadiidka caalamiga ah, waxaana ujeedkeenna yahay inaanu bixino adeegyo la isku halayn karo, ammaan ah, oo hufan.
        </p>
        <h3>Himiladayada</h3>
        <p>In aan bixino adeegyo saadka oo ammaan ah, waxtar leh, iyo la isku halayn karo oo isku xira ganacsiyada adduunka oo dhan.</p>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>Adeegyadayada</h2>
        <div class="services">
            <div>
                <h3>Rarista Hawada</h3>
                <p>Adeegyo raritaan hawada oo degdeg ah, la isku halayn karo, oo hufan oo caalami ah.</p>
            </div>
            <div>
                <h3>Rarista Badda</h3>
                <p>Xalal dhamaystiran oo rarista badda ah oo loogu talagalay dhammaan noocyada alaabta.</p>
            </div>
            <div>
                <h3>Gaadiidka Dhulka</h3>
                <p>Gaadiid dhulka oo la isku halayn karo oo waqtigiisa ku yimaada oo loogu talagalay badeecadahaaga.</p>
            </div>
            <div>
                <h3>Cashuuraha iyo Xaqiijinta</h3>
                <p>Adeegyo sax ah oo fududeeya marin-u-helidda xuduudaha iyada oo aan wax caqabad ah la kulmin.</p>
            </div>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact">
        <h2>Nala Soo Xiriir</h2>
        <p>Cinwaanka: 1234 Logistics Park, Magaalada, Dalka</p>
        <p>Email: info@amanaintl.com</p>
        <p>Telefoon: +123 456 7890</p>

        <h3>Dalbo Qiimeyn</h3>
        <form action="#" method="POST">
            <label for="name">Magaca:</label><br>
            <input type="text" id="name" name="name"><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br><br>

            <label for="service">Adeegga:</label><br>
            <select id="service" name="service">
                <option value="air">Rarista Hawada</option>
                <option value="sea">Rarista Badda</option>
                <option value="land">Gaadiidka Dhulka</option>
                <option value="customs">Cashuuraha iyo Xaqiijinta</option>
            </select><br><br>

            <label for="message">Fariin:</label><br>
            <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>

            <input type="submit" value="Hel Qiimeyn">
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Amana International Logistics Co. Dhammaan xuquuqaha way xafidan yihiin.</p>
        <p>Nagu Raac:
            <a href="#" style="color: white;">LinkedIn</a> |
            <a href="#" style="color: white;">Facebook</a> |
            <a href="#" style="color: white;">Twitter</a>
        </p>
    </footer>

</body>
</html>