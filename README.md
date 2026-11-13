# Blitz Manager - FR

Jeu de gestion de Blitzball dans le navigateur : compose ton équipe, règle ta tactique, mène ton club saison après saison.

Jouer : https://ravagedking.github.io/blitz-manager/

- Un seul fichier HTML, aucune installation, FR (défaut) et EN.
- Les parties sont sauvegardées dans ton navigateur, pour cette adresse seulement.
- Version en test : d'une version à l'autre, les sauvegardes ne sont pas compatibles, on repart d'une partie neuve. Export / import de sauvegarde par fichier et par copier-coller disponibles depuis la v0.6.3.

Hommage non commercial et sans but lucratif au mini-jeu Blitzball de Final Fantasy X. 
Projet de fan, sans lien avec Square Enix ; les noms et termes d'origine appartiennent à leurs ayants droit. Les marques citées appartiennent à leurs propriétaires.

VERSION ACTUELLE : V0.31



NOTES DE VERSION :

Les versions sont numérotées v0.x : toute la phase actuelle est l'Alpha. Quand une version satisfera pleinement son créateur, elle deviendra la Bêta (tests, petits changements), puis viendra la v1.0.


v0.31 : Un stade qui grandit
Mécanique
- Le stade évolue par paliers (T1 à T4) : chaque palier se paie et ouvre des installations et des niveaux plus élevés selon ta division (Semi-Pro 3 : T1, Semi-Pro 2 : T2, Semi-Pro 1 : T3, division 3 et au-dessus : T4)
- Prix du palier (selon la division) : T2 de 7 000 à 9 000, T3 18 000, T4 40 000
- Une relégation ne te fait rien perdre : installations et palier restent à toi
- Le palier ne rapporte rien par lui-même : les revenus viennent toujours des installations

Interface
- Club › Finances : ligne Palier avec bouton « Agrandir », prix affiché et raison quand c'est impossible (division, fonds)
- Les tribunes autour de la Sphère grandissent avec le palier
- Club › Personnalisation : 3 nouvelles eaux (Rubis, Olive, Ardoise), 3 nouveaux ballons (Lime, Rose, Argent), 4 styles de tribunes et la couleur des sièges
- Règles du jeu : nouvelle section sur les paliers de stade

v0.30 : Identité du club
Interface
- Slogan du club (32 caractères), affiché sur la Fiche du club et à l'Accueil.
- Éditeur de blason 24×24 avec zoom ; les anciens blasons restent tels quels et passent en 24×24 sur demande.
- Palette portée à 60 couleurs.
- Nouveau sélecteur « Jeu porté » (Club › Personnalisation) : Auto, Domicile, Extérieur ou maillot Unique ; l'adversaire s'adapte à ton choix.
- Le jeton de la Sphère prend la forme de l'écusson, et le visiteur porte un anneau intérieur pour le distinguer.
Contenu
- Maillots Domicile et Extérieur personnalisables.
- Quatre maillots Uniques à débloquer par code, dont deux avec un effet visuel (arrêté si les animations sont réduites ou désactivées).
- ULTIMATEST débloque aussi ces quatre maillots.
Mécanique
- Tout est cosmétique : aucun effet sur les matchs ni sur l'économie. Les anciennes sauvegardes se chargent sans perte.
Correctifs
- Un long slogan ne fait plus déborder la Fiche du club sur petit écran.

v0.29 : Records, anti-titres et cérémonie de fin de saison
Mécanique
- Nouveaux compteurs de carrière par joueur : distance de passes, passes longues, blocs.
- Titres de statistique supplémentaires et six anti-titres (les pires de la saison), plus un « Pire joueur » et le joueur de la semaine.
- Records du club et du jeu : un record battu est annoncé dans le Journal.
- Deux nouveaux titres de jeu (12 au total), débloqués par le jeu.

Interface
- Cérémonie de fin de saison en 3 étapes, que tu peux passer à tout moment. Elle se désactive dans Options › Affichage.
- Palmarès : l'historique est replié par saison (les deux dernières sont dépliées).
- Fiche du joueur : carrière, records et distinctions.
- Club › Entraîneur : les Badges se replient sur petit écran (sous 700 px), plus de page trop longue sur mobile.
- Règles du jeu et actualité du titre mises à jour.

Contenu
- Les Remerciements et les nouveautés du dernier patch restent affichés sur l'écran titre.

Correctifs
- Le texte de la condition de Dynastie précise maintenant qu'il s'agit des championnats de division.
- Club › Entraîneur ne dépasse plus la hauteur prévue à 390 px.

