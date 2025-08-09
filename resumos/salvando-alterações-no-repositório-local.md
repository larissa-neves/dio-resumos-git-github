# Salvando Alterações no Repositório Local

Resumo dos conteúdos apresentados na aula Salvando Alterações no Repositório Local do curso Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me/).

## 📝 Sobre o conteúdo da aula

Foram apresentados os principais comandos utilizados para salvar alterações em um repositório local com Git. O foco foi entender o fluxo básico de trabalho e como registrar modificações de forma organizada.

## 💻 Comandos

- Verifica o estado atual do repositório, mostrando arquivos modificados, adicionados ou não rastreados

```
$ git status
```

- Adiciona arquivos ao staging area (área de preparação) para serem incluídos no próximo commit

```
$ git add
```

- Salva as alterações no repositório local com uma mensagem descritiva

```
$ git commit -m"<message>"
```

- Exibe o histórico de commits realizados

```
$ git log
```

## 📌 Conceitos importantes:

- O _staging area_ é uma etapa intermediária antes do commit, permitindo selecionar quais alterações serão salvas.
- O commit representa um ponto de salvamento no histórico do projeto.

### ⌨️ Adicional

- Cria um novo arquivo vazio no diretório atual. Muito utilizado para iniciar arquivos que serão versionados com Git

```
$ touch <file-name>
```
