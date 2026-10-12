# Gauss-Jord-n

# EXPLICACIÓN DE LA ESTRUCTURA MODULAR:
El programa esta diseñado siguiendo el paradigma modular lo que significa que el codigo fuente se dividio en 3 partes (archivos) o por otro nombre como (clases independientes) con las terminación ".Java", donde cada uno tiene un rol y/o responsabilidad de manera especifica y única:
1. Lanzador_GaussJ.java: Esta es la clase principal del programa en la cual se compila el codigó. 
Contiene el método "Main" 
Este áctua como el punto de entrada del programa, su trabajo es interactuar con el usuario a tráves de la consola, decidir si se leen nuevos datos o se usa una matriz por defecto para posteriormente por una serie de algoritmos te muestre los resultados finales de la operación
2. GaussJ.java: Esta es la clase de lógica matemática. Esta contiene la lógica pesada del método numérico, el cual implementa tanto la "eliminación gaussiana" como el método de Gauss.Jordan; esta se encuentra desaclopada de la interfaz de usuario lo que hace que se pueda reutilizar.
3. Defmatriz: Dsta es la clase de datos o entrada, esta se encarga de manera única de la gestión de los datos que en este caso son las matrices; este apartado contiene un método el cual se encarga de pedir las ecuaciones al usario paso a paso por la consola y otro metodo que almacena una matriz por defecto como ejemplo de pruebas rápidas


# PASOS PARA SU COMPILACIÓN Y EJECUCIÓN:

1. Verificar que los archivos estén en el mismo paquete:
Lanzador_GaussJ.java
Gaussj.java
defmatrizGJ.java
Se puede verificar en el lado izquierdo superior del compilador intellijIDEA (Project), posteriormente despliega tu proyecto hasta la carpeta "scr" y confirma que los 3 archivos se encuentren ahi 
2. Ejecutar la clase principal:
   Como los arcivhos estan en el mismo directorio de trabajo, el compilador  detecta automaticamente las llamadas entre clases que en este caso seria Lanzador_GaussJ o defmatrizGJ.

3. Revisar la consola inferior:
    En entorno compilara los archivos en segundo plano y mostrara el menú del metodo de Gauss-Jordan en la pestaña "Run"
    se puede verificar mediante la consola la cual debe mostrar las opciones del menú interactivo "Ingresar datos por consola" sin que este arroje errores de simbolo.
#CODIGÓ COMPILADO PREDETERMINADO:
------------------------------------------------------
    MÉTODO DE GAUSS-JORDÁN - MÉTODOS NUMÉRICOS        
------------------------------------------------------
         1. Ingresar datos por la consola             
      2. Usar matriz por defecto del ejemplo en clase 
               Seleccione una opción:                   3

 Soluciones del sistema (Gauss-Jordan):
x1 = 2,3990
x2 = -4,4998
x3 = 3,3292

Process finished with exit code 0

#CODIGÓ COMPILADO CON OTROS DATOS:
------------------------------------------------------
    MÉTODO DE GAUSS-JORDÁN - MÉTODOS NUMÉRICOS        
------------------------------------------------------
         1. Ingresar datos por la consola             
      2. Usar matriz por defecto del ejemplo en clase 
               Seleccione una opción:                   1
Ingrese el número de ecuaciones (variables): 3

Ingrese los coeficientes y el término independiente para cada ecuación:
Ecuación 1:
  Coeficiente x1: 2
  Coeficiente x2: 3
  Coeficiente x3: 8
  Término independiente (b1): 12
Ecuación 2:
  Coeficiente x1: 1
  Coeficiente x2: 4
  Coeficiente x3: 3
  Término independiente (b2): 24
Ecuación 3:
  Coeficiente x1: 9
  Coeficiente x2: 6
  Coeficiente x3: 0
  Término independiente (b3): 12

 Soluciones del sistema (Gauss-Jordan):
x1 = -3,3846
x2 = 7,0769
x3 = -0,3077

Process finished with exit code 0
