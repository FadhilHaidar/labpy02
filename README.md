# Latihan 3: Buat program python untuk kasus berikut:

3 Kasus 1: Program Pemesanan Tiket Bioskop

Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000,
sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka
mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status
member dari user, lalu menghitung total harga yang harus dibayar.

1. Algoritma:
Tampilkan pilihan kepada pengguna untuk menentukan tipe tiket (Reguler atau VIP).
Minta pengguna memasukkan status keanggotaan (member atau bukan member).
Tetapkan harga tiket dasar:
Jika tipe tiket adalah Reguler, harganya adalah Rp50.000.
Jika tipe tiket adalah VIP, harganya adalah Rp100.000.
Cek status keanggotaan pengguna:
Jika pengguna adalah member, berikan diskon 20%.
Jika tidak, harga tetap tanpa diskon.
Tampilkan total harga yang harus dibayar.

3. Program Python:
python
Salin kode
# Harga tiket dasar
harga_reguler = 50000
harga_vip = 100000

# Input dari user
tipe_tiket = input("Masukkan tipe tiket (Reguler/VIP): ").strip().lower()
is_member = input("Apakah Anda memiliki kartu member? (ya/tidak): ").strip().lower()

# Menentukan harga tiket berdasarkan tipe
harga_tiket = harga_reguler if tipe_tiket == "reguler" else harga_vip

# Memberikan diskon jika memiliki kartu member
harga_akhir = harga_tiket * 0.8 if is_member == "ya" else harga_tiket

# Menampilkan hasil
print(f"Total harga yang harus dibayar: Rp{harga_akhir}")

3. Flowchart:
Mulai.
Minta input tipe_tiket dan is_member.
Jika tipe_tiket adalah Reguler, tetapkan harga_tiket = 50,000.
Jika VIP, tetapkan harga_tiket = 100,000.
Jika is_member = ya, hitung harga_akhir = harga_tiket * 0.8.
Jika tidak, harga_akhir = harga_tiket.
Tampilkan harga_akhir.
Selesai.
Kasus 2: Program Kalkulator Sederhana
1. Algoritma:
Minta pengguna untuk memasukkan dua angka.
Minta pengguna memilih operator aritmatika (+, -, *, atau /).
Periksa operator:
Jika operator adalah +, hitung penjumlahan.
Jika operator adalah -, hitung pengurangan.
Jika operator adalah *, hitung perkalian.
Jika operator adalah /, hitung pembagian (cek juga agar tidak membagi dengan 0).
Tampilkan hasil perhitungan.
Jika operator tidak valid, tampilkan pesan kesalahan.
2. Program Python:
python
Salin kode
# Input dari user
angka1 = float(input("Masukkan angka pertama: "))
angka2 = float(input("Masukkan angka kedua: "))
operator = input("Masukkan operator (+, -, *, /): ")

# Proses kalkulasi
if operator == '+':
    hasil = angka1 + angka2
elif operator == '-':
    hasil = angka1 - angka2
elif operator == '*':
    hasil = angka1 * angka2
elif operator == '/':
    # Memastikan tidak ada pembagian dengan 0
    if angka2 != 0:
        hasil = angka1 / angka2
    else:
        hasil = "Error: Pembagian dengan nol tidak diperbolehkan."
else:
    hasil = "Error: Operator tidak valid."

# Menampilkan hasil
print("Hasil perhitungan:", hasil)
