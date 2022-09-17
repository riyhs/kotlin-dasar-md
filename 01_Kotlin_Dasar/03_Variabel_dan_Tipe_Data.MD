[<< Materi Sebelumnya (Hello World) <<](02_Hello_World.MD)

# 03 Variabel dan Tipe Data
## Variabel
Untuk deklarasi variabel di Kotlin sedikit berbeda dengan bahasa C, deklarasi dimulai dengan menggunakan `val` atau `var`

`var` = variabel yang menggunakan `var` nilainya bisa dirubah setelah diinisiasi

`val` = variabel yang menggunakan `val` nilainya tidak bisa dirubah setelah dinisiasi

```Kotlin
val nama = "Pak Dengklek" // Tidak bisa dirubah isinya
var angkaKesukaan: Int = 2024  // Bisa dirubah isinya
```
Contoh kode
```kotlin
fun main() {
    val nama = "Pak Dengklek"
    var angkaKesukaan: Int = 2024

    println(nama + " suka angka " + angkaKesukaan)

    angkaKesukaan = 1945
    println(nama + " suka angka " + angkaKesukaan)
}
```
Output
```
Pak Dengklek suka angka 2024
Pak Dengklek suka angka 1945
```

## Tipe Data di Kotlin
Layaknya wadah dalam dunia nyata kita tidak bisa menggunakan gelas untuk makan nasi ayam, di dunia pemrograman kita perlu menggunakan wadah yang tepat untuk menampung data kita. Tipe data di Kotlin mirip dengan Tipe Data di bahasa C, khusus untuk `String` kita tidak perlu menggunakan `char`, tapi cukup tuliskan `string` saja. 

Untuk Pendefinisian tipe data dilakukan menggunakan ` val namaVariabel: tipeData`

Contoh kode
```kotlin
val myNum: Int = 5                // Int
val myDoubleNum: Double = 5.99    // Double
val myLetter: Char = 'D'          // Char
val myBoolean: Boolean = true     // Boolean
val myText: String = "Hello"      // String
```
*Catatan: Tidak diwajibkan mendefinisikan tipe data di kotlin*

[>> Materi Selanjutnya (Operator) >>](04_Operator.MD)
