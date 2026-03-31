# 🌟 Introdução ao Git

![Git Logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

O **Git** é um sistema de controle de versão distribuído, amplamente utilizado por desenvolvedores para gerenciar código-fonte de projetos de qualquer tamanho. Ele permite rastrear mudanças, colaborar com outras pessoas e manter um histórico completo do projeto.

---

## 🚀 Por que usar Git?

- **Controle de versão**: Permite acompanhar alterações no código ao longo do tempo.  
- **Colaboração**: Equipes podem trabalhar simultaneamente no mesmo projeto sem conflitos.  
- **Segurança e backup**: O histórico completo do projeto fica armazenado.  
- **Trabalho distribuído**: Cada desenvolvedor possui uma cópia completa do repositório.  
- **Integração com plataformas**: Funciona perfeitamente com GitHub, GitLab e Bitbucket.

---

## 🐧 Conceitos básicos do Git

| Conceito           | Descrição |
|-------------------|----------------------------------------------------|
| **Repositório (Repo)** | Local onde o código e o histórico de versões são armazenados. |
| **Commit**         | Registro de alterações com uma mensagem explicativa. |
| **Branch**         | Ramificação do projeto, permitindo desenvolvimento paralelo. |
| **Merge**          | Combina alterações de diferentes branches. |
| **Clone**          | Cópia local de um repositório remoto. |
| **Push**           | Envia alterações do repositório local para o remoto. |
| **Pull**           | Atualiza o repositório local com alterações do remoto. |

---

## 💡 Comandos básicos do Git

| Comando | Função | Exemplo |
|---------|--------|---------|
| `git init` | Cria um novo repositório local | `git init` |
| `git clone` | Copia um repositório remoto | `git clone <url>` |
| `git status` | Mostra alterações não commitadas | `git status` |
| `git add` | Adiciona arquivos para commit | `git add arquivo.txt` |
| `git commit` | Salva alterações com mensagem | `git commit -m "Mensagem"` |
| `git push` | Envia alterações para o remoto | `git push origin main` |
| `git pull` | Atualiza repositório local | `git pull origin main` |
| `git branch` | Lista ou cria branches | `git branch nova-branch` |
| `git merge` | Combina branches | `git merge outra-branch` |

---

## 🌐 Fluxo típico de trabalho com Git

1. Clonar o repositório remoto:  
   ```bash
   git clone <url-do-repositorio>