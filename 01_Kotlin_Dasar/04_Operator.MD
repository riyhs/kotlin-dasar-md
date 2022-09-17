# 04 Operator
## Operator Aritmatika

```kotlin
fun main() {
    val a = 100
    val b = 6
    
    val addition = a + b
    val subtraction = a - b
    val multiplication = a * b
    val division = a / b
    val modulus = a % b

    println(addition)           // 106
    println(subtraction)        // 94
    println(multiplication)     // 600
    println(division)           // 16
    println(modulus)            // 4
}
```

## Operator Penugasan (Assignment Operator)
```kotlin
fun main() {
    var a = 100

    a += 10             // a = a + 10
    println(a)          // 110

    a -= 20             // a = a - 10
    println(a)          // 90

    a /= 10             // a = a / 10
    println(a)          // 9

    a *= 10             // a = a * 10
    println(a)          // 100
}
```

## Operator Perbandingan
```kotlin
fun main() {
    val a = 100

    println(a == 200)           // false
    println(a != 200)           // true
    println(a > 200)            // false
    println(a < 200)            // true
    println(a >= 200)           // false
    println(a <= 200)           // true
}
```

## Operator Logika
| Operator     | Nama | Deskripsi                                                     |
| ------------ | ---- | ------------------------------------------------------------- |
| &&           | And  | Mengembalikan `true` jika kedua pernyataan adalah `true`      |
| &#124;&#124; | Or   | Mengembalikan `true` jika salah satu pernyataan adalah `true` |
| !            | Not  | Membalik hasil                                                |