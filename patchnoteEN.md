# Patch notes - Blitz Manager

Versions are numbered v0.x: the whole current phase is the Alpha. When a version fully satisfies its creator, it will become the Beta (testing, small changes), and then v1.0 will follow.

Categories, always in this order: Gameplay, Balance, Interface, Content, Technical, Fixes.

Version française : [patchnoteFR.md](patchnoteFR.md)

---

## v0.42 - Living world, part two

### Gameplay
- Some events ask you to decide: a "To decide" card appears on the Home page, with Yes or No; without an answer, it is No at the next match.
- Opposing clubs bid for your best players; if you refuse, the player may come back to it a few matchdays later.
- Opposing squads range from 12 to 14 players depending on their fans.
- Some careers last one more season or end early after a serious injury; great careers of opposing clubs get their farewell line in the Journal.

### Interface
- "To decide" card on the Home page.
- History tab on an opposing club's page: titles, coach, records.

### Content
- "Living world" Rules completed and "Living world" Tutorial expanded.

### Technical
- Slightly heavier file: 806 KB instead of 796 KB.

---

## v0.41 - New font, lighter file

### Interface
- New text font, Chakra Petch (open font), replacing Square 721; some pages change height slightly, by a few pixels, mostly on phones.
- Numbers and values in the monospaced font (header, player ratings, match report times) look slightly bolder.

### Technical
- The game now embeds only the characters it displays: the file is about 48 KB lighter (796 KB instead of 845 KB).

---

## v0.40 - Living world

### Gameplay
- Events happen during the season, with at most one major effect per season.
- Rivalries grow with the clubs you face; against a rival, the match becomes a derby (higher ticketing and more fans).
- Opposing clubs have their own coach, who can be fired after bad seasons, and their own popularity.

### Interface
- Derby label on the Home screen and before the match; alert for a major event.
- New World category in the Log; coach, fans and Rival label on an opposing club's sheet; Rivalries panel in Club.

### Content
- "Living world" section in the Rules and "Living world" entry in the Tutorial.

### Fixes
- Log lines display in the chosen language, even if they were written in the other one.
- "Youth −2" is written with a real minus sign.

---

## v0.39 - Tutorial and rewritten Rules

### Interface
- The Rules open on a new Tutorial tab, which groups all tutorials into 5 categories.
- A tutorial's "Game rules" button opens its category directly.
- After the scout is dismissed, the kept specialty is marked and the help offers to rehire them.

### Content
- Game rules reviewed and corrected, in French and English.
- Four new tutorials: coach specialty, second specialty, sudden death, 7-goal gap.

### Fixes
- After renaming the club, the Honours page and the tournament win in the Log show the new name.
- Sponsor objectives mention sudden death instead of overtime.

---

## v0.38 - Scout and tailored training

### Gameplay
- A scout can be hired at the academy, with a chosen specialty: Discovery (one more prospect per season), Assessment (exact potential of prospects) or Reveal (progression profile visible before joining the squad).
- The scout costs upkeep every matchday while hired; their specialty can be changed at the end of the season.
- New "Custom" training path: you choose the 2 stats the prospect works on.

### Interface
- Club › Academy shows the scout, their request for next season, their cost, and the choice of the 2 stats.

### Content
- Game rules updated (Stadium and finances), in French and English.

---

## v0.37 - Academy and squad

### Gameplay
- No more 14-player limit: keep as many players as you want (technical cap at 40). Over-recruiting is still possible, but wages can ruin the club.
- Academy (Club › Academy): unlock it, then upgrade it over 3 levels. 15-year-old prospects arrive every season and join the squad at 18 if you had them sign a pre-contract.
- Choose each prospect's path (Position, Physical or Technical) and pay for intensive training so they progress faster. Their exact potential and profile stay hidden until they turn 18.
- Players decline and retire earlier or later depending on their progression profile (retirement between 35 and 40).
- With an academy, a retiring player is no longer replaced for free.

### Interface
- Indicator of the share of revenue spent on wages in Finances and Squad (orange at 85%, red at 100%), and an estimate after signing in every purchase window.
- "Show more" in the Squad beyond 14 players; the Potential tab shows the player's decline and retirement ages.

