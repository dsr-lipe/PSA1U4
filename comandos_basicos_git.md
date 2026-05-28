# 📚 Comandos Básicos do Git e GitHub

Este guia contém os principais comandos utilizados no Git e GitHub, com explicações simples para facilitar o aprendizado e o uso durante os projetos da faculdade.

---

# 🚀 Inicializando um projeto Git

## 📌 Iniciar o Git em uma pasta

```bash
git init
```

🔹 Cria um repositório Git local na pasta atual.

---

# 📂 Verificando arquivos

## 📌 Ver status do projeto

```bash
git status
```

🔹 Mostra:
- Arquivos modificados
- Arquivos adicionados
- Arquivos que ainda não foram salvos no Git

---

# ➕ Adicionando arquivos

## 📌 Adicionar um arquivo específico

```bash
git add nome-do-arquivo
```

### Exemplo:

```bash
git add novo.py
```

🔹 Adiciona o arquivo para o próximo commit.

---

## 📌 Adicionar todos os arquivos

```bash
git add .
```

🔹 Adiciona TODOS os arquivos modificados.

---

# 💾 Salvando alterações

## 📌 Criar um commit

```bash
git commit -m "Mensagem do commit"
```

### Exemplo:

```bash
git commit -m "Adicionado sistema de objetivos"
```

🔹 Salva uma versão do projeto.

---

# 🌐 Conectando ao GitHub

## 📌 Conectar repositório local ao GitHub

```bash
git remote add origin LINK-DO-REPOSITORIO
```

### Exemplo:

```bash
git remote add origin https://github.com/usuario/projeto.git
```

🔹 Liga seu projeto local ao GitHub.

---

# ⬆️ Enviando arquivos para o GitHub

## 📌 Primeiro envio do projeto

```bash
git push -u origin main
```

🔹 Envia os arquivos para o GitHub.

---

## 📌 Próximos envios

```bash
git push
```

🔹 Atualiza o repositório online.

---

# ⬇️ Baixando projetos

## 📌 Clonar um repositório

```bash
git clone LINK
```

### Exemplo:

```bash
git clone https://github.com/usuario/projeto.git
```

🔹 Baixa um projeto do GitHub para o computador.

---

# 🔄 Atualizando projeto

## 📌 Atualizar projeto com mudanças do GitHub

```bash
git pull
```

🔹 Baixa as alterações mais recentes.

---

# 🌿 Trabalhando com branches

## 📌 Criar uma branch

```bash
git branch nome-da-branch
```

🔹 Cria uma nova ramificação.

---

## 📌 Trocar de branch

```bash
git checkout nome-da-branch
```

🔹 Muda para outra branch.

---

## 📌 Criar e trocar de branch ao mesmo tempo

```bash
git checkout -b nome-da-branch
```

🔹 Cria e entra na branch.

---

# 🗑️ Removendo arquivos

## 📌 Remover arquivo do Git

```bash
git rm nome-do-arquivo
```

🔹 Remove o arquivo do projeto.

---

# 👀 Ver histórico

## 📌 Ver commits realizados

```bash
git log
```

🔹 Mostra o histórico completo de commits.

---

# ⚡ Comandos úteis

## 📌 Ver branches existentes

```bash
git branch
```

---

## 📌 Renomear branch principal para main

```bash
git branch -M main
```

---

## 📌 Ver configurações do Git

```bash
git config --list
```

---

# 🧠 Fluxo básico do Git

```bash
git init
git add .
git commit -m "Primeiro commit"
git remote add origin LINK
git push -u origin main
```

---

# ✨ Autor

Projeto acadêmico desenvolvido para aprendizado de Git e GitHub.