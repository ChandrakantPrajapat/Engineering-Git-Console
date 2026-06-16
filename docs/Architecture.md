1. This document freezes the technical decisions.

i. Application Type: Terminal-based Engineering Git Console
ii. Primary Platform: Windows 10 , Windows 11
iii. Secondary Platforms: Linux, macOS
iv: Runtime: Node.js
v: UI Framework: Blessed

2. Application Identity: Official product name
Engineering-Git-Console

3. Screen List: screen that will exist.
Dashboard,
Branch Explorer,
File Explorer,
Commit Wizard,
Push Confirmation,
Recovery Center,
Offline Help,
Diagnostics,
Settings,
About

4. Navigation Rules
i. Mouse Features
ii. Keyboard Features
Example:
Arrow Keys → Navigate
Enter → Select
Space → Toggle
Esc → Back
Ctrl+C → Exit
F1 → Help
F5 → Refresh
/ → Search
Tab → Switch Panels

5. Define Data Storage Locations
Decide:
Where settings live.
Where logs live.
Where diagnostics live.
Where help articles live.
Where cached reports live.

Example categories:
Configuration
Logs
Diagnostics
Help
Exports

6. Decide Logging Philosophy
App should remember:
Operation history?
Recovery history?
Diagnostics generated?

Recommendation: With configurable retention.

7. Recovery Philosophy
Rules:
Allowed
Suggest repairs.
Guide repairs.
Offer one-click repairs.

Never Allowed
Force push automatically.
Delete branches automatically.
Remove files silently.
Resolve merge conflicts automatically.

These principles prevent future scope creep.

8. Help Philosophy
Help Center should answer:
What happened?
Why did it happen?
How do I fix it?
Can I automate the fix?
When should I seek support?

9. Aerospace Rules Freeze
Before coding, decide:
Which engineering files are:
Recommended
Version-controlled.
Warned
Large files.
Discouraged
Generated outputs.
Blocked
Extremely dangerous artifacts.

10. Deliverable

Do not attempt to build the entire Vision at once.
Version 0.1 must contain.

Recommended:

Version 0.1
Repository Dashboard
Branch Tree Explorer
Branch Search
Changed File Explorer
Commit Workflow
Push Workflow
Basic Diagnostics
Basic Recovery (index.lock, auth errors)
Settings
Desktop Launch Support

