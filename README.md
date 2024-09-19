# notes-formation-a11y

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
  Temesis a créé une font spécifique pour les dyslexiques (Luciole-Regular, gadget selon notre formateur Jonathan Pansiot)
- Mythe à propos de la dyslexie  
  https://www.linkedin.com/pulse/dyslexic-myths-presented-truths-gareth-ford-williams/
  


    
