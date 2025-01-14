---
altLangPage: "/2020/10/09/collect-feedback"
date:   2020-10-09
description: "Obtenir régulièrement de la rétroaction des Canadiens aide les équipes dans l'ensemble du gouvernement à améliorer continuellement la prestation des services sur le site Canada.ca. En mai 2020, quelques équipes ont collaboré au lancement de l'étude pilote d'un widget pour obtenir la rétroaction des gens sur les pages Canada.ca."
title:  "Recueillir la rétroaction, trouver les problèmes"
---

En 2020, les interactions de la majorité des Canadiens avec leur gouvernement se font principalement en ligne. Les pages Web du gouvernement du Canada sont plus qu'un simple outil de communication. Elles sont un important point de prestation de services.

Obtenir régulièrement de la rétroaction des Canadiens aide les équipes dans l'ensemble du gouvernement à améliorer continuellement la prestation des services sur le site Canada.ca. Lorsque les gens peuvent trouver les réponses à leurs questions en ligne, cela permet de réduire le nombre de courriels et d'appels aux centres d'appels.

Et si nous pouvions être informés plus tôt lorsque les gens ne trouvent pas les réponses qu'ils cherchent en ligne?

## Étude pilote

En mai 2020, quelques équipes ont collaboré au lancement de l'étude pilote d'un widget pour obtenir la rétroaction des gens sur les pages Canada.ca. Le Bureau de la transformation numérique (BTN) a travaillé avec les acteurs suivants&nbsp;:
* Santé Canada/Agence de la santé publique du Canada (ASPC);
* Éditeur principal;
* Bureau du Conseil privé.

Le widget de rétroaction sur la page est une simple question qui se trouve au bas de celle-ci, où se trouve habituellement le widget «&nbsp;Signaler un problème&nbsp;». Il s'agit de, «&nbsp;Avez-vous trouvé ce que vous cherchiez?&nbsp;». Les utilisateurs peuvent répondre par oui ou par non. S'ils répondent non, ils ont la possibilité de fournir plus de détails.

Ce widget simple est un outil puissant pour les propriétaires de contenu. Il leur permet de surveiller passivement l'efficacité de leur contenu. Il offre en outre la possibilité de vérifier régulièrement si le contenu fonctionne comme prévu et, si ce n'est pas le cas, pourquoi.

