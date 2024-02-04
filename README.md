# Algunos ejercicios para practicar expresiones regulares
Los haremos con javascript aunque en php u otros lenguajes serían similares
## JavaScript:
JavaScript ofrece una amplia gama de métodos y funciones para trabajar con expresiones regulares.
Vamos a trabajar con tres métodos test(), match(), replace() :


1. Búsqueda de coincidencias:

Método test(): 
Devuelve true si se encuentra una coincidencia en la cadena. ¡

/^[a-zA-Z]+$/.test('Hola').


2. Método match(): 
Devuelve una matriz con todas las coincidencias en la cadena. 
Hola Mundo'.match(/^[a-zA-Z]+$/).

3. Reemplazo de texto:

Método replace():
 Reemplaza todas las coincidencias con un texto especificado. 
'Hola Mundo'.replace(/^[a-zA-Z]+$/, 'Hola').



