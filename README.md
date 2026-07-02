# Geographic-Information-System-Projects
Geospatial portfolio showcasing mapping and remote sensing projects

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio WebGIS Saya</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">GeoPortfolio</div>
        <nav>
            <a href="#home">Beranda</a>
            <a href="#map-section">Peta Interaktif</a>
            <a href="#projects">Proyek Lain</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Selamat Datang di Portfolio SIG Saya</h1>
        <p>Saya adalah seorang GIS Analyst & WebGIS Developer. Di bawah ini adalah beberapa hasil analisis spasial dan pengembangan peta digital yang telah saya lakukan.</p>
    </section>

    <section id="map-section" class="map-container-wrapper">
        <h2>Peta Interaktif (WebGIS Showcase)</h2>
        <div id="map"></div>
    </section>

    <section id="projects" class="projects-grid">
        <h2>Proyek SIG Lainnya</h2>
        <div class="cards">
            <div class="card">
                <h3>Analisis Kesesuaian Lahan</h3>
                <p>Analisis spasial menggunakan metode overlay/skoring untuk menentukan zona pemukiman aman di Kabupaten X.</p>
                <span class="badge">ArcGIS / QGIS</span>
            </div>
            <div class="card">
                <h3>Peta Distribusi Fasilitas Kesehatan</h3>
                <p>Pemetaan point of interest (POI) rumah sakit dan puskesmas menggunakan analisis buffer.</p>
                <span class="badge">Python / Geopandas</span>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Nama Anda. Dibuat dengan Leaflet.js & 💚</p>
    </footer>

    <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
    <script src="script.js"></script>
</body>
</html>
