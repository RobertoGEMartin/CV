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

### Current Structure
```
CV/
├── 00_master/          # Master CV files in Markdown (EN/ES)
├── 01_versions/        # Professional versions by sector/year
├── 02_tailored/        # Specifically adapted CVs for calls/companies
├── 03_archive/         # Past years archive
└── Profile/            # Official profile exports (LinkedIn, etc.)
```
