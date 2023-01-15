
# Jojonomic Test Assessment

Untuk menjalankan aplikasi ini, jalankan docker-compose.yaml yang berada di direktori misc 
```
./jojo/
│
├──1.1.input-harga-emas-storage-service
├──1.2.input-harga-emas-service
├──2.cek-harga-emas-service
├──3.1.customer-topup-storage-service
├──3.2.customer-topup-service
├──4.cek-saldo-service
├──5.cek-mutasi-service
├──6.1.buyback-storage-service
├──6.2.buyback-service
├──misc
│   ├──docker-compose.yaml
│   ├──init.sql
│   └──Jojonomic.postman_collection.json
│
└── README.md
```

jalankan terminal kemudian eksekusi cli berikut :
```bash
docker-compose up -d
```

setelah semua container berjalan tanpa kendala, jalankan semua main.go yang berada di dalam folder berikut:

```
./jojo/
│
├──1.1.input-harga-emas-storage-service
├──1.2.input-harga-emas-service
├──2.cek-harga-emas-service
├──3.1.customer-topup-storage-service
├──3.2.customer-topup-service
├──4.cek-saldo-service
├──5.cek-mutasi-service
├──6.1.buyback-storage-service
└──6.2.buyback-service
```

dengan cli : 
```
go run main.go
```

untuk pengetesan bisa import file Jojonomic.postman_collection.json yang berada folder misc kedalam aplikasi postman.
