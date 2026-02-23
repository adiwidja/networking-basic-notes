# Networking & Basic Cyber Security Notes
Repository ini berisi catatan dasar Networking, Subnetting, dan sedikit konsep Cyber Security yang saya pelajari dan gunakan dalam pekerjaan IT Support.

# 🌐 1. IP Address

IP Address adalah alamat unik setiap perangkat dalam jaringan.

Contoh cek IP di Windows:
ipconfig

Private IP:
- 192.168.x.x
- 10.x.x.x
- 172.16.x.x – 172.31.x.x

Public IP:
IP yang digunakan untuk akses internet.

---

# 🌐 2. OSI Layer (Ringkasan)

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

Layer 3 → Routing (IP Address)
Layer 4 → Port & Protocol (TCP/UDP)

---

# 🌐 3. Subnetting Basic

Subnetting digunakan untuk membagi jaringan menjadi beberapa network kecil.

Contoh:
IP: 192.168.1.0/24

/24 berarti:
- 255.255.255.0
- Total 256 IP
- 254 host usable

Semakin besar angka CIDR (/25, /26, dst):
→ Network makin kecil
→ Host makin sedikit

---

# 🌐 4. Common Port

80   → HTTP  
443  → HTTPS  
22   → SSH  
21   → FTP  
3389 → RDP  
53   → DNS  

Cek port di Windows:
netstat -an

---

# 🔐 5. Basic Cyber Security Concept

## a. Firewall
Digunakan untuk memfilter traffic masuk dan keluar jaringan.

## b. Open Port Risk
Port yang terbuka bisa menjadi celah keamanan jika tidak diamankan.

## c. Brute Force Attack
Serangan mencoba login berkali-kali sampai berhasil.

## d. Basic Scanning
Menggunakan tools seperti Nmap untuk mengecek port dan service.

---

# 🛠 Basic Networking Command

ping 8.8.8.8
tracert google.com
nslookup google.com
ipconfig /all
netstat -an
