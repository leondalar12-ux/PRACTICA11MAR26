# PRACTICA_KOTLIN
##1 DESARROLLO DE VARIABLES Y SALIDAS
###1Declarar nombre con variable
<code>
fun main() {
    var nombre = "Dalia"
    println("Hola soy $nombre")
}
<img width="494" height="450" alt="image" src="https://github.com/user-attachments/assets/5079d1b7-8b61-4fa1-b567-037cacbe0151" />
###2 Declarar una variable de edad
fun main(){
var edad = 42
    println("Tengo $edad añitos")
}
<img width="412" height="241" alt="image" src="https://github.com/user-attachments/assets/2b6a40d9-3179-49b1-b2a4-4f9f5c4d54ee" />
###3 Declara dos números a y b con valores que tú elijas e imprime la suma. 4. 
<code>
fun main(){
var a = 20
    var b = 35
    println("La suma es: ${a + b}")
}
<img width="449" height="227" alt="image" src="https://github.com/user-attachments/assets/7153a584-6427-48c0-a919-ed3c2934683e" />

###4 Declara una variable curso con el nombre del curso
fun main(){
var curso = "Aplicaciones Moviles"
    println("Curso: $curso")
}
<img width="404" height="210" alt="image" src="https://github.com/user-attachments/assets/75d6c868-41e8-4e99-bff6-a7c9b4f59d4f" />
###5 Declara una variable comida con tu comida favorita 
fun main(){
val comida = "Adobo de chancho."
    println("Mi comida favorita es: $comida")
}
<img width="553" height="231" alt="image" src="https://github.com/user-attachments/assets/e1875845-b78a-4416-a9d1-c665c178b1eb" />
###6 Declara una variable videojuego 
fun main(){
val videojuego = "Super Mario"
    println("Mi videojuego favorito es: $videojuego")
}
<img width="597" height="246" alt="image" src="https://github.com/user-attachments/assets/40498706-b228-4fff-aa3d-073fe6320d49" />
##2 DESARROLLO DE CONDICIONALES IF
###1 Variable  edad
fun main() {
    var edad = 42
    if (edad >= 18) println("Eres mayor de edad")
}
<img width="552" height="197" alt="image" src="https://github.com/user-attachments/assets/092e358b-601a-4c10-ab5c-a47a41561f9c" />
###2 Variable notas
fun main() {
    var nota = 10
    if (nota >= 11) println("Aprobado") else println("Desaprobado")
}
<img width="799" height="232" alt="image" src="https://github.com/user-attachments/assets/c62442bb-8621-4405-b0e6-fa68189fd05c" />
###3 creacion e variable con cualquier numero
fun main() {
    var numero = 100   // puedes cambiar el valor
    if (numero > 0) {
        println("Número positivo")
    }
}
<img width="579" height="218" alt="image" src="https://github.com/user-attachments/assets/3a811c68-6bf6-4e49-9cfd-1a61e10a94e3" />
###4 Crea un programa que verifique si un número es par o impar usando if else. 
fun main() {
    var num = 137
    if (num % 2 == 0) println("Número par") else println("Número impar") 
}
<img width="819" height="207" alt="image" src="https://github.com/user-attachments/assets/464e38cb-e45e-49c6-be1e-d45a16f69d8a" />

###5 una variable temperatura. 
fun main() {
    var temperatura = 45
    if (temperatura < 18) println("Hace frío") else println("Hace calor")
}
<img width="848" height="211" alt="image" src="https://github.com/user-attachments/assets/27eac9c2-e683-4cc9-9731-1df3c17034ab" />

##3 DESARROLLO CONDICIONAL WHEN
###1 Crea una variable dia con un número del 1 al 7
fun main() {
    var dia = 4
    when(dia) {
        1 -> println("Lunes")
        2 -> println("Martes")
        3 -> println("Miércoles")
        4 -> println("Jueves")
        5 -> println("Viernes")
        6 -> println("Sábado")
        7 -> println("Domingo")
    }
}
<img width="326" height="288" alt="image" src="https://github.com/user-attachments/assets/878726d9-9420-4a9b-a7f7-c41da6fc0a67" />





###2 Crea una variable numero del 1 al 3. 
