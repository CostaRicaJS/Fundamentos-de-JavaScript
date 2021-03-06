# Guía para contribuciones

Más que felices de aceptar contribuciones externas al proyecto en forma de retroalimentación, informes de errores o incluso mejor - pull requests :)

Útilizamos Kanban con Waffle.io para visualizar el progreso y manejar prioridades del proyecto  
visita https://waffle.io/CostaRicaJS/Fundamentos-de-JavaScript/join   
En la columna "listo" encontrarás todos las tareas que están listas para ser desarrolladas.

## Presentación de propuestas y reporte de errores

Antes de presentar su propuesta por favor utilizar la función de búsqueda el [issue tracker](https://github.com/CostaRicaJS/Fundamentos-de-JavaScript/issues) para asegurarse de que no se haya ya reportado el error y no se haya conversado ya al respecto.

### Publicación de Contenido en el Libro

Aportes no triviales a el contenido se conversan primero en el [issue tracker](https://github.com/CostaRicaJS/Fundamentos-de-JavaScript/issues). Luego para publicar contenido se realiza un Pull Requests y estos son revisados y aprobados por los mantenedores y otros miembros de la comunidad.

## Pull Requests

Para realizar pull request por favor seguir las siguientes indicaciones

* Asegurarse de que hay no hay pull requests existentes que intentan abordar el tema.
* Comprobar si hay discusiones relacionadas con el tema en el [issue tracker](https://github.com/CostaRicaJS/Fundamentos-de-JavaScript/issues).
* Nuevas categorías o mejoras a la categorización existente son bienvenidas.
* Cambios no triviales deben ser discutidos en un issue primero.  
* Crear un pull request por sugerencia siguiendo el [github flow](https://guides.github.com/introduction/flow/).
* Desarrollar en una rama específica, no en master.
* Seguir la [guía de estilo de airbnb](https://github.com/airbnb/javascript).
* Siempre correr `npm test` antes de crear un pull request.  
* Conectar el PR a issue abierto con el keywork `connects to #XX` en la descripción del PR. más info http://bit.ly/1k58aWF   
* Siempre correr `npm run spellcheck` para verificar que no hay errores ortográficos.
* Pull Request y Commits debe tener un título útil.
* Haz squash de tus commits, 1 commit por cambio lógico.

Recomedamos usar [hub](http://hub.github.com) y [git-extras](https://github.com/tj/git-extras) para interactuar con github.

Ejemplos de __buenos mensajes__ en commits:
- agrega sección hoisting
- actualiza ejemplo en patrón singleton
- corrige intro a programación funcional
- cambia título en sección ámbito

## Como mantenedor del proyecto

- Usar [hub](http://hub.github.com) y [git-extras](https://github.com/tj/git-extras) para interactuar con github.
- No utilizar el botón _merge pull request_ en el UI de github. Utilizar hub para hacer merges. Esto evita ensuciar el commit log y permite mas flexibilidad. [Más detalles](http://blog.spreedly.com/2014/06/24/merge-pull-request-considered-harmful/).

# Correr el libro en ambiente local
```
npm install
npm start
```
recomendamos utilizar [avn y nvm para manejar las versiones de nodejs](http://gaboesquivel.com/blog/2015/automatic-node-dot-js-version-switching/)   
más recursos para trabajar con Gitbooks en https://github.com/GitbookIO

# Chat
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/CostaRicaJS/Fundamentos-de-JavaScript?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
