# bootcamp-apuntes
Apuntes del bootcamp Data Analyst
# 📅 Día 1 - [06/02/2026]

## 🎯 Lo que hemos visto hoy

### Mañana
- Dinámica: Gartic Phone (sobre distorsión de información)
- Conceptos: ¿Qué es análisis de datos?
- Ejercicio: Palabras en griego (buscar patrones sin contexto)

### Tarde
- Git y GitHub: instalación y configuración
- Primeros comandos: clone, status, add, commit, push

## 💡 Lo que he aprendido
-Usar consolas y terminales, crear repositorio y archivo, clonar etc

## ❓ Dudas que tengo
-Que uso puedo dar a todo lo aprendido hasta ahora

## 🔗 Recursos útiles
- https://github.com/Anais-RV/da-sat-00-launchpad-fundamentos

**Siguiente paso:** Empezar SAT-01 Atlas

"EJERCICIO 3"

### 🔍 Parte 1: Explora estos comandos


git log --oneline: 
RESULTADO: 77118b7 (HEAD -> main, origin/main, origin/HEAD) feat: añadir apuntes del día 1
0a5c37e Initial commit
DESCRIPCION: Nos muestra el inicio de nuestro commit.

git remote -v:
RESULTADO:origin  https://github.com/Asenjo76/bootcamp-apuntes.git (fetch)
origin  https://github.com/Asenjo76/bootcamp-apuntes.git (push)
DESCRIPCION: Nos muestra los repositorios remotos y su url.

git branch:
RESULTADO: * main
DESCRIPCION: Nos dice en que rama estamos, en este caso en la rama de origen.

### 🔍 Parte 2: Preguntas de investigación

1. **¿Qué hace el comando `git pull`?**
     (descargar el contenido de un repositorio remoto y actualizar instantáneamente tu repositorio local para que coincida con el contenido de ese remoto. )

2. **¿Para qué sirve el archivo `.gitignore`?**
     (sirve para decirle a Git qué archivos, carpetas o patrones de archivos específicos deben excluirse del control de versiones y no subirse al repositorio remoto. Su función principal es mantener el proyecto limpio, evitando subir dependencias, archivos temporales, configuraciones personales o información sensible como contraseñas. )

**¿Qué diferencia hay entre `git add .` y `git add nombre-archivo`?**
  (La principal diferencia es el alcance: git add . añade todos los cambios (nuevos, modificados y eliminados) del directorio actual y subdirectorios, mientras que git add <archivo> solo prepara un archivo o carpeta específico para el commit. git add . se usa para agilizar, y git add <archivo> para mayor control. 
Aquí tienes los detalles:
git add .
Alcance: Afecta al directorio actual (.) y todo su contenido.
Función: Añade archivos nuevos, modificados y, en versiones modernas de Git, también archivos eliminados al área de preparación (staging area).
Uso: Ideal cuando quieres subir todos los cambios realizados en tu carpeta de trabajo actual de una sola vez.
git add <nombre-archivo>
Alcance: Limitado a un archivo o archivo específico.
Función: Prepara únicamente el archivo mencionado para el siguiente commit.
Uso: Ideal para realizar un seguimiento preciso o si quieres hacer commits separados de diferentes características (desarrollo granular). )

### 🔍 Parte 3: Guarda tu investigación


## 🔍 Comandos investigados

### git log --oneline
[Tu explicación]

### git remote -v
[Nos muestra el inicio de nuestro commit]

### git branch
[Nos muestra en que rama estamos trabajando]

### git pull
[sincronizar contenido remoto con local]

### .gitignore
[mantener el git limpio y no mostras contraseñas, datos personales, o cualquier cosa que no queremos que muestre en remoto.]

### git add . vs git add archivo
[git add . se usa para agilizar, y git add <archivo> para mayor control. ] 

