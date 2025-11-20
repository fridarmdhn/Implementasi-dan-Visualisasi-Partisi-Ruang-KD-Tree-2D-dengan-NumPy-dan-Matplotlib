🌳 KD-Tree 2D Visualizer (Proyek Struktur Data)

Halo! Proyek ini berisi kode Python sederhana untuk membangun dan
memvisualisasikan KD-Tree (K-Dimensional Tree). KD-Tree adalah struktur
data yang sangat berguna untuk mengorganisir titik-titik dalam ruang
(seperti koordinat x dan y) agar pencarian lokasi (misalnya, mencari
“tetangga terdekat”) dapat dilakukan dengan cepat.

🤔 Apa Itu KD-Tree? Bayangkan Anda memiliki banyak pin di peta. KD-Tree
adalah cara untuk membagi peta (ruang 2D) secara berulang-ulang dengan
garis lurus (partisi). Pohon ini dibangun dengan membagi data menjadi
dua bagian yang seimbang (berdasarkan nilai tengah/median) secara
bergantian pada sumbu X dan sumbu Y. Tujuan utamanya adalah membuat
pencarian lokasi menjadi sangat cepat!

🛠️ Persiapan Awal (Setup) Untuk menjalankan kode ini, Anda hanya perlu
menginstal beberapa library Python utama: - Python (Versi 3.x) - NumPy
(Untuk operasi array dan perhitungan) - Matplotlib (Untuk membuat
visualisasi grafik)

Anda dapat menginstal library tersebut menggunakan perintah ini: pip
install numpy matplotlib

🚀 Cara Menjalankan Kode 1. Salin semua kode dari file .ipynb atau skrip
Python Anda. 2. Tempel ke notebook baru. 3. Jalankan setiap sel kode
secara berurutan. 4. Setelah menjalankan semua sel, grafik pembagian
ruang KD-Tree akan muncul.

🎯 Data yang Digunakan Kode ini menggunakan 6 titik 2D: (2,3), (5,4),
(9,6), (4,7), (8,1), (7,2)

🧑‍💻 Detail Teknis Singkat 
- Fungsi kdtree: Mengurutkan titik pada dimensi
tertentu (axis), memilih median sebagai root node, lalu rekursif
membangun subtree.
- Fungsi plot_kdtree: Menggambar partisi berdasarkan
kedalaman. - Depth genap → garis vertikal (sumbu X)
- Depth ganjil →
garis horizontal (sumbu Y)
