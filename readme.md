# Proyecto de ejemplo

## Requisitos
Configuración para Ganache
Deberemos tener metamask en nuestro navegador, con la importación de alguno de los usuarios de Ganache
Deberemos tener instalado Truffle

Cargar el proyecto con `npm run start`
Una vez revisado que funciona bien y nos muestra que no tenemos datos, deberemos migrar la información a nuestro Ganache

truffle migrate --reset

Si entramos en ganache, deberíamos ver en contracts nuestros datos.

El usuario podrá hacer stake, recibir recompensa y retirar el stake.

Para migrar a la red de polygon: truffle migrate --reset --network polygon