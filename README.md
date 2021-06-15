
# Project_PSBO
Nama Sistem : Gofind<br />
Paralel Praktkum : P1<br />
Nomor Kelompok : 03<br />

# Deskripsi Aplikasi 
Kami ingin membuat ide atau solusi yang dimana user bisa memperlihatkan track record serta keahlian yang mereka miliki untuk bisa ikut dalam sebuah proyek nyata. User bisa memasukan social media dan cv yang berupa link sehingga user lain bisa langsung melihat social media dan cv nya secara langsung. User juga bisa membuat projek dengan memasukan deskripsi, start-deadline serta photo untuk memperlihatkan informasi lengkap proyek yang ingin diikuti. User juga bisa memilih orang yang sesuai dengan kriteria yang user inginkan dengan cara melihat role, specialist, social media, cv serta track record dari proyek apa saja yang diikuti. User yang ingin membuat proyek atau mengikuti proyek tidak dibatasi dengan jurusan atau departemen tertentu, user bisa membuat atau mengikuti proyek apapun tanpa terpaku dengan jurusan atau departemen tertentu. Namun user hanya dapat berada dalam satu projek dalam satu waktu. Dengan adanya solusi tersebut, diharapkan user dapat meningkatkan kualitas kemampuannya dan memperbanyak pengalaman mereka.

## User Analysis
### User Story
1. Sebagai Mahasiswa IPB yang sedang mencari rekan untuk mengikuti lomba/projek, saya ingin menemukan partner yang sesuai dengan keahlian yang saya butuhkan untuk membantu saya dalam mengerjakan proyek.
2. Sebagai Mahasiswa IPB yang memiliki keahlian yang ingin disalurkan, saya ingin menemukan lomba atau projek nyata yang cocok dengan keahlian yang saya miliki saat ini.

