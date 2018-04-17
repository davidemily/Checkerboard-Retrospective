# Daeth5 Checkerboard-Retrospective
I'll be comparing my old Checkerboard solution with the official solution in the hope of becoming a better programmer.

#### Reflect on the work you did for the challenge. How did you do? What did you get right? What did you get wrong? What did you do differently than what was posted in the solution? What was hard to do?
--- 
The code for the checkerboard was difficult for me. I spent a year away from programming in OO and from the Java FXML environment. While picking up the syntax of Java wasn't too hard, relearning the details of inheritance and interfaces was.

For the most part, my code matched that of the solution. There were some small changes in the methods of the Checkerboard and Controller class. 

Solution Checkerboard: ![alt text](https://github.com/davidemily/Checkerboard-Retrospective/blob/master/daleCheckerboard.PNG)

And then my checkerboard: ![alt text](https://github.com/davidemily/Checkerboard-Retrospective/blob/master/davidCheckerboard.PNG)

Very similar except for the slight changes in where the size of the pane is calculated.

The hardest part of the project for me, was finding out how to do the calculations on the changing pane size due to the user dragging the pane. I also had some issues that when the number of rectangles changed, the title bar would be covered up. After figuring out a solution to these, the rest of the time was spent coding in the logic for the colors.

#### How well did you understand the programming concepts and foundational knowledge needed to complete the challenge?
--- 
I was rusty at FXML and Java at the beginning of the assignment which made this difficult. Sitting down and working out the solution through trial and error definitely helped. The concepts of how to do it didn't seem too difficult, it was just implementing the solution into code that caused me grief.

#### How well did you meet the requirements as set out in the challenge? What requirements did you not meet correctly?
--- 
I met all of the requirements in the challenge. The animation of my board during a size change does not match the way the solution looks but still meets the requirements.

#### How well does your solution match the posted solution? What is different?
--- 
My solution is very similar to the posted solution. While the main parts of the skeleton were the same, I handled calculations in different methods than the posted solution did. For example:
Solution: ![alt text](https://github.com/davidemily/Checkerboard-Retrospective/blob/master/daleSelectSize.PNG)

vs

My checkerboard: ![alt text](https://github.com/davidemily/Checkerboard-Retrospective/blob/master/davidSelectSize.PNG)
The original solution is much cleaner and efficient than the solution I went with. In the solution the information was passed to the renderBoard() method where I handled in the calculation inside the method. Ideally I would have modulated this more like the posted solution.
#### How could you improve going foward? What don't you still understand that was required for the challenge?
--- 
I plan on reviewing more the differences between the posted solution and my solution. I need to focus more on separating my code and creating methods to handle the calculations. I also need to do more OO programming as I sometimes felt I was lost while programming a project like this. While I had the idea in my head, I didn't quite know how to implement in it in Java or use OO principles.
