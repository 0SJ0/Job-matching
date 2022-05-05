Job matching est un programme qui recommandae des offres de travail  à des chercheurs d'emploi.

Pour rejouer le code, il suffit de compiler le notebook dans le dossier.

Le fichier Recommendation.csv dans data contient nos recommendations pour un groupe d'utilisateur test.

Quelques infos sur les données :



jobs.csv :
- JobID : Id de l’emploi
- JobCategoryID : Categorie du métier
- Title : Intitulé
- Description : Description du poste
- Requirements : Prérequis pour le poste
- City, State, Country, Zip5 : Informations géographiques
- StartDate, EndDate : Date de début et fin de visibilité du poste sur le site d’annonce

users.csv :
- UserID : Id du candidat
- City, State, Country, ZipCode : Informations géographiques
- DegreeType, Major, MajorCategoryID, GraduationDate : Information sur le
diplôme du candidat
- WorkHistoryCount : Nb d’expériences
- TotalYearsExperience : Expérience totale
- CurrentlyEmployed : En poste
- ManagedOthers, ManagedHowMany : Si le candidat a occupé un poste de
management et combien de managés.

users_history.csv :
- UserID : Id du candidat
- Sequence : Ordre de l’emploi occupé
- JobTitle : Intitulé de l’emploi occupé
- JobCategoryID : Categorie du métier

feedbacks.csv :
- UserID : Id du candidat
- JobID : Id de l’emploi
- Event : type d’évènement loggé : offre vue sur la plateforme (viewed), candidature
(applied), embauche (hired)

test_users.csv : Candidats de test sur lesquels faire des recommandations.

