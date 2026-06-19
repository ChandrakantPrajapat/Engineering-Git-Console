Recovery Philosophy (Freeze)
The system shall:

Explain First
Always answer:
What happened?
Why did it happen?
Is my work safe?
What should I do next?
before offering actions.

Safety Before Automation
The application may:
Guide repairs
Suggest repairs
Offer one-click repairs
Validate repairs
The application shall never:
Force push automatically
Delete branches automatically
Discard changes automatically
Resolve merge conflicts automatically
Modify credentials automatically

Risk Classification
Every issue must display:
Low Risk
Examples:
Stale index.lock
No internet
Missing upstream

Medium Risk
Examples:
Push rejected
Authentication expired
Detached HEAD

High Risk
Examples:
Merge conflicts
Interrupted rebase
Interrupted cherry-pick

Critical Risk
Examples:
Potential repository corruption
Missing objects
Failed repository integrity checks

Recovery Knowledge Base
Freeze the first issue set.

Repository Errors
Not a Git repository
Git not installed
Invalid Git executable

Lock Errors
index.lock present
HEAD.lock present
Config lock present

Authentication Errors
Invalid credentials
Expired credentials
Permission denied
Two-factor authentication failures

Push Errors
Remote ahead
Non-fast-forward rejection
Protected branch rejection
Remote unavailable

Branch Errors
Detached HEAD
Missing upstream
Unknown branch
Deleted tracking branch

Merge Errors
Merge conflicts
Interrupted merge
Failed rebase
Failed cherry-pick

File Errors
Large file rejection
Missing files
Permission denied
Read-only files

Repository Health Errors
Corrupted index
Failed integrity checks
Missing Git objects

Structure of Every Recovery Article
Every issue must follow this exact format:

Error Name
Example:
Index Lock Detected
Meaning
Plain-English explanation.
Typical Causes

Examples:
VS Code crashed
Computer shutdown unexpectedly
Git process interrupted
Is My Work Safe?

Answer explicitly:
Yes
Probably
Uncertain
Immediate action required

Risk Level
Low
Medium
High
Critical

Recommended Action
Step-by-step guidance.

One-Click Repair Available?
Yes
No

When to Seek Help
Define escalation points.
