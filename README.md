<form action="proses.php" method="POST">
  <h3>*Nama Penerima*</h3>
  <input type="text" name="nama" placeholder="Nama" required>

  <h3>*No Telepon*</h3>
  <input type="tel" id="angkaOnly" name="telepon" placeholder="Hanya angka" 
         oninput="this.value = this.value.replace(/[^0-9]/g, '')" required>

  <h3>*Lokasi Pengambilan*</h3>
  <label for="subjects">LOKASI:</label>
  <select name="lokasi" id="subjects" required>
    <option value="">-- Pilih Lokasi --</option>
    <option value="cempaka">Pasar Cempaka Putih</option>
    <option value="jaya">Pasar Jaya</option>
  </select>

  <br><br>
  <button type="submit">DAFTAR</button>
</form>