### Content
- New tutorial for the academy; game rules updated.

### Fixes
- The shot trajectory no longer spills over the next action at ×4 speed.
- The help for the "Match animations" option says it also turns off the bubbles and the Sphere in Tactics.

---

## v0.36 - A livelier match

### Gameplay
- Key pauses: the live match slows down after a goal, a save or a missed shot, and pauses at the end of a close match and before sudden death (2 times at most), so you can give an instruction or make a substitution.

### Interface
- Crowd in the stands: attendance follows your club's popularity, visitors have their own section, the crowd reacts to goals; the crowd is shown during home matches.
- Clock that runs continuously, in large digits.
- Smoother animations: players arrive before the next action even at ×2 and ×4 speed, ball carrier highlighted, shot trajectory, flashing goal.
- Options › Display: "Match animations" and "Key pauses" (can be turned on and off).

### Content
- 10 new tutorials when a mechanic first appears (mid-season transfer window, end of contracts, tournament registration, injury, talent points, negative budget, half-time, exhausted player, training match, challenges); during a match, they only show at the break.

### Fixes
- Club › Finances no longer overflows on medium screens.
- The Home Log shows the full text of entries on mobile.

---

## v0.35 - Match presentation (I)

### Interface
- Full-screen match on mobile, in portrait (⤢ button) as well as landscape, with a collapsible "Your team" block (HP and substitutions).
- The Home screen shows the log of the last 3 matchdays, in a scrolling area.
- Tournaments are displayed as a bracket, readable on phones too.
- A player's sheet has an "In position" block: saves and clean sheets for goalkeepers, tackles and interceptions for defenders, passes and interceptions for midfielders, goals and assists for forwards, per season and over the career.

---

## v0.34 - Legends by code

### Gameplay
- 11 new "…LEGEND" codes: each gives your club an S+ class Legend, once per code and per game.
- At most 3 Legends received per game, only 1 active at a time. The others wait in reserve (3 at most) and do not age.
- Their power is capped according to your division (higher in Elite, lower in Semi-Pro).
- They earn the division's maximum wage, cannot be sold or released, play challenges and retire at 35.

### Interface
- Options › Codes: receiving Legends, "Legends received" counter, corrected hint.
- Squad: "Legends in reserve" block with an Activate button.
- Player sheet: "Put in reserve" button and a note about the cap. Legends section added to the game rules.

### Fixes
- A club from an old save with a duplicate name or code can be renamed again.

---

## v0.33 - Create your club

### Gameplay
- New game in 5 steps: Path, Coach, Mode, Club, Customization.
- New Create mode: you invent your club, which replaces the weakest one in the league. Three squad orientations to choose from: Balanced, Young, Experienced; unlimited squad rerolls; a club's code and name must be unique.
- The coach's second specialty can be removed for free; choosing another one costs 5,000 gil.

### Interface
- Creation page with a preview of strength and average age.
- Going back without losing anything during creation.
- The figures of the second specialty (Fitness coach, Star coach) are displayed.

### Technical
- Import and export of a club file (.json).

### Fixes
- None. One minor known issue: on an old save that already contains a duplicate name or code, changing the name or code is refused without a message. Fix planned for v0.34.

---

## v0.32 - Captain and second specialty

### Gameplay
- Captain: pick a captain among your outfield players. They wear the "C" armband and give a slight bonus to their line, about +1% effect. If you don't choose, the game picks one automatically, marked "(auto)".
- Second coach specialty: from level 6, you can choose a second one for 5,000 gil. It works at half the strength of the first.

### Interface
- "C" armband visible on the captain, and "(auto)" shown when the choice is automatic.
- Second specialty selection in the coach profile.

### Content
- Title screen news updated for v0.32.

---

## v0.31 - A growing stadium

### Gameplay
- The stadium grows in tiers (T1 to T4): each tier must be paid for and unlocks facilities and higher levels depending on your division (Semi-Pro 3: T1, Semi-Pro 2: T2, Semi-Pro 1: T3, division 3 and above: T4).
- Tier price (depending on the division): T2 from 7,000 to 9,000, T3 18,000, T4 40,000.
- Relegation doesn't make you lose anything: facilities and tier stay yours.
- The tier brings no income by itself: revenue still comes from facilities.

