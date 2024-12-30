#Curso de Git e GitHub

**`git`** (local) != **`GitHub`** (remoto)

 **`git config user.name "Seu Nome"`**      => Configura o nome do usuário localmente, usado para identificar quem fez os commits.
 
 **`git init`**                             => Inicializa um novo repositório Git no diretório atual, criando a pasta `.git`.

 **`git status`**                           => Exibe o status do repositório, mostrando arquivos modificados, novos e prontos para commit.

 **`git add "arquivo"`**                    => Adiciona um arquivo específico ao estágio (staging area), preparando-o para commit.

 **`git add .`**                            => Adiciona todos os arquivos modificados e novos ao estágio.

 **`git commit -m 'comentário'`**           => Faz commit.
 **`git branch -M main`**                   => Renomeia a branch atual para "main". É comum usá-lo após inicializar o repositório para adotar a convenção atual.

 **`git branch`**                           => Lista todas as branches do repositório e indica qual está ativa.

 **`git branch 'nome da branch'`**          => Cria uma nova branch com o nome especificado.

 **`git checkout`**                         => Troca para outra branch ou desfaz alterações em arquivos específicos.

 **`git checkout -b 'branch nova'`**        => Cria uma nova branch e alterna para ela imediatamente.

 **`git branch -D 'nome da branch'`**       => Exclui a branch especificada, forçando a exclusão mesmo que ela tenha alterações não mescladas.

 **`git merge 'nome da branch'`**           => Mescla a branch especificada com a branch atual.

 **`git merge main`**                       => Mescla as alterações da branch `main` com a branch atual.

 **`git remote add origin 'http:------'`**  => Adiciona o repositório remoto chamado `origin` associado ao URL especificado.

 **`git push`**                             => Envia as alterações locais para o repositório remoto na branch ativa.

 **`git pull`**                             => Atualiza a branch local com as alterações do repositório remoto.

 **`git clone ''`**                         => Cria uma cópia local de um repositório remoto a partir do URL fornecido.

 **`git log`**                              => Exibe o histórico completo de commits do repositório.

 **`git restore`**                          => Restaura arquivos ao estado mais recente do repositório, desfazendo alterações não comitadas.

 **`git reset --hard origin/main`**         => Redefine o repositório local para coincidir com o estado atual do repositório remoto na branch `main`.

 **`gitignore`**                            => Refere-se a um arquivo chamado `.gitignore`, onde você pode especificar arquivos ou diretórios que o Git deve ignorar.
