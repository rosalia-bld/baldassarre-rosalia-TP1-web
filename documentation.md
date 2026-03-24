# DOCUMENTATION

## Planification
Pour la planification, j’ai d’abord identifié les éléments qui reviennent souvent dans la page afin de créer des composants réutilisables. Par exemple, les cartes (programmation, artistes, billets, témoignages) ont une structure similaire, tout comme les boutons. Cela permet de garder une cohérence visuelle et de faciliter les modifications.

## Architecture HTML
L’architecture HTML est divisée en plusieurs sections (nav, hero, programmation, horaire, etc.), ce qui rend le code plus clair et mieux organisé. Chaque section est indépendante, ce qui facilite la compréhension et la maintenance.

## Nomenclature BEM
J’ai utilisé la méthode BEM pour nommer mes classes (ex : nav__item, hero__btn, programmation__card). Cette approche rend le CSS plus lisible et évite les conflits entre les styles.

## Système de tokens
Un système de variables CSS a été mis en place dans :root pour les couleurs et certaines valeurs globales. Cela permet de modifier facilement le design du site tout en gardant une cohérence.
