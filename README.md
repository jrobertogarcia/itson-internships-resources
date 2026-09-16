# ITSON Tech Career & Interview Resources

Un mapa práctico para prepararse para **Summer Internships** y vacantes de **New Grad** en empresas de tecnología y Big Tech: CV, proyectos defendibles, inglés técnico, preparación en LeetCode y estrategia de aplicación.

## Tabla de Contenidos

* [Diapositivas y Comunidad](#diapositivas-y-comunidad)
* [Cómo Evalúa la Industria](#cómo-evalúa-la-industria)
* [Estrategia de Calendario y Ventana Universitaria](#estrategia-de-calendario-y-ventana-universitaria)
* [Preparación por Tiempos](#preparación-por-tiempos)
* [El Método: Los 5 Pasos de la Entrevista Técnica](#el-método-los-5-pasos-de-la-entrevista-técnica)
* [LeetCode y Algoritmos](#leetcode-y-algoritmos)
  * [Python para Entrevistas](#python-para-entrevistas)
  * [Estrategia de Estudio](#estrategia-de-estudio)
  * [Rutas Recomendadas](#rutas-recomendadas)
* [CV / Resume](#cv--resume)
  * [Checklist ATS](#checklist-ats)
  * [Redacción de Proyectos con Impacto](#redacción-de-proyectos-con-impacto)
  * [LinkedIn](#linkedin)
* [Proyectos Defendibles](#proyectos-defendibles)
* [Inglés Técnico](#inglés-técnico)
* [Applying](#applying)
* [Behavioral](#behavioral)
* [FAQ](#faq)
* [Mentores y Soporte](#mentores-y-soporte)

## Diapositivas y Comunidad

* **Diapositivas del taller:** [Ver en Google Slides](https://docs.google.com/presentation/d/1TE4vPEolC2-H3QZC3cqKkmoB6YUngX9xj6kZekZoPFk/edit?usp=sharing)
* **Plática previa (Febrero):** [Ver en Canva](https://www.canva.com/design/DAG_lLAilYs/Syh6lLu23on0g6CnZc5APw/view?utm_content=DAG_lLAilYs&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h419278b57f)
* **Comunidad:** [Entrar a Discord](https://discord.gg/cKxpt9vXUw)

En Discord centralizamos el seguimiento y la preparación: avisos y convocatorias (`#announcements`, `#new-grad-internships`), retroalimentación de CVs (`#resume-review`), discusión de problemas semanales (`#problem-of-the-week`) y salas de voz para estudiar o simular entrevistas en equipo.

## Cómo Evalúa la Industria

La universidad te forma como ingeniero de software (programación, bases de datos, arquitectura), pero las empresas de tecnología filtran mediante una prueba distinta: problemas algorítmicos contra reloj, claridad mental y comunicación técnica en inglés. **Ser un buen ingeniero no es lo mismo que ser bueno pasando entrevistas técnicas**; pasar estas evaluaciones es una habilidad aparte que se entrena con práctica constante.

### Qué compone una oferta en tech

Las ofertas de industria suelen incluir beneficios que hacen viable mudarte sin poner de tu bolsa:

* **Summer Internships:** Prácticas 100% remuneradas con salario competitivo, vuelos de ida y vuelta, corporate housing (o housing stipend mensual) y laptop de trabajo asignada.
* **New Grad (Full-Time):** Sueldos de entrada competitivos, seguro de gastos médicos mayores, fondo de ahorro, bonos de reubicación y equity (acciones líquidas de la empresa).
* **Datos de referencia:** Para consultar salarios verificados en la industria dentro de México, revisa [Levels.fyi México](https://www.levels.fyi/t/software-engineer/locations/mexico).

## Estrategia de Calendario y Ventana Universitaria

El error más común es esperar a graduarte para buscar trabajo. En empresas de tecnología globales, los procesos ocurren con un año de anticipación:

* **Rolling basis:** Las vacantes de internships y New Grad abren entre agosto y octubre para ingresar el verano o año siguiente. Se evalúa conforme van llegando las aplicaciones; cuando los cupos se llenan, la vacante se cierra.
* **La meta del Return Offer:** El camino más predecible para entrar a una empresa de tecnología no es aplicar directo a Full-Time, sino entrar por un Summer Internship y asegurar una oferta de retorno (return offer). Esto te permite regresar a la escuela a terminar materias con tu contrato firmado antes de graduarte.
* **Estatus de estudiante activo y extensión:** Para calificar a la gran mayoría de los Summer Internships, es obligatorio ser estudiante activo durante la pasantía y graduarte después de la misma. Como en ITSON no hay residencias profesionales obligatorias de semestre completo, una estrategia común es dejar una o dos materias pendientes para el siguiente semestre. Esto extiende tu ventana universitaria y te permite competir en internships, cuyo filtro técnico suele ser más accesible que el de New Grad.

## Preparación por Tiempos

En lugar de intentar cubrir todo en una semana y frustrarte, divide el esfuerzo según lo que toma construir cada parte:

### Corto plazo (Días a semanas)
* CV de 1 página en formato estándar y en inglés.
* Perfil de LinkedIn limpio con roles claros y enlaces a proyectos.
* Inglés funcional para explicar tu razonamiento técnico sin congelarte.

### Mediano plazo (Semanas a meses)
* 1 a 2 proyectos defendibles con decisiones de diseño justificadas.
* Dominar los fundamentos de LeetCode: Arrays & Hashing, Two Pointers y Sliding Window.

### Largo plazo (Hábito continuo)
* Práctica constante basada en reconocimiento de patrones.
* Enviar aplicaciones de forma regular y tomar los Online Assessments (OAs) como práctica bajo tiempo para medir tu nivel real.

## El Método: Los 5 Pasos de la Entrevista Técnica

En una entrevista técnica, empezar a programar sin hablar es el error más común. Lo que buscan evaluar es cómo piensas a través de estos pasos:

1. **Clarificar:** Haz preguntas sobre datos de entrada, restricciones y casos límite antes de escribir código (¿hay negativos?, ¿el array puede venir vacío?, ¿qué tamaño máximo tiene?).
2. **Proponer (Brute Force):** Plantea de inmediato una primera solución directa que funcione, aunque sea $O(N^2)$. Esto valida que entendiste el problema, quita los nervios y establece una base para optimizar.
3. **Optimizar:** Identifica el cuello de botella del enfoque previo y elige la estructura de datos o técnica adecuada (Hash Set, Two Pointers, ordenamiento) antes de tocar el teclado.
4. **Codificar:** Escribe código limpio practicando think out loud. Narra cada decisión que tomas conforme programas para que el entrevistador siga tu proceso mental.
5. **Probar:** Realiza un dry run manual con un caso de prueba, verifica casos extremos y concluye calculando la complejidad de tiempo y espacio en Big-O.

> **Hints y colaboración:** El entrevistador evalúa cómo resuelves problemas en equipo. Si te ofrece un hint, escúchalo con atención y úsalo para ajustar tu solución; tomar una pista no te resta puntos.

## LeetCode y Algoritmos

LeetCode es un filtro estandarizado para evaluar lógica y velocidad bajo presión, no el trabajo diario. Se supera aprendiendo patrones reutilizables.

### Python para Entrevistas

Nuestra recomendación es resolver entrevistas en **Python**. Su sintaxis concisa y estructuras nativas (`set`, `dict`, `list`) liberan espacio mental para concentrarte de lleno en la lógica del problema, sin la sobrecarga de sintaxis de Java o C++.

* Video sugerido para dominar la sintaxis básica en entrevistas: [Python for Coding Interviews (NeetCode)](https://www.youtube.com/watch?v=0K_eZGS5NsU).

### Estrategia de Estudio

* **La regla de los 15 minutos:** Intenta resolver el ejercicio por tu cuenta durante 15 minutos. Si pasado ese tiempo estás bloqueado, abre la solución o mira la explicación en video. Concéntrate en entender el *porqué* del patrón (por qué se eligió esa estructura de datos), no en memorizar líneas de código.
* **Spaced repetition:** Vuelve a intentar el mismo problema 3 o 4 días después en un editor en blanco. La meta es poder programarlo y explicar el enfoque sin consultar la solución.
* **Tópicos esenciales:** Enfócate primero en dominar los temas con mayor frecuencia en entrevistas: Arrays & Hashing, Two Pointers, Sliding Window, Stack, Binary Search, Linked List y Trees.

### Rutas Recomendadas

Elige la lista de práctica según la ventana de tiempo que tengas disponible:

* **Ruta rápida (Menos de 2 meses):** [Blind 75](https://neetcode.io/practice). Selección de 75 problemas clave que cubren los patrones indispensables.
* **Ruta estándar (3 a 6 meses):** [NeetCode 150](https://neetcode.io/practice). La ruta recomendada para preparar convocatorias con cobertura técnica balanceada.
* **Ruta progresiva (Más de 6 meses o primeros semestres):** [NeetCode 250](https://neetcode.io/practice). Currículo amplio para aprender algoritmos paso a paso sin prisas.
* **Problemas por empresa:** Preguntas frecuentes organizadas por compañía para revisar antes de un proceso específico: [LeetCode Company Wise Problems](https://github.com/liquidslr/leetcode-company-wise-problems).

## CV / Resume

Los sistemas de filtrado inicial (ATS) y los reclutadores descartan CVs en segundos si el formato es confuso o tiene adornos innecesarios.

### Recursos Clave

* **Plantilla recomendada:** [Jake's Resume en Overleaf](https://www.overleaf.com/latex/templates/jakes-resume/syzfjbzwjncs). Haz clic en *Open as Template* y edita directamente el texto entre llaves `{}`. LaTeX garantiza una salida tipográfica limpia y compatible con ATS.
* **Guía de referencia:** [r/EngineeringResumes Wiki](https://www.reddit.com/r/EngineeringResumes/wiki/index/).

### Checklist ATS

* **Exactamente 1 página** redactada en **inglés**.
* Formato en blanco y negro sin diseños de Canva, iconos ni columnas complejas.
* Sin fotografía, sin edad, sin estado civil ni dirección postal completa.
* Sin barras de porcentaje (nada de "Python 80%").
* Enlaces directos y funcionales a tu perfil de LinkedIn y repositorios en GitHub.

### Redacción de Proyectos con Impacto

Estructura cada viñeta siguiendo la fórmula: **Acción + Herramientas/Stack + Impacto medible**.

* *Evita:* "Hice una aplicación web con React y Python."
* *Prefiere:* "Desarrollé una plataforma web con React y FastAPI, optimizando el tiempo de respuesta del backend en un 35%."

### LinkedIn

* Titular profesional claro: "Software Engineering Student | Backend".
* URL personalizada limpia (`linkedin.com/in/tu-nombre`).
* Sección "Acerca de" de dos párrafos explicando tu stack tecnológico, qué proyectos estás desarrollando y qué tipo de roles buscas.

## Proyectos Defendibles

Un proyecto defendible es aquel que puedes desglosar en una conversación de 5 minutos explicando decisiones técnicas reales. No necesitas sistemas masivos; necesitas proyectos funcionales de los cuales conozcas cada componente.

### Preguntas que debes poder responder sobre tu proyecto:

* **El Problema:** Qué soluciona y para qué usuario está pensado.
* **Arquitectura:** Cómo se comunican el frontend, el backend y la persistencia de datos.
* **Decisiones Técnicas:**
  * Por qué elegiste esa base de datos (SQL vs. NoSQL) y cómo estructuraste el esquema.
  * Diseño de endpoints (REST, autenticación, paginación, manejo de errores).
  * Rendimiento (caching, indexación).
  * Trade-offs: qué decisiones técnicas sacrificaste por tiempo o alcance.
* **Limitaciones:** Qué fallas tiene actualmente y qué cambiarías si tuvieras más tiempo para desarrollarlo.

## Inglés Técnico

No necesitas acento nativo ni vocabulario rebuscado. Lo indispensable es poder explicar tu razonamiento técnico de forma estructurada (*"I initialized a hash map to track the indices because dictionary lookup is constant time"*).

* **Herramientas gratuitas:** [Episoden](https://www.episoden.com/) (conversaciones 1:1 para perder el miedo a hablar) y [Sesame](https://app.sesame.com/) (práctica de conversación con asistentes de voz con IA).
* **Hábito mínimo:** Practica hablar en voz alta de 10 a 15 minutos diarios explicando tus soluciones de código en inglés conforme programas.

## Applying

La idea no es mandar cientos de solicitudes en un solo día, sino aplicar de forma constante conforme abran vacantes:

* **Dónde buscar:** LinkedIn Jobs y directamente en las páginas de carreras de las empresas (Careers Pages).
* **Te van a ghostear (y es normal):** En la mayoría de las postulaciones no vas a recibir respuesta o te llegará un correo genérico de rechazo. Es lo estándar en la industria; no te lo tomes personal.
* **Online Assessments (OAs):** Cuando una empresa te envíe un test en HackerRank o CodeSignal, tómalo como una práctica real bajo tiempo para medir tu nivel actual.

## Behavioral

No inviertas tiempo en entrevistas de comportamiento al inicio; prepáralas dos semanas antes de tener rondas programadas.

* **Formato STAR:** Estructura tus respuestas narrando **Situación**, **Tarea**, **Acción** y **Resultado**.
* Prepara 6 a 8 anécdotas reales basadas en: trabajo en equipo, resolución de un desacuerdo técnico, manejo de un error de software y liderazgo en proyectos escolares o personales.
* Guía recomendada: [Matt Huang - Behavioral Interviews](https://www.youtube.com/watch?v=WdyiUe7_3cA).

## FAQ

### ¿Tengo que esperar a estar 100% preparado para aplicar?
No. Casi nadie se siente completamente listo. Aplicar temprano te expone al mercado real, te obliga a mejorar el CV y genera la urgencia necesaria para estudiar.

### ¿Importa mi promedio o venir de ITSON?
No. A las empresas de tecnología globales no les importa tu promedio, kárdex ni el renombre de tu universidad. El filtro es técnico: si tu CV pasa el formato ATS y resuelves las entrevistas, la oferta es tuya.

### ¿Qué pasa si me va mal en una entrevista o en un OA? ¿Me vetan?
Para nada. No existen listas negras. Solo hay un periodo de espera (cooldown) de 6 a 12 meses según la empresa. En el siguiente ciclo de contratación puedes volver a aplicar desde cero sin penalización.

### ¿Cuántos problemas tengo que resolver para estar listo?
No hay una cifra fija. Es mucho mejor dominar 40 o 50 problemas comprendiendo bien el patrón, que memorizar 200 que no sabrás adaptar si te cambian un detalle.

### ¿Sirven los proyectos escolares o tienen que ser personales?
Los proyectos de clase sirven perfectamente. Lo importante no es si lo hiciste para una materia o por tu cuenta, sino que esté terminado, funcione y puedas defender las decisiones técnicas de cómo lo construiste.

### ¿Son indispensables los referrals?
Ayudan a que un reclutador revise tu CV antes, pero no garantizan la oferta. Lo verdaderamente determinante sigue siendo tener un buen CV y pasar las evaluaciones técnicas.

### ¿Un Summer Internship interrumpe mis clases en ITSON?
Normalmente no. Duran 12 semanas (de finales de mayo a agosto), coincidiendo con las vacaciones de verano en ITSON. Terminas el intern y regresas a clases regulares en otoño.

### ¿Necesito visa de trabajo para aplicar?
No. La gran mayoría de estas vacantes son para sedes en México (CDMX, Guadalajara o remoto) con contrato local. Si la pasantía es en Estados Unidos, la empresa tramita y paga la visa correspondiente (J-1).

## Mentores y Soporte

Este recurso y los talleres técnicos de preparación son coordinados por estudiantes y egresados para la comunidad de ITSON:

* [Carlos Juven](https://www.linkedin.com/in/juvenr/)
* [Roberto Garcia](https://www.linkedin.com/in/jrobertogarcia/)
* [Sergio Covarrubias](https://www.linkedin.com/in/sergio-cov/)

Para resolver dudas sobre ejercicios, pedir revisión de CV o consultar convocatorias, únete a la comunidad en nuestro servidor de [Discord](https://discord.gg/cKxpt9vXUw).