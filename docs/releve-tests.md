# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : refaites à la main les résultats de référence de `SUJET.md`, puis comparez avec votre programme. 
Stock total : 30+45+20+50+25+18+12+22+8+10 + 240 plants
Plants gymnospermes : 10+8 = 18
Plants angiospermes : 30+45+20+50+25+18+12+22 = 222

**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action | Attendu | Obtenu | Testeur |
| --- | --- | --- | --- |
| Ajouter un plant| possible | test OK | RichmondToure |
| Lister l'inventaire | possible | test OK | RichmondToure |
| Rechercher (code, nom, groupe) | possible | test OK | RichmondToure |
| Trier (nombre de plants) | possible |test OK| RichmondToure|
| Synthèse des quantités | possible | test OK | RichmondToure|
| Supprimer un plant | possible | test OK | RichmondToure|
| Modifier un plant| possible |  test ok | RichmondToure| 

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : ✏️
Les resultats des tests sont tous conformes aux resultats attendus