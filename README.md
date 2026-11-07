# Blitz Manager - FR

Jeu de gestion de Blitzball dans le navigateur : compose ton équipe, règle ta tactique, mène ton club saison après saison.

Jouer : https://ravagedking.github.io/blitz-manager/

- Un seul fichier HTML, aucune installation, FR (défaut) et EN.
- Les parties sont sauvegardées dans ton navigateur, pour cette adresse seulement.
- Version en test : d'une version à l'autre, les sauvegardes ne sont pas compatibles, on repart d'une partie neuve. Export / import de sauvegarde par fichier et par copier-coller disponibles depuis la v0.6.3.

Hommage non commercial et sans but lucratif au mini-jeu Blitzball de Final Fantasy X. 
Projet de fan, sans lien avec Square Enix ; les noms et termes d'origine appartiennent à leurs ayants droit. Les marques citées appartiennent à leurs propriétaires.

VERSION ACTUELLE : V0.23

NOTES DE VERSION :

Les versions sont numérotées v0.x : toute la phase actuelle est l'Alpha. Quand une version satisfera pleinement son créateur, elle deviendra la Bêta (tests, petits changements), puis viendra la v1.0.

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

ACTUAL VERSION : V0.23
