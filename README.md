#### Comandos SFTP

#### Login servidor remoto

sftp user@192.168.0.100

#### Comandos

ls - listar arquivos servidor remoto<br>
lls - listar arquivos servidor local<br>
pwd - diretório atual servidor remoto<br>
lpwd - diretório atual servidor local<br>
cd - entrar pasta servidor remoto<br>
lcd - entrar pasta servidor local<br>

EM RESUMO

Colocar o "l" antes do comando para acessar o servidor local.

### Transferir arquivo do servidor remoto para o servidor local

get /Documentos/exemplo.txt

### Enviar arquivo do servidor local para o servidor remoto

put /Documentos/exemplo.txt
