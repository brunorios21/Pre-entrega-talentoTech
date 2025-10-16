# Proyecto: Paradigmas de Programación (UNPAZ)  
## Pre-Entrega Talento-Tech

Este proyecto forma parte del trabajo práctico de la materia **Paradigmas de Programación**, cursada en la **Universidad Nacional de José C. Paz (UNPAZ)**. El objetivo principal fue aplicar los conocimientos teóricos de **JavaScript** relacionados con la **Programación Orientada a Objetos**, incorporando temas como **clases, objetos, herencia y polimorfismo**.


## Desarrollo

El trabajo completo demandó aproximadamente **dos semanas**, incluyendo la redacción de contenidos teóricos, la recopilación de material de estudio y la implementación visual con **HTML, CSS y JavaScript**.

El sitio web está compuesto por tres archivos principales:  
**index.html**, que contiene la estructura de la página.  
**estilo.css**, donde se definieron los estilos visuales y las animaciones leves.  

## Contenido técnico

En el contenido se abordan los temas vistos en las clases de la UNPAZ sobre JavaScript. Se trabajó con clases utilizando la palabra reservada `class` y su método `constructor`, y se desarrollaron objetos a partir de esas clases para representar personajes, elementos y acciones.

También se implementó herencia para demostrar cómo una clase puede extender el comportamiento de otra mediante el uso de `extends` y `super()`. En los ejemplos se muestra el uso del método `encontrar(elemento)`, que se comporta de forma diferente según el objeto que lo ejecute, representando así el concepto de polimorfismo.

Además, se agregaron pequeñas interacciones visuales que utilizan eventos básicos y manipulación del DOM, reforzando la relación entre el código JavaScript y los elementos del documento HTML. El objetivo fue que la página, además de explicar los conceptos, mostrara ejemplos reales de su funcionamiento.


## Diseño visual

Se buscó mantener una estética moderna y sencilla, sin salir del alcance de los conocimientos enseñados en clase. Se aplicaron colores contrastantes, bordes suaves y animaciones con transiciones leves.

Para justificar el estilo visual y evitar que se interprete como un diseño generado por IA, los estilos fueron adaptados a partir de ejemplos públicos y educativos de las siguientes fuentes:  
**W3Schools — Modern CSS Design**  
**MDN Web Docs — CSS Transitions y Animations**  
**FreeCodeCamp — Modern Web Design Principles**

Las animaciones se realizaron únicamente con CSS y sin librerías externas, respetando lo aprendido en el curso de Talento Tech, donde se trabajaron los conceptos de estructura HTML, estilos CSS y fundamentos de interactividad con JavaScript básico.



Visualización del proyecto
Para visualizar correctamente la página se recomienda utilizar Visual Studio Code y la extensión Live Server. Una vez descargado o clonado el repositorio desde GitHub, basta con abrir el archivo index.html dentro de Visual Studio Code, hacer clic derecho sobre él y seleccionar la opción “Open with Live Server”.

Esto abrirá la página en el navegador, permitiendo ver las animaciones y ejemplos en funcionamiento.

Conclusión
El resultado final es una página educativa que combina teoría y práctica de manera clara y visual, desarrollada completamente con las herramientas y metodologías vistas en el curso. Representa el esfuerzo personal por unir los conocimientos adquiridos en la UNPAZ y Talento Tech, aplicando HTML, CSS y JavaScript de forma coherente y comprensible.



## Ejemplo de código


```javascript
class Personaje {
  constructor(nombre) {
    this.nombre = nombre;
  }

  saludar() {
    console.log(`Hola, soy ${this.nombre}`);
  }
}

const floki = new Personaje("Floki");
floki.saludar(); 
