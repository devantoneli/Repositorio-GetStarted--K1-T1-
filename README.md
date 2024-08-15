# GetStarted K1-T1
Atividade da trilha (K1-T1): Versionamento de Código. 

## Comandos Git

### Básicos

* `git init`:
Inicializa um novo repositório Git em um diretório. Cria a estrutura inicial de diretórios e o repositório `.git`.

* `git clone [url]`: Clona um repositório Git remoto para o seu computador. Copia todo o histórico de versões.

* `git status`: Mostra o estado atual do repositório, incluindo arquivos modificados, adicionados e não rastreados.

* `git add [arquivo]`:  Adiciona o arquivo especificado à área de stage, preparando-o para o commit.

* `git commit -m "mensagem"`: Cria um commit com as mudanças na área de stage, junto com uma mensagem descritiva.

* `git push`: Envia os commits do repositório local para o repositório remoto.

* `git pull`: Baixa as mudanças do repositório remoto para o repositório local e as mescla com o branch atual.

* `git branch`: Lista todas as branches no repositório. Com a opção a, lista todas as branches, incluindo as remotas.

* `git checkout [branch]`: Muda para a branch especificada.

* `git merge [branch]`: Mescla a branch especificada com a branch atual.

### Avançados

* `git rebase [branch]`: Reaplica os commits da branch atual sobre outra branch, criando uma linha do tempo linear.

* `git cherry-pick [hash]`: Aplica o commit específico de outro branch na branch atual.

* `git stash`: Salva temporariamente as mudanças não commitadas em uma pilha, permitindo que você volte para uma branch limpa.

* `git stash pop`: Aplica as mudanças salvas no stash à branch atual e remove o stash.

* `git reset [--soft | --mixed | --hard] [hash]`: Reseta o histórico de commits. -soft mantém as mudanças em stage, -mixed mantém as mudanças no working directory, e -hard apaga todas as mudanças.

* `git revert [hash]`: Reverte as mudanças de um commit específico, criando um novo commit que desfaz essas mudanças.

* `git log`: Mostra o histórico de commits. Com a opção -oneline, exibe um resumo de uma linha por commit.

* `git diff [branch]`: Compara a diferença entre a branch atual e outra branch.

* `git fetch`: Baixa as atualizações do repositório remoto, mas não mescla as mudanças.

* `git tag [nome] [hash]`: Marca um commit específico com um nome para referência futura.


