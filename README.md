# Megaline: Análisis de planes Surf vs. Ultimate

Proyecto de análisis estadístico basado en datos de 500 clientes de Megaline (2018).  
Se preparan y combinan datasets de llamadas, SMS, internet y planes; se calculan métricas 
mensuales por usuario y se evalúa cuál plan (Surf o Ultimate) genera mayor ingreso promedio.

## Contenido

- Limpieza y preparación de datos (tipos, fechas, uniones por `user_id`).
- Agregación mensual por usuario: minutos, SMS, MB y revenue.
- Visualizaciones (minutos, SMS, datos, revenue por plan/mes).
- Pruebas de hipótesis (t-test) para diferencias de ingresos entre planes y por región.

## Resultados clave

- Los minutos y SMS son similares entre planes; el tráfico de datos muestra alta variabilidad.
- **Ultimate** presenta mayor ingreso promedio y más estable por usuario-mes.
- **Surf** concentra excedentes de datos y mayor dispersión en ingresos.

## Estructura del repositorio

- `Proyecto_S5.ipynb`: notebook principal con código, gráficos y conclusiones.
- Los datos originales provienen del curso de TripleTen y no se comparten en este repositorio.

## Requisitos

- Python 3.x  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scipy`
