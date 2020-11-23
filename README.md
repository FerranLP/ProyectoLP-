# ProyectoLP
Este proyecto trata de crear un árbol de decisión (decision Tree) en Haskell con los datos que tenemos en el fichero "agaricus-lepiota.data".

# Descripcion
Aunque dentro del codigo solo tengamos 2 partes marcadas, el cálculo de la entropía y la creación del árbol, podríamos dividir el programa en un total de 3.

  1a parte: La primera parte del programa es el cáluclo de la entropia.
  
  2a parte: La seunda parte del programa es la creacion del árbol a partir del cálculo de la primera parte.
  
  3a parte: Esta parte ya para finalizar sería la parte donde se imprime el árbol y se pregunta al usuario como se quiere recorrer. 
  
# Instalación  
La instalación del programa es muy simple:

    1.Primero de todo tendremos que entrar con la consola al directorio donde tengamos el progrma "dts.hs" 
      y el archivo "agaricus-lepiota.data".
    
    2.Debemos ejecutar el siguiente comando para entrar al compilador de haskell: -$ ghci
    
    3.Una vez en el compilador compilaremos el programa poniendo: Prelude> :load dts.hs
    
    Si quisieramos correr el programa simplemente tendriamos que ejecutar el siguiente comando: Prelude> main
    
Si esta opción nos falla dejo otra opción:

    Desde la carpeta donde tenemos el programa "dts.hs" y el archivo "agaricus-lepiota.data" abrimos la terminal 
      y ejecutamos el siguiente comando:
    -$ ghc dts.hs. Este nos generará 3 archivos: "dts", "dts.hi", "dts.o"
    Si quisieramos correr el programa simplemente tendriamos que ejecutar el siguiente comando: -$ ./dts

# Usage
Una vez compilado y ejecutado el programa nos imprimirá un árbol. Este es el árbol de decisión. A continuación el programa nos preguntará alguna característica de una seta y nosotros tendremos que ir respondiendo. Una vez hayamos respondido (como máximo 4 preguntas) el programa irá filtrando las respuestas y recorriendo el árbol para así decirnos si la seta que hemos descrito con las respuestas es venenosa o comestible.
