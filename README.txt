FAIRWAY 386 — USER GUIDE
Course Library Edition | Version 1.8.6
============================================

CONTENTS
  1. Welcome and installation
  2. Your first round (quick start)
  3. Swing, aiming, clubs and camera controls
  4. Hazards and scoring
  5. Clubhouse: players, handicaps and round history
  6. Course library: selecting, importing and exporting
  7. Course designer: basic and visual editing
  8. Leagues and scorecards
  9. Solo tournaments
 10. Backups, moving computers and file formats
 11. Troubleshooting and common questions
 12. Important limitations

1. WELCOME AND INSTALLATION
----------------------------
Fairway 386 is a self-contained, offline, nine-hole golf simulator that runs
in a desktop web browser. No installer or online account is needed.

Inside the ZIP:
  Fairway386_v1.8.5/
    index.html                     The complete game
    README.txt                     This guide
    CHANGELOG.txt                  Release history and known notes
    Courses/
      Fairway386_Course_Manuka.json
      Fairway386_Course_Pine_Ridge.json

To install: extract the entire ZIP, then open index.html in a modern browser
(such as Firefox, Chrome or Edge). Do not run it directly from inside the ZIP.
Keep the Courses folder with the game for easy sharing and backups.

The supplied courses may already be present in the game's built-in library.
The files in Courses are also portable backups for manual importing; simply
placing JSON files in that folder does NOT automatically import them.

2. YOUR FIRST ROUND — QUICK START
---------------------------------
  1. Open index.html.
  2. Scroll to the Fairway 386 Clubhouse below the golf view.
  3. Open Players & handicaps. Enter your name and click Add player.
     Confirm your name appears in the Active player dropdown.
  4. Open Course designer. Choose Manuka or Pine Ridge in Course.
  5. Click Play selected course from Hole 1.
  6. Return to the top of the page. Select a club, adjust aim and power,
     and take each shot using the three-click swing (see section 3).
  7. After holing out, use the result screen's Next hole action.
  8. Finish all nine holes. The course-complete result shows the total.
  9. In Players & handicaps, find Player round history and click
     View scorecard to inspect the saved round.
 10. In Course designer, click Export player profile to back up scores.

You do NOT need to create a league to record casual rounds. A round is
recorded against whichever player was active when you played it.

3. SWING, AIMING, CLUBS AND CAMERAS
-----------------------------------
CLUBS: Choose a club under Shot setup. The menu shows approximate club
ranges. Driver and woods travel farther; wedges and the putter suit short
shots. Conditions, power, accuracy, lie and terrain affect actual distance.

AIM: Use Aim left / Aim right or the Shot direction slider. The yellow
guide shows your chosen shot direction; it is not automatic target aiming.
Doglegs may require aiming away from the flag to find the fairway.

POWER: Use Planned power to choose a percentage. Putting permits fine 1%
increments. The game displays an estimate; this is not a guarantee.

THREE-CLICK SWING: Press SWING (or Space) three times:
  First click: start the moving meter.
  Second click: set shot power.
  Third click: time the accuracy mark as the meter returns.
An early or late third click can hook or slice the ball. Watch the
commentary and shot readouts to understand the outcome.

CAMERAS: The three buttons below the view are Fairway camera, Overhead map,
and Putting camera. Switch between them to examine the hole. The putting
camera is designed for green-side play and can switch back when the ball
rolls off the green. Camera direction does not change your manually set aim.

HUD: The display shows hole, par, yards, shot number, distance to cup and
current lie. The right panel shows strokes, score, wind and last shot.

RESTART HOLE: Restarts the current hole; use it carefully while testing.

4. HAZARDS AND SCORING
----------------------
BUNKER: No automatic penalty stroke, but carry is reduced to about 62%
and the ball rolls much less.
WATER: One penalty stroke; play resumes from the previous lie (simplified).
TREES: Canopies knock shots down and trunks can stop a rolling ball. Trees
are obstacles, not automatic penalty areas.
SLOPES: Hills, hollows, elevation and green breaks affect ball movement.

Each hole's par is the target number of strokes. A score below par is
better; a score above par is worse. The completed nine-hole round is saved
with a total, course name, date and per-hole strokes.

