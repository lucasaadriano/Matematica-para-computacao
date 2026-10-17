# Matrizes

## 1. O que é uma matriz?

Uma matriz é uma organização retangular de elementos distribuídos em linhas e colunas.

Exemplo:

\[
A=
\begin{bmatrix}
1&2&3\\
4&5&6
\end{bmatrix}
\]

Essa matriz possui 2 linhas e 3 colunas. Por isso, sua dimensão é \(2\times3\).

## 2. Elementos de uma matriz

Cada elemento ocupa uma posição determinada pela linha e pela coluna.

Considere:

\[
A=
\begin{bmatrix}
1&2\\
3&4
\end{bmatrix}
\]

O elemento da primeira linha e segunda coluna é 2.

O elemento da segunda linha e primeira coluna é 3.

## 3. Adição de matrizes

Para somar duas matrizes, elas precisam ter a mesma dimensão. A soma é realizada entre os elementos que ocupam posições correspondentes.

Considere:

\[
A=
\begin{bmatrix}
1&2\\
3&4
\end{bmatrix}
\]

\[
B=
\begin{bmatrix}
5&6\\
7&8
\end{bmatrix}
\]

Somando os elementos correspondentes:

\[
A+B=
\begin{bmatrix}
1+5&2+6\\
3+7&4+8
\end{bmatrix}
\]

Resultado:

\[
A+B=
\begin{bmatrix}
6&8\\
10&12
\end{bmatrix}
\]

## 4. Subtração de matrizes

A subtração também é feita entre elementos correspondentes e exige matrizes de mesma dimensão.

Utilizando as matrizes anteriores:

\[
A-B=
\begin{bmatrix}
1-5&2-6\\
3-7&4-8
\end{bmatrix}
\]

Resultado:

\[
A-B=
\begin{bmatrix}
-4&-4\\
-4&-4
\end{bmatrix}
\]

## 5. Multiplicação de uma matriz por um número

Para multiplicar uma matriz por um número, multiplicamos cada elemento pelo valor indicado.

Exemplo:

\[
A=
\begin{bmatrix}
1&2\\
3&4
\end{bmatrix}
\]

Multiplicando A por 2:

\[
2A=
\begin{bmatrix}
2\times1&2\times2\\
2\times3&2\times4
\end{bmatrix}
\]

Resultado:

\[
2A=
\begin{bmatrix}
2&4\\
6&8
\end{bmatrix}
\]

## 6. Multiplicação de matrizes

Na multiplicação de matrizes, o número de colunas da primeira matriz deve ser igual ao número de linhas da segunda.

Exemplo:

\[
A=
\begin{bmatrix}
1&2\\
3&4
\end{bmatrix},
\quad
B=
\begin{bmatrix}
5&6\\
7&8
\end{bmatrix}
\]

Para calcular o elemento da primeira linha e primeira coluna do resultado, multiplicamos os elementos correspondentes da primeira linha de A pela primeira coluna de B e somamos:

\[
(1\times5)+(2\times7)=19
\]

Calculando os outros elementos da mesma maneira:

\[
AB=
\begin{bmatrix}
19&22\\
43&50
\end{bmatrix}
\]

A multiplicação de matrizes, em geral, não é comutativa. Isso significa que \(AB\) não precisa ser igual a \(BA\).

## 7. Aplicação na computação

Matrizes são utilizadas no processamento de imagens, em cálculos científicos, em gráficos de computador e em modelos de inteligência artificial.

Uma imagem digital, por exemplo, pode ser representada por uma matriz de valores que indicam as cores ou intensidades dos pixels.

## 8. Conclusão

As matrizes permitem organizar dados em linhas e colunas e realizar operações matemáticas com eles. Conhecer suas dimensões, seus elementos e suas operações é importante para diversas aplicações computacionais.
