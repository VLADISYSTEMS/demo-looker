# Ejercicio 1 – Total de ventas por vendedor

## 1️⃣ Qué ver
Suma de todos los meses por cada vendedor, para identificar quién vendió más y quién menos durante el año.

## 2️⃣ Representación
- Gráfico de barras verticales con todas las barras azules.  
- Cada barra representa el total anual de ventas de un vendedor.

## 3️⃣ Resolución – Paso a paso técnico
- Preparar fuente de datos en Sheets: columna A = Vendedores, columnas B-J = Meses (Ene-Sep).  
- Subir a Looker Studio, conectar Google Sheets.  
- Crear filtro: excluir vendedores vacíos.  
- Métrica calculada: Total Ventas = SUM(Ene+Feb+…+Sep)  
- Configurar gráfico: barras verticales, dimensión = Vendedor, métrica = Total Ventas, color azul.

## 4️⃣ Interpretación
- Cada barra = total anual de un vendedor.  
- La barra más alta indica quién vendió más; la más baja, quién menos.  
- Permite identificar los vendedores más y menos productivos.