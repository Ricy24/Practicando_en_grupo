# 🍎 Blancanieves y los Siete Enanitos  

📘 **Proyecto de clase – Git & GitHub**

¡Bienvenido/a a este repositorio!  
Este proyecto forma parte de una práctica de la clase de **Git**, donde estamos aprendiendo a usar el control de versiones mientras subimos un cuento clásico: **Blancanieves**.

---

## 📖 Descripción del proyecto

En este repositorio encontrarás una versión escrita del cuento **Blancanieves**, utilizada como ejemplo para practicar:

- Creación de repositorios  
- Uso de commits  
- Subida de archivos a GitHub  
- Control de versiones  

Todo esto mientras trabajamos con una historia conocida y divertida ✨

---

## 🎯 Objetivo

El objetivo principal es aprender a usar **Git y GitHub** de manera correcta, entendiendo cómo guardar cambios y organizar un proyecto usando un cuento como contenido.

---

## 🛠️ Tecnologías usadas

- 📄 Markdown  
- 🧠 Git  
- 🌐 GitHub  

---

## 📂 Contenido del repositorio

- `blancanieves.md` → Cuento de Blancanieves  
- `README.md` → Información del proyecto  

---

## 👩‍💻 Autor/a

Proyecto realizado por **Andres Duran**  
Proyecto realizado por **Juan david**  
Clase de Git 💻📚

---

## ✨ Nota final

Este repositorio es solo con fines **educativos**.  
¡Aprendiendo Git paso a paso con cuentos clásicos! 🚀🍎



INFORME DETALLADO: USO DE RAMAS EN GIT – TRABAJO COLABORATIVO

Proyecto: Cuento Blancanieves
Repositorio: Practicando_en_grupo
Integrantes:

Andrés Durán (creador del repositorio)

Juan Gil (colaborador)

1. Objetivo de la actividad

El objetivo de esta actividad fue aplicar el uso de Git y GitHub para el trabajo colaborativo, haciendo uso de ramas (branches), permitiendo que cada integrante trabajara de manera independiente sobre un mismo archivo sin afectar el trabajo del otro, y posteriormente integrar los cambios al repositorio principal.

2. Creación del proyecto y repositorio

El aprendiz Andrés Durán realizó los siguientes pasos iniciales:

Creó una carpeta llamada Cuento en el escritorio.

Abrió Git Bash dentro de la carpeta.

Inicializó el repositorio con el comando:

git init


Se creó el archivo de texto Blancanieves.txt, el cual inicialmente contenía únicamente el título del cuento.

Se verificó el estado del repositorio:

git status


Se agregaron los archivos al área de preparación:

git add .


Se realizó el primer commit:

git commit -m "Creación del archivo del cuento Blancanieves"


El repositorio fue creado en GitHub con el nombre Practicando_en_grupo y enlazado al repositorio local.

Finalmente se subieron los archivos al repositorio remoto:

git push -u origin master

3. Creación de ramas
3.1 Creación de la rama AndresDuran

Para trabajar de forma independiente, Andrés Durán creó su propia rama con el comando:

git branch AndresDuran


Luego cambió a dicha rama con:

git checkout AndresDuran


También se pudo crear y cambiar a la rama directamente con:

git checkout -b AndresDuran


Se verificó la rama activa con:

git branch

3.2 Creación de la rama JuanGil

El aprendiz Juan Gil, después de clonar el repositorio, creó su rama personal con:

git branch JuanGil


Luego accedió a ella usando:

git checkout JuanGil


De esta manera, cada integrante trabajó en su propia rama sin interferir con la del otro.

4. Clonación del repositorio por el compañero

Juan Gil clonó el repositorio desde GitHub utilizando:

git clone https://github.com/Ricy24/Practicando_en_grupo.git


Luego ingresó a la carpeta del proyecto y verificó las ramas existentes:

git branch -a

5. Desarrollo del cuento por ramas
5.1 Trabajo en la rama AndresDuran

En la rama AndresDuran, Andrés realizó las siguientes acciones:

Abrió el archivo Blancanieves.txt.

Escribió el inicio y el nudo del cuento.

Verificó el estado del archivo:

git status


Agregó los cambios:

git add .


Confirmó los cambios:

git commit -m "Inicio y nudo del cuento Blancanieves"


Subió la rama al repositorio remoto:

git push -u origin AndresDuran

5.2 Trabajo en la rama JuanGil

En la rama JuanGil, Juan Gil realizó:

Apertura del archivo Blancanieves.txt.

Escritura del final y desenlace del cuento.

Verificación del estado:

git status


Preparación de los cambios:

git add .


Confirmación del commit:

git commit -m "Final y desenlace del cuento Blancanieves"


Subida de la rama al repositorio remoto:

git push -u origin JuanGil

6. Uso de comandos de verificación y sincronización

Durante el proceso se utilizaron varios comandos para verificar y sincronizar la información:

Ver ramas locales y remotas:

git branch -a


Traer información del repositorio remoto:

git fetch


Ver el estado de los archivos:

git status


También se evidenciaron errores comunes de escritura como git flech o git brunch, los cuales permitieron identificar la importancia de escribir correctamente los comandos.

7. Integración de ramas (merge)
7.1 Unión de la rama AndresDuran a master

Se cambió a la rama principal:

git checkout master


Se integraron los cambios:

git merge AndresDuran


Se subieron los cambios al repositorio remoto:

git push origin master

7.2 Unión de la rama JuanGil a master

Posteriormente, Juan Gil realizó el mismo procedimiento:

git checkout master
git merge JuanGil
git push origin master

8. Resultado final

Como resultado, el archivo Blancanieves.txt quedó completamente construido, integrando los aportes de ambos integrantes en un solo documento, demostrando el correcto uso de ramas, commits, push, pull, fetch y merge.

9. Conclusión

El uso de ramas permitió trabajar de forma organizada y segura, evitando conflictos y facilitando el trabajo colaborativo.
Esta práctica fortaleció los conocimientos sobre Git y GitHub, demostrando cómo se puede desarrollar un proyecto grupal de manera eficiente.
