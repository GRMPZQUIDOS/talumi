# TALUMI · तलुमि · タルミ · 塔鲁米

## Livre blanc — Traduction professionnelle et contrôle du sens par chemins indépendants

Version fondatrice enrichie — 17 octobre 2026

## Overview

Talumi est un dispositif de traduction professionnelle piloté par un traducteur humain. Il associe une traduction dont le professionnel assume les choix à un ensemble de recherches et de contrôles conduits par des modèles d’intelligence artificielle, selon des chemins séparés et initialement à l’aveugle. Ces contrôles servent à faire émerger les difficultés, à documenter les points de convergence et à identifier les passages dont les conséquences exigent une validation humaine.

L’exemple de référence est unique : traduire le Code civil italien en français. Le client commande une traduction française professionnelle. Les passages par le suédois, le coréen ou d’autres langues expressément différentes sont des instruments internes d’investigation du sens. Ils ne constituent pas un service de livraison du code dans plusieurs langues.

Le travail commence par deux branches séparées. La traductrice produit sa traduction à partir de l’original italien. Parallèlement, des modèles examinent cet original et produisent des analyses ou des traductions intermédiaires sans connaître les résultats des autres branches ni la traduction professionnelle. Une fois leurs résultats enregistrés, Talumi les confronte. Il présente au professionnel les divergences, les difficultés récurrentes et les nœuds du texte : les endroits où une erreur, même peu probable, aurait des conséquences importantes.

La traductrice exerce une double compétence : l’expérience des langues, des usages et de la vie réelle ; la compréhension du fonctionnement et des limites du processus machine. Elle arbitre les problèmes et valide les passages importants. Ses décisions alimentent une mémoire contextualisée des difficultés de traduction.

L’ambition de Talumi est d’obtenir une fiabilité supérieure à celle d’une traduction humaine réalisée sans ce dispositif et à celle d’une traduction automatisée seule. Cette supériorité constitue l’objectif mesurable du produit. Elle devra être établie par des comparaisons indépendantes, portant en priorité sur les erreurs qui changent le sens et leurs conséquences.

Le positionnement professionnel se résume ainsi : **Talumi est l’outil des traductions signées.** Un professionnel identifiable, qualifié et joignable examine les points critiques, valide une version précise et la signe. La communauté visée est d’abord celle des traducteurs, avec un ancrage européen envisagé. Le lancement recherché est un site bêta fonctionnel, accompagné d’intégrations utiles, permettant immédiatement d’essayer la méthode et de comprendre la prestation que le traducteur peut vendre.

## 1. Le problème auquel Talumi répond

Une traduction peut être fluide et néanmoins infidèle. Dans un code juridique, un changement de condition, d’exception ou de sujet peut modifier la portée d’un article sans produire de phrase manifestement incorrecte. La relecture doit donc examiner les relations exprimées par le texte, au-delà de la qualité du français.

L’expertise humaine permet de comprendre ces relations, mais l’attention et le temps disponibles restent limités. Une relecture exhaustive ne garantit pas à elle seule que chaque difficulté sera reconnue. À l’inverse, un système automatique peut multiplier les contrôles tout en répétant une interprétation erronée avec assurance.

Talumi organise leur complémentarité : une investigation automatisée étendue, des éléments vérifiables et une décision professionnelle. Il cherche à rendre le travail de contrôle plus efficace en distinguant ce qui est douteux, ce qui est important et ce qui est déjà documenté.

## 2. Une traduction unique et des chemins de contrôle multiples

Le dossier de travail contient un original italien de référence et une traduction française professionnelle. La version de l’original, sa date, sa provenance et son périmètre sont fixés avant le traitement. Pour un code, les articles, alinéas, titres et renvois conservent des identifiants stables.

Les chemins linguistiques peuvent notamment comprendre :

- italien → analyse directe du sens ;
- italien → français, pour une contre-version interne de comparaison ;
- italien → suédois → français ;
- italien → coréen → français ;
- d’autres langues choisies selon les distinctions qu’elles peuvent faire apparaître et les capacités des modèles disponibles.

Sept langues constituent une hypothèse initiale de travail, et non une garantie de qualité ni un nombre imposé à tous les dossiers. Leur choix devra être testé. Une langue éloignée de l’italien peut révéler une difficulté, mais elle peut aussi introduire une perte supplémentaire. La distance linguistique est un moyen d’exploration, pas un certificat de fiabilité.

Les versions intermédiaires restent des pièces de contrôle. La version livrée au client est celle que la traductrice a élaborée, corrigée et validée. Aucun vote entre sorties de modèles ne la remplace automatiquement.

## 3. Le principe méthodologique

### 3.1 Des chemins indépendants à l’aveugle

Le terme retenu est « contrôle par chemins indépendants à l’aveugle ». Chaque branche travaille sans accès aux conclusions des autres. Elle reçoit le texte source nécessaire et les consignes prévues pour sa tâche, puis dépose un résultat figé avant la confrontation.

Dans un chemin italien → coréen → français, la seconde étape reçoit nécessairement la sortie coréenne de la première. L’aveuglement porte sur les autres chemins et sur la traduction professionnelle : il ne supprime pas les dépendances internes au chemin.

Le système d’orchestration contrôle les entrées, les accès et l’ordre des opérations. L’indépendance est organisée par le logiciel ; elle ne repose pas sur une promesse formulée par un modèle. La branche humaine initiale est également enregistrée avant que la traductrice consulte les contre-versions, afin de conserver une lecture professionnelle qui n’a pas été orientée par elles.

