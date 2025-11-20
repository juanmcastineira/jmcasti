# jmcasti
Portfolio técnico: proyectos de SQL, BI, EDA y documentación profesional.
# 📊 Proyecto: Normalización y Análisis Exploratorio de Datos (EDA)

Este proyecto se basa en un dataset obtenido de **Kaggle** relacionado con [tema del dataset].  
El objetivo fue practicar **modelado relacional (normalización)** y **análisis exploratorio de datos (EDA)**.  
Además, se simuló una interacción con un "cliente" para definir parámetros y requerimientos, con el fin de ejercitar habilidades de comunicación y documentación.

---

## 🧱 Normalización

### Problema inicial
El dataset original contenía redundancias y atributos mezclados (ej. categorías repetidas en cada fila).

### Proceso
- Identificación de entidades principales:
  - `Clientes`
  - `Productos`
  - `Categorías`
  - `Ventas`
  - `Métodos de pago`
- Aplicación de reglas de normalización (1NF, 2NF, 3NF).
- Creación de tablas puente para relaciones muchos-a-muchos.

### Resultado
Un modelo relacional más limpio, con claves foráneas y sin redundancia, apto para consultas BI y visualización.

---

## 🔎 Exploratory Data Analysis (EDA)

### Análisis realizado
- **Distribución de variables:** edad de clientes, monto de compras, frecuencia de compra.  
- **Outliers:** detección de valores extremos en ticket promedio → análisis con mediana y percentiles.  
- **Correlaciones:** relación entre método de pago y gasto promedio, categoría y frecuencia de compra.  
- **Visualizaciones:** histogramas, boxplots, gráficos de barras para patrones de consumo y estacionalidad.

---

## 📊 Resultados obtenidos a partir de los KPIs

- **Suscripciones por género y edad**  
  - No se observaron variaciones significativas en el ratio de suscripción según la edad.  
  - Sí se detectó una diferencia por género: no hay registros de personas femeninas con suscripciones activas.  

- **Suscripciones por estado**  
  - South Carolina y West Virginia: 36% de usuarios suscriptos.  
  - Kansas: 13%.  
  - Segmento masculino: Nevada y Kentucky alcanzan un 58%, Kansas sube al 24%.  

- **Ingresos por suscripción**  
  - Solo el 27% del ingreso total proviene de usuarios suscriptos.  

- **Métodos de pago**  
  - El ingreso se distribuye de manera pareja entre las distintas metodologías de pago.  
  - En el top 10 de ítems por monto se observa:  
    - PayPal en 4 posiciones (1°, 2°, 7° y 8°).  
    - Tarjeta de crédito en 3 posiciones.  
    - Transferencia bancaria en 2 posiciones.  
    - Tarjeta de débito en 1 posición.  

- **Relación entre precio y rating**  
  - El precio promedio y máximo por rating muestra valores similares.  
  - Los ratings con mejores montos fueron los de **2** y **4** estrellas.  

---

## 📚 Formación técnica

Complemento mi formación universitaria con certificaciones orientadas a análisis de datos y visualización:

- Diplomatura en Ciencia de Datos y Análisis Avanzado  
- Diplomatura en Bases de Datos  
- Cursos de Tableau (UTN, nivel inicial y avanzado)  
- Curso de Excel aplicado + KPI, Power Pivot y Power Map  

Actualmente estoy incorporando Tableau en mis proyectos para enriquecer la visualización de métricas y dashboards interactivos.

---

## 🛠️ Tecnologías utilizadas
- **SQL**: modelado relacional, normalización, consultas analíticas.  
- **Tableau** (en proceso de integración): visualización de KPIs y dashboards.  

---

## ✅ Conclusiones

- La normalización permitió estructurar el dataset y evitar redundancias.  
- El EDA reveló patrones útiles para decisiones de negocio (segmentación, pricing, fidelización).  
- El análisis de KPIs mostró diferencias relevantes por género, estado y método de pago.  
- La simulación de interacción reflejó mi capacidad de comunicación y documentación, clave en proyectos reales.  

---

## 📬 Contacto
- **LinkedIn:** [tu-linkedin]  
- **GitHub:** [github.com/juanmcastineira](https://github.com/juanmcastineira)  
- **Email:** [tu-email]
