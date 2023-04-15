Performance Testing adalah Teknik non functional testing untuk menentukan parameter sistem dalam hal responsif dan stabilitas dibawah berbagai beban (load) 
kerja. Performance testing mengukur kualitas atribut dari sistem seperti stabilitas, ketahanan (reliability) dan penggunaan sumber daya. Yang diukur dari 
performance testing adalah Performa suatu aplikasi sampai suatu batas tertentu, bukan merupakan functional-test, bisa dalam berbagai macam bentuk untuk memahami 
reliability, stability dan availability pada environment-nya. contoh: Mengamati response time ketika menjalankan request dalam jumlah yang sangat banyak dan 
melihat suatu sistem berinteraksi dengan jumlah dat yang cukup besar. Pada umumnya performance testing cukup mahal untuk diaplikasikan dan dijalankan, namun 
dapat dijadikan tolak ukur apakah sistem tersebut dapat mengakomodasi traffic yang ada. Hal ini disebabkan karena pengetesannya memerlukan persiapan yang 
dimana beberapa kasus harus membuat environment terpisah dari production agar tidak tercampurnya data test dengan data production. Dalam melakukan performance
test biasanya yang menjadi perhatian adalah throughput dan response datanya. 
Introduction to JMeter, ada beberapa tools yang dapat digunakan dalam pengujian ini salah satunya adalah JMeter dan yang lainnya ada grafana k6, locust, BlazeMeter.
Apache JMeter adalah perangkat lunak sumber terbuka, aplikasi desktop Java 100% murni, yang dirancang untuk memuat uji perilaku fungsional dan mengukur kinerja 
situs web. Awalnya dirancang untuk aplikasi web pengujian beban tetapi sejak itu fungsi pengujian lainnyaditambahkan. Keuntungan yang kita dapatkan jika 
menggunakan JMeter adalah Open Source sehingga kita dapat melihat kode dari aplikasi JMeter ini, jika ada masalah kita dapat melihat sendiri permasalahan tersebut
terjadi dibagian mana dan keuntungan yang terakhir adalah easy to use with GUI/ Non GUI. 
Post Processor adalah bagian dari test plan yang merupakan sebuah aksi yang berjalan saat proses setelah dilakukan, proses tersebut adalah request ke sebuah
halaman web. Pada umumnya post processor dilakukan untuk mengekstrak value yang didapatkan dari hasil mengakses sebuah halaman web. 