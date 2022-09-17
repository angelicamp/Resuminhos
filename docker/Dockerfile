FROM node:16 : a partir de uma imagem do node na versao 16
WORKDIR /app-node : na minha imagem vou usar esse diretorio
COPY . . : = COPY <do meu diretorio onde esta esse arquivo copia tudo> <para esse diretorio WORKDIR>
RUN echo "Arquivos copiados com sucesso"
RUN npm install : instala todas as dependencias do node
ENTRYPOINT node app.js : comando de entrada do arquivo
