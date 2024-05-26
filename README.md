# OCR-Project


## Contexte


Dans le cadre d’un projet d’ingestion de rapport d’inspection d’infrastructures et plus généralement de numérisation de documents sous formats hétéroclites, maîtriser les outils et techniques d’OCR est essentiel. C’est la première brique nécessaire à l’élaboration de pipeline d’analyse IA comme dans le cas d’intégration via LLM.


## Objectif 

L'objectif de ce projet est d'expérimenter des techniques d'OCR (optical character recognition) pour retrouver du texte sur une image au format png (cf Genova.png)

Pour chaque élément de texte trouvé, on donnera le texte en question, les coordonnées de ce champ de texte et le taux de confiance associé. 

Un champ de texte sera assimilé à un rectangle, les coordonées seront donc de la forme (x1,y1), (x2,y2), avec (x1,y1) les coordonnées du coin supérieur gauche du rectangle et (x2,y2) les coordonnées du coin inférieur droit.