# Ekstraksi Fitur Warna Citra Buah Apel Menggunakan HSV #

Deskripsi
Project ini merupakan implementasi ekstraksi fitur warna pada citra buah apel menggunakan metode HSV (Hue, Saturation, Value) dalam bidang Computer Vision.

Tujuan
- Mengambil fitur warna dari citra digital
- Mengubah data citra menjadi data numerik
- Menyimpan hasil ekstraksi ke dalam file CSV dan Excel

Metode
- Preprocessing (resize gambar)
- Konversi RGB ke HSV
- Perhitungan rata-rata nilai H, S, V

Dataset
- Jumlah: 10 citra
- Format: JPG
- Ukuran: 256x256 pixel

Tools & Library
- Python
- OpenCV
- NumPy
- Pandas
- OpenPyXL

Hasil
Hasil ekstraksi berupa nilai:
- Hue
- Saturation
- Value

Data disimpan dalam:
- fitur_apel.csv
- fitur_apel.xlsx

Cara Menjalankan
1. Install library:
   ```bash
   pip install opencv-python pandas openpyxl
2. Jalankan Script
   ```bash
   python ekstraksi_hsv.py

3. Output
   File hasil: CSV & Excel
4. Author
   Nama: Aldy Naufal Rafiansyah
   NIM: (2318107)
5. Link Terkait
   [Google Colab](https://colab.research.google.com/drive/1VVPivGOAfsdZCYZBNYBW-zNAY-ei_Y_0?usp=sharing)
   [PPT](https://docs.google.com/presentation/d/1cr4j9LlJ9ol2_BcuiRk2hMbvOYvK5Wra/edit?usp=sharing&ouid=115081197734973150762&rtpof=true&sd=true)
   [LinkedIn](https://www.linkedin.com/posts/aldy-naufal-b26b0a331_ekstraksi-fituur-warna-citra-buah-apel-menggunakan-ugcPost-7446561114089422848-L_I3?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFOi3c4Bv7p_bgUcr_zHe-VKUHjr-C6JiLM)
   
