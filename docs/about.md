# About

This page is just used as a showcase of some of the mkdocs material features that are configured here.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
Nulla et euismod nulla.
Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

!!! warning "non-systemd users beware"

    There is really no reason not to be using `systemd` anymore, right?


```kotlin
import java.util.Scanner

fun main(args: Array<String>) {

    // Creates a reader instance which takes
    // input from standard input - keyboard
    val reader = Scanner(System.`in`)
    print("Enter a number: ")

    // nextInt() reads the next integer from the keyboard
    var integer:Int = reader.nextInt()

    // println() prints the following line to the output screen
    println("You entered: $integer")
}
```