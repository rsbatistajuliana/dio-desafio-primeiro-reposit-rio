# Comandos mais utilizados :

*  cd <name> - para acesso a alguma pasta ou repositório
*  dir ou ls - lista os diretórios da pasta ou repositório
*  cls - limpa o terminal
*  cd .. - volta em um nível na pasta
*  mkdir <name> - cria um novo diretório e solicita o nome do mesmo
*  echo >hello.txt - cria arquivo dentro do diretório do tipo especificado
*  del <name> - deleta apenas os arquivos do repositório name
*  rmdir <name> /s/q - deleta o repositório e seu conteúdo
*  git init - inicia o Git (cria um .git) dessa forma a pasta que estamos trabalhando se transforma num repositório e vai armazenar todo o histórico de versionamento.
*  ls -a - lista todos os arquivos do repositório inclusive os arquivos ocultos(.git é oculto)
*  git config --list - lista todas as configs do git
*  git config --global user.name <name> - define o usuário e posterior autor dos commits [importante ser o mesmo usado no github]
*  git config --global user.email <email> - define o email de usuário do autor dos commits
*  git add <name> - envia para stage apenas o que foi especificado
*  git add *   - envia todos os arquivos de modified para staged (prontos pra serem commited)
*  git commit -m "mensagem" - dão significancia ao commit
*  git status - exibe o status dos arquivos e repositórios
*  git remote add origin <url> - url do novo repositório criado no GitHub e que vai ser utilizado para enviar aos arquivos que ja foram commited
*  git remote -v - lista os url que aponta para o repositório
*  git push origin <master> - empura o repositório de master para origin, sendo master local e origin remoto.
   ! caso erre a url basta fazer:
*  git remote set-url origin <url> - a url antiga é sobrescrita
*  git pull origin <master> - puxa arquivos do remoto para o local
*  git clone <url> - clona o repositório de uma url para seu repositório local.
