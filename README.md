# grupkuis
Plugin Moodle bertipe Quiz Report untuk memfasilitasi kuis kelompok pada Moodle

Adapun alur proses dari plugin yaitu pengajar menentukan kelompok untuk masing-masing peserta didik dan soal-soal yang akan diberikan masing-masing kelompok peserta didik. Masing-masing kelompok kemudian mengerjakan kuis berkelompok. Tiap-tiap peserta didik dalam kelompoknya masing-masing mengerjakan soal yang berbeda namun dikerjakan secara bersama-sama. Tiap-tiap soal memiliki bobot nilai yang akan disesuaikan dengan jumlah soal yang ada pada kuis. Hasil dari kuis berkelompok tersebut menghasilkan output berupa nilai individu masing-masing peserta didik yang akan menentukan nilai kelompok nantinya. Pengajar juga dapat melihat nilai individu maupun nilai kelompok peserta didik.

Nilai individu peserta didik didapatkan dari hasil pengerjaan soal-soal yang ada pada kuis berkelompok yang harus dijawab dengan benar untuk mendapatkan nilai. Apabila dijawab dengan salah maka tidak akan memberikan nilai. Dengan adanya nilai individu maka plugin dapat menghitung nilai kelompok berdasarkan persamaan nilai rata-rata hitung.

Setelah mendapatkan nilai individu dan nilai kelompok, kedua nilai tersebut akan dapat digunakan untuk menghitung nilai akhir. Adapun persamaan 3.1 di bawah ini yang akan digunakan untuk menghitung nilai akhir siswa yaitu :

nA=x_I*Y_i+ x_k*Y_k

Keterangan :
nA	: Nilai Akhir

x_i	: Nilai Individu Peserta Didik

x_k	: Nilai Kelompok Peserta Didik

Y_i	: Persentase Nilai Individu Peserta Didik

Y_k	: Persentase Nilai Kelompok Peserta Didik

Pada persamaan hitung nilai akhir, terdapat 4 buah nilai yaitu nilai individu, nilai kelompok, persentase nilai individu dan persentase nilai kelompok. Nilai individu berasal dari pengerjaan kuis kelompok secara pribadi oleh tiap-tiap peserta didik. Nilai kelompok didapatkan dari rata-rata nilai hasil pengerjaan kuis kelompok oleh suatu kelompok. Sedangkan persentase untuk nilai individu dan nilai kelompok pada plugin nantinya dapat ditentukan oleh pengajar sesuai kriteria yang diinginkan.
