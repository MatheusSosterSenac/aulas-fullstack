git --version
git config --global user.name "MatheusHenriqueSoster"
git config --global user.email "matheus.soster@alunos.sc.senac.br"
ls -al ~/.ssh
ssh-keygen -t ed25519 -C "matheus.soster@alunos.sc.senac.br"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
clip -T "git@github.com"

git init - inicializa um novo repositorio Git em um diretorio existente
git status - exibe os status atual do repositorio
git add - adiciona arquivos ao indice 
git rm --cached - Remove arquivos do indíce
git branch - lista todas as branchs locais existentes
gir checkout - muda para a branch especifica
git checkout -b - cria uma nova branch e muda para ela
git commit -m - faz um commit das mudanças do indice com uma mensagem descritiva
git merge - realiza o merge da branch atual na branch informada
git push - envia commits do repositorio para o repositorio remoto
git branch -D - exclui a branch requisitada
git fetch - baixa objetos e referências do repositorio remoto
git pull - baixa objetos e referências do repositorio remoto e mescla com a branch atual
