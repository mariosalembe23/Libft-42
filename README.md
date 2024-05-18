# O que são arquivos A(.a)?

Em C, os arquivos com a extensão .a são bibliotecas estáticas. Elas contêm código pré-compilado que pode ser vinculado a outros programas para fornecer funcionalidade adicional.

## Vangatens

- Redução do tamanho do programa executável: O código da biblioteca estática é incorporado ao programa final, eliminando a necessidade de distribuir arquivos adicionais.
<br>
- Melhoria no desempenho: O código da biblioteca estática já está compilado e otimizado, o que pode levar a um programa final mais rápido.
<br>
- Maior modularidade: As bibliotecas estáticas permitem que o código seja dividido em módulos reutilizáveis, facilitando o desenvolvimento e a manutenção de software.

## Pontos a se ter em conta

- Aumento do tamanho do programa executável: Se várias bibliotecas estáticas forem vinculadas, o tamanho do programa final poderá aumentar consideravelmente.
<br>
- Dificuldade de atualização: Se a biblioteca estática precisar ser atualizada, todos os programas que dependem dela também precisarão ser recompilados.
<br>
- Incompatibilidade entre plataformas: As bibliotecas estáticas geralmente são compiladas para uma plataforma específica e não podem ser usadas em outras plataformas sem recompilação.

## EXTRAS

- size_t é um tipo de dados definido em C que é usado para representar tamanhos de objetos em memória. Ele é um tipo de dado não assinado, o que significa que ele não aceita valores negativos. O tipo size_t é geralmente usado para representar tamanhos de arrays, buffers, e o resultado de operações relacionadas ao tamanho de objetos.

<br>

 - O objetivo da função <b>bzero()</b> (e consequentemente ft_bzero()) é preencher a memória com zeros('\0'), não com o caractere '0'.

 <br>

```c
#include <stdio.h>

int main() {
    char *ptr = (char *)s; // Converte o ponteiro genérico para um ponteiro de caractere
}

```c
  if (str[i] == c)
        {
            // Correção: atribuir o endereço do caractere encontrado, não o caractere em si
            return ((char *)&str[i]);
        }
