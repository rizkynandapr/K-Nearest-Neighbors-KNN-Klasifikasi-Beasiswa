## 🧠 K-Nearest Neighbors (KNN) — Klasifikasi Beasiswa

Proyek ini merupakan implementasi algoritma K-Nearest Neighbors (KNN) untuk melakukan klasifikasi data beasiswa. Model dibangun menggunakan scikit-learn dengan preprocessing, training, evaluasi, dan visualisasi decision boundary.

---

## 📂 Struktur File

| File                                 | Deskripsi                                                                           |
| ------------------------------------ | ----------------------------------------------------------------------------------- |
| `KNN_Rizky_Nanda_Praditia_057.ipynb` | Notebook utama berisi preprocessing, training, evaluasi, dan visualisasi model KNN. |

---

##⚙️ Alur Model

| Tahap              | Deskripsi                                             |
| ------------------ | ----------------------------------------------------- |
| **Data Loading**   | Membaca dataset `Beasiswa (1).csv`.                   |
| **Data Splitting** | Membagi data menjadi train dan test (rasio 70:30).    |
| **Normalisasi**    | Standarisasi fitur menggunakan `StandardScaler`.      |
| **Training Model** | Menggunakan **KNeighborsClassifier** dengan `k=1`.    |
| **Evaluasi**       | Menggunakan Confusion Matrix & Classification Report. |
| **Visualisasi**    | Menampilkan decision boundary hasil klasifikasi.      |

---

## ✨ Fitur Utama

🔍 Implementasi algoritma KNN dengan scikit-learn.
📊 Evaluasi menggunakan confusion matrix & classification report.
🎨 Visualisasi decision boundary dengan matplotlib.
⚡ Notebook interaktif, mudah dimodifikasi untuk dataset lain.

---

## 🚀 Cara Menjalankan

Clone repo:
git clone https://github.com/rizkynandapr/KNN-Beasiswa.git
cd KNN-Beasiswa

Install dependencies:
pip install -r requirements.txt

Jalankan notebook:
jupyter notebook KNN_Rizky_Nanda_Praditia_057.ipynb

---

## 🛠️ Teknologi yang Digunakan
Python 3.x
scikit-learn
NumPy, Pandas
Matplotlib

---

## 📊 Hasil

✅ Model berhasil melakukan klasifikasi data beasiswa.
📈 Evaluasi ditampilkan dalam bentuk confusion matrix dan classification report.
🎨 Visualisasi decision boundary menunjukkan area prediksi model.
