# Le guide ultime du durcissement d'iOS

[![English](https://img.shields.io/badge/English-read-0969da?style=for-the-badge)](README.md)
[![Français](https://img.shields.io/badge/Fran%C3%A7ais-actif-2ea44f?style=for-the-badge)](README.fr.md)

## Table des matières
1. [Introduction](#introduction)
2. [Choisir le bon appareil : sélection de l'appareil et sécurité biométrique](#choisir-le-bon-appareil--sélection-de-lappareil-et-sécurité-biométrique)
3. [Acheter des appareils iOS de manière anonyme](#acheter-des-appareils-ios-de-manière-anonyme)
4. [Configuration initiale et Apple ID : bonnes pratiques](#configuration-initiale-et-apple-id--bonnes-pratiques)
5. [Codes d'accès et chiffrement](#codes-daccès-et-chiffrement)
6. [Activer Find My](#activer-find-my)
7. [Activer les mises à jour automatiques](#activer-les-mises-à-jour-automatiques)
8. [Authentification à deux facteurs](#authentification-à-deux-facteurs)
9. [Optimiser le suivi et les services de localisation](#optimiser-le-suivi-et-les-services-de-localisation)
10. [Services de localisation et suivi avancés : désactivation pour la confidentialité](#services-de-localisation-et-suivi-avancés--désactivation-pour-la-confidentialité)
11. [Considérations sur la biométrie et implications juridiques](#considérations-sur-la-biométrie-et-implications-juridiques)
12. [Renforcer la sécurité de l'écran verrouillé](#renforcer-la-sécurité-de-lécran-verrouillé)
13. [Désactiver le Control Center lorsque l'appareil est verrouillé](#désactiver-le-control-center-lorsque-lappareil-est-verrouillé)
14. [Activer Stolen Device Protection](#activer-stolen-device-protection)
15. [Gérer les autorisations des applications](#gérer-les-autorisations-des-applications)
16. [Désactiver le suivi et le suivi publicitaire](#désactiver-le-suivi-et-le-suivi-publicitaire)
17. [Utiliser un VPN et un pare-feu pour renforcer la sécurité](#utiliser-un-vpn-et-un-pare-feu-pour-renforcer-la-sécurité)
18. [Configurations VPN et DNS pour une confidentialité renforcée](#configurations-vpn-et-dns-pour-une-confidentialité-renforcée)
19. [Alternatives aux applications Apple axées sur la confidentialité](#alternatives-aux-applications-apple-axées-sur-la-confidentialité)
20. [Applications de messagerie sécurisées](#applications-de-messagerie-sécurisées)
21. [Navigateurs axés sur la confidentialité](#navigateurs-axés-sur-la-confidentialité)
22. [Fournisseurs de messagerie sécurisés](#fournisseurs-de-messagerie-sécurisés)
23. [Isolation des applications (sandbox)](#isolation-des-applications-sandbox)
24. [Connexions sans fil sécurisées](#connexions-sans-fil-sécurisées)
25. [Modélisation des menaces](#modélisation-des-menaces)
26. [Outils d'audit de sécurité](#outils-daudit-de-sécurité)
27. [Paramètres de confidentialité de Siri](#paramètres-de-confidentialité-de-siri)
28. [Sécuriser les réglages iCloud](#sécuriser-les-réglages-icloud)
29. [Paramètres de confidentialité et de sécurité de Safari](#paramètres-de-confidentialité-et-de-sécurité-de-safari)
30. [Ajustements détaillés des paramètres de confidentialité](#ajustements-détaillés-des-paramètres-de-confidentialité)
31. [Écoute en temps réel (Live Listen)](#écoute-en-temps-réel-live-listen)
32. [Rester sécurisé avec les mises à jour iOS](#rester-sécurisé-avec-les-mises-à-jour-ios)
33. [Mesures de sécurité physique de l'appareil](#mesures-de-sécurité-physique-de-lappareil)
34. [Les risques du jailbreak](#les-risques-du-jailbreak)
35. [Sauvegardes sécurisées](#sauvegardes-sécurisées)
36. [Alternatives au transfert de données et à iCloud](#alternatives-au-transfert-de-données-et-à-icloud)
37. [Temps d'écran et restrictions pour renforcer la sécurité](#temps-décran-et-restrictions-pour-renforcer-la-sécurité)
38. [Optimiser les services système pour la confidentialité](#optimiser-les-services-système-pour-la-confidentialité)
39. [Comprendre et utiliser le mode Isolement (Lockdown Mode)](#comprendre-et-utiliser-le-mode-isolement-lockdown-mode)
40. [Apprendre à utiliser Emergency SOS](#apprendre-à-utiliser-emergency-sos)
41. [Activer le mode USB restreint](#activer-le-mode-usb-restreint)
42. [Gérer les alertes d'urgence et les fausses alertes de confidentialité](#gérer-les-alertes-durgence-et-les-fausses-alertes-de-confidentialité)
43. [Gestion des mots de passe et sécurité des comptes](#gestion-des-mots-de-passe-et-sécurité-des-comptes)
44. [Implications pour la confidentialité des sauvegardes iCloud](#implications-pour-la-confidentialité-des-sauvegardes-icloud)
45. [Scénarios de modélisation des menaces](#scénarios-de-modélisation-des-menaces)
46. [Se débarrasser en toute sécurité des anciens appareils](#se-débarrasser-en-toute-sécurité-des-anciens-appareils)
47. [Compromis de confidentialité de Find My](#compromis-de-confidentialité-de-find-my)
48. [Utiliser Apple Pay et les fonctionnalités Wallet en toute sécurité](#utiliser-apple-pay-et-les-fonctionnalités-wallet-en-toute-sécurité)
49. [Sensibiliser famille et amis aux bonnes pratiques de sécurité](#sensibiliser-famille-et-amis-aux-bonnes-pratiques-de-sécurité)
50. [Gérer les appareils IoT et leurs accès](#gérer-les-appareils-iot-et-leurs-accès)
51. [Mettre en perspective les risques du jailbreak](#mettre-en-perspective-les-risques-du-jailbreak)
52. [Mises à jour et révisions régulières](#mises-à-jour-et-révisions-régulières)
53. [Ressources externes pour aller plus loin](#ressources-externes-pour-aller-plus-loin)
54. [Retours et contributions](#retours-et-contributions)

## Introduction
Bienvenue dans le guide ultime du durcissement d'iOS ! Ce guide vise à renforcer la sécurité et la confidentialité des iPhone et iPad pour tous les utilisateurs, des débutants aux plus avancés. Nous explorons et expliquons les fonctionnalités de sécurité d'Apple, leurs limites, et proposons des solutions alternatives pour une confidentialité et une sécurité robustes au sein de l'écosystème Apple.

## Choisir le bon appareil : sélection de l'appareil et sécurité biométrique

Lors de la sélection d'un appareil iOS, il est essentiel de prendre en compte les fonctionnalités de sécurité offertes par les différents modèles. Apple corrige continuellement les failles de sécurité et introduit de nouvelles améliorations de sécurité à chaque génération d'iPhone et d'iPad.

**Passer à un processeur A12 ou supérieur :**
Dans les modèles récents, Apple a apporté des changements importants pour corriger la vulnérabilité [checkm8](https://www.theiphonewiki.com/wiki/Checkm8_Exploit) et améliorer la sécurité globale de l'appareil. Le processeur (CPU) est le « cerveau » de votre appareil ; il exécute les instructions et gère les fonctionnalités de sécurité. La vulnérabilité checkm8 est un problème permanent qui touche les appareils équipés d'une puce A11 ou d'une puce antérieure, permettant à un attaquant disposant d'un accès physique d'exécuter du code non autorisé sur votre appareil.

En introduisant les Pointer Authentication Codes (PAC) sur les appareils équipés d'un processeur A12 et plus récent, Apple a considérablement amélioré la sécurité des appareils iOS récents. PAC utilise la cryptographie pour rendre certaines attaques beaucoup plus difficiles ; cette protection repose sur des fonctionnalités disponibles à partir du processeur A12, présentes dans la plupart des appareils sortis en 2018 et dans tous les appareils sortis depuis 2019.

**Recommandation :**
Le seul correctif de la vulnérabilité checkm8 consiste à remplacer votre appareil par un modèle équipé d'un processeur A12 ou ultérieur. Si vous utilisez un appareil plus ancien, envisagez de passer à un modèle plus récent pour vous protéger de cette vulnérabilité et bénéficier des améliorations de sécurité offertes par les appareils iOS les plus récents.

**Sécurité biométrique :**
Lors de la configuration de votre appareil, vous aurez la possibilité d'activer l'authentification biométrique via Face ID ou Touch ID, selon le modèle. Ces fonctionnalités sont pratiques, mais il est essentiel de comprendre leurs implications juridiques et de sécurité. Dans certaines juridictions, les forces de l'ordre peuvent vous contraindre à déverrouiller votre appareil avec votre visage ou votre empreinte digitale, tandis qu'un code d'accès peut offrir une meilleure protection juridique.

Tenez compte de votre modèle de menace et des implications juridiques dans votre région avant d'activer l'authentification biométrique. Si vous choisissez d'utiliser Face ID ou Touch ID, veillez à définir également un code d'accès robuste comme méthode d'authentification de secours.

## Acheter des appareils iOS de manière anonyme

Pour préserver votre anonymat lors de l'achat d'un appareil iOS, suivez ces bonnes pratiques :

- **Payer en espèces** : achetez les appareils iOS en espèces dans des magasins physiques afin d'éviter de laisser une trace numérique.

- **Éviter la configuration ou l'enregistrement en magasin** : refusez toute configuration ou tout enregistrement proposé en magasin, car cela pourrait associer vos informations personnelles à l'appareil.

- **Utiliser des cartes prépayées pour les achats en ligne** : si vous achetez en ligne, utilisez une carte de crédit prépayée ou une carte cadeau pour préserver votre anonymat. Évitez les cartes de crédit personnelles ou les moyens de paiement liés à votre identité.

- **Limiter les informations personnelles** : lors d'un achat en magasin, évitez de fournir des informations personnelles, comme votre adresse e-mail ou votre numéro de téléphone, même si le vendeur vous le demande. Si vous devez donner un nom pour l'achat, envisagez un pseudonyme ou un nom générique non lié à votre véritable identité.

- **Éviter les cartes de fidélité et les adhésions** : n'achetez pas d'appareils dans des magasins où vous disposez d'une adhésion ou d'une carte de fidélité, car celles-ci peuvent être liées à vos informations personnelles.

- **Utiliser une boîte postale ou un service de domiciliation** : si l'appareil doit être expédié, envisagez une boîte postale ou un service de domiciliation qui vous permet de recevoir des colis sans révéler votre adresse personnelle.

- **Configurer l'appareil en privé** : après l'achat, évitez de configurer l'appareil ou de le connecter à des réseaux Wi-Fi dans le magasin. Attendez d'être dans un lieu privé et sûr pour commencer la configuration.

- **Fournir un minimum d'informations pendant la configuration** : lors de la configuration initiale, ignorez ou fournissez un minimum d'informations lorsque l'Apple ID, l'adresse e-mail ou d'autres données personnelles vous sont demandés. Vous pourrez toujours ajouter ces informations plus tard, si nécessaire, dans un environnement plus sûr.

N'oubliez pas que l'objectif est de minimiser la quantité d'informations personnelles associées à l'achat et à la configuration initiale de l'appareil. En prenant ces précautions, vous contribuez à préserver votre anonymat et à réduire le risque que vos données personnelles soient liées à votre appareil iOS.

## Configuration initiale et Apple ID : bonnes pratiques
Commencez avec un appareil neuf ou réinitialisé en usine. Configurez votre Apple ID en dehors de vos réseaux personnels et utilisez des informations non personnelles pour le compte. Pendant la configuration initiale, désactivez toutes les options de connectivité comme le Wi-Fi, le Bluetooth et les données cellulaires.

## Codes d'accès et chiffrement
- **Code d'accès robuste** : optez pour un code d'accès d'au moins 6 chiffres ou, mieux, un code alphanumérique pour une sécurité accrue.
- **Sécurité biométrique** : utilisez Face ID ou Touch ID en comprenant les implications juridiques et de confidentialité.
- **Options avancées** : désactivez « Simple Passcode » pour accéder à des options de code d'accès plus complexes.
- **Protection des données** : activez toujours la protection des données et la protection du trousseau dans vos réglages.

## Activer Find My

Utilisez Find My pour localiser, verrouiller ou effacer votre appareil en cas de perte ou de vol. Un iPhone verrouillé ne peut pas être réutilisé sans les identifiants de votre Apple ID, même si le téléphone est effacé et que son logiciel est réinstallé.

**Qu'est-ce que Find My ?**

Find My est une application intégrée qui vous permet de :
- Localiser votre appareil sur une carte
- Émettre un son pour vous aider à retrouver votre appareil
- Marquer votre appareil comme perdu et le verrouiller avec un code d'accès
- Effacer votre appareil à distance si nécessaire

**Configurer Find My :**
1. Ouvrez l'application Réglages.
2. Touchez votre nom en haut de l'écran.
3. Touchez « Find My ».
4. Activez l'option « Find My iPhone ».
5. Activez « Find My network » pour localiser votre iPhone même hors ligne, en mode réserve d'énergie ou après extinction.
6. Activez « Send Last Location » pour envoyer automatiquement la position de votre iPhone à Apple lorsque la batterie est critique.

<img src="https://github.com/iAnonymous3000/iOS-Hardening-Guide/assets/32236127/1b264b7c-e062-45ee-896a-2db642ca01e9" alt="Find My settings" width="300">

Si vous êtes invité à vous connecter, saisissez les identifiants de votre Apple ID. Lorsque vous configurez Find My, toute Apple Watch et tous les AirPods appairés sont également configurés automatiquement.

**Find My network :**
Participer au réseau Find My vous permet de localiser votre iPhone même hors ligne, en mode réserve d'énergie ou après extinction. Il s'agit d'une fonctionnalité essentielle qui augmente les chances de récupérer votre appareil en cas de perte ou de vol.

**Send Last Location :**
L'activation de « Send Last Location » garantit que votre iPhone envoie automatiquement sa position à Apple lorsque la batterie est critique. Ces informations peuvent être vitales pour localiser votre appareil si sa batterie est épuisée.

**Recommandation :**
Il est essentiel d'activer Find My sur votre iPhone ou iPad, ainsi que les fonctionnalités « Find My network » et « Send Last Location ». Ces réglages offrent une couche de sécurité supplémentaire, ce qui rend beaucoup plus difficile la revente ou l'utilisation de votre appareil par un voleur en cas de perte ou de vol. Même si votre appareil est effacé et le logiciel réinstallé, il restera verrouillé et inutilisable sans les identifiants de votre Apple ID.

## Activer les mises à jour automatiques
Activez les mises à jour automatiques sous `Settings → General → Software Update → Automatic Updates` pour garantir que votre appareil dispose toujours des derniers correctifs de sécurité.

<img src="https://github.com/iAnonymous3000/iOS-Hardening-Guide/assets/32236127/f6942a24-b984-4ce9-9d65-8b853465cd53" alt="automatic-updates_settings" width="300">

## Authentification à deux facteurs
L'authentification à deux facteurs ajoute une couche de sécurité essentielle. Elle combine quelque chose que vous connaissez (votre mot de passe) et quelque chose que vous possédez (votre appareil).

Lorsqu'elle est activée, vous devez fournir à la fois votre mot de passe et un code de vérification à six chiffres pour vous connecter à votre compte Apple ID. Ce code s'affiche automatiquement sur vos appareils de confiance ou est envoyé à votre numéro de téléphone. Même si quelqu'un connaît votre mot de passe, il ne pourra pas accéder à votre compte sans avoir également accès à votre appareil de confiance ou à votre numéro de téléphone.

L'authentification à deux facteurs d'Apple diffère de la vérification en deux étapes. Si vous utilisez la vérification en deux étapes et souhaitez passer à l'authentification à deux facteurs, vous devez désactiver la vérification en deux étapes, puis activer l'authentification à deux facteurs.

Pour activer l'authentification à deux facteurs :
1. Accédez à `Settings → [Your name] → Password & Security`
2. Touchez `Turn On Two-Factor Authentication`
3. Suivez les instructions de configuration

## Optimiser le suivi et les services de localisation
La confidentialité est essentielle. Voici comment optimiser vos paramètres de suivi et de localisation :

1. Accédez à `Settings → Privacy & Security → Tracking`
2. Désactivez `Allow Apps to Request to Track` pour empêcher les applications de suivre votre activité dans les applications et sites web d'autres entreprises à des fins publicitaires ou de partager vos informations avec des courtiers en données
3. Accédez à `Settings → Location Services` pour gérer les autorisations d'accès à la localisation des applications
   - Choisissez d'autoriser l'accès à la localisation toujours, uniquement lors de l'utilisation de l'application, ou jamais
   - Pour les applications qui n'ont pas besoin de votre position précise, envisagez d'accorder l'accès à votre position approximative
4. Vérifiez régulièrement quelles applications disposent d'autorisations de localisation et révoquez l'accès de celles qui n'en ont pas besoin

## Services de localisation et suivi avancés : désactivation pour la confidentialité
Après la configuration, vérifiez régulièrement les paramètres de localisation et de suivi, en particulier après les mises à jour d'iOS. Les mises à jour peuvent réinitialiser vos préférences ou introduire de nouveaux réglages. Voici quelques étapes supplémentaires pour limiter le suivi :

1. Accédez à `Settings → Privacy & Security → Location Services → System Services`
2. Envisagez de désactiver les services de localisation non essentiels, comme les suggestions basées sur la localisation et les publicités
3. Recherchez les applications qui demandent un accès à la localisation en arrière-plan
   - L'accès en arrière-plan permet aux applications de suivre votre position même lorsque vous ne les utilisez pas activement
   - N'accordez l'accès en arrière-plan qu'aux applications qui en ont réellement besoin, comme les applications de navigation ou de suivi d'activité physique

## Considérations sur la biométrie et implications juridiques
Les méthodes biométriques comme Touch ID et Face ID sont pratiques mais ont des implications juridiques. Dans certaines juridictions, les forces de l'ordre peuvent vous contraindre à déverrouiller votre appareil avec votre visage ou votre empreinte digitale, mais elles ne peuvent pas vous obliger à divulguer votre code d'accès.

Envisagez les scénarios dans lesquels la biométrie peut être moins sûre qu'un code d'accès :
- Quelqu'un pourrait déverrouiller votre appareil pendant votre sommeil ou si vous êtes inconscient
- Lors d'un vol ou d'un enlèvement, vous pourriez être physiquement contraint de déverrouiller votre appareil

Si vous choisissez d'utiliser la biométrie :
- Veillez à définir également un code d'accès robuste comme solution de secours
- N'oubliez pas que vous pouvez toujours désactiver rapidement la biométrie en appuyant cinq fois de suite sur le bouton d'alimentation, ce qui exigera votre code d'accès pour déverrouiller l'appareil

## Renforcer la sécurité de l'écran verrouillé
Votre écran verrouillé peut constituer une vulnérabilité. Pour renforcer sa sécurité :

1. Accédez à `Settings → Touch ID/Face ID & Passcode`
2. Désactivez l'accès à des fonctionnalités comme Today View, Notification Center, Control Center, Siri, Reply with Message, Home Control, Wallet et USB Accessories lorsque votre appareil est verrouillé
   - Moins il y a de fonctionnalités accessibles depuis l'écran verrouillé, plus votre appareil est sécurisé
3. Accédez à `Settings → Display & Brightness → Auto-Lock` et définissez un délai de verrouillage automatique raisonnablement court
   - Cela garantit que votre appareil se verrouille rapidement lorsqu'il n'est pas utilisé, même si vous oubliez de le verrouiller manuellement

## Désactiver le Control Center lorsque l'appareil est verrouillé

Désactivez l'accès au Control Center lorsque votre appareil est verrouillé afin d'empêcher toute modification non autorisée de vos réglages. Par défaut, le Control Center est accessible depuis l'écran verrouillé, ce qui introduit un risque de sécurité inutile.

Par exemple, un voleur pourrait s'emparer de votre téléphone et désactiver rapidement les connexions cellulaires et Wi-Fi, vous empêchant de le localiser avec Find My. De plus, des réglages comme Bluetooth ou AirDrop, que vous avez peut-être désactivés pour réduire les risques, peuvent être réactivés si vous ne suivez pas ces étapes :

1. Ouvrez l'application Réglages.
2. Touchez l'une des options suivantes, selon la configuration de votre appareil :
   - Face ID & Passcode
   - Touch ID & Passcode
   - Passcode
3. Saisissez votre code d'accès.
4. Faites défiler jusqu'à la section « Allow Access When Locked ».
5. Décochez « Control Center ».
6. Décochez également toute autre fonctionnalité que vous n'utilisez pas.

<img src="https://github.com/iAnonymous3000/iOS-Hardening-Guide/assets/32236127/cf3633ba-c904-43c8-81cb-28e64058de07" alt="disable_control_center_when_locked" width="300">

En désactivant l'accès au Control Center lorsque votre appareil est verrouillé, vous empêchez toute modification non autorisée de vos réglages et réduisez les risques de sécurité potentiels.

## Activer Stolen Device Protection
Stolen Device Protection ajoute une couche de sécurité lorsque votre iPhone se trouve loin de lieux familiers, comme votre domicile ou votre lieu de travail, et contribue à protéger vos comptes et vos informations personnelles en cas de vol de votre iPhone.

Pour activer Stolen Device Protection, vous devez utiliser l'authentification à deux facteurs pour votre Apple ID et configurer ou activer les éléments suivants sur votre iPhone : un code d'accès à l'appareil ; Face ID ou Touch ID ; et Significant Locations* (Location Services). Vous devez également avoir activé Find My, et vous ne pouvez pas le désactiver tant que Stolen Device Protection est activé.

Lorsque Stolen Device Protection est activé, certaines fonctionnalités et actions ont des exigences de sécurité supplémentaires lorsque votre iPhone se trouve loin de lieux familiers :

- **Authentification biométrique Face ID ou Touch ID** : certaines actions, comme l'accès aux mots de passe et aux cartes bancaires enregistrés, nécessitent une authentification biométrique unique avec Face ID ou Touch ID — sans autre solution ni code d'accès de secours — afin que vous seul puissiez accéder à ces fonctionnalités.
- **Délai de sécurité** : certaines actions de sécurité, comme la modification du mot de passe de votre Apple ID, vous obligent également à attendre une heure, puis à effectuer une seconde authentification Face ID ou Touch ID.

Vous pouvez activer Stolen Device Protection dans Réglages :

1. Accédez à Réglages, puis touchez Face ID & Passcode.
2. Saisissez le code d'accès de votre appareil.
3. Touchez Stolen Device Protection, puis activez ou désactivez Stolen Device Protection.

Si vous souhaitez que votre iPhone applique les mesures de sécurité supplémentaires de Stolen Device Protection quelle que soit sa position, choisissez « Always » sous Require Security Delay. Par défaut, les mesures de sécurité supplémentaires ne sont requises que lorsque votre iPhone se trouve loin de lieux familiers.

*Significant Locations est une option des services de localisation : Settings > Privacy & Security > Location Services > System Services > Significant Locations.

## Gérer les autorisations des applications
Vérifiez régulièrement les autorisations des applications dans les réglages de votre appareil, en accordant une attention particulière à l'accès au microphone, à la caméra et aux services de localisation.

## Désactiver le suivi et le suivi publicitaire
Pour limiter le suivi publicitaire, accédez à `Settings → Privacy & Security → Apple Advertising` et désactivez « Personalized Ads ».

## Utiliser un VPN et un pare-feu pour renforcer la sécurité
Protégez-vous contre le piratage Wi-Fi et masquez votre adresse IP avec un VPN fiable. C'est essentiel pour préserver votre confidentialité sur les réseaux publics.

## Configurations VPN et DNS pour une confidentialité renforcée
Choisissez un fournisseur VPN respectueux de la confidentialité et configurez-le pour qu'il ne journalise pas vos données. Utilisez des services DNS pour un filtrage et une confidentialité supplémentaires.

## Alternatives aux applications Apple axées sur la confidentialité
Envisagez d'utiliser des alternatives axées sur la confidentialité aux applications natives d'Apple, telles que :
- Safari → [Brave](https://brave.com) (voir la comparaison des navigateurs iOS [ici](https://privacytests.org/ios))
- iMessage → [Signal](https://signal.org)
- iCloud → [Proton Drive](https://proton.me/drive)
- iCloud Keychain → [Bitwarden](https://bitwarden.com) / [Proton Pass](https://proton.me/pass)
- Apple Calendar → [Proton Calendar](https://proton.me/calendar)
- iCloud Private Relay (VPN) -> [MullvadVPN](https://mullvad.net/en) / [IVPN](https://www.ivpn.net) / [Proton VPN](https://protonvpn.com)
- Apple Mail -> [Proton Mail](https://proton.me/mail)
- Apple Notes -> [Standard Notes](https://standardnotes.com)
- iCloud Photos -> [ente](https://ente.io) ([comparaison ente vs Apple Photos](https://ente.io/compare/ente-vs-apple-photos))

Chaque alternative est choisie pour l'importance qu'elle accorde à la confidentialité et à la sécurité.

## Applications de messagerie sécurisées
Lors du choix d'une application de messagerie sécurisée, envisagez les options suivantes :
- Signal : une application de messagerie open source chiffrée de bout en bout, largement adoptée et recommandée par les experts en sécurité.
- SimpleX Chat : une plateforme de messagerie décentralisée et open source qui offre un chiffrement de bout en bout, aucun identifiant utilisateur (comme un numéro de téléphone ou un nom d'utilisateur) et des fonctionnalités de confidentialité renforcées.
- Threema : une application payante qui offre un chiffrement de bout en bout, ne nécessite pas de numéro de téléphone et met fortement l'accent sur la confidentialité et la sécurité.

Pour une comparaison complète des applications de messagerie sécurisée, consultez [Secure Messaging Apps](https://www.securemessagingapps.com). Ce site compare diverses applications de messagerie en fonction de leurs fonctionnalités de sécurité, de leurs politiques de confidentialité et d'autres facteurs importants, pour vous aider à prendre une décision éclairée.

## Navigateurs axés sur la confidentialité
En matière de navigateurs axés sur la confidentialité, envisagez les options suivantes :
- Brave : un navigateur basé sur Chromium avec blocage intégré des publicités et des traqueurs, ainsi qu'un mode de navigation privée axé sur la confidentialité.
- Firefox Focus : un navigateur gratuit et open source avec protection intégrée contre le suivi, blocage des publicités et possibilité d'effacer facilement vos sessions.

Ces navigateurs offrent des fonctionnalités de confidentialité robustes pour protéger vos activités en ligne contre le suivi et la surveillance.

## Fournisseurs de messagerie sécurisés
Pour une communication par e-mail sécurisée et privée, envisagez les fournisseurs suivants :
- ProtonMail : un service de messagerie chiffré de bout en bout qui propose une offre gratuite et des forfaits payants avec des fonctionnalités supplémentaires.
- Tutanota : un service de messagerie gratuit et open source avec chiffrement de bout en bout, authentification à deux facteurs et possibilité d'envoyer des e-mails chiffrés à des utilisateurs non-Tutanota.

Pour comparer différents fournisseurs de messagerie sécurisée, consultez [Email Provider Comparison](https://email-comparison.as93.net). Ce site propose une comparaison détaillée des fournisseurs de messagerie en fonction de leurs fonctionnalités de sécurité, de leurs politiques de confidentialité, de leur juridiction et d'autres facteurs essentiels.

En choisissant avec soin une application de messagerie sécurisée, un navigateur axé sur la confidentialité et un fournisseur de messagerie sécurisé, vous pouvez considérablement renforcer votre confidentialité et votre sécurité lors de vos communications et de votre navigation en ligne.

## Isolation des applications (sandbox)
L'isolation des applications (sandbox) d'iOS est une fonctionnalité de sécurité essentielle qui contribue à la sécurité globale de l'appareil en isolant les applications les unes des autres et en limitant leur accès aux ressources système.

Principaux avantages de l'isolation des applications :
1. **Protection des données** : chaque application dispose de son propre espace dédié au stockage des données, ce qui empêche tout accès non autorisé depuis d'autres applications.
2. **Accès aux ressources** : les applications ne peuvent accéder aux ressources système, comme la caméra ou la localisation, qu'avec l'autorisation explicite de l'utilisateur.
3. **Communication entre applications** : la communication entre applications est limitée à des API iOS spécifiques, ce qui empêche le vol ou l'interférence de données.
4. **Séparation des privilèges** : les applications s'exécutent avec le niveau de privilège minimal nécessaire, ce qui limite les dommages potentiels en cas de compromission.

Bien qu'elle soit largement invisible pour les utilisateurs, l'isolation des applications est essentielle à la sécurité d'iOS. Elle peut toutefois être affaiblie par le jailbreak ou par le chargement latéral (sideloading) d'applications provenant en dehors de l'App Store, exposant votre appareil à des risques accrus.

## Connexions sans fil sécurisées
La sécurisation de vos connexions sans fil est essentielle pour protéger vos données en transit. Voici quelques bonnes pratiques :

1. **Utiliser le chiffrement WPA3 pour le Wi-Fi** :
   - Choisissez WPA3 si votre routeur le prend en charge, car il offre la meilleure protection contre les attaques par devinette de mot de passe et la rupture du chiffrement.
   - Si WPA3 n'est pas disponible, utilisez WPA2 avec chiffrement AES.
   - Évitez WPA, WEP ou les réseaux ouverts, qui sont beaucoup moins sûrs.

2. **Éviter les Wi-Fi publics non sécurisés** :
   - Les points d'accès Wi-Fi publics sont souvent non sécurisés ou mal sécurisés, exposant vos données à l'interception.
   - Si vous devez utiliser un Wi-Fi public, connectez-vous d'abord à un VPN pour chiffrer vos données (voir la section VPN pour plus de détails).
   - Évitez d'accéder à des informations sensibles, comme vos services bancaires, sur un Wi-Fi public, même avec un VPN.

3. **Utiliser les données cellulaires plutôt que le Wi-Fi** :
   - Les réseaux cellulaires sont généralement plus sûrs que le Wi-Fi public : ils utilisent le chiffrement et sont plus difficiles à intercepter.
   - Tenez compte du coût des données, en particulier en itinérance ou avec un forfait limité.

4. **Garder vos appareils à jour** :
   - Installez les mises à jour de vos appareils iOS et de vos routeurs dès qu'elles sont disponibles.
   - Les mises à jour incluent souvent des correctifs de sécurité pour les vulnérabilités récemment découvertes dans les protocoles et implémentations Wi-Fi.

En suivant ces bonnes pratiques, vous pouvez réduire considérablement le risque de compromission de vos connexions sans fil et d'interception de vos données.

## Modélisation des menaces
Évaluez vos besoins de sécurité individuels en fonction de votre situation spécifique et des menaces potentielles auxquelles vous pourriez être confronté. La modélisation des menaces vous aide à identifier, comprendre et hiérarchiser les menaces et vulnérabilités potentielles propres à votre situation. Tenez compte des aspects suivants lors de la modélisation des menaces :

1. **Identifier vos actifs** : déterminez ce que vous devez protéger, comme vos données personnelles, vos informations financières ou des documents professionnels confidentiels.

2. **Identifier les adversaires potentiels** : réfléchissez à qui pourrait vouloir accéder à vos actifs ou les compromettre. Cela peut inclure des pirates, des voleurs, des agences gouvernementales ou même des personnes que vous connaissez.

3. **Identifier les vecteurs d'attaque potentiels** : réfléchissez aux différentes façons dont un adversaire pourrait accéder à vos actifs, comme le vol physique, le piratage réseau, l'ingénierie sociale ou les logiciels malveillants.

4. **Évaluer la probabilité et l'impact des menaces** : évaluez la probabilité de chaque menace et les dommages potentiels qu'elle pourrait causer. Donnez la priorité aux menaces les plus probables et ayant le plus grand impact.

5. **Déterminer les mesures d'atténuation appropriées** : sur la base de votre évaluation des menaces, identifiez les mesures de sécurité qui atténueraient le plus efficacement vos principales menaces. Cela peut inclure un chiffrement robuste, l'authentification à deux facteurs, des contrôles de sécurité physique ou l'utilisation d'applications et de services axés sur la confidentialité.

N'oubliez pas que la modélisation des menaces n'est pas un exercice ponctuel. À mesure que votre situation et le paysage de la sécurité évoluent, réévaluez périodiquement vos menaces et ajustez votre posture de sécurité en conséquence.

### Ressources de modélisation des menaces
- [EFF Surveillance Self-Defense Guide](https://ssd.eff.org/) : comprend une section sur l'évaluation de vos risques et la création d'un plan de sécurité.
- [OWASP Threat Modeling](https://owasp.org/www-community/Application_Threat_Modeling) : fournit une introduction à la modélisation des menaces pour la sécurité des applications, mais nombre de principes s'appliquent plus largement.

En prenant le temps de comprendre votre paysage de menaces unique, vous pouvez vous assurer que vos efforts de sécurité se concentrent là où ils auront le plus grand impact pour protéger vos appareils iOS et vos données.

## Outils d'audit de sécurité
Envisagez d'utiliser des outils d'audit de sécurité comme [iVerify](https://www.iverify.io) pour vérifier votre appareil à la recherche de vulnérabilités et de mauvaises configurations.

## Paramètres de confidentialité de Siri
Gérez l'accès à Siri sous `Settings → Siri & Search` pour une meilleure confidentialité. Envisagez de désactiver « Listen for “Hey Siri” » pour minimiser le partage de données.

## Sécuriser les réglages iCloud
Vérifiez régulièrement vos réglages iCloud. Activez l'authentification à deux facteurs et utilisez le chiffrement de bout en bout lorsque c'est possible.

## Paramètres de confidentialité et de sécurité de Safari
Renforcez votre confidentialité dans Safari en activant les avertissements de sites frauduleux et en gérant efficacement les cookies. Envisagez de désactiver JavaScript pour plus de sécurité.

## Ajustements détaillés des paramètres de confidentialité
Limitez l'accès à Siri et désactivez les notifications pour les applications sensibles. Dans Safari, utilisez la navigation privée et désactivez les suggestions — refusez le partage de données analytiques pour une confidentialité renforcée.

## Écoute en temps réel (Live Listen)

« Écoute en temps réel » (Live Listen) transforme l'iPhone en microphone distant : le son capté par l'iPhone est transmis en direct à des AirPods, à des écouteurs Beats compatibles ou à des appareils auditifs « Made for iPhone » (MFi). C'est une fonction d'accessibilité, mais elle peut aussi servir à écouter une conversation à distance. Il faut donc vérifier qu'elle n'est pas active sans raison.

**Depuis quand ?**
- 2014 : lancement pour les appareils auditifs MFi.
- iOS 12 (2018) : extension aux AirPods.
- iOS 14.3 (2020) : version minimale exigée par Apple pour les AirPods et les Beats.
- iOS 26 (2025) : ajout des sous-titres en direct et du contrôle depuis l'Apple Watch ou un autre appareil connecté au même compte Apple.

**Session d'écoute ou contrôle à distance ?**
Deux réglages différents existent dans `Réglages → Accessibilité → Audio et visuel → Écoute en temps réel` :
- **La session d'écoute** (« Démarrer / Arrêter l'écoute en temps réel ») : elle seule active réellement le microphone. Si elle est arrêtée, aucune écoute n'est en cours.
- **« Contrôle à distance »** : autorise un appareil voisin connecté au même compte Apple (Apple Watch, autre iPhone ou iPad) à démarrer, arrêter ou rembobiner une session. Ce réglage peut être activé par défaut sur les versions récentes d'iOS ; coché ne signifie pas qu'une écoute est en cours, mais il permet à un appareil de confiance de la lancer.

**Vérifier qu'aucune écoute n'est active :**
1. Ouvrez le Centre de contrôle : le bouton « Écoute en temps réel » ne doit pas être allumé.
2. Dans `Réglages → Accessibilité → Audio et visuel → Écoute en temps réel`, la session doit être arrêtée (le bouton doit afficher « Démarrer l'écoute en temps réel »).
3. Un point orange (ou une pastille rouge) en haut de l'écran indique que le microphone est utilisé ; vérifiez quelle app ou fonction en est responsable.
4. Sur iOS 18 et versions antérieures, passez par `Centre de contrôle → Audition → [vos AirPods] → Écoute en temps réel`. Pour des appareils auditifs : `Réglages → Accessibilité → Appareils auditifs`.

**Désactiver et verrouiller :**
1. Arrêtez la session en cours (Centre de contrôle ou réglage ci-dessus).
2. Désactivez **« Contrôle à distance »** si vous n'utilisez ni Apple Watch ni appareil auditif.
3. Retirez le contrôle « Écoute en temps réel » / « Audition » du Centre de contrôle (`Réglages → Centre de contrôle`).
4. Retirez-le du raccourci Accessibilité (`Réglages → Accessibilité → Raccourci Accessibilité`).
5. Sur l'Apple Watch, retirez le contrôle « Audition » de son Centre de contrôle.
6. Pour des appareils auditifs, désactivez « Contrôler sur l'écran verrouillé » dans `Réglages → Accessibilité → Appareils auditifs`.
7. Vérifiez les appareils connectés à votre compte Apple et retirez ceux que vous ne reconnaissez pas.

**À ne pas confondre avec :** Siri et « Dis Siri » (écoute du mot d'éveil), la reconnaissance des sons, les sous-titres en direct et l'autorisation micro accordée aux apps (`Réglages → Confidentialité et sécurité → Microphone`).

**Références :** [Utiliser l'iPhone comme micro distant avec Écoute en temps réel](https://support.apple.com/fr-fr/guide/iphone/iph8bf9386f5/ios) · [Contrôler Écoute en temps réel depuis l'Apple Watch](https://support.apple.com/fr-fr/guide/watch/apd4f5b634f3/watchos).

## Rester sécurisé avec les mises à jour iOS
Mettez régulièrement à jour iOS vers la dernière version pour bénéficier des correctifs de sécurité les plus récents. Gardez également vos applications à jour.

## Mesures de sécurité physique de l'appareil
Ne laissez jamais votre appareil sans surveillance dans les lieux publics. Utilisez des fonctionnalités comme Find My iPhone pour la récupération en cas de vol. Utilisez une coque de protection, un protecteur d'écran et tenez l'appareil à l'écart des températures extrêmes.

## Les risques du jailbreak
Le jailbreak expose votre appareil à des risques de sécurité supplémentaires. Il est généralement conseillé d'éviter le jailbreak pour maintenir la sécurité de l'appareil.

## Sauvegardes sécurisées
Utilisez toujours des sauvegardes chiffrées et testez régulièrement la restauration des sauvegardes pour garantir l'intégrité des données.

## Alternatives au transfert de données et à iCloud
Explorez des services cloud sécurisés comme Proton Drive et privilégiez les transferts de données physiques (comme USB) aux transferts sans fil pour les données sensibles.

## Temps d'écran et restrictions pour renforcer la sécurité
Utilisez Temps d'écran pour appliquer des restrictions de contenu et de confidentialité, empêchant toute modification non autorisée des réglages de votre appareil. Cela est particulièrement utile si quelqu'un découvre le code d'accès de votre appareil.

## Optimiser les services système pour la confidentialité
Ajustez finement `Settings → Privacy & Security → Location Services → System Services`. Désactivez les services non essentiels comme `Location-Based Apple Ads` et `Significant Locations` pour minimiser la collecte de données de localisation.

## Comprendre et utiliser le mode Isolement (Lockdown Mode)
Le mode Isolement (Lockdown Mode) est conçu pour les utilisateurs exposés à un risque élevé de cyberattaques ciblées. Il limite certaines fonctionnalités afin de réduire la surface d'attaque de l'appareil. Activez-le sous `Settings → Privacy & Security → Lockdown Mode`, mais sachez qu'il restreindra de nombreuses fonctionnalités standard. Familiarisez-vous avec le mode Isolement et ses implications.

## Apprendre à utiliser Emergency SOS

Emergency SOS est une fonctionnalité essentielle qui peut vous aider à appeler rapidement à l'aide et à protéger votre appareil dans des situations dangereuses. Lorsqu'elle est activée, elle désactive Touch ID et Face ID jusqu'à ce que vous saisissiez votre code d'accès et, en option, elle peut appeler automatiquement les services d'urgence (le 911 aux États-Unis).

**Comment activer Emergency SOS :**

Il existe deux façons d'activer Emergency SOS :

1. **Appel avec 5 pressions sur le bouton** : appuyez rapidement 5 fois sur le bouton latéral. À la fin du compte à rebours, l'iPhone appelle les services d'urgence.

2. **Appel par maintien puis relâchement** : maintenez enfoncé le bouton latéral et l'un des boutons de volume. Un compte à rebours commence et une alarme retentit. Après le compte à rebours, si vous relâchez les boutons, l'iPhone appelle les services d'urgence. Dans certaines régions, vous devrez peut-être préciser le service d'urgence à appeler.

<img src="https://github.com/iAnonymous3000/iOS-Hardening-Guide/assets/32236127/dd060751-efb0-4ac8-a02a-18a2badb081b" alt="emergency_sos_activation" width="300">

Si nécessaire, vous pouvez appeler les services d'urgence en faisant glisser le curseur Emergency SOS à l'écran.

**Activer l'appel automatique :**

Vous pouvez configurer votre appareil pour appeler automatiquement les services d'urgence après l'apparition de l'écran Emergency SOS. L'appel est effectué après un compte à rebours de 8 secondes. Pour activer l'appel automatique :

1. Ouvrez l'application Réglages.
2. Touchez Emergency SOS.
3. Activez les boutons « Call with Hold » et « Call with 5 Presses ».

Il existe deux façons d'utiliser l'appel automatique :
1. Appel après 5 pressions : continuez de maintenir les boutons d'alimentation et de volume pendant plus de 10 secondes.
2. Appel par maintien : maintenez les boutons pendant plus de 10 secondes.

<img src="https://github.com/iAnonymous3000/iOS-Hardening-Guide/assets/32236127/52685c01-9843-4ce3-a86d-be993c72e772" alt="emergency_sos_settings" width="300">

**Configurer les contacts d'urgence :**

Vous pouvez demander à Emergency SOS d'afficher un contact d'urgence en sélectionnant « Set up Emergency Contacts in Health » dans les réglages Emergency SOS.

**Recommandations d'amélioration :**

Bien qu'Emergency SOS soit une fonctionnalité précieuse, certaines améliorations potentielles pourraient la rendre encore plus efficace :

- Mettre en œuvre un geste discret ou une combinaison de boutons pour déclencher Emergency SOS sans attirer l'attention dans des situations dangereuses.
- Permettre aux utilisateurs de personnaliser le compte à rebours de l'appel automatique (par exemple, options de 3, 5 ou 8 secondes).
- Activer l'envoi de SMS d'urgence automatisés aux contacts désignés lorsque Emergency SOS est activé, y compris les informations de localisation si possible.
- Fournir des indications sur les informations à transmettre à l'opérateur d'urgence, en particulier dans des situations dangereuses.
- Discuter de l'utilisation d'Emergency SOS en combinaison avec d'autres fonctionnalités d'urgence d'iOS comme Medical ID et Emergency Contacts.

En vous familiarisant avec Emergency SOS et en comprenant comment l'activer, vous serez mieux préparé à réagir aux situations d'urgence et à protéger votre appareil et vos informations personnelles.

## Activer le mode USB restreint

L'activation du mode USB restreint renforce encore la sécurité de votre appareil iOS. Cette fonctionnalité empêche les accessoires USB de se connecter lorsque votre appareil est verrouillé depuis plus d'une heure, ce qui protège contre les tentatives d'accès non autorisées via le port Lightning.

**Fonctionnement :** Lorsque le mode USB restreint est activé, votre iPhone ou iPad ne communique pas avec les accessoires USB si l'appareil est verrouillé depuis plus d'une heure. Cela empêche les attaquants potentiels d'utiliser des accessoires USB pour contourner l'écran verrouillé ou extraire des données, même s'ils ont un accès physique à votre appareil.

**Protection contre les outils de piratage :** Le mode USB restreint protège également contre les outils de piratage comme GrayKey et Cellebrite, qui peuvent être utilisés pour contourner l'écran verrouillé en se connectant au port Lightning. En activant cette fonctionnalité, vous ajoutez une couche de sécurité supplémentaire à la protection par code d'accès de votre appareil.

**Activer le mode USB restreint :**

1. Accédez à `Settings → Touch ID/Face ID & Passcode`.

2. Assurez-vous que l'option « Accessories » est désactivée sous « Allow Access When Locked ».

<img src="https://github.com/iAnonymous3000/iOS-Hardening-Guide/assets/32236127/d378c0c6-4427-4d6a-aae8-bdebb7465f46" alt="usb_restricted_mode_settings" width="300">

Lorsque ce réglage est désactivé, votre iPhone affiche le message suivant :

« Unlock iPhone to allow accessories to connect when it has been more than an hour since your iPhone was locked. »

Cela confirme que le mode USB restreint est actif et empêchera les accessoires USB de se connecter si l'appareil est verrouillé depuis plus d'une heure.

**Pourquoi c'est important :** L'activation du mode USB restreint est particulièrement importante si votre iPhone ou iPad contient des données personnelles ou professionnelles sensibles. Elle contribue à garantir que ces données restent sécurisées même si votre appareil est perdu ou volé, offrant un moyen simple mais efficace de renforcer la sécurité de votre appareil et de vous protéger contre les tentatives d'accès non autorisées.

## Gérer les alertes d'urgence et les fausses alertes de confidentialité
Comprenez que certaines alertes gouvernementales peuvent contourner vos réglages. Vérifiez vos réglages si iOS signale un avertissement de confidentialité en raison de modifications DNS. Ces avertissements peuvent souvent être ignorés pour des configurations DNS sécurisées.

## Gestion des mots de passe et sécurité des comptes
Utilisez des mots de passe robustes et uniques pour tous les comptes, pas seulement pour le code d'accès de votre appareil. Envisagez d'utiliser un gestionnaire de mots de passe pour générer et stocker des mots de passe complexes en toute sécurité.

## Implications pour la confidentialité des sauvegardes iCloud
Les sauvegardes iCloud, bien que pratiques, peuvent ne pas offrir le même niveau de confidentialité que les sauvegardes locales. Envisagez d'utiliser des alternatives sécurisées pour les données sensibles.

## Scénarios de modélisation des menaces
Voici quelques scénarios de menaces courants et les mesures de sécurité les plus pertinentes pour chacun :

1. **Appareil perdu ou volé** : activez Find My, utilisez un code d'accès robuste et envisagez d'activer Stolen Device Protection. Sauvegardez régulièrement vos données.
2. **Attaque cyber ciblée** : utilisez le mode Isolement, maintenez votre appareil et vos applications à jour, et soyez prudent lors de l'installation d'applications provenant de sources inconnues.
3. **Violations de données** : utilisez des mots de passe uniques et robustes pour chaque compte, activez l'authentification à deux facteurs partout où c'est possible et surveillez vos comptes pour détecter toute activité suspecte.

## Se débarrasser en toute sécurité des anciens appareils
Avant de vous débarrasser d'un ancien appareil, assurez-vous de déconnecter tous les comptes, d'effectuer une réinitialisation d'usine et de retirer la carte SIM. Détruisez physiquement l'appareil s'il contenait des données hautement sensibles.

## Compromis de confidentialité de Find My
Bien que Find My soit précieux pour localiser un appareil perdu ou volé, il implique de partager les données de localisation de votre appareil avec Apple. Tenez compte de ce compromis dans votre modèle de menace.

## Utiliser Apple Pay et les fonctionnalités Wallet en toute sécurité
Lors de la configuration d'Apple Pay ou d'autres fonctionnalités Wallet, vérifiez que vous êtes sur un appareil et un réseau de confiance. Utilisez Touch ID, Face ID ou un code d'accès robuste pour les transactions.

## Sensibiliser famille et amis aux bonnes pratiques de sécurité
Votre sécurité n'est aussi solide que votre maillon le plus faible. Encouragez votre famille et vos amis à suivre également de bonnes pratiques de sécurité, surtout si vous communiquez fréquemment avec eux.

## Gérer les appareils IoT et leurs accès
Soyez attentif aux appareils IoT que vous connectez à vos appareils Apple. Vérifiez régulièrement leurs autorisations et leurs accès, et utilisez des mots de passe robustes et uniques pour leurs comptes.

## Mettre en perspective les risques du jailbreak
Le jailbreak permet aux utilisateurs de contourner de nombreuses restrictions de sécurité d'iOS, ce qui peut être attrayant pour la personnalisation et l'accès à certaines applications. Cependant, il expose l'appareil à des risques de sécurité importants et devrait être évité pour la plupart des utilisateurs.

## Mises à jour et révisions régulières

### Se tenir informé de l'évolution d'iOS
- **Un paysage de la sécurité en constante évolution** : le domaine de la sécurité et de la confidentialité d'iOS évolue continuellement. Les nouvelles mises à jour d'Apple introduisent souvent des changements dans les fonctionnalités, les réglages et les protocoles de sécurité.
- **Engagement de mise à jour** : nous nous engageons à maintenir ce guide à jour avec les dernières informations et bonnes pratiques. Cela garantit que les conseils et stratégies fournis ici restent pertinents et efficaces.
- **Recommandation aux lecteurs** : nous encourageons les lecteurs à consulter régulièrement ce guide. Se tenir informé des dernières mises à jour et révisions vous aidera à maintenir le plus haut niveau de sécurité et de confidentialité sur vos appareils iOS.
- **Contributions de la communauté** : vos retours et contributions sont précieux pour maintenir ce guide complet et à jour. N'hésitez pas à suggérer des mises à jour ou de nouvelles informations susceptibles d'être utiles.

### Suivre les mises à jour iOS
- **Vérifier les mises à jour iOS** : vérifiez et installez régulièrement les dernières mises à jour iOS sur votre appareil. Ces mises à jour contiennent souvent des correctifs de sécurité essentiels et des améliorations de fonctionnalités.
- **Consulter les mises à jour du guide** : après avoir mis à jour iOS, consultez à nouveau ce guide pour vous assurer que vos paramètres et pratiques de sécurité correspondent aux nouveaux changements introduits par la mise à jour.

## Ressources externes pour aller plus loin
- [Into the Cyberverse](https://alternativeto.net/list/34604/cyberverse) - La liste ultime d'applications et de services pour améliorer la sécurité, la confidentialité et l'anonymat
- [Apple Platform Security Guide](https://support.apple.com/guide/security/welcome/web) : guide détaillé d'Apple sur les fonctionnalités de sécurité de ses plateformes.
- [Apple's Privacy Website](https://www.apple.com/privacy/) : présentation par Apple de son approche de la confidentialité.
- [OWASP Mobile Security Testing Guide](https://owasp.org/www-project-mobile-security-testing-guide/) : manuel complet pour les tests de sécurité des applications mobiles et l'ingénierie inverse.
- [Personal Safety User Guide for Apple Devices](https://help.apple.com/pdf/personal-safety/en_US/personal-safety-user-guide.pdf) : guide officiel d'Apple pour toute personne concernée par les abus, le harcèlement ou la traque facilités par la technologie.
- [r/privacy Wiki](https://www.reddit.com/r/privacy/wiki/index) : le wiki du subreddit r/privacy, qui contient une multitude de ressources liées à la confidentialité.

## Retours et contributions
Nous vous remercions de vos suggestions et de vos retours. Si vous avez des idées pour améliorer ce guide, n'hésitez pas à ouvrir une issue sur ce dépôt GitHub ou à soumettre une pull request avec vos contributions.

N'oubliez pas que la sécurité est un processus continu. Restez vigilant, continuez à apprendre et privilégiez toujours la protection de vos données personnelles. Ensemble, nous pouvons créer un environnement numérique plus sûr et plus respectueux de la confidentialité.

Merci d'utiliser le guide ultime du durcissement d'iOS !
