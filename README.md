# Modèle de présentation pour les évènements de la communauté Mozilla francophone (MozFr)
Ce modèle est basé sur [reveal.js](https://github.com/hakimel/reveal.js).
##Comment ça fonctionne ?

Cet outil permet de réaliser des présentations qui peuvent être lancées depuis un navigateur. C'est du HTML, JavaScript, CSS… Bref, c'est du Web (voir ce que ça donne sur [cette page](https://mozfr.github.io/Presentation_MozFR/). Pour commencer, on aura simplement besoin de savoir écrire [du Markdown](https://fr.wikipedia.org/wiki/Markdown) et d'utiliser un éditeur de texte.

##Comment réaliser ma présentation ?

* Vous pouvez *forker* ce dépôt sur votre profil GitHub ou le récupérer sous forme d'un fichier zip en cliquant sur *Clone or download*
* Une fois les fichiers récupérés, le seul fichier qu'on aura besoin de modifier est le fichier `index.html`
* Vers la ligne 26, vous voyez `<div class="slides">`, pour chaque diapositive que vous souhaitez ajouter, il suffit de rajouter un bloc
```
    <section data-markdown>
      <script type="text/template">
        Mon contenu
      </script>
    </section>
```
* Puis d'ajouter le Markdown correspondant à votre diapositive entre les balises `script`, voici un exemple de diapositive :

```
    <section data-markdown>
      <script type="text/template">
        # Mon grand titre
          * Un élément pour une liste
          * Un autre élément
      </script>
    </section>
```

Si vous souhaitez aller plus loin, vous pouvez consulter [la documentation sur reveal.js](https://github.com/hakimel/reveal.js#configuration).
