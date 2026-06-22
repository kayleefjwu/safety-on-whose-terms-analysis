# safety-on-whose-terms-analysis

ATLAS.ti project and supporting data for the MSc thesis *"Safety on Whose Terms? Participatory Speculative Design for Feminist Safety Technologies"* (University of Amsterdam, Human-Computer Interaction).

The thesis investigates how female-identifying students in Amsterdam collectively imagine and reframe safety technology through participatory speculative design (PSD). It is grounded in feminist HCI, value-sensitive design, and speculative/critical design. Sixteen participants (N=16) took part across four workshops (WS1 to WS4), each producing a speculative safety prototype: Creep Alert, Angel Drone, SafeSpace App, and Teleportation Necklace.

## Contents

```
.
├── docs/
│   ├── SourceDocuments/                            # raw per-workshop source documents
│   ├── Intake_Workshop_Survey_Results.csv
│   ├── Intake_Workshop_Survey_Results_CLEANED.csv
│   ├── List_Codes_and_Groundedness.csv
│   ├── List_Codes_and_Groundedness.xlsx
│   ├── Post_Workshop_Survey_Results.csv
│   ├── Workshop Setup.pdf
│   ├── Workshop_Slides.pdf
│   └── consent_form.pdf
├── exports/
│   └── codebooks/
│       └── codebook_15052026.csv
├── project/
│   └── Thesis_FeministSafety_v1.atlasti            # ATLAS.ti project file
└── .gitignore
```


### ATLAS.ti project

`Thesis_FeministSafety_v1.atlasti` holds the qualitative coding for the study: five coded sources (Mapping, Critical Framing - Assumptions, Critical Framing - Ratings, Presentations, Safety Terms Responses), coded using a mixed inductive, semi-deductive, and sensitising-concept-guided approach. Field notes and intake questionnaires are kept as background context but are not themselves coded.

### docs/SourceDocuments/

The primary qualitative source material, organised per workshop (WS1 to WS4). For each workshop there are five documents, corresponding to the five sources coded in ATLAS.ti:

- `WS#_Mapping.docx` — participants' individual safety maps and the clustered themes from the group debrief
- `WS#_CriticalFraming_Assumptions.docx` — the assumptions participants identified for each existing safety solution card (critical framing exercise, round 1)
- `WS#_CriticalFraming_Ratings.docx` — the group's ratings of each existing safety solution (round 2: strongly contributes / somewhat / not really / actually makes me feel less safe)
- `WS#_Presentation.docx` — the transcript or notes from the group's final presentation of their speculative prototype
- `WS#_SafetyTerms.docx` — participants' written responses to "What does safety on your terms look like?" (the closing reflective prompt)

Workshop 2 was conducted in Dutch; that data was translated to English prior to coding.

### docs/ (survey, codebook, and protocol files)

- `Intake_Workshop_Survey_Results.csv` and `Intake_Workshop_Survey_Results_CLEANED.csv` — the Qualtrics intake questionnaire, capturing demographics and baseline attitudes toward safety and existing safety tools, collected before each workshop. The full file contains 20 responses; the cleaned file contains 16. The four removed in the cleaned version belong to participants who completed the intake questionnaire but cancelled last-minute and never attended a workshop, so they have no corresponding workshop or coded data. The cleaned file is the analytic sample (N=16) referenced throughout the thesis; the full file is kept for transparency and audit purposes only.
- `Post_Workshop_Survey_Results.csv` — the post-workshop Qualtrics survey, capturing participants' reflections on the workshop itself (reframing of safety, the speculative design process, participation, and workshop environment).
- `List_Codes_and_Groundedness.csv` / `.xlsx` — the same export of the ATLAS.ti code list with groundedness and density counts, provided in both CSV and Excel format.
- `Workshop Setup.pdf` — the full facilitation protocol: room setup, materials checklist, the 3-hour workshop programme (safety mapping, critical framing exercise, Crazy 8's sketching, paper prototyping, final presentations, and reflective closing), and facilitation notes.
- `Workshop_Slides.pdf` — the presentation slides used during the workshops to guide participants through the activities and display the speculative scenario.
- `consent_form.pdf` — the physical consent form signed by participants on arrival, covering participation, audio recording of final presentations, and data handling.

Survey CSVs are semicolon-delimited Qualtrics "Advanced Format" exports, with two metadata rows (import IDs and full question text) below the header row. When loading with pandas, use `skiprows=[1,2]`.


### exports/codebooks/

Contains the final codebook export from ATLAS.ti (codebook_15052026.csv), named by export date.

### project/

`Thesis_FeministSafety_v1.atlasti` is the ATLAS.ti project file. It contains the full qualitative coding for the study across the five source types described above.

**Sources and coding approach.** The degree of inductiveness differs by source type. Mapping and Safety Terms Responses were coded inductively, as these were closest to participants' own descriptions of safety. CF-Assumptions and CF-Ratings were coded semi-deductively, as the exercise structure partially organised the data. Presentations were coded inductively with feminist HCI concepts used as a guiding analytical lens. The meaning unit was used as the unit of analysis throughout. Researcher field notes and intake questionnaires were used as contextual background only and are not coded.

**Code structure.** The codebook includes source-aware sub-codes so that themes can be traced across data sources, making it possible to follow links between participants' lived experiences (Mapping, STR), their critique of existing solutions (CF), and the speculative concepts they developed (Presentations). The main code families are: `framing` (safety framings and how they shift), `assumption` (embedded assumptions in existing safety solutions), `burden-bearer` (who bears safety responsibility), `design-move` (specific design decisions in speculative prototypes), `value` (values made explicit or implicit in the prototypes), `solution` (the existing solutions used in the CF exercise), `effect` (effects attributed to solutions), `participant-stance` (explicitly endorsed or rejected assumptions), and `protective strategy` (safety management behaviours from the Mapping activity). In vivo codes are grouped separately and capture language used verbatim by participants.

**Networks.** Themes were structured as networks in ATLAS.ti, with anchor codes forming the central node of each theme. Associated codes were linked through typed relationships: "is associated with", "is cause of", "is part of", and "contradicts". These networks are included as figures in Appendix B of the study and serve as part of the analytical audit trail.

## Notes

- Workshop 2 was conducted in Dutch; that data was translated to English prior to coding.
