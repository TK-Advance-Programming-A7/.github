> Proyek ini dibuat untuk memenuhi tugas Proyek Akhir Semester (PAS)
> pada mata kuliah Pemrograman Lanjut (CSCM602223) yang
> diselenggarakan oleh Fakultas Ilmu Komputer, Universitas Indonesia
> pada Semester Genap, Tahun Ajaran 2023/2024.

--------------------------------------------------------------------------------------------

## Kelompok A-7

-  [Eryawan Presma Yulianrifat](https://github.com/eryawww) `(2206041335)`<br>
-  [Restu Ahmad Ar Ridho](https://github.com/restuaar) `(2206028951)`<br>
-  [Samuel Taniel Mulyadi](https://github.com/SamuelTanielM) `(2206081805)`<br>
-  [Tegar Wahyu Khisbulloh](https://github.com/tegar-wahyu) `(2206082032)`<br>
-  [Vinka Alrezky As](https://github.com/vinkakniv) `(2206820200)`<br>

## Technology Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
--------------------------------------------------------------------------------------------

## Architecture Diagram
### Context Diagram
[](https://ibb.co.com/SdK5S7y)
<a href="https://ibb.co.com/FhZgstc"><img src="https://i.ibb.co.com/0n4hB31/Class-Diagram-Adpro-a7-drawio-1.png" alt="Class-Diagram-Adpro-a7-drawio-1" border="0"></a>

### Container Diagram
<a href="https://ibb.co.com/SdK5S7y"><img src="https://i.ibb.co.com/xfMXZ8L/Class-Diagram-Adpro-a7-drawio.png" alt="Class-Diagram-Adpro-a7-drawio" border="0" /></a>

### Deploy Diagram
<a href="https://ibb.co.com/Zc6MvPx"><img src="https://i.ibb.co.com/F8bDcMz/Class-Diagram-Adpro-a7-drawio-2.png" alt="Class-Diagram-Adpro-a7-drawio-2" border="0"></a>

## Architectual Risk
Dalam skenario di mana proyek Buku.ID sangat sukses, beberapa risiko arsitektur perlu dipertimbangkan untuk memastikan sistem tetap handal, aman, dan mampu menangani beban yang meningkat.

### Risk Storming Buku.ID 

1. Risiko Skalabilitas

	Deskripsi: Sistem mungkin melambat atau tidak bisa menangani banyak pengguna.  
	Dampak: Akses lambat dan potensi downtime.  
	Mitigasi: Gunakan load balancing, optimalkan kode, dan tingkatkan kapasitas server.  

2. Risiko Keamanan

	Deskripsi: Sistem bisa menjadi target serangan siber karena menyimpan data sensitif.  
	Dampak: Kebocoran data dan hilangnya kepercayaan pelanggan.  
	Mitigasi: Enkripsi data, lakukan audit keamanan, dan gunakan autentikasi multi-faktor.  

3. Risiko Keandalan Sistem

	Deskripsi: Sistem harus tetap berfungsi meski pengguna bertambah banyak.  
	Dampak: Layanan terganggu dan penjualan berkurang.  
	Mitigasi: Buat sistem cadangan, pantau sistem secara real-time, dan lakukan backup data.  

4. Risiko Konsistensi Data

	Deskripsi: Data antara sistem Internet dan Mainframe harus selalu sinkron.  
	Dampak: Data tidak konsisten bisa menyebabkan kesalahan informasi.  
	Mitigasi: Gunakan mekanisme transaksi yang kuat, sinkronkan data secara real-time, dan audit data secara berkala.  

## Teknik Risk Storming
Teknik Risk Storming digunakan untuk mengidentifikasi dan mengatasi risiko dengan langkah-langkah berikut:
Identifikasi Risiko: Mengumpulkan semua potensi risiko yang mungkin terjadi.  
Analisis Risiko: Menilai setiap risiko berdasarkan kemungkinan dan dampaknya.  
Strategi Mitigasi: Mengembangkan langkah-langkah konkret untuk mengurangi atau menghilangkan risiko.  
Pelaksanaan dan Pemantauan: Mengimplementasikan strategi mitigasi dan memantau efektivitasnya secara berkala.

Menggunakan teknik Risk Storming membantu kita secara sistematis mengidentifikasi, menganalisis, dan mengatasi risiko arsitektur yang mungkin muncul seiring dengan kesuksesan proyek. Teknik ini memastikan bahwa setiap risiko dievaluasi dengan baik dan solusi mitigasi diterapkan untuk menjaga kinerja, keamanan, keandalan, dan konsistensi data sistem.