### Interface
- Club › Finances: Tier line with an "Expand" button, price shown and the reason when it's not possible (division, funds).
- The stands around the Sphere grow with the tier.
- Club › Customization: 3 new waters (Ruby, Olive, Slate), 3 new balls (Lime, Pink, Silver), 4 stand styles and seat colour.

### Content
- Game rules: new section on stadium tiers.

---

## v0.30 - Club identity

### Gameplay
- Everything is cosmetic: no effect on matches or the economy.

### Interface
- Club motto (32 characters), shown on the Club sheet and on the Home screen.
- 24×24 crest editor with zoom; old crests stay as they are and switch to 24×24 on request.
- Palette expanded to 60 colours.
- New "Kit worn" selector (Club › Customization): Auto, Home, Away or Unique kit; the opponent adapts to your choice.
- The Sphere token takes the shape of the crest, and the visitor wears an inner ring to tell them apart.

### Content
- Customizable Home and Away kits.
- Four Unique kits unlocked by code, two of them with a visual effect (stopped if animations are reduced or turned off).
- ULTIMATEST also unlocks these four kits.

### Technical
- Old saves load without loss.

### Fixes
- A long motto no longer makes the Club sheet overflow on small screens.

---

## v0.29 - Records, anti-titles and end-of-season ceremony

### Gameplay
- New career counters per player: passing distance, long passes, blocks.
- Additional stat titles and six anti-titles (the worst of the season), plus a "Worst player" and the player of the week.
- Club and game records: a broken record is announced in the Log.
- Two new game titles (12 in total), unlocked by playing.

### Interface
- 3-step end-of-season ceremony, which you can skip at any time. It can be turned off in Options › Display.
- Honours: the history is collapsed by season (the last two are expanded).
- Player sheet: career, records and awards.
- Club › Coach: Badges collapse on small screens (under 700 px), no more overly long page on mobile.
- Game rules and title news updated.

### Content
- The Credits and the latest patch notes stay on the title screen.

### Fixes
- The Dynasty condition text now specifies that it means division championships.
- Club › Coach no longer exceeds the intended height at 390 px.

---

## v0.28 - Game titles, division frames and animated backgrounds

### Gameplay
- Ten game Titles to earn by playing (championships, cups, challenges, streaks…), with tiers.
- Obvious Titles are visible, greyed out, with their condition and progress. Secret ones only appear once earned.
- Seven portrait frames depending on the division won.
- Career counters kept from one season to the next.
- The "Auto" mode for title and frame is removed: nothing is shown until you choose it.

### Interface
- Club › Coach: Titles catalogue, title above the name (slow shine at the Diamond tier).
- Five animated backgrounds in Options › Display › Background.
- New "Misc" category in the Log. Unlocks are grouped into a single notification.
- Wording harmonized: "Championships won".

### Content
- Five background codes: THUNDERBG, FIREBG, AQUABG, LIGHTBG, DARKBG. ULTIMATEST now unlocks all code cosmetics.

### Fixes
- The two remaining "champion titles" labels are corrected.

---

## v0.27 - Coach profile and codes

### Interface
- The coach profile fits in a single block: portrait with frame, small title above the name, and a pencil to edit name, portrait, frame and title.
- The Awards list is shorter ("×n").
- The frame and title selectors stay hidden until a code has been entered.

### Content
- 12 codes in Options › Codes: CREATOR, a frame and a title for thunder, fire, water, light and darkness, as well as ULTIMATEST, which unlocks everything.
- Frames and titles are animated (static if animations are reduced in the system).

### Fixes
- The save import error message no longer mentions a version number.
- Wording is unified: "Awards" for what you earn, "Titles" for what you display.
- Two labels in this wording remain to be fixed in the next version.

---

## v0.26 - Awards and Honours

