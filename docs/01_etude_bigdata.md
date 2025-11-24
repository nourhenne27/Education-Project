📘 Étude : Collecte & Stockage des données dans le domaine de l’Éducation (Avant et Après l’apparition du Big Data)
⭐ Introduction

Le domaine de l’éducation génère des données depuis toujours : informations sur les étudiants, cours, examens, enseignants, notes, absences, etc.
Cependant, la manière de collecter, stocker et analyser ces données a fortement changé avec l’arrivée du Big Data.

Le dataset CollegeDatabase choisi sur Kaggle illustre cette évolution : il contient plusieurs tables représentant un modèle éducatif moderne utilisé pour l’analyse et l’aide à la décision.

⭐ 2. Collecte & Stockage des données AVANT le Big Data
2.1 Collecte des données (Avant)

Avant l’apparition du Big Data, la collecte était limitée et manuelle.

✔ Collecte manuelle

Formulaires papier

Registres de présence

Cahiers de notes des enseignants

Examens corrigés à la main

Inscription administrative papier

Pas de données comportementales (uniquement administratives)

✔ Peu de données collectées

Volume très faible

Données simples : nom, prénom, cours, notes, présence

Impossible de suivre les interactions quotidiennes

Pas de données en temps réel

2.2 Stockage des données (Avant)
✔ Stockage physique

Armoires remplies de dossiers

Archives papier

Risques de perte, erreurs, lenteur

✔ Premières bases numériques (mais limitées)

Excel

Access

Quelques petites bases SQL

Pas de centralisation → chaque service avait ses propres fichiers

✔ Limites majeures

Recherche difficile

Pas de suivi en temps réel

Analyses impossibles (faible volume, faible variété)

⭐ 3. Collecte & Stockage des données APRÈS le Big Data
3.1 Collecte des données (Après)
✔ Collecte numérique et automatique

LMS : Moodle, Google Classroom, Microsoft Teams

Plateformes e-learning : Coursera, Udemy

Applications mobiles éducatives

Portails étudiants

Examens en ligne, quiz interactifs

Présence via QR code ou carte RFID

Participation dans les forums

✔ Collecte massive et variée (3V du Big Data)

Volume : logs, vidéos de cours, interactions

Variété : texte, audio, vidéos, clics, activités

Vélocité : collecte en temps réel

✔ Données comportementales (nouveauté)

Temps passé sur les cours

Nombre de tentatives de quiz

Messages envoyés

Engagement

Détection du risque d’échec

3.2 Stockage des données (Après)
✔ Stockage distribué et scalable

Hadoop HDFS

Data Lakes

Data Warehouses modernes

Clusters distribués

✔ Cloud storage

Google Cloud Storage

AWS S3

Azure Data Lake
➜ Permet de stocker plusieurs pétaoctets

✔ Bases NoSQL

MongoDB

Cassandra

Firebase

✔ Avantages majeurs

Centralisation

Accès rapide aux données

Analyses avancées : dashboards, IA, machine learning

Suivi personnalisé des étudiants

⭐ 4. Tableau comparatif : Avant vs Après Big Data

| Critère                 | Avant Big Data        | Après Big Data                    |
| ----------------------- | --------------------- | --------------------------------- |
| Méthodes de collecte    | Papier, manuel        | Automatisé, digital, temps réel   |
| Volume                  | Petit                 | Très grand                        |
| Variété                 | Données simples       | Vidéos, forums, interactions, IoT |
| Stockage                | Papier, Excel, Access | Cloud, Data Lakes, Hadoop         |
| Analyse                 | Très limitée          | IA, dashboards, ML                |
| Prise de décision       | Intuition             | Basée sur données                 |
| Suivi étudiant          | Manuel                | Complet, comportemental           |
| Dataset CollegeDatabase | Fichiers séparés      | Tables relationnelles modernes    |

⭐ 5. Conclusion

Le Big Data a profondément transformé la gestion des données éducatives.
Les établissements peuvent maintenant :

assurer un suivi personnalisé

détecter les difficultés plus tôt

améliorer la qualité de l’enseignement

prendre des décisions basées sur les données

Cette évolution ouvre la voie à une éducation plus intelligente, moderne et efficace.
