# 📦 Predicción de Recompra y CLV en Acería Guadix S.A.

Este proyecto demuestra la viabilidad de aplicar técnicas avanzadas de ciencia de datos en un entorno industrial, utilizando modelos probabilísticos de la familia **BTYD (Buy 'Til You Die)** para estimar la recurrencia de compra y el valor del cliente (CLV). El caso de estudio corresponde a **Acería Guadix S.A.**, empresa boliviana dedicada a la fabricación y venta de repuestos industriales.

## 🎯 Objetivos

1. Recolectar, limpiar y transformar datos históricos de facturación (2021–2025).
2. Construir variables clave como frecuencia, recencia, antigüedad y valor monetario.
3. Aplicar modelos Pareto/NBD y Gamma-Gamma para predecir recompras y CLV.
4. Evaluar la precisión de los modelos mediante visualizaciones y métricas.
5. Estimar la cantidad de compras futuras por cliente y su próxima fecha de compra.
6. Generar reportes estratégicos para la toma de decisiones comerciales.

## 🧠 Tecnologías utilizadas

- Python 3.10+
- [Lifetimes](https://github.com/CamDavidsonPilon/lifetimes)
- Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook
- Plotly/Dash (opcional)

## 📁 Estructura del repositorio

```

📦 raiz/
├── data/
│   ├── facturacion\_original.csv
│   └── resultados\_con\_clv.csv
├── notebooks/
│   ├── 01\_preprocesamiento\_datos.ipynb
│   ├── 02\_modelo\_pareto\_nbd.ipynb
│   ├── 03\_modelo\_gamma\_gamma.ipynb
│   └── 04\_segmentacion\_y\_reportes.ipynb
├── figures/
│   ├── histogramas/
│   ├── validacion\_modelos/
│   └── dashboards/
├── README.md
└── requirements.txt

````

## 📊 Principales resultados

- El **CLV estimado** osciló entre **Bs 1.398** y **Bs 477.914** por cliente.
- El **35.3%** de los clientes tienen **probabilidad de recompra > 0.80**.
- La media de recompras esperadas en 180 días fue de **1.04**, alcanzando hasta **5.9** en algunos casos.
- La tabla resumen por cliente incluyó métricas clave para segmentación y toma de decisiones.

## 📈 Visualizaciones generadas

- Matrices de recencia vs frecuencia.
- Histogramas de CLV y recompras futuras.
- Curvas de retención.
- Dashboards estratégicos por segmentos de cliente.

## 🚀 Cómo ejecutar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_repositorio.git
   cd nombre_repositorio
   ```

2. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Abre y ejecuta los notebooks en `notebooks/`.


## 👨‍💻 Autor

Proyecto realizado por **\[Jose Manuel Vargas Cruz]** como parte del Diplomado en Ciencia de Datos, con la colaboración de **Acería Guadix S.A.**
Fecha: **Junio 2025**


📬 Para consultas o sugerencias, contacta a: \[[201800190@est.umss.edu.bo](201800190@est.umss.edu.bo)]