### Gameplay
- End-of-season awards for the whole division: best player, best in each position, best prospect (23 or under), top scorer, top assister, passes, tackles, interceptions, recoveries, saves and clean sheets, and the division's team of the season. Players must have played at least 60% of matches. These awards are purely honorary.
- "Best player" is judged relative to their position, so it doesn't always go to a forward.
- New stats tracked for all players, per season and over the career: saves, clean sheets, tackles, interceptions and passes.
- New titles: "Tournament double" (both tournaments in the same season, replaces "Double crowned") and "Treble" (division champion and winner of both tournaments in the same season).

### Balance
- Regular challenges recalibrated in Semi-Pro: they are better balanced across the three divisions.

### Interface
- New Club › Honours page: showcase, season awards, team of the season, club winners and honours.
- Division markers next to the crest: diamond-effect crown (Elite), stars (D1 to D3) and triangles (Semi-Pro), in bronze, silver and gold.
- You choose your displayed title and portrait frame in the Coach page.
- New Options › Codes page, with the animated Thunderstruck and Blazing portrait frames.
- Game rules completed.

### Content
- Test codes: CREATOR ("The Creator" title), THUNDERFRAME (thunderstruck frame) and FIREFRAME (blazing frame).

### Technical
- More reliable navigation tests; old test scripts archived.

---

## v0.25 - Semi-Pro

### Gameplay
- New Semi-Pro path: you start at the bottom of a 7-division pyramid (104 clubs) and climb up to the Elite.
- Professional licence: to reach the pro divisions, you need at least 20,000 gil in the bank, confidence of at least 60 and one facility at level 1. Once obtained, it is kept for the whole game.
- GAMOSIC is locked in Semi-Pro.

### Balance
- Revenue, staff, upkeep and facilities are indexed on the division; Semi-Pro starting budgets adjusted (37,500 / 29,000 / 18,000 gil).
- Unique players on the Market follow the division's level in Semi-Pro.
- Wage caps and starting reputation extended to all 7 levels.

### Interface
- New "Path" step (Semi-Pro / Pro) when creating a game.
- Professional licence card with its three conditions and progress messages.
- The title news and the "subject to the licence" message are corrected.

### Technical
- Old saves (versions 11 and 12) are no longer accepted: start a new game.
- The full verification tests are now part of the test suite.

### Fixes
- Home screen height at 390 px aligned with the new target.

---

## v0.24 - Legends and GAMOSIC in 5 tiers

### Gameplay
- The catalogue grows to 11 Unique players, including Daymon Sky; all have a potential of 93.
- Legends (potential 98) exist only in GAMOSIC: never in a squad, cannot be sold.
- The 800 gil reward is only paid if the tier played is at least your division's; below that, it's a free match.

### Balance
- Wage cap per division for Unique players (Elite 2,430, D1 900, D2 690, D3 530 per matchday).
- The Market and Unique player balance are re-measured (potential ratchet, wages).

### Interface
- GAMOSIC: tier menu (Division 3 to Ultimate), 11 Legends viewable read-only, highest tier beaten marked ✓.
- Options: only the "General" group is open on arrival.

### Content
- GAMOSIC has 11 players; OG Loska is a substitute.

### Technical
- Old saves are migrated automatically: removed Unique players become regular players.

---

## v0.23 - Lower start, Dark theme only

### Balance
- The world starts a bit lower: base level 53 instead of 55 (D3 53, D2 57, D1 61, Elite 65).
- Potentials rolled lower when players are created; player value and Market level adjusted accordingly.
- Starting crowd adjusted to the new level.
- Challenges: the loaned team better matches the opponent.
- Income cap per rank raised to 3,600 for the sponsor criterion.

### Interface
- A single theme: Dark. The theme selector is removed from the title screen and Options.
- Options grouped into drop-down menus: General, Display, Sound, Save and log, Game.
- Display: "Animated background" and "Glass effects" switches (they replace the old Simplified mode; an old save stays compatible).

### Fixes
- The theme is applied before the first render, with no flash on load.

---

## v0.22 - Potential tab

