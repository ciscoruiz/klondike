# klondike
Práctica sobre Rational Unified Procecss

# Domain Model

Para estudiar el modelo nos hemos basado en la documentación de la wiki (que no es todo lo clara que se podría esperar)
y en la imagen de una versión muy conocida:

![plot](./domainModel/GNOME_Aisleriot_Solitaire.png)

Las fechas indican los movimientos que estan permitidos entre los distintos grupos de cartas.

Correspondiente a los distintos montones de cartas que intervienen en el juego hemos extraído el siguiente diagrama
de clases:

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/domainModel/entities.puml)

# Actors

![plot](./actor/Actor.png)

# Use Cases

Los casos de uso que hemos detectado son los siguientes:

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/usecases.puml)

El siguiente diagrama muestra un diagrama de estado general:

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/state-diagram.puml)

## Priorización de casos de uso
    * Start
    * Stock to Waste
    * Waste to Pile
    * Waste to Fundation
    * Pile to Fundation
    * Pile to Pile
    * Fundation to Pile
    * Abort

## Descripción detallada de los casos de uso

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/Start.puml)

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/StockToWaste.puml)

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/WasteToPile.puml)

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/WasteToFoundation.puml)

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/PileToFoundation.puml)

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/PileToPile.puml)

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/FoundationToPile.puml)

![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/Abort.puml)




