# Artificial Intelligence — Lab Task 1

## Overview
This project contains three tasks related to the history and basic applications of Artificial Intelligence (AI).

## Task 1: Historical Timeline of AI
A chronological timeline of important AI milestones, including:
- **1950:** Alan Turing proposes the imitation game.
- **1956:** The Dartmouth Summer Research Project helps establish AI as a research field.
- **1974–1980:** An AI winter occurs, with reduced funding and enthusiasm.
- **1997:** IBM Deep Blue defeats world chess champion Garry Kasparov.
- **2012:** AlexNet advances image recognition using a large dataset and GPU computation.
- **2017:** The Transformer architecture is introduced.

Sources are included in the lab report for each milestone.

## Task 2: Rule-Based Scholarship Eligibility System
A Python function checks whether a student meets the example scholarship requirements.

### Rules
- Academic score must be at least **70**.
- Required documents must be complete.
- Attendance must be at least **75%**.
- Fee clearance must be confirmed.

The program returns `Eligible` only when all four conditions are satisfied; otherwise, it returns `Not Eligible`.

**Note:** These rules and thresholds are practice assumptions, not an actual scholarship policy.

### Test cases
1. **Pass:** All conditions are satisfied.
2. **Attendance failure:** Attendance is below 75%.
3. **Fee-clearance failure:** Fee clearance is not confirmed.
4. **Boundary test:** Score is exactly 70 and attendance is exactly 75%; both values pass because the rules use `>=`.

## Task 3: Conversational Test vs. General Intelligence
This task explains why a convincing conversation does not prove general intelligence. An AI may explain scholarship rules fluently but still make an incorrect decision if it ignores a requirement.

A structured rule-checking test is suggested: compare program outputs with independently prepared expected results, including boundary cases and cases where one condition fails.

## Files
- `AI-Lab task 1.docx` — Main lab report.
- `AI-Lab task 1.docx 1.1.docx` — Additional task explanation.
- `Task_1.ipynb` — Jupyter Notebook for the task.

## How to Run
1. Open `Task_1.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Run the notebook cells in order.
3. Review the printed results and compare them with the expected outcomes in the report.

The scholarship example uses basic Python and does not require external packages for the function shown in the report.