### Interface
- New "Potential" tab in the player sheet: potential grade and value, remaining margin, cap per attribute, progression profile (age when they slow down, 30 and 35 markers), level curve per season, key attributes for the position marked with a star.
- The theme is applied as soon as the page loads (less flash); letter X on potential badges more readable.

---

## v0.21 - Progression profiles

### Gameplay
- Each player has a progression profile (fast, steady, slow or late) that adjusts their XP and sets the age when they slow down (26, 29, 32 or 35). After that age, they slow down instead of stopping abruptly. The profile is set by the player: no save to migrate.

### Interface
- Potential badges with an outline (thin from E to A, thick for S, S+ and X); two-layer letter X.
- Dark theme by default (the light theme is still available).

---

## v0.20 - Potential scale E to X

### Gameplay
- New potential scale from E to S (up to 95), with S+ reserved for future Legends and X for the editor. The regular maximum becomes 95 potential and 96 per attribute.
- Auto-allocation of training points follows the position's key attributes; manual allocation is still possible with the same total.

### Interface
- Potential badges coloured by grade, with a legend in the game rules.

---

## v0.19 - Upgrade

### Balance
- XP progression recalibrated (towards 2.5 to 3 levels gained per season).
- Midfielders now have only one secondary line.
- Guado bonuses reduced.
- No more home advantage in Challenges.

### Interface
- Tutorials in a window, can be turned off.
- Game rules with a fixed example.
- History of the clubs each player has been through.
- FR/EN translation completed.

### Fixes
- Cleanup of the match engine and of several discrepancies found during rebalancing.

---

## v0.18 - Full rebalance

### Gameplay
- Live instructions are active again and rebalanced.
- The round pitch uses distances in metres for passes and shots.
- Home advantage.
- AI difficulty level.

### Balance
- Goalkeepers and formation mastery recalibrated.
- Shooting of Unique forwards brought down to 70.

### Fixes
- Mid-season transfer window that could reopen.
- Bilingual log.
- Several interface adjustments.

---

## v0.17 - Recruitment, AI and stakes

### Gameplay
- The owner sets objectives; a poor record leads to dismissal (after one season of grace); club reputation.
- AI clubs recruit and train with style profiles.
- You can make offers to other clubs.
- Mid-season transfer window of 9 players, open after the mid-season tournament.

### Interface
- Objectives, offers and end-of-game summary screens.

---

## v0.16 - Themed challenges

### Gameplay
- Rewards from 300 to 1,200 gil depending on the level, with a cap per season.

### Content
- 16 challenges (4 per level) instead of the 4 generic duels: teams made 100% of one race (Humans, Hypellos, Ronso, Al Bhed, Guado), 100% male, 100% female, and GAMOSIC, the team of Unique players; loaned teams and special constraints.

---

## v0.15 - Divisions

### Gameplay
- Four-division pyramid (D3, D2, D1 with 16 clubs each, then the Elite with 8); start in D3; promotions and relegations; 30 matchdays in D1 to D3, 14 in the Elite.
- Revenue, costs and tournament prizes follow the division; wages are converted when you change division.

### Content
- A world of 56 clubs.

---

## v0.14 - Challenges and Tournaments

### Gameplay
- On-demand challenge (12 challenges in 4 levels, reward capped per season).
- 8-club knockout tournaments, at mid-season and end of season, with paid registration, guests and prizes.

### Content
- Cosmetic awards (gold, silver and bronze cups, crest stars, coach titles, challenge medals) in the honours and on the profile.

---

## v0.13 - Contracts and economy

### Gameplay
- Player contracts (length, renewal, contract end, fixed wages) and free agents.
- Variable win bonus; sponsors with objectives; extended off-season transfer window (18 players).

### Interface
- Contracts page.
- End-of-season screen.
- Contrast reviewed everywhere.
- Log collapsed on small screens.

---

## v0.12 - New look

### Interface
- The bubble background becomes the main interface (the old one becomes "Simplified").
- Square 721 font.
- SVG icons.

### Technical
- File 114 KB lighter.

### Fixes
- Importing a save now completes the crest.

---

## v0.11 - Unique players and identity

### Interface
- Pixel art portraits (24 × 32) and pixel art crest with a 12 × 12 editor.
- Quick tactics.
- Bell on the left.
- Unified HP thresholds.

