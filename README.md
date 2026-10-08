# ⚛️ Chemical Bonding Lab

Six hands-on simulations (plus a comparison summary) that show high school chemistry students how **ionic**, **metallic**, and **covalent** bonds form. Everything runs in the browser, with no install and no accounts.

**▶ Open it:** https://tdavidsm.github.io/chem-bonding-activities/

## The activities

| # | Tab | The big idea | To earn the ⭐ |
|---|-----|--------------|----------------|
| 1 | **Ionic: Electron Transfer** | Metal atoms (Bohr models) give valence electrons to nonmetal atoms. Keep adding atoms until every atom is a stable ion, then read off the formula. | Make 4 different compounds, answer 1 question |
| 2 | **Ionic: Crystal Lattice** | Cooling a melt of Na⁺ and Cl⁻ grows a checkerboard crystal from a seed. Then drag ions toward the crystal and watch them get pulled and pushed into place. | Grow a crystal, add 6 ions that settle, answer 1 question |
| 3 | **Metallic: Electron Sea** | Atoms dropped onto a metal lattice give their valence electrons to the shared sea. A voltage makes the sea flow. | Add 6 atoms (2 different metals) and turn on the voltage |
| 4 | **Covalent: Sharing a Pair** | Two nonmetal atoms (H₂, F₂, Cl₂) approach. Electrons orbiting each atom shift into the space between the nuclei. A live energy curve shows the bond length. | Bond H₂ and F₂/Cl₂, answer the check question |
| 5 | **Covalent: Double Bond** | O₂ shares two pairs (bonus: N₂ triple bond). Compare bond length and energy to single bonds. | Bond O₂, answer the check question |
| 6 | **Covalent: Build a Molecule** | Add H, C, N, O, F, Cl, S, P atoms and drag them together. Atoms share until every atom has a full outer shell, then the molecule is named. | Build H₂O, NH₃, CH₄, CO₂ (bonus: HCN, C₂H₄), answer 3 questions |
| 7 | **Summary: Compare the Bonds** | A side-by-side picture of the three bond types and three comparison questions (ionic vs. covalent, ionic vs. metallic, metallic vs. covalent). | Answer all 3 correctly |

Finishing all seven gives a **completion code**, which only appears once every question in the lab has been answered correctly. **Turn it in** opens the class Google Form with the name and code already filled in (the form has just two questions, Name and Code). Wrong answers get a hint and freeze the question for one minute (with a countdown, saved across reloads); the student must then pick the right answer before the next question unlocks. Progress and answered questions are saved on the device.

To point it at a different form, change `FORM_BASE` and `FORM_ENTRY` in `index.html`.

## Virtual lab: ratio of calcium to chlorine (separate page)

**▶ Open it:** https://tdavidsm.github.io/chem-bonding-activities/calcium-chloride-lab.html (also linked from the main page header)

A walk-through of the *Determine the Ratio of Calcium to Chlorine in Calcium Chloride* lab, in the same order as the handout. It is a practice run for the real lab; it has no completion code and does not touch the bonding activities' progress.

| Tab | Handout step | What students do |
|-----|--------------|------------------|
| Prep | Safety / equipment | Put on goggles, tap each item, answer 2 safety questions |
| Step 1 | 1 | Drag the flask onto the balance, record its mass |
| Step 2 | 2 | TARE, add ~1 g of calcium with forceps (bare hands are refused), record the mass |
| Steps 3–4 | 3, 4 | Pour 25 mL of water via the cylinder; **atom view:** Ca → Ca ions + OH⁻ + H₂ bubbles; test pH with pH paper |
| Steps 5–6 | 5, 6 | Hold the flask, add 10 drops then squirts of HCl with the eyedropper, swirl; **atom view:** H⁺ + OH⁻ → H₂O, Ca ions and Cl⁻ dissolved |
| Step 7 | 7 | pH paper again |
| Steps 8–9 | 8, 9 | Build the ring stand / mesh / clamp / Bunsen burner, light it, boil dry; **atom view:** water and extra HCl leave, ions lock into a solid |
| Steps 10–12 | 10–12 | Cool, mass flask + CaCl₂, wash, return to the center table |
| Analysis | Data Analysis Table 2, Questions 1–4 | Masses → Cl:Ca mass ratio, then pie charts (ion count → mass, side by side with the student's own pie) to pick the formula |

Electron colors in the atom views: **gold** = from calcium, **blue** = a water molecule's own, **violet** = from the H of HCl.

Teacher notes:
- The atom views never show the final Ca:Cl ratio: the sample is a small window of the flask, the solid is a jumbled cluster, and extra HCl (used to dissolve the last of the white solid) boils away. Day 1 does show calcium giving up electrons (the handout already gives Ca(OH)₂).
- The practice masses are randomized per student (flask mass and a small weighing error), and the Analysis tab's three mass boxes can be overwritten with the student's **real** lab numbers.
- Add `#unlock` to the URL to open every tab without finishing the steps. "Start the practice lab over" (under the data table) clears saved progress.

## Modeling notes (for teachers)
- **Activity 1:** a nonmetal is stable at 8 valence electrons; a metal is stable once its valence shell is empty. Electrons that came from the metal stay gold so students can track them. The formula uses the simplest ratio (2 Na + 2 Cl is still NaCl).
- **Activity 2:** ions feel real Coulomb attraction/repulsion plus a hard core. A gentle "lattice-site pull" (it fades as temperature rises) stands in for the periodic potential of the rest of the crystal.
- **Activity 3:** electrons are drawn as dots in a sea around fixed cores. The model does not include electron waves or band theory.
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
