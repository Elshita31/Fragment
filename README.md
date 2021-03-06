# Fragment
<h2>Apa itu Fragment?</h2>
<h5>Fragment merupakan salah satu komponen pada Android Studio dengan fungsi yang hampir sama seperti activity tetapi memiliki “lifecycle” yang berbeda. 
Fragment merupakan bagian dari sebuah activity yang mana sebuah fragment tidak akan ada bila tidak ada sebuah activity karena fragment membutuhkan akses 
dari activity untuk dapat dijalankan.</h5>

<h2>Apa Kelebihan yang dimiliki Fragment?</h2>
<h5>Kelebihan yang didapatkan bila menggunakan fragment adalah sebagai berikut:</h5>
<h5>Tidak perlu memasukkan nama file fragment ke dalam “AndroidManifest” yang diperlukan oleh activity.
Fungsi yang berada pada activity dapat langsung digunakan dalam fragment tersebut tanpa harus membuat ulang. 
Contoh: pada saat back, fragment hanya perlu memanggil fungsi “getactivity</h5>

<h2>Lifecycle Fragment</h2>
<img src="fragment lifecycle.jpg" height="600px" width="300px">
<h4>Keterangan</h4>

<h5>• onAttach() dipanggil saat sebuah fragment terhubung ke activity.	</h5>  
<h5>•	onCreate() adalah kondisi awal saat Activity baru diciptakan, biasanya dilakukan inisialisasi pada tahapan ini.</h5>  
<h5>•	onCreateView() dipanggil saat fragment sudah siap membaca sebuah layout.</h5> 
<h5>•	onViewCreated() dipanggil setelah onCreateView() dan memastikan layout yang dibaca fragment adalah non-null. Semua pengaturan view seperti pembacaan findViewById, menambah onClickListener dapat dilakukan di sini</h5> 
<h5>•	onActivityCreated() dipanggil setelah activity pembaca sudah menyelesaikan onCreate()-nya.</h5> 
<h5>•	onStart() adalah saat Activity dimulai.</h5>  
<h5>•	onResume() adalah saat Activity dibuka kembali, biasanya dieksekusi setelah onPause().</h5>  
<h5>•	onPause() akan dipanggil saat ada Activity lain yang terbuka.</h5>  
<h5>•	onDestroyView() dipanggil saat layout sebuah fragment akan dihapus dari memori, namun fragmentnya masih ada di memori.</h5> 
<h5>•	onDestroy() adalah kondisi saat Activity dihancurkan pada memori.</h5>  
<h5>•	onDetach() dipanggil saat fragment tidak lagi terhubung ke sebuah activity.</h5> 

<h2>Screenshot Aplikasi Fragment</h2>
<img src="1.jpg" height="600px" width="300px">
<img src="2.jpg" height="600px" width="300px">