5. CLUBHOUSE — PLAYERS, HANDICAPS AND ROUND HISTORY
---------------------------------------------------
Open Players & handicaps:
  - Enter a name and click Add player to create a golfer.
  - Use Active player to switch golfers. The history should change
    immediately; a page refresh should not be necessary.
  - Player round history lists completed casual, league and tournament
    rounds for the selected player, including date, course, total strokes,
    par and result relative to par.
  - Click View scorecard for nine-hole stroke and par details.

The displayed handicap is PROVISIONAL, not an official World Handicap
System (WHS) handicap. It is based on the average score over par for
completed nine-hole rounds, scaled to 18 holes and capped at 0–54.

Older imported rounds might not contain individual hole pars. When the
matching course is available the game can use it; otherwise individual
hole pars may be unavailable while the saved total par remains visible.
Newer rounds store hole-by-hole par values in their history.

Important: the player-profile export is a backup of ALL locally stored
players, leagues and tournaments. Its filename uses the currently active
player's name for convenience; it is NOT a single-player-only export.

6. COURSE LIBRARY — SELECT, IMPORT AND EXPORT
----------------------------------------------
Open Course designer. Use the Course dropdown to select a course.
Click Play selected course from Hole 1 to begin a fresh round.

Export selected course: downloads a reusable course-master JSON, e.g.
  Fairway386_Course_Manuka.json
Import course: choose a course-master JSON from your computer.
If the exact layout is already installed, the game may report:
  'This exact course is already installed.'
That is expected and prevents duplicates. A different layout with the
same course ID may be offered as a new imported copy.

Course JSON files contain the layout (holes, hazards, elevations, etc.),
not the scores of people who play them. Playing does NOT rewrite the
JSON files stored in the Courses folder. Editing a course changes the
local browser's copy until you explicitly export it again.

When sharing results with friends, everyone should use the same course
layout. Export and share the course JSON to keep designs consistent.

7. COURSE DESIGNER — BASIC AND VISUAL EDITING
---------------------------------------------
WARNING: Back up a course using Export selected course BEFORE editing.

BASIC EDITOR:
  - New course creates a fresh nine-hole course.
  - Course name changes its display name.
  - The nine hole panels let you edit hole length, par, fairway width,
    bend/dogleg settings and terrain/elevation values.
  - Save course stores your edits in the local course library.
  - Delete course removes the selected local course; saved player
    score history is kept. You must keep at least one course.

VISUAL HOLE DESIGNER:
  - Preview hole chooses which hole you are editing.
  - Tool = Select / move: click an existing object, then drag it.
  - Add fairway waypoint / Remove fairway waypoint: shape the fairway.
  - Add sand bunker / Add water hazard: place hazards.
  - Plant tree / Plant tree grove (7): add obstacles.
  - Raise terrain (hill) / Lower terrain (hollow): sculpt slopes.
  - Erase objects: click an object to delete it.
  - Drag the green flag to reposition the green; drag the gold bend
    marker to reposition the dogleg turn. Drag blue waypoint handles.
  - Green size adjusts the green radius (12–38 yards).
  - Brush size and Terrain strength control placement/sculpting tools.
  - Object list helps select overlapping objects. Selected-object
    controls let you adjust size and delete the object.
  - Undo / Redo buttons, Ctrl+Z / Ctrl+Y, and Delete or Backspace
    help correct editing mistakes. Esc or right-click exits placement.
  - Clear objects on hole removes placed objects from the current hole.
  - Save visual design saves the current visual edits.

These edits affect actual gameplay. After testing a design, export a new
course JSON if you want a portable master. Do not overwrite your only
copy of a treasured course without making a backup first.

8. LEAGUES AND SCORECARDS
-------------------------
Open League & scorecard:
  1. Enter a New league name and click Create league.
  2. Choose the league in the League dropdown.
  3. Select a player in Players & handicaps, then return here and click
     Enter active player to add that golfer to the selected league.
  4. Play completed rounds to populate the league standings.

The Current round table describes the active round in progress; it is NOT
a historical scorecard. For older rounds, use Player round history.
Next hole and Finish round are relevant when the current round permits
them. League standings use completed rounds only. Net scoring uses the
provisional game handicap, allocated proportionally across played holes.
This is an offline/local feature, not network multiplayer.

A round played casually before a league was created stays a casual round;
it does not automatically become a league round.

