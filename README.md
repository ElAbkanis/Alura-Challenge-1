# 📊 Proyecto Alura Store Latam

## 🎯 Propósito del análisis
Este proyecto tiene como objetivo analizar el desempeño de cuatro tiendas de la cadena **Alura Store** en Latinoamérica.  
Se estudian métricas clave como:
- Facturación total y ganancia neta.
- Ventas por categoría de producto.
- Calificación promedio de clientes.
- Ranking de productos más y menos vendidos.
- Distribución geográfica de las compras.

El análisis busca identificar patrones de consumo, productos más rentables y oportunidades de mejora en la operación.

---

## 📂 Estructura del proyecto
AluraStoreLatam/
│
├── base-de-datos-challenge1-latam/   # Archivos CSV con datos de cada tienda
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
│
├── AluraStoreLatam.ipynb             # Notebook principal con el análisis

---

## 📈 Ejemplos de gráficos e insights

### Ventas Totales por Tienda
Se observa que **Tienda 1** lidera en ventas con más de 1.15 mil millones, mientras que **Tienda 4** presenta el menor volumen con 1.03 mil millones.

### Ventas por Categoría
En todas las tiendas, la categoría **Electrónicos** domina las ventas, seguida de **Electrodomésticos** y **Muebles**.

### Calificaciones Promedio
Las tiendas mantienen un nivel de satisfacción alto, con promedios entre **3.97 y 4.05** sobre 5.

### Productos más vendidos
Ejemplo en Tienda 1:
- TV LED UHD 4K (142M)
- Refrigerador (112M)
- iPhone 15 (97M)

### Productos menos vendidos
Ejemplo en Tienda 1:
- Ajedrez de madera (1.4M)
- Set de vasos (1.3M)
- Cubo mágico 8x8 (0.69M)

---

## ⚙️ Instrucciones de ejecución

1. Clonar o descargar este repositorio.
2. Instalar dependencias necesarias:
   ```bash
   pip install pandas matplotlib seaborn numpy
