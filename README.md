# Deep-Learning
# **UAS Deep Learning: Klasifikasi Kendaraan Motor**

## **Nama Kelompok**

| **Nama**                      | **NPM**      |
|-------------------------------|--------------|
| Nazir Mahmudi Lubis            | G1A021013   |
| Kahfi Zairan Maulana           | G1A021041   |
| Gilang Atila Ilham             | G1A0210‎75‎   |

---

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan analisis dan pengolahan dataset citra menggunakan metode deep learning. Data berupa gambar diorganisasikan dan diproses untuk mempersiapkan model deep learning yang dapat digunakan untuk tugas klasifikasi atau analisis visual lainnya.

---

## Langkah-Langkah Proyek

### Pengolahan Data
1. **Impor Library**:  
   - Menggunakan library utama seperti `matplotlib`, `numpy`, dan `PIL` untuk manipulasi data citra.  
2. **Persiapan Data**:  
   - Dataset gambar disimpan di Google Drive, kemudian diakses dan dihitung jumlah file per kategori menggunakan `pathlib`.  
   - Membaca dan memvisualisasikan gambar untuk analisis awal.

### Arsitektur Model
Proyek ini bertujuan untuk membuat model berbasis convolutional neural network (CNN) atau teknik lain yang relevan untuk analisis citra. Komponen arsitektur model dapat mencakup:
- **Conv2D Layer**: Untuk ekstraksi fitur gambar.  
- **Pooling Layer**: Untuk mereduksi dimensi data fitur.  
- **Flatten Layer**: Untuk meratakan data ke vektor 1D.  
- **Dense Layer**: Untuk klasifikasi akhir berdasarkan jumlah kelas.

### Kompilasi Model
- **Loss Function**: Sparse Categorical Crossentropy (kemungkinan).  
- **Optimizer**: Adam atau lainnya yang umum untuk tugas citra.  
- **Metrics**: Accuracy untuk evaluasi performa.

### Pelatihan Model
- **Dataset Split**: Dataset dibagi menjadi bagian training dan testing.  
- **Parameter Pelatihan**: Menggunakan jumlah epoch tertentu (belum disebutkan detailnya).

---

## Hasil Pelatihan
Hasil model belum diekstraksi dari file, namun langkah-langkah pengolahan data citra dan akses dataset telah dilakukan dengan baik.

---

## Kesimpulan
Notebook ini merupakan fondasi untuk proyek deep learning berbasis citra, dengan langkah-langkah yang mencakup:
1. Pengolahan dataset citra yang terorganisasi.  
2. Persiapan model deep learning untuk klasifikasi atau analisis visual.  

Model dapat dilanjutkan untuk proses pelatihan dan evaluasi lebih lanjut.

---

## Cara Menjalankan
1. **Clone Repositori (jika ada)**:  
   Pastikan repositori proyek diunduh, jika tersedia.  
2. **Akses Dataset**:  
   Gunakan Google Drive untuk menyimpan dan mengakses dataset.
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```  
3. **Upload Dataset**:  
   Pastikan file gambar berada di direktori yang benar, seperti `/content/drive/MyDrive/Motor Beat`.  
