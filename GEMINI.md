# GEMINI.md

## Project: Personal CV/Resume Repository

### 2026-01-15: Directory Reorganization
- Reorganized the directory structure to improve management of master files, versions, and tailored documents.
- Created `00_master`, `01_versions`, `02_tailored`, `03_archive`, and `Profile` directories.
- Moved and renamed existing files:
  - `CV_EN.md` -> `00_master/RGEM_CV_MASTER_EN.md`
  - `CV_ES.md` -> `00_master/RGEM_CV_MASTER_ES.md`
  - `docs/Profile.pdf` -> `Profile/Profile.pdf`
  - `docs/cvRGEM.pdf` -> `Profile/Profile_CV.pdf`
  - `docs/cvRGEM.docx` -> `03_archive/2024/cvRGEM_legacy.docx`
- Updated `CLAUDE.md` to reflect the new structure.
- Removed legacy `docs/` directory.

### 2026-01-15: Git Synchronization
- Initialized local Git repository.
- Linked to remote repository: `https://github.com/RobertoGEMartin/CV`.
- Pushed reorganization changes to `main` branch.

### 2026-01-15: CV Optimization & Metrics Engineering
- Executed optimization protocol based on `.claude/commands/mejora_CV.md`.
- Updated `00_master/RGEM_CV_MASTER_EN.md` and `ES.md` with executive tone.
- Generated tailored versions in `01_versions/executive/2025/` and `01_versions/technical/2025/`.
- Created `cv_analysis_report.md` with metrics proposal and Quality Control.
- Pushed optimization changes to `main` branch.

### Current Structure
```
CV/
├── 00_master/          # Master CV files in Markdown (EN/ES)
├── 01_versions/        # Professional versions by sector/year
├── 02_tailored/        # Specifically adapted CVs for calls/companies
├── 03_archive/         # Past years archive
└── Profile/            # Official profile exports (LinkedIn, etc.)
```
