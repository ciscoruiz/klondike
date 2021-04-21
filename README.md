# klondike
Práctica sobre Rational Unified Procecss

# Domain Model

Para estudiar el modelo nos hemos basado en la documentación de la wiki (que no es todo lo clara que se podría esperar)
y en la imagen de una versión muy conocida:

![plot](./requirements/domainModel/GNOME_Aisleriot_Solitaire.png)

Las fechas indican los movimientos que estan permitidos entre los distintos grupos de cartas.

Correspondiente a los distintos montones de cartas que intervienen en el juego hemos extraído el siguiente modelo de dominio:

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/domainModel/entities.puml)

# Actors

![plot](./requirements/actor/Actor.png)

# Use Cases

Los casos de uso que hemos detectado son los siguientes:

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/requirements/useCaseView/usecases.puml)

El siguiente diagrama muestra un diagrama de estado general:

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/requirements/useCaseView/state-diagram.puml)

## Priorización de casos de uso
    * Start Game
    * Move Stock to Waste
    * Move Waste to Pile
    * Move Waste to Fundation
    * Move Pile to Fundation
    * Move Pile to Pile
    * Move Fundation to Pile
    * Show Game
    * Abort Game



