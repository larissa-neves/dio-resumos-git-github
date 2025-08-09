# 🚀 Criando e Clonando Repositórios com Git

Resumo da aula **"Criando e Clonando Repositórios"** do curso _Versionamento de Código com Git e GitHub_ da [Digital Innovation One](https://www.dio.me).

## 📦 Formas de Obter um Repositório Git

Você pode iniciar um projeto com Git de duas maneiras:

1. **Inicializar um repositório local**  
   Transformar uma pasta comum em um repositório Git.

2. **Clonar um repositório existente**  
   Copiar um repositório remoto para sua máquina local.

## 💻 Principais Comandos Utilizados

| Ação                                 | Comando                                                                                    |
| ------------------------------------ | ------------------------------------------------------------------------------------------ |
| Criar um diretório                   | `mkdir resumos`                                                                            |
| Inicializar repositório Git          | `git init resumos`                                                                         |
| Acessar diretório                    | `cd <diretório>`                                                                           |
| Exibir conteúdo de arquivo           | `cat <arquivo>`                                                                            |
| Conectar repositório local ao remoto | `git remote add origin <URL do repositório>`                                               |
| Clonar uma branch específica         | `git clone <URL> --branch <branch> --single-branch`<br>`git clone --branch <branch> <URL>` |

---

✨ _Dica:_ Use `git status` para verificar o estado atual do repositório e `git log` para visualizar o histórico de commits.
