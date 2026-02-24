# TEK1314-2026-KeL04-KelasF
Repository tugas mata kuliah Keamanan Siber Tahun 2026

# Logbook Proyek PBL Keamanan Siber - Kelompok 4
**Skenario:** Data Integrity (NAS/Samba)
## Deskripsi Skenario – Data Integrity Shield

Skenario **Data Integrity Shield** berfokus pada perlindungan integritas data pada sebuah File Server berbasis protokol SMB (Samba). Skenario ini mensimulasikan ancaman ransomware, yaitu serangan yang melakukan enkripsi massal terhadap file sehingga data tidak dapat diakses oleh pengguna.

Arsitektur yang dirancang terdiri dari tiga komponen utama: Attacker Node, Target File Server, dan Monitoring Node (Security Onion). Attacker akan mensimulasikan proses enkripsi terhadap file dummy yang telah disiapkan, bukan file sistem asli, untuk menjaga keamanan lingkungan virtual. Monitoring Node bertugas merekam serta menganalisis aktivitas jaringan guna mendeteksi perilaku mencurigakan yang mengindikasikan terjadinya serangan.

Melalui skenario ini, diharapkan dapat dipahami bagaimana serangan terhadap integritas data terjadi, bagaimana pola aktivitasnya terdeteksi melalui analisis log dan monitoring jaringan, serta bagaimana langkah penahanan dan pemulihan dilakukan agar sistem dapat kembali berjalan normal.

**Anggota:** 
1. Luthfi Alviani (J0404231023) - Lead Analyst 
2. Althof Zufar Musyaffa (J0404231119) - Security Engineer 
3. Bagus Priwendy Simangunsong (J0404221036) - Analyst --- 
## Log Aktivitas Mingguan 
### Minggu 1-2: Fase Setup 
- **Target:** Instalasi CyberOps VM & Security Onion.
- **Update 8 Febuari 2026:**
- Berhasil instalasi VM di Laptop Altof Zufar Musyaffa dan Luthfi Alviani
- Kendala: tidak ada
- Artefak:
  [Bukti Screenshot Instalasi VM Utama](Kelompok-04/Documentation/images/vm-utama.png)
  [Bukti Screenshot Instalasi VM Backup](Kelompok-04/Documentation/images/vm-backup.png)

### Update Minggu ke-3 (Fase Design)
- **Target:** Perancangan arsitektur jaringan dan skema IP Address.
- **Update 16 Febuari 2026:**
- Membuat desain topologi jaringan yang terdiri dari Attacker Node, Target File Server (Samba), dan Monitoring Node (Security Onion).
- Menentukan subnet network dan pembagian IP Address statis untuk setiap node.
- Menyusun tabel IP Address (ip_plan.md) sesuai segmen jaringan yang telah ditentukan.
- Menentukan sistem operasi yang akan digunakan pada masing-masing node:
  - Attacker Node: Kali Linux
  - Target Server: Ubuntu Server (Samba File Server)
  - Monitoring Node: Security Onion
- Status: **Fase Design Selesai.**
  - 📄 [IP Address Plan](Kelompok-04/documentation/ip_plan.md)
  - 🖼️ [Network Topology](Kelompok-04/documentation/images/topology.png)



