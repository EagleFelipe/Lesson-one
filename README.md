# 🧠 Primeiros Passos com Git e GitHub

Este repositório representa minha **primeira lição prática utilizando Git e GitHub**. Estou dando os primeiros passos no mundo do desenvolvimento e aprendendo na prática como controlar versões de um projeto.

Até agora, aprendi a:

- Utilizar comandos básicos no **Git Bash**
- Criar um repositório local com **`git init`**
- Enviar um repositório local para o GitHub com **`git remote add`** e **`git push`**
- Fazer alterações diretamente no GitHub e sincronizar com meu repositório local
- Usar os comandos **`git pull`**, **`git push`**, **`git status`**, **`git add`**,**`git rm nome-do-arquivo`**,**`git restore nome-do-arquivo`**, **`git commit`** e outros para manter o projeto atualizado
- Usar a tecla "." no Github para habilitar o modo .dev

---

## 🛠️ Seção de anotações pessoais sobre sincronizar com o GitHub

- Para **trazer atualizações do repositório remoto (GitHub)** para minha máquina local, usar:  
  **`git pull`**

- Para **enviar alterações locais para o GitHub** :  
  **`git push`**  
  > ⚠️ Sempre executar um **`git pull`** **antes** de um **`git push`**, para garantir que o repositório local está atualizado com as mudanças feitas por outros colaboradores. Isso ajuda a evitar conflitos.

- Para que o **`git pull` funcione corretamente**, observar se as alterações locais foram commitadas (salvas).

  Para tal:

  1. Verifique os arquivos modificados com: **`git status`**
  2. Adicione os arquivos que deseja versionar com: **`git add .`**
  3. Crie um commit com: **`git commit -m "mensagem descritiva"`**

- Para **copiar um projeto completo do GitHub** (por exemplo, ao trocar de máquina), use:  
  **`git clone <URL-do-repositório>`**  
  Isso vai baixar todos os arquivos e o histórico do projeto na máquina.

---

📌 "The journey of a thousand miles begins with a single step." – Lao Tzu
