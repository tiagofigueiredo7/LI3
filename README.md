# LI3 (Português)
Aplicação de análise dos dados relativos a um sistema de streaming de música implementada no âmbito da cadeira de Laboratórios de Informática III. 

## Membros do grupo

* [darteescar](https://github.com/darteescar)
* [luis7788](https://github.com/luis7788)
* [tiagofigueiredo7](https://github.com/tiagofigueiredo7)

## NOTA:

Devido ao limite imposto pelo GitHub, não foi possível incluir os datasets.

## Executável

Para compilar o programa nos vários modos disponibilizados basta fazer:

```console
$ cd trabalho-pratico
$ make
```

### Programa principal

O programa principal é o `programa-principal` e pode ser executado da seguinte forma:

```console
$ ./programa-principal dataset/com-erros input.txt
```

### Programa testes

O programa de testes é o `programa-testes` e pode ser executado da seguinte forma:

```console
$ ./programa-testes dataset/com-erros input.txt resultados-esperados/
```

### Programa interativo

O programa interativo é o `programa-interativo` e pode ser executado da seguinte forma:

```consolo
$ ./programa-interativo
```

## Remoção de ficheiros

Para remover os executáveis e outros ficheiros basta fazer:

```console
$ make clean
```

# LI3 (English)
Music streaming data analysis application implemented in the scope of the Computer Science Laboratory III course. 

## Group members

* [darteescar](https://github.com/darteescar)
* [luis7788](https://github.com/luis7788)
* [tiagofigueiredo7](https://github.com/tiagofigueiredo7)

## NOTE:

Due to the limit imposed by GitHub, it was not possible to include the datasets.

## Executable
To compile the program in the various available modes, just do:

```console
$ cd trabalho-pratico
$ make
```
### Main program
The main program is the `programa-principal` and can be executed as follows:

```console
$ ./programa-principal dataset/com-erros input.txt
```
### Test program
The test program is the `programa-testes` and can be executed as follows:

```console
$ ./programa-testes dataset/com-erros input.txt resultados-esperados/
```

### Interactive program
The interactive program is the `programa-interativo` and can be executed as follows:

```console
$ ./programa-interativo
```
## File removal
To remove the executables and other files, just do:

```console
$ make clean
```