# SmartContractsYBlockchain
version of solidity: 
> - pragma solidity ^0.4.0;          (specific)
> - pragma solidity >=0.4.4 <0.7.0;  (range of versions, from 0.4.4 to 0.7.0)

first steps:
```
contract <contract_name>{
}
```
### Coments: standar natspec
- //     single
- /* */  multiline
- /// @title 'title of the contract'
- /// @author 'author of the contract'
- /// @notice 'What the contract do'
- /// @dev 'details of the contract'
- /// @param 'parameters'
- /// @return 'value return and why'


### Variables enteras

uint<x>  <name_variable>
int<x>  <name_variable>
ejemplo
uint8 entero_8_bits;
uint256 entero_256_bits;

int mi_primer_entero_con_signo;
int mi_numero = -32;


### Variables strings
string <nombre_variable>

### Variables byte
byte<x> <nombre_variable>
 de 1 a 32.

### Variables Address
address <nombre_variable>
 Wallet..
 contienen una direccion de 20bytes


### Enums

enum <nombre_ENUM> {vals}

declarar la variable
<Nombre_enum> <nombre_var>

modificar un enum

<nomb_variable> = <nombre_enumeracion>(<posicioin>);