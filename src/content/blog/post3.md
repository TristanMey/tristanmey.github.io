---
title: "Demo Site ONF e-commerce"
description: "Site d'e-commerce fait en HTML, CSS, PHP, JS deployé dans l'intranet de l'ONF fait pendant un stage de 6 semaines en 2ème année de BTS SIO déployé et utilisé dans le Grand-Est."
pubDate: "6 April 2023"
heroImage: "/Onf.webp"
tags: ["PHP","HTML","CSS","JS","SQL"]
---

<video controls>
  <source src="/videoONF.mp4" type="video/mp4" />
</video>

Ce site web d'e-commerce pour l'ONF de Colmar a été développé pendant ma 2ème année de BTS SIO durant mon stage qui à duré 6 semaines du 27 Février 2023 jusqu'aux 6 Avril 2023. <br>
Il a été déployé dans l'intranet de l'ONF dans tout le Grand-Est. <br>
Le site a été développé à l'aide de 2 autres personnes. <br>
Un client peut réaliser une commande de vêtements et une commande d'EPI
<p class="onfVetement"> Partie Vêtements : </p>
Sur le site le client peut trouver un catalogue de vêtements. <br>
Ce même catalogue propose des vêtements coûtant un certain nombre de points, <br> le client bénéficie de 150 points chaque année pour faire son achats, <br> il peut trier par ordre croissant ou décroissant de prix pour faire ces achats.
Après les avoirs mis dans son panier, le client peut changer dans celui-ci la taille et la quantité voir le supprimer si le client le souhaite. <br>
le client n'a le droit qu'à une seule commande pour une année et cette commande sera définitive, une fois celle-ci faite le client n'aura plus accès aux catalogues de vêtements mais il aura accès à la commande passé avec la date de ça commande et le récapitulatif de son panier qu'il pourra télécharger/imprimer en PDF. <br>
Aucune commande ne pourra être faites après le décompte sur l'écran d'accueil.
<p class="onfVetement"> Partie EPI : </p>
Le catalogue d'EPI ( équipement de protection individuelle) propose des EPI non pas coûtant comme les vêtements mais vous oblige en contre-partie un nombre maximum d'EPI possible à prendre pour une année <br> 
comme par exemple qu'une seule sorte de chaussures, qu'un seul pantalon etc.. <br>
Les différents EPI disponibles sont en fonction de votre métier, <br>
un bûcheron ne verra pas les mêmes chaussures ou pantalon qu'un débardeur. <br>
Après les avoirs mis dans votre panier, vous pouvez changer dans celui-ci la taille et la quantité voir le supprimer si le client le souhaite. <br>
le client n'a le droit qu'à une seule commande pour une année et cette commande sera définitive, une fois celle-ci faite le client n'aura plus accès aux catalogues D'EPI mais il aura accès à la commande passé avec la date de ça commande et le récapitulatif de son panier qu'il pourra télécharger/imprimer en PDF. <br>
Aucune commande ne pourra être faites après le décompte sur l'écran d'accueil.
<p class="onfVetement"> Partie Chef : </p>
En tant que chef, il aura accès aux récapitulatifs des commandes de toutes son équipe,<br>
il pourra voir ceux qui ont déjà commandé et ce qui ne l'a pas encore fait. <br>
Il pourra télécharger/imprimer le récapitulatif de son équipe qui pourra être trié par fournisseur pour permettre une commande groupée simplifiée. <br>
Il pourra aussi " se connecter " sur le compte d'une personne de son équipe sans rentrer le mot de passe et ainsi réaliser une commande 
si la personne ne peut pour x ou y raisons effectuer une commande. <br>
Il aura les mêmes droit qu'un client en ayant accès aux catalogues vêtements mais aussi au catalogue d'EPI
<p class="onfVetement"> Partie Administrateur : </p>
En tant qu'administrateur, il aura accès à tous les utilisateurs et toutes leurs commandes faites,<br>
il pourra bien sûr changer leurs identifiants ainsi que leur mot de passe.<br>
Il a accès aux logs, qui permet de voir quand quelqu'un c'est connecté, déconnecté, ajouter au panier, valider une commande. <br>
Si un chef effectue une commande sur le compte d'un de ces subordonnés, alors le nom afficher sur les logs sera celui du chef. <br>
enfin l'administrateur pourra supprimer tous les bons de commande de l'année grâce à un bouton et une vérification poussée pour la sécurité.

<div class="social-icons px-4 pb-5 pt-1 flex self-center justify-center sticky bottom-0 bg-base-200">
    <a href="https://github.com/TristanMey/ONF-master" target="_blank" class="mx-3" aria-label="Github" title="Github" style="margin-top:20px">
        <svg
            xmlns="http://www.w3.org/2000/svg"
            width="30"
            height="30"
            viewBox="0 0 24 24"
            style="fill: currentColor;transform: ;msFilter:;"
            ><path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M12.026 2c-5.509 0-9.974 4.465-9.974 9.974 0 4.406 2.857 8.145 6.821 9.465.499.09.679-.217.679-.481 0-.237-.008-.865-.011-1.696-2.775.602-3.361-1.338-3.361-1.338-.452-1.152-1.107-1.459-1.107-1.459-.905-.619.069-.605.069-.605 1.002.07 1.527 1.028 1.527 1.028.89 1.524 2.336 1.084 2.902.829.091-.645.351-1.085.635-1.334-2.214-.251-4.542-1.107-4.542-4.93 0-1.087.389-1.979 1.024-2.675-.101-.253-.446-1.268.099-2.64 0 0 .837-.269 2.742 1.021a9.582 9.582 0 0 1 2.496-.336 9.554 9.554 0 0 1 2.496.336c1.906-1.291 2.742-1.021 2.742-1.021.545 1.372.203 2.387.099 2.64.64.696 1.024 1.587 1.024 2.675 0 3.833-2.33 4.675-4.552 4.922.355.308.675.916.675 1.846 0 1.334-.012 2.41-.012 2.737 0 .267.178.577.687.479C19.146 20.115 22 16.379 22 11.974 22 6.465 17.535 2 12.026 2z"
            ></path>