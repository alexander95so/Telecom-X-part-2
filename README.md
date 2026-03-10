<h1 align="center" style="color:#1F4E79;font-family:Trebuchet MS;">
📡 Telecom X Challenge – Predicción de Cancelación de Clientes (Churn)
</h1>

<p align="center" style="font-size:16px;font-family:Georgia;">
Proyecto de Ciencia de Datos enfocado en <b>análisis predictivo de churn</b> en una empresa de telecomunicaciones.
</p>

---

<h2 style="color:#2E75B6;font-family:Verdana;">📌 Descripción del Proyecto</h2>

<p style="font-family:Georgia;font-size:16px;">
Este proyecto forma parte del <b>Telecom X Challenge – Parte 2</b>, centrado en el análisis y predicción de la cancelación de clientes (<b>Churn</b>) en una empresa de telecomunicaciones.
</p>

<p style="font-family:Georgia;font-size:16px;">
El objetivo principal es desarrollar <b>modelos predictivos de Machine Learning</b> capaces de identificar qué clientes tienen mayor probabilidad de cancelar sus servicios, permitiendo a la empresa anticiparse al problema y aplicar estrategias de retención.
</p>

---

<h2 style="color:#1C6E8C;font-family:Verdana;">🎯 Objetivos del Proyecto</h2>

<ul style="font-family:Georgia;font-size:15px;">
<li>Realizar preprocesamiento y limpieza de los datos.</li>
<li>Explorar patrones mediante <b>Análisis Exploratorio de Datos (EDA)</b>.</li>
<li>Entrenar modelos de <b>Machine Learning</b> para predecir churn.</li>
<li>Evaluar el rendimiento de los modelos mediante métricas.</li>
<li>Identificar los factores que influyen en la cancelación.</li>
<li>Proponer estrategias de retención basadas en datos.</li>
</ul>

---

<h2 style="color:#6A329F;font-family:Verdana;">🧹 Preprocesamiento y Análisis Exploratorio</h2>

<ul style="font-family:Georgia;">
<li>Eliminación de columnas irrelevantes (IDs).</li>
<li>Transformación de variables categóricas mediante <b>One-Hot Encoding</b>.</li>
<li>Análisis del desbalance de clases en la variable objetivo.</li>
<li>Visualización de datos con gráficos como:
<ul>
<li>Boxplots</li>
<li>Scatterplots</li>
<li>Matrices de correlación</li>
</ul>
</li>
</ul>

---

<h2 style="color:#38761D;font-family:Verdana;">🤖 Entrenamiento de Modelos</h2>

<p style="font-family:Georgia;">
Los datos fueron divididos en conjuntos de entrenamiento y prueba utilizando una proporción de <b>80/20</b>.
</p>

<h3 style="color:#6AA84F;">Modelos utilizados</h3>

<ul style="font-family:Georgia;">
<li><b>Regresión Logística</b> (requiere normalización de variables)</li>
<li><b>Random Forest</b> (no requiere normalización)</li>
</ul>

<h3 style="color:#6AA84F;">Métricas de evaluación</h3>

<ul style="font-family:Georgia;">
<li>Accuracy</li>
<li>Precision</li>
<li>Recall</li>
<li>F1-score</li>
<li>Matriz de confusión</li>
</ul>

---

<h2 style="color:#B45F06;font-family:Verdana;">📊 Resultados Principales</h2>

<h3 style="color:#E69138;">Rendimiento de Modelos</h3>

<ul style="font-family:Georgia;">
<li><b>Regresión Logística</b><br>
Accuracy: 100%<br>
Precision: 100%<br>
Recall: 100%<br>
F1-score: 100%<br>
(Posible sobreajuste, se recomienda validación cruzada).
</li>

<br>

<li><b>Random Forest</b><br>
Accuracy ≈ 99.6%<br>
Precision = 100%<br>
Recall ≈ 98.6%<br>
F1-score ≈ 99.3%<br>
Modelo más robusto y realista para producción.
</li>
</ul>

---

<h2 style="color:#741B47;font-family:Verdana;">🔎 Factores que Aumentan la Probabilidad de Churn</h2>

<ul style="font-family:Georgia;">
<li>Cargos mensuales elevados.</li>
<li>Método de pago: <b>Electronic Check</b>.</li>
<li>Facturación electrónica (<b>Paperless Billing</b>).</li>
<li>Servicio de Internet por <b>Fiber Optic</b>.</li>
<li>Clientes <b>Senior Citizen</b>.</li>
</ul>

---

<h2 style="color:#274E13;font-family:Verdana;">📉 Factores que Reducen el Churn</h2>

<ul style="font-family:Georgia;">
<li>Mayor antigüedad del cliente (<b>tenure</b>).</li>
<li>Contratos de <b>1 o 2 años</b>.</li>
<li>Servicios adicionales como <b>OnlineSecurity</b> y <b>TechSupport</b>.</li>
</ul>

---

<h2 style="color:#0B5394;font-family:Verdana;">💡 Estrategias de Retención</h2>

<ul style="font-family:Georgia;">
<li>Incentivar contratos de largo plazo mediante bonos o meses gratuitos.</li>
<li>Ofrecer descuentos o paquetes para clientes con cargos mensuales altos.</li>
<li>Promover pagos automáticos en lugar de <b>Electronic Check</b>.</li>
<li>Fomentar servicios adicionales como <b>OnlineSecurity</b> y <b>TechSupport</b>.</li>
<li>Mejorar la experiencia de facturación electrónica y comunicación con clientes.</li>
</ul>

---

<h2 style="color:#3D85C6;font-family:Verdana;">🛠 Tecnologías Utilizadas</h2>

<ul style="font-family:Georgia;">
<li>Python 3</li>
<li>Pandas</li>
<li>Numpy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
<li>Scikit-learn</li>
</ul>

---

<h2 align="center" style="color:#134F5C;font-family:Trebuchet MS;">
📈 Conclusión
</h2>

<p style="font-family:Georgia;font-size:16px;text-align:center;">
El análisis confirmó que los factores más influyentes en la cancelación de clientes están relacionados con <b>precio, tipo de contrato, método de pago, servicios adicionales y antigüedad del cliente</b>.
</p>

<p style="font-family:Georgia;font-size:16px;text-align:center;">
Los modelos predictivos mostraron un rendimiento excelente, siendo <b>Random Forest</b> el modelo más confiable para implementación en producción.
</p>

---

<p align="center" style="font-family:Georgia;font-size:14px;">
Proyecto desarrollado como parte del <b>Challenge de Ciencia de Datos – Telecom X (Parte 2)</b>.
</p>
