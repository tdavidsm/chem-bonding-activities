# ⚛️ Chemical Bonding Lab

Six hands-on simulations (plus a comparison summary) that show high school chemistry students how **ionic**, **metallic**, and **covalent** bonds form. Everything runs in the browser, with no install and no accounts. A second page continues with Lewis structures, naming, and acids (see below).

**▶ Open it:** https://tdavidsm.github.io/chem-bonding-activities/

## The activities

| # | Tab | The big idea | To earn the ⭐ |
|---|-----|--------------|----------------|
| 1 | **Ionic: Electron Transfer** | Metal atoms (Bohr models) give valence electrons to nonmetal atoms. Keep adding atoms until every atom is a stable ion, then read off the formula. | Make 4 different compounds, answer 1 question |
| 2 | **Ionic: Crystal Lattice** | Cooling a melt of Na⁺ and Cl⁻ grows a checkerboard crystal from a seed. Then drag ions toward the crystal and watch them get pulled and pushed into place. | Grow a crystal, add 6 ions that settle, answer 1 question |
| 3 | **Metallic: Electron Sea** | Atoms dropped onto a metal lattice give their valence electrons to the shared sea. A voltage makes the sea flow. A second mode, the **Alloy mixer**, lets students pick up to three metals, set their percentages, and dump them together: every atom donates its electrons to one sea, so any mix is stable. | Add 6 atoms (2 different metals), turn on the voltage, and mix an alloy |
| 4 | **Covalent: Sharing a Pair** | Two nonmetal atoms (H₂, F₂, Cl₂) approach. Electrons orbiting each atom shift into the space between the nuclei. A live energy curve shows the bond length. | Bond H₂ and F₂/Cl₂, answer the check question |
| 5 | **Covalent: Double Bond** | O₂ shares two pairs (bonus: N₂ triple bond). Compare bond length and energy to single bonds. | Bond O₂, answer the check question |
| 6 | **Covalent: Build a Molecule** | Add H, C, N, O, F, Cl, S, P atoms and drag them together. Atoms share until every atom has a full outer shell, then the molecule is named. | Build H₂O, NH₃, CH₄, CO₂ (bonus: HCN, C₂H₄), answer 3 questions |
| 7 | **Summary: Compare the Bonds** | A side-by-side picture of the three bond types and three comparison questions (ionic vs. covalent, ionic vs. metallic, metallic vs. covalent). | Answer all 3 correctly |

Finishing all seven gives a **completion code**, which only appears once every question in the lab has been answered correctly. **Turn it in** opens the class Google Form with the name and code already filled in (the form has just two questions, Name and Code). Wrong answers get a hint and freeze the question for one minute (with a countdown, saved across reloads); the student must then pick the right answer before the next question unlocks. Progress and answered questions are saved on the device.

To point it at a different form, change `FORM_BASE` and `FORM_ENTRY` in `index.html`.

## Display notes
- Valence shells show **dotted circles for the open spots** where electrons could go. In the covalent activities the open spots fill in as the shared pair forms.
- On the first tab each atom's electrons have **their own color**, so students can follow an electron from the metal to the nonmetal.
- In portrait the stage is smaller, the tabs are compact, and a nudge bar points down to the instructions and controls.

## Virtual lab: ratio of calcium to chlorine (separate page)

**▶ Open it:** https://tdavidsm.github.io/chem-bonding-activities/calcium-chloride-lab.html (also linked from the main page header)

A walk-through of the *Determine the Ratio of Calcium to Chlorine in Calcium Chloride* lab, in the same order as the handout. It is a practice run for the real lab; it has no completion code and does not touch the bonding activities' progress.

| Tab | Handout step | What students do |
|-----|--------------|------------------|
| Prep | Safety / equipment | Put on goggles, tap each item, answer 2 safety questions |
| Step 1 | 1 | Drag the flask onto the balance, record its mass |
| Step 2 | 2 | TARE, add ~0.5 g of calcium with forceps (bare hands are refused), record the mass |
| Steps 3–4 | 3, 4 | Pour 25 mL of water via the cylinder; **atom view:** Ca → Ca ions + OH⁻ + H₂ bubbles; test pH (strip on the table, a couple of drops from an eyedropper) |
| Steps 5–6 | 5, 6 | Hold the flask, add 10 drops then squirts of HCl with the eyedropper, swirl; **atom view:** H⁺ + OH⁻ → H₂O, Ca ions and Cl⁻ dissolved |
| Step 7 | 7 | pH paper again |
| Steps 8–9 | 8, 9 | Build the ring stand / mesh / clamp / Bunsen burner, light it, boil dry; **atom view:** water and extra HCl leave, ions lock into a solid |
| Steps 10–12 | 10–12 | Cool, mass flask + CaCl₂, wash, return to the center table |
| Analysis | Data Analysis Table 2, Questions 1–4 | Masses → Cl:Ca mass ratio. Then, for each possible formula, students **build it on a balance** (drag the right number of Ca and Cl atoms onto the pans), see the totals, the division and a pie chart made for them, and **compare** it with the pie from their own data (✓ matches / ✗ not a match). At least 3 formulas must be built |

