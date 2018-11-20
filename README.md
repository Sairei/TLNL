# TLNL
> Traitement du Langage Naturel et Linguistiquei

----
----

# Projet

Dans ce projet, on s'interesse à l'algorithme de Chu Liu Edmonds pour le traitement de la langue.

On va donc devroir créer un modèle d'appentissage sur plusieurs features, chacunes un peu plus complexe que la précédente.
- feature 1 : \[ G.0.POS\ | D.0.POS | DIST \]
- feature 2 : \[ G.0.POS | G.0.LEMMA | G.0.MORPHO | D.0.POS | D.0.LEMMA | D.0.MORPHO | DIST \]
- feature 3 : \[ G.0.POS | G.0.LEMMA | G.0.MORPHO | G.-1.POS | G.1.POS | D.0.POS | D.0.LEMMA | D.0.MORPHO | G.-1.POS | G.1.POS | DIST \]

----

### _Fichiers_

**- DONNEES :** Fichiers au format [CoNLL](http://universaldependencies.org/format.html).
Quelques compléments :
> - Parties de discours [POS](http://universaldependencies.org/u/pos/)
> - Etiquette des relations [LABEL](http://universaldependencies.org/u/dep/) et des [compléments](http://universaldependencies.org/ext-dep-index.html)
> - Mophologie des mots [MORPHO](http://universaldependencies.org/u/feat/index.html)

**- SOURCES :** Notebook au format ipynb

### _A Faire_

- [x] Lecture des fichiers CoNLL
- [x] Creation des 3 features différentes
- [ ] Modèle d'appentissage 
- [ ] Algorithme C.L.E.
