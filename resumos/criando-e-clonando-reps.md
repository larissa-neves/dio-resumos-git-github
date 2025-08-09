# Criando e Clonando Repositórios

Resumo dos conteúdos apresentados na aula Criando e Clonando Repositórios do curso Versionamento de Código com Git e Github da [Digital Innovation One](https://www.dio.me).

## Duas Formas de obter um Repositório
1 - Transformar um repositório local que não está sob controle de versão em um repositório Git.

2 - Clonar um repositório Git já existente.

## 💻 Comandos
- Criando um diretório

```
$ mkdir resumos
```

- Transformando a pasta em um repositório Git.

```
$ git init resumos
```

- Exibir conteúdo 

```
$ cat <arquivo>
```

- Entrar em um diretório

```
$ cd <diretório>
```

- Conectar um repositório local à um repositório remoto

```
$ git remote add origin <link repositório>
```

- Clonar uma *branch* específica (duas maneiras)

```
$ git clone <remote-repo-url> --branch <branchname> --single-branch

$ git clone --branch <branchname> <remote-repo-url>
```
