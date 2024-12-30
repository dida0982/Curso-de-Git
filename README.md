# Curso de Git e GitHub

## ```git``` (local) != ```GitHub``` (remoto)

Configura o nome do usuário localmente, usado para identificar quem fez os commits.
 ``` 
 git config user.name "Seu Nome"
```
 
Inicializa um novo repositório Git no diretório atual, criando a pasta `.git`.
 ``` 
 git init
```

 Exibe o status do repositório, mostrando arquivos modificados, novos e prontos para commit.
 ```
 git status
 ```                         

 Adiciona um arquivo específico ao estágio (staging area), preparando-o para commit.
 ```
 git add "arquivo"
```                    

 Adiciona todos os arquivos modificados e novos ao estágio.
 ```
 git add .
```                             

 Faz commit.
 ```
 git commit -m 'comentário'
```        
 
 Renomeia a branch atual para "main". É comum usá-lo após inicializar o repositório para adotar a convenção atual.
 ```
 git branch -M main
```                   

 Lista todas as branches do repositório e indica qual está ativa.
 ```
 git branch
```                           

 Cria uma nova branch com o nome especificado.
 ```
 git branch 'nome da branch'
```         

 Troca para outra branch ou desfaz alterações em arquivos específicos.
 ```
 git checkout
```                         

 Cria uma nova branch e alterna para ela imediatamente.
 ```
 git checkout -b 'branch nova'
```         

 Exclui a branch especificada, forçando a exclusão mesmo que ela tenha alterações não mescladas.
 ```
 git branch -D 'nome da branch'
```        

 Mescla a branch especificada com a branch atual.
 ```
 git merge 'nome da branch'
```            

 Mescla as alterações da branch `main` com a branch atual.
 ```
 git merge main
```                        

 Adiciona o repositório remoto chamado `origin` associado ao URL especificado.
 ```
 git remote add origin 'http:------'
```   

 Envia as alterações locais para o repositório remoto na branch ativa.
 ```
 git push
```                              

 Atualiza a branch local com as alterações do repositório remoto.
 ```
 git pull
```                              

 Cria uma cópia local de um repositório remoto a partir do URL fornecido.
 ```
 git clone ''
```                          

 Exibe o histórico completo de commits do repositório.
 ```
 git log
```                               

 Restaura arquivos ao estado mais recente do repositório, desfazendo alterações não comitadas.
 ```
 git restore
```                           

 Redefine o repositório local para coincidir com o estado atual do repositório remoto na branch `main`.
 ```
 git reset --hard origin/main
```   
 
 Arquivo `.gitignore`, especificar arquivos ou diretórios que o Git deve ignorar.                          
