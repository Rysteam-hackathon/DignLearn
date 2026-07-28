Aquí tienes el prompt maestro adaptado exactamente a tus nuevas directrices. Mantiene la estructura profesional que vimos en las imágenes, pero el texto está completamente personalizado para **Rysteam**, reflejando que es su primera vez, integrando su lema, la tabla de miembros solicitada y el tono carismático pero humilde.

Copia el siguiente bloque de texto y pégalo directamente en el chat de tu Agente en Antigravity IDE:

**Prompt para Antigravity IDE:**

Actúa como un DevOps y Tech Lead experto. Necesito que me configures la estructura base de directorios, los archivos de documentación profesional y que inicialices el repositorio Git del proyecto **DignaLearn**, desarrollado por el equipo **Rysteam** para el Hackathon Nicaragua 2026\.

El stack tecnológico oficial del proyecto es:

* Frontend: Next.js (TypeScript).  
* Backend: FastAPI (Python) y TypeScript.  
* Base de Datos: PostgreSQL expuesto a través de PostgREST.

Ejecuta las siguientes tareas paso a paso en mi espacio de trabajo actual:

**Tarea 1: Estructura de Carpetas** Crea los siguientes directorios vacíos en la raíz del proyecto para organizar la arquitectura:

* `frontend/`  
* `backend/`  
* `db/`

**Tarea 2: Crear el archivo `.gitignore`** Crea un archivo llamado `.gitignore` en la raíz con el siguiente contenido:

Plaintext  
\# Entornos virtuales y dependencias  
venv/  
env/  
node\_modules/  
.next/  
\_\_pycache\_\_/  
\*.pyc

\# Variables de entorno y secretos  
.env  
.env.local

\# Sistema operativo  
.DS\_Store  
Thumbs.db

**Tarea 3: Crear el archivo `LÉAME.md`** Crea un archivo llamado `LÉAME.md` en la raíz con el siguiente código Markdown exacto. Asegúrate de respetar las tablas y los emojis:

Markdown  
\# 🚀 Rysteam \- Hackathon Nicaragua 2026

