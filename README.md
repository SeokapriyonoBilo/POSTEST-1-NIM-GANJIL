# POSTEST-1-NIM-GANJIL
Seokapriyono Bilo 2309116095

```
# Postest 1

# Nilai tukar mata uang rupiah ke (USD, Yen, Ringgit Malaysia)
nilai_tukar = {
    "USD": 0.000065,
    "JPY": 0.0097,
    "MYR": 0.00030,
}

# meminta input (Jumlah rupiah)
jumlah_rupiah = float(input("Masukan Jumlah Rupiah yang ingin Anda konversikan: "))

# Menampilkan daftar mata uang yang dapat dikonversikan
print("Pilih mata uang yang ingin anda konversikan:")
for mata_uang in nilai_tukar.keys():
    print(mata_uang)

# Meminta input mata uang tujuan
tujuan = input("Masukan kode mata uang tujuan: ").upper()

# Mengecek apakah mata uang tujuan valid
if tujuan in nilai_tukar:
    hasil_konversi = jumlah_rupiah * nilai_tukar[tujuan]
    print(f"{jumlah_rupiah} IDR setara dengan {hasil_konversi} {tujuan}")
else:
    print("kode mata uang tujuan tidak valid. Silahkan pilih kode mata uang yang valid.")

# Nliai Tukar 1 USD = 15,380 IDR
# Nilai Tukar 1 JPY = 103,46 IDR
# Nilai Tukar 1 MYR = 3,282 IDR 

```
![Diagram Tanpa Judul-Halaman-1 drawio](https://github.com/SeokapriyonoBilo/POSTEST-1-NIM-GANJIL/assets/144988079/5a9eb179-c9b5-4500-b7af-7d414a4f28d3)
