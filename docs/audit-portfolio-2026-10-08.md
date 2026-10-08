# Audit et organisation du portfolio
**Junior BOOTO Waba · 8 octobre 2026**

## Diagnostic et périmètre réellement vérifié
Six dépôts accessibles appartiennent au compte connecté Junior-BOOTO. Le plugin confirme les droits de lecture et d’écriture. Inventaires complets non tronqués pour les cinq dépôts non vides ; le sixième, Junior-sfile.py, est vide.

Lecture des cinq README racine existants et de 307 fichiers Markdown, scripts et requirements des deux axes. Contrôle des liens relatifs des fichiers Markdown contre les arborescences : aucun chemin absent détecté avant les modifications. Aucun doublon textuel exact détecté dans les fichiers lus des deux axes (comparaison des SHA de blobs). Ce contrôle n’est pas une comparaison sémantique des projets ni une recherche de doublons dans les PDF ou notebooks.

Points forts : deux axes déjà séparés ; projets contextualisés ; critères et corrigés ; statuts souvent honnêtes ; catalogue de phonétique ; PPTX disponible ; données synthétiques et scripts pour une démonstration à l’interface FLE/Python.

Priorités :
1. Rendre le profil et les deux pages d’accueil plus courts, avec une sélection et un parcours de navigation.
2. Distinguer support conçu, GPT documenté, expérimentation et résultat observé.
3. Documenter les environnements des trois notebooks et la provenance des données RH absentes.
4. Décider les conditions de réutilisation après vérification des droits ; aucune licence détectée dans les métadonnées des trois dépôts principaux.
5. Compléter les preuves d’usage, les liens ChatGPT, les aperçus et les attestations originales si leur publication est souhaitée.

## Organisation recommandée

| Dépôt actuel | Rôle | Décision |
| --- | --- | --- |
| Junior-BOOTO | Présentation, version anglaise, CV et documentation du portfolio | Conserver |
| portfolio-fle | Séquences, assistants, programmes, références et blog | Axe pédagogique principal |
| python.skills | Notebooks d’apprentissage et projets d’analyse | Axe Python principal ; conserver le nom pour préserver les liens |
| cours-prives-fle | Progressions FLE pour cours particuliers | Conserver ; accessible depuis le catalogue |
| cours-prives-anglais | Progressions d’anglais pour cours particuliers | Conserver comme complément |
| Junior-sfile.py | Dépôt vide | Ne pas mettre en avant ; aucune suppression ni modification de visibilité |

Les dépôts « cours-prives » sont publics : le nom ne décrit pas leur visibilité. Les PDF ont été inventoriés, mais pas audités pour leur contenu confidentiel ou leurs droits.

### Dossiers et conventions
Conserver les chemins déjà publiés. Pour les nouveaux contenus :
- portfolio-fle : projets/<theme-niveau>/, gpts-pedagogiques/<assistant>/, blog/articles/, templates/.
- Chaque nouveau projet : README.md, guide-enseignant.md, fiche-apprenant.md, evaluation.md, references.md ; dossiers assets/ et downloads/ seulement si nécessaires.
- python.skills : un dossier par projet ; scripts/, notebooks/, data/ et reports/ selon les besoins réels. Conserver les carnets historiques à leur emplacement actuel.
- Nouveaux noms : minuscules, caractères ASCII et tirets ; intitulés naturels dans les titres Markdown. Exemple : paysages-a1/fiche-apprenant.pdf.
- Statut en tête : conçu, prototype à expérimenter, expérimenté avec protocole, ou démonstrateur sur données synthétiques.

Ne pas créer un dépôt par fiche ou par assistant. La fiche courte et le projet complet sur un même thème ne sont pas présumés doublons : préciser « activité brève » et « séquence complète » dans les futurs index.

Navigation recommandée : profil → axe → sélection ou catalogue → projet → preuves et téléchargements.

### Dépôts à épingler manuellement
portfolio-fle et python.skills en premier ; cours-prives-fle en complément. Le projet phare reste un dossier du portfolio. Aucun besoin de six dépôts épinglés.

