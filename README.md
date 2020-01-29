
# E02a-Control-Structures


Edit README.md to answer the following questions:

- Open main01.py. Before running it, what do you expect this program to do?
      I expect it will first type "greetings" then ask the user what its favorite color it.
  - Now right click on the main1.py window and select “Run Python File in 
  Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
      Upon trying to guess it's favorite color, it did not provide any yes or no answer.
  - What do you think the program did with what you typed in answer to the question?
      It did not seem to do anything with my answer.

- Open main02.py. Before running it, describe how this is different than main01.py.
      This prompt has an input associated with the color you type in.
  - What do you think the color = input() will do?
      The color will be whatever the user inputs for the question.
  - Run the program in the terminal and answer the question. Did the program do what you expected?
      Yes; the program used the user input color as it's "favorite" color.

- Open main03.py. Before running it, describe how this is different than main02.py.
      This program contains "if/else" statements based on the user inputs.
  - What is happening on lines 9–12?
      It is saying that if the user inputs "red", it will affirm it is its favorite color. Otherwise ('else'), it will say it is incorrect.
  - Why are lines 10 and 12 indented?
      It indicates that the print statements "belong" to either the if or else parameters.
  - Run the program and answer the question. What happens if you don’t capitalize Red?
      It counts the answer as 'incorrect'.
  - What does this tell you about "color"?
      It means that 'red' and 'Red' are considered two separate strings; they are not interchangeable.

- Open main04.py. Before running it, describe how this is different than main03.py.
      In this program, it establishes that 'red' and 'Red' are the same input.
  - What problem is this trying to solve?
      It ensures that the lowercase and uppercase input of 'red' would be acceptable correct answers.
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
      It would not be considered a correct answer.

- Open main05.py. What do you expect line 9 to do?
      It would allow the lowercase input 'red' to be a correct answer, along with 'Red'.
  - What problem is it trying to solve?
      As with the previous code, it ensures that the lowercase input of 'Red' would also be an acceptable answer.
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
      These would be considered incorrect answers.

 - Open main06.py. How is line 9 different than in main05.py?
      It includes the .strip() function after the .lower() function
   - What would you guess .strip() is doing?
      I would expect it is included to ensure space before and after the input does not affect the answer.
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
      The only ways I found that would produce an incorrect answer would be reducing the input to 'r' or adding extra letters, or spelling the word wrong in general.

 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
      I expect it will operate similarly, but with some added dialogue in the case of inputing alternate answers.
   - What is happening on line 12?
      the elif function (or "else if") allows a hint to the program's favorite answer. By including this, if the user to happes to input the color 'pink', it would let the user know they are close to the intended answer, since pink is derived from red.
   - Run the program and answer the question.

 - Open main08.py. What is the purpose of line 9?
      It ensures that as long as the user does not type in the correct answer, it will loop the dialogue and keep asking until the right answer is given. 
   - Why are lines 10–17 indented?
      It indicates that the indented operators are going to act as the loop under the conditions of the ! operator.
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
      It would no longer indicate a right or wrong answer, nor would it loop again until the user gets it right.
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)

 - Open main09.py. What is happening on line 13?
      It adds a counting operator to record the number of loops.
   - What is the purpose of “count”?
      It is to count the amount of loops the user goes through.
   - What is happening on line 22?
      This dialogue will appear with the number of attempts the user tried before getting the correct answer.
   - Run the program.
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  
Commit your changes and push them back to the repository.
 

---

Instructions for forking this repository:
 
Log into your account on [github.com](https://github.com)

Go to the [exercise template page](https://github.com/BL-MSCH-C220-S20/E02a-Control-Structures) on GitHub

There is a button in the top right corner of the page labeled "Fork". Press that now

This will create an independent copy of this repository in your account that you can control and edit

Go to your GitHub home page, and select the new E02a-Control-Structures repository

On that page, you will see a green button labeled "Clone or download". Press that now. You will see a drop down box. Press the "Open in Desktop" button.

This should launch GitHub Desktop. It will ask you for a location (on your computer) where the repository may be cloned (downloaded). Choose a location that will be easy for you to find, and press the blue "Clone" button.

Once GitHub Desktop has cloned (downloaded) the code, it will be responsible for keeping the code on your local computer synchronized with the repository in your GitHub account. Now, open Visual Studio Code, and choose File->Open. Find the folder of the cloned repository and select Open.

In the left (File Explorer) panel, you should see a list of files that comprise this repository

First, edit the file called LICENSE. Replace year and name with the current year and your name. Save this file

Then open README.md. Feel free to remove any extraneous information, and then answer the questions posed in the file. You can add your answers after each question

When the time comes for you to run any of the python files, you can do so by clicking the green arrow in the top right corner of the window or by right-clicking on the code and selecting "Run Python File in Terminal". The results will appear at the bottom. If you don't see "Run Python File in Terminal" in the contextual menu, that is because VS Code doesn't have the Python extension installed. You can do that here: [https://marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

When you are done editing the files, return to GitHub Desktop. In the left panel, you should see a list of the files that have changed

At the bottom of the leftmost area, you should see a text box labeled "Summary (required)". Add a message that describes what you have done; these messages are typically stated in the active-present tense. For example, "Updates the LICENSE, README.md, and completes the assignment." Push the blue "Commit to master" button

In the top bar of the window, you should see a button that is labeled "Push origin", push that now

Check out your page on GitHub. You should see the changes you made reflected there, Repeat steps 10 through 16 as necessary

When you are satisfied with your efforts, turn in a URL to your repository on Canvas

---
If you try to push your changes, and you receive a permission error, it is likely that you are trying to edit the BL-MSCH-C220-S20 copy of the repository rather than your own. Make sure you don't skip the step of forking your own copy and cloning that.

---

The grading criteria will be as follows:
 
[1 point] Repository contains a description of the project in README.md

1 point will be awarded for answering the questions associated with each of the files

10 points total (+2 points extra credit)
