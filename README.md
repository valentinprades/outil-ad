# Outil-AD 🏢

> **Le catalogue de GPO et générateur de scripts conçu pour accompagner l'apprentissage d'Active Directory.**

L'administration d'un domaine Windows Server et la sécurisation d'un parc informatique via les stratégies de groupe (GPO) sont des piliers de l'ingénierie système. **Outil-AD** a été développé pour centraliser, vulgariser et simplifier l'accès à ces configurations indispensables.

## 🎓 Intention Pédagogique & Accompagnement
Comprendre Active Directory demande souvent de naviguer dans des menus complexes. Cet outil a été pensé comme un fil conducteur pédagogique pour :
* **Démystifier le "Hardening" (Sécurisation) :** Permettre aux apprenants d'assimiler les bonnes pratiques de sécurité (recommandations ANSSI/CIS Benchmarks) sans se perdre dans la console GPMC.
* **Faire le lien entre l'interface et le système :** En montrant concrètement quelle clé de registre Windows est modifiée par quelle stratégie, l'outil aide à comprendre la mécanique profonde de l'OS.
* **Passer à l'automatisation :** Accompagner la transition cruciale entre l'administration graphique et l'administration par script (PowerShell).

## 🛠️ Ce que propose l'outil
* **Le Catalogue de GPO :** Une classification claire par thématiques (Sécurité, Réseau, Système...) des stratégies de groupe les plus utilisées en entreprise.
* **Fiches d'identité des stratégies :** Chaque GPO est présentée avec sa description, son chemin exact dans l'éditeur et son impact dans la base de registre (`HKLM`/`HKCU`).
* **Générateurs de scripts :** Des outils d'aide à la syntaxe pour générer des commandes d'administration et automatiser les tâches courantes.

## ⚙️ Note sur la conception
Créé sans infrastructure de développement lourde, ce projet repose sur une architecture web simple et autonome (HTML/CSS/JS). Il a été conçu par un technicien en formation pour répondre aux réalités concrètes de l'apprentissage du système, garantissant un outil léger, sans fioritures et directement opérationnel.

## 🤝 Appel aux Contributions !
La sécurité et les systèmes évoluent vite. Vous pouvez participer à cet effort altruiste :
* En ajoutant de nouvelles fiches de GPO au catalogue.
* En proposant des snippets de scripts PowerShell utiles pour le quotidien d'un administrateur.
* En signalant des erreurs de chemins ou de syntaxes.

## ⚖️ Licence & Philosophie
Ce projet est partagé sous licence **Creative Commons CC BY-NC-SA 4.0**. 
Il a été conçu dans un but d'entraide et d'accès libre au savoir. Les centres de formation et les étudiants sont encouragés à l'utiliser, le dupliquer et l'adapter librement, tant que l'usage reste non commercial et partagé sous cette même philosophie.
