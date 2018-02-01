# ETHERART

Proyecto de arte colaborativo usando consenso descentralizado. Para ello utiliza una gama de colores como tokens que se combinan de una forma determinada y diferente para cada red, de modo que cada nodo tiene una obra diferente que a su vez es parte de la blockchain.

# Herramientas

En principio, las Herramientas fundamentales son:

- **Ethereum** para el despliegue de la blockchain. Para ello es necesario tener al menos una cartera.
- **Contratos** en C++ para definir los tokens-color, las transacciones y el tipo de consenso.

# Uso

Idealmente, todos los nodos de la red comienzan cada uno con un token diferente, y las transacciones harán que los tokens (acumulativos) vayan variando tanto para cada nodo individual como el resultado de la blockchain.

Para ello, el usuario A que quiere tener una transacciones de colores con B, debe seleccionar el lado o arista que quiere unir. SI la transacción es aceptada tras un POW basado en hashes, este pasa a la cadena de transacciones. 
