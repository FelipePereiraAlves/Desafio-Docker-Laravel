FROM nginx:1.15.0-alpine

#remover o arquivo de configuração padrão do nginx o index.html
RUN rm /etc/nginx/conf.d/default.conf

#Copiar os arquivos de configuração criado por nos em outro arquivo.
COPY ./nginx.conf /etc/nginx/conf.d