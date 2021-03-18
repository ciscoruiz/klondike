# klondike
Práctica sobre Rational Unified Procecss

# Domain Model

Para estudiar el modelo nos hemos basado en la documentación de la wiki (que no es todo lo clara que se podría esperar)
y en la imagen de una versión muy conocida:

![plot](./domainModel/GNOME_Aisleriot_Solitaire.png)

Las fechas indican los movimientos que estan permitidos entre los distintos grupos de cartas.

Correspondiente a los distintos montones de cartas que intervienen en el juego hemos extraído el siguiente modelo de dominio:

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
    * Valid Move Checker
    * Stock to Waste
    * Waste to Pile
    * Waste to Fundation
    * Pile to Fundation
    * Pile to Pile
    * Fundation to Pile
    * Abort

## Descripción detallada de los casos de uso

### Start Game
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/Start.puml)

### Move from Stock to Waste
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/StockToWaste.puml)

### Move from Waste to Pile
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/WasteToPile.puml)

### Move from Waste to Foundation
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/WasteToFoundation.puml)

### Move from Pile to Foundation
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/PileToFoundation.puml)

### Move from Pile to Pile
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/PileToPile.puml)

### Move from Foundation to Pile
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/FoundationToPile.puml)

### Move from Waste to Stock
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/WasteToStock.puml)

### Abort
![system overview](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/ciscoruiz/klondike/main/useCaseView/Abort.puml)




