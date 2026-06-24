Research Artefact Organisation Template

This repository provides a standardised folder structure for organising a thesis or dissertation project from initial ideation through to final submission. It serves as a central workspace for all research-related materials, including planning, documentation, artefact references, and dissertation writing.

Each top-level directory includes its own README file describing its purpose, contents, and maintenance guidelines.

Folder Structure
Meta/
Brainstorm/
References/
Templates/
Administrative/
Artefact/
Dissertation_Drafts/
Meta/

Contains governing documents that define the project scope and requirements.

Typical contents:

Project descriptor
Grading rubric
Deadlines and milestones
Official guidelines or brief
Brainstorm/

Used for early-stage exploration and ideation.

Typical contents:

Initial ideas and concepts
Scope iterations
Alternative approaches
Rejected or abandoned directions
References/

Used to track and store academic and technical sources.

Typical contents:

Literature review tracking sheet
PDFs or notes from research papers
Summaries and annotations of sources
Citation metadata
Templates/

Contains reusable document templates to ensure consistency across the project.

Typical contents:

Report templates
Proposal structure templates
Presentation templates
Formatting guidelines
Administrative/

Stores formal and supervisory documentation.

Typical contents:

Supervisor meeting notes
Approval forms
Submission confirmations
Institutional documentation
Artefact/

Contains reference material for the implementation, not the source code itself.

Typical contents:

Source code repository links and commit references
System architecture documentation
Dependency and environment specifications
Input data references
Output results and evaluation reports
Validation and reproducibility materials

Note: The actual source code is maintained in a separate repository.

Dissertation_Drafts/

Contains all writing stages of the dissertation and related deliverables.

Typical contents:

Proposal drafts
Chapter-wise writing
Presentation materials
Iterative versions of the dissertation
Final submission copy
Naming and Versioning Convention
File names should avoid spaces (use underscores or camelCase if needed).
Version control should follow incremental numbering:
v1, v2, v3, etc.
Final submission files should be clearly marked:
_FINAL

Example:

literature_review_v2.docx
methodology_FINAL.docx
Suggested Workflow

The repository is intended to be used in the following general progression:

Meta → Brainstorm → References → Templates → Administrative → Artefact → Dissertation_Drafts
Version Control Guidelines
Do not commit large, temporary, or environment-specific files.
Use .gitignore to exclude:
datasets (if large or sensitive)
compiled files
local environment configurations
Maintain clean and meaningful commit messages to ensure traceability.
