<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Profil Mahasiswa</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 40px 16px;
      background-color: #f4f6f8;
      color: #222;
    }

    .foto {
      display: block;
      width: 180px;
      height: 180px;
      margin: 0 auto;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #fff;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    }

    h1 {
      margin: 20px 0 10px;
    }

    p {
      margin: 4px 0;
    }

    .tombol {
      margin-top: 24px;
    }

    .tombol a {
      display: inline-block;
      margin: 4px;
      padding: 10px 22px;
      background-color: #2b6cb0;
      color: #fff;
      text-decoration: none;
      border-radius: 6px;
    }

    .tombol a:hover {
      background-color: #1e4e82;
    }

    .klik {
      display: block;
      margin: 12px auto 0;
      padding: 6px 14px;
      background-color: #38a169;
      color: #fff;
      border: none;
      border-radius: 6px;
      font-size: 13px;
      cursor: pointer;
    }

    .klik:hover {
      background-color: #276749;
    }
  </style>
</head>
<body>

  <img class="foto" src="foto.jpeg" alt="Foto Martin Kitesvara">

  <h1>Profil Mahasiswa</h1>
  <p>Nama: Martin Kitesvara</p>
  <p>NIM: G.231.25.0065</p>
  <p>Kelas: Teknik Informatika A1</p>

  <div class="tombol">
    <a href="https://www.instagram.com/nathanael_martinezz" target="_blank">Instagram</a>
    <a href="https://mail.google.com/mail/?view=cm&fs=1&to=martinkustyadi@gmail.com" target="_blank">Contact</a>
  </div>

  <button class="klik" onclick="halo()">Klik Saya</button>

  <script>
    function halo() {
      alert("Hello Everyone");
    }
  </script>

</body>
</html>
