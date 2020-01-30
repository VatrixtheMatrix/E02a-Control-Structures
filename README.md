- Open main01.py. Before running it, what do you expect this program to do?
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
  A: Nothing. it just finishs.

  - What do you think the program did with what you typed in answer to the question?
  A: Nothing. I was given no directions to do anything with any imput.

- Open main02.py. Before running it, describe how this is different than main01.py.
  - What do you think the color = input() will do?
  A:Might make it do something. But I feel it needs more direction than that.

  - Run the program in the terminal and answer the question. Did the program do what you expected?
  A: It just said what I typed.

- Open main03.py. Before running it, describe how this is different than main02.py.
  - What is happening on lines 9–12?
  A: It actually has instructions to do something. If I type "Red" then it says "Correct!" But if it recieves any other imput it says
    "Sorry Try again."

  - Why are lines 10 and 12 indented?
  A: Because they're part of lines 9 and 11 as reposes to those imputs.

  - Run the program and answer the question. What happens if you don’t capitalize Red?
  A: I says "Correct"

  - What does this tell you about "color"?
  A: Says "Sorry, Try again"

- Open main04.py. Before running it, describe how this is different than main03.py.
  - What problem is this trying to solve?
  A: I allow the imput/answer "red" as a correct answer and not just "Red".

  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
  A: It treats the imput as a incorrect answer.

- Open main05.py. What do you expect line 9 to do?
  A: Probably makes it accept any capitalization of "red" as the correct answer.

  - What problem is it trying to solve?
  A: It's trying to make sure that the capitalization doesn't interfere with the player from getting the right answer.

  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
  A: It fails to precieve the answer as correct.

 - Open main06.py. How is line 9 different than in main05.py?
  A: It was converted to a strip.

   - What would you guess .strip() is doing?
   A: Compensating for the possible spaces the player might answer?

   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
   A: Yeah, "-red-". ;)

 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
  A: main07.py has been given an additional command to sat "Close!" when imputed pink.

   - What is happening on line 12?
   A: Its an elif.

   - Run the program and answer the question.
 - Open main08.py. What is the purpose of line 9?
  A: It does something with the answer "red".

   - Why are lines 10–17 indented?
   A: It's all the response to line 9.

   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
   A: The program no longer knows what to do with the answer "red" and just ends.

   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
 - Open main09.py. What is happening on line 13?
  A: it adds 1 to the count
   - What is the purpose of “count”?
   A: The program is basically counting how many times the player guesses until it's correct.

   - What is happening on line 22?
   A: There is no line 22 on main09.py

   - Run the program.
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?