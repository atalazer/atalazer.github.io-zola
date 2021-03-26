+++
title = "3 - Program Pertama"
date = 2021-02-12

[extra]
author = "Atalazer"
+++

## Pembuka

Setelah kita melakukan instalasi Golang di OS kita, langkah selanjutnya adalah membuat program pertama kita, yaitu program Hello World.  
Sebelum kita membuat program pertama, kita harus menyiapkan Text Editor untuk menuliskan program pertama kita. Kalian bebas menggunakan Text Editor favorit kalian.
Disini saya akan menggunakan Text Editor Vim.  

<!-- ![Vim](../../img/vim.png "Gambar Vim") -->

## Inisialisasi Projek

Sebelum mulai menuliskan program, kita juga harus melakukan inisialisasi program yang akan dibuat.  
Pada tutorial kali ini, kita akan melakukan inisialisasi program Hello World dengan menuliskan command di bawah ini di Terminal atau CMD kalian  

```
mkdir hello-world
cd hello-world
go mod init hello-world
```

Maka Hasil yang akan ditampilakan akan seperti dibawah ini  
<!-- ![Inisialisasi Program](../../img/inisialisasi-program.png) -->

Dengan mengeksekusi command diatas, nanti si Golang akan menghasilkan file bernama go.mod  
File tersebut jangan kita apa-apakan dahulu dan diabaikan saja.

## Hello World

Langkah Selanjutnya, kita akan memuat folder yang sudah kita buat tadi ke dalam Text Editor kita.
Setelah itu, buat file dengan nama apapun, asalkan memiliki ekstensi .go Misalkan main.go .  
<!-- ![File Golang](../../img/file-go.png) -->

Setelah itu, kita bisa menuliskan program pertama kita pada file main.go dengan kode: 
```
package main
import "fmt"

func main() {
    fmt.Println("Hello World!")
}
```

Save file main.go . Lalu, jalankan command di bawah ini di Terminal atau CMD kalian.  
```
go run main.go
```
Hasilnya adalah:  
<!-- ![Go run](../../img/go-run.png) -->

Selamat, Kalian sudah berhasil membuat program pertama kalian.  
Selanjutnya kalian akan belajar tentang variabel dan tipe data pada Golang.

[Sebelumnya](../2-instalasi/)
[Selanjutnya](../4-variabel-tipe-data/)

