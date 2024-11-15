FROM mongo:3.4

COPY drop/* usr/local/data/db/

#es como Entrypoint, pero CMD se puede sobreescribir con otro al 
#ejecutar el contenedor
CMD ["mongod", "--smallfiles", "--rest"]