Link to repo for this coding challenge is: https://github.com/TarynNicole/ISBN-Checking-and-Validation

I chose Option 4 in Section C and used the Python Programming language.

Instructions on how to run the program are provided in the README of the above repo. Alternatively, you can also click on the link in the README to go to the deployed application in Streamlit to test it there.

The program was tested with the following:
## Entering a valid ISBN-13 number:
![image](https://github.com/TarynNicole/ISBN-Checking-and-Validation/assets/70257895/41c33d19-bae6-4c35-b24d-1f2b91f3851c)


## Entering an invalid ISBN-10 number:
![image](https://github.com/TarynNicole/ISBN-Checking-and-Validation/assets/70257895/0106d0b6-e0fd-4b08-a0c7-db86e4fb61e5)

## Entering a valid ISBN-10 number
![image](https://github.com/TarynNicole/ISBN-Checking-and-Validation/assets/70257895/b96f76ca-4750-4dc9-99fe-8c51e518b350)

# Worst Case Space Complexity:

The space complexity depends on the length of the input ISBN number. In the worst-case scenario it will be O(n). This is because when the input is an ISBN-10 that needs to be converted to ISBN-13, additional space is required for the original ISBN string, the converted ISBN string, and intermediate variables. 

In the best-case scenario, when the input is a valid ISBN without the need for conversion, the additional space required is minimal, and the space complexity will be O(1)
