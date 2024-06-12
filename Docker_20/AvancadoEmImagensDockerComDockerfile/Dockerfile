
## execurtar a linha abaixo no terminal para construir a imagem
## docker build -t ubuntu-curl -f Dockerfile .

## docker build => constroi a imagem ubuntu-curl
## -t => nome da imagem
## -f => arquivo Dockerfile
## . => diretorio de contexto (onde esta o Dockerfile)





FROM ubuntu 
RUN apt update && apt install -y curl
LABEL contato="alessandrocds@gmail.com"
WORKDIR /app
COPY arquivo.txt .
ADD https://tm.ibxk.com.br/materias/5866/21577.jpg minhaImagem.jpg
ADD arquivo.tar.gz ./

## RUN => executa um comando
## WORKDIR => define o diretorio de trabalho
## COPY => copia arquivos de um diretorio para outro
## ADD => copia arquivos de um url para um diretorio
## ADD => copia arquivos compactados e descompacta em um diretorio