### 3.2 Un examen contradictoire après les analyses

La confrontation intervient ensuite. Le terme « contradictoire » désigne ici la mise à l’épreuve d’une interprétation par d’autres lectures et par le texte original. Il s’agit d’une méthode de contrôle, sans assimilation à une procédure judiciaire.

La confrontation recherche les désaccords, mais aussi les accords fragiles : plusieurs sorties peuvent reproduire la même erreur. Des modèles distincts peuvent partager des données d’entraînement ou des habitudes d’interprétation. Des appels réellement séparés ne garantissent donc pas des erreurs statistiquement indépendantes.

Toute résolution revient au passage italien, à son contexte et, lorsque nécessaire, à des références documentées. Le consensus entre versions est un indice ; la justification de la décision reste nécessaire.

## 4. Les recherches et contrôles successifs

### Recherche 1 — Définir le but et l’usage du texte

Le professionnel précise le destinataire, l’usage attendu, le domaine, la juridiction et les conséquences possibles d’une erreur. Pour l’exemple du Code civil italien, traduire le droit italien en français ne signifie pas adapter ce droit au droit français. Un terme français apparemment familier peut évoquer une institution différente : cette proximité doit être examinée.

### Recherche 2 — Cartographier la structure et les données

Talumi repère les articles, définitions, listes, conditions, exceptions, délais, montants et références internes. Il contrôle l’intégrité de l’extraction et l’alignement entre source et traduction. Un passage absent ou un renvoi déplacé doit rester visible indépendamment de toute appréciation linguistique.

### Recherche 3 — Identifier les notions sensibles

Des analyses séparées recherchent les termes polysémiques, concepts propres à un système juridique, usages historiques, expressions figées et dépendances au contexte. Chaque difficulté est localisée et expliquée. Le système distingue une difficulté déjà connue d’une nouvelle question à instruire.

### Recherche 4 — Explorer les chemins linguistiques

Les branches produisent leurs résultats sans consulter les autres. Les langues sont choisies pour diversifier les lectures et mettre certaines distinctions à l’épreuve. La capacité réelle du modèle dans chaque langue est prise en compte : une langue moins bien maîtrisée peut produire davantage de bruit que d’information utile.

### Recherche 5 — Examiner les étapes intermédiaires

Une traduction finale française correcte en apparence peut masquer une perte dans une étape intermédiaire. Talumi conserve donc les sorties à chaque étape et organise leur contrôle par des évaluateurs distincts, avec recours à une compétence linguistique humaine lorsque le problème ne peut être résolu autrement. Une note automatique de qualité reste une estimation.

### Recherche 6 — Comparer les relations de sens

La comparaison porte notamment sur les personnes concernées, les actions, les obligations, les permissions, les interdictions, les conditions, les exceptions et les effets dans le temps. Elle distingue les différences de formulation des différences de portée. Les passages concernés sont présentés avec des extraits précis, sans produire une simple moyenne des versions.

### Recherche 7 — Rechercher les références utiles

Les notions litigieuses peuvent nécessiter la consultation de définitions, de sources institutionnelles, de glossaires ou de précédents validés. Chaque référence conserve sa provenance, sa date et son domaine d’application. Une suggestion de source par un modèle n’est utilisable qu’après vérification de son existence et de son contenu pertinent.

### Recherche 8 — Déterminer les nœuds et leur importance

Une analyse du texte source identifie les passages qui demandent une validation humaine en raison de leurs conséquences, même sans désaccord détecté. Cette analyse est distincte de la recherche d’erreurs : un passage peut être stable entre toutes les branches et rester critique.

### Recherche 9 — Soumettre les points à la décision humaine

La traductrice reçoit un dossier ordonné : passage source, traduction professionnelle, éléments concordants ou divergents, références, enjeu et question à résoudre. Elle peut maintenir sa traduction, la modifier, demander une investigation ou solliciter un spécialiste. Chaque décision est motivée et enregistrée.

### Recherche 10 — Contrôler la version finale

Les corrections sont suivies d’un contrôle de cohérence dans l’ensemble du document. Un choix terminologique peut affecter plusieurs articles ; une correction locale peut modifier un renvoi ou une définition. Talumi conserve aussi les points restés ouverts, sans les transformer en validations implicites.

## 5. Un même problème signalé par plusieurs chemins

**Si une même question apparaît dans l’examen de l’italien et dans le chemin passant par le coréen, les deux signalements sont conservés et explicitement notifiés.**

L’interface les rassemble dans un dossier commun tout en maintenant leur provenance :

| Élément | Exemple de présentation |
|---|---|
| Question commune | La condition porte-t-elle sur toute l’obligation ou sur une seule de ses composantes ? |
| Signalement 1 | Analyse du texte italien : portée de la condition à vérifier |
| Signalement 2 | Chemin italien → coréen → français : interprétation différente de cette portée |
| Statut | Question signalée deux fois ; décision humaine attendue |

Cet exemple décrit une situation hypothétique et ne cite aucun article réel du code. Les deux occurrences augmentent la visibilité de la question. Elles ne sont pas présentées comme deux preuves indépendantes d’une erreur. Le système indique aussi si les branches utilisent le même modèle ou une étape commune.

Un signalement isolé demeure consultable. Il peut être le seul à avoir révélé une difficulté réelle ; la majorité ne doit pas l’effacer.

## 6. Les nœuds du texte et l’échelle des conséquences

