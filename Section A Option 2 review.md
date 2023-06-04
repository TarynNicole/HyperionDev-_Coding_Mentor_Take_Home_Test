# Section A:
## Option 2: Java Task

### Instructions given:

"In a file called recursion.java, create:

recursive function that reverses a string

a recursive function that, given a number n, prints out the first n Fibonacci numbers (Fibonacci numbers are a sequence where each number is the sum of the previous two - 0 1 1 2 3 5 8...)"

### Solution provided by student:

```javascript
public class recursion {
 
	public static void main(String[] args) {
 
		// Saves the string that would be reversed
		String myStr = "emosewA si avaJ";
 
 
		//create Method and pass and input parameter string 
		String reversed = reverse_string(myStr);
		System.out.println("The reversed string is: " + reversed + "\nFibonacci Series of 10 numbers:0 1 1 2 3 5 8 13 21 34 ");
	

	}
 
 
	//Method take string parameter and check string is empty or not
	public static String reverse_string(String myStr)
	{
		if (myStr.isEmpty()){
		 System.out.println("String in now Empty");
		 return myStr;
		}
		//Calling Function Recursively
		System.out.println("String to be passed in Recursive Function: "+myStr.substring(1));
		return reverseString(myStr.substring(1)) + myStr.charAt(0);}

	public static <T> void function(T maxNumber) {
		// Set it to the number of elements you want in the Fibonacci Series
		int maxNumber = 10; 
		int previousNumber = 0;
		int nextNumber = 1;
		 
	    System.out.print("Fibonacci Series of "+maxNumber+" numbers:");
 
	for (int i = 1; i <= maxNumber; ++i){
	    System.out.print(previousNumber+" ");
	    // On each iteration, we are assigning second number
	    // to the first number and assigning the sum of last two
	    // numbers to the second number
	    int sum = previousNumber + nextNumber;
	    previousNumber = nextNumber;
	    nextNumber = sum;
	    }
 
	}
 ```
 
 
 ### My Feedback
 
 Hi (name of student)! Thank you so much for your submission!
 
 I have gone through your code and you seem to have the basic knowledge of JavaScript, how to structure your code logically, as well as a good understanding of the use of loops, classes and functions.
 The structure of your code makes sense and follows the logic necessary to complete the tasks required.
 There are however, some areas of your code that require improvement.
 
 Firstly, there are some syntax errors, such as:
 1. The class name should start with an uppercase letter, so it should be Recursion instead of recursion.
 2. You should remove the parameter declaration `<T> maxNumber` as it's not used or needed.
 3. You declare the variable `maxNumber` twice in Function. Remove the declaration of `maxNumber` inside the method since it's already declared as a parameter. This will also allow users to determine the length of the Fibonacci sequence instead of keeping it fixed at printing out only the first 10 digits.
 
 When the change suggested in (3) is done, the function method will look something like this:
 
 ```Javascript
 	public static void function(int maxNumber) {
		int previousNumber = 0;
		int nextNumber = 1;
		 
		System.out.print("Fibonacci Series of "+ maxNumber + " numbers:");
 
		for (int i = 1; i <= maxNumber; ++i) {
			System.out.print(previousNumber + " ");
			// On each iteration, we are assigning the second number
			// to the first number and assigning the sum of the last two
			// numbers to the second number
			int sum = previousNumber + nextNumber;
			previousNumber = nextNumber;
			nextNumber = sum;
		}
    
  ```

In the reverse_string function, the function name on line 18:
`public static String reverse_string(String myStr)`
is different to the function call on line 26:
`return reverseString(myStr.substring(1)) + myStr.charAt(0);}` 

Please fix this by sticking to the same naming convention, either both being `reverse_string` or both being  `reverseString`

The function method is not being called from main. This function method will thus not run to generate the Fibonacci sequence. Please add this method call. An example of how the main method will then look is as follows:

```Javascript
public static void main(String[] args) {
 
		// Saves the string that would be reversed
		String myStr = "emosewA si avaJ";
 
		// create Method and pass an input parameter string 
		String reversed = reverse_string(myStr);
		System.out.println("The reversed string is: " + reversed);
		
		// Print the Fibonacci series
		function(5);
    
   ```
   
  Overall, your code is well structured and demonstrates good knowledge of programming concepts, as well as the ability to structure code in a logical manner. It shows great potential and if you implement the suggested improvements to this code, as well as continue practising, I know you will become a force to be reckoned with in Programming!
  
  Please do not hesistate to contact me if you have any questions regarding my comments and suggestions :)
  
 


 

