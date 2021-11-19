# decouverte_flutter

Flutter est un kit de développement logiciel (SDK) d'interface utilisateur open-source créé par Google. Il est utilisé pour développer des applications pour Android, iOS, Linux, Mac, Windows, Google Fuchsia et le web à partir d'une seule base de code.


## widget

Un widget est un composant visuel. Les Widgets sont organisés sous forme d’arborescence.
Un widget qui contient d’autres widgets est appelé Widget parent (ou conteneur de Widgets). Les widgets contenus dans un Widget parent sont appelés Widgets enfants.


## stateless

Un Stateless Widget est un widget qui ne dépend pas d’autre chose que de ses propres informations qui lui sont fournies au moment de son build (par son parent). Pour faire simple ce sont par exemple les widgets comme : Text, Row, Container, Column, Center…etc. Aucun événement utilisateur ne relancera le build d’un stateless widget.


## stateful

Le stateful widget va générer des “données internes” qui changeront au cours du cycle de vie de ce widget. Les données incluses dans ce type de widget forment un ensemble que l’on nomme “State”. Toute modification sur un State force le re-build du widget associé.