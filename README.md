SCD Primo
=========

Ce module gère les blocks de formulaires de recherche utilisés en haut de page. Ces formulaires redirigent l'utilisateur vers Primo, Scopus ou Pubmed.

 * Un block appelé *Recherche Primo Globale* qui sert sur BU Martinique et BU Guadeloupe, et qui redirige sur Primo. 
 * Un block plus complexe appelé *Recherche Primo pour la Recherche* qui sert sur BU Recherche, et qui redirige sur Primo, Scopus ou Pubmed avec un système de tabs. 

Ces blocks ont une version mobile et une version desktop. Dans tous les cas, le markup des deux versions est envoyé à l'utilisateur, et l'affichage est filtré en CSS grâce aux classes responsives de Bootstrap.
