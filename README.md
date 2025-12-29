===========================================================================
     PORTAFOLIO DE ANÁLISIS NUMÉRICO - UTN FRSF - CURSADA 2025
===========================================================================

FACULTAD: Facultad Regional Santa Fe (UTN)
CÁTEDRA: Análisis Numérico

---------------------------------------------------------------------------
1. DESCRIPCIÓN GENERAL
---------------------------------------------------------------------------
Este repositorio contiene la resolución integral de los Trabajos Prácticos 
de la materia. Se abordan problemas complejos de ingeniería mediante la 
implementación de algoritmos numéricos en Python y C++, con un fuerte foco 
en el análisis de convergencia, estabilidad y error computacional.

---------------------------------------------------------------------------
2. RESUMEN DE LOS TRABAJOS PRÁCTICOS
---------------------------------------------------------------------------

TP 1: ANÁLISIS DE SEÑALES Y SISTEMAS
- Enfoque: Resolución de sistemas de ecuaciones y búsqueda de raíces.
- Herramientas: Implementación de métodos iterativos y directos.

TP 2: ESTEGANOGRAFÍA (LSB Y TF2D)
- Temas: Procesamiento de imágenes en el dominio espacial y de frecuencia.
- Implementación: Ocultamiento de mensajes mediante bit menos significativo 
  (LSB) y modificación de paridad en coeficientes de la TF2D (parámetro delta).
- Conclusión: Análisis de pérdida de información por error de redondeo.

TP 3: BÚSQUEDA DE RAÍCES EN FUNCIONES NO LINEALES
- Problema: Cálculo del volumen real de CO2 usando la ecuación de Van der Waals.
- Algoritmos: Desarrollo de un método basado en la expansión de Taylor hasta 
  la 2da derivada (Newton de orden superior) combinado con Bisección para 
  garantizar robustez.
- Análisis: Comparación de órdenes de convergencia y sensibilidad a valores iniciales.

TP 4: PROCESAMIENTO DE IMÁGENES Y AJUSTE DE CURVAS
- Aplicación: Análisis dinámico de una gota de estaño impactando un sustrato.
- Técnicas: Detección de bordes (Canny/Sobel), ajuste de contornos mediante 
  Splines cúbicos y polinomios de mínimos cuadrados.
- Resultados: Cálculo de ángulos de contacto, perímetros y factor de 
  esparcimiento a partir de secuencias de alta velocidad (20538 fps).

TP 5: ECUACIONES DIFERENCIALES ORDINARIAS (EDO)
- Modelado: Simulación del comportamiento dinámico de gotas (oscilador amortiguado).
- Métodos: Comparativa entre Taylor de orden 3, Runge-Kutta 5-6 y 
  Predictores-Correctores (Adams-Bashforth-Moulton).
- Análisis: Evaluación de eficiencia costo-computacional vs. precisión absoluta.

TP 6: FLUJO EN MEDIOS POROSOS (ECUACIÓN DE RICHARDS)
- Desafío: Simulación de transporte de líquidos en papel (redistribución capilar).
- Modelos: Implementación de difusividad no lineal (Brooks-Corey y Van Genuchten).
- Simulación: Resolución 1D y 2D (gota elíptica) mediante diferencias finitas 
  explícitas, analizando la condición de estabilidad CFL.

---------------------------------------------------------------------------
3. TECNOLOGÍAS Y LIBRERÍAS
---------------------------------------------------------------------------
- Lenguajes: Python (Google Colab), C++ (Qt Framework).
- Librerías: NumPy (Cálculo), OpenCV (Imágenes), Plotly/Matplotlib (Gráficos), 
  SciPy (Interpolación).
- Análisis: Control de errores de truncamiento y redondeo en punto flotante.

---------------------------------------------------------------------------
4. ENLACES A LOS CÓDIGOS (GOOGLE COLAB)
---------------------------------------------------------------------------

🚀 TP 2 - ESTEGANOGRAFÍA:
https://colab.research.google.com/drive/15xi-blam9UT6tYjOGIR0RaDS45aRrcx2?usp=sharing

🚀 TP 3 - BÚSQUEDA DE RAÍCES:
https://colab.research.google.com/drive/1tL1KS9Y5E7ZcvndGcN397UFX2SuasiMg?usp=sharing

🚀 TP 4 - AJUSTE Y SPLINES:
https://colab.research.google.com/drive/13LCBeTl6Z-oniJhLcmhpXPcP18TSa15d?usp=sharing

🚀 TP 5 - RESOLUCIÓN DE EDOs:
https://colab.research.google.com/drive/1buBvsYPycUmXyJT7zzKj-L1YNVECIDJT?usp=sharing

🚀 TP 6 - ECUACIÓN DE RICHARDS (2D):
https://colab.research.google.com/drive/11hAJ4gG9Dlrauhw6PG5tt9BUcnzvBEpr?usp=sharing

===========================================================================
