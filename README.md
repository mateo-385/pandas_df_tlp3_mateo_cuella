# Actividad - Trabajando con DataFrames de Pandas

## Requisitos

- Python 3.x
- Librerías necesarias (incluidas en `requirements.txt`):
  - `pandas`
  - `sqlite3`

## Actividades

1. **Top 10 empleados con mayor salario total (incluyendo beneficios):**

   - Extraer e imprimir un top 10 de empleados con mayor salario total.

2. **Filtrar empleados con más de 50,000 en horas extra:**

   - Filtrar los empleados cuya columna `OvertimePay` sea mayor a 50,000.

3. **Contar cuántos empleados únicos hay por año:**

   - Agrupar por año y contar los empleados únicos.

4. **Ver cuántos cargos únicos existen y los 5 más comunes:**

   - Contar los cargos únicos y mostrar los 5 más comunes.

5. **Mostrar el salario total promedio por año:**

   - Calcular y mostrar el promedio del salario total por año con formato de moneda.

6. **Exportar los datos a un archivo CSV:**
   - Exportar el DataFrame a un archivo `salarios.csv` y mostrar los últimos 10 valores.

## Estructura del Repositorio

- `actividad_df.ipynb`: Notebook principal con las actividades resueltas.
- `Salaries.sqlite`: Base de datos utilizada para el análisis.
- `salarios.csv`: Archivo CSV generado con los datos exportados.
- `requirements.txt`: Archivo con las dependencias necesarias para ejecutar el proyecto.

## Cómo Ejecutar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/mateo-385/pandas_df_tlp3_mateo_cuella
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abre el archivo actividad_df.ipynb en Jupyter Notebook o en tu editor de preferencia (como VS Code).

4. Ejecuta las celdas en orden para realizar las actividades.
