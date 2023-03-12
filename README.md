#Run The Program.
- Try To log in with random username or password.
- You will get a error message asking you to sign up.
- Sign up with username and password (this time remember them :))
- Restart the kernel (This is important step to be done to test for now, bug will be fixed soon...)
- Run the program again.
- Login with your username and password
- You will get a welcome message, saying welcome username, password.
______________________________________________________________________________________
#simple_signupForm_with_python

- Q10 Write a Python program to build a sign_Up and login forms for users.
- Your program should validate/authenticate entered credentials for existing users or create new accounts for new users
1- Create "Credentials.txt" file
2- Add the following information into your Credentials.txt file <Name, Password>
     - Sarah,12ssr#
     - Lisa,pass
     - Donna,D00N
3- Create login function that takes two inputs (name,password)
      3.1 Ask the user to enter their username and password
      3.2 search if the names exist in the Credentials.txt file
      3.2.1 if the name was found, check if the password is correct
      3.2.2 return "Welcome <persons name> if the name and password were corre
      3.2.3 else return "wrong name or password"
      3.2 if the name doesn't exist return "your name doesn't exist, please create
      4 Create sign_Up function that takes two inputs(newName,newPassword)
      Ask user to enter their name and password
      append the new information into the Credentials.txt file, follow the same fo
      5 Test your program by logging in using the new account
