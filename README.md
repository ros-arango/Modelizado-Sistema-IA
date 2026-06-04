# Materia: Modelizado de Sistemas de IA 🤖

Este repositorio contiene los trabajos prácticos desarrollados durante la cursada de la materia **Modelizado de Sistemas de IA**. El objetivo es documentar el avance y la implementación de modelos de inteligencia artificial.

---

## 📁 Trabajos Prácticos Entregados

### TP 1: Sistema Experto - Empresa Constructora
* **Archivo:** [P1_Sistemas_Expertos.ipynb](./P1_Sistemas_Expertos.ipynb)
* **Descripción:** Desarrollo de un sistema experto para automatizar la evaluación de riesgos y la planificación de maquinaria en una empresa de construcción.
* **Estado:** ✅ Completado

### TP 2: Optimización de Cronograma con Algoritmos Genéticos
* **Archivo:** [P2_Algoritmos_Genéticos.ipynb](./P2_Algoritmos_Genéticos.ipynb)
* **Descripción:** Implementación de un modelo de computación evolutiva para resolver el problema de optimización de recursos y tiempos (Makespan) en una obra civil.
* **Desafío:** Planificar 10 tareas críticas respetando un límite estricto de 10 operarios simultáneos.
* **Resultados:** * El algoritmo logró converger en un cronograma óptimo de **18 días**.
    * Se aplicó una **Función de Aptitud** con penalización drástica para asegurar que ningún día superara el máximo de operarios permitido.
    * Se utilizó **Selección por Torneo** y **Elitismo** para garantizar la supervivencia de las mejores planificaciones.
* **Estado:** ✅ Completado

### TP 3: Clasificación de Riesgo Crediticio con Perceptrón
* **Archivo:** [P3_Preceptron_simple.ipynb](./P3_Preceptron_simple.ipynb)
* **Descripción:** Implementación de una neurona artificial (Perceptrón Simple) para la aprobación automatizada de créditos basada en el comportamiento financiero de los clientes.
* **Desafío:** Encontrar la frontera de decisión óptima para separar clientes de "Bajo Riesgo" y "Alto Riesgo" en un espacio bidimensional (Puntaje Crediticio vs. Ratio de Ahorro).
* **Resultados:**
    * El modelo alcanzó un **100% de precisión (Accuracy)**, demostrando que los datos eran linealmente separables.
    * Se utilizó la **Función de Activación Sigmoide** para interpretar la salida como una probabilidad de aprobación entre 0 y 1.
    * Se compararon técnicas de **Regularización L1 (Lasso)** y **L2 (Ridge)**, observando cómo L1 simplifica el modelo mediante la anulación de pesos irrelevantes (Sparsity).
* **Estado:** ✅ Completado
### TP 4: Clasificación de Ropa con Redes Neuronales Multicapa (MLP)
* **Archivo:** [P4_RRNN_multicapa.ipynb](./P4_RRNN_multicapa.ipynb)
* **Descripción:** Diseño de una red neuronal profunda para clasificar el dataset Fashion MNIST (28x28 píxeles).
* **Arquitectura:**
    * **Entrada:** Flatten (784 señales).
    * **Ocultas:** Dos capas densas (128 y 64 neuronas) con activación **ReLU** para detectar patrones complejos.
    * **Salida:** 10 neuronas con **Softmax** para distribución de probabilidad multiclase.
* **Resultados:** 
    * **Precisión en Test:** **87.76%**.
    * **Optimización:** Uso de **Early Stopping** (patience=5) que detuvo el entrenamiento en la época 17, restaurando los mejores pesos de la época 12 para evitar el sobreajuste (overfitting).
* **Estado:** ✅ Completado

### TP5: PREDICCION 
* **Archivo:** [P5_PLANTILLA_prediccion.ipynb](./P5_PLANTILLA_prediccion.ipynb)
* **Descripción:**  Entrenamos un modelo lineal simple como punto de referencia
* **Estado:** ✅ Completado
---

## 🔧 Tecnologías y Herramientas
* **Lenguaje:** Python 3.x
* **Entorno:** Jupyter Notebook / Google Colab
* **Librerías:** Pandas, NumPy.

* **Experta / Python-Constraint:** Para sistemas expertos y lógica simbólica.
    * **PyGAD:** Para la implementación del motor de Algoritmos Genéticos. 
    * **Matplotlib:** Para la visualización de la curva de convergencia (Fitness vs. Generation).

* ** TensorFlow / Keras: Para la construcción y entrenamiento de la arquitectura de la red neuronal.

* **Scikit-Learn: Para la generación y preparación del dataset sintético.
* **Matplotlib: Para la visualización de las prendas clasificadas y las curvas de aprendizaje
## 👤 Datos de la Alumna
* **Nombre:** Rosmery Ramirez
