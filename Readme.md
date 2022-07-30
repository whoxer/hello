# Hello world!

Clássico arquivo "Hello, World!".

## Origem

"Hello, World!" foi uma frase que foi imortalizada pelos criadores da linguagem de propósito geral, linguagem de programação C. Os norte-americanos Brian Kernighan e Dennis Ritchie, fizeram-o no livro de 1978 entitulado "The C Programming Language" (A Linguagem de Programação C) uma demonstração, exemplificando o poder da linguagem.

## Demonstrando o código

O código para fazer o "Hello, World" segue abaixo:
```c
#include <stdio.h> // Biblioteca padrão da linguagem C, necessário para usar o comando printf()

// Função principal com parâmetros argc e argv.
/*
 O argc (argument count) é um inteiro para guardar o número de argumentos com as quais a função main() foi chamada na linha de comando.
 O argv (argument value) é uma variável de caracteres que carrega o valor dos comandos digitados na linha de comando.
*/
int main(int argc, char *argv[]) {
	printf("Hello, World!\n"); // Comando printf() exibe frases na tela com aspas duplas ("").
	return 0; // A função principal tem o tipo int (inteiro) então precisa retornar um valor inteiro, no nosso caso 0.
}
```

## Compilando o código C

No terminal digite:
```
$ gcc nome_arquivo.c
$ ./a.out

```