v0.28 : Titres de jeu, cadres de division et fonds animés
Mécanique

Dix Titres de jeu à gagner en jouant (championnats, coupes, défis, séries…), avec des paliers.
Les Titres évidents sont visibles, grisés, avec leur condition et leur progression. Les secrets n’apparaissent qu’une fois obtenus.
Sept cadres de portrait selon la division remportée.
Compteurs de carrière conservés d’une saison à l’autre.
Le mode « Auto » du titre et du cadre disparaît : rien n’est affiché tant que tu ne l’as pas choisi.

Interface

Club › Entraîneur : catalogue des Titres, titre au-dessus du nom (reflet lent au palier Diamant).
Cinq fonds animés dans Options › Affichage › Fond.
Nouvelle catégorie « Divers » dans le Journal. Les déblocages sont groupés dans une seule notification.
Vocabulaire harmonisé : « Championnats gagnés ».

Contenu

Cinq codes de fond : THUNDERBG, FIREBG, AQUABG, LIGHTBG, DARKBG. ULTIMATEST débloque désormais tous les cosmétiques à code.

Correctifs

Les deux libellés « titres de champion » restants sont corrigés.

v0.27 : Profil de l’entraîneur et codes

Interface
Le profil de l’entraîneur tient dans un seul bloc : portrait avec cadre, titre en petit au-dessus du nom, et un crayon pour modifier nom, portrait, cadre et titre.
La liste des Distinctions est plus courte (« ×n »).
Les sélecteurs de cadre et de titre restent masqués tant qu’aucun code n’a été entré.
Contenu
12 codes dans Options › Codes : CREATOR, un cadre et un titre pour la foudre, le feu, l’eau, la lumière et les ténèbres, ainsi que ULTIMATEST qui débloque tout.
Les cadres et titres sont animés (fixes si les animations sont réduites dans le système).
Correctifs
Le message d’erreur d’import de sauvegarde ne cite plus de numéro de version.
Le vocabulaire est unifié : « Distinctions » pour ce qu’on gagne, « Titres » pour ce qu’on affiche.
Deux libellés de ce vocabulaire restent à corriger dans la prochaine version.

v0.26 : Distinctions et Palmarès

Mécanique
- Récompenses de fin de saison pour toute la division : meilleur joueur, meilleur de chaque poste, meilleur espoir (23 ans ou moins), meilleurs buteur, passeur, passes, tacles, interceptions, récupérations, arrêts et clean sheets, et équipe type de la division. Il faut avoir joué au moins 60 % des matchs. Ces distinctions sont purement honorifiques.
- Le « Meilleur joueur » est évalué par rapport à son poste, pour ne pas toujours revenir à un attaquant.
- Nouvelles statistiques suivies pour tous les joueurs, par saison et en carrière : arrêts, clean sheets, tacles, interceptions et passes.
- Nouveaux titres : « Doublé des tournois » (les deux tournois la même saison, remplace « Double couronné ») et « Triplé » (champion de sa division et vainqueur des deux tournois la même saison).
- Défis ordinaires recalés en Semi-Pro : ils sont mieux équilibrés dans les trois divisions.

Interface
- Nouvelle page Club › Palmarès : vitrine, récompenses de la saison, équipe type, lauréats du club et palmarès.
- Marqueurs de division à côté du blason : couronne à effet diamant (Élite), étoiles (D1 à D3) et triangles (Semi-Pro), en bronze, argent et or.
- Tu choisis ton titre affiché et ton cadre de portrait dans l'Entraîneur.
- Nouvelle page Options › Codes, avec les cadres de portrait animés Foudroyant et Enflammé.
- Règles du jeu complétées.

Contenu
- Codes de test : CREATOR (titre « Le Créateur »), THUNDERFRAME (cadre foudroyant) et FIREFRAME (cadre enflammé).

Correctifs
- Tests de navigation plus fiables ; scripts de test anciens archivés.

v0.25 : Semi-Pro

Mécanique
- Nouveau parcours Semi-Pro : tu pars du dernier niveau d'une pyramide à 7 divisions (104 clubs) et tu montes jusqu'à l'Élite.
- Licence professionnelle : pour accéder aux divisions pro, il faut une trésorerie d'au moins 20 000 gils, une confiance d'au moins 60 et une installation au niveau 1. Une fois obtenue, elle est acquise pour toute la partie.
- Recettes, staff, entretien et installations sont indexés sur la division ; budgets de départ de Semi-Pro ajustés (37 500 / 29 000 / 18 000 gils).
- Les Uniques du Marché suivent le niveau de la division en Semi-Pro.
- GAMOSIC est verrouillé en Semi-Pro.
- Les anciennes sauvegardes (versions 11 et 12) ne sont plus acceptées : commence une nouvelle partie.

