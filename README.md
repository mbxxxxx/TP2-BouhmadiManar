## Rapport du TP2 – GitHub Actions (voir rapport principale avec plus de details sur classroom)

###  Objectif
Mettre en place un workflow GitHub Actions pour une application Android afin de :
- Compiler automatiquement le projet.
- Lancer les tests unitaires.
- Vérifier le bon fonctionnement du CI/CD lors des Pull Requests.

###  Étapes réalisées
1. Création du dépôt GitHub `TP2-BouhmadiManar`.
2. Ajout du projet Android dans le dépôt.
3. Mise en place du workflow `Android-ci.yml`.
4. Ajout de l’étape des tests unitaires (`./gradlew test`).
5. Modification volontaire d’un test pour provoquer une erreur .
6. Vérification de l’échec du workflow sur GitHub.
7. Correction du test  et relance du workflow.
8. Fusion de la Pull Request dans la branche `main`.

###  Captures d’écran
- voir mon rapport sur classroom ppur plus de details et de captures d’écran

###  Résultat
Le workflow GitHub Actions fonctionne correctement :
- Il détecte les erreurs de test.
- Il valide le projet quand les tests passent.
- La Pull Request a été fusionnée avec succès.

### 📄 Rapport PDF
voir classroom
