# 🚀 Desafio Colaborativo Git

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Projeto prático da disciplina do **1º semestre de Análise e Desenvolvimento de Sistemas (2026)**: uma atividade de **versionamento em equipe** usando Git e GitHub.

> Repositório original da equipe: [marciusarantes/desafio-colaborativo-git](https://github.com/marciusarantes/desafio-colaborativo-git). Esta é a minha cópia (fork) para portfólio.

---

## 📌 Visão geral e contexto

Em projetos reais, várias pessoas mexem no mesmo código ao mesmo tempo. Sem um fluxo organizado, uma alteração sobrescreve a outra e ninguém sabe o que mudou.

O objetivo deste desafio foi praticar, em equipe, o fluxo de trabalho usado no mercado:

1. Um integrante cria o repositório central e convida os colegas como colaboradores.
2. Cada integrante cria a sua **branch** para trabalhar sem afetar a `main`.
3. As alterações são enviadas com **commits** descritivos e um **push**.
4. Cada branch vira um **Pull Request (PR)**, que é revisado e depois **mergeado** na `main`.

### 👥 Equipe

| Integrante | Papel |
|------------|-------|
| Marcius | Líder do repositório |
| Sidney | Integrante |
| Gustavo ([@gustavobsb10](https://github.com/gustavobsb10)) | Integrante — revisou e realizou o merge do PR #5 (`feature-apresentacao`) |

## 🛠️ Tecnologias utilizadas

- **Git** — controle de versão (branch, commit, merge)
- **GitHub** — repositório remoto, colaboradores e Pull Requests
- **Markdown** — documentação do projeto

## ▶️ Como executar / reproduzir

Pré-requisito: ter o [Git](https://git-scm.com/downloads) instalado e uma conta no GitHub.

```bash
# 1. Clonar o repositório
git clone https://github.com/gustavobsb10/desafio-colaborativo-git.git
cd desafio-colaborativo-git

# 2. Criar uma branch para a sua alteração
git checkout -b feature-minha-alteracao

# 3. Editar um arquivo (ex.: README.md) e registrar a mudança
git add README.md
git commit -m "docs: adiciona minha apresentação"

# 4. Enviar a branch para o GitHub
git push -u origin feature-minha-alteracao
```

Depois, no GitHub, clique em **Compare & pull request**, descreva a mudança e peça revisão. Após aprovado, faça o **Merge pull request**.

## 🖼️ Demonstração

O fluxo pode ser conferido no histórico do repositório original:

- [Pull Request #5 — `feature-apresentacao`](https://github.com/marciusarantes/desafio-colaborativo-git/pull/5) (mergeado em 02/10/2026)
- [Histórico de commits](https://github.com/marciusarantes/desafio-colaborativo-git/commits/main)

<!-- Para adicionar um print: salve a imagem em docs/pr-mergeado.png e descomente a linha abaixo -->
<!-- ![Pull Request mergeado](docs/pr-mergeado.png) -->

## 📚 O que aprendi

- Trabalhar em branches isoladas evita conflitos na `main`.
- Pull Requests deixam cada mudança revisável e documentada.
- Commits com mensagens claras contam a história do projeto.

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE).
