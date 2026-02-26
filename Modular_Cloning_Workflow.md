# Modular Cloning (MoClo) Workflow

## Day 1 – Overnight Parts and Plate Preparation

### Equipment
- Sterile inoculation loop
- Bunsen burner
- Sterile workspace
- Ice bucket with chilled “ice” (gel packs, aluminum beads, etc.)
- 15 mL culture tubes

### Reagents
- MoClo Kit (CIDAR)
- Antibiotics (kanamycin, ampicilin/carbenicilin)
- LB agar
- LB broth

### Procedure

#### (1) Antibiotic Plate Prep – 1.5 hours
- Prepare antibiotic plates for the final step.
- Determine number of samples: you will need 100 µL of competent cells for each plate, and 1 plate per sample.
- If you do a serial dilution (10 µL, 50 µL, and 100 µL) and positive/negative controls, adjust to 5 plates per sample.
- Use 1 µL per 1 mL of 1000× antibiotic stock.

#### (2) Copying and Storing MoClo Kit Parts (Glycerol Stocks) – 1 hour
- Make 5 mL LB medium culture tubes with appropriate antibiotics for parts and label tubes corresponding to part and location in the kit.
- Work next to a Bunsen burner or other sterile location.
- Pick your parts from the master MoClo kit and inoculate the 5 mL LB medium.
- Keep the master kit on ice (−20 °C).
- Swab each desired well.
- Be careful to not contaminate the wells; using a sterile loop, ensure it is cooled to not burn samples.
- Run loop through flame to sterilize 20–30 seconds until glowing red, then let cool off for 20–30 seconds.
- Alternatively, use any other sterile technique for sampling (multi-tip pipette single-use tips, sterile toothpicks).
- If you already copied parts before, use those glycerol stocks.
- Grow overnight (12–16 h, 37 °C, 100–250 rpm).

---

## Day 2 – Miniprep, Transformation, Stock Solutions

### Equipment
- Bunsen burner
- Sterile workspace
- Ice bucket with chilled “ice” (gel packs, aluminum beads, etc.)
- Qiagen miniprep kit + spin tubes
- Water bath preset at 42 °C
- 1.5 mL microcentrifuge tubes

### Reagents
- MoClo Kit (CIDAR)
- Antibiotics (kanamycin, ampicilin/carbenicilin)
- LB agar
- LB broth
- 30% glycerol
- Qiagen miniprep reagents
- Chemically competent cells (or other transformation method)

### Procedure

#### (1) Copy Parts
- Turn on water bath preset at 42 °C if doing chemical transformation.
- For each strain, mix 500 µL of saturated overnight culture with 500 µL sterile 30% glycerol in a screw-cap cryotube.
- Invert to mix.
- Store glycerol stocks at −80 °C.
- This is now your template kit for the MoClo parts selected.
- If you need to redo the miniprep, use these, not the master kit, to minimize contamination of the master kit.

#### (2) Isolation of Plasmid DNA (Qiagen Miniprep) – 3–4 hours
- Inoculate 5 mL LB + antibiotic with a single colony of each desired MoClo part, and grow overnight (see Day 1, Step (2)).
- Harvest 1–5 mL of culture by centrifugation for 10 min at ~3,500 rpm.
- Label 3 sets of tubes at this time: 2 microcentrifuge tubes per sample and 1 QIAprep column per sample.
- All subsequent centrifuge steps are done on the benchtop centrifuge at 13,000 rpm.
- Resuspend the pellet in 250 µL Buffer P1 with RNase A. Transfer to a 1.5 mL microcentrifuge tube.
- Add 250 µL Buffer P2, invert 4–6 times to lyse (DO NOT LET REACTION GO MORE THAN 5 MINUTES).
- Add 350 µL Buffer N3, invert to mix (should be cloudy), and centrifuge 10 min.
- Transfer 800 µL of the supernatant to a QIAprep column; centrifuge 1 min and discard flow-through.
- Wash with 750 µL Buffer PE, centrifuge, and discard flow-through.
- Spin 1 min to dry; transfer column to a new microcentrifuge tube (not the one used as the QIAprep collection tube).
- Elute plasmid DNA with 30–50 µL nuclease-free water or Buffer EB; incubate 1 min and centrifuge to elute.
- Quantify DNA (e.g., Nanodrop) and store at 4 °C (short term, weeks) or −20 °C (long term, months).

#### (3) Golden Gate Assembly – 3 hours
- Prepare assembly reactions (20 µL total volume):

  - Use a final amount of 75 ng per part.
  - The backbone can be halved (37.5 ng).
  - Calculate the final volume of sterile diH₂O needed and add this first, then add parts (should be 5–11 µL total volume for DNA + water).
  - Add 2 µL of T4 buffer (some vials need to thaw at 4 °C; prepare them before nanodropping minipreps to determine DNA concentration).
  - Add 1 µL of T4 DNA ligase.
  - Add 1 µL of the desired restriction enzyme (BsaI for stage 1, BsbI for stage 2) (temperature-sensitive – add last and keep on ice).
  - If adding more enzymes and buffer, adjust total volume accordingly.
  - Gently mix; tapping is sufficient.
  - Add tubes to the thermocycler and ensure caps are locked.
  - Lock the lid.

- Thermocycler program (example):
  - 37 °C for 20 min.
  - 10 cycles of:
    - 37 °C for 1 min
    - 16 °C for 2 min
  - 50 °C for 5 min
  - 80 °C for 10 min
  - Hold at 4 °C.
- Lock the lid.

#### (4) Transformation into *E. coli* – 3 hours
- Thaw chemically competent *E. coli* cells on ice (place in fridge). Set timer for 20 min (do not exceed).
- Add 1–2 µL Golden Gate assembly reaction to 50 µL competent cells; mix gently.
- Aim for a final plasmid amount of approximately ~100 ng in the transformation.
- Incubate on ice for 30 min (use fridge).
- Heat shock at 42 °C for 45 seconds.
- Return to ice for 2 min.
- Add 200 µL LB medium and recover at 37 °C for 60 min with shaking.
- Plate 100 µL onto LB agar containing the appropriate antibiotic.
- Add 1 mL of LB + antibiotic to the remaining transformation mixture in the tube and grow overnight.
- Incubate overnight at 37 °C.
- Check next day for colony growth.
- Refer to specific strain transformation protocols if needed (e.g., NEB high-efficiency transformation protocols).

---

## Day 3 – Glycerol Stocks, Experimental Results

### Procedure

#### (1) Overnight Culture – 15 min (setup)
- If transformation succeeded, swab a single colony from agar plates into antibiotic LB broth (1–5 mL).
- Grow overnight in antibiotic LB broth (12–16 h, 37 °C, 100–250 rpm).

#### (2) Glycerol Stocks – 15 min
- For each successful growth, mix 500 µL of saturated overnight culture with 500 µL sterile 30% glycerol in a screw-cap cryotube.
- Invert briefly to mix.
- You can use either the re-grown culture from the plate or the original tube; backups and isolation of a single colony are recommended.
- Store glycerol stocks at −80 °C.
