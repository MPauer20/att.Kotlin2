
# att.Kotlin2🫤

## EX1
````
fun main() {
    val a = 5
    val b = 2
    println(a - b)
}


````
## EX2
````
fun main() {
    val nome = readLine()
    val sobrenome = readLine()
    
    println("$nome $sobrenome")
}

````
## EX3
````
fun main() {
    val num1 = 2
    val num2 = 2
    
    println("operação = ${num1 + num2}, ${num1 * num2}, ${num1 - num2}, ${num1 / num2}")
       
  
}

````
## EX4
````
fun main() {
    val lado1 = 3
    val lado2 = 2
    
    var area = lado1 * lado2
    print(area)
  
}

````
## EX5
````
fun main() {
    val base = 5
    val altura = 6
    
    var area = ((base * altura) /2)
    print(area)
  
}

````
## EX6
````
fun main() {
    val peso = 70.0
    val altura = 1.70
    
    var IMC = (peso / (altura * altura))
    print(IMC)
  
}

````
## EX7
````
fun main() {
    val idade = 10 
    
    var anos = idade
    println (anos)
    
    var meses = anos * 12
    println(meses)
    
    var dias = meses * 31
    println(dias)
  
}

````
## EX8
````
fun main() {
    val nota1 = 5
    val nota2 = 8
    val nota3 = 10
    
    var média = ((nota1 + nota2 + nota3) /3)
    print(média)
}


````
## EX9
````
fun main() {
    val segundos = readLine()!!.toInt()

    val horas = segundos / 3600
    val resto = segundos % 3600
    val minutos = resto / 60
    val segRestantes = resto % 60

    println("$horas h $minutos min $segRestantes s")
}



````
## EX10
````
import kotlin.math.sqrt
import kotlin.math.pow

fun main() {
    val x1 = readLine()!!.toDouble()
    val y1 = readLine()!!.toDouble()
    val x2 = readLine()!!.toDouble()
    val y2 = readLine()!!.toDouble()

    val distancia = sqrt((x2 - x1).pow(2) + (y2 - y1).pow(2))
    println("Distância: $distancia")
}

````
## EX11
````
fun main() {
    val a = 20
    val b = 47
    val c = 853

    val r = (a + b) * (a + b)
    val s = (b + c) * (b + c)
    val d = (r + s) / 2

    println("Resultado D: $d")
}

````
## EX12
````
fun main() {
    val custoFabrica = 10000()
    val custoFinal = custoFabrica + (custoFabrica * 0.28) + (custoFabrica * 0.45)
    println("Custo ao consumidor: $custoFinal")
}


````
## EX13
````
fun main() {
    val a = 1
    val b = 2
    val c = 3
    val d = 4
    val e = 5
    val f = 6

    val delta = a * e - b * d

    val x = (c * e - b * f) / delta
    val y = (a * f - c * d) / delta

    println("x = $x")
    println("y = $y")
}

````
## EX14
````
fun main() {
    val salario = 1200
    val novoSalario = salario * 1.25
    println("Novo salário: $novoSalario")
}

````
## EX15
````

fun main() {
    val salario = 1000
    val percentual = 25.0

    val novoSalario = salario + (salario * percentual / 100)
    println("Novo salário: $novoSalario")
}


````
## EX16
````
16-
fun main() {
    val nascimento = 2000
    val atual = 2026

    val idade = atual - nascimento
    val meses = idade * 12
    val dias = idade * 365
    val semanas = dias / 7

    println("Anos: $idade")
    println("Meses: $meses")
    println("Dias: $dias")
    println("Semanas: $semanas")
}

````
## EX17
````
fun main() {
    val pesoKg = 14.0
    val racaoPorGato = 3

    val totalGramas = pesoKg * 1000
    val consumo5Dias = racaoPorGato * 2 * 5

    val restante = totalGramas - consumo5Dias
    println("Restante: $restante g")
}




````
## EX18
````
fun main() {
    var a = 3
    var b = 8

    val temp = a
    a = b
    b = temp

    println("A: $a")
    println("B: $b")
}





````
## EX19
````
fun main() {
    val comprimento = 20
    val largura = 5
    val altura = 8

    val volume = comprimento * largura * altura
    println("Volume: $volume")
}

````
## EX20
````
fun main() {
    val a = 18
    val b = 52

    val resultado = (a - b) * (a - b)
    println(resultado)
}



````
## EX21
````
fun main() {
    val dolar = 240
    val cotacao = 5.50

    val real = dolar * cotacao
    println("Em reais: R$ $real")
}


````
## EX22
````
fun main() {
    val a = 2
    val b = 7
    val c = 9

    val soma = a + b + c
    println(soma * soma)
}


````
## EX23
````
fun main() {
    val a = 19
    val b = 49

    println("Soma: ${a + b}")
    println("Subtração: ${a - b}")
    println("Multiplicação: ${a * b}")
    println("Divisão: ${a / b}")
}



````
## EX24
````
import kotlin.math.pow

fun main() {
    val raio = 7.toDouble()
    val volume = (4.0 / 3.0) * 3.14159 * raio.pow(3)
    println("Volume: $volume")
}


````
## EX25
````

fun main() {
    val numero =1
    println("Antecessor: ${numero - 1}")
    println("Sucessor: ${numero + 1}")
}



````

