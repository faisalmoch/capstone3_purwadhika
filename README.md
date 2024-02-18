# capstone3_purwadhika

### Context

BETA adalah perusahaan broker properti yang berbasis di California, melayani klien yang ingin membeli atau menjual properti tempat tinggal. Dengan sifat pasar real estate yang dinamis, BETA menghadapi banyak tantangan dalam memprediksi harga properti secara akurat. Faktor-faktor seperti lokasi, ukuran properti, kondisi, fasilitas, dan tren pasar berkontribusi terhadap kompleksitas penetapan harga peroperti secara efektif.

### Problem Statement
BETA menyadari perlunya meningkatkan strategi penetapan harga dengan memanfaatkan machine learning. Metode tradisional dalam menentukan harga properti sangat bergantung pada analisis manual dan pengetahuan pasar, yang dapat memakan waktu dan dapat terjadi human error. Selain itu, **pasar real estate di California sangat kompetitif dan berkembang secara pesat, sehingga menyulitkan broker seperti BETA untuk tetap menjadi yang terdepan dalam tren harga dan menawarkan harga yang kompetitif kepada klien.**

### Goals
Tujuan utama penerapan machine learning untuk memprediksi harga rumah adalah untuk meningkatkan akurasi dan efisiensi strategi penetapan harga property. Dengan memanfaatkan kekuatan analisis data dan pemodelan prediktif, hal ini bertujuan untuk:
1. Meningkatkan akurasi harga: Algoritma machine learning dapat menganalisis kumpulan data berjumlah besar yang berisi data penjualan historis, karakteristik properti, demografi lingkungan, dan tren pasar untuk mengidentifikasi pola dan korelasi yang memengaruhi harga rumah. Dengan menangkap faktor-faktor ini secara akurat, BETA dapat menghasilkan estimasi harga properti residensial yang lebih tepat, sehingga mengurangi risiko harga rumah yang terlalu mahal atau terlalu rendah.

2. Mengoptimalisasi pemilihan keputusan: Algoritma machine learning dapat memberikan insight berharga mengenai indikator utama dan dinamika harga, sehingga membantu BETA untuk mengambil keputusan berdasarkan data secara real-time. Dengan memantau tren pasar dan fluktuasi properti, BETA dapat menyesuaikan strategi penetapan harga secara dinamis untuk memanfaatkan peluang yang muncul dan memitigasi potensi risiko.

3. Meningkatkan kepuasan klien: Penetapan harga properti secara akurat sangat penting untuk menjaga kepercayaan dan kepuasan klien. Dengan memanfaatkan machine learning untuk memberikan perkiraan harga yang lebih akurat dan transparan, BETA dapat meningkatkan pengalaman pelanggan secara keseluruhan dan membangun hubungan jangka panjang dengan pembeli dan penjual.

### Analytic Approach
Data yang tersedia akan dianalisa untuk dapat menemukan pola dari fitur-fitur yang ada, yang membedakan satu properti dengan yang lainnya. Berdasarkan analisa tersebut akan dibangun suatu model regresi yang akan membantu BETA menyediakan 'tool' prediksi harga properti, yang akan berguna dalam menentukan nilai suatu properti.

### Metric Evaluation
Evaluasi metrik yang akan digunakan adalah RMSE, MAE, dan MAPE, di mana RMSE adalah nilai rataan akar kuadrat dari error, MAE adalah rataan nilai absolut dari error, sedangkan MAPE adalah rataan persentase error yang dihasilkan oleh model regresi. Semakin kecil nilai RMSE, MAE, dan MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga property sesuai dengan limitasi fitur yang digunakan. 
