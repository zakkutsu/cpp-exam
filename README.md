# 🍽️ Program Restoran Online – Sejahtera

Aplikasi berbasis **C++** untuk melakukan pemesanan makanan secara online.  
Pengguna dapat memilih kategori masakan, memesan beberapa menu sekaligus, memasukkan alamat pengiriman, dan mendapatkan nota pembayaran lengkap dengan biaya kurir serta diskon.

---

## 🎯 Tujuan
- Memberikan simulasi sistem pemesanan makanan online berbasis **console application**.
- Melatih penggunaan **array**, **percabangan**, **looping**, dan **struktur input/output** pada bahasa C++.
- Mempraktikkan perhitungan harga, diskon, dan biaya pengiriman secara otomatis.

---

## 📄 Dokumentasi
Fitur utama program:
1. **Pilihan Kategori Masakan**:
   - Masakan Cina
   - Masakan Jawa
   - Masakan Padang
   - Masakan Sunda
2. **Pemesanan Multi Menu** – Pengguna dapat memesan lebih dari satu menu sekaligus.
3. **Input Alamat & Kontak** – Untuk pengiriman.
4. **Perhitungan Otomatis**:
   - Total harga
   - Diskon (berdasarkan nominal belanja)
   - Biaya kurir (per km)
5. **Nota Pembayaran** – Menampilkan detail pesanan, alamat, biaya kurir, diskon, dan total bayar.
6. **Transaksi Berulang** – Program dapat diulang untuk pemesanan baru.

---

```
Progam Restoran Online Faiz Nasrul Sejahtera
```

---

Daftar Masakan

1. Masakan Cina
2. Masakan Jawa
3. Masakan Padang
4. Masakan Sunda
   Silakan Pilih Jenis Masakan = 1

# Silakan Pilih Menu

# Kode 	Menu 		Harga

1. Dimsum 		Rp.10.000
2. Bakpao 		Rp.5.000
3. Capcay 		Rp.15.000
   Masukkan jumlah menu yang akan dipesan = 2
   ...
   \=================================================
   Nota Pembayaran
   \=================================================
   Total Pembayaran : Rp. 53.000

````

---

## ⚙️ Cara Install
1. Pastikan **compiler C++** (misalnya g++) sudah terpasang.
2. Simpan kode program dalam file `restoran_online.cpp`.
3. Buka terminal / command prompt di folder tempat file disimpan.
4. Compile program:
   ```bash
   g++ restoran_online.cpp -o restoran_online
````

5. Jalankan program:

   ```bash
   ./restoran_online
   ```

---

## 📂 Isi Aplikasi

* **Menu & Harga** – Disimpan dalam array `menu[]` dan `harga[]`.
* **Input Pesanan** – Memilih kategori, jumlah, dan kode makanan.
* **Alamat Pengiriman** – Mengisi nama, nomor telepon, provinsi, kota, kecamatan, kode pos.
* **Perhitungan Biaya**:

  * Harga total = jumlah × harga per menu.
  * Diskon sesuai batas nominal:

    * > Rp 200.000 → 10%
    * > Rp 100.000 → 7%
    * > Rp 50.000 → 5%
  * Biaya kurir = jarak × Rp 3.000.
* **Output Nota** – Menampilkan detail pesanan.

---

## 🏷 Text Tag

* `cpp`
* `restaurant`
* `online order`
* `food delivery`
* `array`
* `console app`
* `diskon`
* `kurir`

---