9. SOLO TOURNAMENTS
-------------------
Open Tournaments:
  1. Enter a Tournament name.
  2. Choose a course under Add course to rotation and click Add course.
     Repeat for the desired rotation (up to 12 rounds).
  3. Click Create tournament.
  4. Select it under Selected tournament, then click Start / Resume next
     round. Play the specified courses in order.
  5. Finish each round to save results and advance the competition.
  6. Use Past tournaments & improvement to review progress.
  7. Replay tournament creates another attempt while retaining earlier
     results.

Tournament results are compared relative to par across courses. This is
a solo stroke-play challenge, not an official handicap-rated event.
Completed tournament rounds also appear in player round history.
Avoid switching courses or players during an active tournament round.

10. BACKUPS, TRANSFERS AND JSON FILE TYPES
------------------------------------------
The game stores working data in browser local storage. It uses separate
storage for the local course library and for player profiles/history.
This does NOT automatically save changes back into files in Courses/.

RECOMMENDED BACKUP ROUTINE:
  A. Course designer -> Export selected course for every course you made
     or changed. Keep these JSON files in a safe folder.
  B. Course designer -> Export player profile after playing rounds.
     Example filename: Fairway386_Player_Profile_Alan.json
  C. Keep both kinds of backups outside the game folder too.

IMPORT PROFILE — IMPORTANT: Import profile REPLACES the current local
player history, players, leagues and tournaments with the imported data.
It does NOT merge the two databases. Export your current profile first!
Course designs are not replaced by a profile import.

EXPORT LEGACY CLUBHOUSE / IMPORT JSON: These are compatibility tools for
older combined clubhouse backups, which can include courses and scores
together. Importing legacy JSON can replace local clubhouse information;
back up first. For normal use, prefer separate course and profile JSONs.

Moving to a new browser, folder or computer can result in different
browser storage. The safest method is to import the saved course files
and then import the player profile. A browser refresh is not a backup.
Clearing browser/site data or using private browsing can lose local data.

11. TROUBLESHOOTING AND COMMON QUESTIONS
----------------------------------------
Q: My new JSON file is in Courses, but the game doesn't show it.
A: Use Course designer -> Import course. Offline browsers do not scan
   that folder automatically.

Q: 'This exact course is already installed.' Is something wrong?
A: No. The course is already available; no duplicate was created.

Q: I finished a round, but League & scorecard looks empty.
A: Your round may be casual, or you may not have created/entered a league.
   Check Players & handicaps -> Player round history.

Q: My round history is showing another player's scores.
A: Confirm the Active player dropdown and use the latest game version.
   Player history should update as soon as you change the player.

Q: The scorecard shows dashes for individual hole pars.
A: Older profiles may lack per-hole par data and the matching course may
   not be installed. Import the corresponding course master, then reopen
   the scorecard. Newer rounds save the hole pars with the round.

Q: The game looks like an older version after I replaced index.html.
A: Close and reopen the new file, verify its version at the top, and try
   Ctrl+F5 for a hard refresh. Confirm you opened the intended folder.

Q: I switched browsers and my scores disappeared.
A: Each browser maintains its own local storage. Import your previously
   exported player profile; import courses separately as needed.

Q: Can I share my scores with a friend?
A: Yes, by exchanging JSON backups. However, importing a player profile
   replaces the receiving browser's existing profile data. It does NOT
   combine your scores with theirs automatically. Back up before import.

Q: Why didn't playing change my Manuka.json file?
A: That's intentional. Course masters are clean layouts; results live in
   the browser profile data and exported player-profile JSON.

Q: Can I use this on the internet or play live multiplayer?
A: The game runs offline. League and tournament records are local, not
   live online multiplayer.

12. IMPORTANT LIMITATIONS
-------------------------
  - Nine-hole courses and local browser play.
  - No automatic scanning of the Courses folder.
  - No automatic cloud sync, online account or live multiplayer.
  - No official World Handicap System verification.
  - Profile import replaces rather than merges local profile records.
  - Course and player JSON exports should be backed up regularly.

Enjoy your round, and watch that sixth hole on Manuka!

Fairway 386 | Course Library Edition v1.8.5

NAS / LOCAL NETWORK HOSTING
---------------------------
Fairway 386 works from an ordinary HTTP NAS address (e.g. http://192.168.1.97/Fairway/index.html). Version 1.8.6 fixes a startup error caused by crypto.randomUUID being unavailable over HTTP. Course and player-profile imports remain browser-specific: export and back up profiles when moving between computers, browsers or site addresses. If an old page remains cached, press Ctrl+F5.
