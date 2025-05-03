# Home Credit Indonesia - Prediksi Risiko Gagal Bayar Pinjaman

## Deskripsi
Proyek ini merupakan bagian dari program **Data Scientist Internship** di **Home Credit Indonesia**. Dalam proyek ini, saya mengembangkan model **machine learning** untuk memprediksi kemungkinan pemohon pinjaman mengalami kesulitan dalam membayar pinjaman. Tujuan dari proyek ini adalah untuk membantu Home Credit Indonesia dalam mengoptimalkan kebijakan kredit, mengurangi kerugian yang disebabkan oleh pemohon yang tidak mampu membayar pinjaman, serta meningkatkan akurasi dalam prediksi risiko gagal bayar.

## Dataset
Proyek ini menggunakan dataset dari **Home Credit Default Risk** yang mencakup informasi historis tentang pemohon pinjaman, seperti:
- Status pekerjaan, pendapatan, dan jumlah pinjaman.
- Riwayat kredit sebelumnya.
- Fitur-fitur terkait dengan perilaku sosial dan geografis pemohon.

## Tujuan Proyek
- Meningkatkan **keakuratan prediksi** dalam menilai risiko gagal bayar pinjaman.
- Mengidentifikasi **pemohon berisiko tinggi** yang kemungkinan besar tidak dapat membayar pinjaman.
- Mengoptimalkan **keputusan bisnis** dengan memberikan prediksi yang lebih tepat mengenai pemohon yang berisiko.

## Metodologi
- **Data Preprocessing**: Menggunakan teknik seperti **SMOTE**, **undersampling**, dan **feature engineering** untuk menyeimbangkan data dan mempersiapkan dataset untuk model machine learning.
- **Modeling**: Menggunakan algoritma seperti **Random Forest**, **XGBoost**, dan **Logistic Regression** untuk membangun model prediksi.
- **Evaluasi Model**: Menggunakan metrik seperti **accuracy**, **precision**, **recall**, **AUC-ROC**, dan **MCC** untuk mengevaluasi kinerja model.

## Hasil
Dari evaluasi yang dilakukan, model **Random Forest** dipilih karena **recall yang lebih baik** dalam mendeteksi kelas minoritas (pemohon berisiko), meskipun **XGBoost** menunjukkan sedikit keunggulan dalam AUC-ROC dan MCC.
