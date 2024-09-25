# formation-a11y

- Checklist pour la qualité d'une page web :  
  https://checklists.opquast.com/fr/assurance-qualite-web
- RGAA Luxembourg  
  https://accessibilite.public.lu/fr/raweb1/index.html
- Texte : Ne jamais utiliser `justify` sinon problème avec les dyslexiques
- Pour gérer les tailles de texte, préférer em
  - La taille de texte em est proportionnelle à la taille de texte de l'élément parent
  - exemple : les navigateurs ont une taille de texte de 16px par défaut  
    => 1em = 16px  
    Si on change la taille de texte de `<main>` par exemple à 20px,  
    tous les éléments enfants de main auront 1em = 20px
  - rem est toujours proportionnel à la taille par défaut de l'appareil
    donc 1rem = 16px dans les navigateurs en permanence
    Et sur une télévision par exemple 1rem peut être égal à 24px
- Meilleure article d'explication de flexbox :  
  https://www.joshwcomeau.com/css/interactive-guide-to-flexbox/
- Télécharger le logiciel Colour Contrast Analyser (CCA) pour analyser le contraste de la page  
  https://www.tpgi.com/color-contrast-checker/  
  Score demandé en AA : 4,5  
  Score demandé en AAA : 9
- `line-height` recommandé : 1.5 (Critère AAA)
- `font-weight` :  
  100 très fin  
  400 normal  
  800/900 bold  
- texte souligné : conserver `uniquement` pour les liens  
  (ne pas frustrer les utilisateurs avec du texte souligné qui n'est pas un lien)
- `font-family` : éviter des fonts spéciales, préférer fonts déjà installées comme Arial  
  Temesis a créé une font spécifique pour les dyslexiques  
  (Luciole-Regular, gadget selon notre formateur Jonathan Pansiot)
- Mythe à propos de la dyslexie  
  https://www.linkedin.com/pulse/dyslexic-myths-presented-truths-gareth-ford-williams/
- `img` a un `display: inline` par défaut, donc modifier pour `display: block` pour centrer etc
- les gens dézooment parce qu'ils ont une vision périphérique restreinte (ce n'est pas une erreur)
- conférence sur l'em  
  https://www.paris-web.fr/2013/conference/un-petit-pas-pour-lem-un-grand-pas-pour-le-web
- font-size pour l'accessibilité : `font-size: 62.5%;`
- 30em en moyenne
- Convertisseur px vers em : https://pxtoem.com.au
- gris minimum comme fond rgb(76,76,76) et rgb(89,89,89)
- background-color : critère 10.5 en RGAA couleur de fond et une couleur pour le texte pour le body
- button peut être activé par space ou enter  
- :nth Tester CSS Tricks (https://css-tricks.com/examples/nth-child-tester/)  
- pseudo class = même poids que class
- media query 2024 : https://caniuse.com/css-media-range-syntax
- En accessibilité, on veut gérer minimum avec une width 320px
- Gérer zoom homothétique + zoom texte (un des deux convient pour l'accessibilité maos préférer zoom texte)
- une petite image = 20px
- padding sur element absolute pour laisser marge
- Ne jamais utiliser height
- Un élément dans un flux flexbox est stretch par défaut
- flex-basis = max-width
- display none = élément sort du DOM, visibility hidden = élément aussi caché mais garde la taille de l'élément
- animations ne doivent pas dépasser 5 secondes
- toujours mettre un background-color et color sur body
