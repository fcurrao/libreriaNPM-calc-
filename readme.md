CALCULADORA EASY_

Description: 
Es una calculadora que cuenta con 4 operaciones basicas

suma(suma)

resta(resta)

multiplicaicon (mult)

division(div)


  ---------------

INSTALL:

npm i calculadora-easy-2

---------------


IMPORT:
  import {suma} from 'calculadora-easy-2'

---------------

  USE:
let resultado = suma(20,2)
console.log("resultado",resultado);
// consola:  22


------------------------

export const suma = (num1, num2) => {
    return num1 + num2;
  };
  
  export const resta = (num1, num2) => {
    return num1 - num2;
  };
  
  export const mult = (num1, num2) => {
    return num1 * num2;
  };
  
  export const div = (num1, num2) => {
    return num1 / num2;
  };

