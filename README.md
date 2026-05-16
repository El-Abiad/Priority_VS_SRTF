# Priority VS SRTF Scheduler

A browser-based CPU scheduling simulator that runs **Shortest Remaining Time First (SRTF)** and **Priority Scheduling** side by side, then compares their performance.


## Algorithms

| Algorithm | Type | Selection Criterion |
|-----------|------|---------------------|
| SRTF | Preemptive | Shortest remaining burst time |
| Priority | Preemptive | Lowest priority number = highest priority |

## Tech Stack

HTML · CSS · Vanilla JavaScript

## Sample Test Case

| Process | Arrival | Burst | Priority |
|---------|---------|-------|----------|
| P1 | 0 | 8 | 3 |
| P2 | 1 | 4 | 1 |
| P3 | 2 | 2 | 2 |

| Process | Arrival | Burst | Priority |
|---------|---------|-------|----------|
| P1 | 0 | 6 | 2 |
| P2 | 0 | 3 | 1 |
| P3 | 0 | 1 | 3 |
