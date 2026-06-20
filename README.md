# safety-on-whose-terms-analysis

ATLAS.ti project and supporting data for the MSc thesis *"Safety on Whose Terms? Participatory Speculative Design for Feminist Safety Technologies"* (University of Amsterdam, Human-Computer Interaction).

The thesis investigates how female-identifying students in Amsterdam collectively imagine and reframe safety technology through participatory speculative design (PSD). It is grounded in feminist HCI, value-sensitive design, and speculative/critical design. Sixteen participants (N=16) took part across four workshops (WS1 to WS4), each producing a speculative safety prototype: Creep Alert, Angel Drone, SafeSpace App, and Teleportation Necklace.

## Contents

```
.
├── Thesis_FeministSafety_v1.atlasti     # ATLAS.ti project file
├── docs/                                # survey exports, support- and source documents
└── exports/codebooks/                   # exported codebook
```

### ATLAS.ti project

`Thesis_FeministSafety_v1.atlasti` holds the qualitative coding for the study: five coded sources (Mapping, Critical Framing - Assumptions, Critical Framing - Ratings, Presentations, Safety Terms Responses), coded using a mixed inductive, semi-deductive, and sensitising-concept-guided approach. Field notes and intake questionnaires are kept as background context but are not themselves coded.

### docs/

Two Qualtrics survey instruments are stored here:

- `Intake_Workshop_Survey_Results.csv` and `Intake_Workshop_Survey_Results_CLEANED.csv` — the intake questionnaire, capturing demographics and baseline attitudes toward safety and existing safety tools, collected before each workshop.
- `Post_Workshop_Survey_Results.csv` — the post-workshop survey, capturing reflections on the workshop activities themselves (reframing of safety, the speculative design process, participation, and workshop environment).

**Full vs. cleaned intake data.** The full intake file contains 20 responses; the cleaned file contains 16. The four responses removed in the cleaned version belong to participants who registered and completed the intake questionnaire but cancelled last-minute and did not attend their workshop, so they have no corresponding workshop or coded data. The cleaned file is the one used as the analytic sample (N=16) referenced throughout the thesis; the full file is kept for transparency and audit purposes only.

Both CSVs are semicolon-delimited Qualtrics "Advanced Format" exports, with two metadata rows (import IDs and full question text) below the header row. When loading with pandas, use `skiprows=[1,2]`.

### exports/codebooks/

Contains the final codebook export from ATLAS.ti (codebook_15052026.csv), named by export date.

## Notes

- Workshop 2 was conducted in Dutch; that data was translated to English prior to coding.
