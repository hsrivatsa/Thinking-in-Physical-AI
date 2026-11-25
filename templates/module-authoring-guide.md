# Module authoring guide — reusable publication standard

[Course home](../README.md) · [Roadmap](../ROADMAP.md)

Use the existing module folder as the source of truth. Do not rename module IDs or break internal links without updating navigation. Keep Core, Applied and optional Extension distinct.

## Author one module at a time

1. Review its overview, objectives and prerequisites; check alignment with the three-stage progression.
2. Develop `lesson.md` with a motivating dilemma, prediction, mental models, intuitive explanations, mechanisms, worked examples, misconceptions, source citations, transfer and summary.
3. Implement `lab.md` as a reproducible experiment; provide inputs, instructions, variables, reset, results interpretation, safe alternatives and limitations. Place supporting assets under `labs/` or `assets/` as needed.
4. Complete `assignment.md` with deliverable instructions, a template, worked example and feedback criteria; link it to the capstone.
5. Complete `assessment.md` with objective-aligned questions, a novel scenario, proficiency anchors and explained answers (separate answer key if helpful).
6. Review technical accuracy, physical and human consequences, source rights, accessibility and workload; reproduce the lab independently.
7. Update the module, stage, course home and roadmap status together; record changes in the changelog.

## Recommended AI-assisted authoring prompt

> Develop Module [ID and title] of Thinking in Physical AI using its existing outline, the human reasoning loop and the Thinking Studio method. Preserve the three-stage progression and distinguish core, applied and optional extension material. Start from an authentic physical dilemma, require an independent prediction, teach intuitive and technical mechanisms, include a reproducible safe investigation with explicit limitations, challenge an assumption, require a defensible decision, and transfer the reasoning to a different domain. Provide the complete lesson, lab, portfolio assignment and assessment as separate Markdown files. Use verified sources; label illustrative evidence and disclose uncertainties. Do not invent experiment results or claim real-world deployment authorization. Review the files against the course rubric and publication checklist before marking them published.

## Publication gates

- [ ] Learning objectives and module content align.
- [ ] Core pathway accessible without hardware or paid tools; extensions labeled.
- [ ] Lab instructions, assets and reference outputs independently tested.
- [ ] Concepts and examples technically reviewed; assumptions and source claims verified.
- [ ] Safety, authorization, privacy, accessibility and licensing considered.
- [ ] Assessment answers and proficiency criteria complete and reviewed.
- [ ] Transfer and portfolio connection present.
- [ ] Internal links, navigation, statuses and changelog updated.

Do not mark a planned or untested lab as published. Published means reviewed course material, not certified physical behavior.
