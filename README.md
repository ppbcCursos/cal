# Calculadora (cal)

Calculadora sencilla para navegador, desarrollada con HTML, CSS y JavaScript sin dependencias.

## Uso
Abre `calculator.html` en cualquier navegador moderno. No necesita instalación ni servidor.

## Funciones
- Suma, resta, multiplicación y división
- Cuadrado (x²), inverso (1/x) y cambio de signo
- Números decimales y borrado con C
- Control mediante teclado: 0–9, punto/coma, +, -, *, /, Enter, Escape y Retroceso
- Errores de división entre cero y resultados no finitos
- Diseño adaptable y etiquetas accesibles

## Comportamiento
Las operaciones se ejecutan en secuencia al pulsar un operador o =. No es un parser de expresiones con precedencia de operadores. Se limita la entrada a 15 dígitos y los resultados se redondean a 12 cifras significativas para facilitar su lectura.

## Pruebas manuales sugeridas
- 2 + 3 = → 5
- 8 ÷ 2 = → 4
- 5 x² → 25
- 4 1/x → 0,25
- 1 ÷ 0 = → Error
- C → 0

## Estructura
- `calculator.html`: interfaz, estilos y lógica.

## Estado
Primera versión funcional. Pendiente de añadir pruebas automatizadas si el proyecto crece.
