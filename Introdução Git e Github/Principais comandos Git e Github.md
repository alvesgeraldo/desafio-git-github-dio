# Principais comandos para uso do Git e Github

## Iniciar o uso do Git na pasta atual

git init

## Mover arquivos para serem comitados

git add 

Junto com o comando usamos . ou * para indicar que queremos mover tudo

Podemos também usar o nome do arquivo ou pasta a ser movido

## Para fazermos um commit

git commit -m "Aqui passamos uma descrição para o commit"

## Para enviarmos os arquivos do repositório local para o repositório remoto

git push origin main

## Para clonarmos um repositório remoto

git clone https://github.com/

Enviamos o endereço HTTPS completo do repositório a ser clonado

## Para verificarmos status dos nossos arquivos locais

git status

Nos retorna o status dos arquivos locais se ainda seram movidos, se precisam ser comitados, ou se estão prontos para serem enviados para repositório remoto

## Para casos de conflito merge

git pull origin main

Em casos de arquivos no repositório remoto estarem diferentes dos arquivos do nosso repositório local
 
