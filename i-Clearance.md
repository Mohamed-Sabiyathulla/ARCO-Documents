

# **Clearance**

| [Vacation Clearance](#1-vacation-clearance) | [End of Service Clearance](#2-end-of-service-clearance) | [Customer Clearance](#3-customer-clearance) |

<br>



### **Mandatory field to update while request for Clearance:**

 **1- Employee ID,**

 - Unique Identification number provided by organization to employee.

 **2- From Date,**

 - From Date is Arrival date of Employee to Organization.

 **3- To Date,**

 - Completion of service or Relieving Date of service from Organization

 **4- Total Salary,**

  - Details of Employee monthly salary

  **5- Contract Number,**

  - This Contract Number Issued by KSA to Employee, and it will renew once in two year.

 **5-Clerance Type,**

- **_Vacation Clearance,_**

     - This Clearance is process on Vacation Settlement for Employee by Organization.

  - **_End Of Service Clearance,_**

     - This clearance is process on End of Service for Employee Final Settlement by Organization,

  - **_Customer Clearance,_**

     -  Clearance is process for End Contract Clearance from customer.

  - **_Clearance Calculation,_**

     - Clearance Calculation on Vacation Settlement and Retirement Final Settlement.

  - **_Customer Clearance,_**

     - This clearance process get clearance from Customer for Employee.

<br>

### Clearance process:

 - User can enable or disable any component by checkbox action in each component.

 - Sum of all component amount will clearance amount except customer charges.

 - New Clearance request will create in **"Clearance calculation" ** stage for _"Vacation Clearance"_, _"EOS Clearance"_ and _"Customer Clearance"_ from Case and Task Management.


 - Then it will moved to New stage.

| [Home](#clearance) |


### Clearance process Calculation:


*	Employee Final Settlement amount is calculated with approximated Kingdom days of Employee.

* And this Final settlement amount calculation is differs as per Working category,

   * 	*(i)* Employee working Type is two category:-
  
          [ _Individual Employee | Business Employee_ ]

         * Settlement will calculate as sum of - (Kingdom days EOS Profile Percentage % Monthly Salary)

         *(A)*. _Individual Employee_:

         Employee who work for individual customer

         * Termination in below 4 Years - Settlement is not applicable for below 4 years.

         * Termination in between 4 to 5 years - 25 percentage of montly salary for every 1 year.

         * Termination above 5 years - 25 percentage of montly salary for every 1 year.



        *(B)*. _Business Employee_:

         * Below 5 years - 50 percentage of monthly salary for every 1 year.

         * Above 5 years - 100 percentage of monthly salary for every 1 year.



     * *(ii)*	Employee work or contract period - Number of Years worked.


<br>

### **1-Vacation Clearance:**


 - ### **New**

   In this stage, user update the clearance in each component.

   New request created in Case and Task Management, and then it will moved to **"New"** for update the clearance components to process the clearance for the settlement.

   - ### **Vacation Settlement:**

       In this stage, User process the calculation on Vacation settlement.

     - Vacation Eligible Days will calculate based on Kingdom days till Last Working Date.

     - Vacation Eligible days will calculate as ((Kingdom days*Yearlyvacation/365)-PrevVacationDays).

     - User will enter the Vacation days by manually.

     - Vacation Amount will Calculate based on per days salary.

   - ### **Employee Salary(Due Salary):**

      In this stage, User process the calculation on pending Employee salary like Un paid and Due.

     - Due or Un Paid salary will show as list in this component.

     - Sum of Sue Salary amount will show in Amount field

   - ### **Employee Loans(Due Loans):**

      In this stage, User process the calculation on pending Employee loans,and Deduction.

     - Due or Un Paid loan will show as list in this component.

     - Sum of Due Loan amount will show in Amount field.

     - Due Loan will deduct the Total Clearance Amount.

   - ### **Government Fees:**

      In this stage, User process the calculation on Government fees is paid by ARCO, as expenses list.

     - It will calculate from the Expense list and Expense Period for remaining Iqama Expiry Days.

     - Govt fee will calculate as sum of (Expense AMount/Expense Period days)*Remaning Iqama Days.

     - Amount will deduct from the Total Clearance Amount.

   - ### **Ticket:**

       In this stage, User process the calculation on Travel Ticket.

     - User will enter ticket amount manually.

     - Amount will deduct from the Total Clearance Amount.

   - ### **Other Payment:**

      In this stage, User process the calculation on Other payments is paid by Arco, list to deduct from the Settlement.

     - User will enter Other Payment amount manually

   - ### **Other Deduction:**

       In this stage, User process the calculation on Other Deduction like not listed in this Components.

     - User will enter Other Payment amount manually

   - ### **New Salary:**

      In this stage, User process the calculation on Salary, as pending days on remaining month which is not generated for salary.

     - System will calculate Not generated salary till Last working day.

     - Total Not Generate salary will show in Amount.

   - ### **Customer Vacation Charges:**

       In this stage, User process the calculation on charges for vacation from customer.

     - **System will calculate Vacation days for Last Working Contract days of employee.**
     
     - Vacation Eligible days will calculate as ((Last Working Contract days*Yearlyvacation/365)-PrevVacationDays).

     - User will enter the Vacation days by manually.

     - Vacation Amount will Calculate based on per day salary.

     - **(This charges for Customer will not update clearance amount.)**

   - ### **Customer Other Charges:**

     In this stage, User process the calculation on other charges from customer. is not listed in clearance.

     - User will enter Other Charges amount manually.

     - This charges for Customer will not update clearance amount.


    And then it moved to Approved stage in Case and Task Management.

 - ### **Approved**



   - Once Clearance Approved, Clearance Amount and enabled Component Lines details updated to Vacation settlement.

   - In Settlement process, stage will moved clearance process to Approval stage.

   - And This Action will impact on finance transaction by following,

       - Due Salary

          If employee have due salary , salary status will update as "Settlement requested".


- **When Payment Completes in Settlement:-**

     - Clearance will move to Approval to Closed stage..

<br>

- **This movement will impact finance transaction following:-**

    - Due Salary:

      - If employee have due salary , salary status will update as **"PaidBySettlement"**.

    - Due Loan:

      - If employee have due loan , loan will settled by clearance.

    - New Salary:

      - New salary will generate and salary status updated as **"PaidBySettlement"**.

    - Customer Charges and Other Charges:

       - System will call finance to create Non Monthly Invoice to the customer.

| [Home](#clearance) | [Back](#1-vacation-clearance) |

<br>


### **2-End of Service Clearance:**


 - ### **New:**
 
   In this stage, user create and update the clearance in each component as below.

      - ### **EOS Settlement:**

        - EOS Settlement will calculate from Kingdom days(Employee Arrival day to last working day).

        - Settlement will calculate based on EOS Profile setup by kingdom days.

        - Settlement will calculate as sum of (Kingdom days EOS Profile Percentage % Monthly Salary).


   - ### **Vacation Settlement:**

     - Vacation Eligible Days will calculate based on Kingdom days till Last Working Date.

     - Vacation Eligible days will calculate as ((Kingdom days*Yearlyvacation/365)-PrevVacationDays).

     - User will enter the Vacation days by manually

     - Vacation Amount will Calculate based on per days salary.

   - ### **Employee Salary(Due Salary):**

     - Due or Un Paid salary will show as list in this component.

     - Sum of Sue Salary amount will show in Amount field

   - ### **Employee Loans(Due Loans):**

     - Due or Un Paid loan will show as list in this component.

     - Sum of Due Loan amount will show in Amount field.

     - Due Loan will deduct the Total Clearance Amount.

   - ### **Food:**

      - Food Deduction is applied only for Individual EMployees.

      - It will calculate based on Lodging Days by employee.

      - It will calculate as (Lodging Days * MealAMount(from factor)).

      - Amount will deduct from the Total Clearance Amount.

   - ### **Government Fees:**

     - It will calculate from the Expense list and Expense Period for remaining Iqama Expiry Days.

     - Govt fee will calculate as sum of (Expense AMount/Expense Period days)*Remaning Iqama Days.

     - Amount will deduct from the Total Clearance Amount.

   - ### **Ticket:**

     - User will enter ticket amount manually.

     - Amount will deduct from the Total Clearance Amount.

   - ### **Other Payment:**

     - User will enter Other Payment amount manually.

   - ### **Other Deduction:**

     - User will enter Other Payment amount manually.

   - ### **New Salary:**

     - System will calculate Not generated salary till Last working day.

     - Total Not Generate salary will show in Amount.


 - ### **Approved:**

     - Once Clearance Approved, Clearance Amount and enabled Component Lines details updated to Final Settlement.

     - In Settlement process, stage will moved clearance process to Approval stage.


     
- ### **This movement will impact on finance transaction following:-**

    - Due Salary:

      - If employee have due salary , salary status will update as **"PaidBySettlement"**.

    - Due Loan:

      - If employee have due loan , loan will settled by clearance.

    - New Salary:

      - New salary will generate and salary status updated as **"PaidBySettlement"**.

    - Customer Charges and Other Charges:

       - System will call finance to create Non Monthly Invoice to the customer.

| [Home](#clearance) | [Back](#2-end-of-service-clearance) |

<br>



### **3-Customer Clearance:**

Customer clearance is request clearance from customer on Employee Settlement.

 ### **New:**

In this stage, user create and update the clearance in each component as below.

 *  **EOS Settlement:**

      - EOS Settlement will calculate from Kingdom days(Employee Arrival day to last working day).

     - Settlement will calculate based on EOS Profile setup by kingdom days.

     - Settlement will calculate as sum of (Kingdom days Percentage % Monthly Salary).


-  **Vacation settlement:**

     - Vacation Eligible Days will calculate based on Kingdom days till Last Working Date.

     - Vacation Eligible days will calculate as ((Kingdom days*Yearlyvacation/365)-PrevVacationDays).

     - User will enter the Vacation days by manually

     - Vacation Amount will Calculate based on per days salary.

-  **Government Fees:**

     - It will calculate from the Expense list and Expense Period for remaining Iqama Expiry Days.

     - Govt fee will calculate as sum of (Expense AMount/Expense Period days)*Remaning Iqama Days.

     - Government Amount will deduct from the Total Amount of Clearance.


-  **Ticket:**

     - User will enter ticket amount manually for clearance.

     - Travel ticket Amount will deduct from the Total Amount of Clearance.

-  **Contract Penalty:**

     - In this stage, calculate the clearance on Contract Penalty.

-  **Other Payment:**

     - User will enter Other Payment amount manually

-  **Other Deduction:**

     - User will enter Other Deductions amount manually.

### **Approved:**

  - Once Clearance Approved, Clearance Amount and enabled Component Lines details updated to Final Settlement.

  - In Settlement process, stage will moved clearance process to Approval stage.

### Re-Calculate Requested:

  - If the clearance request will return to customer for recalculation, then it will send for **"Credit notes"** from Finance Department.



| [Home](#clearance) | [Back](#3-customer-clearance) |


<br>