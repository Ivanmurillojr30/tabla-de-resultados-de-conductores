Mostrar la tabla de resultados de conductores en un TablaView

#capturas


![Captura de pantalla 2024-07-09 171351](https://github.com/Ivanmurillojr30/tabla-de-resultados-de-conductores/assets/168851753/dd0dd86d-a938-4e47-86c6-cc1a479816b6)


![Captura de pantalla 2024-07-09 135110](https://github.com/Ivanmurillojr30/tabla-de-resultados-de-conductores/assets/168851753/7fab6ce9-8aab-4ab9-b3c4-b4ba39069270)


![Captura de pantalla 2024-07-09 171342](https://github.com/Ivanmurillojr30/tabla-de-resultados-de-conductores/assets/168851753/31f14251-3e93-4fe6-a2ae-a6f38b7254db)


# explicacion 

Este programa es una aplicación JavaFX que muestra estadísticas de pilotos de carreras para los años 2016 a 2020. La interfaz gráfica permite seleccionar el año desde un ComboBox y ver las estadísticas de los pilotos en una tabla. Además, hay un botón que imprime los datos de todos los años en la consola.

Componentes Principales
ComboBox: Permite seleccionar el año para ver las estadísticas correspondientes.
TableView: Muestra los datos de los pilotos en columnas: nombre, equipo, victorias, puntos totales y clasificación.
Button (Print Data): Imprime los datos de todos los años en la consola.
Funcionamiento
start(Stage primaryStage): Configura la ventana principal, crea los componentes (ComboBox, TableView, Button), añade listeners y define el layout.
updateTable(String year): Actualiza la tabla con los datos del año seleccionado.
printTableData(): Imprime en la consola los datos de todos los años.
Datos de Ejemplo
Los datos de ejemplo están definidos en un HashMap<String, ObservableList<Driver>>, donde la clave es el año y el valor es una lista observable de objetos Driver. Cada Driver tiene nombre, equipo, victorias, puntos y clasificación.