\!\[Rysteam\](https://img.shields.io/badge/Equipo-R.Y.S.T.E.A.M-blue) \!\[Hackathon\](https://img.shields.io/badge/Hackathon-Nicaragua\_2026-orange)

Somos \*\*Rysteam\*\*, un grupo de mentes curiosas apasionadas por la tecnología, el diseño y la educación. Esta es nuestra primera vez participando en el Hackathon Nicaragua, ¡y venimos con toda la energía y disposición\! Nuestro enfoque es sencillo pero poderoso: 

\> \*"Aprender para innovar y poder avanzar."\* 🌱

Venimos dispuestos a absorber todo el conocimiento posible, dar nuestro mayor esfuerzo y crear una solución que marque la diferencia.

\---

\#\# 👥 Nuestro Equipo 2026

| Miembro | Rol |  
| :--- | :--- |  
| \*\*Eddy Marenco\*\* | Líder / Marketing |  
| \*\*Ronald Dávila\*\* | Comunicador |  
| \*\*Sharis Peralta\*\* | Diseñadora |  
| \*\*Dirk Martinez\*\* | Desarrollador Backend |  
| \*\*Sidar Perez\*\* | Diseñador / Desarrollador Frontend |

\---

\#\# 🎯 El Proyecto: DignaLearn  
DignaLearn es una plataforma digital educativa que busca transformar la manera en que docentes y estudiantes abordan la enseñanza de los Derechos y Dignidad de la Mujer, Prevención de la Violencia y Equidad de Género, a través del aprendizaje basado en juegos.

\#\#\# 🎯 Misión del Equipo  
Desarrollar una solución innovadora y funcional, cumpliendo con los tiempos del hackathon mediante un enfoque de desarrollo ágil y mucho trabajo en equipo. Nos enfocamos en:

\* ⏱️ \*\*Cumplimiento y aprendizaje:\*\* Planificar efectivamente para entregar un MVP funcional mientras aprendemos en el proceso.  
\* 💡 \*\*Resolución creativa:\*\* Analizar el problema y proponer mecánicas de juego lúdicas que realmente eduquen.  
\* 🤝 \*\*Trabajo en equipo coordinado:\*\* Comunicación constante y apoyo mutuo entre diseño, desarrollo y marketing.

\#\#\# ⚡ Filosofía de Trabajo  
Construimos para aprender y aprendemos para impactar. Como equipo nuevo, aplicamos estos principios:  
\* 🛠️ \*\*Buenas prácticas:\*\* Esforzarnos por escribir código limpio y ordenado desde el día uno.  
\* ⚙️ \*\*Tecnologías modernas:\*\* Seleccionamos herramientas potentes (Next.js, FastAPI, PostgreSQL) para retarnos y escalar la solución.  
\* 🎯 \*\*Enfoque en impacto real:\*\* No solo programamos; creamos una herramienta con valor educativo y aplicabilidad en las escuelas.

\#\#\# 📌 Objetivo 2026  
Este año nuestro objetivo es claro:  
🏆 \*\*Dar nuestra mejor versión en nuestra primera participación, absorber experiencia y entregar una plataforma (DignaLearn) completamente funcional que destaque por su innovación educativa.\*\*

\---

\#\# ⚙️ Tecnologías (Stack)  
\* \*\*Frontend:\*\* Next.js (TypeScript)  
\* \*\*Backend:\*\* FastAPI (Python) y TypeScript  
\* \*\*Base de Datos:\*\* PostgreSQL \+ PostgREST

\#\# 🚀 Ejecución Local

\*\*1. Clonar el repositorio\*\*  
\\\`\\\`\\\`bash  
git clone \[URL\_DEL\_REPOSITORIO\]  
cd DignaLearn  
\\\`\\\`\\\`

\*(Instrucciones detalladas de despliegue en construcción...)\*

**Tarea 4: Crear el archivo `CÓDIGO_DE_CONDUCTA.md`** Crea el archivo con este contenido:

Markdown  
\# 🤝 Código de Conducta de Rysteam

\#\# Nuestra Promesa  
Con el interés de fomentar una comunidad abierta y acogedora, y sabiendo que estamos aquí para aprender y crecer, nos comprometemos a hacer de la participación en nuestro proyecto (DignaLearn) una experiencia basada en el respeto mutuo, la empatía y la colaboración.

\#\# Nuestros Estándares  
Comportamientos que contribuyen a crear un ambiente positivo:  
\* Usar un lenguaje amigable y motivador.  
\* Ser respetuoso con las ideas y niveles de experiencia de cada miembro.  
\* Aceptar críticas constructivas con gracia y disposición a mejorar.  
\* Mostrar empatía y ayudarnos mutuamente en los bloqueos técnicos o creativos.

\#\# Cumplimiento  
Cualquier situación puede ser conversada con confianza con el líder del equipo o cualquier compañero. Las decisiones para mejorar nuestra dinámica se tomarán siempre en conjunto.

**Tarea 5: Crear el archivo `CONTRIBUYENDO.md`** Crea el archivo con este contenido:

Markdown  
\# 🛠️ Guía de Contribución \- Rysteam

¡Bienvenidos al desarrollo de DignaLearn\! Para mantener nuestro código ordenado en esta primera experiencia, seguiremos estas reglas básicas:

\#\# 1\. Estrategia de Ramas  
\* \*\*No subir código directamente a \`main\`.\*\*  
\* Cada miembro creará una rama para su tarea: \`git checkout \-b feature/nombre-de-la-tarea\`.  
\* Ejemplo Backend: \`feature/api-usuarios\`.  
\* Ejemplo Frontend: \`feature/ui-dashboard\`.

\#\# 2\. Mensajes de Commit (Conventional Commits)  
Tus mensajes deben explicar claramente qué hiciste:  
\* \`feat:\` Para cosas nuevas (ej. \`feat: agregar vista de inicio\`).  
\* \`fix:\` Para corregir errores (ej. \`fix: corregir color del botón\`).  
\* \`docs:\` Para actualizar textos o LÉAME.

\#\# 3\. Unir el código (Pull Requests)  
Cuando termines tu parte, sube la rama y crea un Pull Request. Nos avisamos por nuestro canal de comunicación para revisarlo juntos antes de unirlo al proyecto principal.

**Tarea 6: Inicialización de Git (Commit Cero)** Abre la terminal integrada del IDE y ejecuta estrictamente estos comandos en este orden para inicializar el control de versiones local:

1. `git init`  
2. `git add .`  
3. `git commit -m "feat(core): initial commit - estructura base, LÉAME adaptado y reglas del equipo Rysteam"`  
4. `git branch -M main`

