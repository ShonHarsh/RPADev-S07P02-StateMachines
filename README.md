![](https://shonharsh.github.io/curriculum-vitae/images/uipath-logo.png)

# S07P02 State Machines

This project is my solution in **C#** to the **State Machines** practice found in section 07 practice 02 of the UiPath - RPA Developer Foundation course.

### Getting Started

After making a pull request or downloading the project, open the Main.xaml in UiPath Studio.  The robot can be run with the play button in the ribbon and the result can be seen in output pane.

#### PRACTICE REQUIREMENTS

###### **The Vending Machine**

Create a workflow that simulates a vending machine. The functionality should be the following:

- The user is asked to choose the initial credit ($5, $10, $20) and to choose if he/she wants to proceed or if they changed their mind and want to get the change;
- If they want to continue: They are asked what drink they want: Coffee ($3) or Tea ($2).

Next, the vending machine should check if the user has enough credit for selected drink. If Yes, display a success message and subtract the price of the drink from the total amount.

The user is then asked if he/she wants to buy another drink or to get the change.

If they want to get the change, a message box is displayed with the value of the change to be given to the customer.

### Details

**Course:** UiPath - RPA Developer Foundation

**Section:** 07 Project Organization

**Practice:** 02 State Machines

**GitHub:** https://github.com/ShonHarsh/RPADev-S07P02-StateMachines

Sample Output

```
09/28/2021 16:37:51 => [Debug] Execution started for project: RPADev-S07P02-StateMachines
09/28/2021 16:37:53 => [Info] RPADev-S07P02-StateMachines execution started
09/28/2021 16:38:08 => [Debug] Dispensing a cold Cheerwine below.
09/28/2021 16:38:13 => [Debug] Dispensing a cold Dr. Pepper below.
09/28/2021 16:38:18 => [Debug] Transaction completed.  Depositing $5 in change [likely pennies].
09/28/2021 16:38:18 => [Info] RPADev-S07P02-StateMachines execution ended in: 00:00:24
```

### Notes

I feel that this project could have had more states that involve the input validation and computation events.  I initially thought of the states as interaction points with the user but realized more states could have been used for the said validations; thus this was a great learning project!

### RPA Developer Foundation Sections

1. Get Started With RPA Development

2. Variables, Data Types And Control Flow In Studio

   P01 [RPADev-S02P01-ForEachIfStatement](https://github.com/ShonHarsh/RPADev-S02P01-ForEachIfStatement)

   P02 [RPADev-S02P02-GenericValue](https://github.com/ShonHarsh/RPADev-S02P02-GenericValue)

   P03 [RPADev-S02P03-Switch](https://github.com/ShonHarsh/RPADev-S02P03-Switch)

3. Data Manipulation In Studio

   P01 [RPADev-S03P01-Lists](https://github.com/ShonHarsh/RPADev-S03P01-Lists)

   P02 [RPADev-S03P03-Dictionaries-Integers](https://github.com/ShonHarsh/RPADev-S03P03-Dictionaries-Integers)

   P03 [RPADev-S03P04-Dictionaries-Doubles](https://github.com/ShonHarsh/RPADev-S03P04-Dictionaries-Doubles)

   P04 [RPADev-S03P05-InputValidation](https://github.com/ShonHarsh/RPADev-S03P05-InputValidation)

   P05 [RPADev-S03P06-ReplacingPlaceholders](https://github.com/ShonHarsh/RPADev-S03P06-ReplacingPlaceholders)

   P06 [RPADev-S03P07-ExtractEmailAddress](https://github.com/ShonHarsh/RPADev-S03P07-ExtractEmailAddress)

   P07 [RPADev-S03P08-ExtractEmailAddressRegEx](https://github.com/ShonHarsh/RPADev-S03P08-ExtractEmailAddressRegEx)

4. Excel And Data Tables With Studio

   P01 [RPADev-S04P01-CalculatingSums](https://github.com/ShonHarsh/RPADev-S04P01-CalculatingSums)

   P02 [RPADev-S04P02-CalculatingLossInvoices](https://github.com/ShonHarsh/RPADev-S04P02-CalculatingLossInvoices)

   P03 [RPADev-S04P03-CalculatingPercentagesOfExpenses](https://github.com/ShonHarsh/RPADev-S04P03-CalculatingPercentagesOfExpenses)

5. UI Automation With Studio

   P01 [RPADev-S05P01-PasswordGenerator](https://github.com/ShonHarsh/RPADev-S05P01-PasswordGenerator)

   P02 [RPADev-S05P02-TheRPAChallenge](https://github.com/ShonHarsh/RPADev-S05P02-TheRPAChallenge)

   P03 [RPADev-S05P03-InputActions](https://github.com/ShonHarsh/RPADev-S05P03-InputActions)

   P04 [RPADev-S05P04-OutputActions](https://github.com/ShonHarsh/RPADev-S05P04-OutputActions)

   P05 [RPADev-S05P05-DataScraping](https://github.com/ShonHarsh/RPADev-S05P05-DataScraping)

6. Selectors In Studio

   P01 [RPADev-S06P01-GetAndSortData](https://github.com/ShonHarsh/RPADev-S06P01-GetAndSortData)

   P02 [RPADev-S06P02-SetData](https://github.com/ShonHarsh/RPADev-S06P02-SetData)

   P03 [RPADev-S06P03-Highlight-TypeItems](https://github.com/ShonHarsh/RPADev-S06P03-Highlight-TypeItems)

7. Project Organization In Studio

   P02 [RPADev-S07P02-StateMachines](https://github.com/ShonHarsh/RPADev-S07P02-StateMachines)

   P03 [RPADev-S07P03-FixMyWorkflow](https://github.com/ShonHarsh/RPADev-S07P03-FixMyWorkflow)

   P04 [RPADev-S07P04-Libraries](https://github.com/ShonHarsh/RPADev-S07P04-Libraries)

8. Error And Exception Handling In Studio

9. Debugging In Studio

10. PDF Automation In Studio

11. Email Automation With Studio

12. Orchestrator For RPA Developers

13. Robotic Enterprise Framework Overview

### Requirements

[UiPath Studio](https://www.uipath.com/product/studio) is required to run the robot.

### Git Notes

Clone the project to develop or change it.

`git clone https://github.com/ShonHarsh/RPADev-S07P02-StateMachines`

### Links

[UiPath: Automation Platform](https://www.uipath.com/)

[UiPath Studio](https://www.uipath.com/product/studio)

[My Website](https://shonharsh.github.io/curriculum-vitae/index.html) - Errors, spelling fixes and comments are very welcome!

