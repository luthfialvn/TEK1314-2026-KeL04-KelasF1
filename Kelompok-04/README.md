# Logbook Proyek PBL Keamanan Siber - Kelompok 4
**Skenario:** Data Integrity (NAS/Samba)

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
  [Bukti Screenshot Instalasi VM Utama](Documentation/images/vm-utama.png)
  [Bukti Screenshot Instalasi VM Backup](Documentation/images/vm-backup.png)

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
  - 📄 [IP Address Plan](docs/design/ip_plan.md)
  - 🖼️ [Network Topology](docs/design/topology.png)

### Update Minggu ke-4-7 (Fase Hardening & Baseline)
- **Target:** Penguatan OS & Dokumentasi kondisi normal.
- **Update 10 Maret 2026:** 
- Melakukan Konfigurasi Firewall di Windows WM.
- Menjalankan Wireshark untuk merekam traffic normal (baseline).

- Status: **Fase 1 Selesai**
  - [Bukti Logging Check](docs/phase-1-baseline/assets/Bukti Logging Minggu5.jpeg)
