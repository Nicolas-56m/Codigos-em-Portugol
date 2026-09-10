# Códigos-em-Portugol - Feitos por mim (para estudo)

## FASE 1 - Escreval/escreva, leia e contas (somente)
<img src="https://img.shields.io/badge/FEITO NO-%2BVisuAlg-red">

### 1-) Mostrar "Olá mundo".

```c
Algoritmo "Olá mundo"

Inicio

    Escreval("Olá mundo")
    
Fimalgoritmo
```

### 2-) Pedir nome e idade e mostrar na tela.

```c
Algoritmo "Nome e idade"
Var
    nome: caractere
    idade: inteiro

Inicio
    Escreval("Digite seu nome: ")
    Leia(nome)
    
    Escreval("Digite sua idade: ")
    Leia(idade)
    
    Escreval("Seu nome: ", nome)
    Escreval("Sua idade: ", idade)
    
Fimalgoritmo

```

### 3-) Pedir idade e mostrar ela.

```c
Algoritmo "Idade"
Var
    idade: inteiro

Inicio
    Escreval("Digite sua idade: ")
    Leia(idade)
    
    Escreval("Sua idade: ", idade)
    
Fimalgoritmo
```

### 4-) Pedir número e mostrar o dobro.

```c
Algoritmo "Dobro"
Var
    num: inteiro

Inicio
    Escreval("Digite um numero: ")
    Leia(num)
    
    num <- num * 2
    
    Escreval("Resultado: ", num)
    
Fimalgoritmo
```

### 5-) Pedir número e mostrar o triplo.

```c
Algoritmo "Triplo"
Var
    num: inteiro

Inicio
    Escreval("Digite um numero: ")
    leia(num)
    
    num <- num * 3
    
    Escreval("Resultado: ", num)
    
Fimalgoritmo
```

## FASE 2 - Soma, subtração, multiplicação e divisão
<img src="https://img.shields.io/badge/FEITO NO-%2BVisuAlg-blue">

### 1-) Somar 2 números.

```c
Algoritmo "Soma"
Var 
    n1, n2, resultado: inteiro
    
Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)
    
    Escreval("Digite seu segundo número: ")
    Leia(n2)
    
    resultado <- n1 + n2
        
    Escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 2-) Subtrair 2 números.

```c
Algoritmo "Subtração"
Var 
    n1, n2, resultado: inteiro
    
Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)
    
    Escreval("Digite seu segundo número: ")
    Leia(n2)
    
    resultado <- n1 - n2
        
    Escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 3-) Multiplicar 2 números.

```c
Algoritmo "Multiplicação"
Var 
    n1, n2, resultado: inteiro
    
Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)
    
    Escreval("Digite seu segundo número: ")
    Leia(n2)
    
    resultado <- n1 * n2
        
    Escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 4-) Somar 3 números.

```c
Algoritmo "Soma"
Var 
    n1, n2, n3, resultado: inteiro
    
Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)
    
    Escreval("Digite seu segundo número: ")
    Leia(n2)

    Escreval("Digite seu terceiro número: ")
    Leia(n3)
    
    resultado <- n1 + n2 + n3
        
    Escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 5-) Fazer média de 2 números.

```c
Algoritmo "Média"
Var
    n1, n2, media: real

Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)

    Escreval("Digite seu segundo número: ")  
    Leia(n2)  
  
    media <- (n1 + n2) / 2  
  
    Escreval("O resultado da média é: ", media)

Fimalgoritmo
```

### 6-) Dividir 2 números.

```c
Algoritmo "Divisão"
Var
    n1, n2, dividir: real

Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)

    Escreval("Digite seu segundo número: ")  
    Leia(n2)  
  
    dividir <- n1 / n2
  
    Escreval("O resultado da divisão é: ", dividir)

Fimalgoritmo
```

### 7-) Calcular média (usa divisão).

```c
Algoritmo "Média"
var
    n1, n2, n3, n4, media: real

Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)

    Escreval("Digite seu segundo número: ")  
    Leia(n2)  
    
    Escreval("Digite seu terceiro número: ")  
    Leia(n3)  
    
    Escreval("Digite seu quarto número: ")  
    Leia(n4)  
  
    media <- (n1 + n2 + n3 + n4) / 4
  
    Escreval("A média é: ", media)

Fimalgoritmo
```

### 8-) Dividir e mostrar resto (desafio leve).

```c
Algoritmo "Resto da divisão"
Var
    n1, n2, resto: inteiro

Inicio
   Escreval("Digite seu primeiro número: ")
   Leia(n1)
   Escreval("Digite seu segundo número: ")
   Leia(n2)

    resto <- n1 mod n2  
  
    Escreval("O resto do resultado é: ", resto)

Fimalgoritmo
```

## FASE 3 - SE, SENAO, SE SENAO
<img src="https://img.shields.io/badge/FEITO NO-%2BVisuAlg-green"> 

### 1-) Verificar se número é ímpar.

```c
Algoritmo "Ímpar ou Par"
Var 
    num: Inteiro
    
Inicio
    Escreval("Digite um número: ")
    Leia(num)
    
    Se (num mod 2 <> 0) entao
        Escreval("Ímpar")
        
    Senao     
        Escreval("Par")
    Fimse    
    
Fimalgoritmo
```

### 2-) Verificar se o número é par.

```c
Algoritmo "Ímpar ou Par"
Var 
    num: Inteiro
    
Inicio
    Escreval("Digite um número: ")
    Leia(num)
    
    Se (num mod 2 = 0) entao
        Escreval("Par")
        
    Senao     
        Escreval("Ímpar")
    Fimse    
    
Fimalgoritmo
```

### 3-) Pedir 2 números e dizer se ambos são pares.

```c
Algoritmo "Pares"
Var 
    n1, n2: inteiro
    
Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(n1)
    
    Escreval("Digite seu segundo número: ")
    Leia(n2)
  
    Se(n1 mod 2 = 0) e (n2 mod 2 = 0) entao
       Escreval("Os dois são pares")
    
    Senao  
       Escreval("Pelo menos um dos números não é par")    
    Fimse
    
Fimalgoritmo
```

### 4-) Mostrar se número é positivo ou negativo.

```c
Algoritmo "Positivo ou Negativo"
Var 
    num: inteiro
    
Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(num)
  
    Se(num > 0) entao
       Escreval("Número positivo")
       
    Senao
       
       Se(num < 0) entao
          Escreval("Número negativo")
    
       Senao 
          Escreval("É zero") 
       Fimse
    Fimse
    
Fimalgoritmo
```

### 5-) Verificar se número é maior que 10.

```c
Algoritmo "Maior que 10"
Var 
    num: real
    
Inicio
    Escreval("Digite seu primeiro número: ")
    Leia(num)
  
    Se(num > 10) entao
       Escreval("Maior que 10")
       
    Senao
       Escreval("Não é maior que 10") 
    Fimse
    
Fimalgoritmo
```