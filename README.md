import java.util.Scanner

fun main() {
    val reader = Scanner(System.`in`)

    print("Enter the radius of the circle: ")
    val radius = reader.nextDouble()

    val area = Math.PI * Math.pow(radius, 2.0)

    println("The area of the circle is: $area")
}
