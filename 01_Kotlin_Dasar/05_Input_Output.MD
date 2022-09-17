# 05 Input Output
## Input
### Input String
```kotlin
fun main() {
    print("Enter text: ")
    val stringInput = readLine()
    println("You entered: $stringInput")
}
```
### Output
```command
Enter text: Hmm, interesting!
You entered: Hmm, interesting!
```
---
### Input Integer

Untuk bisa mendapatkan input dengan tipe data selain `string`, kita harus meneggunakan `Scanner` dari Java Standar library, dengan mengimport `java.util.Scanner` 

```kotlin
import java.util.Scanner

fun main() {
    val reader = Scanner(System.`in`)
    print("Enter a number: ")

    val integer:Int = reader.nextInt()

    println("You entered: $integer")
}
```
### Output
```command
Enter a number: 10
You entered: 10
```
| Fungsi          | Kegunaan                                    |
| --------------- | ------------------------------------------- |
| `nextInt()`     | Untuk menangkap inputan tipe data `Integer` |
| `nextLong()`    | Untuk menangkap inputan tipe data `Long`    |
| `nextFloat()`   | Untuk menangkap inputan tipe data `Float`   |
| `nextDouble()`  | Untuk menangkap inputan tipe data `Double`  |
| `nextBoolean()` | Untuk menangkap inputan tipe data `Boolean` |
