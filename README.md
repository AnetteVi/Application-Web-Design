# Datos Personales
- Nombre: Leslye Anette Villarreal Olvera
- Matr�cula: 3063363
- Carrera: Ingenier�a en Desarrollo de Software
- Semestre: 6

# Materia
- Nombre: Dise�o de aplicaciones web
- Profesor: Aidee Soledad Aragon Cruz

# �Qu� es Markdown?
Markdown es un lenguaje de marcado ligero que permite dar formato a texto en documentos simples. 
Se usa com�nmente para documentaci�n, como los archivos README en GitHub, ya que es f�cil de leer y escribir.

# Opciones de Etiquetado en Markdown

Markdown ofrece varias herramientas para dar formato a texto. Estas son algunas de las m�s usadas:

- **Encabezados**: Se crean usando `#` al principio de una l�nea. Ejemplo:
  ```markdown
  # Encabezado Nivel 1
  ## Encabezado Nivel 2
  ### Encabezado Nivel 3

**Texto en negrita**
*Texto en cursiva*

Listas ordenadas
1. Elemento uno
2. Elemento dos
Listas no ordenadas
- Elemento uno
- Elemento dos

Enlaces: [Texto del enlace](URL)

Tablas: Usa barras verticales |
| Columna 1 | Columna 2 |
|-----------|-----------|
| Fila 1    | Fila 1    |
| Fila 2    | Fila 2    |

Bloques de c�digo: Rodea el c�digo con tres tildes invertidas (```)

# Comandos usados en Git

A continuaci�n, se describen los comandos b�sicos utilizados en Git y su prop�sito:

1. **Ver el estado del repositorio local**:
   ```bash
   git status

2. A�adir archivos al �rea de preparaci�n (stage):

Para a�adir un archivo espec�fico:git add nombre_del_archivo
Para a�adir todos los archivos:git add .

3. Crear un commit:
git commit -m "Mensaje descriptivo del commit"

4. Subir cambios al repositorio remoto:
git push origin rama

5. Crear una nueva rama:
git branch nombre_rama

6. Navegar entre ramas:
git checkout nombre_rama

7. Eliminar una rama:
git branch -d nombre_rama

8. Retroceder a un commit espec�fico:
git reset --hard hash_del_commit

9. Listar las ramas disponibles:
git branch