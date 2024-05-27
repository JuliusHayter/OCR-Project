# OCR-Project


## Contexte


Dans le cadre d’un projet d’ingestion de rapport d’inspection d’infrastructures et plus généralement de numérisation de documents sous formats hétéroclites, maîtriser les outils et techniques d’OCR est essentiel. C’est la première brique nécessaire à l’élaboration de pipeline d’analyse IA comme dans le cas d’intégration via LLM.


## Objectif 

L'objectif de ce projet est d'expérimenter des techniques d'OCR (optical character recognition) pour retrouver du texte sur une image au format PNG (cf Genova.png)

Pour chaque élément de texte trouvé, on donnera le texte en question, les coordonnées de ce champ de texte et le taux de confiance associé. 

Un champ de texte sera assimilé à un rectangle, on retrouvera donc 4 coordonnées, les x et y de chaque angle du rectangle fictif dans lequel se trouve le texte.