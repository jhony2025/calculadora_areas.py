# calculadora_areas.py
calculadora de areas triangulo
#   Calculadora de Áreas de Figuras Geométricas

Este proyecto fue desarrollado como parte de la tarea sobre **Tipos de Datos, Identificadores e Implementación de Código en Python usando PyCharm y GitHub**.  
Su objetivo principal es demostrar la correcta aplicación de los fundamentos básicos de programación en Python, incluyendo el uso adecuado de tipos de datos, convenciones de nomenclatura, y buenas prácticas de codificación.

---

##  Funcionalidad del Programa

Este programa es una **calculadora de áreas** para tres figuras geométricas simples:
- Triángulo
- Rectángulo
- Círculo

El usuario elige la figura que desea calcular y proporciona los valores necesarios (base, altura, radio). El programa calcula y muestra el área correspondiente.

---

##  Tecnologías utilizadas

- Lenguaje: **Python 3**
- Entorno de desarrollo: **PyCharm**
- Control de versiones: **Git**
- Publicación del proyecto: **GitHub**

---

##  Elementos evaluados en el código

### ✔ Tipos de Datos
El código hace uso correcto de distintos tipos de datos:
- `float` para cálculos numéricos (medidas)
- `str` para la selección de opciones del usuario
- `bool` se puede adaptar para versiones extendidas (repetición o validación)

### ✔ Identificadores y Estilo
Se aplicó la convención **snake_case** en todos los nombres de variables y funciones. Los identificadores son **descriptivos** y reflejan claramente su propósito.

Ejemplo:
```python
def calcular_area_triangulo(base: float, altura: float) -> float:
