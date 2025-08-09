# Desfazendo Alterações no Repositório

Resumo dos conteúdos abordados na aula Desfazendo Alterações no Repositório do curso Versionamento de Código com Git e GitHub da [Digital Innovation One](https://www.dio.me/).

## 📝 Sobre o conteúdo da aula

Foram apresentados os principais comandos para desfazer ações no Git, úteis para corrigir erros durante o versionamento. Os principais pontos abordados foram:

- Como remover um repositório Git criado por engano.
- Restaurar arquivos modificados para o estado anterior.
- Corrigir a mensagem do último commit.
- Desfazer commits e voltar para versões anteriores do projeto.
- Retirar arquivos da área de preparação antes de um commit.

Esses comandos ajudam a manter o repositório limpo e organizado durante o desenvolvimento.

## 💻 Comandos

| Ação                                                 | Comando                                    |
| ---------------------------------------------------- | ------------------------------------------ |
| git init na pasta errada                             | `rm -rf .git`                              |
| Alteração indesejada no arquivo                      | `git restore <file-name>`                  |
| Corrigir/Alterar a mensagem do último commit         | `git commit --amend -m"<new message>"`     |
| Desfazer o commit, retornando para o commit anterior | `git reset <--soft/--mixed/--hard> <hash>` |
| Remover arquivo da área de preparação                | `git reset <file-name>`                    |

## Conceitos importantes:

- **`--soft`**: adiciona os arquivos posteriores ao commit indicado à área de preparação.
- **`--mixed`**: adiciona os arquivos posteriores ao commit à árvore de trabalho, indicando os mesmos como _untracked files_ (sendo necessário adicioná-los à área de preparação).
- **`--hard`**: ignora completamente e desfaz os arquivos do commit posterior (apaga os arquivos).

### ⌨️ Complementar

- Exibir um histórico mais detalhado das alterações realizada

```
$ git reflog
```