Un nœud est un passage où le sens, la structure ou les conséquences du texte justifient une attention particulière. Deux dimensions restent séparées : l’incertitude détectée et la gravité possible d’une erreur.

| Conséquence possible | Peu d’incertitude détectée | Incertitude importante |
|---|---|---|
| Faible | Contrôle par échantillonnage selon le protocole | Vérification ciblée |
| Significative | Contrôle renforcé selon l’usage | Vérification humaine prioritaire |
| Critique | Validation humaine systématique | Validation approfondie, avec expertise complémentaire si nécessaire |

Cette grille constitue un point de départ à calibrer. La priorité tient compte des conséquences, de l’étendue des effets et de la difficulté à découvrir l’erreur après livraison. Elle ne se réduit pas à un score de confiance du modèle.

### Dans le Code civil italien

Les contrôles portent particulièrement sur les dispositions qui attribuent ou retirent des droits, imposent une obligation, organisent une responsabilité, fixent une condition ou un délai, ou introduisent une exception. Leur importance dépend de leur effet et de leurs liens avec le reste du code. Une courte définition ou un détail apparent peut gouverner de nombreux articles et devenir critique.

### Dans un plan destiné à construire une tour

Le même principe conduirait à souligner les dimensions, unités, charges, tolérances, signes, valeurs numériques et références techniques. Ces données recevraient un double contrôle : fidélité entre source et traduction, puis vérification par le professionnel compétent selon l’usage. Vérifier la traduction d’une valeur ne certifie pas le calcul de structure qui l’a produite.

### Dans un texte courant

« La petite maison avait un toit rouge et le ciel était bleu » reçoit généralement une faible priorité. Dans un témoignage où la couleur identifie un bâtiment, elle peut devenir importante. La classification dépend donc du but du texte autant que des mots employés.

### Le double check — vérifier ce qui doit absolument être juste

**Talumi signale ce qui semble faux et fait vérifier ce qui doit absolument être juste.** Deux motifs déclenchent donc un contrôle : une incertitude sur la fidélité et l’importance du passage pour l’usage du document. Un passage apparemment fidèle peut exiger une confirmation humaine systématique. Le double check est une procédure de validation, même lorsqu’elle ne conduit à aucune correction.

Le protocole de mission détermine les catégories à vérifier : obligations, exceptions, responsabilités, délais, montants, unités ou consignes de sécurité. L’IA propose leur repérage à partir du texte source et de son contexte ; le traducteur peut ajouter les points oubliés ou revoir leur importance. La qualité du repérage des points critiques doit elle-même être évaluée.

Chaque point présente ensemble l’original, la traduction, le contexte et une question explicite, par exemple : « Le plafond de responsabilité est-il identique dans les deux versions, avec les mêmes conditions et exceptions ? » Les actions proposées sont valider, corriger et demander une clarification. Une correction entraîne le réexamen du passage concerné.

#### États de contrôle dans l’interface

- **Orange — doute détecté** : une possible différence de sens doit être examinée.
- **Bleu — double check obligatoire** : le passage est important, même sans erreur soupçonnée.
- **Vert — validé** : une décision a été enregistrée pour cette version.

Les couleurs sont toujours accompagnées de libellés accessibles. Le motif, la priorité et le statut restent des informations distinctes : un point validé conserve la raison de son contrôle initial. Le protocole peut empêcher la clôture de la mission tant qu’un point obligatoire reste ouvert.

#### Validation individuelle, répétée ou collective

Trois modes sont distingués dans l’interface et dans le rapport :

1. **Examen individuel** : le traducteur examine un passage et répond à la question de contrôle.
2. **Application d’une décision à des occurrences identiques** : il voit la liste des occurrences et confirme le périmètre de réutilisation. Des mots identiques dans des contextes différents ne constituent pas automatiquement le même cas.
3. **Acceptation collective sous la responsabilité du traducteur** : il voit le nombre et la nature des points sélectionnés et les accepte sans examen individuel de chacun, lorsque le protocole de mission le permet. Cette action n’est pas décrite ensuite comme une série de doubles checks individuels.

La répétition de contrôles corrects ne prouve pas que les suivants le seront. Les points les plus critiques peuvent donc être exclus de la validation collective par le protocole. La liberté de décision professionnelle s’accompagne d’une description exacte du travail réalisé.

Chaque décision conserve l’identité du vérificateur, la date, la version du passage, le mode de validation et, selon le cas, la justification ou la règle appliquée. Toute modification ultérieure affectant le passage ou son contexte pertinent rouvre les contrôles concernés. L’absence d’erreur après vérification reste un résultat utile : elle établit qu’un élément important a été examiné, sans garantir l’infaillibilité du document entier.

## 7. La traductrice comme pilote du dispositif

La professionnelle définit la mission, produit la traduction, examine les points de contrôle et prend les décisions finales. Son expérience permet de reconnaître les usages, les implicites et les conséquences concrètes. Sa compréhension du processus machine lui permet d’interpréter les alertes, de demander des contrôles supplémentaires et de distinguer une preuve d’exécution d’une preuve de justesse.

Talumi doit lui faire gagner du temps d’investigation tout en améliorant la couverture des risques. Il ne doit pas déplacer tout son travail vers le traitement de fausses alertes. La présentation des dossiers, leur précision et leur ordre de priorité font donc partie de la qualité du produit.

La supervision ciblée n’exclut pas une lecture complète lorsque le niveau d’exigence de la mission le demande. Des contrôles par échantillonnage des zones sans alerte restent nécessaires pour estimer ce que le système laisse passer.

