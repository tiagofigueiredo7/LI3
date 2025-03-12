# Sistema de streaming de músicas

Projeto de grupo desenvolvido no âmbito da UC de LI3.

 O programa consiste num sistema de streaming de músicas simples, onde está implementada a leitura e armazenamento de dados e a resolução das _queries_ propostas.

**Membros do grupo:**

* [darteescar](https://github.com/darteescar)
* [luis7788](https://github.com/luis7788)
* [tiagofigueiredo7](https://github.com/tiagofigueiredo7)

## Execução

Para executar o programa nos vários modos disponibilizados basta fazer:

```console
$ cd trabalho-pratico
$ make
```

### Programa principal

```console
$ ./programa-principal dataset-errors/ input.txt
```

### Programa testes

```console
$ ./programa-testes dataset-erros/ input.txt resultados-esperados/
```

### Programa interativo

```consolo
$ ./programa-interativo
```

## Remoção de ficheiros

Para remover os executáveis e outros ficheiros basta fazer:

```console
$ make clean
```

**Nota:** Os datasets utilizados não se encontram disponíveis neste repositório.