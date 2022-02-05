# OpenVPN install
Serangan privasi pada jaringan komputer memiliki ancaman yang signifikan seiring perkembangan jaman, salah satunya bocornya informasi saat bertukar data pada jaringan komputer, ie. serangan MITM (Man In The Middle) Attack. sebagai upaya dalam menjaga kemanan bertukar data, dipilihlah salah satunya teknologi VPN. <br />
<br />teknologi VPN atau Virtual Private Network adalah sebuah teknologi tunneling dimana jaringan yang tadinya publik dapat berkomunikasi dengan jaringan lokal seolah-olah mereka satu jaringan secara private, dapat berkirim data dengan keamanan ekstra. Nah pada modul kali ini saya akan memberikan paduan cara menerapkan jaringan virtual dengan jenis teknologi virtual network OpenVPN. <br />
<br />OpenVPN merupakan jenis VPN yang memanfaatkan authentikasi data jarak jauh, disini sebelum client dengan server berkomunikasi, mereka membutuhkan sertifikat `CA (Certificate Authority)` sebagai metode bertukar data.

Langsung saja masuk ke konfigurasi. disini silakan teman-teman clone repository ini dengan perintah :

```bash 
git clone https://github.com/hawk-xc/OpenVPN-auto-installer.git
```

setelah itu `run` executable file dengan perintah.

```bash
./OpenVPN-auto-installer/openvpn-install.sh
```
