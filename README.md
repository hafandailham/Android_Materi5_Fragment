# Fragment 
Fragment adalah komponen yang memiliki fungsi untuk menampilkan antarmuka ke pengguna melalui activity dengan memiliki layout xml sendiri, Fragment digunakan agar komponen tampillan aplikasi menjadi fleksibel dan dapat digunakan kembali ( reusable). Fragment juga bisa disebut sub nya activity, satu activity bisa memiliki lebih dari satu fragment. Satu kelas Java dinyatakan sebagai sebuah fragment ketika kelas tersebut meng-extends (inherit) kelas Fragment.
# LifeCycle Fragment
Class fragment memiliki kode yang terlihat hampir seperti Activity. Fragment berisi method callback mirip dengan Activity, seperti onCreate (), onStart (), onPause (), dan OnStop (). Siklus hidup dari fragment berhubungan dengan siklus hidup Activity, berikut tahapan siklus hidup fragment yang berkaitan dengan siklus hidup dari activity.
- Activity onCreate() dipanggil, dimana activity dapat mengatur tampilan dengan menggunakan method setContentView().
- onAttach() dipanggil setelah fragment dikaitkan dengan activity. Fragment mendapat refrensi ke objek activity yang dapat digunakan sebagai konteks.
- onAttachFragment dipanggil oleh activity untuk menotifikasi activity bahwa fragment telah di attach.
- onCreate () dipanggil ketika saat dibuat fragment.
# Output
![WhatsApp Image 2021-02-25 at 21 52 39(1)](https://user-images.githubusercontent.com/63888291/109171993-e3869a00-77b4-11eb-91f7-be8980f88b7b.jpeg)
![WhatsApp Image 2021-02-25 at 21 52 39](https://user-images.githubusercontent.com/63888291/109172012-e6818a80-77b4-11eb-9995-2f9df06c1347.jpeg)
