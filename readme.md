# 🚀 Golang Hello World

## 📥 1. Instalasi Go

1. Pastikan Go sudah terinstall di sistem kamu. Jika belum, install terlebih dahulu dari 👉 [https://go.dev/dl/](https://go.dev/dl/).

2. Cek versi Go yang terinstall dengan perintah:
```sh
go version
```

## 🔗 2. Clone Repository

Clone repository ini menggunakan git:
```sh
git clone <repo-url>
cd go-helloworld
```

## ▶️ 3. Menjalankan Program

1. Jalankan dengan `go run`
Tanpa perlu kompilasi, jalankan dengan:
```go
go run main.go
```

2. Compile dan Jalankan
Kompilasi dulu dengan perintah:
```go
go build main.go
```
Kemudian jalankan hasil kompilasi:
```sh
./main    # Untuk Linux/macOS
main.exe  # Untuk Windows
```
3. Jalankan dengan `run.sh`
```sh
./run.sh
```
Jika terjadi error izin eksekusi, jalankan perintah:
```sh
chmod +x run.sh
./run.sh
```
## 🎯 4. Cek Output
```output
Compile sukses, menjalankan program...
Hello, world!
```

## Happy Coding! 🚀