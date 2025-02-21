📄 Resumen de lo aprendido
Git es una herramienta que sirve para llevar el control de las versiones de un proyecto. Básicamente, permite ver los cambios que se han hecho en el código, quién los hizo y cuándo. Esto es súper útil cuando se trabaja en equipo, porque evita que se sobrescriban archivos y facilita volver a versiones anteriores si algo sale mal.

La diferencia entre Git y GitHub es que Git es la herramienta que se usa en el computador para manejar versiones, mientras que GitHub es una plataforma donde se pueden guardar esos proyectos en línea y colaborar con otras personas. Ahí se pueden crear issues para reportar problemas, hacer pull requests para sugerir cambios, y más.

El uso de ramas (branching) en Git permite trabajar en nuevas funciones o arreglos sin afectar la versión principal del proyecto. Además, usar Git tiene muchas ventajas comparado con guardar archivos de forma tradicional, como tener un historial completo de cambios y poder trabajar sin conexión.

También aprendí que existen repositorios locales (los que se guardan en el equipo) y remotos (los que están en plataformas como GitHub). Se pueden conectar entre sí para subir los cambios que se hacen localmente. Por último, las claves SSH sirven para conectarse a GitHub de forma segura sin tener que escribir la contraseña cada vez.

📝 Comandos de Git más importantes
git init	Inicializa un nuevo repositorio Git local.
git clone <url>	Clona un repositorio remoto a tu máquina local.
git status	Muestra el estado de los archivos en el repositorio.
git add <archivo>	Agrega archivos específicos al área de preparación.
git add .	Agrega todos los archivos modificados al área de preparación.
git commit -m "mensaje"	Guarda los cambios con un mensaje descriptivo.
git push	Envía los cambios locales al repositorio remoto.
git pull	Descarga y fusiona cambios desde el repositorio remoto.
git fetch	Descarga cambios del repositorio remoto sin fusionarlos.
git branch	Lista todas las ramas en el repositorio.
git branch <nombre>	Crea una nueva rama.
git checkout <rama>	Cambia a la rama especificada.
git merge <rama>	Fusiona la rama especificada con la rama actual.
git remote add origin <url>	Conecta el repositorio local con uno remoto.
git log	Muestra el historial de commits.
git diff	Muestra las diferencias entre versiones.
git reset --hard <commit>	Revierte el repositorio a un commit anterior.
git rm <archivo>	Elimina archivos del repositorio y del sistema de archivos.
git stash	Guarda temporalmente cambios no confirmados.
git tag <nombre>	Crea una etiqueta en un commit específico.
