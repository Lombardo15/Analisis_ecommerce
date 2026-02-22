# Análisis de Ventas E-commerce

Análisis de datos de ventas de una tienda online usando Python y Pandas.
El proyecto cubre desde la limpieza del dataset hasta visualizaciones y recomendaciones de negocio.

---

## Contenido del repositorio

```
├── practica1_portfolio.ipynb   # Notebook principal con el análisis completo
├── ventas_ecommerce.csv        # Dataset de ventas
└── README.md
```

---

## Objetivo

Limpiar y analizar un dataset de 200 registros de ventas con datos sucios (nulos, cantidades inválidas, fechas sin formato) para responder preguntas clave del negocio e identificar patrones de comportamiento.

---

## Estructura del análisis

### Parte 1 - Limpieza de datos
- Identificación y tratamiento de valores nulos por columna
- Relleno de precios con la **mediana por categoría**
- Relleno de cantidades, ciudades y eliminación de registros inválidos
- Conversión de tipos y creación de la columna `total`

### Parte 2 - Análisis Exploratorio
- Ingreso total generado
- Producto más vendido por cantidad y por ingresos
- Ticket promedio por venta
- Ingresos por categoría

### Parte 3 - Análisis Avanzado
- Ranking de ingresos por categoría
- Top 5 clientes por gasto total
- Evolución de ventas por mes
- Productos con precio superior al promedio de su categoría
- Ciudades con mayor facturación

### Parte 4 - Visualizaciones
- Ingresos por categoría (barras)
- Top 5 clientes (barras horizontales)
- Ingresos por producto (barras)

---

## Principales hallazgos

- El ingreso total del trimestre fue de **$159.274,50** con un ticket promedio de **$829,55**
- **Noviembre** concentró el 51% de los ingresos, probablemente impulsado por Black Friday
- La categoría **Computadoras** representó aproximadamente el 59% del ingreso total
- El producto **Laptop** lideró tanto en unidades vendidas como en ingresos generados
- El **top 5 de clientes** concentró una parte desproporcionada del gasto total

---

## Tecnologías utilizadas

![Python]
![Pandas]
![Matplotlib]
![Seaborn]
![Jupyter]

---

## Cómo ejecutar el proyecto


2. Instala las dependencias
```bash
pip install pandas matplotlib seaborn jupyter
```

---

## Autor

**Adolfo Lombardo**  
[LinkedIn](www.linkedin.com/in/adolfo-lombardo)
