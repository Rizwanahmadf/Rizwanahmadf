**Contoh PYTHON**
Program ini akan meminta pengguna untuk memasukkan dua angka dan kemudian menghitung jumlahnya

# Program penjumlahan sederhana

# Meminta pengguna untuk memasukkan dua angka
angka1 = float(input("Masukkan angka pertama: "))
angka2 = float(input("Masukkan angka kedua: "))

# Menghitung jumlah dari dua angka
jumlah = angka1 + angka2

# Menampilkan hasil
print("Jumlah dari", angka1, "dan", angka2, "adalah", jumlah)


**Contoh C#**
Pemrograman yang mencetak pesan sederhana ke konsol

using System;

class Program
{
    static void Main()
    {
        // Mencetak pesan sederhana ke konsol
        Console.WriteLine("Halo, selamat datang di program pertama Anda menggunakan C#!");

        // Menunggu agar pengguna dapat melihat pesan sebelum aplikasi selesai
        Console.ReadLine();
    }
}


**Contoh C++** 
Program ini merupakan program sederhana untuk menghitung luas segitiga berdasarkan alas dan tinggi 

#include <iostream>
using namespace std;

int main() {
    // Deklarasi variabel
    float alas, tinggi, luas;

    // Input alas dari pengguna
    cout << "Masukkan panjang alas segitiga: ";
    cin >> alas;

    // Input tinggi dari pengguna
    cout << "Masukkan tinggi segitiga: ";
    cin >> tinggi;

    // Menghitung luas segitiga
    luas = 0.5 * alas * tinggi;

    // Menampilkan hasil
    cout << "Luas segitiga dengan alas " << alas << " dan tinggi " << tinggi << " adalah: " << luas << endl;

    return 0;
}


**Contoh Javascript**
Program ini adalah program sapaan sederhana

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Program Sapaan JavaScript</title>
</head>
<body>

<script>
  // Meminta nama pengguna
  var namaPengguna = prompt("Masukkan nama Anda:");

  // Memeriksa apakah nama pengguna kosong
  if (namaPengguna === null || namaPengguna === "") {
    alert("Halo, pengguna tanpa nama!");
  } else {
    // Menampilkan sapaan dengan nama pengguna
    alert("Halo, " + namaPengguna + "! Selamat datang di program JavaScript sederhana ini.");
  }
</script>

</body>
</html>


**Contoh PHP**
Program ini hanya mencetak teks sederhana ke layar

<!DOCTYPE html>
<html>
<head>
    <title>Contoh Program PHP</title>
</head>
<body>

<?php
    // Ini adalah komentar di dalam PHP
    echo "<h1>Halo, ini contoh program PHP!</h1>";
    echo "<p>Selamat datang di dunia pemrograman PHP.</p>";
?>

</body>
</html>


**Contoh SWIFT**
program sederhana Swift yang mencetak pesan sederhana ke konsol

// Program Swift sederhana

import Foundation

func main() {
    print("Halo, Selamat datang di program Swift!")
    
    // Contoh penggunaan variabel
    let nama = "John"
    let umur = 25
    
    // Contoh penggunaan interpolasi string
    print("Halo, \(nama)! Umur kamu adalah \(umur) tahun.")
    
    // Contoh penggunaan percabangan if-else
    if umur >= 18 {
        print("Kamu sudah dewasa.")
    } else {
        print("Kamu masih di bawah umur.")
    }
    
    // Contoh penggunaan loop for
    for i in 1...5 {
        print("Iterasi ke-\(i)")
    }
}

// Panggil fungsi main
main()


**Contoh Java**
Program ini merupakan program "Halo, Dunia!" yang umum digunakan sebagai contoh awal

public class HelloWorld {
    public static void main(String[] args) {
        // Menampilkan pesan "Hello, World!" ke konsol
        System.out.println("Hello, World!");
    }
}


**Contoh Go**
Program ini hanya mencetak "Hello, World!" ke konsol

package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}

**Contoh SQL**
Program ini akan membuat sebuah tabel sederhana untuk menyimpan informasi tentang pengguna (user) dalam suatu sistem

-- Membuat database baru dengan nama 'contoh_database'
CREATE DATABASE IF NOT EXISTS contoh_database;

-- Menggunakan database 'contoh_database'
USE contoh_database;

-- Membuat tabel 'pengguna' dengan kolom 'id', 'nama', dan 'email'
CREATE TABLE IF NOT EXISTS pengguna (
    id INT PRIMARY KEY AUTO_INCREMENT,
    nama VARCHAR(50) NOT NULL,
    email VARCHAR(100) UNIQUE NOT NULL
);

-- Menyisipkan beberapa data ke dalam tabel 'pengguna'
INSERT INTO pengguna (nama, email) VALUES
    ('John Doe', 'john.doe@example.com'),
    ('Jane Smith', 'jane.smith@example.com');

-- Menampilkan seluruh data dari tabel 'pengguna'
SELECT * FROM pengguna;


**Contoh Ruby**
Program ini akan meminta pengguna untuk memasukkan nama dan menyapa pengguna dengan pesan sapaan

# Program sederhana dalam Ruby

# Meminta pengguna untuk memasukkan nama
print "Masukkan nama Anda: "
nama = gets.chomp

# Menyapa pengguna
puts "Halo, #{nama}! Selamat datang di program Ruby sederhana."
