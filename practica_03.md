# **Alex Ruiz Mesa** 
# Actividad 3. Análisis de un incidente de seguridad


## Objetivo
Aplicar correctamente la cadena causal activo → amenaza → vulnerabilidad → riesgo → ataque → impacto al análisis de un incidente de seguridad descrito mediante un caso.

---
### Tarea
***Situaciones***
1. Identifique el activo o activos implicados en el incidente.
2. Identifica la amenaza.
3. Identifica la vulnerabilidad explotada.
4. Explique en qué consistía el riesgo antes de que el incidente se produjera.
5. Describe en qué consistió el ataque .
6. Describa el impacto del incidente, distinguiendo si es de tipo cuantitativo, cualitativo o ambos.
7. Indica qué tipo de vulnerabilidad era, según la clasificación por grado de conocimiento vista en clase (conocida sobre software instalado, conocida sobre software no instalado, o día cero), y justifica tu respuesta.
---
***Respuestas***
1. Activo: La base de datos de los alumnos y el servidor donde se almacena. Son los recursos que contienen y almacenan los datos personales y las calificaciones.

2. Amenaza: El atacante externo. Es quien puede provocar un daño al intentar acceder a la información sin autorización.

3. Vulnerabilidad: El fallo de seguridad conocido del CMS que no estaba actualizado. Existía un parche publicado para corregirlo, pero no se había instalado.

4. Riesgo: La posibilidad de que un atacante accediera al servidor y robara los datos de los alumnos. El CMS tenía un fallo conocido que podía ser aprovechado.

5. Ataque: La explotación del fallo de seguridad mediante un exploit público para acceder al servidor y descargar la base de datos. El atacante utilizó el exploit para entrar sin autorización y copiar toda la información.

6. Impacto: La filtración de los datos personales y las calificaciones, la notificación a las familias y la suspensión temporal de la plataforma. Son las consecuencias que sufrió la academia después del ataque.

7. Tipo de vulnerabilidad: Conocida sobre software instalado.El CMS estaba instalado y funcionando en el servidor. Además, el fabricante ya había publicado un parche seis meses antes para corregir el fallo, por lo que no era una vulnerabilidad de día cero.