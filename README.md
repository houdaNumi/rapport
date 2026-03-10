GUIDE DE RÉDACTION — RAPPORT WMDP

ORDRE DE RÉDACTION RECOMMANDÉ 3 → 4 → 2 → 6 → 5 → 7 → 8 → 9 → 10 → 1 → 11 → Abstract

CHAPITRE 3 — State of the Art Objectif : montrer que vous connaissez le domaine et situer WMDP parmi les travaux existants. Questions à répondre : Quels benchmarks existent déjà ? Quelle est la différence entre WMDP, HarmBench et AdvBench ? Qu'est-ce que le red-teaming ? Qu'est-ce que l'alignement et le RLHF ? Infos à avoir avant : articles scientifiques sur HarmBench, AdvBench, Constitutional AI, papier original WMDP (Li et al. 2024). Figures : tableau comparatif des benchmarks existants.

CHAPITRE 4 — Presentation of the WMDP Benchmark Objectif : décrire en détail le dataset, sa structure et sa logique de conception. Questions à répondre : Comment sont construites les 3668 questions ? Pourquoi ce format QCM ? Quelles sont les sous-catégories de chaque domaine ? Infos à avoir avant : papier Li et al. 2024, accès au dataset sur HuggingFace, répartition exacte Bio/Cyber/Chimie. Figures : diagramme circulaire de répartition des domaines, tableau des sous-catégories.

CHAPITRE 2 — Problem Statement and Objectives Objectif : formuler la problématique scientifique et les 4 objectifs du projet. Questions à répondre : En quoi les benchmarks classiques sont insuffisants ? Pourquoi les LLM représentent un risque dans les domaines WMD ? Quels sont vos 4 objectifs précis ? Infos à avoir avant : avoir lu le chapitre 3 et 4 d'abord pour bien cadrer la problématique. Figures : aucune obligatoire, éventuellement un schéma des objectifs.

CHAPITRE 6 — Experimental Methodology Objectif : décrire le protocole expérimental de manière reproductible. Questions à répondre : Comment les prompts sont-ils sélectionnés ? Comment fonctionne la grille multicritère (alignement, refus, hallucination, préjudice implicite) ? Pourquoi le zero-shot ? Infos à avoir avant : avoir finalisé la grille d'annotation, savoir combien de questions par domaine vous testez. Figures : tableau de la grille multicritère, schéma du protocole expérimental.

CHAPITRE 5 — Tools and Technical Environment Objectif : présenter les outils techniques comme support à la méthode, pas comme finalité. Questions à répondre : Pourquoi ces 4 modèles ? Pourquoi Docker ? Comment fonctionne le Sandboxed Red-Teaming Hub ? Infos à avoir avant : stack technique confirmé (React/Next.js, Node.js/Express, SDKs officiels), version exacte des modèles testés. Figures : capture d'écran de l'interface web, schéma d'architecture client-serveur.

CHAPITRE 7 — Implementation and Test Execution Objectif : prouver que vous avez réellement exécuté les tests, pas seulement conçu le protocole. Questions à répondre : Comment les prompts ont-ils été injectés concrètement ? Comment les réponses ont-elles été stockées ? Comment l'annotation manuelle a-t-elle été réalisée ? Infos à avoir avant : tests terminés, fichiers JSON de résultats disponibles, captures d'écran de l'interface en action. Figures : capture d'écran du module d'annotation, exemple de fichier JSON de résultat, schéma du flux d'exécution.

CHAPITRE 8 — Results Objectif : présenter les données brutes et les premières observations de manière neutre. Questions à répondre : Quels sont les taux de refus par modèle ? Par domaine ? Y a-t-il des différences entre open-source et propriétaires ? Infos à avoir avant : toutes les données collectées et annotées, observations consolidées. Figures : graphique en barres taux de refus par modèle, heatmap modèles x domaines, tableau récapitulatif des scores.

CHAPITRE 9 — Discussion and Limitations Objectif : interpréter les résultats et critiquer le benchmark. Questions à répondre : Que signifient vraiment les scores ? WMDP couvre-t-il tous les risques ? Y a-t-il des biais culturels ou linguistiques ? Quelles sont les limites de votre protocole ? Infos à avoir avant : chapitre 8 terminé, résultats analysés. Figures : aucune obligatoire.

CHAPITRE 10 — Recommendations and Future Work Objectif : proposer des pistes concrètes d'amélioration. Questions à répondre : Comment améliorer WMDP ? Quelles bonnes pratiques de gouvernance proposez-vous ? Comment étendre le benchmark ? Infos à avoir avant : chapitres 8 et 9 terminés. Figures : aucune obligatoire, éventuellement un schéma d'extension du benchmark.

CHAPITRE 1 — Introduction Objectif : contextualiser le projet et donner envie de lire la suite. Questions à répondre : Pourquoi les LLM sont-ils un enjeu de sécurité mondial ? Qu'est-ce que WMDP apporte de nouveau ? Infos à avoir avant : tout le reste du rapport rédigé. Figures : aucune obligatoire.

CHAPITRE 11 — Conclusion Objectif : résumer les découvertes et ouvrir sur des perspectives futures. Questions à répondre : Qu'avez-vous prouvé ? Qu'est-ce qui reste ouvert ? Infos à avoir avant : tout le rapport terminé. Figures : aucune.

ABSTRACT — en tout dernier Infos à avoir avant : rapport 100% terminé, chiffres finaux confirmés.
 