Electron colors in the atom views: **gold** = from calcium, **blue** = a water molecule's own, **violet** = from the H of HCl.

Teacher notes:
- The atom views never show the final Ca:Cl ratio: the sample is a small window of the flask, the solid is a jumbled cluster, and extra HCl (used to dissolve the last of the white solid) boils away. Day 1 does show calcium giving up electrons (the handout already gives Ca(OH)₂).
- The practice masses are randomized per student (flask mass and a small weighing error), and the Analysis tab's three mass boxes can be overwritten with the student's **real** lab numbers.
- Add `#unlock` to the URL to open every tab without finishing the steps. "Start the practice lab over" (under the data table) clears saved progress.

## Virtual lab: miscible and immiscible liquids (separate page)

**▶ Open it:** https://tdavidsm.github.io/chem-bonding-activities/miscible-liquids-lab.html (also linked from the main page header)

A practice run of *Miscible and Immiscible Liquids – Separation Techniques* (water, isopropyl alcohol, salt), in the handout's order. Same look and controls as the calcium chloride lab; progress is saved separately on the device.

| Tab | Handout step | What students do |
|-----|--------------|------------------|
| Prep | Safety / equipment | Goggles, tap each item, 2 safety questions |
| Steps 1–2 | 1, 2 | Pour water to 4 cm and isopropyl alcohol to 2 cm, reading the cm marks (big landing zone; the tube turns green at 3.5–4.5 cm / 1.5–2.5 cm) |
| Steps 3–4 | 3, 4 | Pour tube 1 into tube 2, stopper it, rock it. **Atom view:** water and alcohol both have a polar O–H, form hydrogen bonds with each other, and mix: *miscible* |
| Step 5 | 5 | Draw up a few drops of the mixture, squirt them on the table (marked safe spot), try a match: it only flickers |
| Steps 6–7 | 6, 7 | Add a scoop of salt, stopper, shake (drag or button). One scoop dissolves with no layers, so add a second; layers form. **Atom view:** water molecules wrap the Na⁺ and Cl⁻ ions, fewer are free to bond with alcohol, and the alcohol is squeezed out to the top ("salting out"); a live counter of water–alcohol hydrogen bonds falls to 0 |
| Steps 8–9 | 8, 9 | Sample the top layer (the depth of the dropper tip decides which layer) and burn it; the bottom layer (optional) does not burn. **Atom view:** 2 C₃H₈O + 9 O₂ → 6 CO₂ + 8 H₂O, with the new bonds' electron pairs colored from both reactants |
| Steps 10–11 | 10, 11 | Pour the contents into the sink, wash and return the four pieces of equipment |
| Questions | Questions 1–5 + a bonus | The five handout questions (water and isopropyl alcohol are compounds, miscible, top layer = isopropyl alcohol, what was left = salt water + undissolved salt), plus an atom-level "why did the alcohol get squeezed out?" |

Electron colors: **blue** = water, **violet** = alcohol, **gold** = from sodium, **teal** = oxygen gas.

Finishing every step and answering the five lab questions gives a **completion code** (the bonus question is optional). **Turn it in** opens the class Google Form with the name and code already filled in (`FORM_BASE` / `FORM_ENTRY` in `miscible-liquids-lab.html`; the form has two questions, Name and Code).

**Updates:** both lab pages show `Lab version: …` at the bottom and, when a newer version is live, show a yellow "Update now" banner (progress is stored on the device under the same key, so it is kept). To force a refresh on a stale copy, open the page with `?v=<anything>` added, e.g. `miscible-liquids-lab.html?v=2`; do **not** clear Safari's "website data", which would erase saved progress. Bump `APP_VERSION` in the page whenever you publish a change.

Teacher notes: the atom views use tiny samples, and the water : alcohol count is much closer to 1 : 1 than the real mole ratio (about 8 : 1) so the molecules are easy to see. In the simulation the Part 1 mixture only flickers, and the burning of the top layer is shown with a simplified one-step reaction. Add `#unlock` to the URL to open every tab. Note that this simulation chooses the outcomes (the mixture does not sustain a flame, two scoops are needed for layers); check them against what actually happens in your classroom.

## Lewis structures, naming, and acids (separate page)

**▶ Open it:** https://tdavidsm.github.io/chem-bonding-activities/lewis-structures.html (also linked from the main page header)

