# secret_number_v2
Le Jeu du Nombre Mystère est un mini‑projet en JavaScript qui met le joueur au défi de deviner un nombre aléatoire généré par l’ordinateur.


🕹️ Fonctionnement
Le joueur choisit un niveau de difficulté :

Débutant → nombre entre 0 et 10, 3 tentatives

Intermédiaire → nombre entre 0 et 100, 5 tentatives

Expert → nombre entre 0 et 1000, 7 tentatives

GOAT → nombre entre 0 et 10000, 20 tentatives

Le jeu génère un nombre secret dans la plage choisie.

Le joueur saisit ses propositions via un champ de saisie.

Le programme indique si la valeur est trop grande ou trop petite.

Si le joueur trouve le bon nombre → 🎉 victoire avec bonus.

Si le joueur échoue après toutes ses tentatives → 😢 défaite.

⚡ Système de score
Chaque victoire rapporte des points de base selon le niveau.

Des bonus/malus s’ajoutent :

Bonus selon le nombre de tentatives (plus vite = plus de points).

Bonus selon la rapidité (chrono en secondes).

Le score est cumulatif et un High Score est conservé.

Le joueur est classé en fonction de son score total :

🟢 Débutant → ≤ 20 points

🟡 Intermédiaire → ≤ 50 points

🔴 Expert → ≤ 200 points

🟣 God → > 200 points

🎨 Interface
Fond dégradé bleu moderne.

Boutons dorés animés pour choisir la difficulté.

Tableau de score (scoreboard) affichant :

Score total

High Score

Niveau actuel

Chrono ⏱ en direct

🔊 Immersion
Effet sonore de victoire (cloche joyeuse).

Effet sonore de défaite (bruit triste).

Messages dynamiques affichés directement sur la page.
