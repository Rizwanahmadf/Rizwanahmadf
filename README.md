**Contoh PYTHON**
Program ini akan meminta pengguna untuk memasukkan dua angka dan kemudian menghitung jumlahnya

angka1 = float(input("Masukkan angka pertama: "))
angka2 = float(input("Masukkan angka kedua: "))

jumlah = angka1 + angka2

print("Jumlah dari", angka1, "dan", angka2, "adalah", jumlah)


**Contoh C#**
Pemrograman yang mencetak pesan sederhana ke konsol

using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Halo, selamat datang di program pertama Anda menggunakan C#!"); 
        Console.ReadLine();
    }
}


**Contoh C++** 
Program ini merupakan program sederhana untuk menghitung luas segitiga berdasarkan alas dan tinggi 

#include <iostream>
using namespace std;

int main() {
    float alas, tinggi, luas;
    cout << "Masukkan panjang alas segitiga: ";
    cin >> alas;
    cout << "Masukkan tinggi segitiga: ";
    cin >> tinggi;
    luas = 0.5 * alas * tinggi;
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

import Foundation


func main() {
    print("Halo, Selamat datang di program Swift!")

    let nama = "John"
    let umur = 25
    print("Halo, \(nama)! Umur kamu adalah \(umur) tahun.")
    if umur >= 18 {
        print("Kamu sudah dewasa.")
    } else {
        print("Kamu masih di bawah umur.")
    }
    for i in 1...5 {
        print("Iterasi ke-\(i)")
    }
}
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

CREATE DATABASE IF NOT EXISTS contoh_database;

USE contoh_database;

CREATE TABLE IF NOT EXISTS pengguna (
    id INT PRIMARY KEY AUTO_INCREMENT,
    nama VARCHAR(50) NOT NULL,
    email VARCHAR(100) UNIQUE NOT NULL
);

INSERT INTO pengguna (nama, email) VALUES
    ('John Doe', 'john.doe@example.com'),
    ('Jane Smith', 'jane.smith@example.com');

SELECT * FROM pengguna;


**Contoh Ruby**
Program ini akan meminta pengguna untuk memasukkan nama dan menyapa pengguna dengan pesan sapaan

print "Masukkan nama Anda: "
nama = gets.chomp

puts "Halo, #{nama}! Selamat datang di program Ruby sederhana."
