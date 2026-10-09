# Ecuaciones_Lineales

Solución modular de sistemas 3x3 con Gauss y Gauss-Jordan.

### Estructura Modular
- `defmatrizz.java`: Matriz aumentada de prueba.
- `Gauss.java`: Triangulación superior.
- `GaussJordan.java`: Reusa `Gauss.eliminacionGaussiana()`, normaliza pivotes y hace barrido superior.
- `Lanzador_gausjordan.java`: Main, ejecuta y muestra resultados.

### Pasos para compilar y ejecutar
Como los archivos usan `package Ecuaciones_lineales;`:
```bash
javac Ecuaciones_lineales/*.java
java Ecuaciones_lineales.Lanzador_gausjordan
3.0 -0.1 -0.2 | 7.85
0.1  7.0 -0.3 | -19.3
0.3 -0.2 10.0 | 71.4
Soluciones del sistema (Gauss-Jordan):
x1 = 3.0
x2 = -2.5
x3 = 7.0
