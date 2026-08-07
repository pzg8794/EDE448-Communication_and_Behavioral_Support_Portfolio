# EDE448 Communication and Behavioral Support Portfolio

This repository is the dedicated GitHub and Overleaf workspace for Piter Zacari Garcia Bautista's EDE448 **Communication and Positive Behavioral Support Strategies and Resources Portfolio**.

## Overleaf Entry Point

Set `main.tex` as the main document. The project is self-contained:

- `main.tex`: title page, assignment and rubric map, portfolio map, synthesis, and document assembly
- `resources/`: ten numbered practitioner resources
- `references.bib`: unified bibliography

Overleaf should compile the project with pdfLaTeX and BibTeX. A local equivalent is:

```bash
latexmk -pdf main.tex
```

## Portfolio Structure

The portfolio uses **Communication as Access-to-Agency** as its organizing theme. It contains ten resources covering sensory access, inclusive peer culture, Prevent-Teach-Reinforce planning, dignity-centered classroom systems, routines and transitions, AAC selection, communication opportunities, low-tech AAC continuity, home-school communication, and flexible peer participation.

Each resource now carries an explicit assignment or practice-artifact trail. The source set includes the completed Pine Brook sensory walk, taught Grade 2 Kit for Kids lesson, PTR completion notes, Grade 2 IGNITE curriculum supports, EDU486 youth feedback, Field Friday agenda, access-pathways graphic, Identity Beads and policy/showcase roles, and the authentic July 29 family-update workflow. Resource 6 remains native TikZ, and all ten resources remain two-page spreads in the 26-page PDF.

## Privacy and Evidence Boundary

The repository includes only de-identified text and public-safe reconstructions. It does not contain participant photographs, youth names, personalized family stories, parent contact information, or completed parent responses. Resource 9 derives its headings and sequence from the private family-update production archive, then leaves its proposed family-return fields visibly blank. The prospective AAC examples do not claim that a particular camper used TD Snap or another AAC system.

## Course Repository Relationship

The public course hub is [pzg8794/EDE448](https://github.com/pzg8794/EDE448). In a local checkout of that course repository, this dedicated repository lives at:

```text
portfolio/repository/
```

That nested directory is intentionally ignored by the outer course repository, so this repository keeps an independent history and remote. Pull Overleaf/GitHub edits here before review; after an approved revision, synchronize the editable source back to `portfolio/latex/` in the course repository.

## Submission Boundary

GitHub and Overleaf are drafting and review environments. Nothing is considered submitted to Blackboard until Piter reviews the compiled PDF and confirms the Blackboard submission receipt.
