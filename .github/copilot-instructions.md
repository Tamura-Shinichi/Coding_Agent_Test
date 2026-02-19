# Copilot Instructions for Coding_Agent_Test Repository

## Repository Overview
This repository is designed for testing GitHub Copilot Coding Agent with Python examples, specifically focusing on nested loops and control flow demonstrations.

## Code Style and Standards

### Python
- Follow PEP 8 style guidelines
- Use descriptive variable names
- Include docstrings for modules, classes, and functions
- Keep code simple and readable
- Add comments in Japanese or English as appropriate for this bilingual repository

### File Organization
- Python scripts should be placed in the root directory
- Documentation files should be clear and bilingual (Japanese/English) when possible
- Test files should have descriptive names

## Development Guidelines

### When Adding New Code
1. **Nested Loops**: When adding nested loop examples, ensure they are well-commented and demonstrate clear use cases
2. **Control Flow**: For break/continue examples, add comments explaining the logic
3. **Output**: Always include print statements to demonstrate the behavior of the code
4. **Docstrings**: Start each Python file with a module-level docstring explaining its purpose

### Testing and Validation
- Test all Python scripts by running them with `python3 <filename>.py`
- Verify output matches expected results
- Ensure code runs without errors on Python 3.x

### Documentation
- Update README.md when adding new files or features
- Keep bilingual documentation (Japanese and English)
- Include usage examples in the README

## Project-Specific Context

### Current Features
- **nested_loops.py**: Basic nested loop example demonstrating iteration over two lists

### Planned Features
According to the README:
- Changing the number of loops
- Adding control flow with break/continue
- Creating multiplication tables (九九)

## Common Tasks

### Adding New Loop Examples
When adding new nested loop examples:
```python
"""
Brief description of what this example demonstrates.
"""

# Clear descriptive comment
list1 = [...]
list2 = [...]

print("=== Example Name ===")
for i in list1:
    for j in list2:
        # Logic here
        print(i, j)
```

### Adding Control Flow Examples
For break/continue demonstrations:
- Add clear comments explaining when and why the loop breaks or continues
- Show before and after behavior
- Include descriptive print statements

## Notes for Copilot
- This is a testing repository, so prioritize clarity and educational value over performance
- Code examples should be self-contained and easy to understand
- When making changes, consider both Japanese and English speakers who may read the code
- Keep modifications minimal and focused on the specific task at hand
