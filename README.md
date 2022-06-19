# (DIO) Santander Bootcamp Fullstack Developer
## _Módulo I: Introdução ao Git e ao GitHub_

### Objetivo
Entender os conceitos básicos sobre o GIT e o GitHub.

### Anotações Gerais
Observações e anotações gerais levantadas ao decorrer das aulas online.

#### _GIT e GitHub são coisas diferentes!_
- GIT é um sistema de Controle de Versões Distribuído (DVCS) na máquina local.
- Já o GitHub é uma plataforma de hospedagem (servidor) de código-fonte e arquivos com controle de versão usando o Git.

#### _GIT Bash - Comandos via Terminal (CLI)_
  
  O GIT Bash pode ser acessado através da opção "GitBash Here" no diretório desejado.

  | Comando | Descrição |
  | ------ | ------ |
  | DIR | Lista as pastas do diretório atual |
  | CD | Navegação entre o diretório |
  | CLEAR (CTRL+L) | Limpa o prompt de comando  |
  | (TAB) | Autopreenchimento sugerido pelo GIT Bash  |
  | MKIDR | Cria um novo diretório  |
  | LS | Lista o conteúdo do diretório atual  |
  | ECHO | Habilita a exibição de comandos no prompt  |
  | CD .. | Volta um nível do diretório atual  |
  | DEL | Apaga o conteúdo mantendo o diretório  |
  | RMDIR  | Apaga todo o conteúdo inclusive o próprio diretório  |
  
#### _Funcionamento do GIT_
- Utiliza o hash SHA (Secure Hash Algorithm) como criptografia que gera um conjunto único de 40 caracteres. É uma forma curta de representar o estado do arquivo. Via Git Bash inserir o seguinte comando:

  ```sh
  openssl sha1 <nome_do_arquivo> | Output: "SHA1(texto.txt)= ef67e0868c98e5f0b0e2fcd9b0c4a3bad808f551"
  ```
- Os objetos internos que compõem o GIT (Blobs, Trees, Commits) também possuem uma chave única SHA1.
- Composição hierarquica dos objetos, COMMIT > TREE > BLOB.


## Recursos

Os recursos utilizados nesse módulo e suas respectivas instruções estão listadas abaixo.

| Nome | Link | Versão |
| ------ | ------ |------ |
| Git | [https://git-scm.com/docs](https://git-scm.com/docs) | 2.36.1-64-bit |
| GitHub | [https://docs.github.com/pt](https://docs.github.com/pt) | [https://github.com/](https://github.com/) |
