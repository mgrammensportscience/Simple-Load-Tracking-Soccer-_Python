# Simple-Load-Tracking-Soccer-_Python
This is a simple and easy to follow Python code for coaches who do not have access to GPS systems and they still want to track their players load

This project calculates **weekly training load** for a soccer squad using **sRPE × duration**.

## Features
- Input: training data (CSV with Player, Date, Duration_min, sRPE)
- Calculates:
  - Session load = sRPE × duration
  - Weekly load per player
- Visualization:
  - Grouped bar chart of weekly load per player


## How to Use
1. Clone the repo
2. Install requirements:
   ```bash
   pip install pandas matplotlib