## 8. Une mémoire progressive des difficultés

Chaque cas validé peut enrichir une banque structurée : passage source, notion, langues, domaine, juridiction, contexte, difficulté, solutions envisagées, choix final, justification, références et auteur de la validation.

Les catégories initiales comprennent la polysémie, les concepts sans équivalent exact, les usages historiques, les différences entre systèmes juridiques, les négations, les conditions et exceptions, les données numériques, les omissions et les incohérences entre passages.

Une solution reste attachée à ses conditions d’emploi. Elle ne devient pas une substitution universelle. Les décisions sont versionnées et peuvent être révisées. La réutilisation entre clients respecte les règles de confidentialité du dossier.

La méthode progresse grâce aux retours humains : difficulté importante non détectée, alerte excessive, priorité mal estimée ou référence insuffisante. Chaque évolution est évaluée sur des cas distincts de ceux qui ont servi à la concevoir. L’accumulation de décisions ne suffit pas à prouver une amélioration.

## 9. Prouver l’exécution réelle des contrôles

Talumi doit pouvoir établir que les modèles annoncés ont effectivement été appelés. Le logiciel d’orchestration exécute les requêtes ; un modèle ne peut pas remplacer cette exécution par un récit affirmant qu’il a consulté d’autres modèles.

Le journal de chaque branche conserve le fournisseur, le modèle déclaré par l’API, les paramètres disponibles, les heures de départ et de fin, l’identifiant de requête lorsqu’il existe, les entrées et sorties ou leurs empreintes, les étapes de dépendance et les éventuels échecs. Les données sensibles sont protégées selon les conditions de la mission.

Les informations réseau, dont les adresses IP lorsque leur collecte est pertinente, peuvent compléter ces traces. Une adresse IP ne suffit cependant pas à identifier le modèle exécuté : plusieurs modèles peuvent partager une infrastructure. La preuve repose sur un ensemble de traces cohérentes issues du logiciel et des fournisseurs.

Une branche en échec est affichée comme telle. Un modèle de remplacement ou une reprise est identifié explicitement. Le dossier final distingue les contrôles prévus, exécutés, incomplets et non réalisés. Les journaux sont conservés avec des protections contre les modifications non tracées.

## 10. Un service professionnel facturable

Le premier produit est une prestation de traduction professionnelle accompagnée d’un contrôle documenté. La cliente ou le client reçoit :

- la traduction française validée ;
- une synthèse du périmètre, de la méthode et des contrôles exécutés ;
- un relevé des points importants et de leur résolution ;
- les réserves ou questions ouvertes qui affectent l’usage ;
- les éléments de traçabilité prévus au contrat.

La facturation tient compte du volume, de la technicité, du niveau de contrôle et du travail d’arbitrage. Les analyses automatiques sont des moyens de production du service ; la valeur livrée comprend le jugement professionnel et sa documentation.

Le prototype opérationnel peut se concentrer sur une seule direction, italien → français, avec un nombre limité de chemins réellement exécutés et journalisés. L’extension à sept langues intervient selon leur utilité mesurée. Les étapes indispensables au premier service sont la conservation de la source, l’aveuglement initial, la confrontation, la priorisation, la validation humaine et la traçabilité.

## 11. Démontrer la supériorité recherchée

Talumi vise à être meilleur que la traduction humaine sans ce dispositif et meilleur que l’IA seule. L’évaluation compare trois conditions : traduction professionnelle habituelle, traduction automatisée seule et traduction professionnelle avec Talumi.

Les mêmes exigences de livraison sont appliquées. Les textes comprennent des passages ordinaires et difficiles, avec un contexte suffisant pour les comprendre. Les évaluateurs qualifiés examinent les résultats sans connaître leur provenance. Une comparaison à budget comparable complète la mesure de qualité pour apprécier l’intérêt économique.

Les indicateurs prioritaires sont les erreurs résiduelles qui modifient le sens, leur gravité, la détection des problèmes critiques, les fausses alertes et le temps professionnel nécessaire. Les zones sans alerte sont également examinées. Les résultats sont présentés par domaine, langue et catégorie de difficulté ; une bonne moyenne ne masque pas les erreurs les plus graves.

La contribution des langues pivots est testée séparément : apportent-elles des découvertes utiles au-delà des contrôles directs et des modèles distincts ? Le nombre de chemins et les langues sont ajustés à partir de cette réponse.

## 12. L’avantage recherché à l’échelle d’un texte entier

Talumi rend praticable l’exploration parallèle et répétée d’un texte par plusieurs langues, modèles et contrôles, puis l’organisation de leurs résultats pour un professionnel. Une équipe humaine pourrait reproduire certains de ces parcours ; les multiplier systématiquement à cette échelle mobiliserait des compétences, du temps et un budget considérables.

L’avantage attendu est donc une capacité d’investigation étendue, articulée à un jugement humain responsable. Le passage par l’italien, le suédois ou le coréen vaut par les problèmes qu’il révèle et les décisions qu’il permet de mieux justifier.

Talumi doit permettre de répondre, pour chaque dossier : qu’a-t-on vérifié, par quels chemins, quels points demandaient une attention particulière, et sur quelles bases ont-ils été validés ?

## 13. Positionnement : la combinaison propre à Talumi

Talumi inscrit comme signature la combinaison suivante :

