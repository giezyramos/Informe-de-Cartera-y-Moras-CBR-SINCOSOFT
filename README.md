# 📊 Informe de Cartera CBR - Power BI

Este proyecto presenta un reporte en Power BI para analizar la cartera vigente, vencida y recuperaciones en base al comportamiento de pagos. Está orientado al análisis financiero de morosidad y flujo de cartera.

## 📌 Características del informe

- Seguimiento de cartera por antigüedad de mora
- Segmentación por clientes, fechas, regiones o estatus
- Visualización de KPIs: total adeudado, monto recuperado, % de mora
- Análisis comparativo por periodos y evolución

## 🖼 Captura del dashboard

![relacion de tablas - informe de cartera y moras](https://github.com/user-attachments/assets/b8539406-f907-4c9f-bb01-b7152e37d720)

🔀 FLUJO GENERAL DE DATOS
                ADI_LTM Proyectos
                      │
                      ▼
              ADI_LTM Inventarios
                  │         │
                  ▼         ▼
       ADI_LTM Venta   ADI_LTM Acuerdos_Pago
            │
            ▼
  ADI_LTM Empresas ── MonedaPorProyecto
            │
            ▼
  ADI_LTM ListaDePrecios

+ Medidas DAX en All Measures que agrupan y calculan métricas sobre todas las anteriores.


## ⚙️ Tecnología usada

- Power BI Desktop
- Power Query
- DAX

## 👤 Autor

Génesis R.
