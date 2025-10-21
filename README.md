# 🧠 Klasifikasi Kelulusan Mahasiswa dengan Artificial Neural Network (ANN)

## 🎯 Tujuan
Proyek ini membangun model **Artificial Neural Network (ANN)** sederhana untuk memprediksi apakah seorang mahasiswa **lulus atau tidak**, menggunakan dataset `processed_kelulusan.csv`.

---

## ⚙️ Cara Menjalankan Proyek

### 1️⃣ Clone Repository
```
git clone https://github.com/0xRopik/pertemuan7.git
cd pertemuan7
```
2️⃣ Install Library

Pastikan Python 3.10 sudah terpasang.
```
pip install -r requirements.txt
```
3️⃣ Jalankan Notebook (opsi interaktif)
```
jupyter notebook model_ann_kelulusan.ipynb
```
4️⃣ Jalankan Script (opsi cepat)
```
python train_ann.py
```
## Model akan otomatis dilatih dan disimpan sebagai ann_model.h5.
📊 Hasil Output

Setelah training, kamu akan mendapatkan file:
ann_model.h5 → model hasil training
learning_curve.png → grafik learning curve
Akurasi dan AUC test akan ditampilkan di terminal
Contoh hasil:
```
Test Accuracy: 0.89, AUC: 0.93
```
