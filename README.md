# Clasificación de clientes y descuentos

Proyecto ADMI 1301 de Mariagna Arias y Alejandro González. La aplicación clasifica clientes según su gasto anual, calcula descuentos, simula pedidos con inventario y compara escenarios de rentabilidad. Los datos son ficticios y están incluidos en el notebook.

## Ejecución

1. Abra `proyecto_fidelizacion.ipynb` en Google Colab, Jupyter o VS Code con soporte de notebooks.
2. Ejecute todas las celdas en orden. El código usa Python y no necesita librerías externas ni archivos adicionales.
3. Modifique los datos de la sección 4 o las políticas de la sección 6 para explorar otros casos. La sección 9 muestra cómo registrar clientes y compras. El menú interactivo se activa quitando el comentario de la última línea de esa sección.
4. Para volver a los datos iniciales, reinicie el entorno y ejecute todas las celdas. Los registros no se guardan permanentemente y repetir una celda de registro duplica sus operaciones.

El escenario base calcula un descuento por rango y antigüedad, limitado para que el precio cubra el costo más 10 %. Las comparaciones consideran los pedidos de ejemplo, en orden, y no predicen cambios de demanda. Para una comparación reproducible, ejecute todo desde el inicio.

## Entrega

El notebook incluye resultados reproducibles y pruebas de funcionamiento. El informe final debe tener máximo dos páginas e incluir al menos dos tablas o figuras. La presentación muestra el problema, la aplicación, los resultados y sus limitaciones.
