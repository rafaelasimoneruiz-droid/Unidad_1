# Elaboración de sistema de centralización de datos para el area administrativa del Taller de Piano Moreno-Fonseca
---
* **Problemática a resolver:** Digitalizar y centralizar toda la información sobre profesores, estudiantes, detalles curriculares, entre otros del Taller de Piano. Ya que los dueños tienen toda esta información escrita a mano, haciendo la consulta de información más morosa y ocupando espacio físico innecesario.
## Transcripción de la entrevista de levantamiento de requerimientos

**Entrevistador:** Simone Ruiz (estudiante de la UAGRM)

**Entrevistados:** Prof. Giovanni Moreno y Prof. Carmen Fonseca

---

La conversación comenzó planteando el problema central del proyecto a los dueños y profesores de la escuela: la información hoy se maneja en papel, dispersa en cuadernos individuales. Giovanni, profesor de la escuela, lo resumió con claridad al contar que si Carmen quiere saber en qué nivel está un alumno suyo, "tiene que preguntarme directamente" — evidenciando la falta de un registro compartido.

A partir de ahí, Carmen, también profesora y dueña de la escuela, explicó el criterio que organiza todo: los alumnos se agrupan "por nivel, según su avance técnico y su repertorio, no por edad". Enumeró los niveles existentes (Elemental A, Elemental B, Elemental, Nivel 1-7, Técnico medio y Técnico superior) y aclaró que cada uno cuenta con un nombre y una descripción general de lo que el alumno debe dominar para avanzar. Giovanni complementó esta idea señalando que cada nivel tiene además "una currícula asociada", compuesta por piezas, escalas, ejercicios técnicos y conceptos teóricos propios de esa etapa. Carmen lo ilustró con un ejemplo concreto: en Básico 1 se trabajan escalas de una octava, piezas de Bastien y teoría de intervalos simples, contenido que debería quedar registrado como parte del nivel. Giovanni añadió un matiz importante: el paso de un nivel a otro no es automático, sino que depende de una evaluación de los profesores, por lo que también deberían registrarse los requisitos de promoción.

Con el nivel definido como eje del sistema, se planteó la pregunta de qué datos necesitaban guardar de cada alumno. Carmen mencionó nombre completo, edad, datos de contacto de los padres en caso de ser menor, fecha de ingreso a la escuela y nivel actual. Giovanni sumó un punto que enriquece el modelo con una dimensión histórica: registrar también el historial de niveles anteriores, para poder ver la evolución del alumno con el tiempo.

Sobre los propios profesores, Giovanni fue quien detalló los requerimientos: nombre, especialidad (si la tiene), los alumnos que tiene asignados, y en qué niveles está habilitado para enseñar.

Finalmente, se retomó el tema de los festivales. Carmen explicó que estos tienen categorías que suelen corresponder a los niveles o a rangos de niveles, y que un alumno se inscribe según su nivel vigente. Giovanni cerró la entrevista con un requerimiento funcional concreto: poder ver rápidamente qué alumnos de cada nivel están preparados para participar en el próximo festival.

---

## Entidades identificadas
* Profesores: nombre, apellidos, contacto, fecha de nacimiento, detalles sobre nivel académico.
* Estudiantes: nombre, apellidos, contacto, tutores.
* Nivel: desde el nivel Elemental A, B, Elemental , Nivel 1-7, Técnico medio y Técnico Superior.
  Etsos niveles tienen variantes según la edad del estudiante, se dividen entre "Niños" y "Adultos".
* Curricula: Técnica dependiendo del nivel en que se encuentren.
* Repertorio: sugerido según el nivel al que pertenecen. Contiene datos sobre el autor, época y , Obra.
* Festivales: detalles sobre lugar, fechas y categoría.
  
## Diagrama Enrtidad Relación para el Taller de Piano Moreno Fonseca
<img width="640" height="437" alt="image" src="https://github.com/user-attachments/assets/c93ad4ba-dbd8-4300-85d8-24ce33ca54f8" />

