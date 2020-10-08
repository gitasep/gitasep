# Membuat Hostpot Pada Windows CMD
## 1. Check WLAN Apakah didukung dijadikan sebagai hostpot
```
NETSH WLAN show drivers
```
Jika menampilkan dibagaian “Yes” selanjutnya “Hosted network supported” artinya WLAN bisa dijadikan sebagai host

## 2. Buat Host 
```
netsh wlan set hostednetwork mode=allow ssid=NAMAJARINGAN key=katakunci
```

## 3. Hidupkan host telah dibuat atau sebaliknya
Untuk menjalankan
```start
NETSH WLAN start hostednetwork
```
Atau Untuk Memberhentikan
```stop
NETSH WLAN stop hostednetwork
```
