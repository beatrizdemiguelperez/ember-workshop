APLICACIONES WEB CON UN HAMSTER GAFAPASTA
===================

	> ¿Por qué este workshop?
Porque empezar con un framework da mucha pereza. Pero don’t worry my friend, en menos de dos horas sabrás enfrentarte a uno de los mejores frameworks Javascript del momento.

	> ¿Qué vas a aprender?
Te contaremos por qué Ember mola tanto y cómo funciona, y haremos una aplicación web en tiempo récord.
Entenderás lo que es "The Ember Way", sus convenciones y su arquitectura. Definirás rutas, modelos, controladores y componentes.
Descubrirás [Ember CLI](https://ember-cli.com), una herramienta potente y fácil de usar con la que generar automáticamente distintas partes de tu aplicación.
Conocerás los addons de Ember y los generadores de patrones

	> ¿Qué necesito?
- Tu editor de código HTML/JS favorito
- [Node](https://nodejs.org) instalado (versión mínima recomendada 4.0) y npm (2.x)
- Git

	>  Slides:
Puedes verlas aquí: http://slides.com/beatrizdemiguelperez/deck-1


----------


Start! fork this project or just download it
-------------

1. Start up: create your ember app

> **Steps:**

> - `cd foodme` (we did `ember new foodme for you`)
> -  `npm install && bower install` (if it doesn't work, just copy node_modules and bower_components from resources folder)
> - `ember serve`

2. List restaurants from json on new route


> **Steps:**

> - `ember g route index && ember g route restaurants`
> - Redirect index to restaurants route
> - Change the Restaurant Route to use  resources/restaurants.json as the Model
> - Show restaurants list in the restaurants.hbs Template
> - Personalize the page design using resources/css
> - Go http://localhost:4000/ and see it!

3. Add translations


> **Steps:**

> - `ember install ember-i18n`
> - Add translations with `ember generate locale en && ember generate locale es`
> - Add change language dropdown with: `ember install ember-cli-sass && ember install ember-power-select`

3. Add new helper


> **Steps:**

> - `ember g helper restaurant-img`
> - copy images from resources and add restaurant img
