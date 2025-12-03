Dashboard de Análisis de Personal – Power BI

Dashboard enfocado en visualizar estructura de empleados, desempeño, costos salariales y distribución etaria para una empresa con 207 empleados.

🎯 Objetivo del análisis
- Analizar distribución de empleados por edad
- Evaluar desempeño por departamento y rango etario
- Estudiar evolución de contrataciones por año
- Comparar departamentos por cantidad de empleados y costos

🧩 Funcionalidades principales
- Pirámide poblacional
- KPI de Empleados activos y Costo salarial  
- Gráfico de barras para cantidad de empleados según el desempeño
- Gráfico de barras por año de cantidad de contratados por año 
- Tabla por departamento (costos/gerentes)
- Filtros dinámicos por departamento

🛠️ Tecnologías utilizadas
- Power BI (DAX)
    - DAX: medida Costo salarial (Costo_Salarial = SUM(integrantes[Salario]))
    - DAX: medida Total de personal (Tot_Personal = COUNTROWS(integrantes))
- Modelado relacional
    - El modelo se encuentra en la carpeta correspondiente de este repositorio. 
- Power Query
    - Eliminar columnas.
    - Primer fila como encabezado.
    - Columna "Rango" a partir de columna Edad con AI para rango etario

📂 Estructura del proyecto

|-- Capturas/
|-- Modelado/
|-- PowerBI/
| └── HR_Dashboard.pbix
└── README.md

📚 Sobre el dataset
Dataset provisto por el curso ZakiData (no distribuible).

 ✨ Aprendizajes clave
- DAX
- Storytelling de RRHH  
- Construcción de métricas operativas
- Visualización avanzada para áreas de personal  
