# Elaboración de sistema de centralización de datos para el area administrativa del Taller de Piano Moreno-Fonseca
---
* **Problemática a resolver:** Digitalizar y centralizar toda la información sobre profesores, estdiantes, detalles curriculares, entre otros. del Taller de Piano. Ya que los dueños tienen toda esta información escrita a mano, haciendo la consulta de información más morosa y ocupando espacio físico innecesario.
## Transcripción de la entrevista de levantamiento de requerimientos
**Entrevistador:** Simone Ruiz (estudiante de la UAGRM)
**Entrevistados:** Prof. Giovanni Moreno y Prof. Carmen Fonseca
---
**Simone:** Buenas tardes, profesores. Como saben, estoy desarrollando un sistema para centralizar la información de la escuela, ya que hoy todo se maneja en papel. Quería empezar preguntando: ¿cómo organizan actualmente a sus alumnos?

**Carmen:** Los organizamos por nivel. Cada alumno pertenece a un nivel según su avance técnico y su repertorio, no por edad.

**Giovanni:** Exacto. Y el problema es que esa información está en cuadernos distintos, cada uno con el suyo. Si Carmen quiere saber en qué nivel está un alumno mío, tiene que preguntarme directamente.

**Simone:** Entiendo. Hablemos entonces del nivel como concepto central. ¿Cuántos niveles manejan y cómo los definen?

**Carmen:** Manejamos niveles como Iniciación, Básico 1, Básico 2, Intermedio, Avanzado... Cada uno tiene un nombre y una descripción general de lo que el alumno debe dominar para pasar al siguiente.

**Giovanni:** Y cada nivel tiene una currícula asociada: las piezas, escalas, ejercicios técnicos y conceptos teóricos que corresponden a ese nivel.

**Simone:** ¿Entonces cada nivel tiene un contenido curricular propio, y ese contenido puede tener varias piezas o temas dentro?

**Carmen:** Sí. Por ejemplo, en Básico 1 vemos escalas de una octava, piezas de Bastien, y teoría de intervalos simples. Eso debería quedar registrado como el "contenido" de ese nivel.

**Giovanni:** También sería útil registrar los requisitos para pasar de un nivel a otro. No es automático; nosotros evaluamos.

**Simone:** Perfecto, eso me da una buena base para el nivel. Ahora, ¿qué datos necesitan guardar de cada alumno?

**Carmen:** Nombre completo, edad, datos de contacto de los padres si es menor, la fecha en que ingresó a la escuela, y el nivel actual en el que está.

**Giovanni:** Y el historial de niveles anteriores también sería útil, para ver la evolución del alumno.

**Simone:** ¿Y de ustedes como docentes? ¿Qué información debería registrar el sistema?

**Giovanni:** Nombre, especialidad si la hay, y qué alumnos tiene asignados. También en qué niveles está habilitado para enseñar.

**Simone:** Última pregunta: mencionaron festivales antes. ¿Cómo se relacionan con los niveles y alumnos?

**Carmen:** Los festivales tienen categorías que normalmente corresponden a los niveles, o a rangos de niveles. Un alumno se inscribe a un festival según su nivel actual.

**Giovanni:** Y nos gustaría poder ver rápidamente qué alumnos de cada nivel están preparados para participar en el próximo festival.

**Simone:** Excelente, con esto tengo claro el modelo. Muchas gracias a ambos.

## Entidades identificadas
* Profesores, Estudiantes, Nivel, Curricula, Repertorio, Obra, Festivales.
## Diagrama Enrtidad Relación para el Taller de Piano Moreno Fonseca
<img width="448" height="343" alt="image" src="https://github.com/user-attachments/assets/35ca8aee-61a1-410b-b788-e8e809d1e6be" />
