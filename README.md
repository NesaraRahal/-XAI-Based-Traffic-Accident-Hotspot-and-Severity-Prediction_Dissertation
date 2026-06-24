# Research Artefact Organisation Template

This repository provides a reusable folder structure for organising a thesis or dissertation project from initial ideation through to final submission. It serves as a central workspace for all research-related materials, including planning, references, artefact documentation, and dissertation drafts. Each top-level folder contains its own README describing its purpose and usage.

## Folder Structure

Meta/ - Governing documents defining project scope, rubric, deadlines, and official guidelines.  
Brainstorm/ - Early-stage ideas, scope iterations, and rejected directions.  
References/ - Literature tracking, research papers, notes, and citation metadata.  
Templates/ - Reusable templates for reports, proposals, presentations, and formatting.  
Administrative/ - Supervisor meetings, approvals, and formal institutional documents.  
Artefact/ - Implementation references including repo links, architecture, datasets, results, and reproducibility notes (source code is stored separately).  
Dissertation_Drafts/ - All writing stages from proposal to final submission.

## Naming Convention

Files should avoid spaces and use underscores. Versions should be labeled v1, v2, v3, etc., with final submissions marked _FINAL.

## Suggested Workflow

Meta → Brainstorm → References → Templates → Administrative → Artefact → Dissertation_Drafts

## Version Control Notes

Large, temporary, or environment-specific files should not be committed. Use .gitignore for datasets, builds, and local configs. Commit messages should remain clear and descriptive.
