# 🧠 Perceptrón desde Cero (Compuerta AND)

Implementación de un **Perceptrón binario** desde cero usando NumPy y visualización con Matplotlib.

Este proyecto muestra cómo un perceptrón aprende a clasificar la compuerta lógica AND y cómo evoluciona su frontera de decisión durante el entrenamiento.

---

## 🚀 ¿Qué hace este proyecto?

- Implementa un perceptrón sin usar librerías de Machine Learning.
- Entrena el modelo con la compuerta lógica AND.
- Visualiza gráficamente cómo la frontera de decisión cambia época por época.
- Muestra cómo los pesos y el bias afectan la recta de clasificación.

---

## 📊 Dataset utilizado

Compuerta lógica AND:

| x1 | x2 | salida |
|----|----|--------|
| 0  | 0  |   0    |
| 0  | 1  |   0    |
| 1  | 0  |   0    |
| 1  | 1  |   1    |

---

## 🧮 Modelo Matemático

El perceptrón calcula:
z = w1x1 + w2x2 + bias


---

## 📈 Visualización

Se genera una animación que muestra:

- Los puntos del dataset (rojo y azul).
- La evolución de la recta de decisión.
- Cómo el modelo converge hasta clasificar correctamente.

---

## ⚙️ Tecnologías utilizadas

- Python
- NumPy
- Matplotlib
- Google Colab

---

## 🎯 Objetivo del proyecto

Este proyecto tiene fines educativos:

- Comprender cómo funciona un perceptrón internamente.
- Entender el rol de los pesos y el bias.
- Visualizar geométricamente la frontera de decisión.
- Construir fundamentos sólidos antes de usar frameworks como TensorFlow o PyTorch.

---

## 🧠 Conceptos clave demostrados

- Inicialización aleatoria de pesos
- Regla de aprendizaje del perceptrón
- Clasificación lineal
- Separabilidad lineal
- Animación con Matplotlib

---

## 🔬 Limitaciones

El perceptrón solo puede resolver problemas **linealmente separables**.

Por ejemplo:
- ✔ AND → Sí converge
- ✔ OR → Sí converge
- ❌ XOR → No converge

---

## ▶️ Cómo ejecutar

1. Abrir el notebook en Google Colab.
2. Ejecutar todas las celdas.
3. Observar la animación del entrenamiento.

---

## 📌 Autor

Ingeniero Zerna Ramos Luis Fernando


Desarrollado como parte de aprendizaje en Machine Learning desde cero.
