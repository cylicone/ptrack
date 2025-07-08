# ptrack – Personal Project Time Tracker

**ptrack** is a minimalist command-line time tracker written in Go.  
It's designed to help you track the time you spend on different projects — cleanly, quickly, and without distractions.

Built for developers, makers, and anyone who prefers productivity in the terminal.

---

## Features

- Start and stop project timers easily
-  View detailed logs and session summaries
-  Stores data locally in clean JSON (no databases!)
- Integrates into your terminal with no fluff
- Simple commands that just make sense

---

## 📦 Installation

1. Clone the repository:
```bash
   git clone https://github.com/your-username/ptrack.git
   cd ptrack
```
2. Build it:
```bash
go build -o ptrack
```
Move it to your $PATH (e.g., ~/bin):
```bash
    mv ptrack ~/bin/
```
Done! You can now use ptrack from anywhere in your terminal.

🧪 Example Usage

ptrack create my_website          # Create a new project
ptrack start my_website           # Start timing piano practice
ptrack stop my_website            # Stop the timer
ptrack stats my_website           # View logs and sessions
ptrack report                # Get summary across all projects

🧰 Commands
Command	Description
create [project]	Create a new project
delete [project]	Delete a project and all of its time logs
start [project]	Start tracking time on a project
stop [project]	Stop timing a project session
status	Show currently running sessions
stats [project]	View all logs for a project
report	See total time spent on all projects
list	List all projects you've created
help	Show usage instructions

# 📁 Where Data Is Stored

Your data lives in:

~/.ptrack/data.json       # All tracked data
~/.ptrack/ptracker.log    # Internal debug log

No external dependencies. It's just you, your terminal, and your work.
Ideas for Future Features

   - Idle session detection

   - Export to CSV

    - Weekly time breakdowns

    - Tags or categories for projects

# Author

**Ethan Annane**
Built to solve a real problem, tracking projects without bloated tools.
# License

MIT License — free to use, hack, and extend.
🎯 Final Note

Its my honest attempt at making a simple, light time tracker, one that fits into your real developer workflow.
Use it to stay mindful of how you spend your time, and see what you spend the most time on.

   **Happy tracking. You build cool stuff, now measure it.**
