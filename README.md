<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Registrasi Sembako</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <nav>
    <div class="navbar">
      <img src="download.jpeg"alt="jakarta.jpeg">
      <h4><strong>SEMBAKO-</strong></h4>
      <a href="#text-1">DAFTAR</a>
    </div>
  </nav>

  <div class="container-content">
    <p class="text-1" id="text-1">
      <strong>REGISTRASI ANTRIAN</strong>
    </p>

    <h5>***NOTE***</h5>
    <h5>***PASTIKAN MEMBAWA PERSYARATAN***</h5>

    <form action="berhasil.html" method="post">
      <h3>*Nama Penerima*</h3>
      <textarea placeholder="Nama" rows="2" cols="50" required></textarea>

      <h3>*No Telepon*</h3>
      <input type="tel" id="angkaOnly" placeholder="Hanya angka" 
             oninput="this.value = this.value.replace(/[^0-9]/g, '')" required>

      <h3>*Lokasi Pengambilan*</h3>
      <label for="subjects">LOKASI:</label>
      <select name="subjects" id="subjects" required>
        <option value="">-- Pilih Lokasi --</option>
        <option value="cempaka">Pasar Cempaka Putih</option>
        <option value="jaya">Pasar Jaya</option>
      </select>

      <br><br>
      <button type="submit">DAFTAR</button>
    </form>
  </div>
</body>
</html>
