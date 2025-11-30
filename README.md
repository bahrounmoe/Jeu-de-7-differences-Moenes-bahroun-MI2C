# Jeu-de-7-differences-Moenes-bahroun-MI2C

Spot The 7 Differences - Jeu des 7 Différences 🎮

-Description du Projet

        Spot The 7 Differences est un jeu interactif développé en HTML, CSS et JavaScript où les joueurs doivent trouver les différences entre deux images similaires. Le jeu propose plusieurs niveaux de difficulté avec des contraintes de temps différentes pour une expérience de jeu stimulante.


-Technologies Utilisées

        HTML5 : Structure de la page et éléments du jeu
        CSS3 : Styles, animations et design responsive
        JavaScript : Logique du jeu, gestion des événements et interactions
        Google Fonts : Police "Press Start 2P" pour un style rétro pixelisé

-Fonctionnalités Principales
    -Système de Jeu

        Deux niveaux de difficulté :
        Niveau 1 (Robots) : 7 différences en 100 secondes
        Niveau 2 (Chats) : 9 différences en 60 secondes
        Timer dynamique avec compte à rebours
        Système de score basé sur le temps restant et différences trouvées
        Marquage visuel des différences trouvées

    -Interface Utilisateur

        Design rétro pixelisé avec animations
        Navigation intuitive entre les écrans
        Écrans dédiés : Accueil, Aide, Sélection de niveau, Jeu
        Modal de résultats avec score final

    -Fonctionnalités Avancées
        
        Système d'indices pour aider le joueur
        Feedback visuel (marqueurs verts pour les bonnes réponses, croix rouges pour les erreurs)
        Animation de pulsation pour les différences trouvées
        Transition fluide entre les niveaux

-Lien GitHub Pages
        
        Jouer au jeu sur GitHub Pages

-Nouveautés Explorées
    -Apprentissages Techniques

        Gestion d'état complexe avec un objet gameState centralisé
        Calcul de positions relatives pour la détection des clics
        Système de coordonnées pour le positionnement des différences
        Gestion du temps avec setInterval() et clearInterval()

    -Développements Créatifs
    
        Animations CSS avancées (@keyframes, transformations)
        Design responsive avec Flexbox
        Effets visuels : ombres, dégradés, transitions
        Système de modals pour les résultats

    -Concepts Découverts

        Architecture modulaire pour les différents écrans
        Gestion d'événements sur zones interactives
        Calcul de distance pour la tolérance de clic
        Système de scoring avec bonus de temps

-Difficultés Rencontrées
    -Problèmes Techniques
        
        -Détection précise des clics sur les différences
            Problème : Coordonnées absolues vs relatives
            Solution : Utilisation de getBoundingClientRect()

        -Synchronisation des marqueurs entre les deux images
            Problème : Positionnement incohérent
            Solution : Système d'index unique pour chaque différence

        -Gestion du timer lors des changements d'écran

            Problème : Timer qui continue en arrière-plan
            Solution : clearInterval() systématique

        -Chargement des images externes

            Problème : Chemins d'accès et temps de chargement
            Solution : Pré-chargement et gestion d'erreurs

-Problèmes Conceptuels

        Balance difficulté entre les niveaux
        Problème : Niveau 2 trop difficile
        Solution : Ajustement du temps et nombre de différences
        Feedback utilisateur pour les mauvais clics
        Problème : Manque d'indication visuelle
        Solution : Animation de croix rouge temporaire

-Solutions Apportées
    
    -Méthodologie de Résolution
        Recherche documentaire :
        Documentation MDN sur les événements de souris
        Tutoriels sur les animations CSS
        Exemples de jeux similaires
        Approche itérative :
        Prototypage rapide des fonctionnalités
        Tests utilisateurs réguliers
        Ajustements basés sur le feedback
        Debugging systématique :
        Console logs pour le suivi des états
        Validation des coordonnées
        Tests sur différents navigateurs

-Outils Utilisés
        
        Chrome DevTools pour le debugging
        Visual Studio Code avec extensions HTML/CSS/JS
        Git pour le versioning
        Google Fonts pour la typographie

-Améliorations Futures

        Ajouter plus de niveaux avec différentes thématiques
        Implémenter un système de highscores persistants
        Ajouter des effets sonores
        Créer un mode multijoueur
        Optimiser pour mobile avec touch events