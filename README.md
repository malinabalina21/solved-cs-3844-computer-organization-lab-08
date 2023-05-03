Download Link: https://assignmentchef.com/product/solved-cs-3844-computer-organization-lab-08
<br>
Before doing this lab, make sure to do Lab7 since all of the code is the same. In this case, you will complete FUNC2_Student which also finds the length of a string and stores it in the 2<sup>nd</sup> parameter as before. The difference is that this time, you MUST make use of the string instructions, introduced in Lab #7. Your output should look exactly the same as that from Lab #7.




<ol>

 <li>Write an assembly program that finds the length of string using the string instructions. Put this code inside FUNC2_Student and run the program to make sure it works the same as in Lab #7.</li>

</ol>




<ol start="2">

 <li>Modify your program so that it finds the index of an arbitrary character. A 3<sup>rd</sup> parameter passed in will be a single character and the value put in *par2 is the number of characters before the character X. (Hint: scas).</li>

</ol>




FUNC3_Student( char *par1, int *par2, char X);




For example, if we search string n = “<strong>Exams are fun!</strong>” for ‘!’, the result is 13. I encourage you to trace through your code, try different strings, and different search characters. Pay attention to how the one character value is passed to the stack.




Solutions will be posted in the FUNC2_Solution file.  NOTE: We will call FUNC3 directly and not pass through FUNC0.