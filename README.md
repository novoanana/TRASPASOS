# TRASPASOS V1

Primera versión funcional de TRASPASOS para consolidar los archivos diarios de los departamentos.

## Qué hace
- Selección manual de departamento y día.
- Carga de XLSX/XLS/CSV.
- Detecta columnas ID, REFERENCIA y CANTIDAD/TOTAL.
- Impide sobrescribir silenciosamente un día ya cargado.
- Consolida cada artículo por ID y suma toda la semana.
- Muestra totales diarios.
- Control especial del viernes.
- Control de integridad: suma diaria = suma de artículos.
- Búsqueda por ID o referencia.
- Exportación CSV e impresión.
- Guarda temporalmente la semana en el navegador mediante localStorage.

## Prueba
Puedes cargar los cinco archivos diarios reales de prueba. Para probar sin archivos, se puede incorporar después un botón Demo con el dataset de TRASPASOS.xlsx.

## Próxima fase
1. Conectar almacenamiento persistente (Google Sheets / Apps Script).
2. Gestionar múltiples departamentos.
3. Histórico de semanas.
4. Identificación oficial de IDs del hotel.
5. Integración futura con ECONOMATO.
