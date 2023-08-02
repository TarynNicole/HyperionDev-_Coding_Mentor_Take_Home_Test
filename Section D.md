<h1> Option 2: Java Support Task </h1>

<h2> Scenario </h2>

> In this task, we will simulate a typical interaction that you might have with
a student during a mentor support call.
> The student asks you the following question:
> "I am trying to do Task 6 and the JOptionPane.ShowDialog() does not work.
> For some reason it does not store the input to the string variable it is
> assigned to, so my do-while loop ends up in an infinite loop. Can you please help me?"
> Please describe the process that you would follow to help the student.


<h2> Answer: </h2>

I would have a look at the student's code to review whether they have correctly assigned the user input to a string variable, and that they have called the method correctly. This can be done by looking at whether there are any error messages or exceptions being thrown during the execution of the program, as this might offer valuable insights into what's going wrong. I can then ask the student if they understand these error messages, and if not, explain it to them. In this example, I will point out to the student that the method should be ```` JOptionPane.showInputDialog() ```` and not ```` JOptionPane.ShowDialog() ````. The input should then be assigned to a string variable as follows:

````
 String Name = JOptionPane.showInputDialog("What is your name?")
````
Once this has been fixed, we then need to have a look if this has fixed the issue of their do-while loop running infinitely.
If not, we will go through the loop together, examining the conditional and break statements. We can look at the logic of the loop and use an example to see if, with any given input to the loop, it will correctly handle this input.

One way to do this is through constructing a flow chart of the loop to understand its structure, and going through the flow chart with an example input to ensure that the input is processed correctly. This also helps to see whether the student understands coding/loop logic. An example of a flow chart can be seen below:

![image](https://github.com/TarynNicole/HyperionDev-_Coding_Mentor_Take_Home_Test/assets/70257895/65c58bbc-e6b8-4f48-b0c2-816a5e9caf5e)

Using this, we can debug the loop and fix the code to ensure that it runs correctly.
Once the code has been corrected, I will go through the logic of the code, and ensure that the student understands why the code was not working correctly in the first place, as well as understand the fixes made to the code.

<h1> Option 3: Student Feedback </h1>

<h2> Scenario: </h2>
Handling student concerns is an important part of the mentorship role. In the following scenario, you have provided feedback to a student in a
code review for one of their submissions. After reading the feedback, the
student responds in an irate manner claiming that you have provided
feedback that does not provide any value, is generic and seems like you
copy-pasted feedback just to complete the review. You did in fact provide
non-generic, personalised and actionable feedback. On top of this, the
student has also made a complaint on social media about the poor quality
of your review. Please explain how you would handle this situation.

<h2> Answer: </h2>

I will start by going through the feedback I provided the student, and the comments made by the student regarding the feedback. I will in this manner investigate which parts of my feedback may have led them to feel this way. I will also request to meet with the student so they may provide me with their input as to what part of my feedback seemed generic and why they felt it did not provide them with any value. This will also assist me in improving the way I review and provide learners with feedback.
Once this is understood, I will go through my feedback with them verbally and explain what I meant by the various points made, and demonstrate that it was indeed personalised and actionable by showing how these points made relate to the code they submitted for review. I will apologize that the feedback came off that way and ensure that by the end of the meeting, we are both satisfied with the feedback I provided. Once the student is happy with my feedback, I will request that they delete the complaint off social media, as it does give a bad portrayal of me as a mentor, as well as HyperionDev. If they do not do this, I will reply to the complaint apologizing for the way they felt about the initial feedback, and thank them for meeting with me to discuss why they felt this way and allowing me to go through the feedback with them to ensure we are both now happy with it.
I will also let them know to not hesitate to contact me if any feedback I provide them in future does not make sense or if they feel it is not applicable or does not add any value to them.







