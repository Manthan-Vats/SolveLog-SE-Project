# SolveLog: Software Engineering Project

UML diagrams and the SRS project report for **[SolveLog](https://solvelog.vercel.app)**, a practice journal,
spaced-revision system and public portfolio for competitive programmers.
App source: [Manthan-Vats/competitive-programming-journal](https://github.com/Manthan-Vats/competitive-programming-journal).

## Contents

| Folder | What's inside |
|---|---|
| [`diagrams/`](diagrams/) | 16 diagrams, each as Mermaid source (`.mmd`), `.png` and `.svg`, with an exam checklist per diagram. **[Start here](diagrams/README.md)** |
| [`report/`](report/) | Project report in SRS (IEEE 830) format: [PDF](report/SolveLog_Project_Report.pdf) · [Markdown](report/SolveLog_Project_Report.md) |

## Diagrams

Use Case · Class · Object · Sequence (×2) · Activity · State Machine · Communication ·
ER (Crow's Foot + Chen) · Package · Component · Deployment · Control Flow Graph · DFD Level 0 · DFD Level 1

## Regenerating a diagram

Open any `.mmd` file, copy its contents, and paste into [mermaid.live](https://mermaid.live) (or a
` ```mermaid ` block on GitHub or Notion). To redraw in StarUML, use the rendered `.png` as the reference;
every element is listed in the checklist in [`diagrams/README.md`](diagrams/README.md).

## Report contents

1. Introduction · 2. Overall Description · 3. Specific Requirements (20 FRs, 11 NFRs) ·
4. System Design and UML · 5. Estimation (LOC, Function Points, Basic and Intermediate COCOMO) ·
6. Testing (techniques, 339 automated assertions, black-box EP/BVA, white-box basis path, system/security
tests on production, UAT, static analysis) · 7. Screenshots · 8. Conclusion · 9. References ·
Appendix: Requirements Traceability Matrix
