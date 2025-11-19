\# Datos del estudiante

\*\*Nombre:\*\* Angel David Barrios Díaz  

\*\*Matrícula:\*\* 2978194  

\*\*Carrera:\*\* IDS  

\*\*Semestre:\*\* (tu semestre)



\# Datos de la materia

\*\*Materia:\*\* Diseño de Aplicaciones Web  

\*\*Profesor:\*\* (nombre del profesor)



\# ¿Qué es Markdown?

Markdown es un lenguaje de marcado simple y fácil de usar para dar formato a texto. Permite crear títulos, listas, tablas y documentación de forma clara. GitHub lo utiliza para documentar proyectos.



---



\# Sección: Opciones de etiquetado en Markdown



Markdown permite dar formato fácilmente al texto usando símbolos especiales. Aquí están algunas de las opciones más usadas, con ejemplos.



\## 1. Encabezados



&nbsp;   # Título 1

&nbsp;   ## Título 2

&nbsp;   ### Título 3



\## 2. Negritas



&nbsp;   \*\*Texto en negritas\*\*



\## 3. Cursivas



&nbsp;   \*Texto en cursivas\*



\## 4. Listas numeradas



&nbsp;   1. Primer punto

&nbsp;   2. Segundo punto



\## 5. Listas con viñetas



&nbsp;   - Elemento 1

&nbsp;   - Elemento 2



\## 6. Citas



&nbsp;   > Esto es una cita



\## 7. Código en línea



&nbsp;   `console.log("Hola");`



\## 8. Bloques de código



&nbsp;   ```python

&nbsp;   print("Hola mundo")

&nbsp;   ```



\## 9. Tablas



&nbsp;   | Nombre | Edad |

&nbsp;   |--------|------|

&nbsp;   | Angel  | 21   |



\## 10. Imágenes



Para insertar imágenes en Markdown se usa la siguiente sintaxis:



&nbsp;   !\[Texto alternativo](ruta/imagen.png)



Ejemplo usando una imagen ubicada en la misma carpeta del proyecto:



&nbsp;   !\[Logo Tecmilenio](Tecmilenio.png)



---



\# Sección: Comandos utilizados en Git



A continuación se listan los comandos principales usados en Git para esta actividad y como referencia futura.



\## 1. Revisar el estado del repositorio



&nbsp;   git status



\## 2. Agregar archivos al área de preparación (Stage)



Agregar un archivo específico:



&nbsp;   git add archivo.txt



Agregar todos los archivos modificados:



&nbsp;   git add .



\## 3. Crear commits con comentarios



&nbsp;   git commit -m "Mensaje del commit"



\## 4. Subir los cambios al repositorio remoto



Primer push (cuando se configura la rama):



&nbsp;   git push -u origin main



Push en commits posteriores:



&nbsp;   git push



\## 5. Crear, cambiar y eliminar ramas



Crear una rama:



&nbsp;   git branch nombre\_rama



Cambiar a una rama existente:



&nbsp;   git checkout nombre\_rama



Crear una rama y cambiar a ella en un solo paso:



&nbsp;   git checkout -b nueva\_rama



Eliminar una rama:



&nbsp;   git branch -d nombre\_rama



\## 6. Retroceder a un commit específico



Ver historial de commits:



&nbsp;   git log



Cambiar temporalmente a un commit anterior:



&nbsp;   git checkout ID\_del\_commit



Revertir un commit manteniendo la rama actual:



&nbsp;   git revert ID\_del\_commit



