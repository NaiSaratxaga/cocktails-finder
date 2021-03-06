# Hola 馃憢馃徑, soy Naiara

**Y este es mi ejercicio de evaluaci贸n final de JavaScript**

- El ejercicio consiste en desarrollar una aplicaci贸n web que contiene un listado de las bebidas y c贸teles de todo el mundo, que nos permite des/marcar las bebidas como favoritas y guardarlas en local storage.
- El ejercicio tambi茅n tiene una parte de maquetaci贸n con HTML y Sass.

1. **Realizar estructura b谩sica sobre el modelo que nos proporcionan**

   - La aplicaci贸n de b煤squeda de c贸cteles consta de dos partes:
     _Un campo de texto y un bot贸n para buscar un c贸ctel por su t铆tulo_
     _Un listado de resultados de b煤sueda donde aparece la imagen del c贸ctel y el nombre._

2. **B煤squeda**

   - Al hacer click sobre el bot贸n Buscar, la aplicaci贸n debe conectarse al API abierto de TheCocktailDB.
   - Para construir la URL de b煤squeda hay que recoger el texto que ha introducido la usuaria en el
     campo de b煤squeda.
   - Por cada c贸ctel contenido en el resultado de la b煤squeda hay que pintar una tarjeta donde
     mostramos una imagen del c贸ctel y el nombre.
   - Algunas de los c贸cteles que devuelve el API no tienen imagen. En ese caso hay que mostrar una
     imagen de relleno.
   - Para pintar la informaci贸n en la p谩gina se puede elegir entre hacerlo de forma b谩sica con innerHTML
     o manipulando de forma avanzada el DOM.

3. **Favoritos**
   Una vez aparecen los resultados de b煤squeda, la usuaria puede indicar cu谩les son nuestros c贸cteles
   favoritos. Para ello, al hacer clic sobre una c贸ctel debe pasar lo siguiente:

   - El color de fondo y el de fuente se intercambian, indicando que es un c贸ctel favorito.
   - Hay que mostrar un listado en la parte izquierda de la pantalla, debajo del formulario de b煤squeda,
     con los c贸cteles favoritos. Os recomendamos crear un variable o constante de tipo array en JS para
     almacenar los c贸cteles favoritos.
   - Los c贸cteles favoritos deben seguir apareciendo a la izquierda aunque la usuaria realice otra b煤squeda.

4. **Almacenamiento local**

   - Hay que almacenar el listado de favoritos en el localStorage. De esta forma, al recargar la p谩gina el listado
     de favoritos se debe mostrarse.

5. **BONUS**

- Borrar favoritos

6. **BONUS**

- Afinar la maquetaci贸n

# Donde se puede ver 馃憖

http://beta.adalab.es/modulo-2-evaluacion-final-NaiSaratxaga/

# Este proyecto ha sido desarrollado con:

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> </a> <a href="https://sass-lang.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a> </p>

Tambi茅n se ha utilizado el Starter Kit de Aadalab, el cual incluye un motor de plantillas HTML, el preprocesador SASS y un servidor local.

# Gu铆a para arrancar el proyecto

> **NOTA:** Necesitas tener instalado [Node JS](https://nodejs.org/) para trabajar con este Starter Kit.

**Pasos a seguir :**

1. _Clonar este repositorio_
2. _Abrir una terminal en la carpeta ra铆z del repositorio_
3. _Instalar las dependencias locales ejecutando en la terminal el comando:_

```bash
npm install
```

**Arrancar el proyecto con el comando**

```bash
npm start
```

**Para generar la p谩gina**

```bash
npm run docs
```

Autora: <nsaratxaga@gmail.com>
