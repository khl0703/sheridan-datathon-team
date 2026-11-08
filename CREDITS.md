# Sources and development credits

## Dataset

The project uses the **PKDD'99 Discovery Challenge Financial dataset**, from the
[CTU Prague Relational Dataset Repository](https://relational.fel.cvut.cz/dataset/Financial),
as prepared for the Sheridan Datathon Tangerine track. This is the financial data source for the analysis and simulation.

## Frontend design skills

The following open-source agent skills were used with Claude during frontend development.
The credits describe their role as design and implementation guidance, rather than financial datasets or runtime dependencies.

| Skill | Author / maintainer | Role in our frontend workflow | Upstream license |
| --- | --- | --- | --- |
| [Taste](https://github.com/Leonxlnx/taste-skill), invoked as `design-taste-frontend` | Leonxlnx | Visual direction, typography, layout and design consistency. | [MIT](https://github.com/Leonxlnx/taste-skill/blob/main/LICENSE) |
| [Impeccable](https://github.com/pbakaus/impeccable), invoked as `impeccable` | pbakaus | Visual hierarchy, spacing, responsive interface review and polish. | [Apache-2.0](https://github.com/pbakaus/impeccable/blob/main/LICENSE) |
| [Design Engineering](https://github.com/emilkowalski/skills), invoked as `emil-design-eng` | Emil Kowalski | Interaction design, animation easing, hover transitions and tactile feedback. | [MIT](https://github.com/emilkowalski/skills/blob/main/LICENSE) |

Emil Kowalski's skill was originally installed from `emilkowalski/skill`; that repository URL now redirects to
[`emilkowalski/skills`](https://github.com/emilkowalski/skills).

These entries were checked against the project's local skill installation and frontend development records.
Upstream repository and license links were verified on November 8, 2026. The skill packages themselves are not
bundled by this attribution update. Each upstream project's license remains available at the linked source;
this document does not assign those licenses to the whole Resilience Rewired project.

## AI assistance

Claude was used for coding and analysis, including frontend work guided by the skills above. Codex was used for
code review, verification and submission preparation. Gemini is an optional application feature for interpreting
scenario text and rewriting customer messages; the application's financial calculations are implemented in code.

The open-source skill authors are credited for their development resources. They are not represented as project
team members or endorsers of this submission.
