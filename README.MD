Tugas 2 — Pembersihan dan Pra-pemrosesan Data Teks

Identitas Mahasiswa

* Nama: [M REZA AL QHALIL]
* NIM: [24146026]
* Mata Kuliah: [24146026]
* Kelas: [02]

Deskripsi Tugas

Tugas ini bertujuan untuk melakukan pembersihan dan pra-pemrosesan data teks pada dataset ulasan produk e-commerce berbahasa Indonesia.

Proses preprocessing dilakukan untuk meningkatkan kualitas data teks agar lebih bersih, konsisten, dan siap digunakan dalam analisis sentimen.

Dataset

Dataset yang digunakan:

E-Commerce Product Reviews Sentiment

Sumber dataset: Hugging Face

https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment  

Dataset ini berisi ulasan produk e-commerce berbahasa Indonesia yang memiliki label sentimen.

Tujuan

1. Menampilkan informasi dataset.
2. Mengetahui jumlah data dan kolom dataset.
3. Menampilkan distribusi label sentimen.
4. Melakukan preprocessing terhadap data teks.
5. Membandingkan teks sebelum dan sesudah preprocessing.
6. Memahami pengaruh preprocessing terhadap kualitas data teks.

Tahapan Preprocessing

Tahapan preprocessing yang dilakukan:

1. Case Folding

Mengubah seluruh huruf pada teks menjadi huruf kecil agar penulisan lebih konsisten.

Contoh:

PRODUK INI BAGUS

Menjadi:

produk ini bagus

2. Cleaning

Membersihkan teks dari URL, angka, tanda baca, dan karakter khusus yang tidak diperlukan.

3. Tokenisasi

Memisahkan teks menjadi kumpulan kata atau token.

Contoh:

produk ini bagus

Menjadi:

['produk', 'ini', 'bagus']

4. Stopword Removal

Menghapus kata-kata umum yang dianggap kurang memberikan informasi penting dalam analisis, sesuai kebutuhan.

5. Stemming

Mengubah kata berimbuhan menjadi bentuk dasarnya.

Contoh:

membeli menjadi beli

Struktur Repository

Tugas2-Preprocessing-Ecommerce/
│
├── Tugas2_Preprocessing.ipynb
├── Laporan_Tugas2.pdf
└── README.md

Cara Menjalankan Notebook

1. Download atau clone repository ini.
2. Buka file Tugas2_Preprocessing.ipynb menggunakan Jupyter Notebook, JupyterLab, atau Google Colab.
3. Pastikan library yang diperlukan sudah tersedia.
4. Jalankan setiap cell secara berurutan.
5. Periksa hasil informasi dataset, distribusi sentimen, dan contoh preprocessing.

Hasil yang Diharapkan

Hasil dari tugas ini meliputi:

* Informasi jumlah data dan kolom dataset.
* Distribusi label sentimen.
* Data teks yang telah melalui preprocessing.
* 10 contoh teks sebelum dan sesudah preprocessing.
* Penjelasan pengaruh preprocessing terhadap kualitas data teks.

Pengaruh Preprocessing

Preprocessing membantu meningkatkan konsistensi data, mengurangi noise, dan mempermudah proses analisis teks.

Data yang telah dibersihkan dapat membantu proses tokenisasi dan pembentukan fitur menjadi lebih terstruktur. Namun, preprocessing perlu dilakukan dengan tepat agar tidak menghilangkan informasi penting dari ulasan.

Link Repository GitHub

Repository: [Masukkan link repository GitHub di sini]

Kesimpulan

Pra-pemrosesan data teks merupakan tahap penting dalam analisis sentimen. Melalui case folding, cleaning, tokenisasi, stopword removal, dan stemming, data ulasan dapat dipersiapkan agar lebih terstruktur dan siap digunakan untuk proses analisis selanjutnya.