# HackerRank Tasks - AI Coding Agent Instructions

## Project Overview
This repository contains solutions to HackerRank coding challenges, organized by programming language. Currently active: Python solutions.

## Repository Structure
- `Python/` - Python solution files, one per HackerRank challenge
- Each file follows the pattern: `challenge_name.py`

## File Conventions

### Python Files
- **Header format**: Each solution starts with:
  ```python
  #!/bin/python3
  # Task Link:
  # https://www.hackerrank.com/challenges/{challenge-id}/problem
  ```
- **Standard imports**: Files include standard library imports (math, os, random, re, sys) even if not all are used initially
- **Main execution block**: All solutions use `if __name__ == '__main__':` pattern
- **Input/Output**: Solutions read input via `input()` and print results with `print()`
- **Status markers**: Use `# working in progress` comment when the solution is incomplete

## Development Workflow

### When Working on a Challenge
1. Find the HackerRank problem URL
2. Update the Task Link comment with the correct challenge ID
3. Implement the solution using standard input/output patterns
4. Test locally with sample inputs from the problem statement
5. Remove `# working in progress` when complete

### Running Solutions
```bash
python3 Python/challenge_name.py
```

## Key Patterns

### Input/Output Pattern
```python
if __name__ == '__main__':
    # Read input(s)
    s = input()
    # Process solution
    result = process(s)
    # Output result
    print(result)
```

### Problem-Solving Approach
- Solutions should handle the specific constraints mentioned in each HackerRank problem
- Focus on correctness over optimization initially
- Refer to the HackerRank problem statement for exact requirements via the Task Link

## Branch Conventions
- Work on feature branches named after the challenge (e.g., `company_logo_dp`)
- Update related solution files before merging

## Notes for AI Agents
- Each file is a self-contained solution to a single problem
- The repository structure is flat within language folders - don't create nested subdirectories
- Always include the HackerRank problem URL for context when reviewing solutions
