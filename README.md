# Modelo Macroeconómico de Hogares

Este repositorio contiene una simulación en Gretl que modela la estructura económica de hogares ficticios, con el objetivo de analizar dinámicas macroeconómicas como ingreso, consumo, deuda, ahorro, nivel educativo y formalidad laboral.

## Descripción general

- Se generan microdatos sintéticos de 500 hogares.
- Se incluyen variables clave: ingresos, consumo, deuda, tamaño del hogar, edad del jefe, educación y formalidad.
- Se aplican modelos econométricos (regresiones clásicas y log-log).
- Se analizan diferencias por sector formal/informal.
- Se calcula la tasa de ahorro promedio por nivel educativo.

## Archivos incluidos

- `modelo_macroeconomico_hogares.inp`: script completo en Hansl.
- `README.md`: este archivo de documentación.
- (Opcional) `.gfn`: versión empaquetada del script.

## Uso

1. Abre el script en Gretl 2025b o superior.
2. Ejecuta desde el principio para generar los datos simulados.
3. Observa los resultados econométricos y cálculos agregados.
4. Puedes modificar parámetros como tamaño de muestra, estructura de formalidad o composición educativa.

## Créditos

Este proyecto fue creado para fines educativos y de experimentación econométrica.  
Autor: *Edward Ugarte (simulación y diseño econométrico)*  
Licencia: [MIT](https://opensource.org/licenses/MIT)

