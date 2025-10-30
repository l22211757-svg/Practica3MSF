\[!\[Open in MATLAB Online]

# Práctica: Sistema musculoesquelético

## Información de la estudiante

Corina Plata-Ante \[03210981]; corina.plata@tectijuana.edu.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Convertir el diagrama mecánico al diagrama eléctrico.
2. Calcular la función de transferencia aplicando el principio de superposición.
3. Calcular el error en estado estacionario y la estabilidad en lazo abierto.
4. Emular y simular la respuesta del circuito en Simulink/Simscape a la señal impulso unitario.
5. Sintonizar las ganancias de un controlador PID para eliminar el error entre la entrada y la salida del sistema control-caso.
6. Obtener la respuesta en lazo abierto y en lazo cerrado con el controlador PID en Spyder/Python con la función de transferencia.

## Descripción detallada del sistema

El término F0 representa la fuerza desarrollada por el elemento contráctil activo del músculo, mientras que F(t) es la fuerza real que resulta después de tener en cuenta las propiedades mecánicas del músculo, y se asume que F0 = αF(t), donde 0 < α< 1; R representa la amortiguación viscosa inherente al tejido, mientras que Cp (elemento elástico paralelo) y Cs (elemento elástico en serie) reflejan las propiedades de almacenamiento elástico del sarcolema y los tendones musculares, respectivamente.

La configuración paralela se realiza para considerar las restricciones mecánicas impuestas a los componentes del modelo. Si el resorte Cp se estira en una longitud incremental x(t), toda la combinación en serie de R y Cs también se extenderá en la misma longitud. Además, la suma de la fuerza transmitida a través de las dos ramas de la configuración paralela debe ser igual a F(t). Aunque la suma de las extensiones de Cs y R tendrá que ser igual a x(t), las contribuciones individuales de longitud de Cs y R no necesitan ser iguales. Por lo tanto, si se asume que C\_{s} se estira una longitud x₁(t), entonces la extensión en la combinación paralela de R y F0 será x(t)-x₁(t). La velocidad con la que se extiende el amortiguador representado por R se obtiene al derivar x(t) - x1(t) con respecto al tiempo, es decir, d\[x(t) - x1(t)] /dt.

Palabras clave: ???; ???; ???; ???; ???

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB \[.mlx].
2. Modelo de Simulink \[.slx].
3. Archivos de Spyder \[.py].
4. Imagen con los parámetros del controlador.
5. Imágenes de las simulaciones \[.pdf y .png].
6. Evidencia del análisis matemático: función de transferencia, error en estado estacionario y estabilidad en lazo abierto.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley \& Sons, 2020.

