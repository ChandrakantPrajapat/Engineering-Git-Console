# Aerospace-Extensions.md

## Purpose

Provide engineering-aware safeguards, recommendations, and workflows for repositories containing CAD, CFD, automation, and technical documentation assets.

The application shall recognize common engineering file types and help users avoid repository mistakes.

---

# Engineering Categories

## CAD Assets

Recognized file types:

* .CATPart
* .CATProduct
* .CATDrawing
* .CATProcess
* .stp
* .step
* .igs
* .iges
* .stl
* .x_t
* .x_b
* .sldprt
* .sldasm

Display Group Name:

CAD

---

## CFD Assets

Recognized file types:

* .cas
* .cas.h5
* .dat
* .dat.h5
* .msh
* .msh.h5
* .jou
* .trn
* .out
* .res
* .cgns
* .foam

Display Group Name:

CFD

---

## Documentation Assets

Recognized file types:

* .docx
* .pptx
* .xlsx
* .pdf
* .txt
* .md
* .csv

Display Group Name:

Documentation

---

## Scripts and Automation

Recognized file types:

* .py
* .m
* .CATScript
* .js
* .bat
* .ps1
* .sh
* .vbs

Display Group Name:

Scripts

---

## General Assets

Any file not matching predefined categories.

Display Group Name:

General

---

# Engineering File Protection Rules

## Large File Warning

Warn users before committing large files.

Default thresholds:

Warning:
50 MB

Strong Warning:
100 MB

Critical Warning:
250 MB

The user may continue after confirmation.

Thresholds shall be configurable.

---

## Git LFS Recommendations

Recommend Git LFS when:

* Large CAD assets are frequently updated.
* Binary files exceed warning thresholds.
* Teams collaborate on large engineering repositories.

Do not automatically configure Git LFS.

Provide guidance only.

---

# Generated File Detection

Warn users before committing files commonly considered generated outputs.

Examples:

CFD:

* solver outputs
* transient result dumps
* temporary reports
* exported animations

CAD:

* autosave files
* backup files
* temporary exports

Documentation:

* duplicate exports
* generated intermediate reports

Users may override warnings.

---

# Repository Hygiene Rules

Recommended to commit:

* Source CAD models
* Automation scripts
* Journal files
* Documentation source files
* Input configurations

Recommended to avoid committing:

* Temporary files
* Cache directories
* Solver-generated outputs
* Autosave backups
* Intermediate exports

---

# Branch Naming Standards

Recommended patterns:

CAD:
cad/<feature-name>

Examples:
cad/root-airfoil
cad/tip-airfoil
cad/wing-assembly

---

CFD:
cfd/<study-name>

Examples:
cfd/mesh-study
cfd/fluent-validation
cfd/turbulence-study

---

CATIA Automation:
catia/<feature-name>

Examples:
catia/csv-import
catia/macro-generator

---

Documentation:
docs/<topic>

Examples:
docs/final-report
docs/presentation

---

Scripts:
scripts/<purpose>

Examples:
scripts/mesh-parser
scripts/result-export

---

General Features:
feature/<name>

Examples:
feature/dashboard
feature/recovery-center

---

Bug Fixes:
bugfix/<issue>

Examples:
bugfix/index-lock
bugfix/auth-handler

---

# Commit Message Recommendations

Suggested formats:

CAD:
cad: update wing assembly geometry

CFD:
cfd: improve mesh quality

Documentation:
docs: revise final report

Scripts:
scripts: add export utility

Bug Fix:
fix: resolve authentication issue

General:
feat: implement dashboard enhancements

---

# Engineering Dashboard Indicators

The dashboard should display:

CAD Files Modified

CFD Files Modified

Documentation Files Modified

Script Files Modified

Large File Warnings

Generated File Warnings

Repository Health Score

---

# Engineering Warnings

Display warnings when:

* Large binary assets are selected.
* Solver outputs are selected.
* Autosave files are selected.
* Duplicate exports are detected.
* Generated files are selected.

Warnings shall explain:

What was detected.

Why it may be problematic.

Whether it is safe to continue.

---

# User Control Principles

The application shall:

* Warn users.
* Educate users.
* Recommend best practices.

The application shall not:

* Block commits automatically.
* Delete files automatically.
* Modify repositories without confirmation.

Final decisions remain with the user.

---

# Version 0.1 Scope

Include:

* File categorization.
* Large file detection.
* Generated file warnings.
* Branch naming recommendations.
* Commit message suggestions.
* Engineering dashboard indicators.

Future releases may expand engineering intelligence capabilities.
