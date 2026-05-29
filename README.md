
# 📊 **Curiosidades Estadísticas: Un Viaje para Todos**

> *"La estadística es la ciencia que nos permite cruzar la puerta del cine sabiendo que la película puede ser tan realmente mala como buena."*
> — **Lucho Ferrer** 👨‍💻

---

## 🌟 **¿Por qué este repositorio?**

La estadística no es solo para expertos. Aquí exploramos cómo los números, gráficos y análisis pueden ayudarnos a tomar decisiones **más inteligentes y asertivas** en la vida cotidiana. Desde la corrección de Bessel hasta el uso de tablas dinámicas, este espacio está diseñado para mostrarte la diversidad de resultados que la estadística puede ofrecer.

**Objetivo:** Demostrar que la estadística es accesible, útil y, sobre todo, **divertida**.

---

## 🧑‍🚀 **1. Corrección de Bessel: ¿Qué es y por qué importa?**

### 📌 **Explicación para Pollitos (Principiantes)**
La **corrección de Bessel** es un ajuste que se aplica al calcular la **varianza** y la **desviación estándar** de una muestra de datos. ¿Por qué? Porque cuando trabajamos con una **muestra** (un subconjunto de datos) y no con toda la población, queremos que nuestra estimación sea lo más precisa posible.

- **Varianza:** Mide qué tan dispersos están los datos respecto a la media.
- **Desviación estándar:** Es la raíz cuadrada de la varianza y nos dice cuánto varían los datos en promedio.

#### 🔍 **¿Por qué se usa?**
Cuando calculas la varianza de una muestra, si no aplicas la corrección de Bessel, subestimarás la varianza real de la población. La corrección consiste en dividir por **n-1** (donde *n* es el tamaño de la muestra) en lugar de **n**.

**Ejemplo práctico:**
Imagina que tienes las edades de 5 personas: [20, 22, 24, 26, 28].
- **Sin corrección:** Divides por 5.
- **Con corrección:** Divides por 4 (5-1).

Esto hace que tu estimación sea más precisa para la población completa.

---

### 📊 **Fórmula Matemática**

La varianza muestral (*s²*) se calcula como:

\ 
 s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1} \ 

Donde:
- **x_i**: Cada valor en la muestra.
- **\bar{x}**: Media de la muestra.
- **n**: Tamaño de la muestra.

---

### 💡 **¿Dónde se usa?**
- **Encuestas:** Para estimar la variabilidad de opiniones en una población.
- **Control de calidad:** Para evaluar la consistencia de productos en una línea de producción.
- **Ciencias sociales:** Para analizar datos de estudios con muestras limitadas.

---

## 📂 **Recursos Disponibles en el Repositorio**

| **Archivo**               | **Descripción**                                                                 | **Formato**       |
|---------------------------|---------------------------------------------------------------------------------|-------------------|
| [PivotTable.ipynb](https://github.com/lefcgis/StatisticsCuriosities/blob/main/PivotTable.ipynb) | Ejemplo de tablas dinámicas para análisis exploratorio de datos.               | Jupyter Notebook  |
| [StatisticsCuriosities.ipynb](https://github.com/lefcgis/StatisticsCuriosities/blob/main/StatisticsCuriosities.ipynb) | Análisis estadísticos con ejemplos prácticos.                                  | Jupyter Notebook  |
| [people.csv](https://github.com/lefcgis/StatisticsCuriosities/blob/main/people.csv) | Dataset de ejemplo para practicar con tablas dinámicas.                        | CSV               |
| [RECH0_2.csv](https://github.com/lefcgis/StatisticsCuriosities/blob/main/RECH0_2.csv) | Dataset adicional para análisis estadístico.                                   | CSV               |
| [pivottablejs.html](https://github.com/lefcgis/StatisticsCuriosities/blob/main/pivottablejs.html) | Visualización interactiva de tablas dinámicas.                                  | HTML              |

---

## 🎯 **¿Cómo Empezar?**

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/lefcgis/StatisticsCuriosities.git
   ```

2. **Abre los notebooks en Jupyter:**
   - Necesitas tener instalado [Jupyter Notebook](https://jupyter.org/install).
   - Ejecuta:
     ```bash
     jupyter notebook
     ```

3. **Explora los datasets:**
   - Usa los archivos CSV para practicar con tus propios análisis.

---

## 📚 **Conceptos Clave para Pollitos**

### 🔹 **Media (Promedio)**
Es el valor que obtienes al sumar todos los datos y dividir entre el número de datos.
**Ejemplo:** [10, 20, 30] → (10+20+30)/3 = **20**.

### 🔹 **Mediana**
Es el valor del medio cuando los datos están ordenados.
**Ejemplo:** [10, **20**, 30] → **20**.

### 🔹 **Moda**
Es el valor que más se repite.
**Ejemplo:** [10, 20, **20**, 30] → **20**.

### 🔹 **Desviación Estándar**
Indica cuánto se alejan los datos de la media. **A mayor desviación, más dispersos están los datos.**

---

## 🚀 **Próximos Temas**
- **Tablas dinámicas:** Cómo resumir y analizar grandes conjuntos de datos.
- **Visualización de datos:** Gráficos que cuentan historias.
- **Pruebas de hipótesis:** Cómo validar supuestos con estadística.

---

## 🤝 **Contribuye**
¿Tienes ideas o quieres añadir ejemplos? ¡Las contribuciones son bienvenidas!
1. Haz un *fork* del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-característica`).
3. Haz *commit* de tus cambios (`git commit -m 'Añade explicación para pollitos'`).
4. Envía un *pull request*.

---

## 📜 **Licencia**
Este proyecto está bajo la licencia **Apache-2.0**. Puedes usar, modificar y distribuir el código libremente.

---

## 📞 **Contacto**
¿Preguntas o sugerencias?
- **Autor:** Lucho Ferrer
- **GitHub:** [lefcgis](https://github.com/lefcgis)

---

> *"La estadística es el arte de mentir con números... pero también de descubrir la verdad oculta en ellos."* 😉