### Descriptions et sujets recommandés
Les descriptions actuelles des trois dépôts principaux ont été lues. Le plugin ne propose pas ici de modification de description ou d’épinglage ; ces changements restent manuels.

| Dépôt | Description recommandée | Sujets utiles |
| --- | --- | --- |
| Junior-BOOTO | Professeur de FLE en Colombie · conception pédagogique · progression en Python et analyse de données. | fle, instructional-design |
| portfolio-fle | Séquences FLE, évaluations, supports et assistants pédagogiques : objectifs, différenciation et preuves de conception. | fle, learning-design, language-learning |
| python.skills | Parcours Python : notebooks d’apprentissage et analyses documentées, dont un démonstrateur pédagogique sur données fictives. | python, data-analysis, pandas |

## Vérifications et limites
- Compte GitHub confirmé par le plugin ; liens internes contrôlés contre les fichiers et dossiers.
- Génération des données puis analyse FLE Learning Analytics exécutées avec succès dans l’environnement disponible. Cela vérifie le parcours de démonstration, pas tous les environnements compatibles avec les plages de dépendances.
- Script RH lu, données originales absentes ; pas de résultats RH annoncés ni validation complète d’exécution.
- Notebooks, CV, PDF et PPTX : existence confirmée ; contenu binaire et rendu non inspectés pendant cet audit.
- LinkedIn : adresse fournie par le concepteur ; tentative d’ouverture bloquée par l’accès web. Accessibilité et identité du profil non confirmées.
- Liens publics ChatGPT : non vérifiés. Les pages GitHub documentaires ne sont pas présentées comme des assistants exécutables.
- Aucun audit exhaustif des liens web externes, des images des documents binaires, des droits de tiers ou de l’historique ancien.
- Formations : pages d’inventaire lues ; attestations originales non vérifiées à nouveau. Aucun nouveau diplôme ajouté.

## Sources jointes utilisées
Les cinq PDF ont été extraits en texte et leurs passages sur historique, commits, branches, annulation et fichiers ignorés ont été consultés. Quelques caractères du guide Dridi sont mal extraits. Les recommandations de navigation et de design sont des choix de cet audit, pas des prescriptions attribuées aux livres.

- JS Mastery, Git & GitHub Handbook, date non identifiée : traçabilité et commits.
- GoalKicker, Git Notes for Professionals : historique et .gitignore.
- Sumit Jaiswal, Git Repository Management in 30 Days, BPB, 2023 : gestion et collaboration.
- Practical Git Guide, auteur/date non identifiés : commandes usuelles et annulation.
- Fondation Dridi, GitHub et Git, série Apprends et Applique, mars 2024 : dépôts, branches et commits.

Les PDF sources ne sont pas ajoutés au dépôt. Le livre BPB mentionne explicitement tous droits réservés. L’absence de licence globale sur le portfolio n’autorise pas à attribuer une licence aux supports tiers.

## Mise en œuvre
Réécriture des trois pages d’accueil ; ajout d’une version anglaise du profil, d’un catalogue conservant les liens de l’ancienne page FLE, de trois modèles de README et de cet audit. Conservation des ressources, des chemins, des CV et de l’historique. Aucun renommage, suppression ou changement de visibilité.

Les modèles comportent volontairement des champs à renseigner : ils ne constituent pas des preuves de projets réalisés.

## Étapes manuelles restantes
1. Dans le profil GitHub, utiliser « Customize your pins » pour épingler les deux axes.
2. Dans « About » de chaque dépôt, saisir la description et les sujets recommandés.
3. Tester le profil LinkedIn depuis une session accessible et retirer la réserve seulement après vérification.
4. Vérifier les droits et choisir une licence adaptée avec le titulaire des droits ; ne pas supposer que l’accès public implique une autorisation de réutilisation.
5. Ajouter les liens publics des GPT réellement disponibles, les aperçus utiles et les comptes rendus de tests.
