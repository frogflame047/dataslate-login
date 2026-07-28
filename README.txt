ANURA CROIX - DATASLATE CHARACTER APP
=====================================

DROP THESE FILES IN BESIDE index.html (names must match exactly):

  datapad_bg.png   -> your datapad background image (full-page backplate)
  portrait_1.png   -> main character pict (renders up to 400px wide)
  portrait_2.png   -> secondary pict (renders up to 300px wide)

If any are missing the page still works - the background falls back to a
gothic gradient, and each missing portrait shows a dashed "PICT-CAPTURE
ABSENT" box telling you which filename it wants.

MP3s already included and wired into TRACK_LIST (index.html, line ~1090).


ACCESS
------
Any username + password (3+ chars) creates an account on first login.
Clicking "-Vault Node 1-" in the terminal header opens the override prompt:

  omnissiah  or  weiss      -> skip the cypher lock, open the record
  warrant    or  parasite   -> same, plus unlocks the EXPUNGE RECORDS panel

(old passphrases kept working so you don't have to relearn them)


FIREBASE
--------
Same project as the BOS page. Two changes:
  - scoreboard node is now 'dataslateUsers' (old 'terminalUsers' untouched,
    so the two pages keep separate leaderboards)
  - lyric node is still 'lyricEngine/jane' - any live timing tweaks you
    already made carry straight over


EDITING
-------
Stat blocks (WS/BS/S/T/Ag/Int/Per/WP/Fel) are '##' placeholders - search
for 'special-stat' and fill them in once you roll.

Steam ID slot is 'PILGRIM SIGIL' in the scribe-slip block near the top.

Theme colours are the five buttons top-right; the whole page is driven by
--terminal-color, so setTheme('#hex') retints everything at once.
