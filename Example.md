
# Assignment 4b
## Chessmate - Drawly Patterns
<!-- TODO: Set to accurate values/reevaluate -->
*Task 1:* **6** questions Total<br>
*Task 2:* **6** questions Total

---


# Task 1: Chessmate
## Describe Core Concepts

> **Reviewer Info**
> - **Concepts**: Defaults Values, For loops, Multi-file Coding
> - **Required:** Ask **2** Questions
> - **Ask:** *Did you use AI for this task?*
- What is empty string defaulting used for. 
- What happens to the chessboard when the width is different than the height?
- What do the if statements do in the starter code.
  
## Describe Your Solution

> **Reviewer Info**
> -  **Context:** Open Design Document
> -  **Required:** Ask **2** Questions

- How did you make sure you only use *draw_rectangle* once when drawing tiles?
- What paramaters are updated between each call to *draw_rectangle* to draw the tiles?
	- How do you calculate the parameters?
- How do you aternate the black and white tiles?
- How do you set the stroke and fill in *draw_rectangle*?

## Explain your code

> **Reviewer Info**
> -  **Context:** Open code
> -  **Required:** Ask **2** Questions
> -  **Coach Instruction:** Pick section of design document and ask the student to point to where the section is in the code

- Show me where you use *add_poly_point*.
- If you were asked to rotate between 3 colors instead of 2, what would need to change in your code to accomplish that?
- Show me how you calculate the width and height of each rectangle.
- Explain how you avoid using global variables in *chessboard\.py*


#### Test Data
| Description  | start_x| start_y| width| height |
|  ---         |  --- |  --- |  --- |  --- |
| Normal       | 50 | 50 | 400 | 300 |
| Empty String | 100 | 100 | " " | " "    |
  

---

  

# Task 2: Drawly Patterns
## Describe Core Concepts
> **Reviewer Info**
> - **Concepts**: For loops, Multi-file Coding
> - **Required:** Ask **2** Questions
> - **Ask:** *Did you use AI for this task?*
- List the 3 modes and what each mode does.
	- How does the user select each mode?
- For the rectangle and circle patterns, what does the offset parameter do?
- What user input could break your code?


  

## Describe Your Solution

> **Reviewer Info**
> -  **Context:** Open Design Document
> -  **Required:** Ask **2** Questions
- What should *get_distance_point* do?
	- How do you use the output of *get_distance_point*?
- Explain how *task2\.py* chooses which pattern function to call.
- For the rectangle pattern, how do you determine the rotation of each rectangle.
- For the circle pattern, how do you determine where each circle is centered?
- For the super pattern, how do you randomize whether you draw a circle or rectangle pattern
- What does *set_random_color* do?
	- How do you use *set_random_color*?

## Explain your code

> **Reviewer Info**
> -  **Context:** Open code
> -  **Required:** Ask **2** Questions
> -  **Coach Instruction:** Pick section of design document and ask the student to point to where the section is in the code
- What does the program do if the Count is set to *0*
- Show me where you use the offset parameter.
- For the rectangle pattern, where is the rotation parameter used?
- Show me where *set_random_color* is used.
- For the Super Pattern, how do you randomize the parameters for the patterns
	- How do you make sure the pattern shows on screen?

#### Test Data
| Description  | Center X | Center Y| Offset| Height | Width | Count | Rotation |
|  ---         |  --- |  --- |  --- | --- | --- | --- | --- |
| Rectangle    | 300  | 300 | 100 | 40 | 20 | 50 | 45 |
| Super pattern|  |  |  |  |  | 10 |  |
  