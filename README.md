# Datos del estudiante
**Nombre:** Angel David Barrios Díaz  
**Matrícula:** 2978194  
**Carrera:** IDS  


# Datos de la materia
**Materia:** Diseño de Aplicaciones Web  
**Profesor:** Luis Fernando Villafaña Rejón

# ¿Qué es Markdown?
Markdown es un lenguaje de marcado simple utilizado para dar formato a texto mediante símbolos especiales.  
Permite crear documentos claros, organizados y compatibles con plataformas como GitHub.

---

# Sección: Opciones de etiquetado en Markdown

## 1. Encabezados
# Título 1
## Título 2
### Título 3

## 2. Negritas
**Texto en negritas**

## 3. Cursivas
*Texto en cursivas*

## 4. Listas numeradas
1. Primer punto
2. Segundo punto

## 5. Listas con viñetas
- Elemento 1
- Elemento 2

## 6. Citas
> Esto es una cita

## 7. Código en línea
`console.log("Hola");`

## 8. Bloques de código
```python
print("Hola mundo")
```

## 9. Tablas
| Nombre | Edad |
|--------|------|
| Angel  | 21   |

## 10. Imágenes
Para insertar imágenes en Markdown se usa la sintaxis:

![Texto alternativo](Tecmilenio.png)

Ejemplo usando el archivo Tecmilenio.png incluido en la carpeta del proyecto:

![Logo Tecmilenio](Tecmilenio.png)

---

# Sección: Comandos utilizados en Git

## 1. Revisar el estado del repositorio
```
git status
```

## 2. Agregar archivos al Stage
Agregar un archivo específico:
```
git add archivo.txt
```

Agregar todos los archivos:
```
git add .
```

## 3. Crear commits
```
git commit -m "Mensaje del commit"
```

## 4. Subir cambios
Primer push:
```
git push -u origin main
```

Push posteriores:
```
git push
```

## 5. Crear, cambiar y eliminar ramas
Crear:
```
git branch nombre_rama
```

Cambiar:
```
git checkout nombre_rama
```

Crear y cambiar:
```
git checkout -b nueva_rama
```

Eliminar:
```
git branch -d nombre_rama
```

## 6. Retroceder a un commit específico
Ver historial:
```
git log
```

Cambiar a commit anterior:
```
git checkout ID_del_commit
```

Revertir un commit manteniendo la rama:
```
git revert ID_del_commit
```
