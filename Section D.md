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

I would have a look at the student's code to review whether they have correctly assigned the user input to a string variable, and that they have called the method correctly. In this example, it is important to note and point out to the student that the method should be JOptionPane.showInputDialog() and not JOptionPane.ShowDialog(). The input should then be assigned to a string variable as follows:

````
 String Name = JOptionPane.showInputDialog("What is your name?")
````
Once this has been fixed, we then need to have a look if this has fixed the issue of their do-while loop running infinitely.
If not, we will go through the loop together, examining the conditional and break statements. We can look at the logic of the loop and use an example to see if, with any given input to the loop, it will correctly handle this input.

One way to do this is through constructing a flow chart of the loop to understand its structure:

![image](https://github.com/TarynNicole/HyperionDev-_Coding_Mentor_Take_Home_Test/assets/70257895/65c58bbc-e6b8-4f48-b0c2-816a5e9caf5e)








