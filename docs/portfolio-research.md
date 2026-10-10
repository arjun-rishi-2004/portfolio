# Portfolio research for Arjun Rishi S

Researched 10 October 2026. Sources below are the engineers' own sites, plus W3C guidance. These are references for communication and layout, not templates to copy.

## First-party examples

| Site | What works | Useful adaptation for Arjun |
| --- | --- | --- |
| [Brittany Chiang](https://brittanychiang.com/) | The opening states a precise engineering specialty and the rest of the page separates experience, selected projects, writing, and contact. Each project gets a short purpose statement and relevant stack. | Lead with a specific backend and energy infrastructure promise, then show a few strong examples rather than four company product cards. Keep resume and contact readily available. |
| [Brittany Chiang's earlier portfolio](https://v3.brittanychiang.com/) | The older version, from an earlier career stage, combines a focused introduction with skills, work history, and both featured and smaller projects. | Right-size the story for an early-career engineer: one strong role, a few independently demonstrable builds, and concise evidence of range. |
| [Wint Khant Lin](https://wintkhantlin.com/) | A backend-focused home page says what kinds of systems the engineer builds. Its three selected projects identify role, architectural decision, stack, and links to a case study or code. | Describe sanitized work as engineering problems and decisions: interoperability, state transitions, API reliability, and operating a charging network. For public personal work, link to code or demos where available. |
| [Lee Robinson](https://leerob.com/) | A short identity and mission statement lead into notes about engineering ideas and selected writing; the site is easy to scan without elaborate visuals. | Let domain knowledge and engineering judgment carry the narrative. A small "How I think" or technical writing area could demonstrate depth better than more technology badges. |

## Design implications

1. **First viewport:** Name, role, a plain-language sentence about value, and clear links to work, resume, GitHub, and contact. The cited Brittany and Wint sites make the specialty legible immediately.
2. **Work evidence:** Use two or three case-study-style summaries with *problem → contribution → engineering decision → result*. Wint's descriptions show that backend work can be credible without screenshots; Brittany's featured versus archive split prevents the page becoming a list of everything ever built.
3. **Employer confidentiality:** Identify the domain and engineering contribution while omitting internal product, customer, and partner names. Keep public repositories, personal builds, and writing distinct from confidential production examples. This is an adaptation to the user's stated requirement, not a claim from the reference sites.
4. **Credibility at this career stage:** Give specific, supportable scope and outcomes. Avoid seniority claims, generic claims of scalability, and borrowed visual motifs. The older Brittany portfolio demonstrates how to show growth and student work without pretending to have a decade-long career.
5. **Visual priority:** Design for a comfortable desktop reading width and a clear content hierarchy first, then reflow sections on narrow screens. The examples above put readable text before ornamental effects.

## Responsive and accessibility checks

- [W3C WCAG 2.2 Reflow guidance](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html): content should reflow at a width equivalent to 320 CSS pixels without loss of information or two-dimensional scrolling (except content whose meaning needs it). Check the page at 320 px and desktop at 400% zoom.
- [W3C WCAG 2.2 Target Size guidance](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html): pointer targets should generally have at least 24 by 24 CSS pixels of size or sufficient spacing under its exceptions. Check navigation, links, and mobile menu controls.
- [W3C WCAG 2.2 Focus Visible guidance](https://www.w3.org/WAI/WCAG22/Understanding/focus-visible.html): keyboard focus must be visible. Tab through navigation, project links, resume, and contact controls.

## Recommended page order

Hero and primary links → capabilities/domain knowledge → selected work (sanitized production examples plus public builds) → concise experience → technical toolkit → writing/learning → contact. This is a synthesis of the examples above for the user's goal of emphasizing what he brings to a team over current-company products.
