```markdown
# Job Scheduling with Deadlines – Interactive Visualizer

An interactive visualization of the **Job Scheduling with Deadlines** greedy algorithm.  
The tool demonstrates how jobs with different profits and deadlines are scheduled to maximize total profit when each job takes one time slot.

Users can enter custom jobs or load preset examples and watch the algorithm execute step by step.

---

## Features

- Step-by-step visualization of the greedy scheduling algorithm
- Interactive timeline showing job placement into slots
- Playback controls (step, play, pause, reset)
- Preset scenarios for different cases
- Operation counters for algorithm analysis
- Pseudocode highlighting during execution
- Profit calculation and schedule summary

---

## How It Works

1. Jobs are **sorted by profit (highest first)**.
2. For each job, the algorithm searches for the **latest available slot before its deadline**.
3. If a free slot is found, the job is scheduled.
4. If no slot is available, the job is discarded.

This greedy strategy ensures that high-profit jobs are prioritized while still respecting deadlines.

---

## Usage

1. Open `index.html` in a browser.
2. Enter jobs using the format:

```

ID:profit:deadline

```

Example:

```

J1:100:2, J2:19:1, J3:27:2, J4:25:1, J5:15:3

```

3. Click **Build Steps**.
4. Use **Step** or **Play** to watch the algorithm execute.

---

## Technologies

- HTML
- CSS
- JavaScript
- SVG (for visualization)

---

## Algorithm Complexity

| Case | Time Complexity |
|-----|----------------|
| Best | O(n log n) |
| Worst | O(n log n + n²) |
| Average | O(n log n + n²) |

Space Complexity: **O(n)**

---

## Purpose

This project was created as an educational tool to help understand:

- Greedy algorithms
- Job scheduling problems
- Algorithm visualization
- Time complexity analysis

---

## License

This project is available under the **MIT License**.
```
