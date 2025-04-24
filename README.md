# PML_UTS_DesicionTree_OrangeGrape

Langkah-langkah
1. Langkah pertama yaitu menginstall library yang di butuhkan. Library yang di butuhkan yaiutu mengkses google Sheet (gspread,gspread_dataframe (disini saya sudah mengapload ke google sheet terlebih dahulu datanya), namun pakai pandas langsung ke CSV. pasday dan numpy digunakan untuk memanipulasi data; sklearn digunakn untuk mechine learning (train-test split, decition tree dan evaluasi); dan juga menggunakan matplotib untuk menvisualisasikan pohon keputusan.
2. Langkah kedua menganbil data dari google sheet
3. Malakukan preprocessung data (Label Encoding dan Pisah x,y). Dilakukan juga pengecekan untuk kolom name dengan "orange dan "grapefruit". Lalu name di konverssikan menjadi angka (dimana "orange="0" dan grapefruit"="1"). X digunakan untuk gitur selain name dan y adalah target klasifikasi
4. LAngkah selanjutnya yaitu membagi data menjadi data latih dan data uji. Dimana data latih 80% dan data uji 20%. random_state digunakna untuk menghasilkan konsitensi setiap di jalankan.
5. Dilakukannya pelatihan decition Tree dimana membuat objek decition tree
6. Menlakukan evaluasi. Evaluasi dilakukan dengnan akurasi (presentasi prediksi benar), confusion matrix (matrix 2x2 yang menunjukan TP,TN, Fp dan FN) sera classification report (precision, recal, f1 untuk setiap kelas.
7. Langkah terakhir yaitu visualisasi pohon keputusan dimana menampilkan visualissasi struktur pohon dan setiap node menunjukan kondisi fitur, cabang menunjukan keputusan dan warnanya memiliki kelas random.
