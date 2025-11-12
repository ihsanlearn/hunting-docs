# Naabu Scan

**Naabu** adalah pemindai port (port scanner) yang sangat cepat. Dibuat oleh Project Discovery.

#### Tujuan Penggunaan:

* Kecepatan: `naabu` dirancang untuk memindai ribuan atau bahkan jutaan IP/domain dengan sangat cepat untuk menemukan port yang terbuka.
* Fokus: Tujuannya sederhana: Cek IP, temukan port terbuka, laporkan.
* Sinergi (Pipa): `naabu` paling sering digunakan bersama _tools_ lain. Ia menemukan "pintu" (port), lalu hasilnya di-pipe (`|`) ke _tool_ lain (seperti `httpx`) untuk "melihat apa yang ada di balik pintu".

#### Perbedaannya dengan Nmap:

* `nmap` seperti pisau bedah Swiss Army: Bisa melakukan _semuanya_ (deteksi versi, deteksi OS, menjalankan _script_ NSE), tapi lebih lambat jika targetnya ribuan IP.
* `naabu` seperti parang: Sangat cepat untuk satu tugas: menebas dan menemukan port terbuka di _scope_ yang sangat luas.

***