Interface
- Nouvelle étape « Parcours » (Semi-Pro / Pro) à la création de la partie.
- Carte de la licence professionnelle avec ses trois conditions et messages d'avancement.
- L'actualité du titre et le message « sous réserve de la licence » sont corrigés.

Contenu
- Plafonds de salaire et réputation de départ étendus aux 7 niveaux.

Correctifs
- Hauteur de l'Accueil à 390 px alignée sur la nouvelle cible.
- Les tests de vérification complets sont désormais intégrés à la suite de tests.

v0.24 : Légendes et GAMOSIC en 5 échelons

Mécanique
- Le catalogue passe à 11 Uniques, dont Daymon Sky ; tous ont un potentiel de 93.
- Les Légendes (potentiel 98) existent dans GAMOSIC seulement : jamais dans un effectif, non vendables.
- Plafond de salaire par division pour les Uniques (Élite 2 430, D1 900, D2 690, D3 530 par journée).
- Les anciennes sauvegardes sont migrées automatiquement : les Uniques supprimés deviennent des joueurs ordinaires.

Interface
- GAMOSIC : menu d'échelon (Division 3 à Ultime), 11 Légendes consultables en lecture seule, plus haut échelon battu marqué ✓.
- Options : seul le groupe « Général » est ouvert à l'arrivée.

Contenu
- GAMOSIC compte 11 joueurs ; OG Loska est remplaçant.
- La récompense de 800 gils n'est versée que si l'échelon joué est au moins celui de ta division ; en dessous, match libre.

Correctifs
- Le Marché et l'équilibrage des Uniques sont remesurés (cliquet du potentiel, salaires).

v0.23 : Départ plus bas, thème Sombre seul

Mécanique :
- Le monde démarre un peu plus bas : niveau de base 53 au lieu de 55 (D3 53, D2 57, D1 61, Élite 65).
- Potentiels tirés plus bas à la création des joueurs ; la valeur des joueurs et le niveau du Marché sont ajustés en conséquence.
- Public de départ ajusté au nouveau niveau.
- Défis : l'équipe prêtée suit mieux l'adversaire.
- Plafond de revenu par rang relevé à 3 600 pour le critère de sponsor.

