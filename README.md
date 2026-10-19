# UT1: Convergencia IT/OT y Prototipado IoT - Invernadero Agrícola (Zamora / Soria)

## 1. Justificación de la Empresa Cliente
* **Sector:** Agricultura intensiva e hidropónica (Castilla y León).
* **Necesidad:** Los invernaderos de alto rendimiento en zonas de Zamora o Soria sufren fluctuaciones térmicas extremas y radiación solar excesiva. Esto provoca estrés térmico y cierre estomático en las plantas, arruinando la producción. 
* **Solución:** Automatizar la monitorización del microclima interno mediante una placa IoT (Micro:bit) para activar sistemas de ventilación y sombreado, conectando el entorno físico de planta con la analítica de datos en la nube.

---

## 2. Tabla de Clasificación IT/OT

| Componente del Sistema | Entorno (IT / OT) | Descripción / Función |
| :--- | :---: | :--- |
| **Sensores de Luz (LEDs) y Temperatura** | **OT** | Captura directa de los parámetros climáticos físicos del invernadero. |
| **Actuadores (Ventanas cenitales y Mallas)** | **OT** | Dispositivos mecánicos de campo que ejecutan el sombreo y la ventilación. |
| **Placa Micro:bit (Prototipo IoT)** | **Frontera / Híbrido** | Recoge los datos físicos y toma decisiones lógicas a nivel local. |
| **Base de Datos en la Nube / Servidor Web** | **IT** | Almacenamiento centralizado y procesamiento de grandes volúmenes de datos. |
| **Cuadros de Mando (Big Data / Gráficos)** | **IT** | Visualización ejecutiva para que el agricultor optimice el riego y fertilización. |

---

## 3. Definición de KPIs (Indicadores Clave de Rendimiento)
1. **KPI 1: Tasa de Exposición a Estés Térmico (%)**  
   * *Métrica:* Porcentaje de tiempo diario en el que la temperatura supera los límites óptimos del cultivo. Permite evaluar la eficacia de la ventilación automática.
2. **KPI 2: Eficiencia de Sombreo y Radiación (lux/h)**  
   * *Métrica:* Correlación entre las horas de luz incidente detectadas y la activación de las mallas de sombreo, evitando el cierre estomático.
3. **KPI 3: Ratio de Optimización de Riego y Cosecha**  
   * *Métrica:* Rendimiento final de la cosecha comparado con el histórico de temperatura promedio almacenado en la nube.
