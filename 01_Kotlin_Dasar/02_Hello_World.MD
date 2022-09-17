# 02 Hello World 

## Program Sederhana
Seperti di praktikum kita menggunakan bahasa C, di Kotlin kita memiliki kemiripan dengan bahasa C, yaitu terdapat 1 fungsi utama yang akan dijalankan saat pertama kali, yaitu fungsi main()

```kotlin
fun main() {
   println("Hello Kotlin!")
}
```

### Memahami kode
#### fungsi main()
```kotlin
fun main() {
    ...
}
```
`fun` keyword disamping digunakan untuk mendeklarasikan sebuah fungsi di Kotlin, kita tidak perlu menuliskan `void` karena Kotlin otomatis bisa mendeteksi fungsi yang tidak mengembalikan nilai, FYI : fun == senang

`main() { ... }` main adalah nama fungsi kita dan tanda kurung buka kurung tutup menandakan itu adalah sebuah fungsi. Untuk menuliskan codenya kita menuliskan di dalam kurung kurawal

#### Mencetak nilai
```kotlin
println("Hello Kotlin!")
```
`println` berarti Print Line, `println` berfungsi untuk mencetak keluaran dengan otomatis membuat baris baru setelah semua keluaran sudah dikeluarkan. fungsi ini mirip dengan `printf()` di bahasa C, tapi Kotlin lebih EZ yagesya.

`("Hello Kotlin!")` untuk memasukan nilai kita tinggal memasukan nilainya didalam tanda kurung, `"..."` tanda petik 2 menandakan bahwa itu adalah String


