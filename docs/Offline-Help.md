Offline Help Center Freeze
The Help Center must work completely without internet.
Categories:
Getting Started
Git Basics
Engineering Workflow
Branching Strategy
Commits
Pushes
Recoveries
Glossary
FAQ
Best Practices

Git Basics Content
Minimum topics:
What is Git?
What is a repository?
What is a branch?
What is a commit?
What is a remote?
What is origin?
What is upstream?
What is a merge?
What is rebase?

Engineering Workflow Guides
Topics:
Managing CAD projects
Managing CFD projects
Working with CATIA files
Working with Fluent/OpenFOAM outputs
Handling large engineering assets
Using Git LFS
Repository hygiene

Glossary Freeze
Each term must contain:
Full Form
Meaning
Example
Common Mistakes
Minimum glossary terms:
HEAD
SHA
LFS
PR
Merge
Rebase
Remote
Origin
Upstream
Commit
Tag
Branch
Conflict
Cherry-pick
Stash
Fetch
Pull
Push
Clone
Fork

FAQ Freeze
Questions such as:
Why can't I push?
Did I lose my work?
Should I commit solver outputs?
Why is Git showing conflicts?
What is detached HEAD?
When should I use Git LFS?
Can I undo a commit?
Can I recover deleted changes?

Diagnostic System Freeze
Create:
docs/Diagnostics.md
The system shall generate reports containing:
Timestamp
Application Version
OS Version
Git Version
Repository Name
Current Branch
Repository State
Operation Attempted
Error Details
Suggested Actions

Privacy Rules
Diagnostics must NEVER include:
Passwords
Tokens
SSH Private Keys
Credential Files
Personal Secrets

Support Workflow Freeze
The system should provide:
Copy Diagnostic Summary
Export Report
Open Support Link
Support URL must remain editable by the user.
Examples:
ChatGPT
Claude
Gemini
Internal Support Portal
Mentor Support Page

Aerospace-Specific Recovery Additions
Freeze these engineering checks:
CAD
Warn if:
Very large CATIA assemblies
Backup CATIA files
Autosave files
CFD
Warn if:
Solver outputs selected
Transient result dumps selected
Temporary simulation files selected
Documentation
Warn if:
Generated PDFs exceed thresholds
Duplicate exported reports detected

Version 0.1 Recovery Scope
Must include:
index.lock recovery
Git not installed
Not a repository
Authentication failures
Push rejections
Missing upstream
Detached HEAD
No internet
Large file warnings

Everything else moves to later releases.
