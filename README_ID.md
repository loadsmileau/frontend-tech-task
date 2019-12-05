__Language :__ [English](README.md) | Bahasa Indonesia

# Frontend Technical Task
Aplikasi web untuk menyarankan resep makan siang

## Manajemen Waktu
Tidak ada batasan waktu untuk mengerjakan *task* ini. Anda bebas mengatur waktu untuk menyelesaikan *requirement* yang kami minta.

## Penilaian
Kriteria penilaian kami akan memperhatikan hal - hal berikut:
- Bagaimana struktur aplikasinya. 
- *Code quality (Clean code)*.
- Kualitas dari *test* (*Unit test*).
- Pengertian pada masalah.
- Penggunaan `git`.
- Implementasi dan eksekusi akhir.
- *Commits*, ini akan membantu kami untuk mengerti, bagaimana alur kerja dan keputusan anda selama mengerjakan *task* ini.

## User Story
Sebagai *User*, saya ingin mendapatkan sekumpulan resep, apa yang dapat saya persiapkan untuk makan siang hari ini, berdasarkan bahan - bahan di kulkas saya. Sehingga saya dapat memutuskan apa yang akan saya makan.

__Kriteria Utama__
- Ketika saya memulai aplikasi, saya harus dapat mengisikan tanggal makan siang yang saya inginkan, atau tanggal tersebut menjadi tanggal hari ini apabila tidak saya isi.
- Ketika saya melakukan request ke endpoint `/ingredients`, saya harus mendapatkan *response* bahan - bahan yang ada di kulkas saya dalam bentuk data `JSON`.
- Ketika saya mendapatkan pilihan bahan - bahan saya, saya harus memilih beberapa bahan untuk mendapatkan rekomendasi resep.
- Ketika ada bahan saya, yang sudah melewati tanggal `use-by`, saya harus tidak dapat memilih bahan tersebut.
- Ketika saya sudah memilih bahan - bahan saya, saya harus melakukan request ke endpoint `/recipes` dengan *query parameter* sebagai berikut `?ingredients=<title-1>,<title-2>,<title-n>`
- Ketika saya mendapatkan hasil dari resep yang tersedia, saya harus dapat melihan daftar resep beserta dengan bahan - bahannya di setiap resep.

__Kriteria Tambahan__
- Aplikasi HARUS memiliki unit / component tests (contohnya `Mocha.js`).
- Semua dependencies HARUS diinstal melalui *dependency management tools* (`npm` atau `yarn`).
- Semua instruksi untuk instalasi, cara build, testing dan menjalankan HARUS tersedia pada file `README.md` yang berada di folder utama aplikasi. __Jangan menggunakan *file* yang *auto generated*__

## Framework
Gunakan *framework* `React.js` atau `Vue.js`.  

## API Endpoint
__Dokumentasi__

https://documenter.getpostman.com/view/9359572/SW17TFmK

__Mock Base URL__

https://a61d556b-57ca-423f-8706-2e8dec75d714.mock.pstmn.io

__Instruksi__
1. Gunakan `/ingredients` untuk mendapatkan bahan - bahan saya yang ada di kulkas
2. Gunakan `/recipes?ingredients=<title-1>,<title-n>` untuk mendapatkan resep berdasarkan nama bahan - bahan yang saya inginkan

__CATATAN : API ini hanyalah *mock server* untuk mensimulasikan *request* dan *response* dari API. Jadi hasil dari API ini, tidak akan mempengaruhi hasil akhir anda.__ 
 
## Submission
Aplikasi harus di *commit* ke __public repository__ di `GitHub` or `BitBucket` (`<lastname>-<firstname>-techtask-frontend`) dan mohon informasikan *link repository* anda kepada kami.