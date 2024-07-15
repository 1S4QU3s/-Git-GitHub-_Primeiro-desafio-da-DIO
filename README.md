# Link para download do Git: https://git-scm.com/downloads
*O Git Bash é um terminal extendido para otimizar o uso do Git.

Aqui está uma lista dos comandos Git mais comuns e suas funções:

Configuração e Inicialização
git config: Configura as preferências do usuário, como nome de usuário e email.
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
git init: Inicializa um novo repositório Git.
git init
git clone: Clona um repositório existente.
git clone <url-do-repositório>
Gerenciamento de Arquivos
git add: Adiciona arquivos ao índice (staging area).
git add <arquivo>
git add . (adiciona todos os arquivos)
git rm: Remove arquivos do índice e do diretório de trabalho.
git rm <arquivo>
git mv: Move ou renomeia arquivos.
git mv <arquivo-antigo> <arquivo-novo>
Cometimento de Mudanças
git commit: Salva as mudanças no repositório local.
git commit -m "mensagem do commit"
git commit (abre o editor para escrever uma mensagem de commit)
Verificação de Status e Histórico
git status: Mostra o status das mudanças no diretório de trabalho e no índice.
git status
git log: Mostra o histórico de commits.
git log
git log --oneline (exibe cada commit em uma única linha)
git log --graph --decorate (exibe um gráfico ASCII do histórico de commits)
Ramificação e Mesclagem
git branch: Gerencia as branches (ramificações).
git branch (lista todas as branches)
git branch <nome-da-branch> (cria uma nova branch)
git branch -d <nome-da-branch> (deleta uma branch)
git checkout: Troca de branch ou restaura arquivos.
git checkout <nome-da-branch> (troca de branch)
git checkout -b <nome-da-branch> (cria e troca para uma nova branch)
git merge: Mescla mudanças de uma branch em outra.
git merge <nome-da-branch>
Repositórios Remotos
git remote: Gerencia repositórios remotos.
git remote add <nome> <url> (adiciona um repositório remoto)
git remote -v (exibe os repositórios remotos)
git fetch: Busca mudanças do repositório remoto sem integrá-las.
git fetch <nome-remoto>
git pull: Busca e mescla mudanças do repositório remoto.
git pull <nome-remoto> <nome-da-branch>
git push: Envia mudanças para o repositório remoto.
git push <nome-remoto> <nome-da-branch>
Inspeção e Comparação
git diff: Mostra as diferenças entre commits, branches ou o índice e o diretório de trabalho.
git diff
git diff <commit1> <commit2>
git show: Mostra detalhes de um commit específico.
git show <commit>


![image](https://github.com/user-attachments/assets/0c87918c-f27e-47b2-81b5-dd58b68f857e)

