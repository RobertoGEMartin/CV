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

### 2026-01-15: CV Refinement v1.1 with Strategic Metrics
- Extracted concrete metrics from project portfolio spreadsheet.
- Updated all CV versions (Master, Executive, Technical in EN/ES) with real data:
  - Division budget: €10-12M annually
  - Team size: 25+ engineers/researchers (14 AI, 11 R&D)
  - Concurrent programs: 15+ strategic projects
  - Project-specific budgets: SEDA (€196K), DLSM (€389K), ENIGMA (€289K)
- Applied "strategic ownership" language refinement per mejora_CV.md:
  - Emphasized decision authority and risk management
  - Highlighted institutional trust and program renewals
  - Focused on technical-to-operational translation
- Pushed v1.1 refinement to `main` branch.

### 2026-01-15: Integration of Education & Publications
- Integrated structured data from `Profile/Estudios.md` and `Profile/publicaciones.md`.
- **Master CVs Update**:
  - Replaced generic education with full chronological list (UPM, Stanford, Deeplearning.ai, etc.).
  - Added full list of publications categorized by "Applied AI & Defence" vs "Historical Technical".
- **Executive CVs Update**:
  - Filtered education to Degree + Top 3 Strategic Certifications.
  - Summarized publications to a single high-impact statement focusing on DESEI+D and sovereignty.
- **Technical CVs Update**:
  - Included full certification list emphasizing technical breadth (Udacity, Microsoft, etc.).
  - Selected "Top 5" publications relevant to Applied AI & Defence as per strategic guidelines.
- Pushed changes to `main` branch.

### Current Structure
```
CV/
├── 00_master/          # Master CV files in Markdown (EN/ES)
├── 01_versions/        # Professional versions by sector/year
├── 02_tailored/        # Specifically adapted CVs for calls/companies
├── 03_archive/         # Past years archive
└── Profile/            # Official profile exports (LinkedIn, etc.)
```