- des langues de racines et de logiques différentes, utilisées comme instruments de vérification du sens ;
- des chemins conduits à l’aveugle, confrontés seulement après dépôt de leurs résultats ;
- une traductrice qui pilote le dispositif et rend chaque décision ;
- un classement des passages selon la gravité d’une erreur possible ;
- la preuve que chaque contrôle annoncé a réellement été exécuté.

Talumi s’appuie sur des pratiques connues : combinaison de plusieurs traductions, confrontation de modèles et rétrotraduction. Un aller-retour fournit un indice de stabilité sans prouver la fidélité. Mehrparvar et Pezzelle (2024) étudient la détection de l’ambiguïté à partir des représentations internes de modèles et des traductions aller-retour. Ce travail constitue une piste de recherche ; il ne valide pas directement le dispositif Talumi fondé sur la confrontation de sorties textuelles par API. Talumi propose de réunir ces approches dans un service professionnel et d’évaluer l’apport propre de la diversité linguistique. Source : https://aclanthology.org/2024.mrl-1.26/

## 14. Un projet open source pour les traducteurs indépendants

Talumi est conçu comme un projet open source destiné aux professionnels de la traduction, notamment indépendants. Il leur donne un outil de contrôle commun et inspectable. Des versions automatisées peuvent intervenir dans les investigations ; la prestation finale reste validée et signée par un professionnel. Le code ouvert, l’accès au service et les conditions d’usage d’un éventuel label constituent des questions distinctes.

La crédibilité vient de la communauté. Un code ouvert se lit, se teste et se corrige publiquement. Une méthode de contrôle gagne en confiance quand chacun peut vérifier comment elle contrôle.

### Souveraineté et confidentialité

Talumi porte une ambition internationale et envisage un premier ancrage professionnel européen. Le fonctionnement local ou sur des serveurs européens doit être distingué de la destination des appels aux modèles : une application locale peut transmettre un texte à des fournisseurs externes. La confidentialité dépend du parcours réel des données, des accès et de la conservation, et non de la seule localisation de l’interface.

Trois modes sont à étudier : traitement entièrement local sans transmission externe ; fournisseurs expressément sélectionnés avec destinations visibles ; service hébergé dont les traitements et la conservation sont documentés. La promesse de maîtrise des données doit correspondre à la configuration effectivement exécutée. Aucun transfert supposé à un gouvernement n’est présenté comme un fait sans preuve.

### Vivre de l’open source

L’hébergement, l’installation, la formation et le support constituent des offres à tester autour du code ouvert. Une comparaison avec des entreprises comme Odoo fournit une inspiration, pas un modèle transposable sans examen. Les coûts d’API, d’infrastructure et d’assistance sont mesurés dès les premières missions. Les mécanismes essentiels à la compréhension des contrôles doivent rester inspectables.

## 15. Le cœur du besoin — une faute invisible aux conséquences réelles

**Le danger, c’est une traduction fausse qui a l’air juste.** Le lecteur qui ne maîtrise pas la langue cible peut confondre fluidité et fidélité. Un enchaînement suédois peut aboutir à un texte italien plausible qui exprime une autre relation entre les faits, les personnes ou leurs obligations.

La peur de la faute constitue un moteur d’adoption : le client veut pouvoir s’engager sans découvrir trop tard qu’il avait compris autre chose. Cette inquiétude doit être reliée à des risques documentés et à des contrôles observables. La fréquence et la gravité des erreurs dépendent du texte, du couple de langues et du système.

François désigne les inepties observées comme la « connerie artificielle », en contraste avec les seules performances brillantes mises en avant. Pour le produit, la catégorie opérationnelle est celle des **erreurs de traduction à conséquence** : hallucinations, contresens, omissions, changements de négation, de condition ou d’obligation. Une hallucination désigne ici du contenu non fondé sur l’original ; toutes les erreurs ne sont pas des hallucinations.

Un modèle peut produire une suite plausible sans signaler qu’il a perdu une relation de sens. Il n’est pas nécessaire de lui attribuer une volonté de dissimuler son incompréhension. Talumi doit permettre d’examiner le résultat et ses conséquences, sans prétendre déduire le mécanisme interne d’une erreur à partir de sa seule apparence.

## 16. Les traductions signées et le professionnel identifiable

La limite simple proposée pour la prestation Talumi est la **traduction signée**. Derrière chaque livraison se trouve un professionnel qui a examiné les points critiques et validé une version identifiable.

La formule de présentation est : **« Un traducteur identifié, une traduction signée, un professionnel qui répond de son travail. »** Elle exprime la volonté de relier l’outil à une personne réelle, qualifiée et joignable. La signature doit être rattachée au document exact, à sa date et au périmètre de validation. Elle ne signifie pas automatiquement que la traduction est assermentée.

La notion de recours fait partie du besoin du client. Ses effets précis dépendront des engagements contractuels et du droit applicable. Le document n’affirme pas qu’un texte généré par IA supprimerait tout droit de recours ; il constate qu’une sortie automatique, à elle seule, n’identifie pas nécessairement le professionnel qui en assume la fidélité. Le caractère opposable éventuel concerne les documents et engagements, selon leur cadre juridique, plutôt qu’une qualification générale de la personne.

### Registre et qualification — développement envisagé

Un registre pourrait vérifier l’identité, les coordonnées professionnelles, le CV, les diplômes ou qualifications et le numéro de TVA lorsqu’il est applicable. L’âge a été évoqué parmi les informations d’inscription ; sa nécessité reste à déterminer. Les pièces de vérification et les coordonnées privées restent distinctes de ce qui est affiché publiquement.

