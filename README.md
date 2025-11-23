# 🛳️ Predicción de Supervivencia – Titanic (Kaggle)

Este proyecto analiza los datos del naufragio del Titanic y desarrolla un modelo de Machine Learning para predecir la probabilidad de supervivencia de los pasajeros, utilizando el dataset oficial del reto **Titanic: Machine Learning from Disaster** de Kaggle.

## 🎯 Objetivo

* Analizar y comprender las variables que influyen en la supervivencia.
* Limpiar y preparar los datos para el entrenamiento del modelo.
* Entrenar uno o varios modelos predictivos.
* Generar un archivo final con predicciones compatible con Kaggle.

## 📊 Descripción del Dataset

Las principales variables incluidas en el dataset son:

* **Pclass** – Clase del pasajero
* **Name** – Nombre
* **Sex** – Sexo
* **Age** – Edad
* **SibSp / Parch** – Familiares a bordo
* **Cabin** – Número de camarote
* **Embarked** – Puerto de embarque
* **Survived** – Variable objetivo (solo disponible en los datos de entrenamiento)

## 🧠 Modelos Utilizados

Se probaron diversos modelos durante el desarrollo del proyecto, tales como:

* Regresión Logística
* Random Forest
* Support Vector Machine
* Gradient Boosting

El modelo con mejor desempeño según la validación interna fue: **[indicar modelo final]**.

## ⚙️ Instalación

1️⃣ Clonar el repositorio:

```
git clone https://github.com/usuario/titanic-project.git
cd titanic-project
```

2️⃣ Crear entorno virtual (opcional):

```
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

3️⃣ Instalar dependencias:

```
pip install -r requirements.txt
```

## ▶️ Ejecución

### Entrenar el modelo:

```
python model_training.py
```

### Generar archivo de predicción:

```
python model_training.py --export
```

## 📈 Resultados

* Score en Kaggle: **XX.XXX**
* Accuracy local: **XX%**

*(Reemplazar con tus resultados reales.)*

## 📌 Tecnologías

* Python 3.x
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib / Seaborn
* Jupyter Notebook

## 🚀 Mejoras Futuras

* Optimización de hiperparámetros (GridSearch, Optuna).
* Nuevas variables derivadas (feature engineering).
* Evaluación con redes neuronales.
* Creación de un dashboard interactivo.

## 👤 Autor

**Tu nombre aquí**
📧 [email@example.com](mailto:email@example.com)
🔗 [https://www.linkedin.com/in/tu-perfil/](https://www.linkedin.com/in/tu-perfil/)
