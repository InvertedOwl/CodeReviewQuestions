
# Assignment 4b
## Chessmate - Drawly Patterns
Aim for 15 minutes.

---

## Task 1: Chessmate
### Describe Core Concepts

> **Reviewer Info**
> -  **Context:** Open Design Document
> - **Concepts**: Defaults Values, Multi-file Coding
> - **Ask:** *Did you use AI for this task?*
- What happens when a user does not enter a value when creating the chessboard?
- What happens to the chessboard when the width is different than the height?
- What do the if statements do in the starter code.
  
### Describe Your Solution

- How did you make sure you only use *draw_rectangle* once when drawing tiles?
- How do you calculate the location of each tile?
- How do you alternate the black and white tiles?

### Explain your code
> **Reviewer Info**
> -  **Context:** Open code
> -  **Coach Instruction:** Pick section of design document and ask the student to point to where the section is in the code

<!-- Test student confused about this question -->
- If you were asked to rotate between 3 colors instead of 2, what would need to change in your code to accomplish that?
- Show me how you calculate the width and height of each rectangle.
- Explain how you avoid using global variables in *chessboard\.py*

#### Test Data
| Description  | start_x| start_y| width| height |
|  ---         |  --- |  --- |  --- |  --- |
| Normal       | 50 | 50 | 400 | 300 |
| Half Empty       | 50 | 50 | None | 300 |
| Empty String | 100 | 100 | None | None    |
  
---

## Task 2: Drawly Patterns
### Describe Core Concepts
> **Reviewer Info**
> -  **Context:** Open Design Document
> - **Concepts**: For loops, Multi-file Coding
> - **Ask:** *Did you use AI for this task?*
- List the 3 modes and what each mode does.
	- How does the user select each mode?
- For the rectangle and circle patterns, what does the offset parameter do?
- What user input could break your code?

### Describe Your Solution

- How do you use the output of the *get_distance_point* function?
- For the rectangle pattern, how do you determine the rotation of each rectangle.
- How do you choose a random color for each shape?

### Explain your code

> **Reviewer Info**
> -  **Context:** Open code
> -  **Coach Instruction:** Pick section of design document and ask the student to point to where the section is in the code
<!-- good quesiton! -->
- What does the program do if the Count is set to *0*
<!-- Duplicate question -->
- For the rectangle pattern, how is the rotation parameter used?
- How do you make sure the Super Pattern shows on screen?

#### Test Data
| Description  | Center X | Center Y| Offset| Height | Width | Count | Rotation |
|  ---         |  --- |  --- |  --- | --- | --- | --- | --- |
| Rectangle    | 300  | 300 | 100 | 40 | 20 | 50 | 45 |
| Super pattern|  |  |  |  |  | 10 |  |
  