Le 11 mai, nous avons ajouté le widget au bas de deux pages liées à la COVID-19&nbsp;:
* [Symptômes et traitement](https://www.canada.ca/fr/sante-publique/services/maladies/2019-nouveau-coronavirus/symptomes.html)
* [Prévention et risques](https://www.canada.ca/fr/sante-publique/services/maladies/2019-nouveau-coronavirus/prevention-risques.html)

### Objectif du pilote

Notre objectif pour cette étude pilote était ce qui suit&nbsp;:
* mettre à l'essai une nouvelle approche pour la recherche en conception et la mesure de la réussite des tâches;
* découvrir si nous recevrions plus de commentaires utilisables qu'avec le widget «&nbsp;Signaler un problème&nbsp;»;
* cerner les problèmes de convivialité;
* éclairer les améliorations itératives du contenu;
* faire des expériences avec l'apprentissage automatique et le traitement du langage naturel pour aider à trier les commentaires.

## Widget de rétroaction

L'éditeur principal à Service Canada a conçu le widget. En l'intégrant dans les pages, les ministères peuvent recueillir les commentaires qualitatifs et quantitatifs des Canadiens.

<figure>
<img class="img-responsive border" alt="Une longue description peut être trouvée après l'image."
src="/images/feedback-3.png" >
</figure>
<details>
<summary>Le widget de rétroaction sur la page</summary>
<p>Le widget affiche la question&nbsp;: «&nbsp;Avez-vous trouvé ce que vous cherchiez?&nbsp;» et propose des options oui et non.</p>
</details>

<figure>
<img class="img-responsive border" alt="Une longue description peut être trouvée après l'image."
src="/images/feedback-4.png" >
</figure>
<details>
<summary>Écran suivant de le widget de rétroaction sur la page</summary>
 <p>Lorsque les utilisateurs choisissent «&nbsp;non&nbsp;», on leur demande «&nbsp;Qu'est-ce qui n'allait pas?&nbsp;» et on leur donne les options suivantes&nbsp;:</p>
 <ul>
<li>La réponse dont j'ai besoin n'est pas là</li>
<li>L'information n'est pas claire</li>
<li>Je ne suis pas au bon endroit</li>
<li>Quelque chose est brisé ou incorrect</li>
<li>Autre raison</li>
 </ul>
<p>En sélectionnant «&nbsp;autre raison&nbsp;», ils affichent un champ de texte libre où ils peuvent fournir plus de détails, avec la consigne de ne pas inclure d'informations personnelles.</p>
</details>


## Traitement de la rétroaction

Adobe Analytics traite les données quantitatives, c'est-à-dire le nombre de «&nbsp;oui&nbsp;» par rapport au nombre de «&nbsp;non&nbsp;», et les réponses prédéfinies pour ce qui n'allait pas. Pour l'étude pilote, la rétroaction textuelle était envoyée à un compte de courriel générique de Santé Canada. Félicitations à Santé Canada et à l'ASPC pour avoir passé en revue la rétroaction et d'en avoir fait l'analyse.

Depuis ce projet pilote, nous avons mis au point un processus qui permet d'extraire la rétroaction textuelle directement vers une base de données. Nous avons fait des expériences avec l'apprentissage automatique pour la classer automatiquement. Nous avons également créé une interface Web pour aider les ministères à passer en revue la rétroaction afin d'en dégager des tendances et des idées.

L'examen de la rétroaction textuelle peut demander beaucoup de temps, si bien que plus nous pouvons compter sur l'automatisation des tâches manuelles associées à ce travail, plus il sera facile d'envisager un déploiement plus vaste du widget sur l'ensemble du site Canada.ca.

## Protection des renseignements personnels

Nous savions qu'il existait une possibilité que nous recevions des renseignements personnels non sollicités, même si le widget recommande aux gens de ne pas en inclure. Pour régler ce problème, nous avons demandé conseil aux organisations suivantes&nbsp;:
* Division de la gestion de la protection des renseignements personnels, Santé Canada;
* Division de la gestion de la sécurité nationale, Santé Canada;
* Sécurité de la TI, Santé Canada.

À la lumière des conseils que nous avons reçus, le BTN a créé un processus pour retirer automatiquement les renseignements personnels présents dans la rétroaction. Il a été ainsi possible d'éviter un autre élément du traitement manuel. Plus le nombre d'étapes automatisées sera grand, plus les équipes auront le temps de se concentrer sur les améliorations.

## Ce que nous avons constaté

En date du 10 juin, nous avions reçu 5083 réponses par le biais des 2 pages pilotes du widget. Cela représente une moyenne de 164 réponses par jour.

Lorsque les gens ont répondu qu'ils n'avaient pas trouvé ce qu'ils cherchaient, leurs réponses concernant ce qui n'allait pas nous ont donné une idée des principaux problèmes de convivialité sur les pages.

<figure>
  <img class="img-responsive border" alt="Une longue description peut être trouvée après l'image." src="/images/feedback-graph-3.png">
</figure>
<details>
  <summary>Résultats de l'analyse des boutons radio.</summary>
  <h3>Qu'est-ce qui n'allait pas?</h3>
  <ul>
    <li>La réponse dont j'ai besoin n'est pas là</li>
    <li>Aucune raison invoquée</li>
    <li>Autre raison</li>
    <li>L'information n'est pas claire</li>
    <li>Je ne suis pas au bon endroit</li>
    <li>Quelque chose est brisé ou incorrect</li>
  </ul>
</details>

Sur les 1015 personnes qui ont répondu à «&nbsp;ce qui n'allait pas&nbsp;», 782 (77&nbsp;%) ont utilisé la zone de texte pour fournir plus de détails dans leurs propres mots sur ce qui ne fonctionnait pas.

Grâce à cette rétroaction, nous avons commencé à avoir une meilleure idée des éléments qui causaient des problèmes aux gens pendant leur visite. Les spécialistes du contenu ont ensuite examiné la rétroaction pour en saisir l'intention et les causes détaillées de la frustration.

<figure>
  <img class="img-responsive border" alt="Une longue description peut être trouvée après l'image." src="/images/feedback-graph-4.png">
</figure>
<details>
  <summary>Résultats de l'analyse des textes ouverts.</summary>
  <h3>Les 10 premiers thèmes référencés</h3>
  <ul>
    <li>Symptômes</li>
    <li>Activités autorisées</li>
    <li>Dépistage</li>
    <li>Transmission</li>
    <li>Isolement en quarantaine auto-isolement</li>
    <li>Traitement</li>
    <li>Lieux de travail</li>
    <li>Soutien financier</li>
    <li>Populations vulnérables</li>
    <li>EPI</li>
  </ul>
</details>

Ce détail a permis à Santé Canada et à l'ASPC de réaliser ce qui suit&nbsp;:
* répartir les efforts en fonction de la fréquence à laquelle des commentaires semblables revenaient;
* déterminer les principaux points à améliorer;
* cerner les lacunes potentielles dans le contenu;
* constater si une page contenait des problèmes généraux à évaluer.

Par exemple, nous avons remarqué un grand pourcentage de commentaires liés à des symptômes moins courants de la COVID-19 qui n'étaient pas énumérés sur la page des symptômes. Cet aperçu a fourni des données probantes à l'appui de l'ajout de ces symptômes à la liste.

## Leçons essentielles apprises

* La zone de texte permet d'obtenir une rétroaction significative des personnes qui est directement liée au contenu et à ce qu'elles cherchent.
* La rétroaction textuelle permet aux équipes Web de cerner les termes utilisés par les Canadiens afin d'appuyer l'utilisation d'un langage clair.
* L'intégration du widget de rétroaction dans la page permet de créer une expérience harmonieuse pour les gens.
* Sur les pages très achalandées, deux semaines semblaient suffisantes pour déterminer les tendances et les points à améliorer.
* Le widget est une méthode rapide et rentable pour recueillir des observations sur le contenu.
* L'outil aide à normaliser la mesure de l'efficacité de votre contenu et la capacité d'y apporter des améliorations itératives après sa publication.
* La nature continue du widget permet aux équipes, grâce à la surveillance des changements dans le type de rétroaction qu'elles reçoivent, de constater immédiatement les effets des améliorations apportées.

## Prochaines étapes de ce projet pilote

* Mettre le widget à l'essai sur d'autres pages à l'intérieur et à l'extérieur de l'outil AEM (Adobe Experience Manager).
* Parfaire certaines fonctionnalités du widget.
* Continuer d'améliorer nos processus d'apprentissage automatique.
* Élaborer des «&nbsp;tableaux de bord&nbsp;» pour avoir un aperçu des tendances et des problèmes.
* Travailler à un déploiement plus large de l'outil.

## Mot de la fin

Pour finir, le but de la rétroaction est d'améliorer les services Web afin que notre contenu puisse mieux répondre aux besoins des Canadiens. Le widget de rétroaction sur la page est un outil utile qui fournit aux équipes du Web, des programmes et des politiques des renseignements précieux pour la prestation de services. Les leçons apprises peuvent nous aider à appuyer l'orientation et les recommandations relatives au contenu.

Enfin, un grand merci à nos partenaires pour ce projet pilote.

## Pour en savoir davantage

* [Increase the feedback - Gerry McGovern](https://medium.com/@gerrymcgovern/increase-the-feedback-3a0d4c904762) (en anglais seulement)