Un examen à distance pourrait évaluer les capacités de traduction et la maîtrise du contrôle Talumi, avec une procédure de vérification d’identité et d’intégrité de l’évaluation. La qualification préciserait les couples de langues, domaines et limites reconnus. Une compétence générale dans l’outil ne vaut pas compétence universelle en traduction.

Il faut distinguer qualification professionnelle initiale, qualification au processus Talumi et validation d’une mission particulière. Un diplôme, un test ou une inscription ne garantit pas à lui seul chaque livraison. Les conditions de renouvellement, de révision et de contestation de la qualification restent à définir.

### Code ouvert et service professionnel

Le service de production et l’usage d’un éventuel label pourraient être réservés à une communauté de professionnels vérifiés. Le code libre peut rester accessible à tous. Une restriction d’usage du code aux seuls diplômés entrerait en tension avec l’objectif open source ; les règles d’accès au service et à la marque doivent donc être définies séparément. Une démonstration publique sur des exemples publiables peut coexister avec cet accès professionnel.

## 17. Transformer le métier et rendre la prestation vendable

Talumi vise à faire de l’IA une alliée du traducteur. Le professionnel passe davantage de temps à définir la mission, examiner les points importants et décider, tandis que le dispositif automatise une partie des investigations répétitives. La transition est comparée au passage de la machine à écrire à l’ordinateur : la manière de travailler change profondément.

L’objectif exprimé est un travail potentiellement dix fois plus rapide et de meilleure qualité. Ce facteur dix reste une cible à mesurer, en incluant les vérifications, les fausses alertes, les recherches et les corrections. La baisse du temps de production peut modifier les prix ; le traducteur doit pouvoir conserver une rémunération liée à son expertise et au service effectivement fourni.

La valeur commerciale doit être visible : traduction finale, points à conséquence examinés, décisions motivées et signature. Une note globale ou un voyant vert ne remplace pas ce dossier et pourrait effacer la contribution professionnelle. Il faut tester si les clients acceptent de payer cette prestation et si elle améliore la rentabilité réelle du traducteur.

Le premier essai économique envisagé est une mission avec une traductrice partenaire. Les mesures portent sur la qualité, le temps total, les coûts techniques et l’utilité du rapport pour le client. Le risque à surveiller est que l’outil serve seulement à exiger des prix inférieurs sans reconnaître le travail de validation.

## 18. Une communauté professionnelle européenne

Un parti pris européen a été proposé : une communauté de traducteurs qui documente les difficultés des langues, usages et institutions de son marché. Une couverture de 45 langues est une ambition à préciser, et non une liste arrêtée ni une capacité déjà démontrée. Elle ne se confond pas avec les 24 langues officielles de l’Union européenne.

La couverture des langues européennes par les grands outils existe déjà. Le roumain, notamment, ne doit pas être présenté comme inaccessible à ces systèmes. L’avantage recherché tient à la connaissance des difficultés, à la validation professionnelle et aux ressources contextualisées. La Commission européenne propose elle-même des outils couvrant les langues officielles de l’Union et certaines langues supplémentaires : https://translation.ec.europa.eu/tools-and-resources/ai-translation-and-language-tools_en

La communauté peut se structurer par couple de langues et par domaine. Les contributeurs enrichissent les cas difficiles, les glossaires et les protocoles. La maîtrise d’une langue ne suffit pas à valider tous les couples où elle intervient.

L’Europe définit ici un premier marché et un réseau de compétences. Les langues internes de contrôle peuvent rester plus larges : le coréen peut conserver une utilité expérimentale. La prédominance de l’anglais n’annule pas le besoin de vérifier la concordance des engagements.

## 19. Lancement — un site bêta utilisable et une prestation compréhensible

La direction retenue par François est de préparer un **site bêta fonctionnel**, avec les intégrations nécessaires à l’usage, puis de le faire connaître directement aux traducteurs. La publication d’un dépôt et l’attente d’une communauté ne constituent pas le lancement. Le présent livre blanc décrit cette cible ; il n’atteste pas l’existence d’un site ou de plugins déjà opérationnels.

Le professionnel doit comprendre en un paragraphe ce qu’il peut vendre. Le pitch de travail est :

> Talumi est l’outil des traductions signées. Il permet aux traducteurs professionnels de travailler plus vite, avec des contrôles croisés par IA. Un humain examine les points critiques, valide la traduction et la signe.

La signature de communication proposée est : **« Talumi, l’alliée des traducteurs. Transformez les capacités de l’IA en une prestation professionnelle que vous pilotez, signez et vendez. »** L’opposition formulée dans les échanges entre Talumi alliée du métier et IA menaçant le métier exprime l’intention du projet ; elle ne devient pas une affirmation selon laquelle toute utilisation de l’IA détruirait nécessairement la profession.

Le parcours d’essai proposé utilise un original et une traduction existante. Il montre des passages signalés et un exemple de rapport remis au client. Un exercice public en ligne permettrait de comprendre le bénéfice sans installer un logiciel ; les plugins intégreraient ensuite Talumi au travail quotidien. Le choix définitif entre service en ligne, installation locale et intégrations dépendra des contraintes de confidentialité et d’usage.

### Atteindre les traducteurs

Les relais proposés sont les associations professionnelles, les traducteurs qui montrent leur utilisation réelle et les formateurs ou enseignants. Un atelier peut confronter une difficulté de traduction, les signalements de Talumi et les décisions du professionnel. Une démonstration courte, partageable et reproductible sur le site est un support de diffusion prioritaire.