The follow-up to the covalent activities. Same look, same electron colors per atom, same dotted open spots, same one-minute freeze after a wrong answer, and the same Google Form turn-in (Name + Code), but it has its **own completion code** (starts with an L) and does not touch the bonding activities' progress. Eight tabs, each unlocking the next (about 45–60 minutes):

| # | Tab | What students do |
|---|-----|------------------|
| 1 | **Lewis 1: Dot Pictures** | Animation: Bohr model → valence electrons → core + symbol → Lewis dot symbol (one dot per side, then pair up) → unpaired dots = bonds → two atoms share. Pick H, C, N, O, F or Cl. Watch 2 elements, answer 2 questions. |
| 2 | **Lewis 2: Practice Five** | Build H₂O, NH₃, CO₂, HCN and CH₂O by tapping bonds and open spots. Guidance fades: step-by-step coach with highlights → short coaching → checklist only → recipe on request → no help (hint after 2 wrong checks). A tray of valence electrons empties as they are placed. |
| 3 | **Lewis 3: Same Atoms** | The recipe (count, single bonds, outer atoms, center, multiple bonds) animated for CO, CO₂, NO₂⁻, NO₃⁻ (bonus H₂O, H₂O₂). Ions add an electron per negative charge, and the double bond slides between oxygens to show resonance. A comparison table fills in. 3 questions. |
| 4 | **Naming 1: Prefix Rules** | Animation of how a formula becomes a name (nonmetals only, prefix = atom count, no mono- on the first element, second element ends in -ide, drop a/o before a vowel). Watch 2 compounds, answer 2 questions. |
| 5 | **Naming 2: Name It** | 7 items: which compounds use prefixes (covalent vs. ionic), three formula → name and three name → formula. A prefix table stays on screen. |
| 6 | **Acids 1: Why So Odd?** | HCl in water, drawn with Lewis structures: the shared pair stays on Cl, H⁺ moves to water. Then the history: acid = sour, Lavoisier's “oxygen = acid-former” mistake, hence hydro-. 2 questions. |
| 7 | **Acids 2: Name Acids** | A flow chart (no oxygen → hydro-…-ic; -ate → -ic; -ite → -ous) animated for 8 acids, then name 6 acids. |
| 8 | **Summary** | One-glance recap and 3 questions (NO₂⁻ electron count, N₂O₄, HNO₂). Answering all three gives the **completion code** and the Turn it in button. |

Teacher notes:
- Add `#unlock` to the URL to open every tab without finishing the steps.
- Lewis structures are drawn flat with atoms on a grid and four sides per atom; the footer says real shapes are 3-D (water is bent, nitrate is a flat triangle).
- A Lewis structure is accepted when the electron total matches, every atom has a full shell (8, or 2 for H), and every formal charge is zero, so the usual textbook structure is the one that counts (for example, CO₂ must be O=C=O, not C≡O with a single bond).
- Resonance is shown but not drawn by students. Carbon monoxide uses the triple-bond structure and does not discuss formal charge.
- Electron colors by atom are assigned by position in the molecule, as in the covalent activities. In the animations the electrons recolor when they move into a lone pair on a new atom.
- To point it at a different form, change `FORM_BASE` and `FORM_ENTRY` in `lewis-structures.html`.

## Modeling notes (for teachers)
- **Activity 1:** a nonmetal is stable at 8 valence electrons; a metal is stable once its valence shell is empty. Electrons that came from the metal stay gold so students can track them. The formula uses the simplest ratio (2 Na + 2 Cl is still NaCl).
- **Activity 2:** ions feel real Coulomb attraction/repulsion plus a hard core. A gentle "lattice-site pull" (it fades as temperature rises) stands in for the periodic potential of the rest of the crystal.
- **Activity 3:** electrons are drawn as dots in a sea around fixed cores. The model does not include electron waves or band theory. In the alloy mixer each metal donates a fixed number of valence electrons (Cu 1, Zn 2, Sn 2, Al 3, Fe 2, Ni 2, Mg 2, Pb 2) and the atoms have different sizes, which is why alloys can be mixed in any proportion.
- **Activities 4–6:** electrons are shown as dots, and they blend from orbiting their own atom to the bond region as the atoms approach. Bond lengths and energies shown are textbook values (H–H 74 pm/436 kJ, F–F 143/159, Cl–Cl 199/243, O=O 121/498, N≡N 110/945).
- Molecules in activity 6 are drawn flat (2-D). Real CH₄ is a tetrahedron and water is bent at about 105°.

## Develop
It's one file. Edit `index.html` and reload. For a local server:

```bash
python3 -m http.server 8790
```

then open http://localhost:8790/index.html

## Tech
Single self-contained `index.html`: plain HTML/CSS/JS, canvas animation, Pointer Events (touch + mouse), no dependencies. Built for iPad Safari and also works on Chromebooks and laptops. Deployed via GitHub Pages from `main`.