Interface :
- Un seul thème : le Sombre. Le sélecteur de thème disparaît de l'écran titre et des Options.
- Options regroupées en menus déroulants : Général, Affichage, Son, Sauvegarde et journal, Partie.
- Affichage : interrupteurs « Fond animé » et « Effets glass » (remplacent l'ancien mode Simplifiée ; une ancienne sauvegarde reste compatible).

Correctifs :
- Le thème est posé avant le premier affichage, sans flash au chargement.

v0.22 - Onglet Potentiel
- Interface : nouvel onglet « Potentiel » dans la fiche joueur : grade et valeur du potentiel, marge restante, plafond par caractéristique, profil de progression (âge où il ralentit, repères 30 et 35 ans), courbe de niveau par saison, caractéristiques clés du poste repérées par une étoile.
- Interface : le thème est appliqué dès le chargement de la page (moins de flash) ; lettre X des badges de potentiel plus lisible.

v0.21 - Profils de progression
- Mécanique : chaque joueur a un profil de progression (rapide, régulier, lent ou tardif) qui module son XP et fixe l'âge où il ralentit (26, 29, 32 ou 35 ans). Après cet âge, il ralentit au lieu de s'arrêter net. Le profil est fixé par le joueur : aucune sauvegarde à migrer.
- Interface : badges de potentiel avec liseré (fin de E à A, épais pour S, S+ et X) ; lettre X à deux couches.
- Interface : thème sombre par défaut (le thème clair reste disponible).

v0.20 - Échelle de potentiel E à X
- Mécanique : nouvelle échelle de potentiel de E à S (jusqu'à 95), avec S+ réservé aux futures Légendes et X à l'éditeur. Le maximum ordinaire passe à 95 de potentiel et 96 de caractéristique.
- Mécanique : l'auto-répartition des points d'entraînement suit les caractéristiques clés du poste ; la répartition manuelle reste possible au même total.
- Interface : badges de potentiel colorés par grade et légende dans les Règles du jeu.

v0.19 - Mise à niveau
- Mécanique : progression de l'XP recalibrée (vers 2,5 à 3 niveaux gagnés par saison) ; les milieux n'ont plus qu'une seule ligne secondaire ; bonus des Guado réduits ; plus d'avantage du domicile en Défi.
- Interface : tutoriels en fenêtre, désactivables ; Règles du jeu avec un exemple fixe ; historique des clubs traversés par chaque joueur ; traduction FR/EN complétée.
- Correctifs : nettoyage du moteur de match et de plusieurs écarts relevés au rééquilibrage.

v0.18 - Rééquilibrage total
- Mécanique : les consignes en direct sont de nouveau actives et rééquilibrées ; le terrain rond utilise des distances en mètres pour les passes et les tirs ; avantage du domicile ; gardiens et maîtrise des formations recalibrés.
- Mécanique : niveau de difficulté de l'IA.
- Contenu : tirs des Uniques attaquants ramenés à 70.
- Correctifs : fenêtre de mercato de mi-saison qui pouvait se rouvrir ; journal bilingue ; plusieurs ajustements d'interface.

v0.17 - Recrutement, IA et enjeux
- Mécanique : le propriétaire fixe des objectifs ; un mauvais bilan mène au renvoi (après un sursis d'une saison) ; réputation du club.
- Mécanique : les clubs de l'IA recrutent et s'entraînent avec des profils de style ; tu peux faire des offres aux autres clubs ; mercato de mi-saison de 9 joueurs, ouvert après le tournoi de mi-saison.
- Interface : écrans des objectifs, des offres et du bilan de fin de partie.

v0.16 - Défis à thème
- Contenu : 16 défis (4 par niveau) à la place des 4 duels génériques : équipes 100 % d'une race (Humains, Hypellos, Ronso, Al Bhed, Guado), 100 % masculines, 100 % féminines, et GAMOSIC, l'équipe des Uniques ; équipes prêtées et contraintes spéciales.
- Mécanique : récompenses de 300 à 1 200 gils selon le niveau, avec un plafond par saison.

v0.15 - Divisions
- Mécanique : pyramide à quatre divisions (D3, D2, D1 à 16 clubs, puis l'Élite à 8) ; départ en D3 ; montées et descentes ; 30 journées en D1 à D3, 14 en Élite.
- Mécanique : recettes, frais et prix des tournois suivent la division ; les salaires se reconvertissent quand on change de division.
- Contenu : un monde de 56 clubs.

v0.14 - Défis et Tournois
- Mécanique : Défi à la demande (12 défis en 4 niveaux, récompense plafonnée par saison).
- Mécanique : tournois à 8 clubs en élimination directe, à la mi-saison et en fin de saison, avec inscription payante, invités et prix.
- Contenu : distinctions esthétiques (coupes or, argent et bronze, étoiles de blason, titres d'entraîneur, médailles de défi) au palmarès et sur le profil.

v0.13 - Contrats et économie
- Mécanique : contrats de joueurs (durée, renouvellement, fin de contrat, salaires fixes) et joueurs libres.
- Mécanique : prime de victoire variable ; sponsors avec objectifs ; mercato élargi hors saison (18 joueurs).
- Interface : page Contrats, écran de fin de saison, contrastes revus partout, Journal replié sur petit écran.

v0.12 - Habillage
- Interface : le fond à bulles devient l'interface principale (l'ancienne devient « Simplifiée ») ; police Square 721 ; icônes SVG.
- Correctifs : un import de sauvegarde complète désormais le blason ; fichier allégé de 114 Ko.

v0.11 - Joueurs uniques et identité
- Contenu : 22 joueurs Uniques à noms et statistiques fixes, rares sur le Marché ; badge « Unique ».
- Interface : portraits en pixel art (24 × 32) et blason en pixel art avec éditeur 12 × 12 ; tactique rapide ; cloche à gauche ; seuils de HP unifiés.

v0.10 - Ambiance
- Interface : mode d'affichage « Alt » (fond aquatique à bulles, verre flou, variantes jour et nuit).
- Contenu : cinq effets sonores synthétisés et une musique chiptune originale (désactivée par défaut).

v0.9 - Lisibilité du match
- Interface : contour des jetons selon les HP (plein, tirets, pointillé) ; une forme de jeton par club ; bilan de fin de match replié par défaut (jusqu'à 3 fois moins haut sur mobile) ; noms complets sur le radar.
- Correctifs : contrastes ; fichier allégé de 53 Ko.

v0.8 - Règles du terrain
- Mécanique : huit joueurs par équipe (gardien + 7), effectif de départ de 12, banc de 4, 3 remplacements ; six formations (3-2-2, 2-3-2, 2-2-3, 3-3-1, 3-1-3, 1-3-3).
- Mécanique : arrêt du match à 7 buts d'écart ; bonus pour l'attaquant seul.
- Interface : buts triangulaires sur le terrain rond.

v0.7 - Modes
- Mécanique : sélecteur Saison / Entraînement ; match d'entraînement sans effet sur la saison.
- Interface : Tableau de bord en deux colonnes sur grand écran ; comparatif d'équipe fusionné ; bilan de l'entraîneur ; cloche de notifications ; journal de test exportable.

v0.6.10 - Match et navigation
- Mécanique : trois plans d'équipe sauvegardables ; Marché de 12 joueurs renouvelé toutes les 3 journées ; remplacements libres avant le coup d'envoi.
- Interface : match en trois colonnes, Sphère en plein écran, six de départ modifiable depuis l'avant-match.

v0.6.9 - Tactique et listes
- Interface : Tactique sur une seule page avec forces par zone ; filtres Poste, Race, Sexe, niveau et âge ; fiche joueur en feuille du bas sur mobile ; compte à rebours du Marché.
- Mécanique : formations verrouillées par niveau ; jauge de maîtrise ; confirmation avant tout changement de spécialité d'entraîneur.

v0.6.8 - Identité
- Contenu : sexe des joueurs (textes accordés en FR et EN), 200 prénoms féminins, 200 masculins et 300 noms de famille ; Hypellos plus rares et plus lents à progresser.
- Interface : cadre de portrait sur la fiche joueur.

v0.6.7 - Solidité
- Interface : Entraînement en lignes, tous les textes à 12 px ou plus, polices embarquées (plus aucun appel externe).

v0.6.6 - Accueil actionnable
- Interface : « À faire avant le match », fiche de l'adversaire, Journal complet avec filtres.

v0.6.5 - Publication
- Mise en ligne du jeu (GitHub Pages) et licence non commerciale.

v0.6.4 - Consignes en direct
- Mécanique : consignes en pause par blocs de 6 phases (effets désactivés à ce stade).

v0.6.3 - Première impression
- Interface : écran titre avec actualités, parcours de nouvelle partie (entraîneur, club, personnalisation), message de bienvenue, Fiche du club, Tableau de bord.
- Mécanique : sauvegarde par export, import et copier-coller.

v0.6.2 - Navigation
- Interface : cinq sections et barre de navigation mobile.

v0.6.1 - Sphère ronde
- Interface : terrain rond (la Sphère), receveur de la passe nommé dans le journal, bilan d'après-match retouché.

v0.6 - L'expérience en match
- Mécanique : trois consignes de mi-temps ; infos de match (possession, fatigue).
- Interface : détail des duels, bilan d'XP, bandeaux de but.

v0.5 - Rôles et composition
- Mécanique : 9 postes de champ plus le gardien, spécialité de voie, adéquation unique, traits passifs.

v0.4.x - Fondations
- Interface : plus de défilement horizontal, carte joueur à 3 onglets, Règles du jeu.
- Mécanique : postes secondaires, formations débloquées par le niveau, stade, spécialités d'entraîneur, blason à trois couches.
- Correctifs : code découpé en modules pour tester.

v0.3 - Races et profil
- Contenu : 5 races ; côtés préférés ; entraînement individuel ; profil d'entraîneur ; page Club ; langue FR/EN et thèmes.

v0.2 - Refonte
- Mécanique : 8 caractéristiques inspirées de FFX avec HP, moteur par duels, XP et niveaux, finances détaillées.

v0.1 - Première ébauche
- Saison à 8 clubs, matchs en direct, marché et finances simples.

-----

# Blitz Manager - EN

Browser-based Blitzball management game: build your team, set your tactics, and lead your club season after season.

Play: https://ravagedking.github.io/blitz-manager/

- Single HTML file: No installation required, available in FR (default) and EN.
- Local saves: Games are saved directly in your browser, specific to this URL only.
- Testing version: Saves are not compatible between different versions; updating will start a fresh game. Save export/import by file and by copy-paste has been available since v0.6.3.

A non-commercial, non-profit tribute to the Blitzball mini-game from Final Fantasy X.
Fan project, not affiliated with Square Enix; all original names and terms belong to their respective owners. Trademarks mentioned belong to their respective owners.

ACTUAL VERSION : V0.31