Un plugin est un moyen d’accès et non une garantie de visibilité. Les premiers utilisateurs doivent trouver une raison concrète d’essayer, puis de recommander l’outil. Aucun partenaire, association ou établissement n’est considéré comme engagé sans prise de contact et accord.

## 20. Briques existantes et contributions au bien commun

La piste OmegaT identifiée dans la stratégie de Claude est techniquement plausible : le logiciel dispose d’un mécanisme de plugins. L’architecture proposée sépare un moteur Talumi autonome de ses interfaces, afin d’éviter qu’une intégration unique détermine tout le produit. Documentation : https://omegat.readthedocs.io/en/latest/19.PluginManifest.html

Des briques voisines existent : Okapi CheckMate pour des contrôles sur fichiers bilingues ; Translate Toolkit pour des erreurs courantes ; COMET et xCOMET pour l’évaluation automatique et la localisation de passages potentiellement erronés. Leur adoption demande de vérifier licences, langues, performances et ressources nécessaires. La singularité de Talumi est une hypothèse de combinaison et de service à démontrer, pas l’absence de tout outil voisin.

- Okapi CheckMate : https://okapiframework.org/wiki/index.php/CheckMate
- Translate Toolkit : https://translate.readthedocs.io/projects/translate-toolkit/en/latest/guides/using_pofilter.html
- COMET : https://github.com/Unbabel/COMET

European Language Grid est une piste de recherche de ressources et de partenaires européens : https://live.european-language-grid.eu/page/about-elg

Une contribution communautaire essentielle peut être un **cas difficile documenté**, sans écriture de code : original, traduction erronée plausible, conséquence, solution et justification. Une collection publique peut servir à démontrer l’utilité, tester les régressions et associer professionnels, écoles et chercheurs. Les cas d’amélioration restent séparés des cas utilisés pour l’évaluation indépendante.

Une autre fonction à explorer est la clarification du texte source : lorsqu’un original permet plusieurs interprétations, Talumi aide à formuler la question au client. Le protocole distingue ambiguïté à conserver, ambiguïté à éclaircir et erreur de traduction.

## 21. Une vitrine fondée sur des erreurs réelles

La vitrine doit rendre immédiatement perceptible le problème : un texte peut être spectaculaire par sa vitesse de production et pourtant contenir une phrase qui inverse une instruction ou un engagement. La présentation suit quatre éléments : **original, traduction produite, conséquence possible, signalement effectivement obtenu avec Talumi**.

Les sources proposées sont les études sur des documents professionnels, les corpus annotés de recherche et les contributions autorisées de traducteurs. Chaque fiche conserve le système et sa version lorsqu’ils sont connus, la date, le contexte, la source, l’analyse professionnelle et les conditions de reproduction. Une erreur historique ne décrit pas automatiquement les capacités actuelles du même fournisseur.

### Un exemple documenté d’inversion

L’UCSF rapporte en 2019 qu’une consigne anglaise demandant de suspendre un médicament pour les reins a été traduite en chinois comme une consigne de continuer à le prendre. Les chercheurs ont jugé l’erreur potentiellement mortelle. Il s’agit d’un risque évalué, sans décès rapporté dans cette présentation. Ce cas concerne un ancien système de Google Translate et ne prouve pas une défaillance actuelle. Source : https://www.ucsf.edu/news/2019/02/413376/google-translates-doctors-orders-spanish-and-chinese-few-significant-errors

### Des corpus pour constituer les premiers cas

HalOmi documente hallucinations et omissions dans 18 directions de traduction : https://aclanthology.org/2023.emnlp-main.42/

Looking for a Needle in a Haystack annote plus de 3 400 phrases avec des erreurs critiques et hallucinations dans un cadre expérimental sans bruit artificiellement ajouté : https://aclanthology.org/2023.eacl-main.75/

Ces corpus contiennent des sorties de systèmes ; ils ne prouvent pas qu’un engagement a été signé ou qu’un dommage réel s’est produit. L’exemple d’un accord allemand–italien exprimant des obligations opposées reste une illustration recherchée, non un incident vérifié à cette date.

Pour démontrer Talumi, le cas est soumis au dispositif sans lui révéler l’erreur attendue. La vitrine distingue ce qui a été détecté, manqué ou insuffisamment expliqué. Les sorties et les échecs sont conservés. Les droits de publication sont examinés avant toute diffusion.

## 22. Assurabilité — un dernier étage essentiel

Une assurance liée aux traductions signées est envisagée à un stade ultérieur. Elle apporterait une capacité de réparation financière lorsqu’une erreur couverte cause un dommage. Ce développement est considéré comme essentiel dans la vision de long terme, sans être un préalable au site bêta.

L’objectif envisagé est une offre associant qualification du professionnel, validation traçable d’un document et couverture par un assureur partenaire. Aucun contrat ni partenariat d’assurance n’est établi à ce stade.

Une assurance ne fait pas automatiquement disparaître la responsabilité du traducteur. La défense, l’indemnisation, les plafonds, les exclusions et les obligations des parties dépendront du contrat. La formule de travail est : **« Une traduction contrôlée, signée par un professionnel qualifié et couverte par une assurance »**, utilisable commercialement seulement lorsque cette couverture existe effectivement.

La conception prévoit dès le départ la conservation des versions, validations, contrôles et incidents utiles à l’étude future du risque. Ces données peuvent alimenter une discussion avec un assureur, sans garantir son acceptation ni un niveau de couverture.

