# TEK1314-2025-KeL04-KelasF
Repository tugas mata kuliah TEK1314 Tahun 2026

## Deskripsi Skenario – Data Integrity Shield

Skenario **Data Integrity Shield** berfokus pada perlindungan integritas data pada sebuah File Server berbasis protokol SMB (Samba). Skenario ini mensimulasikan ancaman ransomware, yaitu serangan yang melakukan enkripsi massal terhadap file sehingga data tidak dapat diakses oleh pengguna.

Arsitektur yang dirancang terdiri dari tiga komponen utama: Attacker Node, Target File Server, dan Monitoring Node (Security Onion). Attacker akan mensimulasikan proses enkripsi terhadap file dummy yang telah disiapkan, bukan file sistem asli, untuk menjaga keamanan lingkungan virtual. Monitoring Node bertugas merekam serta menganalisis aktivitas jaringan guna mendeteksi perilaku mencurigakan yang mengindikasikan terjadinya serangan.

Melalui skenario ini, diharapkan dapat dipahami bagaimana serangan terhadap integritas data terjadi, bagaimana pola aktivitasnya terdeteksi melalui analisis log dan monitoring jaringan, serta bagaimana langkah penahanan dan pemulihan dilakukan agar sistem dapat kembali berjalan normal.
