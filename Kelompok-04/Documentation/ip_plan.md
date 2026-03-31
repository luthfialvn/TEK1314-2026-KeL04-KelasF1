# IP Address Plan - Kelompok 4 Siber (Data Integrity Shield)

## Network Information

- **Subnet** : 192.168.4.0/24  
- **Subnet Mask** : 255.255.255.0  
- **Core Switch / Gateway** : 192.168.4.1  
- **Usable IP Range** : 192.168.4.1 - 192.168.4.254  
- **Broadcast Address** : 192.168.4.255  

---

## Attacker Nodes

| Hostname   | Role     | IP Address      | Operating System |
|------------|----------|----------------|------------------|
| attacker-1 | Attacker | 192.168.4.100  | Kali Linux       |

---

## Target Nodes

| Hostname           | Role              | IP Address      | Operating System      |
|--------------------|-------------------|----------------|-----------------------|
| kelompok4-1      | Web Server        | 192.168.4.20   | Ubuntu Server CLI     |

---

## Monitoring Node

| Hostname   | Role        | IP Address     | Operating System |
|------------|------------|---------------|------------------|
| SecOnion | IDS / SIEM | 192.168.4.5   | Security Onion   |

---

## Port Plan (Data Integrity Shield Scenario)

| Service            | Port  | Protocol | Keterangan                          |
|--------------------|-------|----------|--------------------------------------|
| SMB (Samba)        | 445   | TCP      | Akses file sharing utama (Target)    |
| NetBIOS Session    | 139   | TCP      | Dukungan komunikasi SMB lama         |
| SSH                | 22    | TCP      | Remote management server             |
| Elastic / SIEM     | 5601  | TCP      | Monitoring dashboard (Security Onion) |
| MySQL (Optional)   | 3306  | TCP      | Jika menggunakan database tambahan   |
