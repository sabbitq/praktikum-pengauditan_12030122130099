# Praktikum Pengauditan - Atlas dan Arbutus

## 📖 Pendahuluan
Dibuat untuk memenuhi tugas mata kuliah Praktikum Pengauditan

M. Sabbit Qolbi<br>
12030122130099<br>

Praktikum Pengauditan<br>
Kelas I (S1 Akuntansi)<br>

## 📖 Keterangan
File Atlas = [Atlas_M. Sabbit Qolbi_12030122130099.xlsx](https://github.com/sabbitq/praktikum-pengauditan_12030122130099/blob/main/Atlas_M.%20Sabbit%20Qolbi_12030122130099.xlsx)

File Arbutus = [M. Sabbit Qolbi_12030122130099.asi](https://github.com/sabbitq/praktikum-pengauditan_12030122130099/blob/main/Arbutus_M.%20Sabbit%20Qolbi_12030122130099/Arbutus/M.%20Sabbit%20Qolbi_12030122130099.asi)

Penjelasan Arbutus = [ARBUTUS_M. SABBIT QOLBI_12030122130099.pdf](https://github.com/sabbitq/praktikum-pengauditan_12030122130099/blob/main/Arbutus_M.%20Sabbit%20Qolbi_12030122130099/ARBUTUS_M.%20SABBIT%20QOLBI_12030122130099.pdf)

## 📖 Penjelasan Arbutus
### 1.	Pengeluaran Kas: Test of Control
* Integrity test – Verify; Duplicates; Gaps <br>
![alt text](https://github.com/sabbitq/asset/blob/fa9459b37d16c34aa17c381c1e6a040563ae7d47/screenshoot/img32.jpg?raw=true)

* Attribute Sampling – Extract <br>
![alt text](https://github.com/sabbitq/asset/blob/4886953e729b921a87c0e2a181d94070ab1529b4/screenshoot/img33.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/a1406933b9e3b62a15beaf25ef1349a4ec51c3d7/screenshoot/img34.jpg?raw=true)
Cara lain dengan Edit Table Layout, lalu di Analyze – Classify <br>
![alt text](https://github.com/sabbitq/asset/blob/a1406933b9e3b62a15beaf25ef1349a4ec51c3d7/screenshoot/img35.jpg?raw=true)
 
### 2.	Piutang
* Integrity test – Verify; Duplicates; Gaps <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/piutang%20integrity%20test.png?raw=true)
  
* Test of Details: Piutang melebihi kredit limitnya <br>
→ Classify per customer <br>
→ Menu Data - Join = menggabungkan kolom credit max ke tabel piutang percustomer <br>
→ di Sort amount > credit max atau dengan edit table layout<br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img42.jpg?raw=true)
 
* Test of Details: Piutang bersaldo negatif <br>
→ Filter → amount < 0 <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img45.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img46.jpg?raw=true)
 
* Analisis Umur Piutang – Age <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img47.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img48.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img49.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img50.jpg?raw=true)
  
### 3.	Persediaan
* Integrity test – Verify; Sequence; Gaps <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/persediaan%20integrity%20test.png?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/persediaan%20gaps.png?raw=true)
  
* Pengujian Substantif: Mengecek Total Rincian dengan Total Saldo <br>
Analyze → Total = untuk mengecek kesamaan saldo di soal dengan rinciannya <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img61.jpg?raw=true) <br>
Sudah sesuai dengan saldo di laporan posisi keuangan (lihat buku)

* Pengujian Substantif: Persediaan Minus <br>
Analyze → Statistic = descriptive statistic, melihat apakah ada nilai persediaan yang minus <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img62.jpg?raw=true) 
Atau dengan Filter → Inventory cost < 0 <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img63.jpg?raw=true)
 
### 4.	Aset Tetap
* Pengujian Substantif: Membandingkan saldo aset tetap di neraca dengan daftar aset <br>
Analyze → Cross Tabulate = untuk menghitung saldo (harga perolehan dan akumulasi penyusutan) berdasarkan jenis akun aset tetap <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img66.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img67.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img68.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img69.jpg?raw=true)
 
* Pengujian Substantif: Mencari koreksi penyusutan <br>
→ menambah kolom baru, Edit Table Layout → New Expression, antara lain: <br>
  defaultnya “salah” <br>
  Penyusutan 2021 = Nilai Buku 2020 - 1 artinya “habis manfaat” <br>
  Penyusutan 2021 = Harga Perolehan * Tarif Penyusutan artinya “benar” <br>
  Penyusutan 2021 > Nilai Buku 2020 - 0.5 artinya “benar” <br>
→ yang “salah” di Extract , lalu dihitung (nambah kolom) penyusutan yang benar → expressionnya Harga Perolehan * Tarif Penyusutan, → lalu dicari selisihnya (nambah kolom) expressionnya Penyusutan 2021 - saldo benar <br>
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img72.jpg?raw=true)
![alt text](https://github.com/sabbitq/asset/blob/57ccffe64ce7380e85161ddaf88695d6f55db3e0/screenshoot/img73.jpg?raw=true) 
 
