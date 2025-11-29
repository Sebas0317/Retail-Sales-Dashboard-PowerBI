# Retail Fashion Performance Dashboard – Power BI  
**Portafolio Profesional – Analista de Datos Junior**

**Autor:** Juan Sebastián Sandoval  
**Fecha:** Noviembre 2025  
**LinkedIn:** https://linkedin.com/in/juan-sebastian-sandoval-686264292  
**GitHub:** https://github.com/Sebas0317  

## Descripción del Proyecto
Dashboard interactivo desarrollado en Power BI para analizar el desempeño de una cadena retail de moda en Portugal (2020–2024).  
Los datos se obtuvieron del dataset público **Messy Retail Data** de Kaggle.

El reporte permite explorar métricas de revenue, profit, comportamiento del cliente y desempeño operativo, con filtros por año, región, categoría, temporada, género y proveedor.

## Dataset
**Fuente:** [Kaggle – Retail Fashion Data](https://www.kaggle.com/datasets/vanpatangan/retail-fashion-data)

Modelo compuesto por cuatro tablas principales:

- **product_data:** product_id, category, color, size, season, supplier, cost_price, list_price 
- **sales_data:** transaction_id, date, product_id, store_id, customer_id, quantity, discount, returned 
- **store_data:** store_id, store_name, region, store_size_m2
- **customer_data:** customer_id, age, gender, city, email

## Preguntas de Negocio Abordadas
1. ¿Qué regiones y canales generan mayor profit?  
2. ¿Qué categorías y temporadas impulsan las ventas?  
3. ¿Existen diferencias relevantes entre géneros?  
4. ¿Hay dependencia de algún proveedor?  
5. ¿Cómo evoluciona el rendimiento año a año y mes a mes?

## Principales Insights

### Resumen Ejecutivo
- **Revenue total:** 537 M  
- **Profit:** 53.6 M (margen ~10%)  
- **Unidades vendidas:** 125 K  
- **Clientes activos:** ~1 K  
  *(el dashboard original mostraba 21 K debido a un error de conteo)*

### Por Región
- Porto (14 M) y Algarve (12 M) son las regiones con mayor profit.  
- Canal **Online** y región **Coimbra** muestran menor rentabilidad.  
  El canal online genera buen revenue, pero con márgenes más bajos.

### Categorías & Temporadas
- Portafolio equilibrado: categorías y estaciones generan entre **130 M y 139 M**.  
- No hay dependencia marcada de una categoría o temporada específica.

### Género
Las ventas están muy balanceadas:  
- Other: 176 M  
- Female: 172 M  
- Male: 166 M  

El género no es un factor determinante en el comportamiento de compra.

### Proveedores
- Cuatro proveedores principales con ingresos entre 132 M y 136 M.  
- Supplier A es el líder (136 M).  
Bajo riesgo de dependencia del supply chain.

### Tallas
Demanda casi uniforme (24.6 K – 25.4 K unidades).  
Esto facilita la planificación y reduce inventario sobrante.

### Tendencias Temporales
- **2023** fue el año más rentable.  
- **2024** inicia con una ligera caída en profit frente a 2023.  
- Meses fuertes: **junio, julio y septiembre**.  
- Meses débiles: **enero y marzo**.

## Conclusiones & Recomendaciones
1. Negocio estable y diversificado (categorías, proveedores, tallas).  
2. Principal oportunidad: mejorar márgenes en el canal Online.  
3. Potencial de crecimiento en la región Coimbra.  
4. Monitorear el inicio de 2024 para evitar una caída sostenida.

## Estructura del Dashboard
- **Página 1:** Visión General — KPIs, mapa, composición y tendencias.  
- **Página 2:** Análisis Detallado — regiones, tallas, proveedores.  
- **Página 3:** Detalle — catálogo completo y transacciones.

---

¡Gracias por visitar mi proyecto!