### Content
- 22 Unique players with fixed names and stats, rare on the Market; "Unique" badge.

---

## v0.10 - Atmosphere

### Interface
- "Alt" display mode (underwater bubble background, frosted glass, day and night variants).

### Content
- Five synthesized sound effects and an original chiptune track (off by default).

---

## v0.9 - Match readability

### Interface
- Token outline based on HP (solid, dashed, dotted).
- One token shape per club.
- End-of-match report collapsed by default (up to 3 times shorter on mobile).
- Full names on the radar.

### Technical
- File 53 KB lighter.

### Fixes
- Contrast.

---

## v0.8 - Pitch rules

### Gameplay
- Eight players per team (goalkeeper + 7), starting squad of 12, bench of 4, 3 substitutions.
- Six formations (3-2-2, 2-3-2, 2-2-3, 3-3-1, 3-1-3, 1-3-3).
- Match stopped at a 7-goal gap; bonus for a lone forward.

### Interface
- Triangular goals on the round pitch.

---

## v0.7 - Modes

### Gameplay
- Season / Training selector; training match with no effect on the season.

### Interface
- Two-column dashboard on large screens.
- Merged team comparison.
- Coach summary.
- Notification bell.

### Technical
- Exportable test log.

---

## v0.6.10 - Match and navigation

### Gameplay
- Three saveable team plans.
- Market of 12 players refreshed every 3 matchdays.
- Free substitutions before kick-off.

### Interface
- Three-column match, full-screen Sphere.
- Starting six editable from the pre-match screen.

---

## v0.6.9 - Tactics and lists

### Gameplay
- Formations locked by level; mastery gauge.
- Confirmation before any change of coach specialty.

### Interface
- Tactics on a single page with strength by zone.
- Position, Race, Sex, level and age filters.
- Player sheet as a bottom sheet on mobile.
- Market countdown.

---

## v0.6.8 - Identity

### Interface
- Portrait frame on the player sheet.

### Content
- Player sex (texts agreed in FR and EN).
- 200 female first names, 200 male first names and 300 surnames.
- Hypellos rarer and slower to progress.

---

## v0.6.7 - Robustness

### Interface
- Training in rows.
- All text at 12 px or more.

### Technical
- Embedded fonts (no more external calls).

---

## v0.6.6 - Actionable Home screen

### Interface
- "To do before the match", opponent sheet, full Log with filters.

---

## v0.6.5 - Release

### Technical
- The game goes online (GitHub Pages) with a non-commercial licence.

---

## v0.6.4 - Live instructions

### Gameplay
- Instructions during pauses in blocks of 6 phases (effects disabled at this stage).

---

## v0.6.3 - First impression

### Interface
- Title screen with news, new game flow (coach, club, customization), welcome message, Club sheet, Dashboard.

### Technical
- Save by export, import and copy-paste.

---

## v0.6.2 - Navigation

### Interface
- Five sections and a mobile navigation bar.

---

## v0.6.1 - Round Sphere

### Interface
- Round pitch (the Sphere), pass receiver named in the log, post-match report reworked.

---

## v0.6 - The match experience

### Gameplay
- Three half-time instructions; match info (possession, fatigue).

### Interface
- Duel details, XP summary, goal banners.

---

## v0.5 - Roles and line-up

### Gameplay
- 9 outfield positions plus the goalkeeper, lane specialty, single suitability rating, passive traits.

---

## v0.4 - Foundations

### Gameplay
- Secondary positions, formations unlocked by level, stadium, coach specialties, three-layer crest.

### Interface
- No more horizontal scrolling, 3-tab player card, game rules.

### Technical
- Code split into modules for testing.

---

## v0.3 - Races and profile

### Content
- 5 races; preferred sides; individual training; coach profile; Club page; FR/EN language and themes.

---

## v0.2 - Overhaul

### Gameplay
- 8 attributes inspired by FFX with HP, duel-based engine, XP and levels, detailed finances.

---

## v0.1 - First draft

### Gameplay
- 8-club season, live matches, simple market and finances.
