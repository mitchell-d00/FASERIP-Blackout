<p align="center"><img src="logo.svg" width="96" alt="FASERIP: Blackout logo"></p>

# FASERIP: Blackout

A solo superhero adventure that runs in the browser, built on the FASERIP
tabletop rules by Gurbintroll Games. Roll up a hero, pick two powers, and stop
whoever has switched off every light in Harbor City.

## Play

Open `index.html` in any browser. There is nothing to install or build.

To put it online, turn on GitHub Pages for this repository (Settings → Pages →
deploy from the `main` branch, root folder). The game will be served at
`https://<your-username>.github.io/<repo-name>/`.

Your progress is saved in the browser, so you can close the page and come back.

## What is in the game

- **Hero creation** by the book: seven abilities start at World Class, three
  random ones go up a rank and three go down. Health and karma are worked out
  from the ability values.
- **Six powers** to choose two from: Blast, Strike, Mental Blast, Resistance,
  Regeneration and Flight.
- **A short adventure** of three fights and several choices, where feats of
  Agility, Strength, Reason and Intuition decide how each scene goes.
- **The universal chart** on screen, with every roll marked on it, plus a
  free roller you can use at a real table.

## Rules it uses

- The rank scale from Zero to Infinite, with rank shifts applied to the rank
  and capped as the rules say.
- Simple feats with White, Bronze, Silver and Gold results, and ranked feats
  against a difficulty.
- Blunt and lethal attacks in melee and at range, with armour, slams, stuns and
  killing blows resisted by Strength or Endurance.
- Dodging and aiming.
- Foes dropped by a lethal attack start dying and lose a rank of Endurance each
  round. A hero who lets one die loses all karma; first aid saves them.
- Karma spent before a roll to guarantee a result, costing the gap between the
  roll and the number needed, with a minimum of 10.
- Foes are the Goon, Gang Leader and Ninja from the rulebook, plus an original
  villain.

## Where it departs from the book

This is a small solo game, so some rules are simplified or left out:

- Each fight happens in one area. There is no movement, charging, grappling,
  catching or interposing, and a slam costs an action rather than moving you.
- Powers are picked from a short list at fixed ranks instead of rolled on the
  power tables. Mental Blast and Flight work in simplified ways.
- "Karma on guard" is a house rule: it spends karma only when a stun or killing
  blow would otherwise knock your hero out.
- A defeated hero can retry the fight with at least three quarters of their
  health. Recovery between fights is the game's own rule, not the book's.
- Origins, specialities, wealth, fame, contacts, pushing limits and power
  stunts are not included, and nothing from Advanced FASERIP is used.

## Files

- `index.html` — the whole game: markup, styles and script
- `logo.svg` — repository logo and page icon
- `LICENSE` — MIT licence for the program code
- `OGL.txt` — Open Game License 1.0a and the designation of Open Game Content

## Licence

The program code is MIT licensed; see `LICENSE`.

The game rules are Open Game Content from FASERIP by Gurbintroll Games, used
under the Open Game License Version 1.0a; see `OGL.txt`. The adventure text,
setting and character names are original to this game and are not Open Game
Content.
