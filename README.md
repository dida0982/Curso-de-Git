#Curso de Git e GitHub

git (local) != GitHub (remoto)

1. **`git config user.name "Seu Nome"`**  
   Configura o nome do usuário localmente, usado para identificar quem fez os commits.

2. **`git init`**  
   Inicializa um novo repositório Git no diretório atual, criando a pasta `.git`.

---

### **Status e Gerenciamento de Arquivos**

3. **`git status`**  
   Exibe o status do repositório, mostrando arquivos modificados, novos e prontos para commit.

4. **`git add "arquivo"`**  
   Adiciona um arquivo específico ao estágio (staging area), preparando-o para commit.

5. **`git add .`**  
   Adiciona todos os arquivos modificados e novos ao estágio.

---

### **Commits**

6. **`git commit 'nome do arquivo' -m 'comentario'`**  
   *Sintaxe incorreta.* O correto seria:  
   ```bash
   git commit -m 'comentário'
   ```
   Faz o commit das alterações no estágio com uma mensagem explicativa.

7. **`git commit -m 'comentario'`**  
   Faz o commit das alterações no estágio com a mensagem passada.

---

### **Branches e Controle de Fluxo**

8. **`git branch -M main`**  
   Renomeia a branch atual para "main". É comum usá-lo após inicializar o repositório para adotar a convenção atual.

9. **`git branch`**  
   Lista todas as branches do repositório e indica qual está ativa.

10. **`git branch 'nome da branch'`**  
   Cria uma nova branch com o nome especificado.

11. **`git checkout`**  
   Troca para outra branch ou desfaz alterações em arquivos específicos.

12. **`git checkout -b 'branch nova'`**  
   Cria uma nova branch e alterna para ela imediatamente.

13. **`git branch -D 'nome da branch'`**  
   Exclui a branch especificada, forçando a exclusão mesmo que ela tenha alterações não mescladas.

14. **`git merge 'nome da branch'`**  
   Mescla a branch especificada com a branch atual.

15. **`git merge main`**  
   Mescla as alterações da branch `main` com a branch atual.

---

### **Sincronização com o Repositório Remoto**

16. **`git remote add origin 'http:---------'`**  
   Adiciona o repositório remoto chamado `origin` associado ao URL especificado.

17. **`git push`**  
   Envia as alterações locais para o repositório remoto na branch ativa.

18. **`git pull`**  
   Atualiza a branch local com as alterações do repositório remoto.

19. **`git clone ''`**  
   Cria uma cópia local de um repositório remoto a partir do URL fornecido.

---

### **Histórico e Restauração**

20. **`git log`**  
   Exibe o histórico completo de commits do repositório.

21. **`git restore`**  
   Restaura arquivos ao estado mais recente do repositório, desfazendo alterações não comitadas.

22. **`git reset --hard origin/main`**  
   Redefine o repositório local para coincidir com o estado atual do repositório remoto na branch `main`.

---

### **Outros**

23. **`gitignore`**  
   Refere-se a um arquivo chamado `.gitignore`, onde você pode especificar arquivos ou diretórios que o Git deve ignorar.

---

Se precisar de mais detalhes sobre algum comando ou uma explicação mais aprofundada, é só falar! 😊

