# USA-House-Price-Prediction

Membangun model machine learning yang mampu memprediksi harga rumah secara akurat berdasarkan data historis dan fitur properti.

---

## Tujuan Bisnis

Mendukung pengambilan keputusan agen properti dalam menentukan harga rumah yang kompetitif dan sesuai dengan kondisi pasar.

---

## Deskripsi Kolom

- Dataset menggunakan data dari [USA Housing Price Prediction](https://www.kaggle.com/datasets/vedavyasv/usa-housing/data)

Berikut adalah penjelasan masing-masing kolom dalam dataset:

| Kolom                          | Deskripsi                                                                  |
|--------------------------------|----------------------------------------------------------------------------|
| `Avg. Area Income`             | Rata-rata pendapatan tahunan penduduk di area tersebut (dalam satuan dolar AS).|
| `Avg. Area House Age`          | Rata-rata umur rumah yang ada di area tersebut (dalam tahun).               |
| `Avg. Area Number of Rooms`    | Rata-rata jumlah ruangan di rumah-rumah pada area tersebut.                 |
| ` Avg. Area Number of Bedrooms`| Rata-rata jumlah kamar tidur di rumah-rumah pada area tersebut.             |
| `Area Population`              | Jumlah total populasi atau penduduk yang tinggal di area tersebut.          |
| `Price`                        | Harga rumah yang menjadi target prediksi (dalam dolar AS).                  |
| `Adress`                       | Alamat dari rumah yang bersangkutan                                         |

## Metodologi

- **Pra-pemrosesan**: Encoding, scaling, handling missing values.
- **Modeling**: Algoritma seperti Linear Regression, Ridge, Lasso, KNN Regressor, Decision Tree Regressor, Random Forest Regressor, XG Boost.
- **Model Asumsi**: Pengecekan menggunakan Normality Residual, Zero Mean of Residuals, Linearity, Homoscedasticity, Correlation Between Residuals and Prediction, No Autocorrelation of Residuals
- **Evaluasi**: MAE, MAPE, RMSE, MSE, R Squared.

---

## Hasil Utama

- Semua fitur kecuali fitur `Avg. Area Number of Bedrooms` memiliki pengaruh yang kuat terhadap penentuan harga rumah.

---

 ## Tools and Technology

- Python, Pandas, Scikit-Learn, Seaborn

  ---
  Adrian Irsanda Boestamam
