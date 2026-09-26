# CPU Scheduling Simulator and Performance Analyzer

A GitHub Pages-ready web application for the Operating Systems Midterm Project.

## Included requirements

- Process input: process name, arrival time, burst time, priority
- Supports 5 or more processes
- FCFS
- SJF (non-preemptive)
- SRTF (preemptive)
- Round Robin with user-defined time quantum
- Priority Scheduling: non-preemptive and preemptive (bonus)
- Smaller priority number = higher priority
- Gantt chart with process names and start/end times
- CPU idle periods
- Completion Time, Turnaround Time, Waiting Time, Response Time
- Average Waiting, Turnaround, and Response Time
- Algorithm comparison table
- Automatic interpretation text
- Tie-breaking rules documented in the UI
- Responsive interface for desktop and mobile
- No server or database required

## Run locally

Open `index.html` in a browser. No installation is required.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `cpu-scheduling-simulator`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. GitHub will provide the public Pages address for the repository.

## Project-source basis

The implementation follows the supplied Operating Systems Midterm Project specification: five required scheduling algorithms, process arrival times, preemption where applicable, Gantt timeline, scheduling metrics, comparison, CPU idle handling, multiple Round Robin cycles, and documented tie-breaking rules.
