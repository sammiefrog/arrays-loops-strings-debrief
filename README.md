# ArraysLoopsStrings
Lesson on Java Arrays, ArrayLists, Loops, Strings
## Directions to Clone and load in IntelliJ

- Go to the [Repo](https://github.com/ocskier/arrays-loops-strings-debrief.git) and copy the HTTPS URL from the "Code" button
- Open your terminal (Git bash) and navigate to the appropriate location where you wish to save the folder to and run 
```bash 
git clone URL-you-Copied-goes-here
```

- Open IntelliJ and click on new project
- Select Java and make sure you have a Project SDK selected and then click next
  - Leave the box for create project from template unchecked and click next
- Click on three dots ... next to project location. Change project location to the directory you just cloned to your machine. Click OK and then click Finish.

- `MSGrades` will be the entry point for your application.
- Click on the `MSGrades` java file and read thru the comments.

<br><br><br><br>
*** Make all your instance fields private and all your classes and methods public 

Your BankAccount class should have an instance field of type double with the name checkingBalance. Set the value equal to 0.00.

Your BankAccount class should have an instance field of type double with the name savingsBalance. Set the value equal to 0.00.

Your BankAccount class should have an instance field of type double with the name checkingOpeningDeposit. Do not assign a value here. We will do so in the Constructor. This instance field should be declared as final.

Your BankAccount class should have an instance field of type double with the name savingsOpeningDeposit. Do not assign a value here. We will do so in the Constructor. This instance field should be declared as final.

Create a Constructor which takes in the following parameters (double checkingOpeningDeposit, double savingsOpeningDeposit) and assign the instance fields checkingOpeningDeposit and savingsOpeningDeposit to these values. (If you make the parameter name the same name as the instance field you will need to use the "this" keyword.

Within the Constructor, make the checkingBalance equal to the sum of checkingBalance + checkingInitialDeposit. Do the same for the savingsBalance.
Create methods which will print out the balance of the checkingAccount and the savingsAccount. Call these methods getCheckingBalance() and getSavingsBalance() respectively. The return type for these methods should be double and they shouldn't take in any parameters.

*** Test your methods. Over in your BankApp Class create an instance of your BankAccount 

*** Test your methods. Over in your BankApp Class call your withdrawal methods on customerAcct and then use your getBalance() methods to see your new balance

*** Test your methods. Over in your BankApp Class call your withdrawal methods on 

*** Test your methods. Over in your BankApp Class call your deposit methods on both the checking account and the savings account and view the results. 

- Push your changes up to your repository. From your git bash terminal, enter the following commands:
```bash
git add .
git commit -m “Adds solutions to activity”
git push -u origin main
```
- Go to your GitHub repository. You should see your changes.
<br>
*** If you finish early, consider adding some additional functionality. Be original, add some of your own functionality to the application.

