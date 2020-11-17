# Template para los proyectos de la Dirección de Tranformación Digital
La estructura es la siguiente

- __functions__: las funciones que puedan ser útiles a todos los análisis
- __pedidos_recurrentes__: pedidos cuya estructura no cambia mucho, como analizar los pilotajes, o hacer comparaciones de operación
  - __files__
    - data
      - input
      - intermedia
      - output
    - models
    - references
  - __notebooks__
    - eda
  - __src__
    - modeling
    - preparation
    - preprocessing
- __pedidos_unicos__: pedidos que se hacen una sola vez, la estructura puede ser de cualquier tipo
- __template__: carpetas para copiar al iniciar un nuevo pedido recurrente
