# Curso de Simulación en Python
Este curso introduce los fundamentos de la Simulación de Eventos Discretos (DES) y su implementación en Python. Se cubren desde los conceptos básicos hasta la construcción de modelos completos utilizando librerías como SimPy, NumPy, pandas, matplotlib y scipy.stats.

Incluye también técnicas de análisis de entrada para modelar datos reales, y métodos de Simulación Monte Carlo, aplicables a problemas de incertidumbre y optimización.
📂 Contenido del curso
Módulo 1: Introducción a la Simulación de Eventos Discretos

Conceptos básicos: sistemas, entidades, eventos, reloj de simulación.

Ejemplos de aplicaciones (call centers, hospitales, fábricas, transporte).

Primer ejemplo: simulación de una cola simple en Python.

Módulo 2: Fundamentos en Python para Simulación

Repaso de estructuras de datos en Python.

Generación de números aleatorios con numpy.random.

Distribuciones de probabilidad comunes en simulación.

Módulo 3: Análisis de Entrada (Input Analysis)

Pasos a seguir en el análisis de entrada:

Recolección de datos: obtención de datos históricos del sistema.

Identificación de distribuciones de probabilidad adecuadas:

Histogramas.

QQ-plot, PP-plot.

Estimación de parámetros: métodos de máxima verosimilitud, método de momentos.

Pruebas de bondad de ajuste:

Prueba Ji-cuadrada.

Prueba Kolmogorov-Smirnov.

Comparación entre distribuciones discretas y continuas.

Ejemplo en Python: ajustar datos de tiempos de servicio a distribuciones usando scipy.stats.

Módulo 4: Modelado con SimPy

Introducción a SimPy.

Procesos, recursos y entorno de simulación.

Ejemplo: modelo de una fila de un banco con un cajero.

Módulo 5: Simulación de Sistemas de Colas

Teoría de colas vs simulación.

Colas M/M/1, M/M/c y colas con capacidad limitada.

Ejemplo: sistema de atención con múltiples servidores.

Módulo 6: Simulación de Monte Carlo

Concepto de Monte Carlo.

Diferencia con simulación de eventos discretos.

Estimación de probabilidades e integrales.

Aplicaciones:

Estimación de π.

Riesgo financiero.

Modelos de inventario.

Ejemplo en Python: simulación Monte Carlo de un problema de inversión.

Módulo 7: Modelos de Manufactura y Producción

Líneas de producción y cuellos de botella.

Simulación de inventarios.

Ejemplo: taller de reparación con llegadas aleatorias.

Módulo 8: Recolección y Análisis de Resultados

Estadísticas de desempeño: tiempo en cola, utilización, throughput.

Visualización con matplotlib y pandas.

Validación y verificación de modelos.

Módulo 9: Proyecto Final

Desarrollo de un modelo de simulación aplicado:

🏥 Hospital.

🚍 Transporte público.

🏭 Planta de producción.

📦 Logística y distribución.

📦 Requisitos del curso
pip install simpy numpy pandas matplotlib scipy

Simulacion-Eventos-Discretos-Python/
│
├── 📄 README.md                   -> Descripción general del curso
├── 📄 requirements.txt             -> Dependencias (simpy, numpy, pandas, matplotlib, scipy)
├── 📄 LICENSE                      -> Licencia del proyecto
│
├── 📁 notebooks/                   -> Notebooks con teoría y ejercicios
│   ├── 01_Introduccion.ipynb
│   ├── 02_Fundamentos_Python.ipynb
│   ├── 03_Analisis_Entrada.ipynb
│   ├── 04_Modelado_SimPy.ipynb
│   ├── 05_Simulacion_Colas.ipynb
│   ├── 06_Simulacion_MonteCarlo.ipynb
│   ├── 07_Modelos_Produccion.ipynb
│   ├── 08_Analisis_Resultados.ipynb
│   └── 09_Proyecto_Final.ipynb
│
├── 📁 data/                        -> Datos para análisis y simulación
│   ├── tiempos_servicio.csv
│   ├── llegadas_clientes.csv
│   └── inventario_hist.csv
│
├── 📁 scripts/                     -> Funciones y librerías en Python
│   ├── utils_random.py             -> Generación de números aleatorios y distribuciones
│   ├── input_analysis.py           -> Ajuste de distribuciones y pruebas de bondad de ajuste
│   ├── simpy_models.py             -> Modelos básicos en SimPy
│   ├── montecarlo.py               -> Funciones para simulación Monte Carlo
│   └── resultados.py               -> Recolección y análisis de resultados
│
├── 📁 projects/                    -> Proyectos aplicados
│   ├── hospital_simulacion/
│   │   ├── hospital.ipynb
│   │   └── README.md
│   ├── transporte_publico/
│   │   ├── transporte.ipynb
│   │   └── README.md
│   ├── manufactura/
│   │   ├── produccion.ipynb
│   │   └── README.md
│   └── logistica/
│       ├── logistica.ipynb
│       └── README.md
│
├── 📁 docs/                        -> Documentación del curso
│   ├── syllabus.md
│   ├── bibliografia.md
│   └── presentaciones/
│       ├── modulo1_intro.pdf
│       └── modulo2_input.pdf
│
└── 📁 tests/                       -> Casos de prueba de funciones
    ├── test_random.py
    ├── test_input_analysis.py
    └── test_montecarlo.py