## Spesifikasi teknis lingkungan pengembangan
### Software
![enter image description here](https://scontent-sin6-2.xx.fbcdn.net/v/t1.15752-9/192647828_350186593197721_8066950454003592681_n.png?_nc_cat=103&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeGPTj6WD-XV0RKsPUJMasCGflueE4t0Zox-W54Ti3RmjN9r6CIfGDZwGMP0VwrIFcGp4dxjWdmoaDVaj6lGe7ds&_nc_ohc=-a1SxhVI6aIAX8BoG24&_nc_ht=scontent-sin6-2.xx&oh=3fe1a5df7e2c008ef12b0db9730b4c9c&oe=60DBF9B2)
### Hardware
-   **Nama:**  Samsung Galaxy A11
-   **Berat:** 177 gram (g)
-   **Material:**  Depan kaca, bingkai dan belakang plastik
-   **Jenis dan Ukuran Layar:** PLS IPS dan 6,4 inci (~81.6% rasio layar ke bodi)
-   **Resolusi Layar:** 720 x 1.560 piksel, 19.5:9 ratio (~268 piksel per inci)
-   **Chipset:**  Qualcomm Snapdragon 450 (11 nm)
-   **CPU:**  Octa-core 1.8 GHz Cortex-A53
-   **GPU:**  Adreno 506
-   **RAM:** 3 GB
-   **Memori Internal:**  64 GB
-   **Kamera Belakang:**  13 MP (f/1.8, 27mm wide, AF) + 5 MP (f/2.2, 115˚ ultrawide) +  
    2 MP (f/2.4, depth)
-   **Kamera Depan:** 8 MP, f/2.0
-   **Bluetooth:** 4.2, A2DP, LE
-   **Sensor:** Sidik jari (di belakang),  _accelerometer, proximity_
-   **Baterai:**  Li-Po 4000 mAh, non-removable, Fast charging 15W
### TechStack
Aplikasi **GoFind** adalah aplikasi yang berbasis Mobile yang dibuat menggunakan framework Flutter yang adalah SDK (_Software Development Kit_) yang dikembangkan oleh Google untuk membuat aplikasi yang bagus dan bisa berjalan pada berbagai platform. Backend untuk aplikasi ini menggunakan MongoDB, Express, ODM Mongoose, dan Thunder Client untuk aplikasi ini.

**Framework Frontend** : Flutter SDK<br />
**Framework Backend** : MongoDB, Express, ODM Mongoose, dan Thunder Client<br />
**Output** : Mobile Application<br />
## Konsep OOP yang digunakan
* #### Mendefenisikan Kelas
* #### Variabel Instans (attribut)
* #### Method Getter & Setter
* #### Penamaan Konstruktor

## Tipe desain pengembangan yang digunakan (Pattern/Anti Pattern)
Kami menggunakan metode waterfall dalam pengembangan sistem ini. Pengembangan sistem aplikasi dengan metode waterfall yang terdiri dari tahap Requirement, Design System, Coding, Integration dan Operation serta Maintenance. Disebut sebagai metode waterfall dikarenakan tahapan dan juga urutan dari metode yang dilakukan merupakan jenis metode yang berurutan dan berkelanjutan, seperti layaknya sebuah air terjun.

Kelebihan dari metode Waterfall adalah :

1.  Memiliki proses yang terurut
    
2.  Proses yang dilakukan tidak tumpah tindih
    
3.  Setiap proses memiliki spesifikasinya sendiri, sehingga sebuah sistem dapat dikembangkan sesuai dengan apa yang dikehendaki.
    

Metode pengembangan waterfall memiliki beberapa tahapan yang berurut yaitu:

**1.  Requirement analysis**
    

Tahap dimana kita harus memahami perangkat lunak yang diharapkan oleh pengguna dan batasan software yang ingin kita rancang Informasi ini biasanya dapat diperoleh melalui wawancara, diskusi atau survei langsung. Informasi dianalisis untuk mendapatkan data yang dibutuhkan oleh pengguna.

**2.  Design System**
    

Proses desain akan diterjemahkan syarat kebutuhan ke sebuah perancangan perangkat lunak yang dapat diperkirakan sebelum dibuat koding. Proses ini berfokus pada struktur data, rancangan perangkat lunak, representasi interface, dan detail (algoritma) prosedural. Tahapan ini akan dihasilkan dokumen yang disebut software requirement. Dokumen inilah yang akan digunakan untuk melakukan aktivitas pembuatan sistemnya.

**3.  Coding & System**
    

Coding merupakan penerjemahan desain dalam bahasa yang dapat dikenali oleh komputer. Tahapan ini merupakan tahapan nyata dalam mengerjakan suatu sistem. Setelah pengkodean selesai selanjutnya akan dilakukan testing terhadap sistem yang telah dibuat tadi. Testing dilakukan bertujuan menemukan kesalahan-kesalahan terhadap sistem tersebut kemudian dapat dilakukannya sebuah perbaikan.

**4.  Integration**
    

Tahapan penetapan dapat dikatakan sebagai tahap final dalam pembuatan suatu sistem. Setelah dilakukan tiga tahap metode sebelumnya, sistem ini siap digunakan oleh user.

**5.  Operation & Maintenance**
    

Sistem perangkat lunak yang sudah diintegrasikan kepada user, tentunya akan mengalami perubahan. Perubahan tersebut terjadi sebab sistem dapat mengalami kesalahan dan harus menyesuaikan dengan lingkungan baru. Perubahan dapat juga terjadi terhadap sistem yang disebabkan oleh kebutuhan pelanggan akan perkembangan fungsional.

## Hasil dan pembahasan

### Use case diagram
![enter image description here](https://scontent-sin6-3.xx.fbcdn.net/v/t1.15752-9/190739721_500564834426213_8908409490674910310_n.png?_nc_cat=106&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeG1b7Ol2W72ozxDSQdW0s43B8GS4hoal00HwZLiGhqXTaAzrLjC4f_FrAV_SgHMV46s2O0WihfEqCItYGyBdC-B&_nc_ohc=2zKuDMgqUJwAX_y2jNv&_nc_ht=scontent-sin6-3.xx&oh=05c9da7e3ee4d6872ba971d345768edc&oe=60DA8E0D)
### Activity diagram
![enter image description here](https://scontent-sin6-1.xx.fbcdn.net/v/t1.15752-9/191771040_165196392231468_6306552687355517317_n.png?_nc_cat=101&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeFxPFSVLdFh6Yb4CMCa0Uku7Lvx6QaX-irsu_HpBpf6KnV8L_9bOCYz-ApLglTJPlYC7eDm4De2Gmj0t303M_GM&_nc_ohc=zvt8I284Cd4AX-tr5T1&tn=xAo5jjmYoiaU7dPL&_nc_ht=scontent-sin6-1.xx&oh=6e073fcb7c73c4aafe95f0a774b188b4&oe=60DACACA)
![enter image description here](https://scontent-sin6-1.xx.fbcdn.net/v/t1.15752-9/191768009_384165572970675_1360656015580899056_n.png?_nc_cat=100&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeHqVJWEqKOBYHvhNXXu1w9rTR-lEaIYPM9NH6URohg8zxyu6Xn1MNxdDmbMu4KUIdImIzn_w_tzam1aYopKTn0A&_nc_ohc=GSz2xmmlaOMAX9zOr0o&_nc_ht=scontent-sin6-1.xx&oh=1f62cf4fda52935127020200f128fd07&oe=60DB875D)
![enter image description here](https://scontent-sin6-1.xx.fbcdn.net/v/t1.15752-9/190984691_771870333522544_2577144138558800129_n.png?_nc_cat=111&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeH7DO2i9dTRmzhbwuQoZFaL3930kDQtmH3f3fSQNC2YfVhE4TXbgjMhSnPFuwqxPUZJFQB4Eo1BHoD2A5I-yDNm&_nc_ohc=YXOboZmedFQAX8IbPJ8&_nc_ht=scontent-sin6-1.xx&oh=159096a4fbe0652cdb32bb1ab5d4874b&oe=60DA3AEA)
### Class diagram
![enter image description here](https://scontent-sin6-1.xx.fbcdn.net/v/t1.15752-9/191351829_144046597718112_8409705003102667686_n.png?_nc_cat=100&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeHOWFQO9nhi7AI_zn0V83Yqu0GVJTWEQkC7QZUlNYRCQO92TK1nAzWfeQPrZOkpZu9XhI1FffQwzslYO8Wg_jwo&_nc_ohc=qrK1M6EpCXQAX__BAcN&_nc_ht=scontent-sin6-1.xx&oh=024045a485279932aca5c0fa87c04053&oe=60D9FA80)
### Entity Relationship Diagram
![enter image description here](https://scontent.fcgk18-2.fna.fbcdn.net/v/t1.15752-9/197460782_4325891917445414_6553478069443013236_n.png?_nc_cat=110&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeGmm5Lvgb6u9hWxF5IOpzBk8HdZKf8awAfwd1kp_xrAB_S5bw20Ap9ATuG5olgpiio5DnM1zA5DVCNRw2ecpgEi&_nc_ohc=HeUQfZGySNgAX8ph8I2&tn=xAo5jjmYoiaU7dPL&_nc_ht=scontent.fcgk18-2.fna&oh=3dc648675ed6f71839af8d826231ee69&oe=60E6C83E)
### Arsitektur sistem
![enter image description here](https://scontent.fcgk8-1.fna.fbcdn.net/v/t1.15752-9/200212655_234929138098479_9048520659434407682_n.png?_nc_cat=111&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeE_OetGLT2ADZxa05fySTvt64jbcsuHyvXriNtyy4fK9Ye1BkbCfaSnEyUCp2jiedSCbLvH_xaVtYxJHm7Ev-MR&_nc_ohc=jfCUirUAtzcAX-MCRdC&tn=xAo5jjmYoiaU7dPL&_nc_ht=scontent.fcgk8-1.fna&oh=5d1b72c5e5e7458f1079cf64f6ba49df&oe=60CE0177)
### Fungsi utama yang dikembangkan
Fungsi Utama yang dikembangkan adalah Pembuatan project yang dibuat oleh Project Manager dan Project tersebut dapat diikuti oleh pengguna lain yang sedang mencari project. 
### Fungsi CRUD
1. Create Project: Pengguna dapat membuat project dengan atribut nama, deskripsi, estimated time dan project photos. Untuk Project Manager akan menggunakan Id User yang sudah membuat Project
2. Read Projet: Pengguna dapat melihat project pengguna lain dan project yang sudah dia buat pada halaman utaan
3. Update Project: Pengguna yang merupkana Project Manager dapat memperbarui atribut project nama, deskripsi dan estimated time selama project member belum di rekrut.
4. Delete Project: Pengguna yang merupakan Project Manager dapat menghapus projeect selama project member belum di rekrut. 


## Hasil implementasi
### Screenshot sistem
### Link aplikasi
https://github.com/AnzeHabibi/Project_PSBO

## Saran untuk pengembangan selanjutnya
Akan dilakukan maintenance dari sistem yang telah dibuat dan akan dievaluasi apakah sistem sudah berjalan sesuai kebutuhan pengguna atau belum. Jika belum akan tingkatkan lagi bagian yang kuran, namun jika sudah akan dibuat fitur baru yang sekiranya bisa menambah kinerja sistem tersebut. 
## Developer dan job desc
|No.|Nama|Jobdesk|
|--|--|--|
|1.|**Muhammad Abiyyu Habibi** (G64180066)|Frontend Developer and UI/UX Designer|
|2.|**Muhammad Fauzan Ramadhan** (G64180117)|Project Manager dan Frontend Developer|
|3.|**Reza Achmad Naufal** (G64180078)|Backend Developer|
|4.|**Mohammad Thareeq Izzulhaq** (G64180041)|Backend Developer|
|5.|**Muhammad Hafiduddin** (G64180017)|Frontend Developer|
