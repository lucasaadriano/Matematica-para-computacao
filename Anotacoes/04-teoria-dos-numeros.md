# Teoria dos Números

## 1. O que é teoria dos números?

A teoria dos números estuda as propriedades dos números inteiros, incluindo divisibilidade, múltiplos, divisores, números primos e operações relacionadas.

Esses conceitos aparecem em diferentes áreas da matemática e da computação.

## 2. Divisibilidade

Um número é divisível por outro quando a divisão é exata, ou seja, quando o resto é zero.

**Exemplo:**

12 é divisível por 3 porque:

\[
12\div3=4
\]

O resto é zero.

Já 13 não é divisível por 3, porque a divisão deixa resto 1.

## 3. Números pares e ímpares

Um número inteiro é par quando é divisível por 2. Caso contrário, ele é ímpar.

Exemplos de números pares:

\[
2,4,6,8,10
\]

Exemplos de números ímpares:

\[
1,3,5,7,9
\]

Na programação, podemos verificar se um número é par utilizando o operador módulo, representado por `%` em Python.

```python
numero = 14

if numero % 2 == 0:
    print("Par")
else:
    print("Ímpar")
```

O operador `%` retorna o resto da divisão. Como 14 dividido por 2 deixa resto zero, o programa imprime `Par`.

## 4. Números primos

Um número primo é um número natural maior que 1 que possui exatamente dois divisores positivos: 1 e ele mesmo.

Exemplos: 2, 3, 5, 7, 11 e 13.

O número 7 é primo porque seus únicos divisores positivos são 1 e 7.

Já o número 8 não é primo, pois possui os divisores 1, 2, 4 e 8.

O número 1 não é considerado primo.

## 5. Múltiplos e divisores

Os múltiplos de um número são obtidos multiplicando-o por números inteiros.

Exemplo: os primeiros múltiplos positivos de 4 são:

\[
4,8,12,16,20,\ldots
\]

Os divisores positivos de 12 são:

\[
1,2,3,4,6,12
\]

Cada um desses números divide 12 sem deixar resto.

## 6. Máximo divisor comum (MDC)

O MDC de dois ou mais números é o maior número inteiro positivo que divide todos eles sem deixar resto.

**Exemplo:** calcular o MDC de 12 e 18.

Divisores de 12:

\[
1,2,3,4,6,12
\]

Divisores de 18:

\[
1,2,3,6,9,18
\]

Os divisores comuns são 1, 2, 3 e 6.

O maior deles é 6.

\[
MDC(12,18)=6
\]

## 7. Mínimo múltiplo comum (MMC)

O MMC é o menor múltiplo positivo compartilhado por dois ou mais números.

**Exemplo:** calcular o MMC de 4 e 6.

Múltiplos positivos de 4:

\[
4,8,12,16,20,\ldots
\]

Múltiplos positivos de 6:

\[
6,12,18,24,\ldots
\]

O menor múltiplo comum é 12.

\[
MMC(4,6)=12
\]

## 8. Aplicação na computação

A teoria dos números é utilizada em criptografia, algoritmos matemáticos e operações com números inteiros. Conceitos como números primos e divisibilidade também ajudam a compreender determinados métodos de segurança digital.

## 9. Conclusão

A teoria dos números permite compreender propriedades dos inteiros e resolver problemas envolvendo divisibilidade, números primos, MDC e MMC. Esses conceitos também podem ser implementados em programas para automatizar cálculos.
