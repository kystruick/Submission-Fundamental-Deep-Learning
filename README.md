\# Proyek Klasifikasi Gambar: 100 Sports Image Classification



\## Deskripsi

Proyek ini merupakan implementasi klasifikasi gambar menggunakan Deep Learning dengan dataset 100 Sports Image Classification dari Kaggle.



\## Dataset

\- Nama: 100 Sports Image Classification

\- Total gambar: 14.493

\- Jumlah kelas: 100

\- Sumber: Kaggle



\## Arsitektur Model

\- Transfer Learning menggunakan EfficientNetB0

\- Model Sequential dengan GlobalAveragePooling2D

\- Optimizer: Adam (learning rate: 1e-4)

\- Loss: Categorical Crossentropy



\## Hasil

\- Train Accuracy: 96.12%

\- Test Accuracy: 96.60%

\- Epochs: 20



\## Format Model

\- SavedModel: saved\_model/

\- TF-Lite: tflite/model.tflite

\- TFJS: tfjs\_model/



\## Requirements

Lihat file requirements.txt

