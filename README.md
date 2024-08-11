# <center>**Capstone Project 3: <br> Customer Lifetime Value** <br> </center>
<center> Cinira Harsaning Aziz </center> <br>

<br>

Sebuah perusahaan yang bergerak di bidang asuransi otomatif memiliki data untuk informasi existing customer mereka, seperti jenis kendaraan, jenis asuransi, hingga perhitungan customer lifetime value (CLV) dari tiap customer. ``CLV merupakan total nilai finansial yang diberikan tiap customer atau pendapatan yang dihasilkan dari setiap customer ke perusahaan selama periode bisnis berlaku.`` Memahami dan meningkatkan CLV di perusahaan dapat meningkatkan keuntungaan perusahaan, merencanakan anggaran yang lebih efektif, dan merancang strategi marketing yang tepat sasaran. Sehingga, Perusahaan asuransi otomatif ini ingin menggunakan informasi CLV tersebut untuk memprediksi nilai CLV dari new customer serta mengidentifikasi faktor-faktor yang memengaruhi CLV dalam upaya memaksimalkan profitabilitas.

## **1.2. Problem Statement**

Selama ini, perusahaan asuransi otomotif tersebut belum menerapkan strategi pemasaran yang tepat sasaran, khususnya dalam menargetkan customer mereka. Salah satu penyebabnya adalah pendekatan marketing yang seragam, di mana anggaran dialokasikan sama rata untuk semua tipe pelanggan. Akibatnya, perusahaan membayar lebih untuk low-value customer dan kehilangan high-value customer. Selain itu, proses perhitungan nilai CLV yang dilakukan secara manual juga sangat tidak efisien, memakan waktu dan sumber daya yang signifikan. Ketidakmampuan untuk memprediksi nilai CLV secara otomatis dan akurat ini menghambat perusahaan dalam merancang strategi marketing yang efektif dan mengoptimalkan profit perusahaan.

## **1.3. Goals**

Perusahaan asuransi otomotif memerlukan alat untuk memprediksi nilai CLV untuk memahami faktor-faktor yang memengaruhi profitabilitas dan menentukan biaya akuisisi customer. Dengan adanya alat ini, divisi marketing hanya cukup menggunakan data yang ada atau informasi asuransi customer (seperti jenis asuransi, jumlah polis, premi, dan klaim) untuk mendapat prediksi angka CLV. Hal tersebut mampu menggantikan proses manual, sehingga memungkinkan perusahaan untuk merancang strategi pemasaran yang lebih tertarget dan efektif.

## **1.4. Analytic Approach**

Kita akan menganalisis data untuk mengidentifikasi pola dari fitur-fitur yang membedakan satu customer dari yang lain. Selanjutnya, kita akan mengembangkan model regresi untuk menyediakan alat dalam memprediksi nilai CLV, yang akan membantu perusahaan memprediksi profit dari setiap customer.

## **1.5. Metric Evaluation**
Evaluasi metrik yang akan digunakan yaitu:
- RMSE adalah nilai rataan akar kuadrat dari error 
- MAE adalah rataan nilai absolut dari error
- MAPE adalah rataan nilai persentase error yang dihasilkan oleh model regresi
- R-squared adalah nilai seberapa baik model dapat merepresentasikan varians keseluruhan data

Semakin kecil nilai RMSE, MAE, dan MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi sesuai dengan limitasi fitur yang digunakan. 

Semakin mendekati 1 nilai R-squared yang dihasilkan, berarti semakin fit pula modelnya terhadap data observasi.
