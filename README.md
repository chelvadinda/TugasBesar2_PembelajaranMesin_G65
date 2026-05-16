# Tugas Besar 2 IF3270 Pembelajaran Mesin

# Kelompok 65
1. Yosef Rafael Joshua 13522133
2. Chelvadinda 13522154

# Dataset

Dataset yang digunakan:  
### Intel Image Classification Dataset

🔗 Link dataset:  
https://www.kaggle.com/datasets/puneet6060/intel-image-classification

---

# Struktur Folder

```text
src/
└── cnn/
    ├── pipeline_CNN.ipynb
    ├── hasil_eksperimen.csv
    └── data/
        └── Intel-Image-Classification/
            ├── seg_train/
            ├── seg_test/
            └── seg_pred/
```

---

# Penempatan Dataset

Setelah dataset di-download, letakkan folder dataset pada path berikut:

```text
src/cnn/data/Intel-Image-Classification/
```

---

# Cara Menjalankan Program

## 1. Install dependency

Jalankan perintah berikut pada terminal:

```bash
pip install tensorflow numpy pandas matplotlib seaborn pillow scikit-learn
```

---

## 2. Buka notebook

Buka file berikut menggunakan:
- Jupyter Notebook, atau
- Visual Studio Code

```text
pipeline_CNN.ipynb
```

---

## 3. Jalankan program

Jalankan seluruh cell notebook secara berurutan.