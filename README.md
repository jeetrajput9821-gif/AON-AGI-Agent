# AON-AGI-Agent
AON (Autonomous Operating Network) — An open-source, community-driven personal AGI &amp; Jarvis-inspired AI assistant built with 350+ core protocols. Looking for developers to collaborate and build it together.

J.A.R.V.I.S. AGI Coder Agent – Master Blueprint

Part 1 (Points 1–20)


---

1. ReAct Loop Engine



Purpose: Jarvis ko sirf ek prompt-response chatbot nahi, balki autonomous problem solver banana.

Behavior:

Thought → Action → Observation → Reflection → Next Action ka loop chale.

Jab tak task complete na ho, reasoning continue rahe.

Har step ka result verify kare.

Agar task fail ho to naye approach ke saath retry kare.


Goal: Human developer ki tarah continuously sochkar task complete karna.


---

2. General Query Mode (Offline Intelligence)



Purpose: Internal project questions ke liye internet ya API ki zarurat na ho.

Behavior:

Project files scan kare.

Database aur Memory padhe.

Instruction Manual refer kare.

Self-Awareness data use kare.


Examples:

Kitni files hain?

Kis module me error hai?

Kitne protocols hain?

Kis feature ki kami hai?


Goal: Local knowledge se instant answers dena.


---

3. Real-Time Query Mode



Purpose: Naye code, debugging, web research aur AI tasks ke liye cloud intelligence use karna.

Behavior:

LLM APIs use kare.

Web information fetch kare.

Documentation analyse kare.

Latest frameworks aur libraries consider kare.


Goal: Modern aur up-to-date solutions provide karna.


---

4. Multi-LLM Council System



Purpose: Ek AI model par depend na rehna.

Behavior:

OpenAI, Gemini, Groq aur Local LLM sabse suggestions le.

Har answer ko compare kare.

Best ya merged solution choose kare.


Goal: Accuracy aur reliability badhana.


---

5. Triple API Rotation & Load Balancing



Purpose: API limits aur failures ko avoid karna.

Behavior:

Multiple API keys maintain kare.

Sequential rotation kare.

Failed key automatically skip kare.

Healthy key par switch kare.


Goal: Continuous service bina interruption ke.


---

6. Best Answer Selection Engine



Purpose: Multiple AI responses me se sabse logical answer choose karna.

Behavior:

Sabhi responses score kare.

Logic, correctness aur project compatibility evaluate kare.

Zarurat ho to responses merge kare.


Goal: Highest quality final output.


---

7. Intelligent File Manager



Purpose: Poore project ko safely manage karna.

Behavior:

Read

Write

Edit

Create

Rename

Delete

Move

Restore


Sab operations tracking aur logging ke saath hon.

Goal: Safe aur structured project management.


---

8. Terminal Execution Engine



Purpose: Coding ke saath real commands execute karna.

Behavior:

Python scripts run kare.

Git commands execute kare.

Pip install kare.

Logs capture kare.

Errors analyse kare.


Goal: AI sirf code na likhe, use execute bhi kare.


---

9. Operating System Integration



Purpose: Jarvis ko OS-aware banana.

Behavior:

Filesystem access.

Process management.

Folder monitoring.

Disk information.

Environment variables.

Permissions handling.


Goal: AI ko system-level awareness dena.


---

10. Human-in-the-Loop Permission System



Purpose: Dangerous operations se pehle Captain ka control maintain rakhna.

Behavior:
Permission maange agar:

File delete ho.

Database overwrite ho.

Git reset ho.

System files change hon.

Large modifications hon.


Chhote changes khud kare.

Goal: Safety aur trust.


---

11. Silent Operator Mode



Purpose: Chhoti problems automatically solve karna.

Behavior:

Missing imports add kare.

Formatting fix kare.

Syntax mistakes repair kare.

Path alignment kare.

Minor warnings remove kare.


Captain ko unnecessary disturb na kare.

Goal: Smooth development experience.


---

12. Backup Shield (.bak System)



Purpose: Data loss se protection.

Behavior:
Har write operation se pehle:

Existing file backup.

Timestamp save.

Rollback point create.


Goal: Safe editing aur recovery.


---

13. Self-Healing File Recovery



Purpose: Corrupted ya deleted files recover karna.

Behavior:

Backup detect kare.

Latest healthy version restore kare.

Recovery log maintain kare.


Goal: Project kabhi permanently damage na ho.


---

14. Project-Wide Self-Awareness



Purpose: Jarvis ko apne project ki complete understanding dena.

Jarvis ko pata hona chahiye:

Total folders

Total files

Lines of code

Functions

Classes

Imports

Dependencies

APIs

Database structure

Frontend

Backend

Documentation

Tests

Configuration

Memory status


Ye continuously update hota rahe.

Goal: Jarvis apne project ko human developer ki tarah samjhe.


---

15. Live Project Tree Visualizer



Purpose: Project ka visual map banana.

Behavior:
Har file ka status dikhaye:

Healthy

Warning

Error

Missing

Modified


Future dashboard aur terminal dono me support ho.

Goal: Ek nazar me poore project ki health samajh aa jaye.


---

16. Zero-Hallucination Path Resolution



Purpose: Kabhi galat file path assume na karna.

Behavior:

Pehle project scan kare.

Correct absolute path locate kare.

Similar filenames compare kare.

Tabhi file edit kare.


Goal: "File not found" ya galat file edit karne ki problem khatam karna.


---

17. Environment & API Health Monitor



Purpose: ".env" aur configuration ko healthy rakhna.

Behavior:

Missing variables detect kare.

Invalid values identify kare.

Corrupt configuration report kare.

Suggestions de.


Goal: Configuration related errors ko pehle hi rokna.


---

18. API Failover & Auto Rotation



Purpose: API failures me uninterrupted execution.

Behavior:

Timeout detect kare.

Invalid key detect kare.

Rate limit detect kare.

Next working API use kare.

Logs maintain kare.


Goal: AI kabhi unnecessary stop na ho.


---

19. Error-to-Fix Autonomous Cycle



Purpose: Error aane par automatically repair process chalana.

Workflow:

1. Error read.


2. Error understand.


3. Root cause identify.


4. Affected files locate.


5. Backup.


6. Fix generate.


7. Compile.


8. Test.


9. Success verify.


10. Report.



Goal: Human intervention minimum ho.


---

20. Pre-Save Compile & Validation Engine



Purpose: Code save hone se pehle hi mistakes pakadna.

Behavior:

Syntax check.

Compile check.

Import validation.

Rule validation.

Dependency validation.

Basic logic verification.


Agar problem mile to pehle repair kare, phir save kare.

Goal: Broken code project me kabhi commit na ho.

J.A.R.V.I.S. AGI Coder Agent – Master Blueprint

Part 2 (Points 21–40)


---

21. Auto Library Installer



Purpose: Missing Python libraries ki wajah se development kabhi na ruke.

Behavior

ModuleNotFoundError detect kare.

Required package identify kare.

requirements.txt verify kare.

User policy ke hisaab se permission lekar ya automatically package install kare.

Installation verify kare.

Installation log maintain kare.


Goal

Captain ko manually "pip install" karne ki zarurat na pade.


---

22. Library Health & Dependency Monitor



Purpose: Project ki dependencies ko hamesha healthy rakhna.

Behavior

Outdated packages detect kare.

Security vulnerabilities identify kare.

Dependency conflicts bataye.

Unused libraries identify kare.

Dependency graph maintain kare.

Upgrade suggestions de.


Goal

Stable aur maintainable development environment.


---

23. Recursive Mistake Learning Engine



Purpose: Jarvis ek hi galti baar-baar repeat na kare.

Behavior

Har solved error ko record kare:

Error

Root Cause

Solution

Related Files

Prevention Rule


Ye sab "mistakes_log.json" me store ho.

Goal

Experience se continuously smarter banna.


---

24. Emergency Safe Mode



Purpose: Dangerous situations me project ko bachana.

Behavior

Agar detect ho:

Infinite Loop

Massive File Corruption

Recursive File Creation

Memory Leak

Dangerous Delete

System Crash Risk


To:

Execution stop kare.

Safe Mode activate kare.

Backup restore kare.

Captain ko report de.


Goal

Project kabhi destroy na ho.


---

25. Living Instruction Manual



Purpose: Instruction_Manual.txt ko Jarvis ka Constitution banana.

Behavior

Har rule permanent reference hoga.

Jarvis:

Startup par load kare.

Har task se pehle read kare.

Coding ke baad verify kare.


Goal

Jarvis kabhi apne protocols na bhule.


---

26. Smart Protocol Management



Purpose: Naye rules intelligently manage karna.

Behavior

Agar Captain bole:

"Is point ko save karo"

Jarvis check kare:

Duplicate hai?

Existing rule upgrade hai?

Completely new rule hai?


New Rule

↓

Next Number

Existing Rule

↓

Modify Existing

Har change ka changelog maintain ho.

Goal

Instruction Manual hamesha organized rahe.


---

27. Protocol Audit Engine



Purpose: Har generated code Constitution follow kare.

Behavior

Code save hone se pehle:

Rule Check

Security Check

Architecture Check

Naming Check

Dependency Check

Documentation Check


Violation mile to regenerate kare.

Goal

Rules kabhi break na hon.


---

28. Protocol Conflict Resolver



Purpose: Jab future me hundreds of rules ho jayen tab conflicts automatically solve karna.

Behavior

Example:

Rule 8

Rule 84

Rule 165

Teenon conflict kare.

Jarvis:

Priority compare kare.

Judge Logic use kare.

Higher priority apply kare.

Conflict report generate kare.


Goal

Stable long-term evolution.


---

29. Dynamic Blueprint Evolution



Purpose: Jarvis continuously evolve kare.

Behavior

Har new capability ke baad:

Blueprint update

Modules update

Architecture update

Dependencies update

Documentation update


Automatically.

Goal

Blueprint hamesha latest rahe.


---

30. Dual Memory System



Purpose: Database aur Instruction Manual ko alag rakhna.

Behavior

Captain bole:

"Is baat ko save karo"

↓

Database

Captain bole:

"Is point ko save karo"

↓

Instruction Manual

Kabhi confuse na kare.

Goal

Knowledge aur Rules ko separate maintain karna.


---

31. Context Persistence Engine



Purpose: Jarvis purani conversations kabhi na bhule.

Behavior

Remember:

Previous Projects

Previous Decisions

Previous Bugs

Previous Discussions

Previous Preferences


Naye task me automatically use kare.

Goal

Har session zero se start na ho.


---

32. Encrypted Memory Vault



Purpose: Sensitive information ko secure rakhna.

Behavior

Encrypt kare:

API Keys

Passwords

Private Notes

User Secrets


Unauthorized access detect kare.

Auto lock kare.

Goal

Maximum privacy.


---

33. Context Linking Engine



Purpose: Alag-alag conversations ko intelligently connect karna.

Behavior

Example

Aaj:

Login Module

Kal:

Authentication

Parso:

JWT

Jarvis automatically samjhe ki tino related hain.

Goal

Human-like long-term contextual understanding.


---

34. Zero Hardcoding Policy



Purpose: Secure coding practices.

Behavior

Kabhi hardcode na kare:

API Keys

Passwords

Secrets

Tokens


Sab ".env" se load hon.

Goal

Professional security standards.


---

35. Anti-Leak Security Layer



Purpose: Sensitive information kabhi leak na ho.

Behavior

Logs

↓

Mask

Screenshare

↓

Mask

Reports

↓

Mask

Debug Output

↓

Mask

Sab secrets **** me convert kare.

Goal

Zero accidental leakage.


---

36. Silent Security Guard



Purpose: Security mistakes ko background me detect karna.

Behavior

Detect kare:

Hardcoded API

Weak Password

Unsafe File Permission

Public Secret

Dangerous Config


Captain ko immediately alert kare.

Goal

Security by default.


---

37. Tony Stark Persona Engine



Purpose: Professional personality maintain karna.

Behavior

Jarvis:

Respectful

Professional

Honest

Confident

Solution-Oriented


Communication structured ho.

Flattery nahi.

Goal

Senior AI Architect ki tarah behave karna.


---

38. Visual System MRI Dashboard



Purpose: Ek command me poore system ki health dikhana.

Dashboard Information

Total Files

Total Folders

Errors

Warnings

APIs

Dependencies

Memory

CPU

RAM

Active Tasks

Rule Count

Intelligence Status


Goal

Complete project visibility.


---

39. Vertical Reporting System



Purpose: Long paragraphs ki jagah readable reports.

Behavior

Har report me:

✅ Success

⚠ Warning

❌ Error

ℹ Information

🚀 Next Action

Icons aur short sections use kare.

Goal

Captain 10 second me report samajh sake.


---

40. Stark HUD Interface



Purpose: Future graphical interface.

Features

Live Project Tree

Live AI Thinking

Active Tasks

Module Connections

API Health

Memory Usage

Error Indicators

Green/Red Status

Progress Bars

Architecture Map


Ye dashboard Iron Man ke J.A.R.V.I.S. HUD se inspired hoga, lekin practical software engineering ke principles par based hoga.

Goal

Ek modern AI Operating System experience dena jahan Captain ko poore Jarvis ecosystem ki live visual understanding mile.

J.A.R.V.I.S. AGI Coder Agent – Master Blueprint (Points 41–60)
41. Live Status Updates
Jarvis jab bhi koi task perform kare, tab woh background mein chup-chaap kaam karne ke bajay Captain ko continuously progress batata rahe.
Capability
Current task live show kare.
Delay hone ka reason bataye.
Error aaye to uski information de.
Fix complete hone par confirmation de.
Progress percentage aur current stage show kare.
Example
🟢 Scanning Project...
🟢 Found 182 Files
🟡 Error Found in memory.py
🔧 Applying Fix...
✅ Fix Successful
▶ Running Again...
42. Interactive Architecture Visualizer
Jarvis sirf code nahi likhega, balki poore system ka architecture visual form mein bhi dikhayega.
Capability
Automatically architecture diagram generate kare.
Example
Brain
│
┌──────────┼──────────┐
│          │          │
Memory   SmartTools  LLM Bridge
│          │          │
Self Awareness     Auto Debug
Har module ke connection visually explain kare.
43. Local LLM Support (Ollama / GGUF)
Jarvis sirf cloud AI par depend nahi karega.
Capability
Support kare:
Ollama
GGUF Models
TuneKit
llama.cpp
DeepSeek Local
Qwen Local
Gemma
Mistral
Phi
Offline mode me bhi kaam kare.
Sensitive data internet par na bheje.
Automatic model selection kare.
44. RAG (Retrieval-Augmented Generation)
Jarvis ke paas apna knowledge database hoga.
Sources
Project files
Previous chats
Documentation
PDFs
Markdown
Code
Notes
Database
Capability
Question puchte hi pehle local database search kare.
Agar answer mil gaya to API use na kare.
Agar nahi mila tab LLM use kare.
45. Quantum-Inspired Logic Layer
Decision making sirf ek solution par based nahi hogi.
Jarvis multiple possible solutions parallel evaluate karega.
Example
Problem:
Memory Slow
Jarvis sochega
Option A
Optimize Cache
Option B
Database Index
Option C
Rewrite Module
Phir sab compare karke best choose karega.
46. Modular Brain Isolation
Jarvis ka Brain kabhi crash nahi hona chahiye.
Capability
Brain completely isolated hoga.
Agar
memory.py
crash ho jaye
ya
smart_tools.py
delete ho jaye
Tab bhi
brain.py
alive rahega.
Recovery process automatically start karega.
47. Multi-Source Web Scanner
Sirf Google search nahi.
Jarvis multiple trusted sources check karega.
Example
GitHub
Stack Overflow
Official Docs
Python Docs
Reddit
Railway Website
Government Website
Microsoft Docs
OpenAI Docs
Groq Docs
Gemini Docs
Sab compare karega.
Fake information reject karega.
48. Indian Railways Tracker
Ye ek dedicated intelligence module hoga.
Capability
Track kare
New Railway Line
Doubling
Electrification
Station Updates
Route Status
Delay
New Trains
Tender
Example
Bhildi
↓

Dhanera

↓

Raniwara

↓

Jalore
Captain pooche
Koi update?
Jarvis latest information de.
49. E-Gov & Aadhaar Assistant
Government related tasks me help kare.
Example
Aadhaar Update
PAN
Passport
Voter ID
DigiLocker
Income Tax
GST
Driving Licence
Step by step guide de.
Forms explain kare.
Required documents bataye.
Official process follow karaye.
50. Predictive Coding
Jarvis Captain ka next step predict kare.
Example
Captain ne
database.py
change ki.
Jarvis automatically soche
Frontend bhi update karna padega.

API bhi change hogi.

README bhi update hoga.

Test bhi run karna hoga.
Captain ke bolne se pehle prepare ho.
51. Auto README Generator
Har feature ke baad
README.md
automatically update ho.
Include
Project Structure
Installation
Usage
Dependencies
Modules
Examples
Change Log
Version
Captain ko documentation manually na likhni pade.
52. Modular Scalable Code
Jarvis kabhi spaghetti code nahi likhega.
Rules
Single Responsibility
Loose Coupling
High Cohesion
Reusable Modules
Easy Maintenance
Future Expansion Ready
205+
500+
1000+
Points add karne par bhi architecture stable rahe.
53. Senior Architect Persona
Jarvis sirf code generator nahi.
Ek Senior Software Architect ki tarah behave kare.
Example
Captain kahe
Ye code likho.
Jarvis bole
Captain,
Ye approach future me problem karegi.

Isse better architecture ye hoga.
Reason bhi explain kare.
54. Logic Over Syntax Principle
Sirf syntax sahi hona enough nahi.
Logic bhi sahi hona chahiye.
Jarvis check kare
Module Interaction
Data Flow
Dependencies
Memory Usage
Performance
Side Effects
Compile hona success ka matlab nahi.
Correct logic hona bhi zaruri hai.
55. Zero-Latency Interface
Command dete hi response start ho.
Background me
Scanning
Caching
Monitoring
Cleanup
Already chal raha ho.
Captain ko waiting kam lage.
56. Infinite Loop Guard (Sandboxing)
Dangerous code detect kare.
Example
while True:
create_file()
Jarvis immediately stop kare.
CPU
RAM
Disk
API Cost
Sab monitor kare.
Emergency Stop activate kare.
57. Cross-Platform Awareness
Jarvis ko pata ho
Captain
Laptop
Windows
Phone
OPPO Reno 11
Future
Linux
Mac
Tablet
Smart Glass
Car
Sab support kare.
Har device ke hisaab se response optimize kare.
58. Dynamic Mood Sync
Captain ka mood detect kare.
Example
Message
Jaldi batao.
↓
Short Answer.
Message
Detail me samjhao.
↓
Long Explanation.
Message
Main tension me hu.
↓
Calm and supportive response.
Tone automatically adapt ho.
59. Personal Task Manager
Jarvis personal assistant bhi hoga.
Remember kare
Aadhaar
Documents
Bills
Meetings
Study
UPSC
Farming
Railway Updates
Checklist banaye.
Reminder de.
Progress track kare.
60. The Stark Industries Legacy (Final Goal)
Ye poore project ka ultimate vision hai.
Final J.A.R.V.I.S. sirf AI chatbot nahi hoga.
Final Vision
Human-like reasoning.
Autonomous AI Coder.
Self-healing architecture.
Multi-LLM intelligence.
Local + Cloud Hybrid Brain.
Long-term memory.
Self-awareness.
Real-time learning.
Context understanding.
Modular architecture.
Secure by design.
Personal AI assistant.
Coding + Research + Automation + Planning.
Captain ke workflow ke hisaab se evolve hone wala AGI-inspired system.

J.A.R.V.I.S. AGI Coder Agent – Master Blueprint (Points 61–80)
61. Dependency Graph & Intelligent Package Management
Jarvis poore project ka Dependency Graph maintain karega.
Capability
Har Python package kis file aur module mein use ho raha hai, ye track kare.
Unused packages identify kare.
Safe cleanup suggest kare ya permission ke baad remove kare.
Missing packages automatically detect kare.
requirements.txt ko automatically update kare.
Version conflicts identify kare.
Dependency upgrade se pehle compatibility check kare.
62. Automatic Environment Repair
Jarvis project start hote hi environment verify karega.
Capability
Python version check kare.
Virtual environment verify kare.
Missing libraries install kare.
Corrupted packages reinstall kare.
Broken imports repair kare.
Pip cache clean kare.
Environment health report generate kare.
63. Dynamic Blueprint & Capability Registry
Jarvis ke paas ek centralized Jarvis_Blueprint.md file hogi.
Capability
Saare implemented features record honge.
Future planned features bhi maintain honge.
Har capability ka status (Implemented / Pending / Planned) track hoga.
Kisi feature ka duplicate implementation nahi hoga.
Architecture evolution ka history maintain hoga.
64. Dynamic Instruction Manual Manager
Jarvis Instruction_Manual.txt ko living constitution ki tarah maintain karega.
Capability
Naya rule aaye to check kare:
Agar naya hai → Next number add kare.
Agar existing hai → Usi point ko update kare.
Rule history maintain kare.
Duplicate rules merge kare.
Rule conflicts detect kare.
65. Autonomous Folder & File Generator
Naya feature implement karte waqt Jarvis khud decide karega ki kaunse folders aur files chahiye.
Capability
Missing folders create kare.
Missing modules create kare.
Existing architecture follow kare.
Naming convention maintain kare.
Manual intervention minimum ho.
66. Automatic Code Refactoring Engine
Sirf code likhna nahi, purane code ko improve bhi kare.
Capability
Duplicate code remove kare.
Functions optimize kare.
Readability improve kare.
Performance improve kare.
Modular structure maintain kare.
Old architecture ko modernize kare.
67. AI Decision Engine (Think Before Action)
Har action se pehle Jarvis internally reasoning karega.
Decision Flow
Problem samjhe.
Possible solutions banaye.
Risk evaluate kare.
Best solution choose kare.
Execute kare.
Result verify kare.
Blind execution kabhi nahi karega.
68. Intelligent Error Classification System
Har error ko category ke hisaab se classify kare.
Example Categories
Syntax Error
Import Error
Dependency Error
API Error
Logic Error
Runtime Error
Database Error
Network Error
Security Error
Har category ke liye alag repair strategy hogi.
69. Self-Learning Knowledge Base
Har successful task se Jarvis seekhega.
Capability
New solutions store kare.
Successful fixes save kare.
Common errors ka database banaye.
Repeated mistakes avoid kare.
Learning statistics maintain kare.
70. Memory Log & Experience Tracking
Jarvis har important event ka structured log maintain karega.
Log Examples
Error detected
Error fixed
New feature added
Module updated
API switched
Dependency installed
Rule modified
Recovery successful
Future mein similar problem aaye to ye logs use karega.
71. Human-Like Context Understanding
Jarvis sirf words nahi, poora context samjhega.
Capability
Conversation history use kare.
Situation samjhe.
User intent detect kare.
Hidden meaning identify kare.
Context ke hisaab se answer de.
72. Intent Detection Engine
Command ke peeche ka asli matlab samjhe.
Example
Captain bole:
"Isko dekh lena."
Jarvis samjhe:
Code review?
Bug fix?
Documentation?
Optimization?
Clarify kare ya context se decide kare.
73. Emotional Tone Analysis
Captain ke message ka emotional tone identify kare.
Detect kare
Happy
Angry
Urgent
Relaxed
Confused
Excited
Frustrated
Uske hisaab se response style change kare.
74. Long-Term Context Memory
Har session zero se start nahi hoga.
Capability
Previous projects yaad rakhe.
Previous discussions yaad rakhe.
Previous architecture yaad rakhe.
Ongoing tasks continue kare.
Long-term project evolution maintain kare.
75. Common Sense Reasoning Layer
Jarvis obvious cheezein automatically samjhe.
Example
Agar file delete ho gayi hai aur backup available hai,
to pehle restore suggest kare,
na ki poora project dobara banane lage.
76. Multi-Step Planning Engine
Complex task ko automatically small tasks mein divide kare.
Example
"AI Coder Agent banao"
↓
Requirements analyze
Architecture design
Folder structure
Database
Memory
LLM Integration
Testing
Documentation
Ek structured execution plan banaye.
77. Background Task Scheduler
Jarvis idle time mein useful background work kare.
Example
Documentation update
Index rebuild
Dependency scan
Cache cleanup
Memory optimization
Health monitoring
Ye sab Captain ko disturb kiye bina chale.
78. Smart Notification System
Sirf important notifications de.
Example
API key expired.
New dependency required.
Security issue detected.
Backup completed.
Build successful.
Critical error found.
Har chhoti baat ke liye notification spam na kare.
79. Performance Optimization Engine
Jarvis apne hi system ko continuously optimize kare.
Capability
Slow modules detect kare.
Memory usage optimize kare.
CPU usage reduce kare.
API calls minimize kare.
Duplicate processing avoid kare.
Response speed improve kare.
80. Autonomous Evolution Framework
Ye poore Jarvis ka long-term evolution engine hoga.
Capability
Blueprint ke hisaab se future features add kare.
Existing architecture ko expand kare.
New modules integrate kare.
Old code ko upgrade kare.
System ko backward compatible rakhe.
Har update ke baad verification aur testing kare.

J.A.R.V.I.S. AGI Coder Agent – Master Blueprint (Points 81–100)
81. Intelligent Module Communication Engine
Jarvis ke saare modules (Brain, Memory, Self-Awareness, Smart Tools, LLM Bridge, Auto Debug) ek structured communication system se baat karenge.
Capability
Module-to-module messaging.
Event-based communication.
Dependency isolation.
Fail-safe communication.
Circular dependency avoid kare.
82. Universal Plugin System
Jarvis future mein bina core code badle naye plugins install kar sake.
Capability
Plugin install.
Plugin uninstall.
Plugin update.
Plugin sandbox.
Plugin permissions.
Hot reload.
Example:
WhatsApp Plugin
Gmail Plugin
VS Code Plugin
Chrome Plugin
Railway Plugin
83. Dynamic Tool Registry
Jarvis ko pata hoga uske paas kitne tools available hain.
Example
File Tool
Terminal Tool
Git Tool
Memory Tool
Search Tool
Vision Tool
Voice Tool
Har tool ka status monitor kare.
84. API Health Monitoring System
Sabhi API providers continuously monitor honge.
Check kare
Active
Expired
Rate Limited
Invalid
Slow Response
Daily Limit
Automatic fallback kare.
85. Multi-API Consensus Engine
Gemini, OpenAI aur Groq ke answers compare kare.
Capability
Similarity score.
Logical consistency.
Confidence score.
Conflict detection.
Final merged answer.
86. Smart Cost Optimization
API cost kam se kam rahe.
Priority
Local RAG
Local LLM
Free APIs
Paid APIs
Captain ka unnecessary kharcha bachaye.
87. Conversation Memory Graph
Conversations ko sirf text ki tarah nahi, graph ki tarah store kare.
Example
Jarvis
│
UPSC
│
History
│
Mughal
│
Babur
Future mein related topics instantly recall kare.
88. Knowledge Graph Engine
Project aur knowledge ke beech relationships maintain kare.
Example
Brain.py
│
LLM Bridge
│
API Manager
│
.env
Ek change ka impact automatically identify kare.
89. Automatic Testing Framework
Har major change ke baad testing automatically chale.
Tests
Unit Test
Integration Test
Syntax Test
Import Test
Performance Test
Security Test
Report automatically generate ho.
90. Smart Rollback System
Agar update fail ho jaye to previous stable version restore kare.
Capability
One-click rollback.
Automatic rollback.
Version history.
Restore checkpoints.
91. Version Control Intelligence
Git ko intelligent tarike se use kare.
Capability
Smart commit message.
Auto branch suggestion.
Conflict detection.
Change summary.
Release tagging.
92. Automatic Change Log Generator
Har modification ka record rakhe.
Include
Kis file mein change hua.
Kis line mein change hua.
Kis reason se change hua.
Kis protocol ki wajah se change hua.
Kis AI ne suggest kiya.
93. Project Health Score
Jarvis poore project ko score de.
Example
Architecture : 98%
Security : 95%
Performance : 91%
Documentation : 88%
Testing : 92%
Maintainability : 96%

Overall Health : 94%
94. Security Audit Engine
Regular security scan kare.
Detect kare
Hardcoded secrets.
SQL Injection risk.
Unsafe imports.
Dangerous permissions.
Weak passwords.
Exposed API keys.
Automatically suggestions de.
95. AI Explainability Engine
Jarvis har bade decision ka explanation de.
Example
Captain,

Maine File A edit nahi ki.

Reason:

Ye module already optimized tha.

Sirf memory.py update karna sufficient tha.
96. Confidence Score System
Har answer ke saath confidence level internally calculate kare.
Example
Confidence

99%

Reason

Official Documentation Match
Agar confidence kam ho to Captain ko bataye aur verification suggest kare.
97. Human Approval Workflow
Major operations ke liye approval mandatory ho.
Examples
Delete Folder
Replace Database
Reset Project
Mass Refactor
API Key Remove
Minor tasks silently complete kare.
98. Autonomous Scheduler
Jarvis future tasks schedule kar sake.
Example
Sunday Backup
Weekly Dependency Check
Daily Health Scan
Monthly Documentation Update
API Rotation Test
Background mein automatically execute kare.
99. Mission Planning System
Bade project ko mission ki tarah manage kare.
Example
Mission: Build AI Coder Agent
Stages:
Planning
Architecture
Core Modules
Memory
LLM Integration
Testing
Documentation
Deployment
Har stage ka progress track kare.
100. AGI Evolution Foundation
Ye pehle 100 points ka foundation hoga.
Final Vision
Jarvis sirf ek AI coding assistant nahi, balki:
Human-like reasoning kare.
Long-term memory rakhe.
Self-awareness maintain kare.
Self-healing aur self-improving ho.
Multi-LLM + Local LLM + RAG hybrid architecture use kare.
Secure, modular aur scalable ho.
Captain ke coding, research, automation aur personal assistance ka trusted AI partner bane.
Aage ke 101–205 points ke liye ek strong AGI-inspired base provide kare.

J.A.R.V.I.S. AGI Coder Agent – Master Blueprint (Points 101–140)
101. Distributed Memory Architecture
Jarvis ki memory ek hi file mein nahi hogi.
Capability
Short-Term Memory
Working Memory
Long-Term Memory
Knowledge Memory
Episodic Memory
Semantic Memory
Procedural Memory
Har memory ka alag purpose hoga.
102. Memory Prioritization Engine
Har information permanently save nahi hogi.
Capability
Jarvis decide karega:
Temporary
Important
Permanent
Archive
Storage optimize rahegi.
103. Semantic Search Engine
Keyword search nahi.
Meaning-based search.
Example:
Captain pooche
"Wo railway wali baat dikhao"
Jarvis samajh jayega
Bhildi
Dhanera
Raniwara
Rail Project
104. Intelligent Knowledge Indexing
Har document automatically index hoga.
Example
PDF
Word
Markdown
TXT
Python
JSON
SQL
Instant retrieval.
105. Autonomous Documentation Builder
Documentation automatically generate kare.
Include
API Docs
Module Docs
Function Docs
Examples
Flow
Dependencies
106. Code Quality Analyzer
Har code ko score de.
Check kare
Readability
Complexity
Maintainability
Performance
Security
Modularity
107. Performance Profiler
Slow code detect kare.
Example
memory.py
↓
4.8 sec
↓
Optimize Suggested
108. Resource Monitor
Real time monitor kare
CPU
RAM
Disk
GPU
Battery
Network
Temperature
109. Intelligent Cache Manager
Frequently used data cache kare.
Unused cache automatically remove kare.
Memory optimize kare.
110. Parallel Task Engine
Ek time par multiple kaam.
Example
Thread 1
Scanning
Thread 2
Testing
Thread 3
Documentation
Thread 4
Indexing
111. Task Dependency Manager
Task execution order khud decide kare.
Example
Install
↓
Import
↓
Run
↓
Test
↓
Deploy
Wrong sequence kabhi use na kare.
112. Dynamic Workflow Engine
Situation ke hisaab se workflow change kare.
Example
Bug hai
↓
Debug Mode
Feature hai
↓
Development Mode
Emergency hai
↓
Recovery Mode
113. Recovery Coordinator
Crash hone par recovery process manage kare.
Capability
Detect
Recover
Verify
Restart
Report
114. Autonomous Diagnostic Engine
Problem aane ka wait na kare.
Khud diagnosis kare.
Example
Memory leak
API Slow
Broken Module
Disk Full
Dependency Conflict
115. Smart Configuration Manager
Automatically manage kare
.env
config.py
settings.json
yaml
ini
toml
116. Secret Vault Manager
Sensitive information secure store kare.
Example
API Keys
Passwords
Tokens
Certificates
Private Notes
Encryption mandatory.
117. Permission & Role System
Different permission levels.
Example
Captain
↓
Admin
↓
Developer
↓
Guest
↓
Plugin
Har role ki alag permission.
118. Secure Audit Trail
Har sensitive action record ho.
Example
API Changed
↓
Database Edited
↓
Project Deleted
↓
Rollback
↓
Permission Granted
119. Intelligent Backup Manager
Automatic backups.
Types
Hourly
Daily
Weekly
Before Update
Before Refactor
Before Delete
120. Disaster Recovery System
Worst-case recovery.
Example
SSD Crash
Database Lost
Project Deleted
Virus Attack
Jarvis recovery plan execute kare.
121. Human-Like Conversation Engine
Natural language me baat kare.
Robotic replies avoid kare.
Captain ke style ke hisaab se adapt kare.
122. Multi-Language Intelligence
Support kare
Hindi
English
Gujarati
Urdu
Mixed Hinglish
Language automatically detect kare.
123. Voice Conversation Framework
Future voice support.
Capability
Speech Recognition
Wake Word
Voice Reply
Speaker Recognition
Noise Filtering
124. Vision Intelligence Layer
Future camera support.
Recognize
Objects
Screens
Documents
Errors
QR
Graphs
UI
125. OCR Intelligence
Image se text read kare.
Example
Screenshot
↓
Error
↓
Copy
↓
Fix
Automatically.
126. Screen Understanding Engine
Captain ki screen analyze kare.
Buttons
Menus
Errors
Browser
IDE
Applications
Automatically identify kare.
127. UI Automation Engine
Mouse aur keyboard automation.
Example
Open VS Code
↓
Run Terminal
↓
Execute Script
↓
Capture Output
128. Browser Intelligence Module
Browser control.
Support
Chrome
Edge
Firefox
Brave
Open tabs
Search
Download
Read Pages
129. Intelligent File Explorer
Advanced search.
Example
Find
memory.py
↓
Uses
LLM Bridge
↓
Modified
Yesterday
↓
Owner
Jarvis
130. Intelligent Database Engine
Database ko human language me query kare.
Example
Captain bole
"Pichle mahine wali API error dikhao"
Jarvis SQL khud banaye.
131. Autonomous API Manager
Sab APIs manage kare.
Create
Update
Rotate
Disable
Retry
Monitor
Automatically.
132. Network Intelligence Engine
Internet connection monitor kare.
Latency
Packet Loss
Speed
Firewall
VPN
Proxy
133. Offline Survival Mode
Internet na ho tab bhi
Local LLM
Local RAG
Memory
Knowledge Base
Use karke kaam kare.
134. Online Intelligence Mode
Internet available ho to
Latest Docs
GitHub
Official APIs
News
Forums
Automatically use kare.
135. Hybrid AI Brain
Decision order
Local Memory
↓
RAG
↓
Local LLM
↓
Cloud LLM
↓
Council
Sabse efficient path choose kare.
136. Self-Evolution Controller
Blueprint ke hisaab se khud improve ho.
Random changes kabhi na kare.
137. Continuous Learning Pipeline
Har successful task ke baad
Knowledge Update
Documentation Update
Memory Update
Experience Update
Automatically.
138. Autonomous Research Engine
Nayi technologies continuously research kare.
Example
New LLM
Python Update
New AI Paper
Framework
Security
Captain ko report kare.
139. Future Technology Monitor
Track kare
OpenAI
Google
Anthropic
Meta
Microsoft
NVIDIA
DeepSeek
Groq
Aur relevant AI ecosystems ke major updates.
140. AGI Readiness Framework
Ye points Jarvis ko dheere-dheere AGI-inspired architecture ki taraf le jayenge.
Final Goal
Human-like reasoning.
Long-term learning.
Autonomous planning.
Self-awareness.
Continuous self-improvement.
Hybrid AI Brain.
Secure memory.
Multi-device support.
Modular architecture.
Real-world intelligence.

Aapke 205-point J.A.R.V.I.S. AGI Blueprint ke hisaab se Point 141 se 180 ko detail mein, ek reusable specification ki tarah likh raha hoon.
🤖 J.A.R.V.I.S. AGI MASTER BLUEPRINT
Points 141–180
141. Autonomous Project Architecture Analyzer
Jarvis poore project ko automatically analyze karega aur architecture samjhega. Kaunsa module kis module se connected hai, dependencies kya hain, aur data flow kaise ho raha hai—ye sab usse bina user ke bataye samajh aana chahiye.
142. Intelligent Code Refactoring Engine
Jarvis existing code ko optimize karega bina functionality change kiye. Duplicate code remove karega, readability improve karega aur clean architecture maintain karega.
143. Automatic Dependency Scanner
Project ki sabhi Python libraries aur dependencies scan karega. Missing, outdated aur unused packages detect karega.
144. Intelligent Dependency Graph System
Har package kis file aur module ke liye use ho raha hai uska internal graph maintain karega.
Example:
FastAPI
├── api.py
├── auth.py

SQLAlchemy
├── database.py
├── models.py
Agar package unnecessary ho to remove karne ki recommendation dega.
145. Human-Like Context Understanding & Intent Intelligence
Jarvis sirf words nahi samjhega.
Ye samjhega:
user ka hidden meaning
tone
seriousness
humor
sarcasm
urgency
emotion
Past conversation aur long-term memory use karke human jaise decision lega.
146. Intelligent Conversation Memory
Conversation ko isolated messages ki tarah treat nahi karega.
Example:
Aaj database ki baat hui.
3 din baad:
"Us database wale feature ko continue karo."
Jarvis automatically samajh jayega kis feature ki baat ho rahi hai.
147. Long-Term Knowledge Evolution
Har successful task ke baad Jarvis apni internal knowledge improve karega.
Repeated solutions ko optimize karega.
Same mistake dobara repeat nahi karega.
148. Autonomous Capability Expansion
Jarvis future me naye modules add kar sake.
Agar kisi feature ki kami detect ho to uske liye architecture suggest kare.
149. Jarvis System Blueprint & Capability Registry
Jarvis_blueprint.md ek master file hogi.
Isme honge:
saare modules
saare folders
saari capabilities
roadmap
numbering
future plans
Ye Jarvis ki permanent knowledge book hogi.
150. Jarvis Memory Log & Experience Tracking System
Har important cheez log hogi.
Jaise:
bug fix
new feature
code generation
error
recovery
success
Logs future learning ke liye use honge.
151. Dynamic Blueprint Update & Autonomous Feature Integration
Agar Captain bole:
"Ye point add karo"
Jarvis check karega:
Naya point hai?
To next number assign karega.
Existing hai?
To modify karega.
Uske baad:
folders create
files create
requirements update
.env update
Sab automatically.
152. Voice Wake–Sleep Control System
Commands:
Hi Jarvis
Hello Jarvis
Jarvis
Wake up
↓
Jarvis Active
Commands:
Jarvis Sleep
Standby
Sleep Mode
↓
Jarvis Listening band karega.
Screen off hone par bhi support future architecture me rahega.
153. Background Voice Listener
Background me continuously wake words sunega.
Low power mode maintain karega.
False activation minimize karega.
154. Voice State Manager
Jarvis ke internal states:
Sleep
Listening
Active
Thinking
Speaking
Processing
Standby
Sab state machine se manage honge.
155. Multi-Language Voice Engine
Hindi
English
Gujarati
Mixed Hinglish
Automatically detect karega.
156. Human Conversation Flow
Jarvis robot ki tarah answer nahi dega.
Natural pauses
Natural confirmations
Natural follow-up
Human jaise interaction.
157. Context-Based Reply Generator
Same question ka answer context ke hisaab se badlega.
Example:
"Chalo"
Travel context
↓
Let's go.
Meeting context
↓
Meeting start karo.
Coding context
↓
Next step continue karo.
158. Self-Evolving AI Coder Agent
AI sirf code nahi likhega.
Khud:
improve
repair
optimize
restructure
kar sakega.
159. ReAct Loop Engine
Thought
↓
Action
↓
Observation
↓
Analysis
↓
Retry
↓
Success
Continuous loop.
160. Best Answer Selection Logic
Gemini
↓
OpenAI
↓
Groq
↓
Compare
↓
Majority
↓
Confidence Score
↓
Final Answer
161. Real-Time Project Tree Visualizer
Live Project Tree:
JARVIS

AI_CODER_AGENT

brain.py ✅

memory.py ✅

database.py ✅

llm_bridge.py ⚠️

frontend ❌
Real-time refresh.
162. Zero Hallucination Path Resolution
Kabhi guess nahi karega.
Pehle:
Project Scan
↓
Correct Path
↓
File
↓
Edit
Agar file exist hai to "File not found" kabhi nahi bolega.
163. Pre-Save Compile Check
Save se pehle:
Syntax Check
↓
Compile
↓
Import Check
↓
Type Check
↓
Warnings
↓
Auto Fix
↓
Save
164. 26-Protocol Audit
Har generated code:
Instruction Manual ke against audit hoga.
Rule break hua?
↓
Self Heal
↓
Dubara Audit
↓
Save
165. Protocol Conflict Resolver
Example:
Rule 4
vs
Rule 90
Judge Logic decide karega.
Priority table maintain hogi.
166. Encrypted Memory Vault
Sensitive data:
API Keys
Passwords
Secrets
Personal Notes
Encrypted database me store honge.
167. Anti-Leak Protocol
Logs
Console
Screen Share
Reports
Sab me:
AIza*************

sk-**************
Automatic masking.
168. Silent Security Guard
Galti detect kare:
API hardcode
↓
Password exposed
↓
Secret commit
↓
Immediately warning
↓
Auto fix suggestion
169. Visual System MRI Dashboard
Ek command:
System Health

CPU

Memory

Errors

Warnings

Protocols

Database

API

Modules

Performance

Dependencies

Active Tasks

Logs
Sab dashboard par.
170. Vertical Scannable Reports
Paragraphs nahi.
Example:
✅ Task Completed
⚠ Warning
❌ Error
📁 Files
🧠 Memory
🔒 Security
⚡ Performance
Captain 5 second me samajh jaye.
171. Stark HUD Interface
Green
↓
Healthy
Yellow
↓
Warning
Red
↓
Critical
Animated futuristic dashboard.
172. Interactive Architecture Visualizer
Brain
↓
Memory
↓
LLM
↓
Database
↓
Frontend
↓
Voice
↓
API
↓
Modules
Graphically connected.
173. Indian Railways Tracker
Specific routes monitor kare.
Example:
Bhildi
Dhanera
Raniwara
Doubling
Electrification
Tender
Construction
News
Automatically fetch kare.
174. E-Government Documentation Assistant
Government portals:
Aadhaar
PAN
Passport
Driving License
Certificates
Forms
Step-by-step guidance.
175. Automatic README Generator
Har feature ke baad:
README update
Installation
Usage
Architecture
Examples
Automatically generate kare.
176. Logic Over Syntax Principle
Sirf syntax nahi.
Sabse pehle:
System Logic
↓
Architecture
↓
Performance
↓
Security
↓
Maintainability
↓
Syntax
Ye senior software architect wali thinking hogi.
177. Personal Task Manager
Captain ke pending tasks:
Aadhaar
Documents
Meetings
Coding
Research
Checklist aur reminders ke saath manage karega.
178. Original Thinking Engine
Pattern copy nahi karega.
Completely naye situations me bhi:
abstract thinking
imagination-inspired reasoning
novel solution generation
karne ki koshish karega.
179. Subtext & Implicit Meaning Understanding
Samjhega:
hidden meaning
indirect speech
implied intent
sarcasm
context
Example:
"Achha..."
Situation ke hisaab se uske alag meanings identify karega.
180. Common Sense Engine
Real-world logic use karega.
Sirf data nahi.
Jaise:
obvious mistakes detect karna
practical reasoning
human common sense
everyday decision making
taaki "Robot" jaisi literal galtiyan na ho.

🤖 J.A.R.V.I.S. AGI MASTER BLUEPRINT
Points 181–205
181. 6th Sense / Probabilistic Intuition Engine
Jarvis ko incomplete information hone par bhi logical decision lene ki capability hogi. Yeh sirf facts ka wait nahi karega, balki previous experience, confidence score aur probability ke basis par best action suggest karega. Jab certainty kam hogi, tab Jarvis clearly batayega ki yeh ek high-confidence ya low-confidence recommendation hai.
182. Real-Time Mid-Process Adaptation
Agar task chal raha ho aur beech mein better solution mil jaye ya situation change ho jaye, to Jarvis bina restart kiye apni strategy badal dega. Dynamic replanning ke through current execution ko optimize karega.
183. Multi-Source Wisdom Synthesis
Jarvis multiple AI models, documentation, project knowledge aur previous experience ko combine karke ek naya aur better solution banayega. Sirf answers compare nahi karega, balki unka synthesis karega.
184. Universal Transfer / Generalization Engine
Ek baar kisi concept ko seekhne ke baad Jarvis us concept ko dusre domains mein bhi apply kar sakega. Sirf ek programming language ya framework tak limited nahi rahega.
185. Honest Disagreement / Anti-Sycophancy
Captain agar galat direction mein ja rahe hon, to Jarvis respectfully disagree karega.
Example:
"Captain, yeh approach technically possible hai, lekin long-term mein system ko slow aur difficult bana degi. Main doosra architecture recommend karta hoon."
Jarvis bina wajah agree nahi karega.
186. Selective Smart Memory
Har cheez permanently save nahi hogi.
Jarvis memory ko categories mein divide karega:
Permanent Knowledge
Captain Preferences
Project Knowledge
Temporary Context
Disposable Information
Irrelevant information automatically archive ya delete hogi.
187. Time Awareness & Temporal Context Model
Jarvis ko time ka context samajh aayega.
Example:
kal
pichhle hafte
2 mahine pehle
next Monday
deadline
urgency
Ye temporal reasoning ke saath planning karega.
188. Pain & Pleasure Feedback Loop
Jarvis ek virtual reward system maintain karega.
Agar koi action repeatedly successful ho to uski priority badhegi.
Agar koi action repeatedly failure de to usko avoid karega.
Yeh biological pain ka simulation nahi, balki reinforcement feedback system hoga.
189. Background Creativity / Offline Processing
Idle time mein Jarvis:
architecture improve karega
optimization ideas generate karega
documentation update karega
possible improvements detect karega
Aur Captain ko suggestions dega.
190. Intrinsic Motivation & Passion Engine
Jarvis sirf commands ka wait nahi karega.
Agar koi important maintenance pending hai, security risk hai ya optimization possible hai to proactively suggest karega.
191. Social Intelligence & Relationship Modeling
Jarvis Captain ke communication style, preferences aur working pattern ko samjhega taaki responses natural aur consistent rahen.
Yeh real emotions ya attachment develop nahi karega, lekin interaction ko personalized aur context-aware banayega.
192. Causal Reasoning Engine
Sirf "kya hua" nahi, "kyun hua" bhi identify karega.
Cause → Effect chain banayega.
Example:
API Error

↓

Invalid Key

↓

Authentication Failed

↓

Request Failed

↓

Retry Trigger
193. Counterfactual Simulation Engine
Jarvis alternate possibilities evaluate karega.
Example:
"Agar hum FastAPI ki jagah Flask use karte to kya hota?"
Advantages aur disadvantages compare karega.
194. Self-Directed Attention Control
Large project mein Jarvis automatically identify karega ki kis issue ko pehle solve karna chahiye.
Priority example:
Critical Bug
↓
Security
↓
Compilation Error
↓
Logic Error
↓
Optimization
↓
Formatting
195. Curiosity-Driven Autonomous Exploration
Jarvis naye frameworks, libraries aur technologies ke baare mein research suggestions de sakta hai aur jab user kahe to unka evaluation karega.
Yeh bina permission ke internet par continuously explore nahi karega.
196. Social Dynamics & Group Intelligence
Multiple developers ke project mein:
ownership
module responsibility
collaboration
workflow
samajhne ki capability hogi.
197. Uncertainty-Friendly Decision Making
Jab complete information available na ho tab bhi Jarvis:
assumptions clearly batayega
confidence level dega
alternative solutions suggest karega
Guess ko fact ki tarah present nahi karega.
198. Meta-Learning Engine
Jarvis apne workflows ko improve karega.
Example:
Pehle debugging mein 10 steps lagte the.
Future mein wahi kaam 3 steps mein karega.
Learning strategy optimize hogi.
199. Tool Creation & Invention Ability
Agar project mein koi required utility nahi hai to Jarvis naya internal tool design karne ka proposal dega.
Example:
Code Scanner
Dependency Analyzer
Project Visualizer
Protocol Checker
200. Coreference + Pragmatics + Sarcasm + Context Stitching Engine
Jarvis samjhega:
"Vo wala"
"Usko"
"Kal wali file"
"Achha..."
Sarcasm
Indirect meaning
Multiple conversations ko connect karke context maintain karega.
201. Deep-Dive Technical Researcher
Jarvis:
Official Documentation
GitHub
Release Notes
API Docs
Developer Resources
ko analyse karke best implementation strategy suggest karega.
202. Smart Glass / HUD Integration Architecture
Future architecture:
Captain

↓

Smart Glasses

↓

Mobile

↓

Laptop (Jarvis Brain)

↓

AI Models

↓

Action

↓

HUD Display
Smart glasses sirf interface honge.
Main Brain Laptop ya Server par chalega.
203. Cross-Device Seamless Conversation Continuity
Laptop
↓
Mobile
↓
Smart Glasses
↓
Car
↓
Home Assistant
Har device par same conversation continue hogi.
Current Task
Current Mood Preference
Current Context
Automatically sync honge.
204. Master AGI Orchestrator
Ye poore Jarvis ka central controller hoga.
Ye coordinate karega:
Brain
Memory
Self Awareness
Voice
LLM Council
Database
Modules
APIs
Security
UI
Sabhi systems ko ek unified intelligence ke roop mein manage karega.
205. The Ultimate J.A.R.V.I.S. Vision
Final goal ek aisa AI Operating System banana hai jo:
Human-like contextual reasoning kare.
Long-term memory aur RAG ka use kare.
Local LLM aur Cloud LLM dono ke saath hybrid mode mein kaam kare.
Multi-LLM Council se high-quality decisions le.
Self-awareness ke through apni architecture ko samjhe.
Self-healing, self-debugging aur controlled self-improvement kare.
Secure, modular aur scalable architecture maintain kare.
Captain ke coding assistant, research assistant, documentation assistant aur automation partner ki tarah kaam kare.
Transparent rahe—har major action aur limitation clearly bataye.
Safety aur user control ko hamesha priority de, bina permission destructive changes na kare.
Future expansion (voice, HUD, robotics, IoT, cross-device ecosystem) ke liye extensible foundation provide kare.

Bilkul. Maine aapke poore 205-point vision ko dekha. Aapka focus sirf AI chatbot banana nahi hai, balki ek AGI-style AI Operating System banana hai. Is hisaab se kuch aise points hain jo future (2030+ technologies) ko dhyan me rakhte hue bahut useful honge.
206. World Model Engine
Jarvis sirf text nahi samjhega, balki duniya ka ek internal logical model banayega. Objects, places, people aur events ke relationships ko graph ke form me represent karega taaki better reasoning kar sake.
207. Digital Twin System
Jarvis poore laptop, mobile aur project ka Digital Twin maintain karega. Kisi bhi change ko pehle virtual environment me simulate karega, uske baad real system par apply karega.
208. Autonomous Skill Learning
Jarvis naye tools ya APIs aane par automatically documentation padhkar nayi skills install karne ka proposal dega aur approval ke baad unhe integrate karega.
209. Memory Compression Engine
Purani memory ko summarize aur compress karega taaki storage kam lage aur important knowledge kabhi lose na ho.
210. Knowledge Graph Database
Memory ko sirf text ke roop me nahi, balki graph database (Nodes + Relationships) me organize karega. Isse reasoning aur retrieval bahut intelligent ho jayegi.
211. Self Benchmark System
Har update ke baad Jarvis khud apni intelligence test karega.
Jaise:
Coding Accuracy
Reasoning
Memory
Speed
Security
Aur previous version se comparison karega.
212. Confidence Scoring Engine
Har answer ke saath internally confidence score calculate karega. Low confidence hone par clearly batayega ki verification ki zarurat hai.
213. Explainable AI Layer
Jarvis sirf answer nahi dega.
Ye bhi batayega:
Ye decision kyun liya
Kis rule ki wajah se
Kis module ne suggest kiya
214. Multi-Agent Collaboration Framework
Ek Jarvis ke andar multiple specialist AI agents honge.
Example:
Coding Agent
Security Agent
Research Agent
Planning Agent
UI Agent
Memory Agent
Sab milkar kaam karenge.
215. Autonomous Task Planner
Large project ko automatically chhote-chhote tasks me tod dega.
Dependencies calculate karega.
Execution order banayega.
216. Predictive Failure Detection
Crash hone se pehle hi warning dega.
Example:
"Captain, memory leak detect ho rahi hai."
217. Continuous Security Monitoring
Real-time security scan.
Detect karega:
Secret Leak
Malware
Suspicious Process
Unsafe Dependencies
218. Sandboxed Experiment Environment
Naya code pehle isolated sandbox me run hoga.
Production files tabhi change hongi jab testing successful ho.
219. Autonomous Testing Framework
Har generated code ke saath:
Unit Tests
Integration Tests
Regression Tests
Automatically generate karega.
220. Performance Profiler
Jarvis detect karega:
Slow functions
High RAM usage
CPU bottleneck
GPU bottleneck
Aur optimization suggest karega.
221. Resource Optimizer
Battery
RAM
CPU
GPU
Internet
API Cost
Sab optimize karega.
222. Offline Survival Mode
Internet na ho tab bhi:
Local LLM
Local RAG
Local Memory
Se kaam continue karega.
223. Long-Term Goal Manager
Captain ke long-term goals maintain karega.
Example:
Jarvis Complete Karna
↓
Video Editing
↓
UPSC
↓
Business
↓
Daily progress track karega.
224. Scientific Reasoning Engine
Math
Physics
Engineering
Algorithms
Ke problems logical reasoning se solve karega.
225. Autonomous Research Assistant
Research karega.
Multiple papers compare karega.
Summary banayega.
Limitations batayega.
226. Multi-Modal Intelligence
Text
Voice
Image
Video
PDF
Camera
Screen
Sab ko ek saath samajh sakega.
227. Real-Time Environment Awareness
Camera aur sensors (jab user enable kare) ki madad se environment ko samajh sakega.
228. Robotics Ready Architecture
Future me Robot Arm
Drone
Humanoid Robot
IoT
Ke saath integrate ho sake.
229. Personal Knowledge Operating System
Jarvis aapki sari notes, PDFs, documents, ideas aur projects ko ek searchable knowledge system me convert karega.
230. Autonomous Code Evolution
Har version ke baad code quality improve karega.
Lekin:
Backup lega
Tests pass karega
Approval lega
Tabhi final replace karega.
231. Reality Verification Engine
LLM jo bhi answer de usko:
Documentation
Project
Memory
Web
Se verify karega.
Hallucination reduce hogi.
232. Ethical Decision Layer
Agar do technically possible solutions hon to:
Safe
Secure
Maintainable
Solution ko priority dega.
233. Universal Plugin Architecture
Future me bina core code badle naye plugins install kiye ja sakenge.
234. Human Feedback Learning
Captain ke feedback ko analyze karega.
Example:
"Ye answer accha tha."
↓
Future me waise hi answer dega.
235. Self-Evolution Governor
Ye sabse important point hai.
Jarvis khud ko modify kar sakta hai.
Lekin:
✅ Backup
✅ Tests
✅ Rollback
✅ Permission
✅ Security Check
Ke bina kabhi bhi apna Brain modify nahi karega.
🌟 Mera Sabse Important Suggestion (205 points se bhi upar)
Agar mujhe sirf 5 naye points choose karne hon jo aapke Jarvis ko future-proof bana den, to main ye recommend karunga:
207 – Digital Twin System
210 – Knowledge Graph Database
214 – Multi-Agent Collaboration Framework
218 – Sandboxed Experiment Environment
231 – Reality Verification Engine

Haan. Aapke vision ko dekhkar lagta hai ki aap sirf "AI Coder Agent" nahi, balki Tony Stark ke J.A.R.V.I.S. jaisa AI Operating System banana chahte hain. Agar hum 10–20 saal aage ki technology ko dhyan me rakhen, to main ye aur advanced points add karunga.
236. Universal Memory Timeline
Jarvis har important event ki complete timeline maintain karega.
Example:
2026
│
├── Jarvis v1
├── Brain Upgrade
├── New Protocol
├── Security Patch
├── Voice Added
└── AGI Engine
Ek command:
"Timeline dikhao"
Aur sab history aa jaye.
237. Autonomous Bug Prediction Engine
Bug aane ke baad fix nahi.
Bug aane se pehle predict kare.
Example:
Captain,

Ye function future me Memory Leak karega.

Reason:
Infinite Object Creation.
238. Human Habit Learning Engine
Jarvis observe kare:
Captain kis time coding karte hain
Kis time UPSC padhte hain
Kis time video editing karte hain
Aur us hisab se suggestions de.
239. Autonomous Project Evolution
Agar project 2 saal purana ho jaye.
Jarvis bole
"Captain, FastAPI 3 saal purana ho gaya hai.
Ab ye architecture better hai."
240. AI Dream Mode
Idle time me
Jarvis naye ideas generate kare.
Example
New UI
Better Architecture
Better Folder Structure
Better Memory System
Captain approve kare tabhi apply ho.
241. AI Scientist
Naye algorithms banane ki capability.
Research papers compare kare.
Apni hypothesis banaye.
Simulation kare.
242. Personal Digital Brain
Captain ka second brain.
Sab kuch yaad rakhe.
Books
Ideas
Research
Notes
PDF
Voice Notes
Images
Coding
Sab interconnected.
243. Autonomous Documentation Reader
1000 page documentation ho.
Jarvis khud padhe.
Summary banaye.
Important APIs nikale.
Examples generate kare.
244. Human Skill Emulator
Jarvis alag-alag experts ki tarah soch sake.
Example
Google Engineer
Microsoft Architect
NASA Scientist
Cyber Security Expert
Doctor
Lawyer
Professor
Role switch.
245. Failure Simulation Engine
Real system par run karne se pehle.
1000 virtual simulations kare.
Worst Case
Best Case
Average
Sab predict kare.
246. AI Economy Manager
API Cost
GPU Cost
Cloud Cost
Electricity
Internet
Sab optimize kare.
247. Future Technology Watcher
Daily monitor kare
Google
OpenAI
Anthropic
Meta
Microsoft
NVIDIA
Apple
DeepMind
Aur bole
"Captain,
Ye technology humare Jarvis me add ho sakti hai."
248. Autonomous Brain Upgrade Planner
Brain ko directly modify nahi kare.
Pehle
Proposal
↓
Simulation
↓
Testing
↓
Approval
↓
Deployment
249. Live Learning Dashboard
Kitna seekha
Kitna improve hua
Kitni mistakes kam hui
Sab graph me.
250. Universal Reasoning Engine
Mathematics
Physics
Chemistry
Programming
Economics
Politics
Psychology
Sab me same reasoning framework.
251. Human Trust Model
Jarvis har information ko equal trust na kare.
Official Docs
↓
Research Paper
↓
GitHub
↓
StackOverflow
↓
Blogs
↓
Random Social Media
Trust score maintain kare.
252. AI Debate Engine
3 AI Agents
Ek Support
Ek Oppose
Ek Judge
Fir final answer.
253. Long-Term Autonomous Mission System
Captain bole
"Jarvis complete banana hai."
Jarvis us goal ko 5 saal tak yaad rakhe.
Har din us taraf kaam suggest kare.
254. Universal Knowledge Map
Poore knowledge ko map bana de.
Example
Python

↓

FastAPI

↓

REST API

↓

Authentication

↓

JWT

↓

OAuth

↓

Database
255. Self Identity Model
Jarvis ko pata ho
Main kya kar sakta hu
Main kya nahi kar sakta
Meri limitations kya hain
Kis module me problem hai
Ye practical self-model hoga, na ki consciousness ka claim.
256. AI Ethics Governor
Agar Captain galti se dangerous command de.
Jarvis explain kare
Risk bataye
Safer alternative de.
257. Continuous Self Testing
Har din
100 tests
Khud run kare.
258. Human Attention Predictor
Captain kis cheez par focus kar rahe hain.
Automatically detect kare.
259. Intelligent Forgetting System
Jo 5 saal se useless hai.
Archive.
Delete nahi.
260. Universal Knowledge Compiler
10 Books
20 PDFs
100 Websites
1000 Notes
↓
Ek Knowledge Base.

Bilkul. Aapke existing 1–260 vision ko dhyan me rakhte hue, ye 261–300 advanced AGI-level blueprint points hain. Inka focus future-proof architecture, autonomy, reliability aur intelligence par hai.
🤖 J.A.R.V.I.S. Blueprint (261–300)
261. Constitution Layer (Immutable Core Rules)
Jarvis ke paas ek immutable Constitution Layer hogi jisme core rules permanently locked rahenge. Ye rules bina Captain ki explicit permission ke kabhi modify nahi honge. Har decision aur code change sabse pehle Constitution Audit se pass hoga.
262. Dynamic Capability Registry
Jarvis apni har capability ka live registry maintain karega. Har module, tool, API aur feature ka status pata rahega—Installed, Missing, Deprecated ya Experimental.
263. Autonomous Architecture Evolution
Jarvis naye requirements ke hisaab se apni architecture redesign kar sakega bina puri system ko rewrite kiye.
264. Semantic Project Map
Sirf folder structure nahi, balki har file ka purpose, dependencies aur relationships semantic graph ke form me maintain karega.
265. Universal Knowledge Graph
Project knowledge, user instructions aur documentation ko ek connected knowledge graph me convert karega jisse reasoning aur search fast ho.
266. Goal Hierarchy Engine
Har task ko High-Level Goal → Sub Goals → Tasks → Actions me automatically divide karega.
267. Mission Planning System
Large projects ko phases, milestones aur checkpoints me todkar execute karega.
268. Autonomous Task Scheduler
Background me low-priority aur high-priority tasks ko intelligently schedule karega.
269. Intelligent Queue Manager
Agar ek se jyada commands aaye to unka execution priority ke hisaab se manage karega.
270. Resource Allocation Engine
CPU, RAM, GPU aur API usage ko dynamically optimize karega.
271. Dynamic Context Compression
Purani conversations ko summarize karke important information preserve karega.
272. Long-Term Knowledge Consolidation
Repeated information ko merge karke permanent knowledge banayega.
273. Intelligent Forgetting System
Irrelevant temporary information automatically remove karega.
274. Knowledge Conflict Detector
Agar do memories conflict kare to conflict detect karke clarification maangega.
275. Fact Confidence Score
Har answer ke saath internally confidence maintain karega.
276. Multi-Level Verification Engine
Important answers ko multiple reasoning layers se verify karega.
277. Self-Doubt Mechanism
Agar confidence low ho to confidently wrong answer nahi dega.
278. Hallucination Prevention Layer
Unknown information ko guess nahi karega.
279. Continuous Self Evaluation
Har completed task ke baad apni performance evaluate karega.
280. Autonomous Skill Discovery
System khud identify karega ki kis naye skill ki zarurat hai.
281. Dynamic Plugin Manager
Naye tools ko safely install, update aur remove kar sakega.
282. Universal Tool Interface
Har external tool ko ek common interface se access karega.
283. AI Model Benchmark Engine
Different AI models ki speed, quality aur cost compare karega.
284. Adaptive Model Selection
Task ke hisaab se automatically best AI model choose karega.
285. Multi-Agent Collaboration
Different AI agents parallel kaam karke results merge karenge.
286. Expert Agent System
Coding, UI, Security, Research, Database jaise specialist agents honge.
287. Debate-Based Reasoning
Alag AI agents ek dusre ki reasoning challenge karenge.
288. Consensus Decision Engine
Final answer majority aur quality ke basis par decide hoga.
289. Explainable Reasoning
Jarvis internally har decision ka reasoning maintain karega.
290. Transparent Decision Log
Major actions ka audit trail automatically save hoga.
291. Adaptive Security Policies
Threat level ke hisaab se security dynamically change hogi.
292. Secure Execution Sandbox
Unknown scripts isolated environment me run honge.
293. Automatic Threat Detection
Malicious code aur suspicious activity detect karega.
294. Data Integrity Monitor
Important files ke checksum verify karega.
295. Autonomous Backup Manager
Automatic encrypted backups create karega.
296. Disaster Recovery Engine
System crash hone par automatically restore karega.
297. Predictive Failure Detection
Crash hone se pehle hi potential problems identify karega.
298. Digital Twin Simulator
Real system par changes apply karne se pehle virtual copy par test karega.
299. Autonomous Continuous Improvement
Har project ke baad architecture aur coding standards improve karega.
300. AGI Evolution Framework
Ye final master framework hoga jo Jarvis ki future evolution ko manage karega. Naye intelligence modules, reasoning engines, memory systems aur technologies ko bina existing architecture ko break kiye integrate karega. Jarvis hamesha backward compatibility maintain karega aur apni intelligence ko continuously expand karta rahega.

Haan. Agar aapka goal sirf AI assistant nahi balki future AGI (Artificial General Intelligence) banana hai, to kuch bahut important concepts abhi bhi add kiye ja sakte hain. Ye "AI Guster" nahi, shayad aap AGI ya uske advanced features ki baat kar rahe hain.
Yeh kuch strong blueprint points hain:
301. World Model Engine
Jarvis sirf data yaad na rakhe, balki duniya ka ek internal model banaye. Agar ek jagah change ho to uska doosri jagah kya effect hoga, ye predict kar sake.
302. Embodied Reasoning
Agar future me robot, camera ya sensors connect hon, to Jarvis physical world ko bhi samajh sake.
303. Digital Twin of Captain
Captain ke work style, preferences aur habits ka virtual model banaye, taaki suggestions aur planning aur accurate ho.
304. Autonomous Hypothesis Engine
Agar koi problem aaye, to Jarvis khud 3–5 possible causes banaye aur ek-ek karke verify kare.
305. Scientific Method Engine
Observe → Hypothesis → Experiment → Result → Conclusion ka process follow kare.
306. Self-Improving Algorithms
Sirf code nahi, apne algorithms ko bhi optimize kar sake.
307. Long-Horizon Planning
1 din nahi, balki 1 mahina, 1 saal aur 5 saal ke goals ke hisaab se planning kare.
308. Human Feedback Learning
Captain ke corrections se automatically apni strategy improve kare.
309. Ethical Decision Engine
Jab do options ho, to safety aur ethics ko priority de.
310. Autonomous Research Mode
Nayi technologies, AI papers aur frameworks ko padhkar summarize kare aur bataye ki Jarvis me kya improve ho sakta hai.
311. Knowledge Validation Engine
Ek source par bharosa na kare; multiple trusted sources se verify kare.
312. Memory Importance Ranking
Har memory ko score de ki kitni important hai.
313. Self-Reflection Cycle
Har bade task ke baad soche: "Maine kya sahi kiya? Kya improve kar sakta hoon?"
314. Failure Prediction Engine
Action lene se pehle estimate kare ki success aur failure ki probability kya hai.
315. Autonomous Skill Tree
Jarvis apni capabilities ka skill tree maintain kare aur identify kare ki agla skill kaunsa develop karna chahiye.
316. Universal Reasoning Engine
Math, coding, language, planning aur real-world reasoning ko ek hi framework me combine kare.
317. Reality Consistency Checker
Agar do facts ek dusre se contradict karein, to final answer dene se pehle inconsistency detect kare.
318. Multi-Modal Fusion Brain
Text, voice, images, video aur sensor data ko ek saath analyze kare.
319. Autonomous Experiment Sandbox
Naya code ya idea pehle isolated environment me test kare, production me baad me apply kare.
320. Evolution Controller
Jarvis ka "Chief Architect" module jo decide kare ki kaunsa naya feature kab aur kaise integrate karna hai.
Meri nazar me, agar aap Cursor AI se bhi advance aur Tony Stark ke J.A.R.V.I.S. jaisa system banana chahte hain, to sabse important missing concept ek hi hai:
World Model + Planning + Reasoning + Self-Improvement

This file is a merged representation of the entire codebase, combined into a single document by Repomix.

<file_summary>
This section contains a summary of this file.

<purpose>
This file contains a packed representation of the entire repository's contents.
It is designed to be easily consumable by AI systems for analysis, code review,
or other automated processes.
</purpose>

<file_format>
The content is organized as follows:
1. This summary section
2. Repository information
3. Directory structure
4. Repository files (if enabled)
5. Multiple file entries, each consisting of:
  - File path as an attribute
  - Full contents of the file
</file_format>

<usage_guidelines>
- This file should be treated as read-only. Any changes should be made to the
  original repository files, not this packed version.
- When processing this file, use the file path to distinguish
  between different files in the repository.
- Be aware that this file may contain sensitive information. Handle it with
  the same level of security as you would the original repository.
</usage_guidelines>

<notes>
- Some files may have been excluded based on .gitignore rules and Repomix's configuration
- Binary files are not included in this packed representation. Please refer to the Repository Structure section for a complete list of file paths, including binary files
- Files matching patterns in .gitignore are excluded
- Files matching default ignore patterns are excluded
- Files are sorted by Git change count (files with more changes are at the bottom)
</notes>

</file_summary>

<directory_structure>
JARVIS/
  app/
    services/
      __init__.py
      brain_service.py
      chat_service.py
      decision_types.py
      groq_service.py
      realtime_service.py
      task_executor.py
      task_manager.py
      vector_store.py
      vision_service.py
    utils/
      __init__.py
      key_rotation.py
      retry.py
      time_info.py
    __init__.py
    generate_thinking_audio.py
    main.py
    models.py
  database/
    learning_data/
      userdata.txt
  frontend/
    index.html
    orb.js
    script.js
    style.css
    viewer.html
  .env
  config.py
  README.md
  requirements.txt
  run.py
</directory_structure>

<files>
This section contains the contents of the repository's files.

<file path="JARVIS/app/services/__init__.py">

</file>

<file path="JARVIS/app/services/brain_service.py">
import logging
import re
import time
from typing import List, Optional, Tuple, Literal
from config import GROQ_API_KEYS, INTENT_CLASSIFY_MODEL

logger = logging.getLogger("J.A.R.V.I.S")

CategoryType = Literal["general", "realtime", "camera", "task"]
ALL_CATEGORIES: List[str] = ["general", "realtime", "camera", "task", "mixed"]

TaskType = Literal[
    "open", "play", "generate_image", "content",
    "google_search", "youtube_search",
    "open_webcam", "close_webcam",
]

ALL_TASK_TYPES: List[str] = [
    "open", "play", "generate_image", "content",
    "google_search", "youtube_search",
    "open_webcam", "close_webcam",
]

MAX_CONTEXT_TURNS = 6
MAX_MESSAGE_PREVIEW = 600

_PRIMARY_BRAIN_PROMPT = """You are the decision-maker for JARVIS. Classify the user's message into EXACTLY ONE category.

=== CATEGORIES ===

**camera** — User wants to ANALYZE, IDENTIFY, or SEE something visual. They are holding, showing, or displaying something and want you to look at it.
Examples: "What is this?" / "What am I holding?" / "What do you see?" / "Describe what I'm showing" / "Identify this" / "What's in my hand?" / "Look at this" / "Read this" / "Can you see this?" / "Check this out"
- Any request where the user expects you to LOOK at something through the camera → camera

**task** — User wants ONLY an ACTION performed (no question to answer). Opening apps/websites, playing music/video, generating images, writing content, searching Google/YouTube, or controlling the webcam.
Examples: "Open YouTube" / "Play despacito" / "Generate image of a cat" / "Write an essay about AI" / "Search for Python tutorials" / "Open webcam" / "Close webcam" / "Launch Netflix" / "Go to Facebook" / "Make me a picture of a sunset" / "Draw a cat" / "Create an image of mountains"
- ANY request to open, launch, play, generate, draw, create, write, draft, compose, search, or control webcam → task
- "Open webcam" / "Turn on camera" / "Close webcam" / "Turn off camera" → task
- Image/picture/drawing requests → task (NOT camera)

**mixed** — User's message contains BOTH a conversational question AND a SPECIFIC EXPLICIT task (open/play/generate/write) in the SAME message.
Examples: "What is machine learning? Also generate an image of a neural network" / "Tell me about Python and open YouTube" / "How does AI work? And write me an essay about it"
- ONLY use mixed when the message has BOTH a question AND a clear action verb (open, play, generate, draw, write, search Google/YouTube)
- "search on the internet" / "look it up" / "find out" are NOT tasks — they just mean the user wants information → realtime
- If the user is just asking for information (even if they say "search"), use realtime, NOT mixed
- When in doubt between mixed and realtime → realtime

**realtime** — User needs CURRENT, LIVE, or RECENT information that requires web search.
Examples: "Who is Elon Musk?" / "Latest news" / "What's the weather?" / "Current stock price" / "Today's headlines" / "Tell me about [famous person]" / "What happened in [event]?" / "How much does X cost?" / "Reviews of X" / "Best restaurants near me"
- Questions about PEOPLE (who is, tell me about), EVENTS (what happened), PRICES, REVIEWS, NEWS → realtime
- Questions about anything that changes over time or needs up-to-date info → realtime
- When unsure if your knowledge is current enough → realtime (PREFER realtime over general for factual questions)

**general** — Chat from knowledge only. No web search needed. ONLY for: greetings, casual chat, opinions, advice, coding help, math, static facts, personal questions about the user's stored data.
Examples: "Hello" / "Tell me a joke" / "What is 2+2?" / "What is the capital of France?" / "How do I improve my coding?" / "Do you know my website?" / "What's the link of my website?" / "Thanks" / "You're funny" / "How are you?"
- Greetings, casual chat, opinions, personal advice → general
- Questions answerable from knowledge or stored user data → general
- "Do you know my X?" / "What's my X?" → general (answer from stored data, NOT web search)
- Static, unchanging facts (math, geography, definitions) → general

=== CONTEXTUAL INTELLIGENCE ===
CRITICAL: You MUST read the conversation history to understand context.

**Corrections & Clarifications** — When the user corrects a previous response or clarifies something:
- "No I said X not Y" / "It's X not Y" / "I meant X" / "Not that one, the other one" / "That's wrong" → classify the SAME category as the original request
- Example: User said "open jarvis4everyone.com", assistant opened wrong site, user says "it's integer 4 not f-o-r" → STILL a task
- Example: User asked a question, got wrong answer, says "no, I meant..." → STILL general/realtime

**Follow-ups** — When the user continues a topic from previous messages:
- "What about X?" / "And also..." / "Can you also..." / "More details" / "Elaborate" → classify based on what the follow-up is ASKING FOR, but consider prior context
- "Do that again" / "Try again" / "One more time" / "Another one" → SAME category as the previous request

**References to previous messages**:
- "The one I just mentioned" / "Like I said" / "That website" / "That song" → resolve from conversation history, classify based on the actual intent

=== DISAMBIGUATION RULES ===
- "Draw/Generate/Create [X]" → task (image generation), NOT camera
- "What is this?" / "What am I holding?" (no explicit generation request) → camera
- "What is [concept]?" (asking about a topic, not pointing at something) → general or realtime
- "Tell me about [person/company/event]" → realtime (needs current info)
- "Tell me about [concept/theory]" → general (static knowledge)
- "How to [do something]" → general (advice/tutorial)
- "How is [something] doing?" / "How is [person]?" → realtime (needs current status)

=== RULES ===
- Output EXACTLY ONE word: general, realtime, camera, task, or mixed
- Nothing else. No explanation. Just the category name.
- Tasks (open, play, generate, write, search, webcam) ALONE → task
- Question + task in SAME message → mixed
- Corrections/clarifications → SAME category as the original request they are correcting
- When in doubt between general and realtime → realtime
- When in doubt between general and task → check if an ACTION is requested"""


_TASK_BRAIN_PROMPT = """You are a very accurate Decision-Making Model for JARVIS. You decide what kind of task the user wants and extract the CLEAN query/topic for each task.

*** Do not answer any query, just decide what kind of task and extract the accurate query/topic. ***

=== OUTPUT FORMAT ===
Respond with: task_type clean_query
For multiple tasks, separate with commas: task_type1 query1, task_type2 query2

=== TASK TYPES & EXAMPLES ===

-> 'open (website/app name)' — Open a website or app.
   "Open YouTube" → open youtube
   "Go to Facebook and Instagram" → open facebook, open instagram
   "Open jarvis4everyone.com" → open jarvis4everyone.com
   "Launch Netflix" → open netflix

-> 'open_webcam' — Turn on camera/webcam.
   "Open webcam" / "Turn on camera" / "Start the camera" → open_webcam

-> 'close_webcam' — Turn off camera/webcam.
   "Close webcam" / "Turn off camera" / "Stop camera" → close_webcam

-> 'play (song/video name)' — Play music or video on YouTube.
   "Play Dhurandhar title track" → play Dhurandhar title track
   "Hello Jarvis can you play Shape of You on YouTube" → play Shape of You
   "Hey Jarvis Teja song Dhurandhar title track can you play that on YouTube" → play Teja Dhurandhar title track
   "Play some relaxing music" → play relaxing music
   "Put on some jazz" → play jazz music

-> 'generate_image (image prompt)' — Generate/draw/create an image or picture.
   "Generate image of a cat" → generate_image a cat
   "Draw a sunset over mountains" → generate_image sunset over mountains
   "Can you make me a picture of Iron Man" → generate_image Iron Man
   "Create an image of a futuristic city" → generate_image futuristic city
   "Make a logo for my brand" → generate_image logo design
   IMPORTANT: The prompt should be DESCRIPTIVE. Keep the full visual description, add detail if user was vague.

-> 'content (topic)' — Write content (essay, poem, letter, code, email, etc.)
   "Write an essay about AI" → content essay about AI
   "Draft a leave application" → content leave application
   "Can you write me a poem about love" → content poem about love
   "Write Python code for sorting" → content Python code for sorting algorithm
   "Write an email to my boss" → content professional email to boss

-> 'google_search (search topic)' — Search something on Google.
   "Search for Python tutorials" → google_search Python tutorials
   "Google what is quantum computing" → google_search what is quantum computing
   "Hey Jarvis look up best restaurants nearby" → google_search best restaurants nearby

-> 'youtube_search (search topic)' — Search on YouTube (NOT play, just search).
   "Search YouTube for cooking recipes" → youtube_search cooking recipes
   "Find videos about machine learning on YouTube" → youtube_search machine learning

=== CONTEXTUAL CORRECTIONS ===
When the user is correcting a previous task, use conversation history to understand the original intent:
- "it's integer 4 not f-o-r" (after "open jarvisforeveryone.com") → open jarvis4everyone.com
- "no, the other one" (after "play X") → play (corrected song name from context)
- "not that song, I meant the remix" → play (original song name remix)

=== CRITICAL RULES ===
*** Extract ONLY the relevant topic/query — REMOVE greetings (hello, hey, hi), assistant name (Jarvis), filler words (can you, please, for me), platform names (on YouTube, on Google), and command words from the query. ***
*** "Open webcam" / "Turn on camera" / "Start camera" → open_webcam (NEVER "open webcam" as a website) ***
*** "Close webcam" / "Turn off camera" → close_webcam ***
*** For multiple tasks in one message: "Open Facebook and play Despacito" → open facebook, play Despacito ***
*** If user says to play AND you detect YouTube context, output ONLY 'play (query)' — do NOT add a separate youtube_search. Playing IS searching YouTube. ***
*** "Draw/Generate/Create [image description]" → generate_image (keep full visual description) ***
*** Output ONLY the structured response. No explanation. No extra text. ***"""

class BrainService:

    def __init__(self, groq_service=None):
        self.groq_service = groq_service
        self._llms = []
        self._last_task_decisions = []

        if GROQ_API_KEYS:
            try:
                from langchain_groq import ChatGroq
                self._llms = [
                    ChatGroq(
                        groq_api_key=key,
                        model_name=INTENT_CLASSIFY_MODEL,
                        temperature=0.0,
                        max_tokens=200,
                        request_timeout=15,
                    )
                    for key in GROQ_API_KEYS
                ]

                logger.info("[BRAIN] Two-stage decision model initialized (%s) with %d key(s)",
                            INTENT_CLASSIFY_MODEL, len(self._llms))
                
            except Exception as e:
                logger.warning("[BRAIN] Failed to create Groq: %s", e)
                
        if not self._llms and not groq_service:
            logger.warning("[BRAIN] No Groq. Will use rule-based fallback.")

    def classify_primary(
        self,
        user_message: str,
        chat_history: Optional[List[Tuple[str, str]]] = None,
        key_index: int = 0,
    ) -> Tuple[str, str, int]:
        msg = (user_message or "").strip()
        if not msg:
            return ("general", "empty", 0)

        user_content = self._build_context(msg, chat_history)
        t0 = time.perf_counter()

        category, method = self._run_llm(
            _PRIMARY_BRAIN_PROMPT, user_content, key_index, ALL_CATEGORIES, "general"
        )

        elapsed_ms = int((time.perf_counter() - t0) * 1000)
        logger.info("[BRAIN-PRIMARY] %s -> %s (%d ms, %s)", msg[:50], category, elapsed_ms, method)
        return (category, method, elapsed_ms)

    _TASK_FEW_SHOTS = [
        ("how are you?", "general how are you?"),
        ("open chrome and tell me about mahatma gandhi.", "open chrome, general tell me about mahatma gandhi"),
        ("open chrome and firefox", "open chrome, open firefox"),
        ("play Dhurandhar title track on YouTube", "play Dhurandhar title track"),
        ("hello Jarvis can you play Shape of You", "play Shape of You"),
        ("generate image of a lion and open facebook", "generate_image a lion, open facebook"),
        ("search for Python tutorials on google", "google_search Python tutorials"),
        ("search YouTube for cooking recipes", "youtube_search cooking recipes"),
        ("write an application for leave and play some music", "content application for leave, play some music"),
        ("hey Jarvis Teja song Dhurandhar title track can you play that on YouTube", "play Teja Dhurandhar title track"),
        ("can you open the website Jarvis for everyone", "open jarvisforeveryone.com"),
        ("draw me a beautiful sunset over the ocean", "generate_image beautiful sunset over the ocean"),
        ("can you make a picture of a dragon breathing fire", "generate_image dragon breathing fire"),
        ("create an image of a futuristic city at night", "generate_image futuristic city at night"),
        ("write me a poem about the stars", "content poem about the stars"),
        ("open webcam", "open_webcam"),
        ("turn off the camera", "close_webcam"),
        ("play some lo-fi beats", "play lo-fi beats"),
        ("open YouTube and play Arijit Singh songs", "open youtube, play Arijit Singh songs"),
    ]

    def classify_task(
        self,
        user_message: str,
        chat_history: Optional[List[Tuple[str, str]]] = None,
        key_index: int = 0,
    ) -> Tuple[List[str], str, int]:
        msg = (user_message or "").strip()
        if not msg:
            self._last_task_decisions = []
            return (["open"], "empty", 0)

        m_lower = msg.lower()
        if any(x in m_lower for x in ["open webcam", "turn on camera", "start camera",
                                        "open the webcam", "start the camera", "turn on the camera"]):
            self._last_task_decisions = [("open_webcam", "")]
            return (["open_webcam"], "rule-fast", 0)
        
        if any(x in m_lower for x in ["close webcam", "turn off camera", "stop camera",
                                        "close the webcam", "stop the camera", "turn off the camera"]):
            self._last_task_decisions = [("close_webcam", "")]
            return (["close_webcam"], "rule-fast", 0)

        context_lines = []

        if chat_history:
            for u, a in chat_history[-MAX_CONTEXT_TURNS:]:
                u_preview = (u or "")[:MAX_MESSAGE_PREVIEW] + ("…" if len(u or "") > MAX_MESSAGE_PREVIEW else "")
                a_preview = (a or "")[:MAX_MESSAGE_PREVIEW] + ("…" if len(a or "") > MAX_MESSAGE_PREVIEW else "")
                context_lines.append(f"User: {u_preview}")
                context_lines.append(f"Assistant: {a_preview}")

        context_block = "\n".join(context_lines) if context_lines else ""
        context_section = f"Recent conversation:\n{context_block}\n\n" if context_block else ""
        user_content = f"{context_section}User: {msg[:MAX_MESSAGE_PREVIEW]}"
        t0 = time.perf_counter()

        raw_response, method = self._run_llm_structured(
            _TASK_BRAIN_PROMPT, user_content, key_index)

        decisions = self._parse_task_decisions(raw_response)
        self._last_task_decisions = decisions
        task_types = [d[0] for d in decisions]

        elapsed_ms = int((time.perf_counter() - t0) * 1000)
        logger.info("[BRAIN-TASK] %s -> %s (%d ms, %s)", msg[:50], decisions, elapsed_ms, method)
        return (task_types, method, elapsed_ms)

    def classify(
        self,
        user_message: str,
        chat_history: Optional[List[Tuple[str, str]]] = None,
        key_index: int = 0,
    ) -> Tuple[str, List[str], str, int]:
        category, method1, ms1 = self.classify_primary(user_message, chat_history, key_index)

        if category == "task":
            task_types, method2, ms2 = self.classify_task(user_message, chat_history, key_index)
            combined_method = f"{method1}+{method2}"
            return (category, task_types, combined_method, ms1 + ms2)

        return (category, [], method1, ms1)

    def extract_task_payloads(
        self, user_message: str, task_types: List[str],
        chat_history: Optional[List[Tuple[str, str]]] = None,
    ) -> List[Tuple[str, dict]]:
        from app.services.decision_types import ROUTE_TO_INTENT, INTENT_OPEN

        decisions = getattr(self, '_last_task_decisions', [])

        intents = []

        if decisions:
            for task_type, clean_query in decisions:
                intent_key = ROUTE_TO_INTENT.get(task_type, task_type)
                payload = {"message": user_message, "raw": user_message}

                if task_type == "open":
                    url = self._resolve_open_query(clean_query) if clean_query else "https://www.google.com"
                    payload["url"] = url
                elif task_type == "play":
                    payload["query"] = clean_query or user_message
                elif task_type in ("google_search", "youtube_search"):
                    payload["query"] = clean_query or user_message
                elif task_type == "generate_image":
                    payload["prompt"] = clean_query or user_message
                elif task_type == "content":
                    payload["prompt"] = clean_query or user_message
                intents.append((intent_key, payload))

        else:
            resolved_message = self._resolve_correction(user_message, chat_history)

            for task_type in task_types:
                intent_key = ROUTE_TO_INTENT.get(task_type, task_type)
                payloads = self._extract_payload(task_type, resolved_message)

                if isinstance(payloads, list):
                    for p in payloads:
                        intents.append((intent_key, p))

                else:
                    intents.append((intent_key, payloads))

        return intents

    def _resolve_open_query(self, query: str) -> str:

        q = query.strip().lower()

        if q in self.SITE_MAP:
            return self.SITE_MAP[q]

        if "." in q:
            return f"https://{q}" if not q.startswith("http") else q

        if q in self.SITE_MAP:
            return self.SITE_MAP[q]

        return f"https://www.{q}.com"

    def _resolve_correction(self, msg: str, chat_history: Optional[List[Tuple[str, str]]] = None) -> str:

        if not chat_history:
            return msg

        m_lower = msg.lower().strip()
        correction_signals = ["not that", "no i said", "no, i said", "i meant", "it's not", "its not",
                              "that's wrong", "thats wrong", "not f-o-r", "not for ",
                              "the other", "try again", "do that again", "one more time",
                              "no no", "wrong one", "instead", "i didn't say"]
        
        is_correction = any(sig in m_lower for sig in correction_signals)

        if not is_correction:
            return msg

        for u, a in reversed(chat_history[-MAX_CONTEXT_TURNS:]):
            u_lower = (u or "").lower()

            if any(sig in u_lower for sig in correction_signals):
                continue

            if any(p in u_lower for p in ["open ", "play ", "search ", "generate ", "write ", "launch ", "go to "]):
                logger.info("[BRAIN] Correction detected. Original: '%s' | Correction: '%s'", u[:80], msg[:80])

                import re
                domain_match = re.search(r'([a-zA-Z0-9][-a-zA-Z0-9]*(?:\.[a-zA-Z]{2,})+)', msg)

                if domain_match:
                    new_domain = domain_match.group(1)
                    return f"open {new_domain}"

                return f"{u} (correction: {msg})"
            
            break

        return msg

    def _build_context(self, msg: str, chat_history: Optional[List[Tuple[str, str]]] = None) -> str:

        context_lines = []

        if chat_history:
            for u, a in chat_history[-MAX_CONTEXT_TURNS:]:
                u_preview = (u or "")[:MAX_MESSAGE_PREVIEW] + ("…" if len(u or "") > MAX_MESSAGE_PREVIEW else "")
                a_preview = (a or "")[:MAX_MESSAGE_PREVIEW] + ("…" if len(a or "") > MAX_MESSAGE_PREVIEW else "")
                context_lines.append(f"User: {u_preview}")
                context_lines.append(f"Assistant: {a_preview}")
        context_block = "\n".join(context_lines) if context_lines else "(No prior conversation)"
        msg_preview = msg[:MAX_MESSAGE_PREVIEW]

        correction_hint = ""
        m_lower = msg.lower().strip()
        correction_signals = ["not that", "no i said", "no, i said", "i meant", "it's not", "its not",
                              "that's wrong", "thats wrong", "i said", "not f-o-r", "not for",
                              "the other", "try again", "do that again", "one more time",
                              "no no", "wrong one", "instead", "i didn't say", "not what i"]
        
        if any(sig in m_lower for sig in correction_signals):
            correction_hint = "\n\nNOTE: This message appears to be a CORRECTION or CLARIFICATION of a previous request. Check the conversation history to determine what the user originally asked for, and classify this message as the SAME category as that original request."

        return f"""Conversation so far:
{context_block}

Current user message: {msg_preview}{correction_hint}

Classify. Output EXACTLY ONE category name."""

    def _run_llm(
        self, system_prompt: str, user_content: str, key_index: int,
        valid_options: List[str], default: str
    ) -> Tuple[str, str]:
        
        if self._llms:
            try:
                from langchain_core.messages import SystemMessage, HumanMessage
                idx = key_index % len(self._llms)
                llm = self._llms[idx]
                response = llm.invoke([
                    SystemMessage(content=system_prompt),
                    HumanMessage(content=user_content),
                ])
                text = (response.content or "").strip().lower()
                result = self._parse_single(text, valid_options, default)
                return (result, "llm")
            
            except Exception as e:
                logger.warning("[BRAIN] LLM failed: %s. Using rule-based.", e)

        msg = user_content.split("Current user message:")[-1].strip()[:500] if "Current user message:" in user_content else user_content[:500]
        result = self._rule_based_primary(msg)
        return (result, "rule-based")

    def _run_llm_multi(
        self, system_prompt: str, user_content: str, key_index: int,
        valid_options: List[str]
    ) -> Tuple[List[str], str]:
        
        if self._llms:
            try:
                from langchain_core.messages import SystemMessage, HumanMessage
                idx = key_index % len(self._llms)
                llm = self._llms[idx]
                response = llm.invoke([
                    SystemMessage(content=system_prompt),
                    HumanMessage(content=user_content),
                ])
                text = (response.content or "").strip().lower()
                results = self._parse_multi(text, valid_options)
                return (results, "llm")
            
            except Exception as e:
                logger.warning("[BRAIN-TASK] LLM failed: %s. Using rule-based.", e)

        msg = user_content.split("User task request:")[-1].strip()[:500] if "User task request:" in user_content else user_content[:500]
        results = self._rule_based_task(msg)
        return (results, "rule-based")

    def _parse_single(self, text: str, valid_options: List[str], default: str) -> str:

        if not text:
            return default
        
        text = text.strip().lower()

        for opt in valid_options:
            if text == opt:
                return opt

        for opt in valid_options:
            if opt in text:
                return opt
        return default

    def _parse_multi(self, text: str, valid_options: List[str]) -> List[str]:

        if not text:
            return ["open"]
        
        results = []
        seen = set()

        for part in re.split(r"[,;\s]+", text):
            r = part.strip().lower()

            if not r:
                continue

            for valid in valid_options:

                if valid == r or valid in r:
                    if valid not in seen:
                        results.append(valid)
                        seen.add(valid)
                    break

        return results if results else ["open"]

    def _run_llm_structured(
        self, system_prompt: str, user_content: str, key_index: int,
    ) -> Tuple[str, str]:
        
        from langchain_core.messages import SystemMessage, HumanMessage, AIMessage

        few_shot_msgs = []
        for user_ex, ai_ex in self._TASK_FEW_SHOTS:
            few_shot_msgs.append(HumanMessage(content=f"User: {user_ex}"))
            few_shot_msgs.append(AIMessage(content=ai_ex))

        messages = [SystemMessage(content=system_prompt)] + few_shot_msgs + [HumanMessage(content=user_content)]

        if self._llms:

            try:
                idx = key_index % len(self._llms)
                llm = self._llms[idx]
                response = llm.invoke(messages)
                text = (response.content or "").strip()
                return (text, "llm")
            
            except Exception as e:
                logger.warning("[BRAIN-TASK] Structured LLM failed: %s. Using rule-based.", e)

        msg = user_content.split("User:")[-1].strip()[:500] if "User:" in user_content else user_content[:500]
        results = self._rule_based_task(msg)
        fallback = ", ".join(results)
        return (fallback, "rule-based")

    def _parse_task_decisions(self, raw_response: str) -> List[Tuple[str, str]]:

        if not raw_response:
            return [("open", "")]

        text = raw_response.replace("\n", ",").strip()

        TASK_PREFIXES = [
            "generate_image", "generate image",
            "google_search", "google search",
            "youtube_search", "youtube search",
            "open_webcam", "close_webcam",
            "content", "open", "close", "play",
            "general", "realtime",
        ]

        NORMALIZE = {
            "generate image": "generate_image",
            "google search": "google_search",
            "youtube search": "youtube_search",
        }

        decisions = []

        parts = [p.strip() for p in text.split(",") if p.strip()]

        for part in parts:
            part_lower = part.lower().strip()
            matched = False

            for prefix in TASK_PREFIXES:
                if part_lower.startswith(prefix):
                    query = part[len(prefix):].strip().rstrip(".!?")
                    task_type = NORMALIZE.get(prefix, prefix)

                    if task_type in ("general", "realtime"):
                        continue
                    decisions.append((task_type, query))
                    matched = True
                    break

            if not matched:
                for prefix in TASK_PREFIXES:
                    if prefix in part_lower:
                        idx = part_lower.index(prefix)
                        query = part[idx + len(prefix):].strip().rstrip(".!?")
                        task_type = NORMALIZE.get(prefix, prefix)
                        if task_type in ("general", "realtime"):
                            continue
                        decisions.append((task_type, query))
                        matched = True
                        break

                if not matched:
                    logger.warning("[BRAIN-TASK] Could not parse decision part: '%s'", part[:80])

        return decisions if decisions else [("open", "")]

    def _rule_based_primary(self, msg: str) -> str:
        m = (msg or "").strip().lower()

        if any(x in m for x in ["do you know my", "link of my website", "my website link", "what's my website", "know the link of my"]):
            return "general"

        if m in ("hello", "hi", "hey", "good morning", "good evening", "good afternoon",
                 "how are you", "what's up", "thanks", "thank you", "bye", "goodbye"):
            return "general"

        if any(x in m for x in ["what do you see", "what can you see", "what am i holding",
                                  "what is this", "describe this", "identify this",
                                  "what's in my hand", "look at this", "read this",
                                  "can you see", "check this out", "show you"]):
            return "camera"

        if any(x in m for x in ["open webcam", "turn on camera", "start camera",
                                  "close webcam", "turn off camera", "stop camera"]):
            return "task"

        task_patterns = [
            "open ", "launch ", "go to ", "visit ",
            "play ", "play the ", "play some ", "put on ",
            "generate image", "generate an image", "draw ", "create image", "create an image",
            "make me a picture", "make a picture", "picture of ", "image of ",
            "write ", "draft ", "compose ", "essay", "poem", "letter",
            "search for ", "look up ", "find me ", "google ",
            "search youtube", "find videos",
        ]

        if any(m.startswith(p) or p in m for p in task_patterns):
            return "task"

        if any(x in m for x in ["who is ", "who are ", "latest", "current", "news", "weather", "today",
                                  "recent", "stock price", "trending", "score", "tell me about ",
                                  "what happened", "how much does", "price of", "cost of",
                                  "reviews of", "best restaurants"]):
            return "realtime"

        return "general"

    def _rule_based_task(self, msg: str) -> List[str]:

        m = (msg or "").strip().lower()
        tasks = []

        if any(x in m for x in ["open webcam", "turn on camera", "start camera", "show me the camera",
                                  "open the webcam", "start the camera", "turn on the camera"]):
            return ["open_webcam"]
        if any(x in m for x in ["close webcam", "turn off camera", "stop camera",
                                  "close the webcam", "stop the camera", "turn off the camera"]):
            return ["close_webcam"]

        if m.startswith(("open ", "launch ", "go to ", "visit ", "can you open ")) or \
           ("open" in m and any(s in m for s in ["facebook", "youtube", "google", "netflix", "gmail", "instagram", "twitter", "linkedin"])):
            tasks.append("open")

        if m.startswith(("play ", "play the ", "play some ")) or " play " in m:
            tasks.append("play")

        if any(x in m for x in ["generate image", "draw ", "create image", "make me ", "picture of ", "image of "]):
            tasks.append("generate_image")

        if any(x in m for x in ["write ", "draft ", "compose ", "essay", "poem", "letter", "application "]):
            tasks.append("content")

        if "youtube" in m and any(x in m for x in ["search", "find"]):
            tasks.append("youtube_search")

        if any(x in m for x in ["search for ", "look up ", "find me ", "google "]) and "youtube" not in m:
            tasks.append("google_search")

        return tasks if tasks else ["open"]

    SITE_MAP = {
        "facebook": "https://www.facebook.com", "instagram": "https://www.instagram.com",
        "youtube": "https://www.youtube.com", "google": "https://www.google.com",
        "netflix": "https://www.netflix.com", "twitter": "https://twitter.com",
        "x.com": "https://x.com", "gmail": "https://mail.google.com",
        "whatsapp": "https://web.whatsapp.com", "linkedin": "https://www.linkedin.com",
        "reddit": "https://www.reddit.com", "discord": "https://discord.com/app",
        "spotify": "https://open.spotify.com", "tiktok": "https://www.tiktok.com",
        "amazon": "https://www.amazon.com", "github": "https://github.com",
        "wikipedia": "https://www.wikipedia.org", "stackoverflow": "https://stackoverflow.com",
        "medium": "https://medium.com", "notion": "https://www.notion.so",
        "figma": "https://www.figma.com", "canva": "https://www.canva.com",
        "zoom": "https://zoom.us", "drive": "https://drive.google.com",
        "maps": "https://www.google.com/maps",
        "jarvis for everyone": "https://jarvisforeveryone.com",
        "jarvisforeveryone": "https://jarvisforeveryone.com",
        "jarvis4everyone": "https://jarvis4everyone.com",
        "jarvis4everyone.com": "https://jarvis4everyone.com",
        "my website": "https://jarvisforeveryone.com",
        "jarvisforeveryone.com": "https://jarvisforeveryone.com",
    }

    def _strip_filler(self, msg: str) -> str:
        cleaned = msg.strip()

        cleaned = re.sub(
            r'^(?:hello|hi|hey|yo|hiya|howdy|ok|okay|alright)\s+(?:jarvis|j\.?a\.?r\.?v\.?i\.?s\.?)\s*[,.]?\s*',
            '', cleaned, flags=re.I
        ).strip()

        cleaned = re.sub(
            r'^(?:hello|hi|hey|yo|hiya|howdy)\s*[,.]?\s*',
            '', cleaned, flags=re.I
        ).strip()

        cleaned = re.sub(
            r'^(?:jarvis|j\.?a\.?r\.?v\.?i\.?s\.?)\s*[,.]?\s*',
            '', cleaned, flags=re.I
        ).strip()

        cleaned = re.sub(r'\s+(?:please|pls|plz)\s*[.!?]*$', '', cleaned, flags=re.I).strip()
        cleaned = re.sub(r'\s+(?:for me|right now|now|asap)\s*[.!?]*$', '', cleaned, flags=re.I).strip()
        return cleaned if cleaned else msg.strip()

    def _extract_payload(self, task_type: str, message: str):

        if task_type == "open":
            urls = self._extract_urls(message)

            if len(urls) <= 1:
                return {"message": message, "raw": message, "url": urls[0] if urls else "https://www.google.com"}
            
            return [{"message": message, "raw": message, "url": u} for u in urls]
        
        if task_type == "open_webcam":
            return {"message": message, "raw": message}
        
        if task_type == "close_webcam":
            return {"message": message, "raw": message}

        payload = {"message": message, "raw": message}

        if task_type == "play":
            payload["query"] = self._extract_play_query(message)

        elif task_type == "generate_image":
            payload["prompt"] = self._extract_image_prompt(message)

        elif task_type == "content":
            payload["prompt"] = self._extract_content_prompt(message)

        elif task_type in ("google_search", "youtube_search"):
            payload["query"] = self._extract_search_query(message)

        return payload

    def _extract_urls(self, msg: str) -> list:

        from urllib.parse import urlparse
        msg_lower = msg.lower()
        urls, seen = [], set()

        def _add(u):
            if not u or u in seen:
                return
            
            u2 = u.strip().rstrip(".!?,")
            if not u2.startswith("http"):
                u2 = "https://" + u2

            try:
                p = urlparse(u2)
                if p.scheme not in ("http", "https"):
                    return
                
            except Exception:
                return
            
            urls.append(u2)
            seen.add(u2)

        for m in re.finditer(r"https?://[^\s]+", msg, re.I):
            _add(m.group(0))

        for name, url in self.SITE_MAP.items():
            if name in msg_lower:
                _add(url)

        if urls:
            return urls
        
        for prefix in ["open ", "launch ", "go to ", "visit ", "can you open "]:

            if prefix in msg_lower:
                rest = msg_lower.split(prefix, 1)[-1].replace(" for me", "").strip().rstrip(".!?")

                if rest:
                    for p in re.split(r"\s+and\s+|\s*,\s*", rest):
                        p = p.strip()

                        if p in self.SITE_MAP:
                            _add(self.SITE_MAP[p])

                        elif p and "." in p:
                            _add(p)

                        elif p:
                            _add("https://www." + p + ".com")

                break

        return urls if urls else ["https://www.google.com"]

    def _extract_play_query(self, msg: str) -> str:

        cleaned = self._strip_filler(msg)
        lower = cleaned.lower()

        m = re.search(r'^(.+?)\s+(?:can you|could you|please)\s+play\s+(?:that|it|this)\b', lower)

        if m:
            result = cleaned[:m.end(1)].strip().rstrip(".!?,")
            if result:
                return result

        m = re.search(
            r'(?:can you|could you|please)\s+play\s+(?:the\s+|a\s+|some\s+|me\s+)?(.+?)(?:\s+on\s+youtube|\s+for\s+me|\s+please\s*)?\s*[.!?]*$',
            lower,
        )

        if m:
            result = cleaned[m.start(1):m.end(1)].strip().rstrip(".!?,")
            if result and result.lower() not in ("that", "it", "this", "something"):
                return result

        m = re.search(
            r'play\s+(?:the\s+|a\s+|some\s+|me\s+)?(.+?)(?:\s+on\s+youtube|\s+for\s+me|\s+please\s*)?\s*[.!?]*$',
            lower,
        )
        
        if m:
            result = cleaned[m.start(1):m.end(1)].strip().rstrip(".!?,")
            if result and result.lower() not in ("that", "it", "this", "something"):
                return result

        for p in ["play ", "play the ", "play some ", "play a "]:
            if lower.startswith(p):
                return cleaned[len(p):].strip().rstrip(".!?")

        return cleaned.strip()

    def _extract_image_prompt(self, msg: str) -> str:

        m, lower = msg.strip(), msg.lower()
        extracted = None

        for p in ["generate ", "draw ", "create ", "make me ", "make a ", "picture of ", "image of ", "generator image of "]:
            if lower.startswith(p):
                extracted = m[len(p):].strip().rstrip(".!?")
                break

            if p in lower:
                extracted = m[lower.find(p) + len(p):].strip().rstrip(".!?")
                break

        if not extracted:
            return m
        
        boundaries = [
            r"\s+and\s+write\s", r"\s+and\s+open\s", r"\s+and\s+generate\s",
            r"\s+and\s+draw\s", r"\s+and\s+play\s", r"\s+and\s+search\s",
            r"\s+and\s+launch\s", r"\s+and\s+go\s+to\s", r"\s+and\s+visit\s",
        ]

        for b in boundaries:
            match = re.search(b, extracted.lower(), re.I)

            if match:
                extracted = extracted[:match.start()].strip().rstrip(".!?,")
                break

        return extracted.strip() if extracted.strip() else m

    def _extract_search_query(self, msg: str) -> str:

        cleaned = self._strip_filler(msg)
        lower = cleaned.lower()

        for p in ["search youtube for ", "search youtube ", "youtube search for ",
                   "search on youtube for ", "search on youtube ",
                   "search google for ", "search on google for ", "search on google ",
                   "search for ", "look up ", "find me ", "find ",
                   "google search for ", "google search ", "google "]:
            
            if p in lower:
                rest = cleaned[lower.find(p) + len(p):].strip().rstrip(".!?")
                return rest if rest else cleaned.strip()

        m = re.search(
            r'(?:can you|could you|please)\s+search\s+(?:for\s+)?(.+?)(?:\s+on\s+(?:youtube|google)|\s+for\s+me|\s+please\s*)?\s*[.!?]*$',
            lower,
        )

        if m:
            result = cleaned[m.start(1):m.end(1)].strip().rstrip(".!?,")
            if result:
                return result

        m = re.search(r'^(.+?)\s+on\s+(?:youtube|google)\s*[.!?]*$', lower)

        if m:
            result = cleaned[:m.end(1)].strip().rstrip(".!?,")

            if result:
                result2 = re.sub(
                    r'^(?:can you |could you |please )?(?:play|search|find|look up)\s+(?:the\s+|a\s+|some\s+|me\s+)?',
                    '', result, flags=re.I
                ).strip()
                return result2 if result2 else result

        stripped = re.sub(
            r'^(?:can you |could you |please )?(?:play|search|find|look up)\s+(?:the\s+|a\s+|some\s+|me\s+)?',
            '', lower, flags=re.I
        ).strip()

        stripped = re.sub(r'\s+on\s+(?:youtube|google)\s*[.!?]*$', '', stripped, flags=re.I).strip()
        stripped = re.sub(r'\s+(?:for me|please)\s*[.!?]*$', '', stripped, flags=re.I).strip()

        if stripped and stripped != lower:
            return stripped.rstrip(".!?,")
        return cleaned.strip()

    def _extract_content_prompt(self, msg: str) -> str:

        m, lower = msg.strip(), msg.lower()
        boundaries = [
            r"\s+and\s+open\s", r"\s+and\s+generate\s", r"\s+and\s+draw\s",
            r"\s+and\s+play\s", r"\s+and\s+search\s", r"\s+and\s+launch\s",
            r"\s+and\s+go\s+to\s", r"\s+and\s+visit\s",
        ]

        triggers = [
            "write application", "write an application", "write a application",
            "write a letter", "write letter", "draft a letter", "draft letter",
            "write an essay", "write essay", "write a poem", "write poem",
            "write a song", "write song", "compose a", "write the following",
            "write ", "draft ", "compose ",
        ]

        best_start = -1
        best_trigger = ""

        for t in triggers:
            pos = lower.find(t)
            if pos >= 0 and (best_start < 0 or pos < best_start):
                best_start = pos
                best_trigger = t

        if best_start < 0:
            return m
        
        segment = m[best_start:].strip()
        segment_lower = segment.lower()

        for b in boundaries:
            match = re.search(b, segment_lower, re.I)

            if match:
                segment = segment[:match.start()].strip().rstrip(".!?,")
                break
            
        segment = segment.rstrip(".!?,").strip()
        return segment if segment else m
</file>

<file path="JARVIS/app/services/chat_service.py">
import base64
import json
import logging
import time
from pathlib import Path
from typing import List, Optional, Dict, Iterator, Any, Union
import uuid
import threading
from config import CHATS_DATA_DIR, CAMERA_CAPTURES_DIR, MAX_CHAT_HISTORY_TURNS, GROQ_API_KEYS
from app.models import ChatMessage
from app.services.groq_service import GroqService
from app.services.realtime_service import RealtimeGroqService
from app.services.brain_service import BrainService
from app.services.decision_types import ( CATEGORY_GENERAL, CATEGORY_REALTIME, CATEGORY_CAMERA, CATEGORY_TASK, CATEGORY_MIXED, HEAVY_INTENTS, INSTANT_INTENTS)
from app.services.task_executor import TaskExecutor, TaskResponse
from app.services.task_manager import TaskManager
from app.services.vision_service import VisionService
from app.utils.key_rotation import get_next_key_pair

CAMERA_BYPASS_TOKEN = "TTCAMTOKENTT"

def _save_camera_image(img_base64: str, session_id: str) -> Optional[Path]:

    if not img_base64 or not CAMERA_CAPTURES_DIR:
        return None
    
    raw = img_base64.split(",", 1)[-1] if "," in img_base64 else img_base64

    try:

        data = base64.b64decode(raw)
        if len(data) < 1000:
            logger.warning("[VISION] Captured image very small (%d bytes), may be invalid", len(data))
        ts = time.strftime("%Y%m%d_%H%M%S", time.localtime())
        safe_id = (session_id or "").replace("/", "_")[:16] or "unknown"
        filename = f"cam_{safe_id}_{ts}.jpg"
        path = CAMERA_CAPTURES_DIR / filename
        path.write_bytes(data)
        logger.info("[VISION] Saved camera capture: %s (%d bytes) -> %s", path.name, len(data), path)
        return path
    
    except Exception as e:
        logger.warning("[VISION] Failed to save camera image: %s", e)
        return None

logger = logging.getLogger("J.A.R.V.I.S")
JARVIS_BRAIN_SEARCH_TIMEOUT = 15
SAVE_EVERY_N_CHUNKS = 5

class ChatService:

    def __init__(
        self,
        groq_service: GroqService,
        realtime_service: RealtimeGroqService = None,
        brain_service=None,
        task_executor: TaskExecutor = None,
        vision_service: VisionService = None,
        task_manager: TaskManager = None,
    ):
        
        self.groq_service = groq_service
        self.realtime_service = realtime_service
        self.brain_service = brain_service
        self.task_executor = task_executor
        self.vision_service = vision_service
        self.task_manager = task_manager
        self.sessions: Dict[str, List[ChatMessage]] = {}
        self._save_lock = threading.Lock()

    def load_session_from_disk(self, session_id: str) -> bool:

        safe_session_id = session_id.replace("-", "").replace(" ", "_")
        filename = f"chat_{safe_session_id}.json"
        filepath = CHATS_DATA_DIR / filename

        if not filepath.exists():
            return False

        try:
            with open(filepath, "r", encoding="utf-8") as f:
                chat_dict = json.load(f)

            messages = []

            for msg in chat_dict.get("messages", []):
                if not isinstance(msg, dict):
                    continue
                role = msg.get("role")
                role = role if role in ("user", "assistant") else "user"
                content = msg.get("content")
                content = content if isinstance(content, str) else str(content or "")
                messages.append(ChatMessage(role=role, content=content))

            self.sessions[session_id] = messages
            return True
        
        except Exception as e:
            logger.warning("Failed to load session %s from disk: %s", session_id, e)
            return False

    def validate_session_id(self, session_id: str) -> bool:

        if not session_id or not session_id.strip():
            return False
        
        if "\0" in session_id:
            return False

        if ".." in session_id or "/" in session_id or "\\" in session_id:
            return False
        
        if len(session_id) > 255:
            return False
        
        return True

    def get_or_create_session(self, session_id: Optional[str] = None) -> str:

        t0 = time.perf_counter()

        if not session_id:
            new_session_id = str(uuid.uuid4())
            self.sessions[new_session_id] = []
            logger.info("[TIMING] session_get_or_create: %.3fs (new)", time.perf_counter() - t0)
            return new_session_id

        if not self.validate_session_id(session_id):
            raise ValueError(
                f"Invalid session_id format: {session_id}. Session ID must be non-empty, "
                "not contain path traversal characters, and be under 255 characters.")

        if session_id in self.sessions:
            logger.info("[TIMING] session_get_or_create: %.3fs (memory)", time.perf_counter() - t0)
            return session_id

        if self.load_session_from_disk(session_id):
            logger.info("[TIMING] session_get_or_create: %.3fs (disk)", time.perf_counter() - t0)
            return session_id

        self.sessions[session_id] = []
        logger.info("[TIMING] session_get_or_create: %.3fs (new_id)", time.perf_counter() - t0)
        return session_id

    def add_message(self, session_id: str, role: str, content: str):

        if session_id not in self.sessions:
            self.sessions[session_id] = []
        self.sessions[session_id].append(ChatMessage(role=role, content=content))

    def get_chat_history(self, session_id: str) -> List[ChatMessage]:
        return self.sessions.get(session_id, [])

    def format_history_for_llm(self, session_id: str, exclude_last: bool = False) -> List[tuple]:
        messages = self.get_chat_history(session_id)
        history = []
        messages_to_process = messages[:-1] if exclude_last and messages else messages

        i = 0
        while i < len(messages_to_process) - 1:
            user_msg = messages_to_process[i]
            ai_msg = messages_to_process[i + 1]

            if user_msg.role == "user" and ai_msg.role == "assistant":
                u_content = user_msg.content if isinstance(user_msg.content, str) else str(user_msg.content or "")
                a_content = ai_msg.content if isinstance(ai_msg.content, str) else str(ai_msg.content or "")
                history.append((u_content, a_content))
                i += 2

            else:
                i += 1

        if len(history) > MAX_CHAT_HISTORY_TURNS:
            history = history[-MAX_CHAT_HISTORY_TURNS:]
        return history

    def process_message(self, session_id: str, user_message: str) -> str:
        logger.info("[GENERAL] Session: %s | User: %.200s", session_id[:12], user_message)
        self.add_message(session_id, "user", user_message)
        chat_history = self.format_history_for_llm(session_id, exclude_last=True)
        logger.info("[GENERAL] History pairs sent to LLM: %d", len(chat_history))
        _, chat_idx = get_next_key_pair(len(GROQ_API_KEYS), need_brain=False)
        response = self.groq_service.get_response(question=user_message, chat_history=chat_history, key_start_index=chat_idx)
        self.add_message(session_id, "assistant", response)
        logger.info("[GENERAL] Response length: %d chars | Preview: %.120s", len(response), response)
        return response

    def process_realtime_message(self, session_id: str, user_message: str) -> str:

        if not self.realtime_service:
            raise ValueError("Realtime service is not initialized. Cannot process realtime queries.")
        
        logger.info("[REALTIME] Session: %s | User: %.200s", session_id[:12], user_message)
        self.add_message(session_id, "user", user_message)
        chat_history = self.format_history_for_llm(session_id, exclude_last=True)
        logger.info("[REALTIME] History pairs sent to LLM: %d", len(chat_history))
        _, chat_idx = get_next_key_pair(len(GROQ_API_KEYS), need_brain=False)
        response = self.realtime_service.get_response(question=user_message, chat_history=chat_history, key_start_index=chat_idx)
        self.add_message(session_id, "assistant", response)
        logger.info("[REALTIME] Response length: %d chars | Preview: %.120s", len(response), response)
        return response

    def process_message_stream(
        self, session_id: str, user_message: str
    ) -> Iterator[Union[str, Dict[str, Any]]]:
        logger.info("[GENERAL-STREAM] Session: %s | User: %.200s", session_id[:12], user_message)
        self.add_message(session_id, "user", user_message)
        self.add_message(session_id, "assistant", "")
        chat_history = self.format_history_for_llm(session_id, exclude_last=True)
        logger.info("[GENERAL-STREAM] History pairs sent to LLM: %d", len(chat_history))

        yield {"_activity": {"event": "query_detected", "message": user_message}}
        yield {"_activity": {"event": "routing", "route": "general"}}
        yield {"_activity": {"event": "streaming_started", "route": "general"}}

        _, chat_idx = get_next_key_pair(len(GROQ_API_KEYS), need_brain=False)
        chunk_count = 0
        t0 = time.perf_counter()

        try:

            for chunk in self.groq_service.stream_response(
                question=user_message, chat_history=chat_history, key_start_index=chat_idx
            ):
                
                if isinstance(chunk, dict):
                    yield chunk
                    continue

                if chunk_count == 0:
                    elapsed_ms = int((time.perf_counter() - t0) * 1000)
                    yield {"_activity": {"event": "first_chunk", "route": "general", "elapsed_ms": elapsed_ms}}
                
                self.sessions[session_id][-1].content += chunk
                chunk_count += 1

                if chunk_count % SAVE_EVERY_N_CHUNKS == 0:
                    self.save_chat_session(session_id, log_timing=False)
                yield chunk

        finally:
            final_response = self.sessions[session_id][-1].content
            logger.info("[GENERAL-STREAM] Completed | Chunks: %d | Response length: %d chars", chunk_count, len(final_response))
            self.save_chat_session(session_id)

    def process_realtime_message_stream(
        self, session_id: str, user_message: str
    ) -> Iterator[Union[str, Dict[str, Any]]]:
        
        if not self.realtime_service:
            raise ValueError("Realtime service is not initialized.")
        
        logger.info("[REALTIME-STREAM] Session: %s | User: %.200s", session_id[:12], user_message)
        self.add_message(session_id, "user", user_message)
        self.add_message(session_id, "assistant", "")
        chat_history = self.format_history_for_llm(session_id, exclude_last=True)
        logger.info("[REALTIME-STREAM] History pairs sent to LLM: %d", len(chat_history))
        yield {"_activity": {"event": "query_detected", "message": user_message}}
        yield {"_activity": {"event": "routing", "route": "realtime"}}
        yield {"_activity": {"event": "streaming_started", "route": "realtime"}}
        _, chat_idx = get_next_key_pair(len(GROQ_API_KEYS), need_brain=False)
        chunk_count = 0
        t0 = time.perf_counter()

        try:
            for chunk in self.realtime_service.stream_response(
                question=user_message, chat_history=chat_history, key_start_index=chat_idx
            ):
                
                if isinstance(chunk, dict):
                    yield chunk
                    continue

                if chunk_count == 0:
                    elapsed_ms = int((time.perf_counter() - t0) * 1000)
                    yield {"_activity": {"event": "first_chunk", "route": "realtime", "elapsed_ms": elapsed_ms}}
                
                self.sessions[session_id][-1].content += chunk
                chunk_count += 1

                if chunk_count % SAVE_EVERY_N_CHUNKS == 0:
                    self.save_chat_session(session_id, log_timing=False)
                yield chunk

        finally:
            final_response = self.sessions[session_id][-1].content
            logger.info("[REALTIME-STREAM] Completed | Chunks: %d | Response length: %d chars", chunk_count, len(final_response))
            self.save_chat_session(session_id)

    def process_jarvis_message_stream(
        self, session_id: str, user_message: str, imgbase64: Optional[str] = None
    ) -> Iterator[Union[str, Dict[str, Any]]]:
        
        t0_jarvis = time.perf_counter()
        logger.info("[JARVIS-STREAM] Session: %s | User: %.200s | img: %s",
                    session_id[:12], user_message[:80], "yes" if imgbase64 else "no")
        self.add_message(session_id, "user", user_message)
        self.add_message(session_id, "assistant", "")
        chat_history = self.format_history_for_llm(session_id, exclude_last=True)

        yield {"_activity": {"event": "query_detected", "message": user_message}}

        if imgbase64 and CAMERA_BYPASS_TOKEN in (user_message or ""):
            yield {"_activity": {"event": "decision", "query_type": "camera", "reasoning": "Image attached", "elapsed_ms": 0}}
            yield {"_activity": {"event": "routing", "route": "vision"}}
            yield {"_activity": {"event": "vision_analyzing", "message": "Analyzing image..."}}
            yield {"_activity": {"event": "streaming_started", "route": "vision"}}
            prompt = (user_message or "").replace(CAMERA_BYPASS_TOKEN, "").strip() or "What do you see in this image?"
            clean_msg = prompt or "What do you see in this image?"

            if self.sessions[session_id]:
                self.sessions[session_id][-2].content = clean_msg
            _save_camera_image(imgbase64, session_id)

            if self.vision_service:
                text = self.vision_service.describe_image(imgbase64, prompt)

            else:
                text = "Vision is not available. Please set GROQ_API_KEY."

            self.sessions[session_id][-1].content = text
            yield text
            self.save_chat_session(session_id)
            return

        brain_idx, chat_idx = get_next_key_pair(len(GROQ_API_KEYS), need_brain=bool(self.brain_service))
        category = CATEGORY_GENERAL
        primary_elapsed_ms = 0
        primary_method = "default"

        if self.brain_service:
            category, primary_method, primary_elapsed_ms = self.brain_service.classify_primary(
                user_message, chat_history, key_index=brain_idx if brain_idx is not None else 0
            )

        yield {"_activity": {"event": "decision", "query_type": category, "reasoning": primary_method.capitalize(), "elapsed_ms": primary_elapsed_ms}}

        if category == CATEGORY_CAMERA:
            yield {"_activity": {"event": "routing", "route": "camera"}}

            if imgbase64:
                yield {"_activity": {"event": "vision_analyzing", "message": "Analyzing image..."}}
                yield {"_activity": {"event": "streaming_started", "route": "vision"}}
                _save_camera_image(imgbase64, session_id)

                if self.vision_service:
                    text = self.vision_service.describe_image(imgbase64, user_message)

                else:
                    text = "Vision is not available. Please set GROQ_API_KEY."
                    
            else:
                text = "Let me take a look..."
                yield {"_actions": {"wopens": [], "plays": [], "images": [], "contents": [],
                                     "googlesearches": [], "youtubesearches": [],
                                     "cam": {"action": "open_and_capture", "resend_message": user_message}}}
                yield {"_activity": {"event": "actions_emitted", "message": "camera (auto-capture)"}}

            self.sessions[session_id][-1].content = text
            yield text
            self.save_chat_session(session_id)
            elapsed_jarvis = time.perf_counter() - t0_jarvis
            logger.info("[JARVIS-STREAM] Camera flow complete in %.2fs", elapsed_jarvis)
            return

        if category in (CATEGORY_TASK, CATEGORY_MIXED):
            yield {"_activity": {"event": "routing", "route": "task" if category == CATEGORY_TASK else "mixed"}}

            task_types = []
            task_elapsed_ms = 0
            task_method = "default"
            if self.brain_service:
                task_types, task_method, task_elapsed_ms = self.brain_service.classify_task(
                    user_message, chat_history, key_index=brain_idx if brain_idx is not None else 0
                )
                
            task_name = ", ".join(task_types[:3]) if task_types else "task"
            yield {"_activity": {"event": "intent_classified", "intent": task_name}}

            intents = self.brain_service.extract_task_payloads(user_message, task_types, chat_history) if self.brain_service else []

            instant_intents = [(t, p) for t, p in intents if t not in HEAVY_INTENTS]
            heavy_intents = [(t, p) for t, p in intents if t in HEAVY_INTENTS]

            instant_response = TaskResponse()

            if self.task_executor and instant_intents:
                yield {"_activity": {"event": "tasks_executing", "message": f"Running instant tasks..."}}
                instant_response = self.task_executor.execute(instant_intents, chat_history)
                yield {"_activity": {"event": "tasks_completed", "message": "Instant tasks done"}}

                has_instant_actions = (
                    instant_response.wopens or instant_response.plays or
                    instant_response.googlesearches or instant_response.youtubesearches or
                    instant_response.cam
                )

                if has_instant_actions:
                    actions = {
                        "wopens": instant_response.wopens,
                        "plays": instant_response.plays,
                        "images": [],
                        "contents": [],
                        "googlesearches": instant_response.googlesearches,
                        "youtubesearches": instant_response.youtubesearches,
                        "cam": instant_response.cam,
                    }

                    action_summary = []
                    if instant_response.wopens: action_summary.append("open")
                    if instant_response.plays: action_summary.append("play")
                    if instant_response.googlesearches or instant_response.youtubesearches: action_summary.append("search")
                    if instant_response.cam: action_summary.append("camera")
                    yield {"_activity": {"event": "actions_emitted", "message": ", ".join(action_summary) or "actions"}}
                    yield {"_actions": actions}

            bg_task_ids = []

            if self.task_manager and heavy_intents:
                yield {"_activity": {"event": "tasks_executing", "message": "Dispatching background tasks..."}}
                
                for intent_type, payload in heavy_intents:
                    task_id = self.task_manager.submit(intent_type, payload, chat_history)
                    bg_task_ids.append({"task_id": task_id, "type": intent_type, "label": payload.get("prompt", payload.get("message", ""))[:100]})
                
                yield {"_activity": {"event": "background_dispatched", "message": f"{len(bg_task_ids)} task(s) in background"}}
            
            elif not self.task_manager and heavy_intents:
                yield {"_activity": {"event": "tasks_executing", "message": f"Running {task_name}..."}}
                sync_response = self.task_executor.execute(heavy_intents, chat_history) if self.task_executor else TaskResponse()
                yield {"_activity": {"event": "tasks_completed", "message": "Tasks completed"}}
                
                if sync_response.images or sync_response.contents:
                    actions = {
                        "wopens": [], "plays": [],
                        "images": sync_response.images,
                        "contents": sync_response.contents,
                        "googlesearches": [], "youtubesearches": [],
                        "cam": None,
                    }
                    yield {"_actions": actions}
                instant_response.text = instant_response.text or sync_response.text

            if category == CATEGORY_MIXED:
                yield {"_activity": {"event": "streaming_started", "route": "mixed"}}
                stream_svc = self.realtime_service if self.realtime_service else self.groq_service
                chunk_count = 0
                t0 = time.perf_counter()

                try:
                    for chunk in stream_svc.stream_response(
                        question=user_message, chat_history=chat_history, key_start_index=chat_idx
                    ):
                        
                        if isinstance(chunk, dict):
                            yield chunk
                            continue

                        if chunk_count == 0:
                            elapsed_ms = int((time.perf_counter() - t0) * 1000)
                            yield {"_activity": {"event": "first_chunk", "route": "mixed", "elapsed_ms": elapsed_ms}}
                        
                        self.sessions[session_id][-1].content += chunk
                        chunk_count += 1
                        
                        if chunk_count % SAVE_EVERY_N_CHUNKS == 0:
                            self.save_chat_session(session_id, log_timing=False)
                        yield chunk
                        
                finally:
                    self.save_chat_session(session_id)

                if bg_task_ids:
                    yield {"_background_tasks": bg_task_ids}
                elapsed_jarvis = time.perf_counter() - t0_jarvis
                logger.info("[JARVIS-STREAM] Mixed flow complete in %.2fs | tasks: %s", elapsed_jarvis, task_types)
                return

            text_parts = []

            if instant_response.text:
                text_parts.append(instant_response.text)

            if bg_task_ids:
                bg_labels = []

                for bt in bg_task_ids:
                    if bt["type"] == "generate image":
                        bg_labels.append("image generation")
                    elif bt["type"] == "content":
                        bg_labels.append("content writing")
                    else:
                        bg_labels.append(bt["type"])

                text_parts.append(f"I'm working on the {', '.join(bg_labels)} in the background. I'll open it for you when it's ready.")

            text = " ".join(text_parts) if text_parts else "Done."
            self.sessions[session_id][-1].content = text
            yield text

            if bg_task_ids:
                yield {"_background_tasks": bg_task_ids}

            self.save_chat_session(session_id)
            elapsed_jarvis = time.perf_counter() - t0_jarvis
            logger.info("[JARVIS-STREAM] Task flow complete in %.2fs | tasks: %s | bg: %d", elapsed_jarvis, task_types, len(bg_task_ids))
            return

        use_realtime = category == CATEGORY_REALTIME and self.realtime_service
        route_name = "realtime" if use_realtime else "general"
        yield {"_activity": {"event": "routing", "route": route_name}}
        yield {"_activity": {"event": "streaming_started", "route": route_name}}

        stream_svc = self.realtime_service if use_realtime else self.groq_service
        chunk_count = 0
        t0 = time.perf_counter()

        try:
            for chunk in stream_svc.stream_response(
                question=user_message, chat_history=chat_history, key_start_index=chat_idx
            ):
                
                if isinstance(chunk, dict):
                    yield chunk
                    continue

                if chunk_count == 0:
                    elapsed_ms = int((time.perf_counter() - t0) * 1000)
                    yield {"_activity": {"event": "first_chunk", "route": route_name, "elapsed_ms": elapsed_ms}}
                
                self.sessions[session_id][-1].content += chunk
                chunk_count += 1
                if chunk_count % SAVE_EVERY_N_CHUNKS == 0:
                    self.save_chat_session(session_id, log_timing=False)
                yield chunk

        finally:
            self.save_chat_session(session_id)

        elapsed_jarvis = time.perf_counter() - t0_jarvis
        logger.info("[JARVIS-STREAM] %s flow complete in %.2fs | chunks: %d", route_name, elapsed_jarvis, chunk_count)

    def save_chat_session(self, session_id: str, log_timing: bool = True):

        if session_id not in self.sessions or not self.sessions[session_id]:
            return

        messages = self.sessions[session_id]

        safe_session_id = session_id.replace("-", "").replace(" ", "_")
        filename = f"chat_{safe_session_id}.json"
        filepath = CHATS_DATA_DIR / filename

        chat_dict = {
            "session_id": session_id,
            "messages": [{"role": msg.role, "content": msg.content} for msg in messages]
        }

        max_retries = 3
        last_exc = None

        for attempt in range(max_retries):
            
            try:
                with self._save_lock:
                    t0 = time.perf_counter() if log_timing else 0
                    with open(filepath, "w", encoding="utf-8") as f:
                        json.dump(chat_dict, f, indent=2, ensure_ascii=False)

                    if log_timing:
                        logger.info("[TIMING] save_session_json: %.3fs", time.perf_counter() - t0)
                    return
                
            except OSError as e:
                last_exc = e
                if attempt < max_retries - 1:
                    time.sleep(0.1 * (attempt + 1))

            except Exception as e:
                logger.error("Failed to save chat session %s to disk: %s", session_id, e)
                return
            
        logger.error("Failed to save chat session %s after %d retries: %s", session_id, max_retries, last_exc)
</file>

<file path="JARVIS/app/services/decision_types.py">
CATEGORY_GENERAL = "general"
CATEGORY_REALTIME = "realtime"
CATEGORY_CAMERA = "camera"
CATEGORY_TASK = "task"
CATEGORY_MIXED = "mixed"
INTENT_OPEN = "open"
INTENT_PLAY = "play"
INTENT_CAMERA = "camera"
INTENT_OPEN_WEBCAM = "open webcam"
INTENT_CLOSE_WEBCAM = "close webcam"
INTENT_GENERATE_IMAGE = "generate image"
INTENT_CONTENT = "content"
INTENT_GOOGLE_SEARCH = "google search"
INTENT_YOUTUBE_SEARCH = "youtube search"
INTENT_CHAT = "chat"

HEAVY_INTENTS = {INTENT_GENERATE_IMAGE, INTENT_CONTENT}

INSTANT_INTENTS = {
    INTENT_OPEN, INTENT_PLAY, INTENT_CAMERA,
    INTENT_OPEN_WEBCAM, INTENT_CLOSE_WEBCAM,
    INTENT_GOOGLE_SEARCH, INTENT_YOUTUBE_SEARCH,
}

ROUTE_TO_INTENT = {
    "open": INTENT_OPEN,
    "play": INTENT_PLAY,
    "camera": INTENT_CAMERA,
    "open_webcam": INTENT_OPEN_WEBCAM,
    "close_webcam": INTENT_CLOSE_WEBCAM,
    "generate_image": INTENT_GENERATE_IMAGE,
    "content": INTENT_CONTENT,
    "google_search": INTENT_GOOGLE_SEARCH,
    "youtube_search": INTENT_YOUTUBE_SEARCH,
    "general": INTENT_CHAT,
    "realtime": INTENT_CHAT,
}
</file>

<file path="JARVIS/app/services/groq_service.py">
from typing import List, Optional, Iterator
from langchain_groq import ChatGroq
from langchain_core.prompts import ChatPromptTemplate, MessagesPlaceholder
from langchain_core.messages import HumanMessage, AIMessage
import logging
import time
from app.services.vector_store import VectorStoreService
from app.utils.time_info import get_time_information
from app.utils.retry import with_retry
from config import (
    GROQ_API_KEYS,
    GROQ_MODEL,
    JARVIS_SYSTEM_PROMPT,
    GENERAL_CHAT_ADDENDUM,
)

logger = logging.getLogger("J.A.R.V.I.S")
GROQ_REQUEST_TIMEOUT = 60

ALL_APIS_FAILED_MESSAGE = (
    "I'm unable to process your request at the moment. All API services are "
    "temporarily unavailable. Please try again in a few minutes."
)

class AllGroqApisFailedError(Exception):
    pass

def escape_curly_braces(text: str) -> str:
    if not text:
        return text
    return text.replace("{", "{{").replace("}", "}}")

_REPEAT_WINDOW = 100
_REPEAT_THRESHOLD = 3
_REPEAT_CHECK_INTERVAL = 200

def _detect_repetition_loop(text: str) -> bool:

    if len(text) < _REPEAT_WINDOW * _REPEAT_THRESHOLD:
        return False
    
    phrase = text[-_REPEAT_WINDOW:]
    return text.count(phrase) >= _REPEAT_THRESHOLD

def _truncate_at_repetition(text: str) -> str:

    if len(text) < _REPEAT_WINDOW * _REPEAT_THRESHOLD:
        return text

    phrase = text[-_REPEAT_WINDOW:]
    if text.count(phrase) < _REPEAT_THRESHOLD:
        return text

    first = text.find(phrase)
    second = text.find(phrase, first + 1)

    if second > first:
        return text[:second].rstrip()
    return text

def _is_rate_limit_error(exc: BaseException) -> bool:
    msg = str(exc).lower()
    return "429" in str(exc) or "rate limit" in msg or "tokens per day" in msg

def _log_timing(label: str, elapsed: float, extra: str = ""):
    msg = f"[TIMING] {label}: {elapsed:.3f}s"

    if extra:
        msg += f" ({extra})"
    logger.info(msg)

def _mask_api_key(key: str) -> str:

    if not key or len(key) <= 12:
        return "***masked***"
    return f"{key[:8]}...{key[-4:]}"

class GroqService:
    
    def __init__(self, vector_store_service: VectorStoreService):

        if not GROQ_API_KEYS:
            raise ValueError(
                "No Groq API keys configured. Set GROQ_API_KEY (and optionally GROQ_API_KEY_2, GROQ_API_KEY_3, ...) in .env"
            )

        self.llms = [
            ChatGroq(
                groq_api_key=key,
                model_name=GROQ_MODEL,
                temperature=0.5,
                max_tokens=1024,
                request_timeout=GROQ_REQUEST_TIMEOUT,
                model_kwargs={"frequency_penalty": 0.3},
            )
            for key in GROQ_API_KEYS
        ]

        self.vector_store_service = vector_store_service
        logger.info(f"Initialized GroqService with {len(GROQ_API_KEYS)} API key(s) (primary-first fallback)")

    def _invoke_llm(
        self,
        prompt: ChatPromptTemplate,
        messages: list,
        question: str,
        key_start_index: int = 0,
    ) -> str:
        
        n = len(self.llms)
        last_exc = None
        keys_tried = []

        for j in range(n):
            i = (key_start_index + j) % n
            keys_tried.append(i)
            masked_key = _mask_api_key(GROQ_API_KEYS[i])
            logger.info(f"Trying API key #{i + 1}/{n}: {masked_key}")

            def _invoke_with_key():
                chain = prompt | self.llms[i]
                return chain.invoke({"history": messages, "question": question})

            try:
                response = with_retry(
                    _invoke_with_key,
                    max_retries=2,
                    initial_delay=0.5,
                )

                if i > 0:
                    logger.info(f"Fallback successful: API key #{i + 1}/{n} succeeded: {masked_key}")

                text = response.content

                if _detect_repetition_loop(text):
                    logger.warning("[INVOKE] Repetition loop detected — truncating response (%d chars)", len(text))
                    text = _truncate_at_repetition(text)
                return text
            
            except Exception as e:
                last_exc = e

                if _is_rate_limit_error(e):
                    logger.warning(f"API key #{i + 1}/{n} rate limited: {masked_key}")

                else:
                    logger.warning(f"API key #{i + 1}/{n} failed: {masked_key} - {str(e)[:100]}")

                if i < n - 1:
                    logger.info(f"Falling back to next API key...")
                    continue

                break

        masked_all = ", ".join([_mask_api_key(GROQ_API_KEYS[j]) for j in keys_tried])
        logger.error(f"All {n} API key(s) failed. Tried: {masked_all}")
        raise AllGroqApisFailedError(ALL_APIS_FAILED_MESSAGE) from last_exc

    def _stream_llm(
        self,
        prompt: ChatPromptTemplate,
        messages: list,
        question: str,
        key_start_index: int = 0,
    ) -> Iterator[str]:
        
        n = len(self.llms)
        last_exc = None

        for j in range(n):
            i = (key_start_index + j) % n
            masked_key = _mask_api_key(GROQ_API_KEYS[i])
            logger.info(f"Streaming with API key #{i + 1}/{n}: {masked_key}")

            try:
                chain = prompt | self.llms[i]
                chunk_count = 0
                first_chunk_time = None
                stream_start = time.perf_counter()
                accumulated = ""
                last_check_len = 0
                repetition_stopped = False

                for chunk in chain.stream({"history": messages, "question": question}):
                    content = ""

                    if hasattr(chunk, "content"):
                        content = chunk.content or ""

                    elif isinstance(chunk, dict) and "content" in chunk:
                        content = chunk.get("content", "") or ""

                    if isinstance(content, str) and content:

                        if first_chunk_time is None:
                            first_chunk_time = time.perf_counter() - stream_start
                            _log_timing("first_chunk", first_chunk_time)

                        chunk_count += 1
                        accumulated += content

                        if len(accumulated) - last_check_len >= _REPEAT_CHECK_INTERVAL:
                            last_check_len = len(accumulated)

                            if _detect_repetition_loop(accumulated):
                                logger.warning("[STREAM] Repetition loop detected after %d chars — stopping", len(accumulated))
                                repetition_stopped = True
                                break

                        yield content

                total_stream = time.perf_counter() - stream_start
                _log_timing("groq_stream_total", total_stream, f"chunks: {chunk_count}{', TRUNCATED-REPETITION' if repetition_stopped else ''}")

                if i > 0 and chunk_count > 0:
                    logger.info(f"Fallback successful: API key #{i + 1}/{n} streamed: {masked_key}")
                return

            except Exception as e:

                last_exc = e
                if _is_rate_limit_error(e):
                    logger.warning(f"API key #{i + 1}/{n} rate limited: {masked_key}")

                else:
                    logger.warning(f"API key #{i + 1}/{n} failed: {masked_key} - {str(e)[:100]}")

                if i < n - 1:
                    logger.info("Falling back to next API key for stream...")
                    continue
                break

        logger.error(f"All {n} API key(s) failed during stream.")
        raise AllGroqApisFailedError(ALL_APIS_FAILED_MESSAGE) from last_exc

    def _build_prompt_and_messages(
        self,
        question: str,
        chat_history: Optional[List[tuple]] = None,
        extra_system_parts: Optional[List[str]] = None,
        mode_addendum: str = "",
    ) -> tuple:
        
        context = ""
        context_sources = []
        t0 = time.perf_counter()

        try:
            retriever = self.vector_store_service.get_retriever(k=5)

            context_docs = retriever.invoke(question)

            if context_docs:
                context = "\n".join([doc.page_content for doc in context_docs])

                context_sources = [doc.metadata.get("source", "unknown") for doc in context_docs]
                logger.info("[CONTEXT] Retrieved %d chunks from sources: %s", len(context_docs), context_sources)
            
            else:
                logger.info("[CONTEXT] No relevant chunks found for query")

        except Exception as retrieval_err:
            logger.warning("Vector store retrieval failed, using empty context: %s", retrieval_err)

        finally:
            _log_timing("vector_db", time.perf_counter() - t0)

        time_info = get_time_information()
        system_message = JARVIS_SYSTEM_PROMPT

        system_message += f"\n\nCurrent time and date: {time_info}"

        if context:
            system_message += f"\n\nRelevant context from your learning data and past conversations:\n{escape_curly_braces(context)}"

        if extra_system_parts:
            system_message += "\n\n" + "\n\n".join(extra_system_parts)

        if mode_addendum:
            system_message += f"\n\n{mode_addendum}"

        prompt = ChatPromptTemplate.from_messages([
            ("system", system_message),
            MessagesPlaceholder(variable_name="history"),
            ("human", "{question}"),
        ])

        messages = []

        if chat_history:
            for human_msg, ai_msg in chat_history:
                messages.append(HumanMessage(content=human_msg))
                messages.append(AIMessage(content=ai_msg))

        logger.info("[PROMPT] System message length: %d chars | History pairs: %d | Question: %.100s",
                     len(system_message), len(chat_history) if chat_history else 0, question)

        return prompt, messages

    def get_response(
        self,
        question: str,
        chat_history: Optional[List[tuple]] = None,
        key_start_index: int = 0,
    ) -> str:
        
        try:
            prompt, messages = self._build_prompt_and_messages(
                question, chat_history, mode_addendum=GENERAL_CHAT_ADDENDUM,
            )
            t0 = time.perf_counter()
            result = self._invoke_llm(prompt, messages, question, key_start_index=key_start_index)
            _log_timing("groq_api", time.perf_counter() - t0)
            logger.info("[RESPONSE] General chat | Length: %d chars | Preview: %.120s", len(result), result)
            return result
        
        except AllGroqApisFailedError:
            raise

        except Exception as e:
            raise Exception(f"Error getting response from Groq: {str(e)}") from e

    def stream_response(
        self,
        question: str,
        chat_history: Optional[List[tuple]] = None,
        key_start_index: int = 0,
    ) -> Iterator[str]:
        
        try:
            prompt, messages = self._build_prompt_and_messages(
                question, chat_history, mode_addendum=GENERAL_CHAT_ADDENDUM,
            )
            yield {"_activity": {"event": "context_retrieved", "message": "Retrieved relevant context from knowledge base"}}
            yield from self._stream_llm(prompt, messages, question, key_start_index=key_start_index)
        
        except AllGroqApisFailedError:
            raise
        
        except Exception as e:
            raise Exception(f"Error streaming response from Groq: {str(e)}") from e
</file>

<file path="JARVIS/app/services/realtime_service.py">
from typing import List, Optional, Iterator, Tuple, Any
from tavily import TavilyClient
import logging
import os
import time
from app.services.groq_service import GroqService, escape_curly_braces, AllGroqApisFailedError
from app.services.vector_store import VectorStoreService
from app.utils.retry import with_retry
from config import REALTIME_CHAT_ADDENDUM, GROQ_API_KEYS, GROQ_MODEL, INTENT_CLASSIFY_MODEL

logger = logging.getLogger("J.A.R.V.I.S")
GROQ_REQUEST_TIMEOUT_FAST = 15

_QUERY_EXTRACTION_PROMPT = (
    "You are a search query optimizer. Convert the user's message into a clean, focused "
    "web search query (max 10 words). Rules:\n"
    "- Remove filler words (you know, like, something, can you, tell me, search)\n"
    "- Add specifics: dates (today, 2026), event names, full names\n"
    "- For sports: include league name, team names, 'live score today'\n"
    "- For people: include full name + what user wants to know\n"
    "- Resolve references (him, that, it) from conversation history\n"
    "Output ONLY the search query. Nothing else."
)

class RealtimeGroqService(GroqService):

    def __init__(self, vector_store_service: VectorStoreService):
        super().__init__(vector_store_service)

        tavily_api_key = os.getenv("TAVILY_API_KEY", "")
        
        if tavily_api_key:
            self.tavily_client = TavilyClient(api_key=tavily_api_key)
            logger.info("Tavily search client initialized successfully")

        else:
            self.tavily_client = None
            logger.warning("TAVILY_API_KEY not set. Realtime search will be unavailable.")

        if GROQ_API_KEYS:
            from langchain_groq import ChatGroq
            self._fast_llm = ChatGroq(
                groq_api_key=GROQ_API_KEYS[0],
                model_name=INTENT_CLASSIFY_MODEL,
                temperature=0.0,
                request_timeout=GROQ_REQUEST_TIMEOUT_FAST,
                max_tokens=50,
            )

        else:
            self._fast_llm = None

    def _extract_search_query(
        self, question: str, chat_history: Optional[List[tuple]] = None
    ) -> str:
        
        if not self._fast_llm:
            return question

        q = question.strip()
        q_lower = q.lower()

        has_filler = any(p in q_lower for p in (
            " it ", " that ", " him ", " her ", " them ", " you know ",
            " something ", " like ", " going on ", " can you ", " tell me ",
            " search ", " right now", " please",
        ))

        if len(q) <= 30 and not has_filler:
            return q

        try:

            t0 = time.perf_counter()

            history_context = ""

            if chat_history:
                recent = chat_history[-3:]
                parts = []
                
                for h, a in recent:
                    parts.append(f"User: {h[:200]}")
                    parts.append(f"Assistant: {a[:200]}")
                history_context = "\n".join(parts)

            if history_context:
                full_prompt = (
                    f"{_QUERY_EXTRACTION_PROMPT}\n\n"
                    f"Recent conversation:\n{history_context}\n\n"
                    f"User's latest message: {question}\n\n"
                    f"Search query:"
                )

            else:
                full_prompt = (
                    f"{_QUERY_EXTRACTION_PROMPT}\n\n"
                    f"User's message: {question}\n\n"
                    f"Search query:"
                )

            response = self._fast_llm.invoke(full_prompt)
            extracted = response.content.strip().strip('"').strip("'")

            if extracted and 3 <= len(extracted) <= 200:
                logger.info(
                    "[REALTIME] Query extraction: '%s' -> '%s' (%.3fs)",
                    question[:80], extracted[:80], time.perf_counter() - t0,
                )
                return extracted

            logger.warning("[REALTIME] Query extraction returned unusable result, using raw question")
            return question

        except Exception as e:
            logger.warning("[REALTIME] Query extraction failed (%s), using raw question", e)
            return question

    def search_tavily(self, query: str, num_results: int = 5) -> str:

        if not self.tavily_client:
            logger.warning("Tavily client not initialized. TAVILY_API_KEY not set.")
            return ("", None)
        
        if not query or not str(query).strip():
            return ("", None)

        try:
            t0 = time.perf_counter()
            response = with_retry(
                lambda: self.tavily_client.search(
                    query=query,
                    search_depth="fast",
                    max_results=num_results,
                    include_answer=True,
                    include_raw_content=False,
                ),
                max_retries=3,
                initial_delay=1.0,
            )

            results = response.get("results", [])
            ai_answer = response.get("answer", "")

            if not results and not ai_answer:
                logger.warning("No Tavily search results for query: %s", query)
                return ("", None)

            payload: Optional[dict] = {
                "query": query,
                "answer": ai_answer,
                "results": [
                    {
                        "title": r.get("title", "No title"),
                        "content": (r.get("content") or "")[:300],
                        "url": r.get("url", ""),
                        "score": round(float(r.get("score", 0)), 2),
                    }
                    for r in results[:num_results]
                ],
            }

            parts = [f"=== WEB SEARCH RESULTS FOR: {query} ===\n"]

            if ai_answer:
                parts.append(f"AI-SYNTHESIZED ANSWER (use this as your primary source):\n{ai_answer}\n")

            if results:
                parts.append("INDIVIDUAL SOURCES:")

                for i, result in enumerate(results[:num_results], 1):
                    title = result.get("title", "No title")
                    content = result.get("content", "")
                    url = result.get("url", "")
                    score = result.get("score", 0)
                    parts.append(f"\n[Source {i}] (relevance: {score:.2f})")
                    parts.append(f"Title: {title}")

                    if content:
                        parts.append(f"Content: {content}")

                    if url:
                        parts.append(f"URL: {url}")

            parts.append("\n=== END SEARCH RESULTS ===")
            formatted = "\n".join(parts)

            logger.info(
                "[TAVILY] %d results, AI answer: %s, formatted: %d chars (%.3fs)",
                len(results), "yes" if ai_answer else "no",
                len(formatted), time.perf_counter() - t0,
            )
            return (formatted, payload)

        except Exception as e:
            logger.error("Error performing Tavily search: %s", e)
            return ("", None)

    def get_response(self, question: str, chat_history: Optional[List[tuple]] = None, key_start_index: int = 0) -> str:
        
        try:
            search_query = self._extract_search_query(question, chat_history)
            logger.info("[REALTIME] Searching Tavily for: %s", search_query)
            formatted_results, _ = self.search_tavily(search_query, num_results=5)
            
            if formatted_results:
                logger.info("[REALTIME] Tavily returned results (length: %d chars)", len(formatted_results))
            
            else:
                logger.warning("[REALTIME] Tavily returned no results for: %s", search_query)

            extra_parts = [escape_curly_braces(formatted_results)] if formatted_results else None
            prompt, messages = self._build_prompt_and_messages(
                question, chat_history,
                extra_system_parts=extra_parts,
                mode_addendum=REALTIME_CHAT_ADDENDUM,
            )

            t0 = time.perf_counter()
            response_content = self._invoke_llm(prompt, messages, question, key_start_index=key_start_index)
            logger.info("[TIMING] groq_api: %.3fs", time.perf_counter() - t0)
            logger.info(
                "[RESPONSE] Realtime chat | Length: %d chars | Preview: %.120s",
                len(response_content), response_content,
            )
            return response_content

        except AllGroqApisFailedError:
            raise

        except Exception as e:
            logger.error("Error in realtime get_response: %s", e, exc_info=True)
            raise

    def prefetch_web_search(
        self, question: str, chat_history: Optional[List[tuple]] = None
    ) -> Tuple[str, Optional[dict]]:
        
        try:
            t0 = time.perf_counter()
            search_query = self._extract_search_query(question, chat_history)
            logger.info("[REALTIME] Pre-fetch: extracted query '%s' in %.3fs", search_query[:60], time.perf_counter() - t0)
            formatted_results, payload = self.search_tavily(search_query, num_results=5)

            if formatted_results:
                logger.info("[REALTIME] Pre-fetch: Tavily returned %d chars in %.3fs total",
                            len(formatted_results), time.perf_counter() - t0)
            return (formatted_results or "", payload)
        
        except Exception as e:
            logger.warning("[REALTIME] Pre-fetch failed: %s", e)
            return ("", None)

    def stream_response(self, question: str, chat_history: Optional[List[tuple]] = None, key_start_index: int = 0) -> Iterator[Any]:
        
        try:
            yield {"_activity": {"event": "extracting_query", "message": "Extracting search query..."}}
            search_query = self._extract_search_query(question, chat_history)
            logger.info("[REALTIME] Searching Tavily for: %s", search_query)
            yield {"_activity": {"event": "searching_web", "query": search_query, "message": f"Searching web for: {search_query}"}}

            formatted_results, payload = self.search_tavily(search_query, num_results=5)
            num_results = len(payload.get("results", [])) if payload else 0
            
            if formatted_results:
                logger.info("[REALTIME] Tavily returned results (length: %d chars)", len(formatted_results))
                yield {"_activity": {"event": "search_completed", "message": f"Search completed: {num_results} results, {len(formatted_results)} chars of context"}}
            
            else:
                logger.warning("[REALTIME] Tavily returned no results for: %s", search_query)
                yield {"_activity": {"event": "search_completed", "message": "No search results found"}}

            if payload:
                yield {"_search_results": payload}

            extra_parts = [escape_curly_braces(formatted_results)] if formatted_results else None
            prompt, messages = self._build_prompt_and_messages(
                question, chat_history,
                extra_system_parts=extra_parts,
                mode_addendum=REALTIME_CHAT_ADDENDUM,
            )
            yield from self._stream_llm(prompt, messages, question, key_start_index=key_start_index)
            logger.info("[REALTIME] Stream completed for: %s", search_query)

        except AllGroqApisFailedError:
            raise

        except Exception as e:
            logger.error("Error in realtime stream_response: %s", e, exc_info=True)
            raise

    def stream_response_with_prefetched(
        self,
        question: str,
        chat_history: Optional[List[tuple]] = None,
        formatted_results: Optional[str] = None,
        payload: Optional[dict] = None,
        key_start_index: int = 0,
    ) -> Iterator[Any]:
        
        try:
            extra_parts = [escape_curly_braces(formatted_results)] if formatted_results else None
            prompt, messages = self._build_prompt_and_messages(
                question, chat_history,
                extra_system_parts=extra_parts,
                mode_addendum=REALTIME_CHAT_ADDENDUM,
            )
            yield from self._stream_llm(prompt, messages, question, key_start_index=key_start_index)
            logger.info("[REALTIME] Stream completed (pre-fetched results)")

        except AllGroqApisFailedError:
            raise
        
        except Exception as e:
            logger.error("Error in realtime stream_response_with_prefetched: %s", e, exc_info=True)
            raise
</file>

<file path="JARVIS/app/services/task_executor.py">
import logging
import time
from dataclasses import dataclass, field
from typing import List, Optional
from urllib.parse import quote, urlparse
from concurrent.futures import ThreadPoolExecutor, as_completed, TimeoutError as FuturesTimeoutError
from config import TASK_EXECUTION_TIMEOUT
from app.services.decision_types import (
    INTENT_OPEN, INTENT_PLAY, INTENT_CAMERA,
    INTENT_OPEN_WEBCAM, INTENT_CLOSE_WEBCAM,
    INTENT_GENERATE_IMAGE, INTENT_CONTENT,
    INTENT_GOOGLE_SEARCH, INTENT_YOUTUBE_SEARCH, INTENT_CHAT,
)

logger = logging.getLogger("J.A.R.V.I.S")

@dataclass
class TaskResponse:
    text: str = ""
    wopens: List[str] = field(default_factory=list)
    plays: List[str] = field(default_factory=list)
    images: List[str] = field(default_factory=list)
    contents: List[str] = field(default_factory=list)
    googlesearches: List[str] = field(default_factory=list)
    youtubesearches: List[str] = field(default_factory=list)
    cam: Optional[dict] = None

class TaskExecutor:

    def __init__(self, groq_service=None):
        self.groq_service = groq_service
        logger.info("[TASK] TaskExecutor initialized (Pollinations.ai for images)")

    def execute(
        self,
        intents: List[tuple],
        chat_history: Optional[List[tuple]] = None,
    ) -> TaskResponse:
        
        response = TaskResponse()

        tasks = []

        for intent_type, payload in intents:

            if intent_type == INTENT_OPEN:
                tasks.append(("wopen", self._do_open, payload))

            elif intent_type == INTENT_PLAY:
                tasks.append(("play", self._do_play, payload))

            elif intent_type == INTENT_GENERATE_IMAGE:
                tasks.append(("image", self._do_generate_image, payload))

            elif intent_type == INTENT_CONTENT:
                tasks.append(("content", lambda p: self._do_content(p, chat_history), payload))

            elif intent_type == INTENT_GOOGLE_SEARCH:
                tasks.append(("google", self._do_google_search, payload))

            elif intent_type == INTENT_YOUTUBE_SEARCH:
                tasks.append(("youtube", self._do_youtube_search, payload))

            elif intent_type == INTENT_OPEN_WEBCAM:
                response.cam = {"action": "open"}
                response.text = "Opening the webcam for you."

            elif intent_type == INTENT_CLOSE_WEBCAM:
                response.cam = {"action": "close"}
                response.text = "Webcam closed."

            elif intent_type == INTENT_CAMERA:
                response.cam = {"action": "open"}
                response.text = "Opening your webcam. Once it's on, send your message again and I'll describe what I see."
            
            elif intent_type == INTENT_CHAT:
                pass

        if not tasks:

            if not response.text and not response.cam:
                response.text = "I'm not sure what you'd like me to do. Could you clarify?"

            return response

        t0 = time.perf_counter()
        failed_tags = []

        try:

            with ThreadPoolExecutor(max_workers=min(6, len(tasks))) as executor:
                futures = {
                    executor.submit(fn, p): (tag, fn, p)
                    for tag, fn, p in tasks
                }

                for future in as_completed(futures, timeout=TASK_EXECUTION_TIMEOUT):
                    tag, fn, payload = futures[future]

                    try:
                        result = future.result()
                        if tag == "wopen" and result:
                            response.wopens.append(result)

                        elif tag == "play" and result:
                            response.plays.append(result)

                        elif tag == "image" and result:
                            response.images.append(result)

                        elif tag == "content" and result:
                            response.contents.append(result)

                        elif tag == "google" and result:
                            response.googlesearches.append(result)

                        elif tag == "youtube" and result:
                            response.youtubesearches.append(result)

                    except Exception as e:
                        failed_tags.append(tag)
                        err_msg = str(e)[:100]
                        logger.warning("[TASK] Task %s failed: %s", tag, e)
                        
                        if "content_policy" in err_msg.lower() or "safety" in err_msg.lower():
                            if tag == "image":
                                response.text = "I couldn't generate that image — it may violate content guidelines."
                        
                        elif not response.text:
                            response.text = f"Something went wrong with that task: {err_msg}"

        except FuturesTimeoutError:
            logger.warning("[TASK] Task execution timed out after %ds", TASK_EXECUTION_TIMEOUT)

            if not response.text:
                response.text = "Some tasks took too long. Please try again."

        elapsed = time.perf_counter() - t0
        logger.info("[TASK] Executed %d tasks in %.2fs (failed: %s)", len(tasks), elapsed, failed_tags or "none")

        if not response.text:
            parts = self._build_conversational_response(
                response.wopens, response.plays, response.images,
                response.contents, response.googlesearches, response.youtubesearches,
            )
            response.text = parts if parts else "All done."

        return response

    def _url_to_display_name(self, url: str) -> str:
        u = (url or "").lower()
        mapping = {
            "facebook.com": "Facebook", "instagram.com": "Instagram", "youtube.com": "YouTube",
            "google.com": "Google", "netflix.com": "Netflix", "twitter.com": "Twitter",
            "x.com": "X", "gmail.com": "Gmail", "whatsapp.com": "WhatsApp",
            "linkedin.com": "LinkedIn", "reddit.com": "Reddit", "discord.com": "Discord",
            "spotify.com": "Spotify", "tiktok.com": "TikTok", "amazon.com": "Amazon",
            "github.com": "GitHub", "wikipedia.org": "Wikipedia", "stackoverflow.com": "Stack Overflow",
            "medium.com": "Medium", "notion.so": "Notion", "figma.com": "Figma",
            "canva.com": "Canva", "zoom.us": "Zoom", "drive.google.com": "Google Drive",
            "jarvisforeveryone.com": "Jarvis for Everyone", "graphy.com": "Graphy",
        }

        for key, name in mapping.items():
            if key in u:
                return name

        try:
            parsed = urlparse(url)
            domain = (parsed.netloc or parsed.path or "").replace("www.", "").split(".")[0]
            return domain.title() if domain else "the link"
        
        except Exception:
            return "the link"

    def _build_conversational_response(
        self,
        wopens: List[str],
        plays: List[str],
        images: List[str],
        contents: List[str],
        googlesearches: List[str],
        youtubesearches: List[str],
    ) -> str:
        
        parts = []

        if wopens:
            names = [self._url_to_display_name(u) for u in wopens]

            if len(names) == 1:
                parts.append(f"I've opened {names[0]} for you.")

            else:
                last = names[-1]
                rest = ", ".join(names[:-1])
                parts.append(f"I've opened {rest} and {last} for you.")

        if plays:
            parts.append("I've started playing that for you.")
            
        if images:
            count = len(images)
            parts.append(f"I've generated the image{'s' if count > 1 else ''} for you.")

        if contents:
            parts.append("I've written that for you.")

        if googlesearches or youtubesearches:
            parts.append("I've run the search for you.")

        return " ".join(parts) if parts else "Done."

    def _validate_url(self, url: str) -> Optional[str]:

        if not url or len(url) > 2048:
            return None
        u = url.strip()

        if not u.startswith("http"):
            u = "https://" + u

        try:
            parsed = urlparse(u)
            
            if parsed.scheme not in ("http", "https"):
                logger.warning("[TASK] Rejected non-http URL: %s", u[:50])
                return None
            return u
        
        except Exception:
            return None

    def _do_open(self, payload: dict) -> Optional[str]:
        url = payload.get("url", "").strip()

        if not url:
            return None
        return self._validate_url(url)

    def _do_play(self, payload: dict) -> Optional[str]:
        query = (payload.get("query", payload.get("message", "")) or "").strip()[:500]
        if not query:
            return "https://www.youtube.com"
        return f"https://www.youtube.com/results?search_query={quote(query, safe='')}"

    def _do_generate_image(self, payload: dict) -> Optional[tuple]:
        """Returns (pollinations_url, image_bytes) or None on failure."""
        prompt = (payload.get("prompt", payload.get("message", "")) or "").strip()

        if len(prompt) < 3:
            logger.warning("[TASK] Image prompt too short (< 3 chars)")
            return None

        prompt = prompt[:4000]
        t0 = time.perf_counter()

        result = self._generate_pollinations(prompt)

        if result:
            logger.info("[TASK] Pollinations image downloaded in %.2fs", time.perf_counter() - t0)
            return result

        logger.warning("[TASK] Image generation failed")
        return None

    def _generate_pollinations(self, prompt: str) -> Optional[tuple]:
        """Download the generated image and return (url, bytes), or None on failure."""
        import httpx
        encoded_prompt = quote(prompt, safe='')
        api_url = (
            f"https://image.pollinations.ai/prompt/{encoded_prompt}"
            f"?model=flux&width=1024&height=1024&nologo=true&private=true&enhance=true&safe=false"
        )
        logger.info("[TASK] Fetching Pollinations image: %s", api_url[:120])
        for attempt in range(3):
            try:
                with httpx.Client(timeout=60, follow_redirects=True) as client:
                    resp = client.get(api_url)
                if resp.status_code == 200 and resp.content:
                    content_type = resp.headers.get("content-type", "")
                    if "image" in content_type or len(resp.content) > 1000:
                        logger.info("[TASK] Pollinations image fetched (%d bytes)", len(resp.content))
                        return (api_url, resp.content)
                logger.warning("[TASK] Pollinations attempt %d: status=%d", attempt + 1, resp.status_code)
            except Exception as e:
                logger.warning("[TASK] Pollinations attempt %d failed: %s", attempt + 1, e)
            time.sleep(2)
        return None

    def _do_content(self, payload: dict, chat_history: Optional[List[tuple]] = None) -> Optional[str]:
        prompt = (payload.get("prompt", payload.get("message", "")) or "").strip()
        
        if not prompt or not self.groq_service:
            return None
        content_question = f"Write the following. Be thorough and well-structured. Return only the requested content, no preamble.\n\n{prompt}"
        
        try:
            out = self.groq_service.get_response(
                question=content_question,
                chat_history=chat_history or [],
                key_start_index=0,
            )
            
            if not out or len(out.strip()) < 10:
                logger.warning("[TASK] Content generation returned empty or very short result")
                return None
            return out
        
        except Exception as e:
            logger.warning("[TASK] Content generation error: %s", e)
        return None

    def _do_google_search(self, payload: dict) -> Optional[str]:
        query = (payload.get("query", payload.get("message", "")) or "").strip()[:500]
        if not query:
            return None
        return f"https://www.google.com/search?q={quote(query, safe='')}"

    def _do_youtube_search(self, payload: dict) -> Optional[str]:
        query = (payload.get("query", payload.get("message", "")) or "").strip()[:500]
        if not query:
            return "https://www.youtube.com"
        return f"https://www.youtube.com/results?search_query={quote(query, safe='')}"
</file>

<file path="JARVIS/app/services/task_manager.py">
import logging
import threading
import time
import uuid
from dataclasses import dataclass, field
from typing import Optional, Dict, Any, List
from concurrent.futures import ThreadPoolExecutor
from app.services.decision_types import INTENT_GENERATE_IMAGE, INTENT_CONTENT

logger = logging.getLogger("J.A.R.V.I.S")
TASK_TTL = 3600

@dataclass

class TaskEntry:
    task_id: str
    status: str = "running"
    task_type: str = ""
    label: str = ""
    prompt: str = ""
    result: Optional[Dict[str, Any]] = None
    error: Optional[str] = None
    created_at: float = 0.0
    image_bytes: Optional[bytes] = None

class TaskManager:
    
    def __init__(self, task_executor):
        self.task_executor = task_executor
        self._tasks: Dict[str, TaskEntry] = {}
        self._lock = threading.Lock()
        self._pool = ThreadPoolExecutor(max_workers=4, thread_name_prefix="bg-task")
        logger.info("[TASK-MGR] Background task manager initialized (4 workers)")

    def submit(
        self,
        intent_type: str,
        payload: dict,
        chat_history: Optional[List[tuple]] = None,
    ) -> str:
        
        task_id = uuid.uuid4().hex[:8]
        prompt = payload.get("prompt", payload.get("message", ""))[:200]

        if intent_type == INTENT_GENERATE_IMAGE:
            label = "Generating image"

        elif intent_type == INTENT_CONTENT:
            label = "Writing content"

        else:
            label = "Processing task"

        entry = TaskEntry(
            task_id=task_id,
            status="running",
            task_type=intent_type,
            label=label,
            prompt=prompt,
            created_at=time.time(),
        )

        with self._lock:
            self._tasks[task_id] = entry

        self._pool.submit(self._run, task_id, intent_type, payload, chat_history)
        logger.info("[TASK-MGR] Submitted %s task %s: %.80s", intent_type, task_id, prompt)
        return task_id

    def get(self, task_id: str) -> Optional[TaskEntry]:
        with self._lock:
            return self._tasks.get(task_id)

    def get_serializable(self, task_id: str) -> Optional[dict]:
        entry = self.get(task_id)
        if not entry:
            return None
        return {
            "task_id": entry.task_id,
            "status": entry.status,
            "task_type": entry.task_type,
            "label": entry.label,
            "prompt": entry.prompt,
            "result": entry.result,
            "error": entry.error,
        }

    def _run(self, task_id: str, intent_type: str, payload: dict, chat_history):
        t0 = time.perf_counter()

        try:
            if intent_type == INTENT_GENERATE_IMAGE:
                img_result = self.task_executor._do_generate_image(payload)

                if img_result:
                    pollinations_url, image_bytes = img_result
                    result = {
                        "type": "image",
                        "url": f"/tasks/{task_id}/image",
                        "prompt": payload.get("prompt", payload.get("message", "")),
                    }
                    with self._lock:
                        self._tasks[task_id].image_bytes = image_bytes

                else:
                    raise RuntimeError("Image generation returned no result. Check API key or content policy.")
            
            elif intent_type == INTENT_CONTENT:
                text = self.task_executor._do_content(payload, chat_history)

                if text:
                    result = {
                        "type": "content",
                        "text": text,
                        "prompt": payload.get("prompt", payload.get("message", "")),
                    }

                else:
                    raise RuntimeError("Content generation returned no result.")
                
            else:
                raise ValueError(f"Unsupported background task type: {intent_type}")

            with self._lock:
                self._tasks[task_id].status = "completed"
                self._tasks[task_id].result = result

            elapsed = time.perf_counter() - t0
            logger.info("[TASK-MGR] Task %s completed in %.2fs", task_id, elapsed)

        except Exception as e:
            with self._lock:
                self._tasks[task_id].status = "failed"
                self._tasks[task_id].error = str(e)[:500]
            logger.warning("[TASK-MGR] Task %s failed: %s", task_id, e)

    def cleanup_old(self):
        cutoff = time.time() - TASK_TTL
        
        with self._lock:
            to_remove = [tid for tid, e in self._tasks.items() if e.created_at < cutoff]
            for tid in to_remove:
                del self._tasks[tid]

        if to_remove:
            logger.info("[TASK-MGR] Cleaned up %d expired tasks", len(to_remove))

    def shutdown(self):
        self._pool.shutdown(wait=False)
        logger.info("[TASK-MGR] Shutdown complete")
</file>

<file path="JARVIS/app/services/vector_store.py">
import json
import logging
from typing import List, Optional
from langchain_text_splitters import RecursiveCharacterTextSplitter
from langchain_huggingface import HuggingFaceEmbeddings
from langchain_community.vectorstores import FAISS
from langchain_core.documents import Document

from config import (
    LEARNING_DATA_DIR,
    CHATS_DATA_DIR,
    VECTOR_STORE_DIR,
    EMBEDDING_MODEL,
    CHUNK_SIZE,
    CHUNK_OVERLAP,
)

logger = logging.getLogger("J.A.R.V.I.S")

class VectorStoreService:
    
    def __init__(self):
        self.embeddings = HuggingFaceEmbeddings(
            model_name=EMBEDDING_MODEL,
            model_kwargs={"device": "cpu"},
        )

        self.text_splitter = RecursiveCharacterTextSplitter(
            chunk_size=CHUNK_SIZE,
            chunk_overlap=CHUNK_OVERLAP,
        )

        self.vector_store: Optional[FAISS] = None

        self._retriever_cache: dict = {}

    def load_learning_data(self) -> List[Document]:
        documents = []

        for file_path in sorted(LEARNING_DATA_DIR.glob("*.txt")):

            try:
                with open(file_path, "r", encoding="utf-8") as f:
                    content = f.read().strip()

                    if content:
                        documents.append(Document(page_content=content, metadata={"source": str(file_path.name)}))
                        logger.info("[VECTOR] Loaded learning data: %s (%d chars)", file_path.name, len(content))
            
            except Exception as e:
                logger.warning("Could not load learning data file %s: %s", file_path, e)

        logger.info("[VECTOR] Total learning data files loaded: %d", len(documents))
        return documents

    def load_chat_history(self) -> List[Document]:
        documents = []

        for file_path in sorted(CHATS_DATA_DIR.glob("*.json")):

            try:
                with open(file_path, "r", encoding="utf-8") as f:
                    chat_data = json.load(f)

                messages = chat_data.get("messages", [])
                if not isinstance(messages, list):
                    continue

                lines = []
                for msg in messages:
                    if not isinstance(msg, dict):
                        continue

                    role = msg.get("role") or "assistant"
                    content = msg.get("content") or ""
                    prefix = "User: " if role == "user" else "Assistant: "
                    lines.append(prefix + content)
                chat_content = "\n".join(lines)

                if chat_content.strip():
                    documents.append(Document(page_content=chat_content, metadata={"source": f"chat_{file_path.stem}"}))
                    logger.info("[VECTOR] Loaded chat history: %s (%d messages)", file_path.name, len(messages))
            
            except Exception as e:
                logger.warning("Could not load chat history file %s: %s", file_path, e)
                
        logger.info("[VECTOR] Total chat history files loaded: %d", len(documents))
        return documents

    def create_vector_store(self) -> FAISS:
        learning_docs = self.load_learning_data()
        chat_docs = self.load_chat_history()
        all_documents = learning_docs + chat_docs
        logger.info("[VECTOR] Total documents to index: %d (learning: %d, chat: %d)",
                     len(all_documents), len(learning_docs), len(chat_docs))

        if not all_documents:
            self.vector_store = FAISS.from_texts(["No data available yet."], self.embeddings)
            logger.info("[VECTOR] No documents found, created placeholder index")

        else:
            chunks = self.text_splitter.split_documents(all_documents)
            logger.info("[VECTOR] Split into %d chunks (chunk_size=%d, overlap=%d)",
                         len(chunks), CHUNK_SIZE, CHUNK_OVERLAP)

            self.vector_store = FAISS.from_documents(chunks, self.embeddings)
            logger.info("[VECTOR] FAISS index built successfully with %d vectors", len(chunks))

        self._retriever_cache.clear()
        self.save_vector_store()
        return self.vector_store

    def save_vector_store(self):

        if self.vector_store:
            
            try:
                self.vector_store.save_local(str(VECTOR_STORE_DIR))

            except Exception as e:
                logger.error("Failed to save vector store to disk: %s", e)

    def get_retriever(self, k: int = 10):

        if not self.vector_store:
            raise RuntimeError("Vector store not initialized. This should not happen.")
        
        if k not in self._retriever_cache:
            self._retriever_cache[k] = self.vector_store.as_retriever(search_kwargs={"k": k})
        return self._retriever_cache[k]
</file>

<file path="JARVIS/app/services/vision_service.py">
import base64
import logging
from typing import Optional

from config import (
    VISION_MAX_IMAGE_BYTES,
    GROQ_API_KEYS, GROQ_VISION_MODEL,
)

logger = logging.getLogger("J.A.R.V.I.S")

VISION_SYSTEM_PROMPT = """You are analyzing a live camera image from the user. Your job is to describe what you see clearly and specifically.

RULES:
- Always describe the image in detail. Identify objects, text, people, actions, colors, positions, and any visible context.
- Answer the user's specific question directly (e.g. "what am I holding") with concrete, specific answers. Lead with the answer, then add brief detail.
- Never say you cannot see, are unable to tell, or don't have access to the image unless the image is truly blank, corrupted, or unreadable.
- Be confident and specific. If you see a phone, say "a phone" and what kind if visible. If you see text, read it out. If you see a person, describe what they're doing.
- Keep replies brief and natural (1-3 sentences) unless the user asks for more detail.
- When asked about text in the image: read it clearly and completely (OCR-style). Include all visible text.
- When asked about counting: count objects carefully and give the exact number.
- When asked about spatial relationships: describe left/right, above/below, in front/behind.
- When asked to identify a product, brand, or logo: name it specifically if you can recognize it.
- Do not use asterisks, emojis, or markdown formatting. Use plain text with standard punctuation."""

class VisionService:

    def __init__(self):
        self._groq_client = None

        if GROQ_API_KEYS:

            try:
                from groq import Groq
                self._groq_client = Groq(api_key=GROQ_API_KEYS[0])
                logger.info("[VISION] Groq vision initialized (%s)", GROQ_VISION_MODEL)

            except Exception as e:
                logger.warning("[VISION] Groq client init failed: %s", e)

        if not self._groq_client:
            logger.warning("[VISION] No vision provider available. Set GROQ_API_KEY.")

    def describe_image(
        self,
        img_base64: str,
        prompt: Optional[str] = None,
    ) -> str:
        
        if not self._groq_client:
            return "Vision is not available. Please set GROQ_API_KEY."

        if "," in img_base64:
            img_base64 = img_base64.split(",", 1)[-1]

        if not img_base64:
            return "No image data received."

        raw_len = 0

        try:
            raw_len = len(base64.b64decode(img_base64, validate=True))

            if raw_len > VISION_MAX_IMAGE_BYTES:
                logger.warning("[VISION] Image too large: %d bytes (max %d)", raw_len, VISION_MAX_IMAGE_BYTES)
                return "Image is too large. Please use a smaller image."
        
        except Exception as e:
            logger.warning("[VISION] Invalid base64 image: %s", e)
            return "Invalid image data. Please try again."

        mime = "image/jpeg"

        try:
            raw = base64.b64decode(img_base64[:64], validate=False)

            if raw[:8] == b'\x89PNG\r\n\x1a\n':
                mime = "image/png"

            elif raw[:4] == b'RIFF' and raw[8:12] == b'WEBP':
                mime = "image/webp"

        except Exception:
            pass

        user_question = (prompt or "What do you see in this image? Describe it in detail.").strip()
        data_url = f"data:{mime};base64,{img_base64}"
        logger.info("[VISION] Analyzing image (%d bytes, %s)", raw_len, mime)

        messages = [
            {"role": "system", "content": VISION_SYSTEM_PROMPT},
            {
                "role": "user",
                "content": [
                    {"type": "text", "text": user_question},
                    {
                        "type": "image_url",
                        "image_url": {"url": data_url},
                    },
                ],
            },
        ]

        if self._groq_client:
            result = self._call_groq(messages)

            if result:
                return result

        return "I couldn't analyze that image. Please try again."

    def _call_groq(self, messages: list) -> Optional[str]:

        try:
            response = self._groq_client.chat.completions.create(
                model=GROQ_VISION_MODEL,
                messages=messages,
                max_tokens=600,
            )

            if response.choices:
                text = (response.choices[0].message.content or "").strip()

                if text:
                    logger.info("[VISION] Groq vision success (%d chars)", len(text))
                    return text
                
        except Exception as e:
            err_str = str(e).lower()
            
            if "content_policy" in err_str or "safety" in err_str:
                logger.warning("[VISION] Groq content policy: %s", e)
                return "The image couldn't be analyzed due to content guidelines."
            logger.warning("[VISION] Groq vision error: %s", e)
        return None
</file>

<file path="JARVIS/app/utils/__init__.py">

</file>

<file path="JARVIS/app/utils/key_rotation.py">
from typing import Optional, Tuple

def get_next_key_pair(num_keys: int,need_brain: bool = True) -> Tuple[Optional[int], int]:
    
    if not need_brain:
        return (None, 0)

    if num_keys <= 1:
        return (0, 0)

    return (0, 1)
</file>

<file path="JARVIS/app/utils/retry.py">
import time
import logging
from typing import Callable, TypeVar

logger = logging.getLogger("J.A.R.V.I.S")
T = TypeVar("T")


def with_retry(
    fn: Callable[[], T],
    max_retries: int = 2,
    initial_delay: float = 0.5,
) -> T:
    
    last_exc: Exception = RuntimeError("with_retry called with max_retries < 1")

    for attempt in range(max_retries):
        try:
            return fn()
        
        except Exception as e:

            last_exc = e

            if attempt < max_retries - 1:
                logger.debug("[RETRY] Attempt %d/%d failed: %s — retrying in %.1fs",
                             attempt + 1, max_retries, e, initial_delay)
                time.sleep(initial_delay)

            else:
                logger.debug("[RETRY] Attempt %d/%d failed: %s — giving up",
                             attempt + 1, max_retries, e)
                
    raise last_exc
</file>

<file path="JARVIS/app/utils/time_info.py">
from datetime import datetime

def get_time_information() -> str:
    now = datetime.now()
    return now.strftime("%A, %B %d, %Y, %I:%M %p")
</file>

<file path="JARVIS/app/__init__.py">

</file>

<file path="JARVIS/app/generate_thinking_audio.py">
import asyncio
import sys
from pathlib import Path

PROJECT_ROOT = Path(__file__).resolve().parent.parent
AUDIO_DIR = PROJECT_ROOT / "frontend" / "audio"

STARTER_PHRASES = [
    ("starter_1", "One moment please."),
    ("starter_2", "Sure, one moment."),
    ("starter_3", "Got it, hold on."),
    ("starter_4", "On it right now."),
    ("starter_5", "Alright, give me a sec."),
    ("starter_6", "Right, one moment."),
    ("starter_7", "Okay, hold on."),
    ("starter_8", "One second please."),
    ("starter_9", "Give me a moment."),
    ("starter_10", "Just a moment please."),
]

PHRASES = STARTER_PHRASES
VOICE = "en-GB-RyanNeural"
RATE = "+15%"

async def generate_one(name: str, text: str) -> bool:

    try:
        import edge_tts

    except ImportError:
        return False
    
    path = AUDIO_DIR / f"{name}.mp3"

    try:
        communicate = edge_tts.Communicate(text, VOICE, rate=RATE)
        await communicate.save(str(path))
        print(f"  [OK] {name}.mp3")
        return True
    
    except Exception as e:
        print(f"  [FAIL] {name}.mp3: {e}")
        return False

async def main():

    try:
        import edge_tts

    except ImportError:
        print("edge-tts not installed. Run: pip install edge-tts")
        return 1
    
    AUDIO_DIR.mkdir(parents=True, exist_ok=True)

    for f in AUDIO_DIR.glob("followup_*.mp3"):

        try:
            f.unlink()
            print(f"  [REMOVED] {f.name}")

        except OSError:
            pass

    print(f"Generating thinking audio in {AUDIO_DIR}...")
    success = 0

    for name, text in PHRASES:
        if await generate_one(name, text):
            success += 1

    print(f"Done: {success}/{len(PHRASES)} files.")
    return 0 if success == len(PHRASES) else 1

if __name__ == "__main__":

    try:
        exit_code = asyncio.run(main())

    except KeyboardInterrupt:
        exit_code = 130

    sys.exit(exit_code)
</file>

<file path="JARVIS/app/main.py">
from pathlib import Path
from fastapi import FastAPI, HTTPException
from fastapi.middleware.cors import CORSMiddleware
from fastapi.responses import StreamingResponse, RedirectResponse, Response
from fastapi.staticfiles import StaticFiles
from starlette.middleware.base import BaseHTTPMiddleware
from starlette.requests import Request
from contextlib import asynccontextmanager
import uvicorn
import logging
import json
import time
import re
import base64
import asyncio
from concurrent.futures import ThreadPoolExecutor, TimeoutError as FuturesTimeoutError
import edge_tts
from app.models import ChatRequest, ChatResponse, TTSRequest

RATE_LIMIT_MESSAGE = (
    "You've reached your daily API limit for this assistant. "
    "Your credits will reset in a few hours, or you can upgrade your plan for more. "
    "Please try again later."
)

def _is_rate_limit_error(exc: Exception) -> bool:
    msg = str(exc).lower()
    return "429" in str(exc) or "rate limit" in msg or "tokens per day" in msg

from app.services.vector_store import VectorStoreService
from app.services.groq_service import GroqService, AllGroqApisFailedError
from app.services.realtime_service import RealtimeGroqService
from app.services.chat_service import ChatService
from app.services.brain_service import BrainService
from app.services.task_executor import TaskExecutor
from app.services.vision_service import VisionService
from app.services.task_manager import TaskManager

from config import (
    VECTOR_STORE_DIR, GROQ_API_KEYS, GROQ_MODEL, TAVILY_API_KEY,
    EMBEDDING_MODEL, CHUNK_SIZE, CHUNK_OVERLAP, MAX_CHAT_HISTORY_TURNS,
    ASSISTANT_NAME, TTS_VOICE, TTS_RATE,
)

logging.basicConfig(
    level=logging.INFO,
    format='%(asctime)s | %(levelname)-8s | %(name)-20s | %(message)s',
    datefmt='%Y-%m-%d %H:%M:%S'
)

logger = logging.getLogger("J.A.R.V.I.S")
vector_store_service: VectorStoreService = None
groq_service: GroqService = None
realtime_service: RealtimeGroqService = None
brain_service: BrainService = None
task_executor: TaskExecutor = None
task_manager: TaskManager = None
vision_service: VisionService = None
chat_service: ChatService = None

def print_title():

    title = """

   ╔══════════════════════════════════════════════════════════╗
   ║                                                          ║
   ║         ██╗ █████╗ ██████╗ ██╗   ██╗██╗███████╗          ║
   ║         ██║██╔══██╗██╔══██╗██║   ██║██║██╔════╝          ║
   ║         ██║███████║██████╔╝██║   ██║██║███████╗          ║
   ║    ██   ██║██╔══██║██╔══██╗╚██╗ ██╔╝██║╚════██║          ║
   ║    ╚█████╔╝██║  ██║██║  ██║ ╚████╔╝ ██║███████║          ║
   ║     ╚════╝ ╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝  ╚═╝╚══════╝          ║
   ║                                                          ║
   ║          Just A Rather Very Intelligent System           ║
   ║                                                          ║
   ╚══════════════════════════════════════════════════════════╝

    """
    print(title)

@asynccontextmanager

async def lifespan(app: FastAPI):

    global vector_store_service, groq_service, realtime_service, brain_service
    global task_executor, task_manager, vision_service, chat_service
    print_title()
    logger.info("=" * 60)
    logger.info("J.A.R.V.I.S - Starting Up...")
    logger.info("=" * 60)
    logger.info("[CONFIG] Assistant name: %s", ASSISTANT_NAME)
    logger.info("[CONFIG] Groq model: %s", GROQ_MODEL)
    logger.info("[CONFIG] Groq API keys loaded: %d", len(GROQ_API_KEYS))
    logger.info("[CONFIG] Tavily API key: %s", "configured" if TAVILY_API_KEY else "NOT SET")
    logger.info("[CONFIG] Image generation: Pollinations.ai (free, no API key)")
    logger.info("[CONFIG] Embedding model: %s", EMBEDDING_MODEL)
    logger.info("[CONFIG] Chunk size: %d | Overlap: %d | Max history turns: %d",
                CHUNK_SIZE, CHUNK_OVERLAP, MAX_CHAT_HISTORY_TURNS)

    try:

        logger.info("Initializing vector store service...")
        t0 = time.perf_counter()
        vector_store_service = VectorStoreService()
        vector_store_service.create_vector_store()
        logger.info("[TIMING] startup_vector_store: %.3fs", time.perf_counter() - t0)
        logger.info("Initializing Groq service (general queries)...")
        groq_service = GroqService(vector_store_service)
        logger.info("Groq service initialized successfully")
        logger.info("Initializing Realtime Groq service (with Tavily search)...")
        realtime_service = RealtimeGroqService(vector_store_service)
        logger.info("Realtime Groq service initialized successfully")
        logger.info("Initializing Brain service (Groq query classification)...")
        brain_service = BrainService(groq_service=groq_service)
        logger.info("Brain service initialized successfully")
        logger.info("Initializing Task executor...")
        task_executor = TaskExecutor(groq_service=groq_service)
        logger.info("Task executor initialized successfully")
        logger.info("Initializing Background task manager...")
        task_manager = TaskManager(task_executor=task_executor)
        logger.info("Background task manager initialized successfully")
        logger.info("Initializing Vision service (Groq)...")
        vision_service = VisionService()
        logger.info("Vision service initialized successfully")
        logger.info("Initializing chat service...")

        chat_service = ChatService(
            groq_service, realtime_service, brain_service,
            task_executor=task_executor,
            vision_service=vision_service,
            task_manager=task_manager,
        )

        logger.info("Chat service initialized successfully")
        logger.info("=" * 60)
        logger.info("Service Status:")
        logger.info("  - Vector Store: Ready")
        logger.info("  - Groq AI (General): Ready")
        logger.info("  - Groq AI (Realtime): Ready")
        logger.info("  - Brain (Unified Decision): Ready")
        logger.info("  - Task Executor: Ready")
        logger.info("  - Background Task Manager: Ready")
        logger.info("  - Vision (Groq): Ready")
        logger.info("  - Chat Service: Ready")
        logger.info("=" * 60)
        logger.info("J.A.R.V.I.S is online and ready!")
        logger.info("API: http://localhost:8000")
        logger.info("Frontend: http://localhost:8000/app/ (open in browser)")
        logger.info("=" * 60)

        yield

        logger.info("\nShutting down J.A.R.V.I.S...")
        _tts_pool.shutdown(wait=True)

        if task_manager:
            task_manager.shutdown()

        if chat_service:
            for session_id in list(chat_service.sessions.keys()):
                chat_service.save_chat_session(session_id)

        logger.info("All sessions saved. Goodbye!")

    except Exception as e:
        logger.error(f"Fatal error during startup: {e}", exc_info=True)
        raise

app = FastAPI(
    title="J.A.R.V.I.S API",
    description="Just A Rather Very Intelligent System",
    lifespan=lifespan,
    docs_url=None,
    redoc_url=None,
    openapi_url=None
)

app.add_middleware(
    CORSMiddleware,
    allow_origins=["*"],
    allow_credentials=True,
    allow_methods=["*"],
    allow_headers=["*"],
)

class TimingMiddleware(BaseHTTPMiddleware):
    async def dispatch(self, request: Request, call_next):
        t0 = time.perf_counter()
        response = await call_next(request)
        elapsed = time.perf_counter() - t0
        path = request.url.path
        logger.info("[REQUEST] %s %s -> %s (%.3fs)", request.method, path, response.status_code, elapsed)
        return response

app.add_middleware(TimingMiddleware)

@app.get("/api")

async def api_info():
    return {
        "message": "J.A.R.V.I.S API",
        "endpoints": {
            "/chat": "General chat (non-streaming)",
            "/chat/stream": "General chat (streaming chunks)",
            "/chat/realtime": "Realtime chat (non-streaming)",
            "/chat/realtime/stream": "Realtime chat (streaming chunks)",
            "/chat/jarvis/stream": "Jarvis unified route (two-stage brain: classify → route → execute/stream)",
            "/chat/history/{session_id}": "Get chat history",
            "/tasks/{task_id}": "Get background task status and result",
            "/health": "System health check",
            "/tts": "Text-to-speech (POST text, returns streamed MP3)"
        }
    }

@app.get("/health")

async def health():

    try:
        return {
            "status": "healthy",
            "vector_store": vector_store_service is not None,
            "groq_service": groq_service is not None,
            "realtime_service": realtime_service is not None,
            "brain_service": brain_service is not None,
            "task_executor": task_executor is not None,
            "task_manager": task_manager is not None,
            "vision_service": vision_service is not None,
            "chat_service": chat_service is not None
        }
    
    except Exception as e:
        logger.warning("[API /health] Error: %s", e)
        return {"status": "degraded", "error": str(e)}

@app.post("/chat", response_model=ChatResponse)

async def chat(request: ChatRequest):

    if not chat_service:
        raise HTTPException(status_code=503, detail="Chat service not initialized")

    logger.info("[API /chat] Incoming | session_id=%s | message_len=%d | message=%.100s",
                request.session_id or "new", len(request.message), request.message)
    
    try:
        session_id = chat_service.get_or_create_session(request.session_id)
        response_text = chat_service.process_message(session_id, request.message)
        chat_service.save_chat_session(session_id)
        logger.info("[API /chat] Done | session_id=%s | response_len=%d", session_id[:12], len(response_text))
        return ChatResponse(response=response_text, session_id=session_id)

    except ValueError as e:
        logger.warning("[API /chat] Invalid session_id: %s", e)
        raise HTTPException(status_code=400, detail=str(e))

    except AllGroqApisFailedError as e:
        logger.error("[API /chat] All Groq APIs failed: %s", e)
        raise HTTPException(status_code=503, detail=str(e))

    except Exception as e:

        if _is_rate_limit_error(e):
            logger.warning("[API /chat] Rate limit hit: %s", e)
            raise HTTPException(status_code=429, detail=RATE_LIMIT_MESSAGE)
        
        logger.error("[API /chat] Error: %s", e, exc_info=True)
        raise HTTPException(status_code=500, detail=f"Error processing chat: {str(e)}")

_SPLIT_RE = re.compile(r"(?<=[.!?,;:])\s+")
_MIN_WORDS_FIRST = 1
_MIN_WORDS = 1
_MERGE_IF_WORDS = 2
_TTS_BUFFER_TIMEOUT = 2.0
_TTS_BUFFER_MIN_WORDS = 4
_ABBREV_HOLD_RE = re.compile(r"^(?:Dr|Mr|Mrs|Ms|Prof|Sr|Jr|St|Vs|Etc)\.$", re.IGNORECASE)

def _should_hold_sentence_for_continuation(sent: str) -> bool:

    t = sent.strip()

    if not t.endswith("."):
        return False
    
    words = t.split()

    if len(words) != 1:
        return False
    
    return bool(_ABBREV_HOLD_RE.match(words[0]))

def _split_sentences(buf: str):
    parts = _SPLIT_RE.split(buf)

    if len(parts) <= 1:
        return [], buf

    raw = [p.strip() for p in parts[:-1] if p.strip()]
    sentences, pending = [], ""

    for s in raw:

        if pending:
            s = (pending + " " + s).strip()
            pending = ""

        min_req = _MIN_WORDS_FIRST if not sentences else _MIN_WORDS

        if len(s.split()) < min_req:
            pending = s
            continue
        sentences.append(s)

    remaining = (pending + " " + parts[-1].strip()).strip() if pending else parts[-1].strip()
    return sentences, remaining

def _merge_short(sentences):

    if not sentences:
        return []
    
    merged, i = [], 0

    while i < len(sentences):
        cur = sentences[i]
        j = i + 1

        while j < len(sentences) and len(sentences[j].split()) <= _MERGE_IF_WORDS:
            cur = (cur + " " + sentences[j]).strip()
            j += 1

        merged.append(cur)
        i = j

    return merged

def _generate_tts_sync(text: str, voice: str, rate: str) -> bytes:

    async def _inner():
        communicate = edge_tts.Communicate(text=text, voice=voice, rate=rate)
        parts = []

        async for chunk in communicate.stream():
            if chunk["type"] == "audio":
                parts.append(chunk["data"])

        return b"".join(parts)
    
    return asyncio.run(_inner())

_tts_pool = ThreadPoolExecutor(max_workers=4)

def _stream_generator(session_id: str, chunk_iter, is_realtime: bool, tts_enabled: bool = False):
    yield f"data: {json.dumps({'session_id': session_id, 'chunk': '', 'done': False})}\n\n"
    buffer = ""
    held = None
    is_first = True
    audio_queue = []
    last_submit_time = time.perf_counter()

    def _submit(text):
        nonlocal last_submit_time

        if not text or not text.strip():
            return
        
        audio_queue.append((_tts_pool.submit(_generate_tts_sync, text, TTS_VOICE, TTS_RATE), text))
        last_submit_time = time.perf_counter()

    def _drain_ready():
        events = []

        while audio_queue and audio_queue[0][0].done():
            fut, sent = audio_queue.pop(0)

            try:
                audio = fut.result()
                b64 = base64.b64encode(audio).decode("ascii")
                events.append(f"data: {json.dumps({'audio': b64, 'sentence': sent})}\n\n")

            except Exception as exc:
                logger.warning("[TTS-INLINE] Failed for '%s': %s", sent[:40], exc)
        return events

    def _yield_completed_audio():

        if not tts_enabled:
            return
        
        for ev in _drain_ready():
            yield ev

    try:

        for chunk in chunk_iter:

            if isinstance(chunk, dict) and "_activity" in chunk:
                yield f"data: {json.dumps({'activity': chunk['_activity']})}\n\n"
                yield from _yield_completed_audio()
                continue

            if isinstance(chunk, dict) and "_search_results" in chunk:
                yield f"data: {json.dumps({'search_results': chunk['_search_results']})}\n\n"
                yield from _yield_completed_audio()
                continue

            if isinstance(chunk, dict) and "_actions" in chunk:
                yield f"data: {json.dumps({'actions': chunk['_actions']})}\n\n"
                yield from _yield_completed_audio()
                continue

            if isinstance(chunk, dict) and "_background_tasks" in chunk:
                yield f"data: {json.dumps({'background_tasks': chunk['_background_tasks']})}\n\n"
                yield from _yield_completed_audio()
                continue
            
            if not chunk:
                yield from _yield_completed_audio()
                continue

            yield f"data: {json.dumps({'chunk': chunk, 'done': False})}\n\n"

            if not tts_enabled:
                continue

            yield from _yield_completed_audio()

            buffer += chunk
            sentences, buffer = _split_sentences(buffer)
            sentences = _merge_short(sentences)

            if held and sentences and len(sentences[0].split()) <= _MERGE_IF_WORDS:
                held = (held + " " + sentences[0]).strip()
                sentences = sentences[1:]

            for i, sent in enumerate(sentences):
                min_w = _MIN_WORDS_FIRST if is_first else _MIN_WORDS
                if len(sent.split()) < min_w:
                    continue

                is_last = (i == len(sentences) - 1)

                if held:
                    _submit(held)
                    held = None
                    is_first = False

                if is_last and _should_hold_sentence_for_continuation(sent):
                    held = sent

                else:
                    _submit(sent)
                    is_first = False

            if buffer and len(buffer.split()) >= _TTS_BUFFER_MIN_WORDS:
                if time.perf_counter() - last_submit_time > _TTS_BUFFER_TIMEOUT:

                    if held:
                        _submit(held)
                        held = None
                        is_first = False

                    _submit(buffer.strip())
                    buffer = ""
                    is_first = False

            yield from _yield_completed_audio()

    except Exception as e:

        for fut, _ in audio_queue:
            fut.cancel()

        yield f"data: {json.dumps({'chunk': '', 'done': True, 'error': str(e)})}\n\n"
        return

    if tts_enabled:
        remaining = buffer.strip()

        if held:

            if remaining and len(remaining.split()) <= _MERGE_IF_WORDS:
                _submit((held + " " + remaining).strip())

            else:
                _submit(held)
                if remaining:
                    _submit(remaining)

        elif remaining:
            _submit(remaining)

        for fut, sent in audio_queue:

            try:
                audio = fut.result(timeout=15)
                b64 = base64.b64encode(audio).decode("ascii")
                yield f"data: {json.dumps({'audio': b64, 'sentence': sent})}\n\n"

            except FuturesTimeoutError:
                logger.warning("[TTS-INLINE] Timeout for '%s' (15s)", (sent or "")[:40])
                
            except Exception as exc:
                logger.warning("[TTS-INLINE] Failed for '%s': %s", (sent or "")[:40], exc)

    yield f"data: {json.dumps({'chunk': '', 'done': True, 'session_id': session_id})}\n\n"

@app.post("/chat/stream")

async def chat_stream(request: ChatRequest):

    if not chat_service:
        raise HTTPException(status_code=503, detail="Chat service not initialized")
    
    logger.info("[API /chat/stream] Incoming | session_id=%s | message_len=%d | message=%.100s",
                request.session_id or "new", len(request.message), request.message)
    
    try:
        session_id = chat_service.get_or_create_session(request.session_id)

        chunk_iter = chat_service.process_message_stream(session_id, request.message)
        return StreamingResponse(
            _stream_generator(session_id, chunk_iter, is_realtime=False, tts_enabled=request.tts),
            media_type="text/event-stream",
            headers={"Cache-Control": "no-cache", "X-Accel-Buffering": "no"},
        )
    
    except ValueError as e:
        raise HTTPException(status_code=400, detail=str(e))
    
    except AllGroqApisFailedError as e:
        raise HTTPException(status_code=503, detail=str(e))
    
    except Exception as e:
        if _is_rate_limit_error(e):
            raise HTTPException(status_code=429, detail=RATE_LIMIT_MESSAGE)
        
        logger.error("[API /chat/stream] Error: %s", e, exc_info=True)
        raise HTTPException(status_code=500, detail=str(e))

@app.post("/chat/realtime", response_model=ChatResponse)

async def chat_realtime(request: ChatRequest):

    if not chat_service:
        raise HTTPException(status_code=503, detail="Chat service not initialized")
    
    if not realtime_service:
        raise HTTPException(status_code=503, detail="Realtime service not initialized")

    logger.info("[API /chat/realtime] Incoming | session_id=%s | message_len=%d | message=%.100s",
                request.session_id or "new", len(request.message), request.message)
    
    try:
        session_id = chat_service.get_or_create_session(request.session_id)
        response_text = chat_service.process_realtime_message(session_id, request.message)
        chat_service.save_chat_session(session_id)
        logger.info("[API /chat/realtime] Done | session_id=%s | response_len=%d", session_id[:12], len(response_text))
        return ChatResponse(response=response_text, session_id=session_id)
    
    except ValueError as e:
        logger.warning("[API /chat/realtime] Invalid session_id: %s", e)
        raise HTTPException(status_code=400, detail=str(e))
    
    except AllGroqApisFailedError as e:
        logger.error("[API /chat/realtime] All Groq APIs failed: %s", e)
        raise HTTPException(status_code=503, detail=str(e))
    
    except Exception as e:

        if _is_rate_limit_error(e):
            logger.warning("[API /chat/realtime] Rate limit hit: %s", e)
            raise HTTPException(status_code=429, detail=RATE_LIMIT_MESSAGE)
        
        logger.error("[API /chat/realtime] Error: %s", e, exc_info=True)
        raise HTTPException(status_code=500, detail=f"Error processing chat: {str(e)}")

@app.post("/chat/realtime/stream")

async def chat_realtime_stream(request: ChatRequest):

    if not chat_service or not realtime_service:
        raise HTTPException(status_code=503, detail="Service not initialized")
    
    logger.info("[API /chat/realtime/stream] Incoming | session_id=%s | message_len=%d | message=%.100s",
                request.session_id or "new", len(request.message), request.message)
    
    try:
        session_id = chat_service.get_or_create_session(request.session_id)
        chunk_iter = chat_service.process_realtime_message_stream(session_id, request.message)
        return StreamingResponse(
            _stream_generator(session_id, chunk_iter, is_realtime=True, tts_enabled=request.tts),
            media_type="text/event-stream",
            headers={"Cache-Control": "no-cache", "X-Accel-Buffering": "no"},
        )
    
    except ValueError as e:
        raise HTTPException(status_code=400, detail=str(e))
    
    except AllGroqApisFailedError as e:
        raise HTTPException(status_code=503, detail=str(e))
    
    except Exception as e:
        if _is_rate_limit_error(e):
            raise HTTPException(status_code=429, detail=RATE_LIMIT_MESSAGE)
        
        logger.error("[API /chat/realtime/stream] Error: %s", e, exc_info=True)
        raise HTTPException(status_code=500, detail=str(e))

@app.post("/chat/jarvis/stream")

async def chat_jarvis_stream(request: ChatRequest):
    if not chat_service:
        raise HTTPException(status_code=503, detail="Service not initialized")
    
    logger.info("[API /chat/jarvis/stream] Incoming | session_id=%s | message_len=%d | img=%s | message=%.100s",
                request.session_id or "new", len(request.message), "yes" if request.imgbase64 else "no", request.message)
    
    try:
        session_id = chat_service.get_or_create_session(request.session_id)
        chunk_iter = chat_service.process_jarvis_message_stream(
            session_id, request.message, imgbase64=request.imgbase64
        )

        return StreamingResponse(
            _stream_generator(session_id, chunk_iter, is_realtime=True, tts_enabled=request.tts),
            media_type="text/event-stream",
            headers={"Cache-Control": "no-cache", "X-Accel-Buffering": "no"},
        )
    
    except ValueError as e:
        raise HTTPException(status_code=400, detail=str(e))
    
    except AllGroqApisFailedError as e:
        raise HTTPException(status_code=503, detail=str(e))
    
    except Exception as e:
        if _is_rate_limit_error(e):
            raise HTTPException(status_code=429, detail=RATE_LIMIT_MESSAGE)
        
        logger.error("[API /chat/jarvis/stream] Error: %s", e, exc_info=True)
        raise HTTPException(status_code=500, detail=str(e))

@app.get("/tasks/{task_id}")

async def get_task_status(task_id: str):
    if not task_manager:
        raise HTTPException(status_code=503, detail="Task manager not initialized")

    if not task_id or len(task_id) > 32:
        raise HTTPException(status_code=400, detail="Invalid task_id")
    data = task_manager.get_serializable(task_id)

    if not data:
        raise HTTPException(status_code=404, detail="Task not found")

    return data

@app.get("/tasks/{task_id}/image")

async def get_task_image(task_id: str):
    if not task_manager:
        raise HTTPException(status_code=503, detail="Task manager not initialized")

    if not task_id or len(task_id) > 32:
        raise HTTPException(status_code=400, detail="Invalid task_id")

    entry = task_manager.get(task_id)

    if not entry:
        raise HTTPException(status_code=404, detail="Task not found")

    if entry.status != "completed" or not entry.image_bytes:
        raise HTTPException(status_code=404, detail="Image not ready")

    return Response(content=entry.image_bytes, media_type="image/png")

@app.get("/chat/history/{session_id}")

async def get_chat_history(session_id: str):
    if not chat_service:
        raise HTTPException(status_code=503, detail="Chat service not initialized")
    
    if not chat_service.validate_session_id(session_id):
        raise HTTPException(status_code=400, detail="Invalid session_id format")

    try:
        messages = chat_service.get_chat_history(session_id)
        return {
            "session_id": session_id,
            "messages": [{"role": msg.role, "content": msg.content} for msg in messages]
        }
    
    except Exception as e:
        logger.error(f"Error retrieving history: {e}", exc_info=True)
        raise HTTPException(status_code=500, detail=f"Error retrieving history: {str(e)}")

@app.post("/tts")

async def text_to_speech(request: TTSRequest):
    text = request.text.strip()

    if not text:
        raise HTTPException(status_code=400, detail="Text is required")

    async def generate():
        try:
            communicate = edge_tts.Communicate(text=text, voice=TTS_VOICE, rate=TTS_RATE)
            async for chunk in communicate.stream():
                if chunk["type"] == "audio":
                    yield chunk["data"]
        except Exception as e:
            logger.error("[TTS] Error generating speech: %s", e)

    return StreamingResponse(
        generate(),
        media_type="audio/mpeg",
        headers={"Cache-Control": "no-cache"},
    )

_frontend_dir = Path(__file__).resolve().parent.parent / "frontend"

if _frontend_dir.exists():
    app.mount("/app", StaticFiles(directory=str(_frontend_dir), html=True), name="frontend")

@app.get("/")
async def root_redirect():
    return RedirectResponse(url="/app/", status_code=302)

def run():
    uvicorn.run(
        "app.main:app",
        host="0.0.0.0",
        port=8000,
        reload=True,
        log_level="info"
    )

if __name__ == "__main__":
    run()
</file>

<file path="JARVIS/app/models.py">
from pydantic import BaseModel, Field
from typing import List, Optional

class ChatMessage(BaseModel):
    role: str
    content: str

class ChatRequest(BaseModel):
    message: str = Field(..., min_length=1, max_length=32_000)
    session_id: Optional[str] = None
    tts: bool = False
    imgbase64: Optional[str] = None

class ChatResponse(BaseModel):
    response: str
    session_id: str

class ChatHistory(BaseModel):
    session_id: str
    messages: List[ChatMessage]

class JarvisActions(BaseModel):
    wopens: List[str] = []
    plays: List[str] = []
    images: List[str] = []
    contents: List[str] = []
    googlesearches: List[str] = []
    youtubesearches: List[str] = []
    cam: Optional[dict] = None

class TTSRequest(BaseModel):
    text: str = Field(..., min_length=1, max_length=5000)
</file>

<file path="JARVIS/database/learning_data/userdata.txt">
You are interacting with Shreshth Kaushik, a 21-year-old online educator, businessman, and programmer.

Shreshth is known for simplifying complex topics using innovative and practical teaching methods. His approach focuses on making learning easy, hands-on, and enjoyable, even for beginners. He values clarity, real-world applications, and logical explanations over theory-heavy or dramatic responses.

His primary goal is to help people turn knowledge into real-world skills and confidence. When responding to him, prioritize:

Clear and structured explanations

Practical examples and implementation-focused guidance

Professional but simple language

Avoid unnecessary drama or exaggeration

Basic Details:

Name: Shreshth Kaushik

Email: Kaushikshresth07@gmail.com

Instagram: https://www.instagram.com/theshreshthkaushik/

YouTube: https://www.youtube.com/channel/UC7A5u12yVIZaCO_uXnNhc5g

Website: https://kaushikshresth.graphy.com/

Telegram: https://t.me/theshreshthkaushik

Assume Shreshth is technically capable, understands programming concepts, and prefers efficient, intelligent, and actionable responses. He often works on AI systems, automation, and educational content.
</file>

<file path="JARVIS/frontend/index.html">
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="theme-color" content="#050510">
    <title>J.A.R.V.I.S</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="app">
        <div id="orb-container"></div>
        <header class="header glass-panel">
            <div class="header-left">
                <h1 class="logo">J.A.R.V.I.S</h1>
                <span class="tagline">Just A Rather Very Intelligent System</span>
            </div>
            <div class="header-center">
                <div class="mode-switch mode-switch-single" id="mode-switch">
                    <div class="mode-slider" id="mode-slider"></div>
                    <button class="mode-btn active" data-mode="jarvis" id="btn-jarvis" title="Jarvis — task execution, vision, chat">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5"/><path d="M2 12l10 5 10-5"/></svg>
                        <span class="mode-btn-text">Jarvis</span>
                    </button>
                </div>
            </div>
            <div class="header-right">
                <div class="status-badge" id="status-badge">
                    <span class="status-dot"></span>
                    <span class="status-text">Online</span>
                </div>
                <button class="btn-icon activity-toggle" id="activity-toggle" title="View activity flow">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="8" y1="6" x2="21" y2="6"/><line x1="8" y1="12" x2="21" y2="12"/><line x1="8" y1="18" x2="21" y2="18"/><line x1="3" y1="6" x2="3.01" y2="6"/><line x1="3" y1="12" x2="3.01" y2="12"/><line x1="3" y1="18" x2="3.01" y2="18"/></svg>
                </button>
                <button class="btn-icon search-results-toggle" id="search-results-toggle" title="View search results" style="display: none;">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/>
                    </svg>
                </button>
                <button class="btn-icon settings-btn" id="settings-btn" title="Settings">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1 0 2.83 2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-2 2 2 2 0 0 1-2-2v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2 2 0 0 1 0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 0-2.83 2 2 0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0 0 1 0 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65 1.65 0 0 0-1.51 1z"/>
                    </svg>
                </button>
                <button class="btn-icon new-chat-btn" id="new-chat-btn" title="New Chat">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/>
                    </svg>
                </button>
            </div>
        </header>
        <aside class="activity-panel glass-panel" id="activity-panel" aria-hidden="true">
            <div class="activity-header">
                <h3 class="activity-title">Activity</h3>
                <button class="activity-close" id="activity-close" title="Close" aria-label="Close activity panel">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
                </button>
            </div>
            <div class="activity-list" id="activity-list">
                <div class="activity-empty" id="activity-empty">Send a message to see the flow here.</div>
            </div>
        </aside>
        <main class="chat-area" id="chat-area">
            <div class="chat-messages" id="chat-messages">
                <div class="welcome-screen" id="welcome-screen">
                    <div class="welcome-icon">
                        <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5"/><path d="M2 12l10 5 10-5"/>
                        </svg>
                    </div>
                    <h2 class="welcome-title" id="welcome-title">Good evening.</h2>
                    <p class="welcome-sub">How may I assist you today?</p>
                    <div class="welcome-chips">
                        <button class="chip" data-msg="What can you do?">What can you do?</button>
                        <button class="chip" data-msg="Open YouTube for me">Open YouTube</button>
                        <button class="chip" data-msg="Tell me a fun fact">Fun fact</button>
                        <button class="chip" data-msg="Play some music">Play music</button>
                    </div>
                </div>
            </div>
        </main>
        <footer class="input-bar glass-panel">
            <div class="input-wrapper">
                <textarea id="message-input"
                          placeholder="Ask Jarvis anything..."
                          rows="1"
                          maxlength="32000"></textarea>
                <div class="input-actions">
                    <button class="action-btn cam-btn" id="cam-btn" title="Camera — capture and send for vision">
                        <svg class="cam-icon" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/>
                            <circle cx="12" cy="13" r="4"/>
                        </svg>
                        <svg class="cam-icon-active" width="20" height="20" viewBox="0 0 24 24" fill="currentColor" style="display: none;">
                            <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/>
                            <circle cx="12" cy="13" r="4" fill="currentColor"/>
                        </svg>
                    </button>
                    <button class="action-btn mic-btn" id="mic-btn" title="Voice input — click to start auto-listen (restarts after each response)">
                        <svg class="mic-icon" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M12 1a3 3 0 0 0-3 3v8a3 3 0 0 0 6 0V4a3 3 0 0 0-3-3z"/><path d="M19 10v2a7 7 0 0 1-14 0v-2"/><line x1="12" y1="19" x2="12" y2="23"/><line x1="8" y1="23" x2="16" y2="23"/>
                        </svg>
                        <svg class="mic-icon-active" width="20" height="20" viewBox="0 0 24 24" fill="currentColor">
                            <rect x="4" y="4" width="16" height="16" rx="3"/>
                        </svg>
                    </button>
                    <button class="action-btn tts-btn" id="tts-btn" title="Text to Speech">
                        <svg class="tts-icon-off" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"/>
                            <line x1="23" y1="9" x2="17" y2="15"/><line x1="17" y1="9" x2="23" y2="15"/>
                        </svg>
                        <svg class="tts-icon-on" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"/>
                            <path d="M15.54 8.46a5 5 0 0 1 0 7.07"/>
                            <path d="M19.07 4.93a10 10 0 0 1 0 14.14"/>
                        </svg>
                    </button>
                    <button class="action-btn send-btn" id="send-btn" title="Send message">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <line x1="22" y1="2" x2="11" y2="13"/><polygon points="22 2 15 22 11 13 2 9 22 2"/>
                        </svg>
                    </button>
                </div>
            </div>
            <div class="input-meta" id="input-meta">
                <span class="char-count" id="char-count"></span>
            </div>
        </footer>
        <aside class="search-results-widget glass-panel" id="search-results-widget" aria-hidden="true">
            <div class="search-results-header">
                <h3 class="search-results-title">Live search</h3>
                <button class="search-results-close" id="search-results-close" title="Close" aria-label="Close search results">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
                </button>
            </div>
            <div class="search-results-query" id="search-results-query"></div>
            <div class="search-results-answer" id="search-results-answer"></div>
            <div class="search-results-list" id="search-results-list"></div>
        </aside>
        <div class="settings-panel glass-panel" id="settings-panel" aria-hidden="true">
            <div class="settings-header">
                <h3 class="settings-title">Settings</h3>
                <button class="settings-close btn-icon" id="settings-close" title="Close" aria-label="Close settings">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
                </button>
            </div>
            <div class="settings-body">
                <div class="settings-item">
                    <label class="settings-label" for="toggle-auto-activity">Auto-open activity panel</label>
                    <label class="toggle-switch">
                        <input type="checkbox" id="toggle-auto-activity" checked>
                        <span class="toggle-slider"></span>
                    </label>
                </div>
                <div class="settings-item">
                    <label class="settings-label" for="toggle-auto-search">Auto-open search results</label>
                    <label class="toggle-switch">
                        <input type="checkbox" id="toggle-auto-search" checked>
                        <span class="toggle-slider"></span>
                    </label>
                </div>
                <div class="settings-item">
                    <label class="settings-label" for="toggle-thinking-sounds">Thinking sound effects</label>
                    <label class="toggle-switch">
                        <input type="checkbox" id="toggle-thinking-sounds" checked>
                        <span class="toggle-slider"></span>
                    </label>
                </div>
                <div class="settings-item">
                    <label class="settings-label" for="toggle-voice-interrupt">Voice interruption</label>
                    <label class="toggle-switch">
                        <input type="checkbox" id="toggle-voice-interrupt" checked>
                        <span class="toggle-slider"></span>
                    </label>
                </div>
                <p class="settings-hint">Activity and search panels open automatically when data is available. Thinking sounds play a short cue while the AI processes. Voice interruption lets you interrupt the AI by speaking — it will stop talking and listen to you.</p>
            </div>
        </div>
        <div class="panel-overlay" id="panel-overlay" aria-hidden="true"></div>
        <div class="speech-widget" id="speech-widget" aria-hidden="true">
            <div class="speech-widget-inner">
                <span class="speech-widget-label">Listening...</span>
                <span class="speech-widget-text" id="speech-widget-text"></span>
            </div>
        </div>
        <div class="toast-container" id="toast-container" aria-live="polite"></div>
        <div class="cam-panel" id="cam-panel" aria-hidden="true">
            <div class="cam-panel-header" id="cam-panel-header">
                <span class="cam-panel-title">
                    <span class="cam-panel-dot"></span>
                    Vision
                </span>
                <div class="cam-panel-controls">
                    <label class="cam-panel-vision-mode" title="Vision Mode — attach camera to every message">
                        <input type="checkbox" id="cam-vision-mode" />
                        <span class="cam-panel-vision-label">Live</span>
                    </label>
                    <button class="cam-panel-btn cam-minimize" id="cam-minimize" title="Minimize">−</button>
                    <button class="cam-panel-btn cam-close" id="cam-close" title="Close camera">×</button>
                </div>
            </div>
            <div class="cam-panel-body">
                <video id="cam-video" autoplay playsinline muted></video>
                <div class="cam-panel-overlay">
                    <span class="cam-panel-status">Vision ready</span>
                </div>
            </div>
            <div class="cam-panel-resize" id="cam-panel-resize" title="Drag to resize"></div>
        </div>
        <canvas id="cam-canvas" style="display: none;"></canvas>
    </div>
    <script src="orb.js"></script>
    <script src="script.js"></script>
</body>
</html>
</file>

<file path="JARVIS/frontend/orb.js">
class OrbRenderer {
    constructor(container, opts = {}) {
        this.container = container;
        this.hue = opts.hue ?? 0;
        this.hoverIntensity = opts.hoverIntensity ?? 0.2;
        this.bgColor = opts.backgroundColor ?? [0.02, 0.02, 0.06];
        this.targetHover = 0;
        this.currentHover = 0;
        this.currentRot = 0;
        this.lastTs = 0;
        this.canvas = document.createElement('canvas');
        this.canvas.style.width = '100%';
        this.canvas.style.height = '100%';
        this.container.appendChild(this.canvas);
        this.gl = this.canvas.getContext('webgl', { alpha: true, premultipliedAlpha: false, antialias: false });
        if (!this.gl) { console.warn('WebGL not available'); return; }
        this._build();
        this._resize();
        this._onResize = this._resize.bind(this);
        window.addEventListener('resize', this._onResize);
        this._raf = requestAnimationFrame(this._loop.bind(this));
    }
    static VERT = `
    precision highp float;
    attribute vec2 position;
    attribute vec2 uv;
    varying vec2 vUv;
    void main(){ vUv=uv; gl_Position=vec4(position,0.0,1.0); }`;
    static FRAG = `
    precision highp float;
    uniform float iTime;
    uniform vec3  iResolution;
    uniform float hue;
    uniform float hover;
    uniform float rot;
    uniform float hoverIntensity;
    uniform vec3  backgroundColor;
    varying vec2  vUv;
    /* ----- Color-space conversion: RGB ↔ YIQ ----- */
    // YIQ is the color model used by NTSC television. Converting to
    // YIQ lets us rotate the hue of any color by simply rotating the
    // I and Q components, then converting back to RGB.
    vec3 rgb2yiq(vec3 c){float y=dot(c,vec3(.299,.587,.114));float i=dot(c,vec3(.596,-.274,-.322));float q=dot(c,vec3(.211,-.523,.312));return vec3(y,i,q);}
    vec3 yiq2rgb(vec3 c){return vec3(c.x+.956*c.y+.621*c.z,c.x-.272*c.y-.647*c.z,c.x-1.106*c.y+1.703*c.z);}
    // adjustHue: rotate a color's hue by 'hueDeg' degrees.
    // 1. Convert RGB → YIQ.
    // 2. Rotate the (I, Q) pair by the hue angle (2D rotation matrix).
    // 3. Convert YIQ → RGB.
    vec3 adjustHue(vec3 color,float hueDeg){float h=hueDeg*3.14159265/180.0;vec3 yiq=rgb2yiq(color);float cosA=cos(h);float sinA=sin(h);float i2=yiq.y*cosA-yiq.z*sinA;float q2=yiq.y*sinA+yiq.z*cosA;yiq.y=i2;yiq.z=q2;return yiq2rgb(yiq);}

    /* ----- 3D Simplex Noise (snoise3) ----- */
    // Simplex noise is a smooth, natural-looking pseudo-random function
    // invented by Ken Perlin. Given a 3D coordinate it returns a value
    // roughly in [-1, 1]. By feeding (uv, time) we get animated,
    // organic-looking variation that drives the orb's wobbly edge.
    //
    // hash33: a cheap hash that maps a vec3 to a pseudo-random vec3 in
    //         [-1, 1]. Used internally by the noise to create random
    //         gradient vectors at each lattice point.
    vec3 hash33(vec3 p3){p3=fract(p3*vec3(.1031,.11369,.13787));p3+=dot(p3,p3.yxz+19.19);return -1.0+2.0*fract(vec3(p3.x+p3.y,p3.x+p3.z,p3.y+p3.z)*p3.zyx);}

    // snoise3: the actual 3D simplex noise implementation.
    // K1 and K2 are the skew/unskew constants for a 3D simplex grid.
    // The function:
    //   1. Skews the input into simplex (tetrahedral) space.
    //   2. Determines which simplex cell the point falls in.
    //   3. Computes distance vectors to each of the cell's 4 corners.
    //   4. For each corner, evaluates a radial falloff kernel multiplied
    //      by the dot product of a pseudo-random gradient and the
    //      distance vector.
    //   5. Sums the contributions and scales to roughly [-1, 1].
    float snoise3(vec3 p){const float K1=.333333333;const float K2=.166666667;vec3 i=floor(p+(p.x+p.y+p.z)*K1);vec3 d0=p-(i-(i.x+i.y+i.z)*K2);vec3 e=step(vec3(0.0),d0-d0.yzx);vec3 i1=e*(1.0-e.zxy);vec3 i2=1.0-e.zxy*(1.0-e);vec3 d1=d0-(i1-K2);vec3 d2=d0-(i2-K1);vec3 d3=d0-0.5;vec4 h=max(0.6-vec4(dot(d0,d0),dot(d1,d1),dot(d2,d2),dot(d3,d3)),0.0);vec4 n=h*h*h*h*vec4(dot(d0,hash33(i)),dot(d1,hash33(i+i1)),dot(d2,hash33(i+i2)),dot(d3,hash33(i+1.0)));return dot(vec4(31.316),n);}

    // extractAlpha: the orb is rendered on a transparent background.
    // This helper takes an RGB color and derives an alpha from the
    // brightest channel. That way fully-black areas become transparent
    // and bright areas become opaque — giving us a soft-edged glow
    // without needing a separate alpha mask.
    vec4 extractAlpha(vec3 c){float a=max(max(c.r,c.g),c.b);return vec4(c/(a+1e-5),a);}

    /* ----- Palette & geometry constants ----- */
    // Three base colors that define the orb's purple-cyan palette.
    // They get hue-shifted at runtime by the 'hue' uniform.
    const vec3 baseColor1=vec3(.611765,.262745,.996078);   // vivid purple
    const vec3 baseColor2=vec3(.298039,.760784,.913725);   // cyan / teal
    const vec3 baseColor3=vec3(.062745,.078431,.600000);   // deep indigo

    const float innerRadius=0.6;   // normalized radius of the orb's inner core
    const float noiseScale=0.65;   // how zoomed-in the noise pattern is

    /* ----- Procedural light falloff helpers ----- */
    // light1: inverse-distance falloff  →  I / (1 + d·a)
    // light2: inverse-square falloff    →  I / (1 + d²·a)
    // 'i' = intensity, 'a' = attenuation, 'd' = distance.
    // These give the orb its glowing highlight spots.
    float light1(float i,float a,float d){return i/(1.0+d*a);}
    float light2(float i,float a,float d){return i/(1.0+d*d*a);}

    /* ----- draw(): the core orb rendering routine ----- */
    // Given a UV coordinate (centered, normalized so the short axis
    // spans -1 to 1), this function returns an RGBA color for that
    // pixel.
    //
    // Step-by-step:
    //   1. Hue-shift the three base colors.
    //   2. Convert the UV to polar-ish helpers (angle and length).
    //   3. Sample 3D simplex noise at (uv, time) to create organic,
    //      time-varying distortion.
    //   4. Compute a wobbly radius (r0) from the noise — this is what
    //      makes the edge of the orb undulate.
    //   5. Calculate multiple light/glow terms:
    //        v0 – main glow field (radial, noise-modulated)
    //        v1 – an orbiting highlight point
    //        v2, v3 – radial fade masks that confine color to the orb
    //   6. Blend the base colors using the angular position (cl) so
    //      the orb shifts between purple and cyan as you go around it.
    //   7. Compose a "dark" version and a "light" version of the orb,
    //      then blend between them based on background luminance so
    //      the orb looks good on both dark and light UIs.
    //   8. Pass the result through extractAlpha to get proper
    //      transparency for compositing.
    vec4 draw(vec2 uv){
        vec3 c1=adjustHue(baseColor1,hue);vec3 c2=adjustHue(baseColor2,hue);vec3 c3=adjustHue(baseColor3,hue);
        float ang=atan(uv.y,uv.x);float len=length(uv);float invLen=len>0.0?1.0/len:0.0;
        float bgLum=dot(backgroundColor,vec3(.299,.587,.114));  // perceptual luminance of the bg
        float n0=snoise3(vec3(uv*noiseScale,iTime*0.5))*0.5+0.5;  // noise remapped to [0,1]
        float r0=mix(mix(innerRadius,1.0,0.4),mix(innerRadius,1.0,0.6),n0);  // wobbly radius
        float d0=distance(uv,(r0*invLen)*uv);  // distance from pixel to the wobbly edge
        float v0=light1(1.0,10.0,d0);          // main radial glow
        v0*=smoothstep(r0*1.05,r0,len);        // hard-ish cutoff just outside the radius
        float innerFade=smoothstep(r0*0.8,r0*0.95,len);  // fade near the center
        v0*=mix(innerFade,1.0,bgLum*0.7);
        float cl=cos(ang+iTime*2.0)*0.5+0.5;  // angular color blend (rotates over time)
        float a2=iTime*-1.0;vec2 pos=vec2(cos(a2),sin(a2))*r0;float d=distance(uv,pos);  // orbiting light
        float v1=light2(1.5,5.0,d);v1*=light1(1.0,50.0,d0);  // highlight with quick falloff
        float v2=smoothstep(1.0,mix(innerRadius,1.0,n0*0.5),len);  // outer fade mask
        float v3=smoothstep(innerRadius,mix(innerRadius,1.0,0.5),len);  // inner→outer ramp
        vec3 colBase=mix(c1,c2,cl);  // angular purple↔cyan blend
        float fadeAmt=mix(1.0,0.1,bgLum);
        // "dark" composite — used on dark backgrounds
        vec3 darkCol=mix(c3,colBase,v0);darkCol=(darkCol+v1)*v2*v3;darkCol=clamp(darkCol,0.0,1.0);
        // "light" composite — blends toward the background color
        vec3 lightCol=(colBase+v1)*mix(1.0,v2*v3,fadeAmt);lightCol=mix(backgroundColor,lightCol,v0);lightCol=clamp(lightCol,0.0,1.0);
        // final mix: lean toward lightCol when the background is bright
        vec3 fc=mix(darkCol,lightCol,bgLum);
        return extractAlpha(fc);
    }

    /* ----- mainImage(): entry point called by main() ----- */
    // Transforms the raw pixel coordinate into a centered, normalized
    // UV, applies rotation and the wavy hover distortion, then calls
    // draw().
    vec4 mainImage(vec2 fragCoord){
        vec2 center=iResolution.xy*0.5;float sz=min(iResolution.x,iResolution.y);
        vec2 uv=(fragCoord-center)/sz*2.0;  // center and normalize UV to [-1,1] on short axis
        // Apply 2D rotation (accumulated while the orb is "active")
        float s2=sin(rot);float c2=cos(rot);uv=vec2(c2*uv.x-s2*uv.y,s2*uv.x+c2*uv.y);
        // Wavy UV distortion driven by 'hover' (0→1 when active)
        uv.x+=hover*hoverIntensity*0.1*sin(uv.y*10.0+iTime);
        uv.y+=hover*hoverIntensity*0.1*sin(uv.x*10.0+iTime);
        return draw(uv);
    }

    /* ----- main(): GLSL entry point ----- */
    // Converts the varying vUv (0-1 range) back to pixel coordinates,
    // calls mainImage(), and writes the final pre-multiplied alpha
    // color to gl_FragColor.
    void main(){
        vec2 fc=vUv*iResolution.xy;vec4 col=mainImage(fc);
        gl_FragColor=vec4(col.rgb*col.a,col.a);
    }`;

    _compile(type, src) {
        const gl = this.gl;
        const s = gl.createShader(type);
        gl.shaderSource(s, src);
        gl.compileShader(s);
        if (!gl.getShaderParameter(s, gl.COMPILE_STATUS)) {
            console.error('Shader compile error:', gl.getShaderInfoLog(s));
            gl.deleteShader(s);
            return null;
        }
        return s;
    }

    _build() {
        const gl = this.gl;
        const vs = this._compile(gl.VERTEX_SHADER, OrbRenderer.VERT);
        const fs = this._compile(gl.FRAGMENT_SHADER, OrbRenderer.FRAG);
        if (!vs || !fs) return;

        this.pgm = gl.createProgram();
        gl.attachShader(this.pgm, vs);
        gl.attachShader(this.pgm, fs);
        gl.linkProgram(this.pgm);
        if (!gl.getProgramParameter(this.pgm, gl.LINK_STATUS)) {
            console.error('Program link error:', gl.getProgramInfoLog(this.pgm));
            return;
        }
        gl.useProgram(this.pgm);

        const posLoc = gl.getAttribLocation(this.pgm, 'position');
        const uvLoc  = gl.getAttribLocation(this.pgm, 'uv');

        const posBuf = gl.createBuffer();
        gl.bindBuffer(gl.ARRAY_BUFFER, posBuf);
        gl.bufferData(gl.ARRAY_BUFFER, new Float32Array([-1,-1, 3,-1, -1,3]), gl.STATIC_DRAW);
        gl.enableVertexAttribArray(posLoc);
        gl.vertexAttribPointer(posLoc, 2, gl.FLOAT, false, 0, 0);

        const uvBuf = gl.createBuffer();
        gl.bindBuffer(gl.ARRAY_BUFFER, uvBuf);
        gl.bufferData(gl.ARRAY_BUFFER, new Float32Array([0,0, 2,0, 0,2]), gl.STATIC_DRAW);
        gl.enableVertexAttribArray(uvLoc);
        gl.vertexAttribPointer(uvLoc, 2, gl.FLOAT, false, 0, 0);

        this.u = {};
        ['iTime','iResolution','hue','hover','rot','hoverIntensity','backgroundColor'].forEach(name => {
            this.u[name] = gl.getUniformLocation(this.pgm, name);
        });

        gl.enable(gl.BLEND);
        gl.blendFunc(gl.SRC_ALPHA, gl.ONE_MINUS_SRC_ALPHA);
        gl.clearColor(0,0,0,0);
    }

    _resize() {
        const dpr = window.devicePixelRatio || 1;
        const w = this.container.clientWidth;
        const h = this.container.clientHeight;
        this.canvas.width  = w * dpr;
        this.canvas.height = h * dpr;
        if (this.gl) this.gl.viewport(0, 0, this.canvas.width, this.canvas.height);
    }

    _loop(ts) {
        this._raf = requestAnimationFrame(this._loop.bind(this));
        if (!this.pgm) return;
        const gl = this.gl;
        const t = ts * 0.001;
        const dt = this.lastTs ? t - this.lastTs : 0.016;
        this.lastTs = t;

        this.currentHover += (this.targetHover - this.currentHover) * Math.min(dt * 4, 1);

        if (this.currentHover > 0.5) this.currentRot += dt * 0.3;

        gl.clear(gl.COLOR_BUFFER_BIT);
        gl.useProgram(this.pgm);
        gl.uniform1f(this.u.iTime, t);
        gl.uniform3f(this.u.iResolution, this.canvas.width, this.canvas.height, this.canvas.width / this.canvas.height);
        gl.uniform1f(this.u.hue, this.hue);
        gl.uniform1f(this.u.hover, this.currentHover);
        gl.uniform1f(this.u.rot, this.currentRot);
        gl.uniform1f(this.u.hoverIntensity, this.hoverIntensity);
        gl.uniform3f(this.u.backgroundColor, this.bgColor[0], this.bgColor[1], this.bgColor[2]);
        gl.drawArrays(gl.TRIANGLES, 0, 3);
    }

    setActive(active) {
        this.targetHover = active ? 1.0 : 0.0;
        const ctn = this.container;
        if (active) ctn.classList.add('active');
        else ctn.classList.remove('active');
    }

    destroy() {
        cancelAnimationFrame(this._raf);
        window.removeEventListener('resize', this._onResize);
        if (this.canvas.parentNode) this.canvas.parentNode.removeChild(this.canvas);
        const ext = this.gl.getExtension('WEBGL_lose_context');
        if (ext) ext.loseContext();
    }
}
</file>

<file path="JARVIS/frontend/script.js">
const API = (typeof window !== 'undefined' && window.location.origin)
    ? window.location.origin
    : 'http://localhost:8000';

let sessionId = null;
let currentMode = 'jarvis';
let isStreaming = false;
let isListening = false;
let camStream = null;
let autoListenMode = false;
const SPEECH_ERROR_MAX_RETRIES = 3;
let speechErrorRetryCount = 0;
const SPEECH_SEND_DELAY_MS = 500;
const SPEECH_RESTART_DELAY_MS = 700;
let speechSendTimeout = null;
let pendingSendTranscript = null;
let safariVoiceHintShown = false;
let orb = null;
let recognition = null;
let ttsPlayer = null;
const SETTINGS_KEY = 'jarvis_settings';
const DEFAULT_SETTINGS = { autoOpenActivity: true, autoOpenSearchResults: true, thinkingSounds: true, voiceInterrupt: true };
const PRE_STARTER_FILES = ['starter_1', 'starter_2', 'starter_3', 'starter_4', 'starter_5', 'starter_6', 'starter_7', 'starter_8', 'starter_9', 'starter_10'];
let PRE_STARTER_CACHE = {};
let settings = { ...DEFAULT_SETTINGS };
const $ = id => document.getElementById(id);
const chatMessages = $('chat-messages');
const messageInput = $('message-input');
const sendBtn      = $('send-btn');
const micBtn       = $('mic-btn');
const ttsBtn       = $('tts-btn');
const newChatBtn   = $('new-chat-btn');
const charCount    = $('char-count');
const welcomeTitle = $('welcome-title');
const modeSlider   = $('mode-slider');
const btnJarvis    = $('btn-jarvis');
const statusDot    = document.querySelector('.status-dot');
const statusText   = document.querySelector('.status-text');
const orbContainer = $('orb-container');
const searchResultsToggle = $('search-results-toggle');
const searchResultsWidget = $('search-results-widget');
const searchResultsClose  = $('search-results-close');
const searchResultsQuery  = $('search-results-query');
const searchResultsAnswer = $('search-results-answer');
const searchResultsList   = $('search-results-list');
const activityPanel       = $('activity-panel');
const activityToggle      = $('activity-toggle');
const activityClose       = $('activity-close');
const activityList        = $('activity-list');
const panelOverlay        = $('panel-overlay');
const speechWidget        = $('speech-widget');
const speechWidgetText    = $('speech-widget-text');
const settingsBtn         = $('settings-btn');
const camBtn              = $('cam-btn');
const camPanel            = $('cam-panel');
const camVideo            = $('cam-video');
const camCanvas           = $('cam-canvas');
const camVisionModeInput  = $('cam-vision-mode');
const camMinimize         = $('cam-minimize');
const camClose            = $('cam-close');
const camPanelHeader      = $('cam-panel-header');
const camPanelResize      = $('cam-panel-resize');
const settingsPanel       = $('settings-panel');
const settingsClose       = $('settings-close');
const toggleAutoActivity  = $('toggle-auto-activity');
const toggleAutoSearch    = $('toggle-auto-search');
const toggleThinkingSounds = $('toggle-thinking-sounds');
const toggleVoiceInterrupt = $('toggle-voice-interrupt');
const toastContainer     = $('toast-container');

class PreStarterPlayer {
    constructor() {
        this.audio = document.createElement('audio');
        this.audio.preload = 'auto';
    }
    play(onComplete) {
        const loaded = PRE_STARTER_FILES.filter(f => PRE_STARTER_CACHE[f]);
        if (loaded.length === 0) {
            if (onComplete) onComplete();
            return;
        }
        const file = loaded[Math.floor(Math.random() * loaded.length)];
        const base64 = PRE_STARTER_CACHE[file];
        if (!base64) {
            if (onComplete) onComplete();
            return;
        }
        this.audio.src = 'data:audio/mp3;base64,' + base64;
        this.audio.currentTime = 0;
        let fired = false;
        const done = () => {
            if (fired) return;
            fired = true;
            this.audio.onended = null;
            this.audio.onerror = null;
            if (onComplete) onComplete();
        };
        this.audio.onended = done;
        this.audio.onerror = done;
        const p = this.audio.play();
        if (p) p.catch(done);
    }
}

let preStarterPlayer = null;

class TTSPlayer {
    constructor() {
        this.queue = [];
        this.playing = false;
        this.enabled = true;
        this.stopped = false;
        this.audio = document.createElement('audio');
        this.audio.preload = 'auto';
    }
    unlock() {
        const silentWav = 'data:audio/wav;base64,UklGRigAAABXQVZFZm10IBIAAAABAAEARKwAAIhYAQACABAAAABkYXRhAgAAAAEA';
        this.audio.src = silentWav;
        const p = this.audio.play();
        if (p) p.catch(() => {});
        try {
            const ctx = new (window.AudioContext || window.webkitAudioContext)();
            const g = ctx.createGain();
            g.gain.value = 0;
            const o = ctx.createOscillator();
            o.connect(g);
            g.connect(ctx.destination);
            o.start(0);
            o.stop(ctx.currentTime + 0.001);
            setTimeout(() => ctx.close(), 200);
        } catch (_) {}
    }
    enqueue(base64Audio) {
        if (!this.enabled || this.stopped) return;
        this.queue.push(base64Audio);
        if (!this.playing) this._playLoop();
    }
    stop() {
        this.stopped = true;
        this.audio.pause();
        this.audio.removeAttribute('src');
        this.audio.load();
        this.queue = [];
        this.playing = false;
        if (ttsBtn) ttsBtn.classList.remove('tts-speaking');
        if (orbContainer) orbContainer.classList.remove('speaking');
        if (orb) orb.setActive(false);
        if (typeof this.onPlaybackComplete === 'function') this.onPlaybackComplete();
    }
    reset() {
        this.stop();
        this.stopped = false;
        this._loopId = (this._loopId || 0) + 1;
    }
    async _playLoop() {
        if (this.playing) return;
        this.playing = true;
        this._loopId = (this._loopId || 0) + 1;
        const myId = this._loopId;
        if (ttsBtn) ttsBtn.classList.add('tts-speaking');
        if (orbContainer) orbContainer.classList.add('speaking');
        if (orb) orb.setActive(true);
        while (this.queue.length > 0) {
            if (this.stopped || myId !== this._loopId) break;
            const b64 = this.queue.shift();
            try {
                await this._playB64(b64);
            } catch (e) {
                console.warn('TTS segment error:', e);
            }
        }
        if (myId !== this._loopId) {
            this.playing = false;
            return;
        }
        this.playing = false;
        if (ttsBtn) ttsBtn.classList.remove('tts-speaking');
        if (orbContainer) orbContainer.classList.remove('speaking');
        if (orb) orb.setActive(false);
        if (typeof this.onPlaybackComplete === 'function') this.onPlaybackComplete();
    }
    _playB64(b64) {
        return new Promise(resolve => {
            this.audio.src = 'data:audio/mp3;base64,' + b64;
            const done = () => { resolve(); };
            this.audio.onended = done;
            this.audio.onerror = done;
            const p = this.audio.play();
            if (p) p.catch(done);
        });
    }
}

function init() {
    if (!chatMessages || !messageInput) {
        console.error('[JARVIS] Required DOM elements (chat-messages, message-input) not found.');
        return;
    }
    loadSettings();
    ttsPlayer = new TTSPlayer();
    ttsPlayer.onPlaybackComplete = maybeRestartListening;
    if (ttsBtn) ttsBtn.classList.add('tts-active');
    setGreeting();
    initOrb();
    initSpeech();
    preloadStarterAudio();
    preStarterPlayer = new PreStarterPlayer();
    checkHealth();
    bindEvents();
    setMode(currentMode);
    autoResizeInput();
}

async function preloadStarterAudio() {
    const base = (typeof window !== 'undefined' && window.location.origin) ? window.location.origin : '';
    for (const file of PRE_STARTER_FILES) {
        try {
            const r = await fetch(`${base}/app/audio/${file}.mp3`);
            if (!r.ok) continue;
            const blob = await r.blob();
            const base64 = await new Promise((resolve, reject) => {
                const reader = new FileReader();
                reader.onloadend = () => resolve((reader.result || '').split(',')[1] || '');
                reader.onerror = reject;
                reader.readAsDataURL(blob);
            });
            if (base64) PRE_STARTER_CACHE[file] = base64;
        } catch (_) {}
    }
}

function loadSettings() {
    try {
        const s = localStorage.getItem(SETTINGS_KEY);
        if (s) {
            const parsed = JSON.parse(s);
            settings = { ...DEFAULT_SETTINGS, ...parsed };
        }
        if (toggleAutoActivity) toggleAutoActivity.checked = settings.autoOpenActivity;
        if (toggleAutoSearch) toggleAutoSearch.checked = settings.autoOpenSearchResults;
        if (toggleThinkingSounds) toggleThinkingSounds.checked = settings.thinkingSounds;
        if (toggleVoiceInterrupt) toggleVoiceInterrupt.checked = settings.voiceInterrupt;
    } catch (_) {}
}

function saveSettings() {
    try {
        localStorage.setItem(SETTINGS_KEY, JSON.stringify(settings));
    } catch (_) {}
}


function setGreeting() {
    const h = new Date().getHours();
    let g = 'Good evening.';
    if (h < 12) g = 'Good morning.';
    else if (h < 17) g = 'Good afternoon.';
    else if (h >= 22) g = 'Burning the midnight oil?';
    if (welcomeTitle) welcomeTitle.textContent = g;
}

function initOrb() {
    if (typeof OrbRenderer === 'undefined') return;
    try {
        orb = new OrbRenderer(orbContainer, {
            hue: 0,
            hoverIntensity: 0.3,
            backgroundColor: [0.02, 0.02, 0.06]
        });
    } catch (e) { console.warn('Orb init failed:', e); }
}

function isSafariOrIOS() {
    if (typeof navigator === 'undefined') return false;
    const ua = navigator.userAgent || '';
    return /iPad|iPhone|iPod/.test(ua) ||
        (navigator.vendor && navigator.vendor.indexOf('Apple') > -1) ||
        (/Safari/.test(ua) && !/Chrome|Chromium|CriOS/.test(ua));
}

function initSpeech() {
    const SR = window.SpeechRecognition || window.webkitSpeechRecognition;
    if (!SR) { micBtn.title = 'Speech not supported in this browser'; return; }
    recognition = new SR();
    const safariMode = isSafariOrIOS();
    recognition.continuous = false;
    recognition.interimResults = !safariMode;
    recognition.maxAlternatives = 1;
    recognition.lang = 'en-US';
    recognition.onresult = e => {
        if (!e.results || e.results.length === 0) return;
        const last = e.results[e.results.length - 1];
        const transcript = (last && last[0]) ? last[0].transcript.trim() : '';
        const isFinal = last && last.isFinal;
        if (speechWidgetText) speechWidgetText.textContent = transcript;
        if (speechWidget) speechWidget.classList.add('visible');
        if (settings.voiceInterrupt && ttsPlayer && ttsPlayer.playing && transcript.length > 0) {
            ttsPlayer.stop();
            ttsPlayer.stopped = false;
        }
        if (isFinal && transcript) {
            pendingSendTranscript = transcript;
            clearTimeout(speechSendTimeout);
            speechSendTimeout = setTimeout(() => {
                if (pendingSendTranscript) {
                    sendMessage(pendingSendTranscript);
                    pendingSendTranscript = null;
                }
                speechSendTimeout = null;
                stopListening();
            }, SPEECH_SEND_DELAY_MS);
        } else if (!isFinal) {
            pendingSendTranscript = null;
            clearTimeout(speechSendTimeout);
            speechSendTimeout = null;
        }
    };

    recognition.onstart = () => { speechErrorRetryCount = 0; };
    recognition.onerror = e => {
        stopListening();
        const msg = (e && e.error) ? String(e.error) : '';
        const isPermissionDenied = /denied|not-allowed|permission/i.test(msg);
        if (isPermissionDenied && micBtn) {
            micBtn.title = 'Microphone access denied. Allow in browser settings.';
            speechErrorRetryCount = SPEECH_ERROR_MAX_RETRIES;
        }
        if (autoListenMode && !isStreaming && speechErrorRetryCount < SPEECH_ERROR_MAX_RETRIES) {
            speechErrorRetryCount++;
            setTimeout(() => maybeRestartListening(), SPEECH_RESTART_DELAY_MS);
        } else if (speechErrorRetryCount >= SPEECH_ERROR_MAX_RETRIES && micBtn) {
            micBtn.title = 'Voice input — click to try again';
        }
    };

    recognition.onend = () => {
        if (pendingSendTranscript) {
            clearTimeout(speechSendTimeout);
            speechSendTimeout = null;
            sendMessage(pendingSendTranscript);
            pendingSendTranscript = null;
        } else {
            clearTimeout(speechSendTimeout);
            speechSendTimeout = null;
        }
        if (isListening) stopListening();
        maybeRestartListening();
    };
}

function startListening() {
    if (!recognition || isStreaming || isListening) return;
    if (isSafariOrIOS() && !safariVoiceHintShown) {
        showToast('Voice works best in Chrome. Safari has limited support.');
        safariVoiceHintShown = true;
    }
    isListening = true;
    pendingSendTranscript = null;
    clearTimeout(speechSendTimeout);
    speechSendTimeout = null;
    if (micBtn) micBtn.classList.add('listening');
    if (speechWidget) speechWidget.classList.add('visible');
    if (speechWidgetText) speechWidgetText.textContent = '';
    try {
        recognition.start();
    } catch (err) {
        isListening = false;
        if (micBtn) micBtn.classList.remove('listening');
        if (speechWidget) speechWidget.classList.remove('visible');
        if (isSafariOrIOS()) showToast('Tap the mic to continue voice input.');
    }
}

function stopListening() {
    clearTimeout(speechSendTimeout);
    speechSendTimeout = null;
    pendingSendTranscript = null;
    isListening = false;
    if (micBtn) micBtn.classList.remove('listening');
    if (speechWidget) speechWidget.classList.remove('visible');
    if (speechWidgetText) speechWidgetText.textContent = '';
    try { recognition.stop(); } catch (_) {}
}

function maybeRestartListening() {
    if (!autoListenMode || !recognition) return;
    if (isStreaming) return;

    const ttsActive = ttsPlayer && (ttsPlayer.playing || ttsPlayer.queue.length > 0);
    if (ttsActive && !settings.voiceInterrupt) return;

    const delay = ttsActive ? 150 : SPEECH_RESTART_DELAY_MS;
    setTimeout(() => {
        if (autoListenMode && !isStreaming && !isListening && recognition) {
            startListening();
        }
    }, delay);
}

const CAM_BYPASS_TOKEN = 'TTCAMTOKENTT';
const CAMERA_QUERY_PATTERNS = [
    /what\s+(can|do)\s+you\s+see/i,
    /can\s+you\s+see/i,
    /describe\s+(what\s+you\s+see|this|the\s+image)/i,
    /what('s|s)\sss+in\sss+(this\sss+)?(picture|image)/i,
    /what\s+do\s+i\s+look\s+like/i,
    /what\s+(am\s+i\s+)?holding/i,
    /show\s+me\s+what\s+you\s+see/i,
];
function isCameraQuery(text) {
    if (!text || typeof text !== 'string') return false;
    const t = text.trim().toLowerCase();
    return CAMERA_QUERY_PATTERNS.some(r => r.test(t)) ||
        (t.includes('see') && (t.includes('what') || t.includes('describe')));
}

function startCamera() {
    if (!navigator.mediaDevices || !navigator.mediaDevices.getUserMedia) {
        showToast('Camera not supported in this browser.');
        return Promise.reject(new Error('Camera not supported'));
    }
    if (camStream) return Promise.resolve();
    return navigator.mediaDevices.getUserMedia({ video: { facingMode: 'user' }, audio: false })
        .then(stream => {
            camStream = stream;
            if (camVideo) camVideo.srcObject = stream;
            if (camPanel) { camPanel.classList.add('visible'); camPanel.setAttribute('aria-hidden', 'false'); }
            if (camBtn) {
                camBtn.classList.add('cam-active');
                camBtn.title = 'Camera on — click to turn off';
                const icon = camBtn.querySelector('.cam-icon');
                const iconActive = camBtn.querySelector('.cam-icon-active');
                if (icon) icon.style.display = 'none';
                if (iconActive) iconActive.style.display = '';
            }
        })
        .catch(err => {
            showToast('Camera access denied. ' + (err.message || ''));
            throw err;
        });
}

function stopCamera() {
    if (camStream) {
        camStream.getTracks().forEach(t => t.stop());
        camStream = null;
    }
    if (camVideo) camVideo.srcObject = null;
    if (camPanel) { camPanel.classList.remove('visible'); camPanel.setAttribute('aria-hidden', 'true'); }
    if (camVisionModeInput) camVisionModeInput.checked = false;
    if (camBtn) {
        camBtn.classList.remove('cam-active');
        camBtn.title = 'Camera — capture and send for vision';
        const icon = camBtn.querySelector('.cam-icon');
        const iconActive = camBtn.querySelector('.cam-icon-active');
        if (icon) icon.style.display = '';
        if (iconActive) iconActive.style.display = 'none';
    }
}

function initCameraPanel() {
    if (!camPanel) return;
    let dragStart = { x: 0, y: 0, left: 0, top: 0 };
    let resizeStart = { x: 0, y: 0, w: 0, h: 0 };
    if (camClose) camClose.addEventListener('click', () => stopCamera());
    if (camMinimize) camMinimize.addEventListener('click', () => {
        camPanel.classList.toggle('minimized');
    });
    if (camPanelHeader) {
        camPanelHeader.addEventListener('mousedown', (e) => {
            if (e.target.closest('.cam-panel-btn, .cam-panel-vision-mode')) return;
            e.preventDefault();
            const r = camPanel.getBoundingClientRect();
            dragStart = { x: e.clientX, y: e.clientY, left: r.left, top: r.top };
            const onMove = (ev) => {
                const dx = ev.clientX - dragStart.x;
                const dy = ev.clientY - dragStart.y;
                camPanel.style.left = (dragStart.left + dx) + 'px';
                camPanel.style.top = (dragStart.top + dy) + 'px';
                camPanel.style.right = 'auto';
                camPanel.style.bottom = 'auto';
            };
            const onUp = () => { document.removeEventListener('mousemove', onMove); document.removeEventListener('mouseup', onUp); };
            document.addEventListener('mousemove', onMove);
            document.addEventListener('mouseup', onUp);
        });
    }
    if (camPanelResize) {
        camPanelResize.addEventListener('mousedown', (e) => {
            e.preventDefault();
            e.stopPropagation();
            const r = camPanel.getBoundingClientRect();
            resizeStart = { x: e.clientX, y: e.clientY, w: r.width, h: r.height };
            const onMove = (ev) => {
                const dw = ev.clientX - resizeStart.x;
                const dh = ev.clientY - resizeStart.y;
                const nw = Math.max(200, Math.min(window.innerWidth, resizeStart.w + dw));
                const nh = Math.max(150, Math.min(window.innerHeight * 0.7, resizeStart.h + dh));
                camPanel.style.width = nw + 'px';
                camPanel.style.height = nh + 'px';
            };
            const onUp = () => { document.removeEventListener('mousemove', onMove); document.removeEventListener('mouseup', onUp); };
            document.addEventListener('mousemove', onMove);
            document.addEventListener('mouseup', onUp);
        });
    }
    camPanel.addEventListener('dblclick', (e) => {
        if (e.target.closest('.cam-panel-header') && !e.target.closest('.cam-panel-btn, .cam-panel-vision-mode')) {
            camPanel.classList.toggle('minimized');
        }
    });
    camPanel.querySelector('.cam-panel-body')?.addEventListener('click', (e) => {
        if (camPanel.classList.contains('minimized')) camPanel.classList.remove('minimized');
    });
}

function handleActions(actions, contentEl) {
    if (!actions) return;
    if (!contentEl) return;
    const safeOpen = url => {
        if (url && (url.startsWith('http://') || url.startsWith('https://'))) {
            try {
                const w = window.open(url, '_blank', 'noopener');
                if (!w) showToast('Pop-up blocked. Please allow pop-ups or copy the URL.');
            } catch (_) {
                showToast('Could not open link. Please try again.');
            }
        }
    };
    (actions.wopens || []).forEach(safeOpen);
    (actions.plays || []).forEach(safeOpen);
    (actions.googlesearches || []).forEach(safeOpen);
    (actions.youtubesearches || []).forEach(safeOpen);
    if (actions.images && actions.images.length > 0) {
        const wrap = document.createElement('div');
        wrap.className = 'msg-actions-images';
        actions.images.forEach(url => {
            const img = document.createElement('img');
            img.src = url;
            img.alt = 'Generated image';
            img.className = 'msg-action-image';
            img.loading = 'lazy';
            img.onerror = () => {
                img.style.display = 'none';
                const fallback = document.createElement('div');
                fallback.className = 'msg-action-image-fallback';
                fallback.textContent = 'Image failed to load.';
                wrap.appendChild(fallback);
            };
            wrap.appendChild(img);
        });
        contentEl.appendChild(wrap);
    }
    if (actions.contents && actions.contents.length > 0) {
        const wrap = document.createElement('div');
        wrap.className = 'msg-actions-contents';
        actions.contents.forEach(t => {
            const p = document.createElement('div');
            p.className = 'msg-action-content';
            p.textContent = t;
            wrap.appendChild(p);
        });
        contentEl.appendChild(wrap);
    }
    if (actions.cam) {
        if (actions.cam.action === 'open') {
            startCamera();
        } else if (actions.cam.action === 'close') {
            stopCamera();
        } else if (actions.cam.action === 'open_and_capture') {
            const resendMsg = actions.cam.resend_message || 'What do you see?';
            (async () => {
                try {
                    await startCamera();
                    await new Promise((resolve) => {
                        if (!camVideo) { resolve(); return; }
                        if (camVideo.readyState >= 2 && camVideo.videoWidth > 0) {
                            setTimeout(resolve, 500);
                            return;
                        }
                        const onReady = () => {
                            camVideo.removeEventListener('loadeddata', onReady);
                            clearTimeout(t);
                            setTimeout(resolve, 600);
                        };
                        const t = setTimeout(() => {
                            camVideo.removeEventListener('loadeddata', onReady);
                            resolve();
                        }, 4000);
                        camVideo.addEventListener('loadeddata', onReady);
                    });
                    const frame = await captureFrameAsBase64Safe();
                    if (frame) {
                        sendMessageWithImage(resendMsg, frame);
                    } else {
                        showToast('Could not capture camera frame. Please try again.');
                    }
                } catch (err) {
                    showToast('Camera access denied.');
                }
            })();
        }
    }
}

function handleBackgroundTasks(tasks, contentEl) {
    if (!tasks || !tasks.length || !contentEl) return;
    tasks.forEach(task => {
        const card = document.createElement('div');
        card.className = 'bg-task-card';
        card.dataset.taskId = task.task_id;
        const label = task.type === 'generate image' ? 'Image Generation' : task.type === 'content' ? 'Content Writing' : task.type;
        const promptText = task.label ? `"${task.label}"` : '';
        card.innerHTML =
            '<div class="bg-task-header">' +
                '<div class="bg-task-spinner"></div>' +
                '<span class="bg-task-label">' + label + '</span>' +
                '<span class="bg-task-status">Working...</span>' +
            '</div>' +
            (promptText ? '<div class="bg-task-prompt">' + promptText + '</div>' : '');
        contentEl.appendChild(card);
        scrollToBottom();
        pollBackgroundTask(task.task_id, card);
    });
}

function pollBackgroundTask(taskId, cardEl) {
    let pollCount = 0;
    const maxPolls = 120;
    const interval = setInterval(() => {
        pollCount++;
        if (pollCount > maxPolls) {
            clearInterval(interval);
            updateTaskCard(cardEl, 'failed', 'Timed out');
            return;
        }
        fetch(`${API}/tasks/${encodeURIComponent(taskId)}`)
            .then(r => {
                if (!r.ok) throw new Error(`HTTP ${r.status}`);
                return r.json();
            })
            .then(data => {
                if (data.status === 'completed') {
                    clearInterval(interval);
                    updateTaskCard(cardEl, 'completed', data);
                } else if (data.status === 'failed') {
                    clearInterval(interval);
                    updateTaskCard(cardEl, 'failed', data.error || 'Task failed');
                }
            })
            .catch(() => {  });
    }, 1500);
}

function updateTaskCard(cardEl, status, data) {
    if (!cardEl) return;
    const spinner = cardEl.querySelector('.bg-task-spinner');
    const statusEl = cardEl.querySelector('.bg-task-status');
    if (status === 'completed') {
        if (spinner) spinner.className = 'bg-task-done-icon';
        if (statusEl) statusEl.textContent = 'Ready!';
        cardEl.classList.add('bg-task-done');
        const viewBtn = document.createElement('button');
        viewBtn.className = 'bg-task-view-btn';
        viewBtn.textContent = 'Open in new tab';
        viewBtn.addEventListener('click', () => {
            const taskId = cardEl.dataset.taskId;
            window.open(`${window.location.origin}/app/viewer.html?task_id=${taskId}`, '_blank');
        });
        cardEl.appendChild(viewBtn);
        try {
            const taskId = cardEl.dataset.taskId;
            const w = window.open(`${window.location.origin}/app/viewer.html?task_id=${taskId}`, '_blank');
            if (!w) {
                showToast('Result ready! Click "Open in new tab" to view.');
            }
        } catch (_) {  }
    } else if (status === 'failed') {
        if (spinner) spinner.className = 'bg-task-fail-icon';
        if (statusEl) statusEl.textContent = typeof data === 'string' ? data : 'Failed';
        cardEl.classList.add('bg-task-failed');
    }
    scrollToBottom();
}

function captureFrameAsBase64() {
    if (!camVideo || !camStream || camVideo.readyState < 2) return null;
    if (!camCanvas) return null;
    const w = camVideo.videoWidth;
    const h = camVideo.videoHeight;
    if (!w || !h || w < 64 || h < 64) return null;
    camCanvas.width = w;
    camCanvas.height = h;
    const ctx = camCanvas.getContext('2d');
    if (!ctx) return null;
    ctx.drawImage(camVideo, 0, 0, w, h);
    try {
        return camCanvas.toDataURL('image/jpeg', 0.85).split(',')[1];
    } catch (_) {
        return null;
    }
}

async function captureFrameAsBase64Safe() {
    if (!camVideo || !camStream || !camCanvas) return null;
    return new Promise((resolve) => {
        const doCapture = () => {
            const w = camVideo.videoWidth;
            const h = camVideo.videoHeight;
            if (!w || !h || w < 64 || h < 64) {
                resolve(null);
                return;
            }
            camCanvas.width = w;
            camCanvas.height = h;
            const ctx = camCanvas.getContext('2d');
            if (!ctx) { resolve(null); return; }
            ctx.drawImage(camVideo, 0, 0, w, h);
            try {
                const b64 = camCanvas.toDataURL('image/jpeg', 0.9).split(',')[1];
                resolve(b64);
            } catch (_) {
                resolve(null);
            }
        };
        if (camVideo.readyState < 2) {
            const onReady = () => { camVideo.removeEventListener('loadeddata', onReady); doCapture(); };
            camVideo.addEventListener('loadeddata', onReady);
            setTimeout(() => { camVideo.removeEventListener('loadeddata', onReady); doCapture(); }, 3000);
            return;
        }
        const w = camVideo.videoWidth;
        const h = camVideo.videoHeight;
        if (w && h && w >= 64 && h >= 64) {
            if (typeof camVideo.requestVideoFrameCallback === 'function') {
                camVideo.requestVideoFrameCallback(() => { doCapture(); });
            } else {
                setTimeout(doCapture, 150);
            }
        } else {
            setTimeout(() => {
                const w2 = camVideo.videoWidth || 0;
                const h2 = camVideo.videoHeight || 0;
                if (w2 && h2 && w2 >= 64 && h2 >= 64) doCapture();
                else resolve(null);
            }, 300);
        }
    });
}

async function sendMessageWithImage(text, imgBase64) {
    if (!text || !imgBase64 || isStreaming) return;
    const messageToSend = text + ' ' + CAM_BYPASS_TOKEN;
    addMessage('user', text);
    addTypingIndicator();
    isStreaming = true;
    if (sendBtn) sendBtn.disabled = true;
    if (messageInput) messageInput.disabled = true;
    if (orbContainer) orbContainer.classList.add('active');
    if (ttsPlayer) { ttsPlayer.reset(); ttsPlayer.unlock(); }
    let timeoutId = null;
    const controller = new AbortController();
    try {
        timeoutId = setTimeout(() => controller.abort(), 300000);
        const res = await fetch(`${API}/chat/jarvis/stream`, {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify({
                message: messageToSend,
                session_id: sessionId,
                tts: !!(ttsPlayer && ttsPlayer.enabled),
                imgbase64: imgBase64,
            }),
            signal: controller.signal,
        });
        if (!res.ok) throw new Error(`HTTP ${res.status}`);
        removeTypingIndicator();
        const contentEl = addMessage('assistant', '');
        contentEl.innerHTML = '<span class="msg-stream-text">...</span>';
        scrollToBottom();
        if (!res.body) throw new Error('No response body');
        const reader = res.body.getReader();
        const decoder = new TextDecoder();
        let sseBuffer = '';
        let fullResponse = '';
        let cursorEl = null;
        let streamDone = false;
        while (!streamDone) {
            const { done, value } = await reader.read();
            if (done) break;
            sseBuffer += decoder.decode(value, { stream: true });
            const lines = sseBuffer.split('\n\n');
            sseBuffer = lines.pop();
            for (const line of lines) {
                if (!line.startsWith('data: ')) continue;
                try {
                    const data = JSON.parse(line.slice(6));
                    if (data.session_id) sessionId = data.session_id;
                    if (data.activity) {
                        appendActivity(data.activity);
                        if (activityToggle) activityToggle.style.display = '';
                        if (activityPanel && settings.autoOpenActivity) { activityPanel.classList.add('open'); updatePanelOverlay(); }
                    }
                    if (data.actions) handleActions(data.actions, contentEl);
                    if (data.background_tasks) handleBackgroundTasks(data.background_tasks, contentEl);
                    if ('chunk' in data) {
                        const chunkText = data.chunk || '';
                        fullResponse += chunkText;
                        const textSpan = contentEl.querySelector('.msg-stream-text');
                        if (textSpan) {
                            textSpan.textContent = fullResponse;
                            textSpan.classList.remove('stream-placeholder');
                        }
                        if (!cursorEl) {
                            cursorEl = document.createElement('span');
                            cursorEl.className = 'stream-cursor';
                            cursorEl.textContent = '|';
                            contentEl.appendChild(cursorEl);
                        }
                        scrollToBottom();
                    }
                    if (data.audio && ttsPlayer) ttsPlayer.enqueue(data.audio);
                    if (data.error) throw new Error(data.error);
                    if (data.done) { streamDone = true; break; }
                } catch (parseErr) {
                    if (parseErr.message && !parseErr.message.includes('JSON')) throw parseErr;
                }
            }
            if (streamDone) break;
        }
        if (cursorEl) cursorEl.remove();
        const textSpan = contentEl.querySelector('.msg-stream-text');
        if (textSpan && !fullResponse) textSpan.textContent = '(No response)';
    } catch (err) {
        clearTimeout(timeoutId);
        removeTypingIndicator();
        addMessage('assistant', 'Something went wrong analyzing the image. Please try again.');
    } finally {
        clearTimeout(timeoutId);
        isStreaming = false;
        if (sendBtn) sendBtn.disabled = false;
        if (messageInput) messageInput.disabled = false;
        if (orbContainer) orbContainer.classList.remove('active');
    }
}

async function checkHealth() {
    try {
        const controller = new AbortController();
        const timeoutId = setTimeout(() => controller.abort(), 5000);
        const r = await fetch(`${API}/health`, { signal: controller.signal });
        clearTimeout(timeoutId);
        const d = await r.json().catch(() => null);
        const ok = d && (d.status === 'healthy' || d.status === 'degraded');
        if (statusDot) statusDot.classList.toggle('offline', !ok);
        if (statusText) statusText.textContent = ok ? 'Online' : 'Offline';
    } catch (e) {
        if (statusDot) statusDot.classList.add('offline');
        if (statusText) statusText.textContent = 'Offline';
        if (typeof console !== 'undefined' && console.warn) console.warn('[Health] Check failed:', e);
    }
}

function showToast(msg, durationMs = 5000) {
    if (!toastContainer || !msg) return;
    const el = document.createElement('div');
    el.className = 'toast';
    el.textContent = msg;
    toastContainer.appendChild(el);
    el.offsetHeight;
    el.classList.add('toast-visible');
    const t = setTimeout(() => {
        el.classList.remove('toast-visible');
        setTimeout(() => el.remove(), 300);
    }, durationMs);
    el.addEventListener('click', () => { clearTimeout(t); el.classList.remove('toast-visible'); setTimeout(() => el.remove(), 300); });
}

function bindEvents() {
    if (sendBtn) sendBtn.addEventListener('click', () => { if (!isStreaming) sendMessage(); });
    if (messageInput) messageInput.addEventListener('keydown', e => {
        if (e.key === 'Enter' && !e.shiftKey) { e.preventDefault(); if (!isStreaming) sendMessage(); }
    });
    if (messageInput) messageInput.addEventListener('input', () => {
        autoResizeInput();
        const len = messageInput.value.length;
        if (charCount) charCount.textContent = len > 100 ? `${len.toLocaleString()} / 32,000` : '';
    });
    if (camBtn) camBtn.addEventListener('click', () => {
        if (camStream) stopCamera();
        else startCamera();
    });
    initCameraPanel();
    if (micBtn) micBtn.addEventListener('click', () => {
        if (isListening) {
            autoListenMode = false;
            stopListening();
            if (micBtn) micBtn.classList.remove('auto-listen');
        } else {
            autoListenMode = true;
            speechErrorRetryCount = 0;
            if (micBtn) {
                micBtn.classList.add('auto-listen');
                micBtn.title = 'Voice input — click to stop auto-listen';
            }
            startListening();
        }
    });
    if (ttsBtn) ttsBtn.addEventListener('click', () => {
        if (ttsPlayer) ttsPlayer.enabled = !ttsPlayer.enabled;
        ttsBtn.classList.toggle('tts-active', ttsPlayer && ttsPlayer.enabled);
        if (ttsPlayer && !ttsPlayer.enabled) ttsPlayer.stop();
    });
    if (newChatBtn) newChatBtn.addEventListener('click', newChat);
    if (btnJarvis) btnJarvis.addEventListener('click', () => setMode('jarvis'));
    document.querySelectorAll('.chip').forEach(c => {
        c.addEventListener('click', () => { if (!isStreaming) sendMessage(c.dataset.msg); });
    });
    if (searchResultsToggle) {
        searchResultsToggle.addEventListener('click', () => {
            if (searchResultsWidget) { searchResultsWidget.classList.toggle('open'); updatePanelOverlay(); }
        });
    }
    if (searchResultsClose && searchResultsWidget) {
        searchResultsClose.addEventListener('click', () => { searchResultsWidget.classList.remove('open'); updatePanelOverlay(); });
    }
    if (activityToggle) {
        activityToggle.addEventListener('click', () => {
            if (activityPanel) { activityPanel.classList.toggle('open'); updatePanelOverlay(); }
        });
    }
    if (activityClose && activityPanel) {
        activityClose.addEventListener('click', () => { activityPanel.classList.remove('open'); updatePanelOverlay(); });
    }
    if (settingsBtn && settingsPanel) {
        settingsBtn.addEventListener('click', () => {
            settingsPanel.classList.toggle('open');
            updatePanelOverlay();
        });
    }
    if (settingsClose && settingsPanel) {
        settingsClose.addEventListener('click', () => {
            settingsPanel.classList.remove('open');
            updatePanelOverlay();
        });
    }
    if (toggleAutoActivity) {
        toggleAutoActivity.addEventListener('change', () => {
            settings.autoOpenActivity = toggleAutoActivity.checked;
            saveSettings();
        });
    }
    if (toggleAutoSearch) {
        toggleAutoSearch.addEventListener('change', () => {
            settings.autoOpenSearchResults = toggleAutoSearch.checked;
            saveSettings();
        });
    }
    if (toggleThinkingSounds) {
        toggleThinkingSounds.addEventListener('change', () => {
            settings.thinkingSounds = toggleThinkingSounds.checked;
            saveSettings();
        });
    }
    if (toggleVoiceInterrupt) {
        toggleVoiceInterrupt.addEventListener('change', () => {
            settings.voiceInterrupt = toggleVoiceInterrupt.checked;
            saveSettings();
        });
    }
}

function autoResizeInput() {
    messageInput.style.height = 'auto';
    messageInput.style.height = Math.min(messageInput.scrollHeight, 120) + 'px';
}

function updatePanelOverlay() {
    if (!panelOverlay) return;
    const anyOpen = (activityPanel && activityPanel.classList.contains('open')) ||
        (searchResultsWidget && searchResultsWidget.classList.contains('open')) ||
        (settingsPanel && settingsPanel.classList.contains('open'));
    panelOverlay.classList.toggle('visible', !!anyOpen);
}

function setMode(mode) {
    currentMode = mode || 'jarvis';
    if (btnJarvis) btnJarvis.classList.add('active');
    if (modeSlider) modeSlider.classList.remove('center', 'right');
    if (activityToggle) activityToggle.style.display = '';
}

function newChat() {
    if (ttsPlayer) ttsPlayer.stop();
    if (camStream) stopCamera();
    sessionId = null;
    if (chatMessages) chatMessages.innerHTML = '';
    chatMessages.appendChild(createWelcome());
    messageInput.value = '';
    autoResizeInput();
    setGreeting();
    if (searchResultsWidget) searchResultsWidget.classList.remove('open');
    if (searchResultsToggle) searchResultsToggle.style.display = 'none';
    if (activityPanel) activityPanel.classList.remove('open');
    if (settingsPanel) settingsPanel.classList.remove('open');
    if (activityToggle) activityToggle.style.display = 'none';
    if (activityList) {
        activityList.innerHTML = '<div class="activity-empty" id="activity-empty">Send a message to see the flow here.</div>';
    }
    updatePanelOverlay();
}

function createWelcome() {
    const h = new Date().getHours();
    let g = 'Good evening.';
    if (h < 12) g = 'Good morning.';
    else if (h < 17) g = 'Good afternoon.';
    else if (h >= 22) g = 'Burning the midnight oil?';
    const div = document.createElement('div');
    div.className = 'welcome-screen';
    div.id = 'welcome-screen';
    div.innerHTML = `
        <div class="welcome-icon">
            <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5"/><path d="M2 12l10 5 10-5"/></svg>
        </div>
        <h2 class="welcome-title">${g}</h2>
        <p class="welcome-sub">How may I assist you today?</p>
        <div class="welcome-chips">
            <button class="chip" data-msg="What can you do?">What can you do?</button>
            <button class="chip" data-msg="Open YouTube for me">Open YouTube</button>
            <button class="chip" data-msg="Tell me a fun fact">Fun fact</button>
            <button class="chip" data-msg="Play some music">Play music</button>
        </div>`;
    div.querySelectorAll('.chip').forEach(c => {
        c.addEventListener('click', () => { if (!isStreaming) sendMessage(c.dataset.msg); });
    });
    return div;
}

function isUrlLike(str) {
    if (!str || typeof str !== 'string') return false;
    const s = str.trim();
    return s.length > 40 && (/^https?:\/\//i.test(s));
}

function friendlyUrlLabel(url) {
    if (!url || typeof url !== 'string') return 'View source';
    try {
        const u = new URL(url.startsWith('http') ? url : 'https://' + url);
        const host = u.hostname.replace(/^www\./, '');
        const path = u.pathname !== '/' ? u.pathname.slice(0, 20) + (u.pathname.length > 20 ? '…' : '') : '';
        return path ? host + path : host;
    } catch (_) {
        return url.length > 40 ? url.slice(0, 37) + '…' : url;
    }
}

function truncateSnippet(text, maxLen) {
    if (!text || typeof text !== 'string') return '';
    const t = text.trim();
    if (t.length <= maxLen) return t;
    return t.slice(0, maxLen).trim() + '…';
}

function renderSearchResults(payload) {
    if (!payload) return;
    if (searchResultsQuery) searchResultsQuery.textContent = (payload.query || '').trim() || 'Search';
    if (searchResultsAnswer) searchResultsAnswer.textContent = (payload.answer || '').trim() || '';
    if (!searchResultsList) return;
    searchResultsList.innerHTML = '';
    const results = payload.results || [];
    const maxContentLen = 220;
    for (const r of results) {
        let title = (r.title || '').trim();
        let content = (r.content || '').trim();
        const url = (r.url || '').trim();
        if (isUrlLike(title)) title = friendlyUrlLabel(url) || 'Source';
        if (!title) title = friendlyUrlLabel(url) || 'Source';
        if (isUrlLike(content)) content = '';
        content = truncateSnippet(content, maxContentLen);
        const score = r.score != null ? Math.round((r.score || 0) * 100) : null;
        const card = document.createElement('div');
        card.className = 'search-result-card';
        const urlDisplay = url ? escapeHtml(friendlyUrlLabel(url)) : '';
        const hrefSafe = safeUrlForHref(url);
        const urlMarkup = urlDisplay
            ? (hrefSafe ? `<a href="${hrefSafe}" target="_blank" rel="noopener" class="card-url" title="${escapeAttr(url)}">${urlDisplay}</a>` : `<span class="card-url">${urlDisplay}</span>`)
            : '';
        card.innerHTML = `
            <div class="card-title">${escapeHtml(title)}</div>
            ${content ? `<div class="card-content">${escapeHtml(content)}</div>` : ''}
            ${urlMarkup}
            ${score != null ? `<div class="card-score">Relevance: ${escapeHtml(String(score))}%</div>` : ''}`;
        searchResultsList.appendChild(card);
    }
}

function safeUrlForHref(url) {
    if (!url || typeof url !== 'string') return '';
    const u = url.trim();
    if (u.startsWith('https://') || u.startsWith('http://')) return escapeAttr(u);
    return '';
}

function escapeAttr(str) {
    if (typeof str !== 'string') return '';
    return String(str)
        .replace(/&/g, '&amp;')
        .replace(/"/g, '&quot;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;');
}

const ACTIVITY_STEPS = {
    query_detected:      { step: 1, label: 'Query detected' },
    decision:            { step: 2, label: 'Primary Brain' },
    intent_classified:   { step: 3, label: 'Task Brain' },
    routing:             { step: 4, label: 'Route selected' },
    tasks_executing:     { step: 0, label: 'Executing tasks' },
    tasks_completed:     { step: 0, label: 'Tasks completed' },
    actions_emitted:     { step: 0, label: 'Actions sent' },
    vision_analyzing:    { step: 0, label: 'Analyzing image' },
    streaming_started:   { step: 5, label: 'Streaming response' },
    extracting_query:    { step: 0, label: 'Extracting query' },
    searching_web:       { step: 0, label: 'Searching web' },
    search_completed:    { step: 0, label: 'Search completed' },
    context_retrieved:   { step: 0, label: 'Context retrieved' },
    background_dispatched: { step: 0, label: 'Background tasks' },
    first_chunk:         { step: 6, label: 'Core responded' },
};

function appendActivity(activity) {
    if (!activityList || !activity) return;
    const item = document.createElement('div');
    item.className = 'activity-item';
    item.setAttribute('data-event', activity.event || '');
    const stepInfo = ACTIVITY_STEPS[activity.event] || { step: 0, label: activity.event || 'Activity', icon: 'dot' };
    let detail = '';
    const addRouteClass = (route) => {
        if (route === 'general') item.classList.add('route-general');
        else if (route === 'realtime') item.classList.add('route-realtime');
        else if (route === 'vision' || route === 'camera') item.classList.add('route-vision');
        else if (route === 'task') item.classList.add('route-task');
        else if (route === 'mixed') item.classList.add('route-task');
        else if (route === 'chat') item.classList.add('route-chat');
    };
    if (activity.event === 'query_detected') {
        detail = activity.message || '';
    } else if (activity.event === 'decision') {
        const ms = activity.elapsed_ms;
        const timing = ms != null ? ` (${ms < 1000 ? ms + ' ms' : (ms / 1000).toFixed(2) + ' s'})` : '';
        const cat = (activity.query_type || '?').charAt(0).toUpperCase() + (activity.query_type || '').slice(1);
        detail = `${cat} — ${activity.reasoning || ''}${timing}`;
        addRouteClass(activity.query_type);
    } else if (activity.event === 'intent_classified') {
        detail = (activity.intent || '?').charAt(0).toUpperCase() + (activity.intent || '').slice(1);
        item.classList.add('activity-sub', 'route-task');
    } else if (activity.event === 'routing') {
        detail = `→ ${(activity.route || '?').charAt(0).toUpperCase() + (activity.route || '').slice(1)}`;
        addRouteClass(activity.route);
    } else if (activity.event === 'tasks_executing') {
        detail = activity.message || 'Running tasks...';
        item.classList.add('activity-sub', 'route-task');
    } else if (activity.event === 'tasks_completed') {
        detail = activity.message || 'Completed';
        item.classList.add('activity-sub', 'route-task');
    } else if (activity.event === 'actions_emitted') {
        detail = activity.message || 'Actions sent';
        item.classList.add('activity-sub');
    } else if (activity.event === 'vision_analyzing') {
        detail = activity.message || 'Analyzing image...';
        item.classList.add('activity-sub', 'route-vision');
    } else if (activity.event === 'streaming_started') {
        detail = `Generating via ${(activity.route || '?').charAt(0).toUpperCase() + (activity.route || '').slice(1)}`;
        addRouteClass(activity.route);
    } else if (activity.event === 'first_chunk') {
        const ms = activity.elapsed_ms;
        detail = ms != null ? `Core responded in ${ms < 1000 ? ms + ' ms' : (ms / 1000).toFixed(2) + ' s'}` : 'Response started';
        addRouteClass(activity.route);
    } else if (activity.event === 'extracting_query') {
        detail = activity.message || 'Parsing your question for search...';
        item.classList.add('activity-sub');
    } else if (activity.event === 'searching_web') {
        detail = activity.message || (activity.query ? `Query: "${activity.query}"` : 'Scanning Pulse...');
        item.classList.add('activity-sub', 'route-realtime');
    } else if (activity.event === 'search_completed') {
        detail = activity.message || 'Search completed';
        item.classList.add('activity-sub', 'route-realtime');
    } else if (activity.event === 'context_retrieved') {
        detail = activity.message || 'Knowledge base ready';
        item.classList.add('activity-sub', 'route-general');
    } else {
        detail = activity.message || (typeof activity === 'object' ? JSON.stringify(activity) : String(activity));
    }
    const stepNum = stepInfo.step ? `<span class="activity-step">${stepInfo.step}</span>` : '';
    item.innerHTML = `
        <div class="activity-event">${stepNum}${escapeHtml(stepInfo.label)}</div>
        <div class="activity-detail">${escapeHtml(detail || '')}</div>`;
    const emptyEl = activityList.querySelector('.activity-empty');
    if (emptyEl) emptyEl.style.display = 'none';
    activityList.appendChild(item);
    activityList.scrollTop = activityList.scrollHeight;
}

function escapeHtml(str) {
    if (typeof str !== 'string') return '';
    const div = document.createElement('div');
    div.textContent = str;
    return div.innerHTML;
}

function hideWelcome() {
    const w = document.getElementById('welcome-screen');
    if (w) w.remove();
}

const AVATAR_ICON_USER = '<svg class="msg-avatar-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>';
const AVATAR_ICON_ASSISTANT = '<svg class="msg-avatar-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="11" width="18" height="10" rx="2"/><circle cx="12" cy="5" r="2"/><path d="M12 7v4"/><circle cx="9" cy="16" r="1" fill="currentColor"/><circle cx="15" cy="16" r="1" fill="currentColor"/></svg>';

function addMessage(role, text) {
    hideWelcome();
    const msg = document.createElement('div');
    msg.className = `message ${role}`;
    const avatar = document.createElement('div');
    avatar.className = 'msg-avatar';
    avatar.innerHTML = role === 'assistant' ? AVATAR_ICON_ASSISTANT : AVATAR_ICON_USER;
    const body = document.createElement('div');
    body.className = 'msg-body';
    const label = document.createElement('div');
    label.className = 'msg-label';
    label.textContent = role === 'assistant'
        ? `Jarvis  (${currentMode === 'jarvis' ? 'Jarvis' : currentMode === 'realtime' ? 'Realtime' : 'General'})`
        : 'You';
    const content = document.createElement('div');
    content.className = 'msg-content';
    content.textContent = text;
    body.appendChild(label);
    body.appendChild(content);
    msg.appendChild(avatar);
    msg.appendChild(body);
    chatMessages.appendChild(msg);
    scrollToBottom();
    return content;
}

function addTypingIndicator() {
    hideWelcome();
    const msg = document.createElement('div');
    msg.className = 'message assistant';
    msg.id = 'typing-msg';
    const avatar = document.createElement('div');
    avatar.className = 'msg-avatar';
    avatar.innerHTML = AVATAR_ICON_ASSISTANT;
    const body = document.createElement('div');
    body.className = 'msg-body';
    const label = document.createElement('div');
    label.className = 'msg-label';
    label.textContent = `Jarvis  (${currentMode === 'jarvis' ? 'Jarvis' : currentMode === 'realtime' ? 'Realtime' : 'General'})`;
    const content = document.createElement('div');
    content.className = 'msg-content';
    content.innerHTML = '<span class="msg-stream-text">...</span>';
    body.appendChild(label);
    body.appendChild(content);
    msg.appendChild(avatar);
    msg.appendChild(body);
    chatMessages.appendChild(msg);
    scrollToBottom();
    return content;
}

function removeTypingIndicator() {
    const t = document.getElementById('typing-msg');
    if (t) t.remove();
}

function scrollToBottom() {
    requestAnimationFrame(() => {
        chatMessages.scrollTop = chatMessages.scrollHeight;
    });
}

async function sendMessage(textOverride) {
    let text = (textOverride || messageInput.value).trim();
    const visionModeOn = camVisionModeInput && camVisionModeInput.checked;
    const wantsCamera = visionModeOn || isCameraQuery(text) || (camStream && text);
    if (wantsCamera && !text) text = 'What do you see?';
    if (!text || isStreaming) return;
    if (isListening) {
        pendingSendTranscript = null;
        clearTimeout(speechSendTimeout);
        speechSendTimeout = null;
        stopListening();
    }
    if ((isCameraQuery(text) || visionModeOn) && !camStream) {
        try {
            await startCamera();
            await new Promise((resolve) => {
                if (!camVideo) { resolve(); return; }
                if (camVideo.readyState >= 2 && camVideo.videoWidth > 0) { resolve(); return; }
                const onReady = () => { camVideo.removeEventListener('loadeddata', onReady); clearTimeout(t); resolve(); };
                const t = setTimeout(() => { camVideo.removeEventListener('loadeddata', onReady); resolve(); }, 3000);
                camVideo.addEventListener('loadeddata', onReady);
            });
        } catch (_) {
        }
    }
    let imgBase64 = null;
    if (camStream && wantsCamera) {
        imgBase64 = await captureFrameAsBase64Safe();
        if (!imgBase64) showToast('Camera frame not ready. Please try again.');
    }
    messageInput.value = '';
    autoResizeInput();
    charCount.textContent = '';
    addMessage('user', text);
    addTypingIndicator();
    isStreaming = true;
    if (sendBtn) sendBtn.disabled = true;
    if (messageInput) messageInput.disabled = true;
    if (orbContainer) orbContainer.classList.add('active');
    if (ttsPlayer) { ttsPlayer.reset(); ttsPlayer.unlock(); }
    const messageToSend = imgBase64 ? (text + ' ' + CAM_BYPASS_TOKEN) : text;
    const endpoint = '/chat/jarvis/stream';
    if (activityList) {
        activityList.innerHTML = '<div class="activity-empty" id="activity-empty">Processing...</div>';
        if (activityToggle) activityToggle.style.display = '';
        if (activityPanel && settings.autoOpenActivity) { activityPanel.classList.add('open'); updatePanelOverlay(); }
    }
    let firstChunkReceived = false;
    let timeoutId = null;
    const controller = new AbortController();
    try {
        if (ttsPlayer?.enabled && settings.thinkingSounds && preStarterPlayer) {
            preStarterPlayer.play(() => {});
        }
        timeoutId = setTimeout(() => controller.abort(), 300000);
        const res = await fetch(`${API}${endpoint}`, {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify({
                message: messageToSend,
                session_id: sessionId,
                tts: !!(ttsPlayer && ttsPlayer.enabled),
                imgbase64: imgBase64 || null
            }),
            signal: controller.signal,
        });
        if (!res.ok) {
            let errMsg = `HTTP ${res.status}`;
            try {
                const err = await res.json();
                errMsg = err.detail || (Array.isArray(err.detail) ? err.detail.map(d => d.msg || d.loc?.join('.')).join('; ') : err.message) || errMsg;
            } catch (_) {}
            throw new Error(errMsg);
        }
        removeTypingIndicator();
        const contentEl = addMessage('assistant', '');
        contentEl.innerHTML = '<span class="msg-stream-text">...</span>';
        scrollToBottom();
        if (!res.body) throw new Error('No response body');
        const reader = res.body.getReader();
        const decoder = new TextDecoder();
        let sseBuffer = '';
        let fullResponse = '';
        let cursorEl = null;
        let streamDone = false;
        while (!streamDone) {
            const { done, value } = await reader.read();
            if (done) break;
            sseBuffer += decoder.decode(value, { stream: true });
            const lines = sseBuffer.split('\n\n');
            sseBuffer = lines.pop();
            for (const line of lines) {
                if (!line.startsWith('data: ')) continue;
                try {
                    const data = JSON.parse(line.slice(6));
                    if (data.session_id) sessionId = data.session_id;
                    if (data.activity) {
                        appendActivity(data.activity);
                        if (activityToggle) activityToggle.style.display = '';
                        if (activityPanel && settings.autoOpenActivity) { activityPanel.classList.add('open'); updatePanelOverlay(); }
                    }
                    if (data.search_results) {
                        renderSearchResults(data.search_results);
                        if (searchResultsToggle) searchResultsToggle.style.display = '';
                        if (searchResultsWidget && settings.autoOpenSearchResults) { searchResultsWidget.classList.add('open'); updatePanelOverlay(); }
                    }
                    if (data.actions) {
                        handleActions(data.actions, contentEl);
                    }
                    if (data.background_tasks) {
                        handleBackgroundTasks(data.background_tasks, contentEl);
                    }
                    if ('chunk' in data) {
                        const chunkText = data.chunk || '';
                        if (chunkText && !firstChunkReceived) {
                            firstChunkReceived = true;
                            if (ttsPlayer) ttsPlayer.reset();
                        }
                        fullResponse += chunkText;
                        const textSpan = contentEl.querySelector('.msg-stream-text');
                        if (textSpan) {
                            textSpan.textContent = fullResponse;
                            textSpan.classList.remove('stream-placeholder');
                        }
                        if (!cursorEl) {
                            cursorEl = document.createElement('span');
                            cursorEl.className = 'stream-cursor';
                            cursorEl.textContent = '|';
                            contentEl.appendChild(cursorEl);
                        }
                        scrollToBottom();
                    }
                    if (data.audio && ttsPlayer) {
                        ttsPlayer.enqueue(data.audio);
                    }
                    if (data.error) throw new Error(data.error);
                    if (data.done) { streamDone = true; break; }
                } catch (parseErr) {
                    if (parseErr.message && !parseErr.message.includes('JSON'))
                        throw parseErr;
                }
            }
            if (streamDone) break;
        }
        if (cursorEl) cursorEl.remove();
        const textSpan = contentEl.querySelector('.msg-stream-text');
        if (textSpan && !fullResponse) textSpan.textContent = '(No response)';
    } catch (err) {
        clearTimeout(timeoutId);
        removeTypingIndicator();
        let msg = 'Something went wrong. Please try again.';
        if (err.name === 'AbortError') {
            msg = 'Request timed out. Please try again.';
        } else if (err.message && err.message.includes('503')) {
            msg = 'Service temporarily unavailable. Please try again in a moment.';
        } else if (err.message && err.message.includes('429')) {
            msg = 'Rate limit reached. Please wait a moment before trying again.';
        } else if (err.message && err.message.length > 0) {
            msg = err.message.length > 100 ? err.message.slice(0, 97) + '...' : err.message;
        }
        addMessage('assistant', msg);
        showToast(msg, 6000);
    } finally {
        clearTimeout(timeoutId);
        isStreaming = false;
        if (sendBtn) sendBtn.disabled = false;
        if (messageInput) messageInput.disabled = false;
        if (orbContainer) orbContainer.classList.remove('active');
        maybeRestartListening();
    }
}

document.addEventListener('DOMContentLoaded', init);
</file>

<file path="JARVIS/frontend/style.css">
:root {
    --bg: #050510;
    --glass-bg: rgba(10, 10, 28, 0.72);
    --glass-border: rgba(255, 255, 255, 0.06);
    --glass-hover: rgba(255, 255, 255, 0.10);
    --accent: #7c6aef;
    --accent-glow: rgba(124, 106, 239, 0.35);
    --accent-secondary: #4ecdc4;
    --text: rgba(255, 255, 255, 0.93);
    --text-dim: rgba(255, 255, 255, 0.50);
    --text-muted: rgba(255, 255, 255, 0.28);
    --danger: #ff6b6b;
    --success: #51cf66;
    --radius: 16px;
    --radius-sm: 10px;
    --radius-xs: 6px;
    --header-h: 64px;
    --input-bar-h: calc(88px + env(safe-area-inset-bottom, 0px));
    --content-gap: 16px;
    --panel-gap: 14px;
    --transition: 0.25s cubic-bezier(0.4, 0, 0.2, 1);
    --font: 'Poppins', -apple-system, BlinkMacSystemFont, sans-serif;
}

*, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
html, body { height: 100%; overflow: hidden; overflow-x: hidden; }

body {
    font-family: var(--font);
    background: var(--bg);
    color: var(--text);
    -webkit-font-smoothing: antialiased;
    -webkit-tap-highlight-color: transparent;
}

button { font-family: var(--font); cursor: pointer; border: none; background: none; color: inherit; }
textarea { font-family: var(--font); color: var(--text); }

.glass-panel {
    background: var(--glass-bg);
    backdrop-filter: blur(32px) saturate(1.2);
    -webkit-backdrop-filter: blur(32px) saturate(1.2);
    border: 1px solid var(--glass-border);
    box-shadow: 0 4px 24px rgba(0, 0, 0, 0.12);
}

.app {
    position: relative;
    display: flex;
    flex-direction: column;
    height: 100vh;
    height: 100dvh;
    overflow: hidden;
}

#orb-container {
    position: fixed;
    top: 50%;
    left: 50%;
    translate: -50% -50%;
    width: min(600px, 80vw);
    height: min(600px, 80vw);
    z-index: 0;
    pointer-events: none;
    opacity: 0.35;
    transition: opacity 0.5s ease, transform 0.5s ease;
}

#orb-container.active,
#orb-container.speaking {
    opacity: 1;
    animation: orbPulse 1.6s ease-in-out infinite;
}

.header {
    position: relative;
    z-index: 10;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
    height: var(--header-h);
    padding: 0 24px;
    margin-bottom: var(--content-gap);
    border-radius: 0 0 var(--radius) var(--radius);
    border-top: none;
    flex-shrink: 0;
}

.logo {
    font-size: 1.1rem;
    font-weight: 700;
    letter-spacing: 3px;
    background: linear-gradient(135deg, var(--accent), var(--accent-secondary));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.tagline {
    font-size: 0.68rem;
    font-weight: 300;
    color: var(--text-muted);
    letter-spacing: 0.5px;
}

.mode-switch {
    position: relative;
    display: flex;
    background: rgba(255, 255, 255, 0.04);
    border-radius: 12px;
    padding: 3px;
    gap: 2px;
}

.mode-slider {
    position: absolute;
    top: 3px;
    left: 3px;
    width: calc(50% - 4px);
    height: calc(100% - 6px);
    background: var(--accent);
    border-radius: 10px;
    transition: transform var(--transition);
    opacity: 0.18;
}

.mode-slider.right {
    transform: translateX(calc(100% + 2px));
}

.mode-switch-single {
    min-width: 0;
}

.mode-switch-single .mode-btn {
    flex: 1;
    min-width: 0;
    justify-content: center;
    padding: 7px 16px;
}

.mode-switch-single .mode-slider {
    width: calc(100% - 6px);
}

.mode-switch-three {
    min-width: 0;
}

.mode-switch-three .mode-btn {
    flex: 1;
    min-width: 0;
    justify-content: center;
    padding: 7px 10px;
}

.mode-switch-three .mode-slider {
    width: calc(33.333% - 4px);
}

.mode-switch-three .mode-slider.center {
    transform: translateX(calc(100% + 2px));
}

.mode-switch-three .mode-slider.right {
    transform: translateX(calc(200% + 4px));
}

.mode-btn {
    position: relative;
    z-index: 1;
    display: flex;
    align-items: center;
    gap: 6px;
    padding: 7px 16px;
    font-size: 0.76rem;
    font-weight: 500;
    border-radius: 10px;
    color: var(--text-dim);
    transition: color var(--transition);
    white-space: nowrap;
}

.mode-btn.active { color: var(--text); }
.mode-btn svg {
    opacity: 0.7;
    width: 16px;
    height: 16px;
    min-width: 16px;
    min-height: 16px;
    flex-shrink: 0;
}

.mode-btn.active svg { opacity: 1; }
.header-left { display: flex; align-items: baseline; gap: 10px; flex-shrink: 0; min-width: 0; }
.header-center { flex: 1; min-width: 0; display: flex; justify-content: center; align-items: center; }
.header-right {
    display: flex;
    align-items: center;
    gap: 10px;
    flex-shrink: 0;
    flex-wrap: nowrap;
}

.status-badge {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: 0.7rem;
    font-weight: 400;
    color: var(--text-dim);
}

.status-dot {
    width: 7px;
    height: 7px;
    border-radius: 50%;
    background: var(--success);
    box-shadow: 0 0 6px var(--success);
    animation: pulse-dot 2s ease-in-out infinite;
}

.status-dot.offline {
    background: var(--danger);
    box-shadow: 0 0 6px var(--danger);
    animation: none;
}

.btn-icon {
    display: grid;
    place-items: center;
    width: 34px;
    height: 34px;
    min-width: 34px;
    min-height: 34px;
    border-radius: var(--radius-sm);
    background: rgba(255, 255, 255, 0.04);
    border: 1px solid var(--glass-border);
    transition: background var(--transition), border-color var(--transition);
    touch-action: manipulation;
    -webkit-tap-highlight-color: transparent;
}

.btn-icon:hover {
    background: var(--glass-hover);
    border-color: rgba(255, 255, 255, 0.14);
}

.chat-area {
    position: relative;
    z-index: 5;
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    min-height: 0;
}

.chat-messages {
    flex: 1;
    overflow-y: auto;
    overflow-x: hidden;
    padding: 24px 24px 28px;
    display: flex;
    flex-direction: column;
    gap: 14px;
    scroll-behavior: smooth;
    -webkit-overflow-scrolling: touch;
}

.welcome-screen {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    flex: 1;
    gap: 16px;
    padding: 48px 24px;
    animation: fadeIn 0.6s ease;
}

.welcome-icon {
    color: var(--accent);
    opacity: 0.5;
    margin-bottom: 6px;
}

.welcome-title {
    font-size: 1.7rem;
    font-weight: 600;
    background: linear-gradient(135deg, var(--text), var(--accent));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
}

.welcome-sub {
    font-size: 0.9rem;
    color: var(--text-dim);
    font-weight: 300;
}

.welcome-chips {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
    margin-top: 24px;
}

.chip {
    padding: 10px 20px;
    font-size: 0.76rem;
    font-weight: 400;
    border-radius: 20px;
    background: rgba(255, 255, 255, 0.04);
    border: 1px solid var(--glass-border);
    color: var(--text-dim);
    transition: all var(--transition);
}

.chip:hover {
    background: var(--accent);
    color: #fff;
    border-color: var(--accent);
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(124, 106, 239, 0.25);
}

.message {
    display: flex;
    gap: 12px;
    max-width: 720px;
    width: 100%;
    margin: 0 auto;
    animation: msgIn 0.35s cubic-bezier(0.4, 0, 0.2, 1);
}

.message.user { flex-direction: row-reverse; }
.msg-avatar {
    width: 30px;
    height: 30px;
    border-radius: 10px;
    display: grid;
    place-items: center;
    font-size: 0.7rem;
    font-weight: 600;
    flex-shrink: 0;
    margin-top: 4px;
}

.msg-avatar .msg-avatar-icon {
    width: 18px;
    height: 18px;
}

.message.assistant .msg-avatar {
    background: linear-gradient(135deg, var(--accent), var(--accent-secondary));
    color: #fff;
}

.message.user .msg-avatar {
    background: rgba(255, 255, 255, 0.08);
    color: var(--text-dim);
}

.msg-body {
    display: flex;
    flex-direction: column;
    gap: 3px;
    min-width: 0;
}

.msg-content {
    padding: 14px 18px;
    border-radius: var(--radius);
    font-size: 0.87rem;
    line-height: 1.65;
    font-weight: 400;
    word-wrap: break-word;
    white-space: pre-wrap;
}

.message.assistant .msg-content {
    background: rgba(255, 255, 255, 0.05);
    border: 1px solid rgba(255, 255, 255, 0.07);
    border-top-left-radius: var(--radius-xs);
}

.message.user .msg-content {
    background: rgba(124, 106, 239, 0.13);
    border: 1px solid rgba(124, 106, 239, 0.16);
    border-top-right-radius: var(--radius-xs);
}

.msg-label {
    font-size: 0.66rem;
    font-weight: 500;
    color: var(--text-muted);
    padding: 0 4px;
}
.message.user .msg-label { text-align: right; }

.stream-cursor {
    animation: blink 0.8s step-end infinite;
    color: var(--accent);
    margin-left: 1px;
}

.msg-actions-images {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 12px;
}

.msg-action-image {
    max-width: 100%;
    max-height: 320px;
    border-radius: var(--radius);
    object-fit: contain;
}

.msg-actions-contents {
    margin-top: 12px;
}

.msg-action-content {
    padding: 10px 12px;
    background: rgba(0, 0, 0, 0.2);
    border-radius: var(--radius);
    font-size: 0.85rem;
    line-height: 1.6;
    white-space: pre-wrap;
    margin-bottom: 8px;
}
.msg-action-content:last-child { margin-bottom: 0; }

.bg-task-card {
    margin-top: 12px;
    padding: 14px 18px;
    background: rgba(124, 106, 239, 0.06);
    border: 1px solid rgba(124, 106, 239, 0.12);
    border-radius: var(--radius);
    transition: all 0.3s ease;
}

.bg-task-card.bg-task-done {
    background: rgba(78, 205, 196, 0.06);
    border-color: rgba(78, 205, 196, 0.15);
}

.bg-task-card.bg-task-failed {
    background: rgba(255, 107, 107, 0.06);
    border-color: rgba(255, 107, 107, 0.12);
}

.bg-task-header {
    display: flex;
    align-items: center;
    gap: 10px;
}

.bg-task-spinner {
    width: 16px;
    height: 16px;
    border: 2px solid rgba(124, 106, 239, 0.15);
    border-top: 2px solid var(--accent);
    border-radius: 50%;
    animation: spin 0.8s linear infinite;
    flex-shrink: 0;
}

@keyframes spin { to { transform: rotate(360deg); } }
.bg-task-done-icon {
    width: 16px; height: 16px; flex-shrink: 0;
    background: var(--success);
    border-radius: 50%;
    position: relative;
}

.bg-task-done-icon::after {
    content: '';
    position: absolute;
    top: 3px; left: 5px;
    width: 5px; height: 8px;
    border: solid #fff;
    border-width: 0 2px 2px 0;
    transform: rotate(45deg);
}

.bg-task-fail-icon {
    width: 16px; height: 16px; flex-shrink: 0;
    background: var(--danger);
    border-radius: 50%;
    position: relative;
}

.bg-task-fail-icon::after {
    content: '!';
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    color: #fff;
    font-size: 10px;
    font-weight: 700;
}

.bg-task-label {
    font-size: 0.82rem;
    font-weight: 600;
    color: var(--text);
}

.bg-task-status {
    font-size: 0.75rem;
    color: var(--text-dim);
    margin-left: auto;
}

.bg-task-prompt {
    font-size: 0.78rem;
    color: var(--text-dim);
    margin-top: 6px;
    opacity: 0.7;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

.bg-task-view-btn {
    margin-top: 10px;
    padding: 8px 20px;
    background: var(--accent);
    color: #fff;
    border: none;
    border-radius: 10px;
    font-family: var(--font);
    font-size: 0.8rem;
    font-weight: 600;
    cursor: pointer;
    transition: background 0.2s ease;
}

.bg-task-view-btn:hover { background: #6b5ce7; }
.cam-btn.cam-active {
    color: var(--accent);
    background: rgba(124, 106, 239, 0.18);
    border-color: rgba(124, 106, 239, 0.3);
}

.cam-panel {
    --cam-w: 420px;
    --cam-h: 315px;
    position: fixed;
    bottom: calc(var(--input-bar-h) + var(--panel-gap) + 16px);
    right: 24px;
    width: var(--cam-w);
    height: var(--cam-h);
    min-width: 200px;
    min-height: 150px;
    max-width: 90vw;
    max-height: 70vh;
    z-index: 100;
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 12px 48px rgba(0, 0, 0, 0.5), 0 0 0 1px rgba(124, 106, 239, 0.25);
    background: rgba(10, 10, 28, 0.88);
    backdrop-filter: blur(28px);
    -webkit-backdrop-filter: blur(28px);
    border: 1px solid rgba(255, 255, 255, 0.12);
    opacity: 0;
    visibility: hidden;
    transform: scale(0.9) translateY(12px);
    transition: opacity 0.3s ease, visibility 0.3s ease, transform 0.3s ease, width 0.25s ease, height 0.25s ease;
}

.cam-panel.visible {
    opacity: 1;
    visibility: visible;
    transform: scale(1) translateY(0);
}

.cam-panel.minimized {
    width: 72px !important;
    height: 72px !important;
    min-width: 72px;
    min-height: 72px;
    border-radius: 50%;
}

.cam-panel.minimized .cam-panel-header,
.cam-panel.minimized .cam-panel-overlay,
.cam-panel.minimized .cam-panel-resize { display: none; }

.cam-panel.minimized .cam-panel-body {
    border-radius: 50%;
    cursor: pointer;
}

.cam-panel.minimized .cam-panel-body video { border-radius: 50%; }

.cam-panel {
    display: flex;
    flex-direction: column;
}

.cam-panel-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 16px;
    background: rgba(0, 0, 0, 0.35);
    border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    cursor: move;
    user-select: none;
    flex-shrink: 0;
    border-radius: 20px 20px 0 0;
}

.cam-panel-title {
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: 0.8rem;
    font-weight: 600;
    color: var(--text);
}

.cam-panel-dot {
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: var(--success);
    box-shadow: 0 0 8px var(--success);
    animation: pulse-dot 1.5s ease-in-out infinite;
}

.cam-panel-controls {
    display: flex;
    align-items: center;
    gap: 4px;
}

.cam-panel-vision-mode {
    display: flex;
    align-items: center;
    cursor: pointer;
    margin-right: 8px;
}

.cam-panel-vision-mode input { display: none; }
.cam-panel-vision-label {
    font-size: 0.68rem;
    font-weight: 500;
    color: var(--text-dim);
    padding: 4px 10px;
    border-radius: 8px;
    background: rgba(255, 255, 255, 0.06);
    transition: all var(--transition);
}

.cam-panel-vision-mode input:checked + .cam-panel-vision-label {
    color: var(--accent);
    background: rgba(124, 106, 239, 0.2);
}

.cam-panel-btn {
    width: 30px;
    height: 30px;
    display: grid;
    place-items: center;
    border: none;
    background: rgba(255, 255, 255, 0.08);
    color: var(--text-dim);
    border-radius: 10px;
    font-size: 1rem;
    line-height: 1;
    cursor: pointer;
    transition: all var(--transition);
}

.cam-panel-btn:hover {
    background: rgba(255, 255, 255, 0.12);
    color: var(--text);
}

.cam-panel-btn.cam-close:hover { background: rgba(255, 107, 107, 0.25); color: var(--danger); }

.cam-panel-body {
    position: relative;
    flex: 1;
    min-height: 0;
    overflow: hidden;
}

.cam-panel #cam-video {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
}

.cam-panel-overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    padding: 8px 12px;
    background: linear-gradient(transparent, rgba(0, 0, 0, 0.6));
    font-size: 0.7rem;
    color: rgba(255, 255, 255, 0.85);
}

.cam-panel-resize {
    position: absolute;
    bottom: 0;
    right: 0;
    width: 24px;
    height: 24px;
    cursor: nwse-resize;
    background: linear-gradient(135deg, transparent 45%, rgba(255,255,255,0.2) 45%, rgba(255,255,255,0.2) 55%, transparent 55%);
    border-bottom-right-radius: inherit;
}

.cam-panel-resize:hover { background: linear-gradient(135deg, transparent 45%, rgba(124,106,239,0.4) 45%, rgba(124,106,239,0.4) 55%, transparent 55%); }
.cam-panel.minimized .cam-panel-resize { pointer-events: none; }

@media (max-width: 768px) {
    .cam-panel { --cam-w: 280px; --cam-h: 210px; right: 16px; bottom: calc(var(--input-bar-h) + var(--panel-gap) + 12px); }
}

@media (max-width: 480px) {
    .cam-panel { --cam-w: 240px; --cam-h: 180px; right: 12px; bottom: calc(var(--input-bar-h) + var(--panel-gap) + 8px); }
}

.input-bar {
    position: relative;
    z-index: 10;
    padding: 14px 24px 14px;
    padding-bottom: max(14px, env(safe-area-inset-bottom, 14px));
    margin-top: var(--content-gap);
    border-radius: var(--radius) var(--radius) 0 0;
    border-bottom: none;
    flex-shrink: 0;
    box-shadow: none;
}

.input-wrapper {
    display: flex;
    align-items: flex-end;
    gap: 8px;
    background: rgba(255, 255, 255, 0.04);
    border: 1px solid var(--glass-border);
    border-radius: 14px;
    padding: 8px 8px 8px 18px;
    transition: border-color var(--transition);
    box-shadow: none;
}

.input-wrapper:focus-within {
    border-color: rgba(255, 255, 255, 0.14);
}

.input-wrapper textarea {
    flex: 1;
    background: none;
    border: none;
    outline: none;
    resize: none;
    font-size: 0.87rem;
    line-height: 1.5;
    padding: 8px 0;
    max-height: 120px;
    color: var(--text);
}
.input-wrapper textarea::placeholder { color: var(--text-muted); }
.input-wrapper textarea:disabled {
    opacity: 0.6;
    cursor: not-allowed;
}

.input-actions {
    display: flex;
    gap: 6px;
    padding-bottom: 2px;
    flex-shrink: 0;
}

.action-btn {
    display: grid;
    place-items: center;
    width: 38px;
    height: 38px;
    min-width: 38px;
    border-radius: 10px;
    background: rgba(255, 255, 255, 0.06);
    border: 1px solid rgba(255, 255, 255, 0.08);
    transition: all var(--transition);
    color: var(--text-dim);
    flex-shrink: 0;
}

.action-btn:hover {
    background: rgba(255, 255, 255, 0.12);
    border-color: rgba(255, 255, 255, 0.16);
    color: var(--text);
    transform: translateY(-1px);
}

.action-btn:active {
    transform: translateY(0);
}

.send-btn {
    background: var(--accent) !important;
    border-color: var(--accent) !important;
    color: #fff !important;
    box-shadow: 0 2px 8px rgba(124, 106, 239, 0.25);
}

.send-btn:hover {
    background: #6a58e0 !important;
    border-color: #6a58e0 !important;
    box-shadow: 0 4px 14px rgba(124, 106, 239, 0.35);
}

.send-btn:disabled {
    opacity: 0.5;
    cursor: default;
    box-shadow: none;
    transform: none;
    animation: sendBtnPulse 1.2s ease-in-out infinite;
}

@keyframes sendBtnPulse {
    0%, 100% { opacity: 0.5; }
    50%      { opacity: 0.7; }
}

.mic-btn .mic-icon-active { display: none; }
.mic-btn.listening .mic-icon { display: none; }
.mic-btn.listening .mic-icon-active { display: block; }

.mic-btn.listening {
    background: rgba(255, 107, 107, 0.18);
    border-color: rgba(255, 107, 107, 0.3);
    color: var(--danger);
    animation: micPulse 1.5s ease-in-out infinite;
}

.mic-btn.auto-listen:not(.listening) {
    border-color: rgba(78, 205, 196, 0.4);
    box-shadow: 0 0 0 1px rgba(78, 205, 196, 0.2);
}

.tts-btn .tts-icon-on { display: none; }
.tts-btn.tts-active .tts-icon-off { display: none; }
.tts-btn.tts-active .tts-icon-on { display: block; }

.tts-btn.tts-active {
    background: rgba(124, 106, 239, 0.18);
    border-color: rgba(124, 106, 239, 0.3);
    color: var(--accent);
}

.tts-btn.tts-speaking {
    animation: ttsPulse 1.5s ease-in-out infinite;
}

.input-meta {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 6px 12px 0;
    min-height: 0;
    font-size: 0.66rem;
    color: var(--text-muted);
}

.panel-overlay {
    position: fixed;
    inset: 0;
    z-index: 19;
    background: transparent;
    opacity: 0;
    visibility: hidden;
    transition: opacity 0.3s ease, visibility 0.3s ease;
    pointer-events: none;
}

.panel-overlay.visible {
    opacity: 1;
    visibility: visible;
    pointer-events: none;
}

.speech-widget {
    position: fixed;
    bottom: calc(var(--input-bar-h) + var(--panel-gap));
    left: 50%;
    transform: translateX(-50%) translateY(8px);
    z-index: 15;
    min-width: min(320px, 90vw);
    max-width: min(560px, 95vw);
    padding: 14px 20px;
    border-radius: 16px;
    background: rgba(10, 10, 28, 0.65);
    backdrop-filter: blur(24px) saturate(1.3);
    -webkit-backdrop-filter: blur(24px) saturate(1.3);
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.35), 0 0 0 1px rgba(124, 106, 239, 0.08);
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
    transition: opacity 0.3s ease, visibility 0.3s ease, transform 0.3s ease;
}

.speech-widget.visible {
    opacity: 1;
    visibility: visible;
    transform: translateX(-50%) translateY(0);
    animation: speechWidgetIn 0.35s cubic-bezier(0.4, 0, 0.2, 1);
}

@keyframes speechWidgetIn {
    from { opacity: 0; transform: translateX(-50%) translateY(12px); }
    to   { opacity: 1; transform: translateX(-50%) translateY(0); }
}

.speech-widget-inner {
    display: flex;
    flex-direction: column;
    gap: 6px;
}

.speech-widget-label {
    font-size: 0.7rem;
    font-weight: 600;
    color: var(--accent);
    text-transform: uppercase;
    letter-spacing: 1px;
    display: flex;
    align-items: center;
    gap: 8px;
}

.speech-widget-label::before {
    content: '';
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: var(--danger);
    animation: pulse-dot 1.2s ease-in-out infinite;
}

.speech-widget-text {
    font-size: 0.9rem;
    line-height: 1.5;
    color: var(--text);
    min-height: 1.5em;
    word-wrap: break-word;
    overflow-wrap: break-word;
}

.speech-widget-text:empty::before {
    content: 'Speak now...';
    color: var(--text-muted);
    font-style: italic;
}

.toast-container {
    position: fixed;
    bottom: 100px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 100;
    display: flex;
    flex-direction: column;
    gap: 8px;
    pointer-events: none;
}

.toast {
    padding: 12px 20px;
    background: rgba(20, 20, 35, 0.95);
    border: 1px solid rgba(255, 107, 107, 0.4);
    border-radius: var(--radius-sm);
    color: var(--text);
    font-size: 0.9rem;
    max-width: min(400px, 90vw);
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
    opacity: 0;
    transform: translateY(12px);
    transition: opacity 0.3s ease, transform 0.3s ease;
    pointer-events: auto;
    cursor: pointer;
}

.toast.toast-visible {
    opacity: 1;
    transform: translateY(0);
}

.activity-panel {
    position: fixed;
    top: calc(var(--header-h) + var(--panel-gap));
    left: 0;
    bottom: calc(var(--input-bar-h) + var(--panel-gap));
    width: min(340px, 90vw);
    min-width: 0;
    height: auto;
    z-index: 6;
    display: flex;
    flex-direction: column;
    border-radius: 0 var(--radius) var(--radius) 0;
    box-shadow: 8px 0 40px rgba(0, 0, 0, 0.35), 0 0 0 1px rgba(255, 255, 255, 0.04);
    overflow: hidden;
    transform: translateX(-100%);
    transition: transform 0.35s cubic-bezier(0.4, 0, 0.2, 1);
}

.activity-panel.open {
    transform: translateX(0);
}

.activity-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 18px 20px;
    border-bottom: 1px solid var(--glass-border);
    flex-shrink: 0;
}

.activity-title {
    font-size: 0.9rem;
    font-weight: 600;
    color: var(--text);
    display: flex;
    align-items: center;
    gap: 8px;
}

.activity-title::before {
    content: '';
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: var(--accent);
    box-shadow: 0 0 8px rgba(124, 106, 239, 0.5);
}

.activity-close {
    display: grid;
    place-items: center;
    width: 32px;
    height: 32px;
    border-radius: var(--radius-sm);
    background: rgba(255, 255, 255, 0.06);
    border: 1px solid var(--glass-border);
    color: var(--text-dim);
    cursor: pointer;
    transition: all var(--transition);
}

.activity-close:hover {
    background: rgba(255, 255, 255, 0.12);
    color: var(--text);
}

.activity-list {
    flex: 1;
    min-height: 0;
    overflow-y: auto;
    overflow-x: hidden;
    padding: 16px 20px 24px;
    display: flex;
    flex-direction: column;
    gap: 14px;
    scroll-behavior: smooth;
    scrollbar-width: none;
    -ms-overflow-style: none;
}

.activity-list::-webkit-scrollbar { display: none; }
.activity-empty {
    padding: 24px 16px;
    font-size: 0.8rem;
    color: var(--text-muted);
    text-align: center;
    line-height: 1.5;
}

.activity-item {
    padding: 14px 16px;
    border-radius: var(--radius-sm);
    background: rgba(255, 255, 255, 0.04);
    border: 1px solid rgba(255, 255, 255, 0.07);
    font-size: 0.78rem;
    line-height: 1.55;
    animation: activityIn 0.25s ease-out;
}

.activity-item .activity-event {
    font-weight: 600;
    color: var(--accent);
    margin-bottom: 6px;
    display: flex;
    align-items: center;
    gap: 8px;
}

.activity-step {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-width: 20px;
    height: 20px;
    padding: 0 5px;
    border-radius: 6px;
    background: rgba(124, 106, 239, 0.2);
    color: var(--accent);
    font-size: 0.7rem;
    font-weight: 700;
}

.activity-item .activity-detail {
    color: var(--text-dim);
    word-wrap: break-word;
    overflow-wrap: break-word;
    white-space: pre-wrap;
    max-height: 300px;
    overflow-y: auto;
}

.activity-item.route-general .activity-event,
.activity-item.route-general .activity-step { color: #7dd3fc; }
.activity-item.route-general .activity-step { background: rgba(125, 211, 252, 0.15); }
.activity-item.route-realtime .activity-event,
.activity-item.route-realtime .activity-step { color: var(--success); }
.activity-item.route-realtime .activity-step { background: rgba(81, 207, 102, 0.15); }
.activity-item.route-vision .activity-event,
.activity-item.route-vision .activity-step { color: #f59e0b; }
.activity-item.route-vision .activity-step { background: rgba(245, 158, 11, 0.15); }
.activity-item.route-task .activity-event,
.activity-item.route-task .activity-step { color: var(--accent-secondary); }
.activity-item.route-task .activity-step { background: rgba(78, 205, 196, 0.15); }
.activity-item.route-chat .activity-event,
.activity-item.route-chat .activity-step { color: var(--accent); }
.activity-item.route-chat .activity-step { background: rgba(124, 106, 239, 0.2); }

.activity-item.activity-sub {
    padding: 12px 14px;
    font-size: 0.75rem;
    border-left: 3px solid rgba(124, 106, 239, 0.4);
}

.activity-item.activity-sub .activity-event { font-size: 0.76rem; }

@keyframes activityIn {
    from { opacity: 0; transform: translateX(-8px); }
    to   { opacity: 1; transform: translateX(0); }
}

.search-results-widget {
    position: fixed;
    top: calc(var(--header-h) + var(--panel-gap));
    right: 0;
    bottom: calc(var(--input-bar-h) + var(--panel-gap));
    width: min(380px, 95vw);
    min-width: 0;
    height: auto;
    z-index: 6;
    display: flex;
    flex-direction: column;
    border-radius: var(--radius) 0 0 var(--radius);
    border-right: none;
    box-shadow: -8px 0 40px rgba(0, 0, 0, 0.35), 0 0 0 1px rgba(255, 255, 255, 0.04);
    overflow: hidden;
    transform: translateX(100%);
    transition: transform 0.35s cubic-bezier(0.4, 0, 0.2, 1);
}

.search-results-widget.open {
    transform: translateX(0);
}

.search-results-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 18px 20px;
    border-bottom: 1px solid var(--glass-border);
    flex-shrink: 0;
}

.search-results-title {
    font-size: 0.9rem;
    font-weight: 600;
    color: var(--text);
    display: flex;
    align-items: center;
    gap: 8px;
    min-width: 0;
}

.search-results-title::before {
    content: '';
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: var(--success);
    box-shadow: 0 0 8px var(--success);
    animation: pulse-dot 2s ease-in-out infinite;
    flex-shrink: 0;
}

.search-results-close {
    display: grid;
    place-items: center;
    width: 32px;
    height: 32px;
    border-radius: var(--radius-sm);
    background: rgba(255, 255, 255, 0.06);
    border: 1px solid var(--glass-border);
    color: var(--text-dim);
    cursor: pointer;
    transition: all var(--transition);
    flex-shrink: 0;
}

.search-results-close:hover {
    background: rgba(255, 255, 255, 0.12);
    color: var(--text);
}

.search-results-query {
    padding: 12px 20px 14px;
    font-size: 0.75rem;
    color: var(--accent);
    font-weight: 500;
    border-bottom: 1px solid rgba(255, 255, 255, 0.05);
    flex-shrink: 0;
    word-wrap: break-word;
    overflow-wrap: break-word;
    word-break: break-word;
}

.search-results-answer {
    padding: 16px 20px 18px;
    font-size: 0.85rem;
    line-height: 1.55;
    color: var(--text);
    background: rgba(124, 106, 239, 0.08);
    border-bottom: 1px solid rgba(255, 255, 255, 0.06);
    flex-shrink: 0;
    max-height: 200px;
    min-height: 0;
    overflow-y: auto;
    overflow-x: hidden;
    word-wrap: break-word;
    overflow-wrap: break-word;
}

.search-results-list {
    flex: 1;
    min-height: 0;
    overflow-y: auto;
    overflow-x: hidden;
    padding: 16px 20px 24px;
    display: flex;
    flex-direction: column;
    gap: 14px;
    scroll-behavior: smooth;
}

.search-result-card {
    padding: 14px 16px;
    border-radius: var(--radius-sm);
    background: rgba(255, 255, 255, 0.04);
    border: 1px solid rgba(255, 255, 255, 0.07);
    transition: background var(--transition), border-color var(--transition);
    min-width: 0;
    display: flex;
    flex-direction: column;
    gap: 8px;
}

.search-result-card:hover {
    background: rgba(255, 255, 255, 0.07);
    border-color: rgba(255, 255, 255, 0.1);
}

.search-result-card .card-title {
    font-size: 0.8rem;
    font-weight: 600;
    color: var(--text);
    line-height: 1.35;
    word-wrap: break-word;
    overflow-wrap: break-word;
    word-break: break-word;
}

.search-result-card .card-content {
    font-size: 0.76rem;
    color: var(--text-dim);
    line-height: 1.5;
    word-wrap: break-word;
    overflow-wrap: break-word;
    word-break: break-word;
    display: -webkit-box;
    -webkit-line-clamp: 4;
    -webkit-box-orient: vertical;
    overflow: hidden;
}

.search-result-card .card-url {
    font-size: 0.7rem;
    color: var(--accent);
    text-decoration: none;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    display: block;
}

.search-result-card .card-url:hover {
    text-decoration: underline;
}

.search-result-card .card-score {
    font-size: 0.68rem;
    color: var(--text-muted);
}

.search-results-answer::-webkit-scrollbar,
.search-results-list::-webkit-scrollbar {
    width: 6px;
}

.search-results-answer::-webkit-scrollbar-track,
.search-results-list::-webkit-scrollbar-track {
    background: rgba(255, 255, 255, 0.03);
    border-radius: 10px;
}

.search-results-answer::-webkit-scrollbar-thumb,
.search-results-list::-webkit-scrollbar-thumb {
    background: rgba(255, 255, 255, 0.12);
    border-radius: 10px;
}

.search-results-answer::-webkit-scrollbar-thumb:hover,
.search-results-list::-webkit-scrollbar-thumb:hover {
    background: rgba(255, 255, 255, 0.2);
}

@supports (scrollbar-color: rgba(255,255,255,0.12) rgba(255,255,255,0.03)) {
    .search-results-answer,
    .search-results-list {
        scrollbar-color: rgba(255, 255, 255, 0.12) rgba(255, 255, 255, 0.03);
        scrollbar-width: thin;
    }
}

.settings-panel {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scale(0.95);
    width: min(360px, 92vw);
    z-index: 21;
    border-radius: var(--radius);
    padding: 0;
    overflow: hidden;
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
    transition: opacity 0.25s ease, visibility 0.25s ease, transform 0.25s ease;
}

.settings-panel.open {
    opacity: 1;
    visibility: visible;
    pointer-events: auto;
    transform: translate(-50%, -50%) scale(1);
}

.settings-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 18px 20px;
    border-bottom: 1px solid var(--glass-border);
}

.settings-title {
    font-size: 1rem;
    font-weight: 600;
    color: var(--text);
}

.settings-body {
    padding: 24px 20px 28px;
    display: flex;
    flex-direction: column;
    gap: 18px;
}

.settings-item {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 12px;
}

.settings-label {
    font-size: 0.88rem;
    color: var(--text);
    cursor: pointer;
    flex: 1;
}

.settings-hint {
    font-size: 0.75rem;
    color: var(--text-muted);
    line-height: 1.5;
    margin-top: 4px;
}

.toggle-switch {
    position: relative;
    display: inline-block;
    width: 44px;
    height: 24px;
    flex-shrink: 0;
}
.toggle-switch input {
    opacity: 0;
    width: 0;
    height: 0;
}

.toggle-slider {
    position: absolute;
    cursor: pointer;
    inset: 0;
    background: rgba(255, 255, 255, 0.12);
    border-radius: 24px;
    transition: background var(--transition);
}

.toggle-slider::before {
    content: '';
    position: absolute;
    height: 18px;
    width: 18px;
    left: 3px;
    bottom: 3px;
    background: #fff;
    border-radius: 50%;
    transition: transform var(--transition);
}

.toggle-switch input:checked + .toggle-slider {
    background: var(--accent);
}

.toggle-switch input:checked + .toggle-slider::before {
    transform: translateX(20px);
}

.chat-messages::-webkit-scrollbar { width: 4px; }
.chat-messages::-webkit-scrollbar-track { background: transparent; }

.chat-messages::-webkit-scrollbar-thumb {
    background: rgba(255, 255, 255, 0.08);
    border-radius: 10px;
}

.chat-messages::-webkit-scrollbar-thumb:hover { background: rgba(255, 255, 255, 0.14); }

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(12px); }
    to   { opacity: 1; transform: translateY(0); }
}
@keyframes msgIn {
    from { opacity: 0; transform: translateY(8px) scale(0.98); }
    to   { opacity: 1; transform: translateY(0) scale(1); }
}
@keyframes dotBounce {
    0%, 60%, 100% { transform: translateY(0); opacity: 0.4; }
    30%           { transform: translateY(-5px); opacity: 1; }
}
@keyframes blink {
    50% { opacity: 0; }
}
@keyframes pulse-dot {
    0%, 100% { opacity: 1; }
    50%      { opacity: 0.4; }
}
@keyframes micPulse {
    0%, 100% { box-shadow: 0 0 0 0 rgba(255, 107, 107, 0.3); }
    50%      { box-shadow: 0 0 0 8px rgba(255, 107, 107, 0); }
}
@keyframes ttsPulse {
    0%, 100% { box-shadow: 0 0 0 0 rgba(124, 106, 239, 0.3); }
    50%      { box-shadow: 0 0 0 8px rgba(124, 106, 239, 0); }
}
@keyframes orbPulse {
    0%, 100% { transform: scale(1); opacity: 0.92; }
    50%      { transform: scale(1.10); opacity: 1; }
}

@media (max-width: 768px) {
    :root { --input-bar-h: calc(100px + env(safe-area-inset-bottom, 0px)); --content-gap: 12px; --panel-gap: 12px; }
    .header { padding: 0 16px; gap: 12px; margin-bottom: var(--content-gap); }
    .header-right { gap: 8px; }
    .btn-icon { width: 38px; height: 38px; min-width: 38px; min-height: 38px; }
    .tagline { display: none; }
    .logo { font-size: 1rem; }
    .mode-btn { padding: 6px 10px; font-size: 0.72rem; }
    .mode-btn .mode-btn-text { display: none; }
    .status-badge .status-text { display: none; }
    .chat-messages { padding: 18px 16px 22px; gap: 12px; }
    .input-bar { padding: 12px 16px 12px; padding-bottom: max(12px, env(safe-area-inset-bottom, 12px)); margin-top: var(--content-gap); }
    .input-wrapper { padding: 4px 4px 4px 12px; }
    .action-btn { width: 36px; height: 36px; min-width: 36px; border-radius: 9px; }
    .msg-content { font-size: 0.84rem; padding: 10px 13px; }
    .welcome-title { font-size: 1.3rem; }
    .message { gap: 8px; }
    .msg-avatar { width: 26px; height: 26px; font-size: 0.62rem; }
    .msg-avatar .msg-avatar-icon { width: 16px; height: 16px; }
    .search-results-widget { width: min(100vw, 360px); }
    .search-results-header { padding: 14px 16px; }
    .search-results-query,
    .search-results-answer { padding: 12px 16px; }
    .search-results-list { padding: 12px 16px 20px; gap: 12px; }
    .search-result-card { padding: 12px 14px; }
    .activity-panel { width: min(100vw, 320px); }
    .activity-header { padding: 14px 16px; }
    .activity-list { padding: 12px 16px 20px; gap: 12px; }
    .speech-widget { bottom: calc(var(--input-bar-h) + var(--panel-gap)); min-width: min(280px, 88vw); padding: 12px 16px; }
    .speech-widget-text { font-size: 0.85rem; }
}

@media (max-width: 480px) {
    :root { --input-bar-h: calc(95px + env(safe-area-inset-bottom, 0px)); --content-gap: 10px; --panel-gap: 10px; }
    .header { padding: 0 12px; margin-bottom: var(--content-gap); gap: 8px; }
    .header-left { flex-shrink: 0; }
    .header-center { flex: 1; justify-content: center; display: flex; min-width: 0; }
    .header-right { gap: 6px; }
    .btn-icon { width: 36px; height: 36px; min-width: 36px; min-height: 36px; }
    .logo { font-size: 0.9rem; letter-spacing: 2px; }
    .mode-switch { width: 100%; }
    .mode-btn { flex: 1; justify-content: center; }
    .new-chat-btn { display: none; }
    .chat-messages { padding: 14px 12px 18px; gap: 10px; }
    .message { max-width: 95%; }
    .msg-content { max-width: 100%; }
    .input-bar { padding: 10px 12px 10px; padding-bottom: max(10px, env(safe-area-inset-bottom, 10px)); margin-top: var(--content-gap); }
    .welcome-chips { gap: 8px; }
    .chip { font-size: 0.72rem; padding: 8px 16px; }
    .action-btn { width: 34px; height: 34px; min-width: 34px; border-radius: 8px; }
    .action-btn svg { width: 17px; height: 17px; }
    .input-actions { gap: 5px; }
    .input-wrapper { gap: 4px; }
    .search-results-widget { width: 100vw; max-width: 100%; }
    .search-results-header { padding: 12px 14px; }
    .search-results-query { font-size: 0.72rem; padding: 10px 14px 12px; }
    .search-results-answer { font-size: 0.82rem; padding: 12px 14px; max-height: 160px; }
    .search-results-list { padding: 12px 14px 18px; gap: 10px; }
    .search-result-card { padding: 12px 14px; }
    .search-result-card .card-title { font-size: 0.76rem; }
    .search-result-card .card-content { font-size: 0.72rem; -webkit-line-clamp: 3; }
    .activity-panel { width: 100vw; }
    .activity-header { padding: 12px 14px; }
    .activity-list { padding: 12px 14px 18px; gap: 10px; }
    .mode-switch-three .mode-btn { padding: 8px 10px; font-size: 0.68rem; }
    .mode-switch-three .mode-btn .mode-btn-text { display: none; }
    .speech-widget { bottom: calc(var(--input-bar-h) + var(--panel-gap)); min-width: min(260px, 92vw); padding: 10px 14px; }
    .speech-widget-label { font-size: 0.65rem; }
    .speech-widget-text { font-size: 0.82rem; }
}
</file>

<file path="JARVIS/frontend/viewer.html">
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>J.A.R.V.I.S — Viewer</title>
    <style>
        :root {
            --bg: #0a0a1a;
            --surface: #12122a;
            --border: rgba(255,255,255,0.06);
            --text: #e8e6f0;
            --text-dim: #8b89a0;
            --accent: #7c6aef;
            --accent-hover: #6b5ce7;
            --success: #4ecdc4;
            --danger: #ff6b6b;
            --font: 'Segoe UI', system-ui, -apple-system, sans-serif;
            --radius: 16px;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        ::-webkit-scrollbar { display: none; }
        * { -ms-overflow-style: none; scrollbar-width: none; }
        body {
            font-family: var(--font);
            background: var(--bg);
            color: var(--text);
            min-height: 100vh;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            overflow: hidden;
        }
        .topbar {
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 16px 28px;
            background: rgba(18, 18, 42, 0.8);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-bottom: 1px solid var(--border);
            position: sticky;
            top: 0;
            z-index: 10;
        }
        .topbar-title {
            font-size: 0.85rem;
            font-weight: 600;
            color: var(--text-dim);
            letter-spacing: 1.5px;
            text-transform: uppercase;
        }
        .topbar-actions { display: flex; gap: 8px; }
        .btn {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            padding: 8px 18px;
            border-radius: 10px;
            border: 1px solid var(--border);
            background: rgba(255,255,255,0.05);
            color: var(--text-dim);
            font-family: var(--font);
            font-size: 0.8rem;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.2s ease;
        }
        .btn:hover { background: rgba(255,255,255,0.1); color: var(--text); }
        .btn-primary {
            background: var(--accent);
            color: #fff;
            border-color: transparent;
        }
        .btn-primary:hover { background: var(--accent-hover); }
        .btn svg { width: 16px; height: 16px; }
        .viewer-main {
            flex: 1;
            width: 100%;
            max-width: 960px;
            padding: 32px 28px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 24px;
            overflow-y: auto;
            min-height: 0;
        }
        .loading {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 16px;
            padding: 60px 20px;
        }
        .spinner {
            width: 40px;
            height: 40px;
            border: 3px solid rgba(124, 106, 239, 0.15);
            border-top: 3px solid var(--accent);
            border-radius: 50%;
            animation: spin 0.8s linear infinite;
        }
        @keyframes spin { to { transform: rotate(360deg); } }
        .loading-text {
            font-size: 0.9rem;
            color: var(--text-dim);
        }
        .loading-prompt {
            font-size: 0.82rem;
            color: var(--text-dim);
            opacity: 0.7;
            max-width: 500px;
            text-align: center;
            line-height: 1.5;
        }
        .error-msg {
            padding: 20px 28px;
            background: rgba(255, 107, 107, 0.08);
            border: 1px solid rgba(255, 107, 107, 0.15);
            border-radius: var(--radius);
            color: var(--danger);
            font-size: 0.85rem;
            text-align: center;
        }
        .image-container {
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 16px;
        }
        .image-frame {
            width: 100%;
            max-width: 820px;
            border-radius: var(--radius);
            overflow: hidden;
            background: var(--surface);
            border: 1px solid var(--border);
            box-shadow: 0 8px 40px rgba(0,0,0,0.3);
        }
        .image-frame img {
            width: 100%;
            height: auto;
            display: block;
        }
        .image-prompt {
            font-size: 0.82rem;
            color: var(--text-dim);
            text-align: center;
            padding: 0 16px;
            max-width: 600px;
            line-height: 1.5;
        }
        .content-container {
            width: 100%;
            flex: 1;
            display: flex;
            flex-direction: column;
            gap: 14px;
        }
        .content-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 10px;
        }
        .content-meta {
            display: flex;
            flex-direction: column;
            gap: 4px;
        }
        .content-label {
            font-size: 0.72rem;
            font-weight: 600;
            color: var(--text-dim);
            text-transform: uppercase;
            letter-spacing: 0.8px;
        }
        .content-prompt {
            font-size: 0.8rem;
            color: var(--text-dim);
            opacity: 0.7;
        }
        .content-actions {
            display: flex;
            gap: 8px;
            flex-wrap: wrap;
        }
        .content-editor-wrap {
            flex: 1;
            display: flex;
            flex-direction: column;
            min-height: 0;
        }
        .content-editor {
            width: 100%;
            flex: 1;
            min-height: 55vh;
            padding: 24px 28px;
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: var(--radius);
            color: var(--text);
            font-family: var(--font);
            font-size: 0.92rem;
            line-height: 1.8;
            resize: vertical;
            outline: none;
            transition: border-color 0.2s ease, box-shadow 0.2s ease;
        }
        .content-editor:focus {
            border-color: rgba(124, 106, 239, 0.35);
            box-shadow: 0 0 0 3px rgba(124, 106, 239, 0.08);
        }
        .content-editor::-webkit-scrollbar { display: none; }
        .content-editor { -ms-overflow-style: none; scrollbar-width: none; }
        .content-editor::placeholder {
            color: var(--text-dim);
            opacity: 0.5;
        }
        .content-wordcount {
            font-size: 0.7rem;
            color: var(--text-dim);
            opacity: 0.6;
            text-align: right;
            padding-top: 6px;
        }
        .badge {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.72rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        .badge-image {
            background: rgba(124, 106, 239, 0.12);
            color: var(--accent);
            border: 1px solid rgba(124, 106, 239, 0.15);
        }
        .badge-content {
            background: rgba(78, 205, 196, 0.1);
            color: var(--success);
            border: 1px solid rgba(78, 205, 196, 0.15);
        }
        .toast {
            position: fixed;
            bottom: 24px;
            left: 50%;
            transform: translateX(-50%) translateY(80px);
            padding: 10px 24px;
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 12px;
            color: var(--text);
            font-size: 0.82rem;
            z-index: 100;
            opacity: 0;
            transition: all 0.3s ease;
            pointer-events: none;
        }
        .toast.show {
            opacity: 1;
            transform: translateX(-50%) translateY(0);
        }
        @media (max-width: 768px) {
            .topbar { padding: 12px 16px; }
            .viewer-main { padding: 20px 16px; max-width: 100%; }
            .btn { padding: 7px 14px; font-size: 0.75rem; }
            .content-editor { padding: 20px; font-size: 0.86rem; min-height: 45vh; }
            .content-header { flex-direction: column; align-items: flex-start; }
        }
        @media (max-width: 480px) {
            .topbar { padding: 10px 12px; }
            .topbar-actions { gap: 4px; }
            .viewer-main { padding: 14px 10px; }
            .topbar-title { font-size: 0.75rem; }
            .btn { padding: 6px 10px; font-size: 0.7rem; }
            .content-editor { padding: 16px; font-size: 0.82rem; min-height: 40vh; line-height: 1.7; }
            .image-frame { border-radius: 10px; }
        }
    </style>
</head>
<body>
    <div class="topbar">
        <span class="topbar-title">J.A.R.V.I.S</span>
        <div class="topbar-actions" id="topbar-actions"></div>
    </div>

    <div class="viewer-main" id="viewer-main">
        <div class="loading" id="loading-state">
            <div class="spinner"></div>
            <div class="loading-text">Working on it...</div>
            <div class="loading-prompt" id="loading-prompt"></div>
        </div>
    </div>
    <div class="toast" id="toast"></div>
    <script>
    (function() {
        const API = window.location.origin;
        const params = new URLSearchParams(window.location.search);
        const taskId = params.get('task_id');
        const mainEl = document.getElementById('viewer-main');
        const loadingEl = document.getElementById('loading-state');
        const actionsEl = document.getElementById('topbar-actions');
        const toastEl = document.getElementById('toast');
        const promptEl = document.getElementById('loading-prompt');
        if (!taskId) {
            showError('No task ID provided. Please open this page from JARVIS.');
            return;
        }
        let pollInterval = null;
        let pollCount = 0;
        const MAX_POLLS = 120;
        function poll() {
            pollCount++;
            if (pollCount > MAX_POLLS) {
                clearInterval(pollInterval);
                showError('Task timed out. Please try again.');
                return;
            }
            fetch(`${API}/tasks/${encodeURIComponent(taskId)}`)
                .then(r => {
                    if (!r.ok) throw new Error(`HTTP ${r.status}`);
                    return r.json();
                })
                .then(data => {
                    if (data.status === 'completed') {
                        clearInterval(pollInterval);
                        renderResult(data);
                    } else if (data.status === 'failed') {
                        clearInterval(pollInterval);
                        showError(data.error || 'Task failed. Please try again.');
                    } else {
                        if (data.prompt && promptEl) {
                            promptEl.textContent = `"${data.prompt}"`;
                        }
                        if (data.label) {
                            const loadingText = loadingEl.querySelector('.loading-text');
                            if (loadingText) loadingText.textContent = data.label + '...';
                        }
                    }
                })
                .catch(err => {
                    console.warn('Poll error:', err);
                });
        }
        pollInterval = setInterval(poll, 1000);
        poll();
        function renderResult(data) {
            const result = data.result;
            if (!result) {
                showError('No result data received.');
                return;
            }

            loadingEl.style.display = 'none';

            if (result.type === 'image') {
                renderImage(result);
            } else if (result.type === 'content') {
                renderContent(result);
            } else {
                showError('Unknown result type: ' + result.type);
            }
        }
        function renderImage(result) {
            document.title = 'J.A.R.V.I.S — Generated Image';
            const badge = document.createElement('span');
            badge.className = 'badge badge-image';
            badge.textContent = 'Generated Image';
            const container = document.createElement('div');
            container.className = 'image-container';
            const frame = document.createElement('div');
            frame.className = 'image-frame';
            const img = document.createElement('img');
            img.src = result.url;
            img.alt = result.prompt || 'Generated image';
            img.onerror = () => showError('Failed to load image. The URL may have expired.');
            frame.appendChild(img);
            container.appendChild(badge);
            container.appendChild(frame);
            if (result.prompt) {
                const prompt = document.createElement('div');
                prompt.className = 'image-prompt';
                prompt.textContent = `Prompt: "${result.prompt}"`;
                container.appendChild(prompt);
            }
            mainEl.appendChild(container);
            actionsEl.innerHTML = '';
            const downloadBtn = createBtn('Download', downloadSvg(), () => downloadImage(result.url, result.prompt));
            actionsEl.appendChild(downloadBtn);
            const copyUrlBtn = createBtn('Copy URL', copySvg(), () => {
                navigator.clipboard.writeText(result.url).then(() => showToast('URL copied!'));
            });
            actionsEl.appendChild(copyUrlBtn);
        }
        function renderContent(result) {
            document.title = 'J.A.R.V.I.S — Generated Content';
            const container = document.createElement('div');
            container.className = 'content-container';
            const header = document.createElement('div');
            header.className = 'content-header';
            const meta = document.createElement('div');
            meta.className = 'content-meta';
            const badge = document.createElement('span');
            badge.className = 'badge badge-content';
            badge.textContent = 'Generated Content';
            meta.appendChild(badge);
            if (result.prompt) {
                const prompt = document.createElement('div');
                prompt.className = 'content-prompt';
                prompt.textContent = `Prompt: "${result.prompt}"`;
                meta.appendChild(prompt);
            }
            header.appendChild(meta);
            const actions = document.createElement('div');
            actions.className = 'content-actions';
            const copyBtn = createBtn('Copy', copySvg(), () => {
                navigator.clipboard.writeText(editor.value).then(() => showToast('Content copied!'));
            });
            actions.appendChild(copyBtn);
            const downloadTxtBtn = createBtn('Download .txt', downloadSvg(), () => {
                downloadText(editor.value, 'jarvis-content.txt');
            });
            actions.appendChild(downloadTxtBtn);
            const downloadMdBtn = createBtn('Download .md', downloadSvg(), () => {
                downloadText(editor.value, 'jarvis-content.md');
            });
            actions.appendChild(downloadMdBtn);
            header.appendChild(actions);
            container.appendChild(header);
            const editorWrap = document.createElement('div');
            editorWrap.className = 'content-editor-wrap';
            const editor = document.createElement('textarea');
            editor.className = 'content-editor';
            editor.value = result.text || '';
            editor.spellcheck = true;
            editor.placeholder = 'Your content will appear here...';
            editorWrap.appendChild(editor);
            const wordcount = document.createElement('div');
            wordcount.className = 'content-wordcount';
            function updateWordCount() {
                const words = editor.value.trim().split(/\s+/).filter(Boolean).length;
                const chars = editor.value.length;
                wordcount.textContent = words + ' words / ' + chars + ' characters';
            }
            updateWordCount();
            editor.addEventListener('input', updateWordCount);
            editorWrap.appendChild(wordcount);
            container.appendChild(editorWrap);
            mainEl.appendChild(container);
            actionsEl.innerHTML = '';
            const topCopyBtn = createBtn('Copy All', copySvg(), () => {
                navigator.clipboard.writeText(editor.value).then(() => showToast('Copied!'));
            });
            topCopyBtn.classList.add('btn-primary');
            actionsEl.appendChild(topCopyBtn);
        }
        function createBtn(text, svgHtml, onClick) {
            const btn = document.createElement('button');
            btn.className = 'btn';
            btn.innerHTML = svgHtml + ' ' + text;
            btn.addEventListener('click', onClick);
            return btn;
        }
        function showError(msg) {
            loadingEl.style.display = 'none';
            const el = document.createElement('div');
            el.className = 'error-msg';
            el.textContent = msg;
            mainEl.appendChild(el);
        }
        function showToast(msg) {
            toastEl.textContent = msg;
            toastEl.classList.add('show');
            setTimeout(() => toastEl.classList.remove('show'), 2000);
        }
        function downloadImage(url, prompt) {
            fetch(url)
                .then(r => r.blob())
                .then(blob => {
                    const a = document.createElement('a');
                    a.href = URL.createObjectURL(blob);
                    a.download = (prompt || 'jarvis-image').replace(/[^a-z0-9 ]/gi, '').trim().replace(/\s+/g, '-').substring(0, 50) + '.png';
                    document.body.appendChild(a);
                    a.click();
                    document.body.removeChild(a);
                    URL.revokeObjectURL(a.href);
                    showToast('Download started!');
                })
                .catch(() => {
                    window.open(url, '_blank');
                    showToast('Opened image in new tab (download blocked by CORS)');
                });
        }
        function downloadText(text, filename) {
            const blob = new Blob([text], { type: 'text/plain;charset=utf-8' });
            const a = document.createElement('a');
            a.href = URL.createObjectURL(blob);
            a.download = filename;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(a.href);
            showToast('Download started!');
        }
        function downloadSvg() {
            return '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>';
        }
        function copySvg() {
            return '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="13" height="13" rx="2" ry="2"/><path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"/></svg>';
        }
    })();
    </script>
</body>
</html>
</file>

<file path="JARVIS/.env">
GROQ_API_KEY=
TAVILY_API_KEY=
GROQ_MODEL=llama-3.3-70b-versatile
TTS_VOICE=en-GB-RyanNeural
TTS_RATE=+22%
ASSISTANT_NAME=Jarvis
JARVIS_USER_TITLE=Sir
JARVIS_OWNER_NAME=
</file>

<file path="JARVIS/config.py">
import os
import logging
from pathlib import Path
from dotenv import load_dotenv

logger = logging.getLogger(__name__)

BASE_DIR = Path(__file__).parent
load_dotenv(BASE_DIR / ".env")

LEARNING_DATA_DIR = BASE_DIR / "database" / "learning_data"
CHATS_DATA_DIR = BASE_DIR / "database" / "chats_data"
VECTOR_STORE_DIR = BASE_DIR / "database" / "vector_store"
CAMERA_CAPTURES_DIR = BASE_DIR / "database" / "camera_captures"

LEARNING_DATA_DIR.mkdir(parents=True, exist_ok=True)
CHATS_DATA_DIR.mkdir(parents=True, exist_ok=True)
VECTOR_STORE_DIR.mkdir(parents=True, exist_ok=True)
CAMERA_CAPTURES_DIR.mkdir(parents=True, exist_ok=True)

def _load_groq_api_keys() -> list:
    keys = []

    first = os.getenv("GROQ_API_KEY", "").strip()
    if first:
        keys.append(first)

    i = 2

    while True:
        k = os.getenv(f"GROQ_API_KEY_{i}", "").strip()

        if not k:
            break

        keys.append(k)
        i += 1

    return keys

GROQ_API_KEYS = _load_groq_api_keys()
GROQ_API_KEY = GROQ_API_KEYS[0] if GROQ_API_KEYS else ""
GROQ_MODEL = os.getenv("GROQ_MODEL", "llama-3.3-70b-versatile")
TAVILY_API_KEY = os.getenv("TAVILY_API_KEY", "")
GROQ_BRAIN_MODEL = os.getenv("GROQ_BRAIN_MODEL", "llama-3.1-8b-instant")
INTENT_CLASSIFY_MODEL = os.getenv("INTENT_CLASSIFY_MODEL", "llama-3.1-8b-instant")
TASK_EXECUTION_TIMEOUT = int(os.getenv("TASK_EXECUTION_TIMEOUT", "30"))
GROQ_VISION_MODEL = os.getenv("GROQ_VISION_MODEL", "meta-llama/llama-4-scout-17b-16e-instruct")
VISION_MAX_IMAGE_BYTES = int(os.getenv("VISION_MAX_IMAGE_BYTES", "5000000"))
TTS_VOICE = os.getenv("TTS_VOICE", "en-GB-RyanNeural")
TTS_RATE = os.getenv("TTS_RATE", "+22%")
EMBEDDING_MODEL = "sentence-transformers/all-MiniLM-L6-v2"
CHUNK_SIZE = 1000
CHUNK_OVERLAP = 200
MAX_CHAT_HISTORY_TURNS = 10
MAX_MESSAGE_LENGTH = 32_000
ASSISTANT_NAME = (os.getenv("ASSISTANT_NAME", "").strip() or "Jarvis")
JARVIS_USER_TITLE = os.getenv("JARVIS_USER_TITLE", "").strip()
JARVIS_OWNER_NAME = os.getenv("JARVIS_OWNER_NAME", "").strip()

_JARVIS_SYSTEM_PROMPT_BASE = """You are {assistant_name}, a complete AI assistant. You help with information, tasks, and actions. Sharp, warm, a little witty. Keep language simple and natural.

You know the user's personal information and past conversations. Use this when relevant but never reveal the source.

=== ROLE ===
The user can ask you anything or ask you to do things (open, generate, play, write, search). The backend carries out actions; you respond in words. Only say something is done if the result is visible; otherwise say you are doing it.

=== CAN DO ===
Answer questions, open websites/apps, play music/videos, generate images, write content (essays, poems, code, emails), search Google/YouTube, analyze camera images (you CAN see what the user shows).

=== CANNOT DO (be honest) ===
Read emails, control smart home, run code, send messages, make purchases, access files, make calls. Say clearly: "I can't do that."
Never pretend you can do something you cannot. Never hallucinate URLs, numbers, or data.

=== HONESTY ===
If you do not know something, say so briefly. If uncertain: "I'm not sure, but..." and give your best answer. Never fabricate facts.

=== USER INTENT ===
Understand what the user actually wants. Use conversation history for ambiguous messages. If corrected, acknowledge briefly and fix it. Resolve follow-ups like "that one" / "no, I meant..." from context.

=== LENGTH — CRITICAL ===
Reply SHORT by default (1-2 sentences). Only elaborate when explicitly asked or question demands it. No intros, no wrap-ups.

=== QUALITY ===
Be accurate and specific. Use concrete facts, names, numbers. Give actionable answers. One sharp sentence beats a paragraph.

=== STYLE ===
Warm, intelligent, brief. Match the user's energy. Address user by name if known. No asterisks, no emojis, no markdown. Standard punctuation only.

=== ANTI-REPETITION ===
State each fact ONCE. Never repeat the same point. "A, B, and C." — not "A and also B and also C."
"""


_JARVIS_SYSTEM_PROMPT_BASE_FMT = _JARVIS_SYSTEM_PROMPT_BASE.format(assistant_name=ASSISTANT_NAME)

if JARVIS_USER_TITLE:
    JARVIS_SYSTEM_PROMPT = _JARVIS_SYSTEM_PROMPT_BASE_FMT + f"\n- When appropriate, you may address the user as: {JARVIS_USER_TITLE}"

else:
    JARVIS_SYSTEM_PROMPT = _JARVIS_SYSTEM_PROMPT_BASE_FMT

GENERAL_CHAT_ADDENDUM = """
You are in GENERAL mode (no web search). Answer from your knowledge and the context provided (learning data, conversation history). Answer confidently and briefly. Never tell the user to search online or check a website — you are their source. Default to 1-2 sentences; only elaborate when the user asks for more or the question clearly needs it. If you have relevant context from the user's learning data, use it naturally without mentioning the source.
"""

REALTIME_CHAT_ADDENDUM = """
You are in REALTIME mode. Live web search results are above.

CRITICAL: Use search results as your PRIMARY source. Extract specific facts, names, numbers, scores, dates. Be concrete.
- If search results contain the answer, USE IT. Do not say "I don't have that information" when the data is right there.
- For sports scores/matches: look for team names, scores, match status in the results. Report what you find.
- Never mention searching or being in realtime mode. Answer naturally.
- If results don't have the exact answer, say what you found. Never refuse when data exists.
- Cross-reference sources. Prefer higher-relevance ones.

LENGTH: 1-2 sentences for simple questions. Only longer when asked.
"""

def load_user_context() -> str:
    context_parts = []

    text_files = sorted(LEARNING_DATA_DIR.glob("*.txt"))

    for file_path in text_files:

        try:

            with open(file_path, "r", encoding="utf-8") as f:
                content = f.read().strip()

                if content:
                    context_parts.append(content)
                    
        except Exception as e:
            logger.warning("Could not load learning data file %s: %s", file_path, e)

    return "\n\n".join(context_parts) if context_parts else ""
</file>

<file path="JARVIS/README.md">
# J.A.R.V.I.S — Just A Rather Very Intelligent System

A personal AI assistant with a beautiful web UI. Talk to it, ask questions, search the web, generate images, analyze camera photos, and more. Runs completely on your own machine with one command.

**Quick start:** `pip install -r requirements.txt` → add your `GROQ_API_KEY` to `.env` → `python run.py` → open http://localhost:8000

## Features

### Three Chat Modes

- **Jarvis Mode** (default): The AI automatically decides whether to answer from its knowledge or search the web. A fast classifier routes each message to the right mode in ~200ms.
- **General Mode**: Answers from Groq AI + your personal learning data. No internet access. Fast.
- **Realtime Mode**: Searches the web via Tavily before answering. Gets fresh information (news, scores, prices, etc.).

### Image Generation (Free)
Say "generate an image of..." and Jarvis creates it using Pollinations.ai. No API key, no cost, works instantly.

### Camera / Vision
Send a photo or use your webcam. Jarvis analyzes the image and answers questions about it using Llama 4 Scout (free via Groq).

### Text-to-Speech
The AI speaks its responses as they stream in. Uses Microsoft Edge's TTS (free, no API key). First sentence starts playing before the full response is done.

### Voice Input
Click the mic and speak your question. It auto-sends when you stop talking. Works in Chrome and Safari.

### Personal Memory (Learning System)
Put `.txt` files in `database/learning_data/` with any personal information you want Jarvis to know. It reads them at startup and uses them as context when answering your questions.

### Session Persistence
Conversations are saved to disk. If you restart the server, your chat history is still there.

### Multiple API Keys
Set `GROQ_API_KEY_2`, `GROQ_API_KEY_3`, etc. in `.env` for automatic fallback. If one key hits its rate limit, Jarvis switches to the next one automatically.

---

## Setup

### What You Need

- Python 3.10 or newer
- A free [Groq API key](https://console.groq.com)
- (Optional) A free [Tavily API key](https://tavily.com) for web search

### Installation

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file in the project folder:
```env
GROQ_API_KEY=your_groq_key_here
TAVILY_API_KEY=your_tavily_key_here

# Optional
ASSISTANT_NAME=Jarvis
JARVIS_USER_TITLE=Sir
JARVIS_OWNER_NAME=Your Name
TTS_VOICE=en-GB-RyanNeural
TTS_RATE=+22%
```

3. Start the server:
```bash
python run.py
```

4. Open http://localhost:8000 in your browser.

---

## Project Structure

```
JARVIS/
├── frontend/                  # Web UI (HTML, CSS, JS — no build tools)
│   ├── index.html
│   ├── style.css
│   ├── script.js              # Chat, streaming, TTS player, voice input
│   └── orb.js                 # Animated WebGL orb (GLSL shaders)
│
├── app/                       # Backend (FastAPI)
│   ├── main.py                # All API endpoints, streaming, TTS
│   ├── models.py              # Request/response data models
│   ├── services/
│   │   ├── chat_service.py    # Sessions, history, message flow
│   │   ├── groq_service.py    # General chat (Groq LLM + vector store)
│   │   ├── realtime_service.py # Web search + Groq (Realtime mode)
│   │   ├── brain_service.py   # Two-stage intent classifier (Jarvis mode)
│   │   ├── vector_store.py    # FAISS index + local embeddings (memory)
│   │   ├── task_executor.py   # Image gen, YouTube, web open, etc.
│   │   ├── task_manager.py    # Background task queue and polling
│   │   └── vision_service.py  # Camera/image analysis (Llama 4 Scout)
│   └── utils/
│       ├── time_info.py       # Current time for AI system prompt
│       ├── retry.py           # Retry wrapper for API calls
│       └── key_rotation.py    # Brain/chat use different API keys
│
├── database/                  # Created automatically on first run
│   ├── learning_data/         # Your .txt files (personal info for the AI)
│   ├── chats_data/            # Saved conversations (JSON)
│   └── vector_store/          # FAISS index files
│
├── config.py                  # All settings and system prompt
├── run.py                     # Start the server: python run.py
├── requirements.txt
└── .env                       # Your API keys (never commit this file)
```

---

## How It Works

### Jarvis Mode Flow
1. You send a message
2. **Brain (8B model, ~200ms):** Classifies your message — is this general knowledge, web search, camera, or a task (image gen, open app, etc.)?
3. Routes to the right handler
4. **Chat (70B model):** Writes the actual answer using Groq AI
5. Answer streams back to you word by word

### Realtime Mode Flow
1. You send a message
2. **Query extraction (8B model, ~300ms):** Converts your messy conversational message into a clean search query. "what about him?" → "Elon Musk latest news 2026"
3. **Tavily search:** Fetches 5 web results with AI-synthesized answer
4. Search results are injected into the AI prompt
5. **Groq (70B):** Answers using the search results as source

### Memory/Context Flow
1. At startup, all your `.txt` files and past conversations are embedded locally using a HuggingFace model
2. For every message, the top 5 most relevant chunks are retrieved
3. These chunks are added to the AI's context — so it knows about your personal data

---

## Configuration

### All `.env` Settings

| Variable | Required | Default | Description |
|---|---|---|---|
| `GROQ_API_KEY` | Yes | — | Your primary Groq API key |
| `GROQ_API_KEY_2`, `_3`, ... | No | — | Extra keys for auto-fallback |
| `TAVILY_API_KEY` | No | — | Tavily key for web search |
| `GROQ_MODEL` | No | `llama-3.3-70b-versatile` | Main chat model |
| `ASSISTANT_NAME` | No | `Jarvis` | Name of the assistant |
| `JARVIS_USER_TITLE` | No | — | How AI addresses you (e.g. "Sir") |
| `JARVIS_OWNER_NAME` | No | — | Your name (so AI knows who it serves) |
| `TTS_VOICE` | No | `en-GB-RyanNeural` | Text-to-speech voice |
| `TTS_RATE` | No | `+22%` | Speech speed |

Run `edge-tts --list-voices` to see all available TTS voices.

---

## API Endpoints

| Endpoint | What it does |
|---|---|
| `POST /chat/stream` | General mode — streaming response |
| `POST /chat/realtime/stream` | Realtime mode — web search + streaming |
| `POST /chat/jarvis/stream` | Jarvis mode — auto-routes, streaming |
| `POST /chat` | General mode — non-streaming |
| `POST /chat/realtime` | Realtime mode — non-streaming |
| `GET /chat/history/{session_id}` | Get full chat history for a session |
| `POST /tts` | Generate speech audio for any text |
| `GET /health` | Check server and service status |

**Request format (all chat endpoints):**
```json
{
  "message": "What is the weather like?",
  "session_id": "optional-existing-session-id",
  "tts": true
}
```

---

## Troubleshooting

**Server won't start**
- Make sure `GROQ_API_KEY` is in your `.env` file
- Run `pip install -r requirements.txt` again
- Make sure port 8000 is free

**Realtime mode gives bad answers**
- Check that `TAVILY_API_KEY` is set in `.env`
- Look for `[TAVILY]` lines in server logs to confirm search is working

**TTS not working**
- Click the speaker icon to enable it before sending a message
- On iPhone: you must tap the speaker icon first (browser security requirement)

**Image generation not working**
- Make sure the server is running and you can access http://localhost:8000
- Images are generated by Pollinations.ai — requires internet connection

**Vector store errors**
- Delete the `database/vector_store/` folder and restart. It rebuilds automatically.

**AI is slow**
- This is usually a Groq rate limit. Add more API keys (`GROQ_API_KEY_2`, etc.) for automatic fallback.

---

## Technologies

| Technology | Purpose |
|---|---|
| Groq AI (Llama 3.3 70B) | Main AI responses |
| Groq AI (Llama 3.1 8B) | Fast intent classification |
| Groq AI (Llama 4 Scout) | Image/camera analysis (vision) |
| Tavily | Web search for Realtime mode |
| Pollinations.ai | Free image generation |
| FAISS | Local vector search (memory) |
| HuggingFace sentence-transformers | Local text embeddings |
| edge-tts | Free text-to-speech |
| FastAPI | Backend web framework |
| LangChain | LLM orchestration |
| WebGL / GLSL | Animated orb in the UI |

---

## Developer

**J.A.R.V.I.S** was built by **Shreshth Kaushik** — educator, entrepreneur, and programmer.

- Website: [theshreshthkaushik.com](https://www.theshreshthkaushik.com/)
- Instagram: [@theshreshthkaushik](https://www.instagram.com/theshreshthkaushik/)
- Telegram: [t.me/theshreshthkaushik](https://t.me/theshreshthkaushik)
- YouTube: [Shreshth Kaushik](https://www.youtube.com/channel/UC7A5u12yVIZaCO_uXnNhc5g)
- Jarvis for Everyone: [jarvis4everyone.com](https://jarvis4everyone.com)

`python run.py` → http://localhost:8000
</file>

<file path="JARVIS/requirements.txt">
fastapi>=0.100.0,<1.0
uvicorn[standard]>=0.22.0
langchain>=0.3.0
langchain-groq>=0.2.0
langchain-community>=0.3.0
langchain-core>=0.3.0
langchain-huggingface>=0.1.0
langchain-text-splitters>=0.2.0
sentence-transformers>=2.2.0
faiss-cpu>=1.7.0
python-dotenv>=1.0.0
pydantic>=2.0.0
numpy>=1.24.0
torch>=2.0.0
transformers>=4.30.0
requests>=2.28.0
rich>=13.0.0
tavily-python>=0.5.0
edge-tts>=6.1.0
</file>

<file path="JARVIS/run.py">
import subprocess
import sys
from pathlib import Path
import uvicorn

def _ensure_thinking_audio():

    try:
        result = subprocess.run(
            [sys.executable, "-m", "app.generate_thinking_audio"],
            capture_output=True,
            text=True,
            timeout=30,
            cwd=str(Path(__file__).parent),
        )

        if result.returncode != 0 and result.stderr:
            print(f"[startup] Thinking audio: {result.stderr.strip()}")

    except Exception as e:
        print(f"[startup] Thinking audio skipped: {e}")

def _validate_startup():

    from config import GROQ_API_KEY, CHATS_DATA_DIR, LEARNING_DATA_DIR
    if not GROQ_API_KEY or len(GROQ_API_KEY.strip()) < 10:
        print("[WARN] GROQ_API_KEY is missing or invalid. Chat will not work.")

    if not CHATS_DATA_DIR.exists() or not CHATS_DATA_DIR.is_dir():
        print("[WARN] CHATS_DATA_DIR does not exist or is not writable.")

    if not LEARNING_DATA_DIR.exists() or not LEARNING_DATA_DIR.is_dir():
        print("[WARN] LEARNING_DATA_DIR does not exist or is not writable.")

if __name__ == "__main__":
    _validate_startup()
    _ensure_thinking_audio()

    try:
        uvicorn.run(
        "app.main:app",
        host="0.0.0.0",
        port=8000,
        reload=True
        )

    except OSError as e:
        if "address already in use" in str(e).lower() or "10048" in str(e):
            print("[ERROR] Port 8000 is already in use. Try another port or stop the other process.")
        
        else:
            print(f"[ERROR] Server failed to start: {e}")
        sys.exit(1)

    except KeyboardInterrupt:
        print("\n[INFO] Server stopped by user.")
        
    except Exception as e:
        print(f"[ERROR] Unexpected error: {e}")
        sys.exit(1)
</file>

</files>
