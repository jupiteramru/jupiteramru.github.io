<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portofolio</title>

    <!-- FONT -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />

    <!-- FONT -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />
    <!-- FONT -->

    <!-- STYLE -->
    <link rel="stylesheet" href="style.css" />
    <!-- STYLE -->
  </head>

  <!-- CONTENT -->
  <body>
    <!-- NAVBAR -->
    <nav class="navbar">
      <h1 class="logo">JUPITER AMRU</h1>

      <div class="navbar-nav">
        <a href="#about">Tentang Saya</a>
        <a href="#experience">Pengalaman Kerja</a>
        <a href="#contact">Kontak Saya</a>
      </div>
    </nav>
    <!-- NAVBAR -->

    <!-- CONTENT -->
    <main class="container">
      <!-- ABOUT -->
      <section id="about">
        <div class="card" onclick="toggleCard(this)">
          <h2>Tentang Saya</h2>
          <div class="card-content">
            <div class="inner-card">
              <p class="p1">
                Saya memiliki pribadi yang ambisius dan memiliki ketertarikan
                besar di bidang teknologi informasi, khususnya dalam
                pengembangan web sebagai Fullstack Developer.
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- EXPERIENCE -->
      <section id="experience">
        <div class="card" onclick="toggleCard(this)">
          <h2>Pengalaman Kerja</h2>
          <div class="card-content">
            <div class="inner-card">
              <h3>PT INDOMARCO PRISMATAMA</h3>

              <p>Jakarta, Indonesia</p>
              <p>Jul 2022 - sekarang</p>
              <p>Warehouse Operator</p>
              <ol>
                <li>Stock Opname barang.</li>
                <li>Menerima barang dari supplier.</li>
                <li>Display barang.</li>
                <li>Picking barang.</li>
                <li>Sortir barang retur.</li>
              </ol>
            </div>
            <div class="inner-card">
              <h3>PT AKEBONO BRAKE ASTRA INDONESIA</h3>
              <p>Jakarta, Indonesia</p>
              <p>Sep 2019 - Des 2019</p>
              <p>PPIC (Internship)</p>
              <ol>
                <li>Distribusi material produksi</li>
                <li>Update stock</li>
                <li>Laporan stock</li>
              </ol>
            </div>
          </div>
        </div>
      </section>

      <!-- CONTACT -->
      <section id="contact">
        <div class="card">
          <h2>Kontak Saya</h2>
          <div class="inner-card2">
            <a href="mailto:jupiteramru03@gmail.com">jupiteramru03@gmail.com</a>
            <p>
              LinkedIn
              <a href="https://www.linkedin.com/in/jupiter-amru-338658248/"
                >Jupiter Amru</a
              >
            </p>
          </div>
        </div>
      </section>
    </main>
    <!-- CONTENT -->

    <!-- FOOTER -->
    <footer>
      <p>© 2026 | Dibuat oleh Jupiter Amru</p>
    </footer>
    <!-- FOOTER -->

    <!-- SCRIPT -->
    <script src="script.js"></script>
    <!-- SCRIPT -->
  </body>
</html>
