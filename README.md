# Analisis Sentimen Komentar YouTube Wakil Presiden

Repositori ini berisi kode untuk melakukan analisis sentimen terhadap komentar-komentar dari video YouTube yang menampilkan Wakil Presiden. Proyek ini bertujuan untuk mengklasifikasikan sentimen publik (positif, negatif, atau netral) dari warganet berdasarkan data teks.

## Deskripsi

Analisis ini menggunakan dataset yang bersumber dari komentar-komentar pada video YouTube berjudul [**Generasi Muda, Bonus Demografi dan Masa Depan Indonesia**](https://youtu.be/SzXMacu80o8?si=31HYiHIwFV3KmXW7). Kode dalam repositori ini akan memproses data teks, melakukan *preprocessing*, dan kemudian mengaplikasikan model *machine learning* untuk analisis sentimen. Hasil akhir dari analisis ini adalah visualisasi data yang menunjukkan distribusi sentimen dari para komentator.

## Sumber Data

  * **Video YouTube:** [Generasi Muda, Bonus Demografi dan Masa Depan Indonesia](https://youtu.be/SzXMacu80o8?si=31HYiHIwFV3KmXW7)
  * **Dataset Kaggle:** [Indonesia's Vice President Youtube Comment](https://www.kaggle.com/datasets/faiqkhoirulmuna/indonesias-vice-president-youtube-comment/data)
  * **Asal-usul Data:** Dataset ini awalnya dikumpulkan dan dibagikan melalui sebuah unggahan di [Facebook](https://www.facebook.com/share/p/1Kq8YAARrQ/).

Video tersebut membahas tantangan dan peluang bonus demografi di Indonesia, serta peran penting generasi muda sebagai penentu kemajuan bangsa.

## Instalasi

Untuk menjalankan proyek ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

1.  **Clone repositori ini:**

    ```bash
    git clone https://github.com/ZakyFauzi/tes_analisis-sentimen.git
    ```

2.  **Masuk ke direktori proyek:**

    ```bash
    cd tes_analisis-sentimen
    ```

3.  **Buat dan aktifkan lingkungan virtual (disarankan):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # Untuk Windows: venv\Scripts\activate
    ```

4.  **Instal dependensi yang dibutuhkan:**

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn jupyterlab
    ```

    *Catatan: Pastikan untuk menambahkan library lain jika ada yang spesifik di dalam notebook Anda (misalnya: NLTK, Sastrawi, WordCloud).*

## Penggunaan

1.  Pastikan Anda sudah mengunduh dataset dari Kaggle dan meletakkannya di direktori yang sama dengan *notebook*.

2.  Jalankan Jupyter Lab atau Jupyter Notebook:

    ```bash
    jupyter lab
    ```

3.  Buka file `.ipynb` yang ada di dalam repositori.

4.  Jalankan setiap sel kode di dalam *notebook* secara berurutan untuk melihat proses analisis dari awal hingga akhir, termasuk pemrosesan data, pelatihan model (jika ada), dan visualisasi hasil.

## Kontribusi

Kontribusi sangat diterima\! Jika Anda ingin meningkatkan proyek ini, silakan buat *fork* dari repositori ini dan ajukan *pull request*.

## Ucapan Terima Kasih

  * Terima kasih kepada **Faiq Khoirul Muna** dari IMPHNEM yang telah membagikan dataset ini di Kaggle.

-----
