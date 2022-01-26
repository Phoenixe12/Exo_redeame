1-Les widgets

        Un widget est une extension d’application, souvent intégrée dans une application déjà installée sur votre téléphone.

        Les widgets Flutter sont construits à l’aide d’un framework moderne qui s’inspire de React. L’idée centrale est que vous construisez votre interface utilisateur à partir de widgets. Les widgets décrivent à quoi devrait ressembler leur vue compte tenu de leur configuration et de leur état actuels . Lorsque l’état d’un widget change, le widget reconstruit sa description, que l’infrastructure différencie de la description précédente afin de déterminer les modifications minimales nécessaires dans l’arborescence de rendu sous-jacente pour passer d’un état à l’autre.

2- Les catégories de widgets en Flutter

     Dans Flutter , il existe deux principaux types de widgets : avec état  et sans état.

3- La liste de chaque catégorie

          Flutter est livré avec une suite de widgets de base puissants, dont les suivants sont couramment utilisés:

Text
Le widget vous permet de créer une série de texte stylisé dans votre application.Text

Ligne, Colonne
Ces widgets flexibles vous permettent de créer des mises en page flexibles dans les directions horizontale () et verticale (). La conception de ces objets est basée sur le modèle de mise en page flexbox du Web.RowColumn

Stack
Au lieu d’être orienté linéairement (horizontalement ou verticalement), un widget vous permet de placer des widgets les uns sur les autres dans l’ordre de peinture. Vous pouvez ensuite utiliser le widget Positionné sur les enfants d’un pour les positionner par rapport au bord supérieur, droit, inférieur ou gauche de la pile. Les piles sont basées sur le modèle de mise en page de positionnement absolu du Web.StackStack

Container
Le widget vous permet de créer un élément visuel rectangulaire. Un conteneur peut être décoré avec une BoxDecoration, telle qu’un arrière-plan, une bordure ou une ombre. A peut également avoir des marges, un rembourrage et des contraintes appliquées à sa taille. De plus, a peut -être transformé dans un espace tridimensionnel à l’aide d’une matrice.
