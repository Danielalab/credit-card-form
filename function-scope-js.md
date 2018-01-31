# Function Scope Js

El siguiente Readme presenta las diversas funciones identificadas en el archivo app.js 

### Funciones Globales
+ La función anónima y statement declarada en la línea 1 del archivo.

### Funciones Locales

+ Función activeButton
+ Función desactiveButton
+ Función longitud
+ Función soloNumeros
+ Función isValidCreditCard

### Funciones Callback

+ La función anónima y statement declara en la linea 1 , escucha el evento ready del objeto document.
+ La función anónima y statement declarada en la linea 14 , escucha el evento input.

### Funciones Expresions  
No se encontró ninguna función expresions

### Funciones Statement

+ Función activeButton
+ Función desactiveButton
+ Función longitud
+ Función soloNumeros
+ Función isValidCreditCard

### Clousure
+ Por el clousure la función activeButton y la función desactiveButton pueden hacer referencia a la variable $buttonNext ya que recuerda el entorno donde fue creada.

### Scope
Las siguientes variables son de scope local dentro de la función statement que escucha el evento ready del objeto document:
+  var $inputCard
+  var $inputMonth 
+  var $inputYear 
+  var $buttonNext 
+  var regexOnlyNumbers
+  var labelErrorOrSuccessMessages 

La variable *regex* (linea 37) es de scope local dentro de la función soloNumeros.
Las siguientes variables son de scope local dentro de la función isValidCreditCard :
+ var creditCardNumber
+ var arr
+ var sumaTotal
+ var index (lineas: 49, 52 ,59)

### Contexto de ejecución 
#### + STACK EXECUTION
El siguiente orden inicia desde la base de la pila de ejecución.  
1. La función  console.log('Probar con el numero valido 4544164785372342'); en la línea 3 del archivo. 

#### + EVENT QUEUE
1. La función isValidCreditCard.
2. La función soloNumeros
3. La función longitud
4. La función activeButton
5. La función desactiveButton



