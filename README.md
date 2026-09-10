# Códigos-em-Portugol - Feitos por mim (para estudo)

## FASE 1 - Escreval/escreva, leia e contas (somente)
<img src="https://img.shields.io/badge/FEITO NO-%2BVisuAlg-red">

### 1-) Mostrar "Olá mundo".

```c

Algoritmo "Olá mundo"
inicio

    escreval("Olá mundo")
    
fimalgoritmo

```

### 2-) Pedir nome e idade e mostrar na tela.

```c
Algoritmo "Nome e idade"
Var
    nome: caractere
    idade: inteiro

inicio
    escreval("Digite seu nome: ")
    leia(nome)
    
    escreval("Digite sua idade: ")
    leia(idade)
    
    escreval("Seu nome: ", nome)
    escreval("Sua idade: ", idade)
    
fimalgoritmo

```

### 3-) Pedir idade e mostrar ela.

```c
Algoritmo "Nome e idade"
Var
    idade: inteiro

inicio
    escreval("Digite sua idade: ")
    leia(idade)
    
    escreval("Sua idade: ", idade)
    
fimalgoritmo
```

### 4-) Pedir número e mostrar o dobro.

```c
Algoritmo "Nome e idade"
Var
    num: inteiro

inicio
    escreval("Digite um numero: ")
    leia(num)
    
    num <- num * 2
    
    escreval("Resultado: ", num)
    
fimalgoritmo
```

### 5-) Pedir número e mostrar o triplo.

```c
Algoritmo "Nome e idade"
Var
    num: inteiro

inicio
    escreval("Digite um numero: ")
    leia(num)
    
    num <- num * 3
    
    escreval("Resultado: ", num)
    
fimalgoritmo
```

## FASE 2 - Soma, subtração, multiplicação e divisão
<img src="https://img.shields.io/badge/FEITO NO-%2BVisuAlg-blue">

### 1-) Somar 2 números.

```c
Algoritmo "Soma"
    Var n1, n2, resultado: inteiro
    
inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)
    
    escreval("Digite seu segundo número: ")
    leia(n2)
    
    resultado <- n1 + n2
        
    escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 2-) Subtrair 2 números.

```c
Algoritmo "Subtração"
    Var n1, n2, resultado: inteiro
    
inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)
    
    escreval("Digite seu segundo número: ")
    leia(n2)
    
    resultado <- n1 - n2
        
    escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 3-) Multiplicar 2 números.

```c
Algoritmo "Multiplicação"
    Var n1, n2, resultado: inteiro
    
inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)
    
    escreval("Digite seu segundo número: ")
    leia(n2)
    
    resultado <- n1 * n2
        
    escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 4-) Somar 3 números.

```c
Algoritmo "Soma"
    Var n1, n2, n3 resultado: inteiro
    
inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)
    
    escreval("Digite seu segundo número: ")
    leia(n2)

    escreval("Digite seu terceiro número: ")
    leia(n3)
    
    resultado <- n1 + n2 + n3
        
    escreval("Resultado: ", resultado)
    
Fimalgoritmo
```

### 5-) Fazer média de 2 números.

```c
Algoritmo "Média"
Var
    n1, n2, media: real

inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)

    escreval("Digite seu segundo número: ")  
    leia(n2)  
  
    media <- (n1 + n2) / 2  
  
    escreval("O resultado da média é: ", media)

fimalgoritmo
```

### 6-) Dividir 2 números.

```c
Algoritmo "Divisão"
Var
    n1, n2, media: real

inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)

    escreval("Digite seu segundo número: ")  
    leia(n2)  
  
    dividir <- n1 / n2
  
    escreval("O resultado da média é: ", dividir)

fimalgoritmo
```

### 7-) Calcular média (usa divisão).

```c
Algoritmo "Média"
Var
    n1, n2, n3, n4, media: real

inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)

    escreval("Digite seu segundo número: ")  
    leia(n2)  
    
    escreval("Digite seu segundo número: ")  
    leia(n3)  
    
    escreval("Digite seu segundo número: ")  
    leia(n4)  
  
    media <- (n1 + n2 + n3 + n4) / 4
  
escreval("A média é: ", media)

fimalgoritmo
```

### 8-) Dividir e mostrar resto (desafio leve).

```c
Algoritmo "Resto da divisão"
Var
    n1, n2, resto: inteiro

inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)
    escreval("Digite seu segundo número: ")
    leia(n2)

    resto <- n1 mod n2  
  
    escreval("O resto do resultado é: ", resto)

fimalgoritmo
```

## FASE 3 - SE, SENAO, SE SENAO
<img src="https://img.shields.io/badge/FEITO NO-%2BVisuAlg-green"> 

### 1-) Verificar se número é ímpar.

```c
Algoritmo "Ímpar ou Par"
Var 
    num: Inteiro
    
inicio
    escreval("Digite um número: ")
    leia(num)
    
    se (num mod 3 = 0) entao
        escreval("Ímpar")
        
    senao     
        escreval("Par")
    fimse    
    
fimalgoritmo
```

### 2-) Verificar se o número é par.

```c
Algoritmo "Ímpar ou Par"
Var 
    num: Inteiro
    
inicio
    escreval("Digite um número: ")
    leia(num)
    
    se (num mod 2 = 0) entao
        escreval("Par")
        
    senao     
        escreval("Ímpar")
    fimse    
    
fimalgoritmo
```

### 3-) Pedir 2 números e dizer se ambos são pares.

```c
Algoritmo "Pares"
Var 
    n1, n2: inteiro
    
inicio
    escreval("Digite seu primeiro número: ")
    leia(n1)
    
    escreval("Digite seu segundo número: ")
    leia(n2)
  
    se(n1 mod 2 = 0) e (n2 mod 2 = 0) entao
       escreval("Os dois são pares")
    
    senao  
       escreval("Pelo menos um dos números não é par")    
    fimse
    
fimalgoritmo
```

### 4-) Mostrar se número é positivo ou negativo.

```c
Algoritmo "Positivo ou Negativo"
Var 
    num: inteiro
    
inicio
    escreval("Digite seu primeiro número: ")
    leia(num)
  
    se(num > 0) entao
       escreval("Número positivo")
       
    senao
       
       se(num < 0) entao
          escreval("Número negativo")
    
       senao 
          escreval("É zero") 
       fimse
    fimse
    
fimalgoritmo
```

### 5-) Verificar ze número é maior que 10.

```c
Algoritmo "Maior que 10"
Var 
    num: real
    
inicio
    escreval("Digite seu primeiro número: ")
    leia(num)
  
    se(num > 10) entao
       escreval("Maior que 10")
       
    senao
    escreval("Não é maior que 10") 
    fimse
    
fimalgoritmo
```