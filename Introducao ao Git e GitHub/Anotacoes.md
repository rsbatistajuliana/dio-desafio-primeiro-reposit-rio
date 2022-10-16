# Anotações

Git é um sistema seguro, distribuído com várias cópias de si distribuídas.

Link para baixar o Git: https://git-scm.com/download/win

O Git Bash é um terminal extendido para facilitar o uso do Git.

### Versionamento:

* O controle de versões é feito com base em identificadores SHA1 que são uma sequência única de caracteres com 40 digitos para cada arquivo e objeto do Git.

* Commits são compostos por trees que são compostas por bobs.
  Cada objeto tem seu conjunto de metadados associados e seu SHA1. 
  Uma mudança num blob acarreta num novo SHA1 para toda a estrutura a qual ele pertence.

* Chave SSH é uma maneira segura de estabelecer uma conxão segura entre duas máquinas.
  para isso é necessário criar um par de chaves pública e privada para essa conexão e uma chave SSH no github.

* Token de acesso pessoal é gerado pelo GitHub, com validade escolhida pelo usuário.
  É exibida uma única vez e deve ser mantida em segurança para consultas posteriores.