## 23. Contrats multilingues — pistes de développement ultérieur

Le cas discuté est celui d’une entreprise espagnole qui doit s’engager sur un document de 300 pages avec un partenaire étranger. Une langue commune facilite la négociation mais ne garantit pas l’identité des interprétations. Talumi vise une confiance fondée sur un examen documenté, sans promettre une certitude absolue.

### Trois versions alignées

Une option envisagée associe la langue de chaque partie à une version anglaise commune, utilisée comme point de repère pendant les échanges. Les versions sont comparées dans les trois directions ; l’anglais peut lui-même contenir une erreur. Chaque modification d’un montant, d’une condition ou d’un délai déclenche le réexamen des passages correspondants.

La référence commune réside dans l’alignement documenté. La décision sur la version qui fait foi appartient aux parties et à leurs conseils. Ce dispositif est une piste pour certains engagements importants et non une obligation générale de traduction en trois langues.

### Cadre juridique de la mission

Le dossier doit distinguer langue du contrat, version faisant foi, droit applicable, tribunal compétent et langue de procédure. Une rédaction anglaise n’implique pas l’application du droit anglais. Le choix d’un tribunal dans un pays tiers ou d’un arbitrage est une possibilité à examiner avec les conseils des parties, sans règle universelle présumée.

Le Netherlands Commercial Court d’Amsterdam est un exemple de juridiction permettant certaines procédures commerciales internationales en anglais selon ses conditions de compétence et l’accord requis ; il peut appliquer un droit étranger. Sources : https://www.rechtspraak.nl/english/ncc et https://www.rechtspraak.nl/english/ncc/faq

La distinction entre choix de loi et choix de tribunal est exposée dans les principes de La Haye : https://www.hcch.net/en/instruments/conventions/full-text/?cid=135

Le traducteur valide la fidélité linguistique dans le périmètre convenu. L’arbitrage d’une intention contractuelle ou d’une question juridique peut exiger les parties et leurs juristes. Ces développements orientent la vision future ; ils ne retardent pas l’expérimentation du produit et de son adoption par les traducteurs.

## 24. E2C : le terrain premier de Talumi

Les documents d'affaires internationaux circulent d'anglais à anglais (E2E). Les parties signent un même texte anglais, qui fait foi. La traduction y sert à comprendre ; elle n'engage pas.

Talumi se place au moment où l'anglais devient le texte d'un consommateur dans sa propre langue (E2C, English to consumer). Sur un emballage polonais, une notice italienne ou des conditions d'utilisation en portugais, la version locale est la seule que le consommateur lit. Aucun texte anglais ne la double sur le produit. C'est elle qui informe, avertit et engage.

Le droit européen impose cette version locale. Pour les denrées alimentaires, le règlement (UE) n° 1169/2011 exige que les mentions obligatoires figurent dans une langue facilement comprise par les consommateurs de l'État membre où le produit est commercialisé. Les notices de médicaments, les avertissements de jouets et les mentions des cosmétiques suivent la même logique.

Le terrain E2C réunit les conditions où Talumi apporte le plus : un texte court, une conséquence directe pour une personne (allergène, dosage, mise en garde), aucune version de référence lisible par le lecteur final, et une même source anglaise déclinée dans de nombreuses langues à la fois.

## 25. Le modèle à crédits et la revente par le traducteur

Le traducteur indépendant crédite son compte Talumi, puis dépose son document en PDF. Talumi calcule le prix du contrôle et l'affiche. Le traducteur fixe lui-même le prix qu'il facture à son client.

Il reçoit en retour :

- le document traduit, documenté et surligné selon les zones à risque et à valider ;
- le texte brut, prêt à livrer ;
- la note Talumi destinée au client, qui ne mentionne que le prix fixé par le traducteur.

Le prix de Talumi reste entre Talumi et le traducteur. Le traducteur décide seul de sa marge. Talumi devient l'outil de production d'une prestation qu'il vend sous son nom.

### Face à un concurrent moins cher

Le code étant ouvert, un tiers peut installer Talumi et proposer un contrôle à plus bas prix. Le modèle tient pour quatre raisons.

1. **Le certificat reste propre à Talumi.** Le client vérifie le certificat sur le site de Talumi, dans le registre des traducteurs qualifiés. Un service concurrent peut contrôler un texte ; il ne peut pas délivrer un certificat Talumi vérifiable.
2. **La banque des cas difficiles reste au service.** Les difficultés validées par les traducteurs alimentent la mémoire décrite en section 8. Elle vit dans le service hébergé et s'enrichit avec chaque mission. Un concurrent repart d'une mémoire vide.
3. **La licence AGPL ramène les améliorations.** Un concurrent qui modifie le moteur et le propose en ligne doit publier ses modifications. Talumi peut les reprendre.
4. **Le prix de Talumi reste bas.** Le coût de calcul d'un contrôle est minime. Un tarif bas retire l'intérêt de construire un service concurrent, avec son hébergement, sa réputation et son assistance.

Un concurrent qui s'installe sur le code Talumi peut aussi devenir un partenaire, sur le modèle des partenaires Odoo.

## Note sur l’identité internationale

TALUMI · तलुमि · タルミ · 塔鲁米 réunit une forme latine, une proposition en devanagari, une proposition en katakana et une proposition en caractères chinois. Cette signature exprime l’ambition internationale du projet. Les formes non latines sont des propositions de marque à faire valider linguistiquement avant un usage commercial. Le devanagari représente certaines langues de l’Inde, et non la totalité de ses écritures.
