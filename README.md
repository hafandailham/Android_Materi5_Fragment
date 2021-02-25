# Fragment 
Fragment adalah komponen yang memiliki fungsi untuk menampilkan antarmuka ke pengguna melalui activity dengan memiliki layout xml sendiri, Fragment digunakan agar komponen tampillan aplikasi menjadi fleksibel dan dapat digunakan kembali ( reusable). Fragment juga bisa disebut sub nya activity, satu activity bisa memiliki lebih dari satu fragment. Satu kelas Java dinyatakan sebagai sebuah fragment ketika kelas tersebut meng-extends (inherit) kelas Fragment.
# LifeCycle Fragment
Class fragment memiliki kode yang terlihat hampir seperti Activity. Fragment berisi method callback mirip dengan Activity, seperti onCreate (), onStart (), onPause (), dan OnStop (). Siklus hidup dari fragment berhubungan dengan siklus hidup Activity, berikut tahapan siklus hidup fragment yang berkaitan dengan siklus hidup dari activity.
- Activity onCreate() dipanggil, dimana activity dapat mengatur tampilan dengan menggunakan method setContentView().
- onAttach() dipanggil setelah fragment dikaitkan dengan activity. Fragment mendapat refrensi ke objek activity yang dapat digunakan sebagai konteks.
- onAttachFragment dipanggil oleh activity untuk menotifikasi activity bahwa fragment telah di attach.
- onCreate () dipanggil ketika saat dibuat fragment.
