# 🧩 Exercício de Treino Git & GitHub

## 🎯 Objetivo
Este repositório serve para praticar o uso básico do **Git** e do **GitHub**.  
O objetivo é realizares todas estas tarefas:
1. Criar uma **branch** com o teu nome  
2. Adicionar um **ficheiro com o teu nome** na pasta "/Ficheiros"  
3. Fazer **push** para o GitHub  
4. Fazer um **Pull Request (PR)** para a `main`  
5. Fazer o **merge**  

---

## 🛠️ Instalação do Git
Se ainda não tens o Git instalado, segue um dos métodos abaixo:

### 💻 Windows
1. Vai a [https://git-scm.com/downloads](https://git-scm.com/downloads)  
2. Faz o download e segue o instalador padrão (podes aceitar todas as opções por defeito)  

### 🍎 macOS
Abre o terminal e escreve:
```shell
brew install git
```

> Se não tiveres o Homebrew instalado, podes também usar o instalador do site do Git.

### 🐧 Linux (Ubuntu/Debian)
```bash
sudo apt install git
```

Para confirmar que está instalado:
```bash
git --version
```

---

## 🚀 Como fazer o exercício

### 👉 Opção 1 — Através do **terminal**

1. **Clonar o repositório**
```bash
git clone https://github.com/davidmarafuzgaspar/junitec-git-flash-course.git
cd junitec-git-flash-course
```

2. **Criar uma branch com o teu nome**
```bash
git checkout -b branch-<nome>
```

3. **Criar o ficheiro**
```bash
"Olá, eu sou o <nome>!" > Ficheiros/<nome>.txt
```

4. **Adicionar, fazer commit e push**
```bash
git add .
git commit -m "Adicionar ficheiro <nome>.txt"
git push -u origin branch-<nome>
```

5. **No GitHub**
- Vai ao repositório no GitHub
- Clica em **Compare & Pull Request**
- Clica em **Create Pull Request**
- Depois de aprovado, faz **Merge**

---

### 👉 Opção 2 — Usando o **GitHub Desktop**

1. Abre o **GitHub Desktop**. Podes fazer o download através deste [Link](https://desktop.github.com/download/)
2. Vai a **File → Clone Repository...** e escolhe este repositório
3. Clica em **Current Branch → New Branch**, e chama-lhe `branch-<nome>`
4. No teu explorador de ficheiros, cria uma pasta com o teu nome e adiciona um ficheiro `.txt` lá dentro
5. Volta ao GitHub Desktop:
- Vai aparecer o ficheiro como "Changed"
- Escreve uma mensagem de commit, por exemplo:
  > Adicionar ficheiro de <nome>
- Clica em **Commit to branch-<nome>**
- Depois clica em **Push origin**
6. No GitHub, cria o Pull Request e faz o merge

---

## ✅ O que deves entregar
- [ ] Branch criada com o teu nome
- [ ] Ficheiro `.txt` com uma frase tua
- [ ] Pull Request feito e merge concluído  

---

## 💡 Dica
Se quiseres ver o teu progresso:
```bash
git status
```

---

## 📚 Recursos úteis
- [Documentação oficial do Git](https://git-scm.com/doc)
- [Guia rápido do GitHub Desktop](https://docs.github.com/desktop)  