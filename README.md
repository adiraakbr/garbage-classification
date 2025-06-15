
# Image Classification Model - CNN Sampah Kategori

Proyek ini proyek klasifikasi gambar dengan menggunakan Convolutional Neural Network (CNN) untuk mengelompokkan jenis sampah ke dalam beberapa kategori seperti plastik, kaca, logam, dll. Model dibuat menggunakan TensorFlow dan disimpan dalam berbagai format untuk keperluan deployment.

---

## 🧠 Model Arsitektur

Model CNN dibangun menggunakan Keras `Sequential API` dengan komponen utama:
- `Conv2D`
- `MaxPooling2D`
- `Flatten`
- `Dense`

Fungsi aktivasi: ReLU  
Loss function: Categorical Crossentropy  
Optimizer: Adam

---

## 🛠️ Cara Menjalankan

1. **Install dependensi:**

```bash
pip install -r requirements.txt
```

2. **Buka Notebook:**

Gunakan Jupyter Notebook atau Google Colab untuk membuka dan menjalankan `notebook.ipynb`.

---

## 📦 Format Model

| Format        | Deskripsi                                                  |
|---------------|-------------------------------------------------------------|
| `.h5`         | Format default Keras, berisi arsitektur dan bobot model     |
| `.pb`         | Format SavedModel                  |
| `.tflite`     | Format ringan untuk Android/Edge Devices                    |
| `TFJS`        | Format untuk penggunaan model di browser                    |

---

## 🧪 Dataset

Dataset terdiri dari gambar-gambar dengan label kategori sampah. Semua gambar telah diproses ulang dan dikategorikan sebelum pelatihan.

---

## ✨ Fitur Tambahan

- EarlyStopping & ReduceLROnPlateau untuk mencegah overfitting
- Class Weight Handling untuk data tidak seimbang

---

