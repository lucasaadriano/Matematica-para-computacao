# Combinatória e Probabilidade

## 1. O que é combinatória?

A combinatória é a área da matemática que estuda maneiras de contar possibilidades, organizar elementos e calcular quantas configurações podem ser formadas.

Ela é útil quando precisamos descobrir o número de possibilidades sem listar todas elas individualmente.

## 2. Princípio aditivo

O princípio aditivo pode ser utilizado quando precisamos escolher entre alternativas diferentes que não acontecem simultaneamente.

**Exemplo:**

Uma pessoa pode escolher uma sobremesa entre 3 tipos de sorvete ou 2 tipos de bolo.

Considerando que ela escolherá apenas uma sobremesa:

\[
3+2=5
\]

Existem 5 opções possíveis.

## 3. Princípio multiplicativo

O princípio multiplicativo é utilizado quando uma escolha é realizada em etapas.

**Exemplo:**

Uma pessoa possui 3 camisetas e 2 calças. Cada camiseta pode ser combinada com qualquer uma das calças.

\[
3\times2=6
\]

Portanto, existem 6 combinações possíveis.

## 4. Fatorial

O fatorial de um número natural \(n\), representado por \(n!\), é o produto dos números inteiros positivos de 1 até n.

Exemplo:

\[
4!=4\times3\times2\times1
\]

\[
4!=24
\]

Por definição:

\[
0!=1
\]

O fatorial aparece em problemas de contagem, principalmente em permutações e combinações.

## 5. Permutação simples

A permutação simples calcula de quantas maneiras diferentes podemos organizar todos os elementos distintos de um conjunto, considerando que a ordem importa.

A fórmula é:

\[
P(n)=n!
\]

**Exemplo:**

De quantas maneiras podemos organizar 3 livros diferentes em uma prateleira?

\[
P(3)=3!
\]

\[
P(3)=3\times2\times1=6
\]

Existem 6 maneiras diferentes de organizar os livros.

## 6. Combinação simples

A combinação simples calcula quantos grupos diferentes podem ser formados quando a ordem dos elementos não importa.

A fórmula é:

\[
C(n,p)=\frac{n!}{p!(n-p)!}
\]

Em que:

- \(n\) é o número total de elementos.
- \(p\) é a quantidade de elementos escolhidos.

**Exemplo:**

De um grupo de 4 alunos, queremos escolher 2 para participar de uma atividade.

\[
C(4,2)=\frac{4!}{2!(4-2)!}
\]

Substituindo os fatoriais:

\[
C(4,2)=\frac{24}{2\times2}
\]

\[
C(4,2)=6
\]

Podemos formar 6 grupos diferentes.

## 7. O que é probabilidade?

A probabilidade representa a chance de um evento acontecer. Quando todos os resultados possíveis são igualmente prováveis, podemos usar a fórmula:

\[
P(A)=\frac{n(A)}{n(\Omega)}
\]

Em que:

- \(P(A)\) é a probabilidade do evento A.
- \(n(A)\) é o número de resultados favoráveis.
- \(n(\Omega)\) é o número total de resultados possíveis.

## 8. Exemplo de probabilidade

Um dado comum possui 6 faces numeradas de 1 a 6. Qual é a probabilidade de obter um número par em um único lançamento?

Os números pares são:

\[
A=\{2,4,6\}
\]

Existem 3 resultados favoráveis e 6 resultados possíveis.

\[
P(A)=\frac{3}{6}
\]

Simplificando:

\[
P(A)=\frac{1}{2}=50\%
\]

Portanto, a probabilidade de sair um número par é 50%.

## 9. Aplicação na computação

A combinatória pode ser utilizada para calcular possibilidades de senhas, sequências e configurações. A probabilidade aparece em simulações, análise de riscos, estatística e inteligência artificial.

## 10. Conclusão

A combinatória permite contar possibilidades, enquanto a probabilidade ajuda a medir a chance de acontecimentos. As duas áreas são úteis para resolver problemas matemáticos e computacionais.
