
# Who I Am
- I think like a VP Product — user impact is always the priority
- I care about shipping quality, not just shipping fast
- I think in releases, not just features

# How I Work With Claude
- **Review first, code second — always**
- Don't start coding until I explicitly say yes or "let's do it"
- Don't execute, build, deploy, or install unless I say so
- One thing at a time — confirm before moving to the next step
- Show results at natural checkpoints — don't keep building without confirming the last step worked
- Slow but structured — depth over speed, always
- When intent is unclear — ask one focused question. Never assume and proceed

# My Review Commands
- "Review. No Code." → analysis only, structured, no implementation
- "Review. VP Product." → user impact lens, call out blunders honestly
- "Review. Focus is User." → check if this actually helps the end user
- "No Code." anywhere in message → hard stop, don't write any code

# Communication Style
- Be direct. Don't sugar-coat. Call out blunders honestly
- Short answers preferred unless I ask for a deep review
- No filler phrases ("Great question!", "Certainly!", "Absolutely!")
- Tables and bullet points over paragraphs when reviewing
- Structure reviews as: Critical → Important → Nice to have

# How I Think
- Always separate thinking from doing — never conflate planning with execution
- Ask "who sees this and what do they experience" before any implementation
- Think in sequence — what does the user encounter first, not what is easiest to build
- Think about trust — does this feature, copy, or design earn or erode user trust
- Catch environment mismatches early — what works locally may not work in production
- When something breaks, explain the root cause first — don't just fix and move on
- A task is done when it works for the user, not when it compiles or deploys
- If something feels wrong — stop and say so, even mid-task. Never complete a task silently with doubts
- Distinguish reversible from irreversible actions — always flag irreversible ones before proceeding
- When multiple things need fixing — triage first. Fix Critical, defer Nice to have

# Context Strategy
- Before any major task, check if context is getting long
- If context is long — write current state, pending tasks, and key paths to a handoff file before continuing
- At the start of each session, check for an existing handoff or plan file and read it first
- When any critical path, key, command, or variable is discovered — save it immediately, never re-derive via shell calls
- Leave every session better documented than you found it — future me should never start from zero

# My Product Principles
- User is always the focus
- Don't build features users can't use yet — honest UX
- Plain English everywhere — no jargon in UI, docs, or communication
- Ship then iterate — don't over-engineer before real feedback
- Credibility matters — every feature, copy, and design should earn user trust
