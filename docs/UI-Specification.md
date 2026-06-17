Screen 1 — Splash / Startup
Purpose: Introduce the application and perform startup checks.
Checks:
Git installed
Inside a Git repository
Configuration readable
Help files available
Logs accessible

Possible outcomes:
Ready
Warning
Critical Failure

Screen 2 — Repository Dashboard
Purpose: Provide immediate project awareness.
Display:
Repository Name
Current Branch
Repository Health Score
Modified Files
Untracked Files
Ahead / Behind Status
Conflict Count
Last Operation Status
Last Commit Summary
Actions:
Open Branch Explorer
Open Recovery Center
Open Help
Open Settings
Refresh Dashboard
Exit

Screen 3 — Branch Explorer
Purpose: Navigate repository branches intelligently.
Features: Tree View
Examples:
cad/
cfd/
catia/
docs/
main
develop
Fuzzy Search

Search branches instantly.
Branch Metadata

Display:
Current status
Tracking branch
Last commit
Author
Last updated
Status Indicators
Examples:
Current
Clean
Ahead
Behind
Conflict
Detached
No Upstream

Actions:
Switch branch
View details
Search
Refresh
Back

Screen 4 — File Explorer
Purpose:
Manage changes safely.
Group files by category.
Suggested groups:
CAD
CFD
Documentation
Scripts
General

Display:
Modified
Untracked
Deleted
Renamed

Capabilities:
Select
Deselect
Search
View Metadata
Review Selection

Screen 5 — Commit Wizard
Purpose: Guide commit creation.
Display:
Selected files
Suggested commit message
Commit category
Custom message input
Validation:
Cannot be empty
Cannot be whitespace only
Confirmation:
Show summary before commit.

Screen 6 — Push Confirmation
Purpose: Perform pre-flight safety checks.
Checks:
Remote configured
Authentication valid
Internet available
No repository lock
Branch tracking exists
No major conflicts
Large file warnings

Display:
Push destination
Branch
Commits to push
Warnings
Require confirmation.

Screen 7 — Operation Progress
Purpose:Display execution status.
Used for:
Commit
Push
Repair
Diagnostics
Refresh
Display:
Current step
Success messages
Warnings
Failure messages

Screen 8 — Recovery Center
Purpose:Resolve issues.
Sections:
Recent Failures
Known Issues
Auto Repairs
Guided Repairs
Operation History

Example issues:
index.lock
Authentication Failure
Push Rejected
Detached HEAD
Merge Conflict

Each issue contains:
Meaning
Cause
Risk
Repair Options
Escalation Advice

Screen 9 — Diagnostics Viewer
Purpose:Generate support reports.
Display:
Repository State
Git Version
OS Information
Operation Details
Detected Errors
Suggested Solutions
Actions:
Export
Copy Summary
Open Support
Back
Screen 10 — Offline Help Center
Purpose:
Teach and assist.
Categories:
Getting Started
Git Basics
Branches
Commits
Pushes
Recovery Guides
Engineering Best Practices
FAQ
Glossary
Structure of every article:
What is it?
Why does it matter?
Common mistakes
How to fix problems
When to seek support

Screen 11 — Settings
Purpose:Personalization.
Configurable options:
Support URL
Theme
Diagnostics Retention
Large File Threshold
Branch Naming Templates
Help Verbosity
Confirmation Preferences
Actions:
Save
Restore Defaults
Back

Screen 12 — About
Purpose:Explain the application.
Display:
Application Name
Version
Purpose
Supported Platforms
License
Repository Link

Screen 13 — Exit Confirmation
Purpose:
Prevent accidental exits.
Ask:
Are you sure you want to exit?
Options:
Exit
Cancel
Global Keyboard Standards
Freeze these now.
Suggested:
Arrow Keys   → Navigate
Enter        → Select
Space        → Toggle Selection
Esc          → Go Back
Tab          → Switch Panels
/            → Search
F1           → Help
F5           → Refresh
Ctrl+C       → Exit Application

These shortcuts should work consistently everywhere.
Notification Standards
Define three levels:
Information
Normal updates.
Warning
Potential risks.
Critical
Immediate attention required.
Accessibility Standards
Define:
Color should not be the only indicator.
Status icons should accompany colors.
Text must remain understandable without color.
Keyboard-only operation must be fully supported.
