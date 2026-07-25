# PachaTech: Análisis y Simulación de Riego Inteligente

**Trabajo Final - Curso de Dinámica de Sistemas**
Universidad Nacional Federico Villarreal

---

## Descripción del Proyecto
Este repositorio contiene el modelamiento, simulación y análisis dinámico del sistema **PachaTech**, una solución de riego automatizado basada en Edge Computing (ATmega328P) y arquitectura MVVM móvil. 

El proyecto aborda la ineficiencia hídrica y el estrés vegetal en la agricultura urbana aplicando **Dinámica de Sistemas**. Se analiza cómo el "Agua en el Sustrato" (Stock) interactúa con la "Tasa de Riego" (Flujo de entrada) y la "Evapotranspiración" (Flujo de salida), rompiendo el esquema lineal del riego tradicional mediante bucles de retroalimentación en tiempo real.

## Estructura del Repositorio

El proyecto está organizado según los entregables requeridos para el análisis sistémico:

* **`informe/`**: Contiene el `informe-final.pdf` con el análisis detallado de los 17 puntos del marco teórico y sistémico.
* **`presentacion/`**: Diapositivas (`exposicion-final.pptx`) para la sustentación.
* **`modelos/`**: Diagramas causales, diagramas stock-flow y los archivos base de simulación (Vensim / Python).
* **`datos/`**: Historiales en formato CSV y matrices de supuestos (`supuestos_modelo.xlsx`).
* **`resultados/`**: Gráficas Behavior Over Time (BOT) comparando el escenario base, optimista, pesimista y con nuestra política de intervención.
* **`matrices/`**: Archivos Excel documentando variables, bucles, escenarios y validación estructural.
* **`evidencias/`**: Capturas del modelo validado.

## Tecnologías Analizadas
* **Hardware:** Microcontrolador ATmega328P, Sensores de humedad, Relé (Actuadores).
* **Software Móvil:** Kotlin, Jetpack Compose, Arquitectura MVVM, SQLite/SharedPreferences.
* **Simulación Sistémica:** Vensim / Python.

## Equipo Nª5
* **SALCEDO MEGO ARNOLD ALONZO**
* **TOCCAS ROJAS LUIS FERNANDO**
* **ZAPANA PORRAS JOHAN JAIRO**
* **TORO SUYLLON GABRIEL DAVID**

---
*Proyecto desarrollado para demostrar la aplicación del pensamiento sistémico en soluciones tecnológicas de la agricultura urbana.*
