# PROGRAMA CIFRADO CESAR

# PSEUDOCODIGO
INICIO
DECLARAR LA FUNCION 
Para (var i=0; i<text.length ; i++), Comparar y luego incrementa
    letra = text.charCodeAt(i); Sacar el código ASCII de cada letra
    Comparar letras según posición ASCII
         letra = (letra-65+33)%26+65  Aplicar la fórmula según código ASCII
         letra = String.fromCharCode(letra)  Obtener la nueva letra según posición ASCII
         sustit += letra  Se añade la nueva letra
         
        else if(letra>=97 && letra<=122) Nueva condición entre rangos según ASCII 
            letra = (letra-97+33)%26+97;  Aplicando la fórmula para código ASCII
            letra= String.fromCharCode(letra);
            sustit += letra 
          }
        }
  console.log((cipher(prompt)))  Mostrar en consola el cifrado