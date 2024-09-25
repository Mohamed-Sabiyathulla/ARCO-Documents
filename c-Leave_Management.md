# **Human Resource Management**

| [Employee](#employee) | [On Board](#on-board) | [Leave Management](#leave-management) | [Travel](#travel) | [Employee Retirement](#employee-retirement) | [Loan](#loan) | [Reissue](#reissue) | [Renewal](#renewal) | [Clearance](#clearance) |

<br>


# **[Leave Management](#human-resource-management)**

| [Leave Request](#leave-request) | [Vacation Settlement](#vacation-settlement) | [Vacation Return](#vacation-return) | [Leave Reject Request](#leave-reject-request) |

<br>

## **[Leave Request:](#leave-management)**

The Leave Request is initiated from **Case and Task Management** for Employee by User or Customer.

New request created in Case and Task Management and then it will moved to **ARCO Approval** from **Case and Task management**.




| [ARCO Approval](#arco-approval) > [Customer Approval](#customer-approval) > [Under Processing](#under-processing) > [Customer Clearance](#customer-clearance) > [ARCO Clearance](#arco-clearance) > [Travel Arrangement](#travel-arrangements) > [Waiting for Travel](#waiting-for-travel) > [Rejected Request](#rejected-request) > [Completed](#completed) |

<br>


- ### **ARCO Approval:**

    - In This stage, Initiated New Request is received from Case and Task Management to ARCO Approval.

    - And Waiting to get ARCO Approval for the Leave Request.

    - In ARCO Approval, Validate the residence status of Employee in this stage, Once ARCO Approved then it will move to **Customer Approval** stage in HRM.

    - If Employee escaped then it moved to **Escape** stage.

    - **In Case and Task Management**, process moved to **Customer Approval** Stage, Once ARCO Approval Completed.



    - **User can move the request to required stage**,

      - *In The action field is following to,*

         **1-[Complete](#customer-approval)** - User complete this request and refer to [Customer Approval](#customer-approval) Stage.

        **2-[Reject](#rejected-request)** - User reject the request to [Rejected Request](#rejected-request) stage.

        **3-[Escape](#completed)** - User reject and complete the request as Escape to [completed](#completed) stage.

- ### **Customer Approval:**


    - In this stage, Waiting for the **Customer Approval** in Case and Task Management, Once customer approved in Case and Task Management, then it moved to **Under processing** Stage in HRM.

    - In **Case and Task Management**, Vacation Process will move to **Customer Approval** stage, then Customer can Approve the request from Case and Task Management.

    - Once Customer Approved the Request, then it will moved to **"UnderProcess"** Stage in "Case and Task Management".

    - **User can move the request to required stage**,

      - *In The action field is following to,*

          **1-[Reject](#rejected-request)** -  complete and reject the request to [Rejected Request](#rejected-request) stage.

          **2-[Complete](#under-processing)** - User complete and refer this request to [Under Processing](#under-processing) stage. for Vacation process.


- ### **Under Processing:**

    - In This stage, Waiting to Process the Vacation Settlement in **Finance Portal**.

    -  In Case and Task Management, waiting to process the request in **Under Process** stage.

    - **Once the Vacation Settlement is completed in Finance Portal**.
    
       * In HRM, The Request moved to **Customer Clearance** stage.

       * In Case and Task Management, The Request moved to **Customer Confirmation** stage.

    - **(Paid Vacation / Local Vacation / Vacation Encashment have to apply and proceed for Vacation settlement.)**

    - **(Unpaid vacation is not Applicable to apply for Vacation settlement.)**

    - And Then **[Vacation Settlement](#vacation-settlement)** process will begins and create from this **Under Processing** stage with System Integration. when the "customer request for Settlement" in Leave Request from **Case and Task Management**.

    - If Employee Request, **Visa** and **Travel Request** from **ARCO**, then Visa and Travel process will start for the employee After Vacation settlement is completed with system integration.

    - If Customer not request for Clearance, then **Customer Clearance** process will **skipped** and moved to **Waiting for Travel** stage


    - **User can move the request to required stage**,

       - *In The action field is following to,*

         **1-[Reject](#rejected-request)** - and reject the request and refer [Rejected Request](#rejected-request) stage.

         **2-[Complete](#customer-clearance)** - user complete the task and refer the request for [Customer Clearance](#customer-clearance) stage.

- ### **Customer Clearance:**

    - In This stage, Waiting to process the customer clearance on Vacation settlement, Once customer clearance completed on Vacation settlement, then it will move to **ARCO Clearance** stage.

    - In Case and Task Management, Leave request process will move to **Customer Confirmation** stage, then Customer will Approve the request from Case and Task Management.
    
    -  In Case and Task Management, Once Customer Approved in customer confirmation stage , then it will moved to **Approved for payment** Stage.

    -  In **Case and Task Management**, Clearance is optional for employee in **Leave Request**, and it will process who requested the Clearance on Vacation settlement.

    - Otherwise this Clearance stage will be **skipped** and moved to **completed** stage.


    - **User can move the request to required stage**,

        - *In The action field is following to,*

            **1-[Complete](#arco-clearance)** -  complete the stage and refer the [ARCO Clearance](#arco-clearance) stage.

            **2-[Reject](#rejected-request)** - User reject the request and complete [Rejected Request](#rejected-request) stage.

- ### **Arco Clearance:**

    - In This stage, waiting to get **ARCO Clearance** on Vacation Settlement, Once ARCO complete the Clearance on Settlement, then it will moved to Required stage.

      - In **ARCO Clearance**, Waiting to complete the process in **Finance Department** Approval, If The Finance Depart complete the process, then it will move to **Waiting for Travel** stage

    -  **In Case and Task Management**, Leave Request will move to **"Approved for Payment"** stage.

       -  Once User Approved from Finance Department, Then it will moved to **Visa Requested Stage** in Case and Task Management.


    - ARCO Clearance is **Optional** for Employee, it will process who requested the Clearance for settlement in Case and Task Management.

    - Otherwise This Clearance stage will be **Skipped** and moved completed stage.


    - **User can move the request to required stage**,

       - *In The action field is following to,*

          **1-[Complete](#waiting-for-travel)** - complete the request and refer [Waiting for Travel](#waiting-for-travel) stage.

          **2-[Reject](#rejected-request)**   - User reject the request to [Rejected Request](#rejected-request) stage.

- ### **Travel Arrangements:**

    - In This stage, Prepare the Employee to Travel, once Travel Preparation is completed, Then it will moved to **Waiting for Travel** stage.

    - Travel Arrangements is Applicable, to who on Accommodate in lodging.

    - Travel Arrangements is not Applicable, to who do not Accommadate in Lodging.

     - Otherwise this stage **skipped** and moved to **Waiting for Travel** stage.

    - **User can move the request to next stage**,

       - *In The action field is following to,*

         **1-[Complete](#waiting-for-travel)** - User complete this task and refer the request into [Waiting for Travel](#waiting-for-travel) stage.

- ### **Waiting for Travel:**

    - In This stage, when Employee went **On Vacation**, Muqeem status will change as **OutsideKingdom** in **Muqeem portal**.

    - By **System schedule** will check, If **Muqeem status** is **On-Vacation_OutSide Kingdom**, Then *Complete the Vacation Process with Travel Date*.

    - **User can move the request to required stage**,

      - *In The action field is following to,*

        **1-[Complete](#completed)** - User complete the request and moved to [Completed](#completed) Stage.

        **2-[Reject](#rejected-request)**   - User reject the request to **[Rejected Request](#rejected-request)** stage. and holding for the requirements.

- ### **Rejected Request:**

    - In This stage, Rejected Request is reject and moved to completed stage.

    - **User can move the request to next stage**,

      - *In The action field is following to,*

        **1-[Reject](#completed)** - User reject and complete the Request to [Completed](#completed) stage.

- ### **Completed:**

    - Completed Request moved to **Completed** Stage, After Vacation Settlement, Then will start The Visa and Travel Request to Employee for Vacation.

    - And System checking on **Muqeem status** on reqular time of period, then **Return process** will start with **Muqeem Status**.

    - Once Vacation Process Complete, Employee Status will change as **"On-Vacation_Out-SideKingdom"** and **"Vacation Return"** Process will Start.


| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#leave-request) |



<br>

## **[Vacation Settlement:](#leave-management)**

- Vacation Settlement is initiated in Leave Request from **Case and Task Management**, and Settlement will process in **Finance Department**.

- If The Employee not required/applied for the settlement in Leave Request, Then this stage will **Complete without Payment**.


| [Requested](#requested) > [Clearance Process](#clearance_process) > [Approval](#approval) > [Client_Confirmation](#client_confirmation) > [Payment](#payment) > [Client Rejection](#client-rejection) > [Complete](#complete) |

<br>

- ### **Requested:**

    - New request initiated by user or customer from Case and Task Management, And this Request is waiting to process.

    - Then User will move the request to **Clearance_Process** stage.

    - In Case and Task Management, Vacation Process will move to **Finance Approval** stage

    - **User can move the request to next stage**,

       - *In The action field is following to,*

         **1-[Move to Clearance](#clearance_process)** - User complete the request and refer into [Clearance_Process](#clearance_process) stage.

- ### **Clearance_Process:**


     - In This stage, Clearance Process will start for employee, and Waiting to complete the Clearance in **Clearance Module**. Once Clearance is completed, Then it will send **Approval** to **Finance Department** Approval.

    - In Case of Customer required settlement, Then it will send for approval to **Client Confirmation**, Otherwise it will move and **Complete Without Payment**.

    - **User can move the request to next stage**,

      - *In The action field is following to,*

        **1-[Complete](#approval)** - User complete the task and refer the request for [Approval](#approval) stage.


- ### **Approval:**

     - In This stage, Waiting to get Finance Approval from Finanace Department for **Vacation Settlement**, Once **Finance Department** Approved, Then User will complete the request.

     - Then it will send for **Approval** to **Client Confirmation** stage.

     - If Do not have any **Vacation Settlement** Payment for Employee, Then this request complete with **Move without Payment**.

    - **User can move the request to required stage**,

      - *In The action field is following to,*

        **1-[Approve](#client_confirmation)** - User complete the request and refer to [Client Confirmation](#client_confirmation) stage.

        **2-[Re-Calculate Clearance](#clearance_process)** - user reject the request and return to [Clearance_Process](#clearance_process) stage. for recalculation of clearance.

- ### **Client_Confirmation:**

    - In This stage, Waiting to complete for Client Confirmation.

    - User Complete the request with **Client_Confirmation** from **Case and Task Management**.

    - Once Client_Confirmation is completed, Then it will moved to **Finance Department** with **Payment** stage.

    - **In Case and Task Management**, Vacation Process will move to **Customer Confirmation** stage, Customer or User will Approve from Case and Task Management.

    -  Once Approved in Case and Task Management, Then it will moved to **Payment** Stage in HRM.

    - If Customer Reject in Casa and Task Management, Then process will moved to **Client Rejection** stage.


    - **User can move the request to required stage**,

      - *In The action field is following to,*

        **1-[Complete](#payment)** - User complete the request and approve with **Client_Confirmation** then refer the [Payment](#payment) stage.

        2-**Reject** - reject the request and **complete** the stage.

- ### **Payment:**

    - In This stage, Waiting to complete the payment, The payment will process in Finance Department, Once **Payment** is **Completed** in **Finance Department** then it will moved to completed stage.

    - After Payment is completed in Finance Department, Then request has been moved to **Completed** stage.

    - User can compare the **Payment Status** of Vacation Settlement in between the **[Vacation Settlement](#vacation-settlement)** and  **Finance Department**.

      Payment have settled to Employee in Finace Department.

    - In Case and Task Management, Vacation Process will move to **Approved For Payment** stage.

    - **User can move the request to required stage**,

       - *In The action field is following to,*

         **1-[Complete](#complete)** - User complete this request and move to [Complete](#complete) Stage.

         **2-[ReCalculate](#clearance_process)** - User reject the request and moved to [Clearance _Process](#clearance_process) stage. for Payment Clearance.

- ### **Client Rejection:**

     - Pending Requests are reject and moved to **Client Rejection** stage, and holding the request for review and **Resend for Client Confirmation** stage.

     - If The Customer required, Then Resend to process the **Re-Calculate** the Clearance.

     - In Case and Task Management, Vacation Process will move to **Customer Rejection** stage.

    - **User can move the request to required stage**,

       - *In The action field is following to,*

         **1-[Re Send - CustomerConfirmation](#client_confirmation)** - User return the request, **Resend for Customer Confirmation** to [Client Confirmation](#client_confirmation) stage.

         **2-[Re Calculate Clearance](#clearance_process)** - User Return the request to [Clearance_Process](#clearance_process) stage. for **Re Calculate Clearance** on Vacation Settlement.

- ### **Complete:**

    - Completed Request is moved to **Completed** Stage, After the Vacation Settlement request is completed.

    - And Use These Completed Request for Tracking the Status of Request.

    - Once **Settlement** Completed to Employee, If **Vacation** requests for **Travel**, then Travel process will start to Employee Vacation.
     
    - If Employee requests for **Visa** in **Vacation** process, then **Visa** process will start to Employee Vacation once **Settlement** process is completed.

    - If Employee requests for **Ticket** in **Vacation** process, then **Travel Ticket** process will start to Employee Vacation Once **Visa** process completed.


| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#vacation-settlement) |



<br>

## **[Vacation Return:](#leave-management)**

- Employee should not be pending in **Vacation** or **Retirement** process.

- When Employee **On Vacation**, Muqeem status will be **On-Vacation_Outside Kingdom** status,

- If Employee arrived, Muqeem status will change to valid, then **Vacation Return** process will move to **Return from Vacation** stage.

- If Exit Re-Entry Date is expired and Muqeem is expired, then that request is moved to **Visa Expired** stage.

- If Iqama Expiry Date is less then 10 days, the request will move to **Iqama Approval cancellation** stage,

- Then User will register **"Left Not Return"** in Muqeem, then move to the **Iqma Expiry** date.

<br>

| [On Vacation](#on-vacation) > [Waiting for Return](#waiting-for-return) > [Not Return](#not-return) > [Return from Vacation](#return-from-vacation) > [Visa Expired](#visa-expired) > [Iqama Approval Cancellation](#iqama-approval-cancellation) > [Iqama Expired](#iqama-expired) > [Left Not Return](#leftnotreturn) > [Completed](#completed-1) |

<br>


- ### **On Vacation:**

     - When The Employee not return, On Requested Return Date, Then System will move to **Waiting For Return** stage.

     -  In Case of Employee is on vacation, The Muqeem status will be update **On-Vacation_OutsideKingdom** status,

     - If Employee arrived, Muqeem status will change to valid, Then Vacation Return process will move to **Return From Vacation** stage.

     - System will check the muqeem status requlary, Until The Employee Return,

       If Vacation End Date is mentioned, Then moved to **Return From Vacation** stage.

    - **User can move the request to next stage**

       - *In The action field is following to,*

         **1-[Complete](#return-from-vacation)** - User Complete the Request and refer [Return From Vacation](#return-from-vacation) stage.

- ### **Waiting for Return:**

    - In This stage, Waiting for Employees who do not Return on Requested Return Date,
     If The Employee arrived on Date, Then it will moved to **Return From Vacation** stage.

    - System check the Muqeem status on period of Time.

    - If Employee arrived, Muqeem status will change to valid, Then Vacation Return process will move to **Return From Vacation** stage.

    - Either User complete the request manually or with Employee Check-in process, Then refer to **Return From Vacation** stage.

    - **User can move the request to next stage**

      - *In The action field is following to,*

        **1-[Return](#return-from-vacation)** - User decide to complete this request and refer [Return from Vacation](#return-from-vacation) stage.

- ### **Not Return:**

    - System integration is scheduled the Employee, who do not arrive on Date of Return into Lodging, Then refer to [Waiting For Return](#waiting-for-return) stage.

    - **User can move the request to next stage**

    - 

      - *In The action field is following to,*

        **1-[Move to  Waiting for Return](#waiting-for-return)** - User dicided and refer to [Waiting for Return](#waiting-for-return) stage.

- ### **Return From Vacation:**

    - If Employee returned, Muqeem status will be Valid, and change Employee status as **Inside-kingdom** status.

   - If Employee **Active** in Customer Contract, Employee status will changes to **Working-WithCustomer** and process will moved to **Completed** stage

   - If employee **Not Active** in customer contract, **Check-In** process will create in **Lodging Module**.

   - Once **Check-In Process** Completed, Then process will moved to Completed stage.

   - If Did not complete the process with **Muqeem Integration**, Then It will process by User Manually.

    - **User can move the request to next stage**

        - *In The action field is following to,*

          **1-[Complete](#completed-1)** - User Complete the request and refer to [Completed](#completed-1) Stage.

- ### **Visa Expired:**

    - In this stage, ERE Visa expired is received to extend the validation

    - If **Exit Re-Entry** date is expired and **Muqeem** is expired, then that request is moved to **Visa Expired** stage.

    - And Then request moved **Iqama Expiry** stage.
 
     - **User can move the request to required stage**

        - *In The action field is following to,* decision

          **1-[Iqama Expired](#iqama-expired)** - User complete and refer the request with [Iqama Expiry](#iqama-expired) stage.

          **2-[Move_To_WaitingForReturn](#waiting-for-return)** - User decide to complete the request and refer the [Waiting For Return](#waiting-for-return) stage.


- ### **Iqama Approval Cancellation:**

     - If Iqama Expiry Date is less then 10 days, The request will move to **Iqama Approval cancellation** stage.

     - User validate the Iqama validity and moved to **Waiting For Return** stage.

     - **User can move the request to next stage**

        - *In The action field is following to,*

          **1-[Waiting for Return](#waiting-for-return)** - User complete the task and moved to [Waiting for Return](#waiting-for-return) stage.

- ### **Iqama Expired:**

    - User will register **"Left Not Return"** in **Muqeem**, then move to the **Iqama Expiry Date** stage.

    - Validate the Iqama Expiry Date And move to **Waiting for Return** stage, If The Iqama validation is Expired.

     - **User can move the request to next stage**

       - *In The action field is following to,*

         **1-[Waiting for Return](#waiting-for-return)** - User complete the Task refer to [Waiting for Return](#waiting-for-return) stage.

- ### **LeftNotReturn:**

     - In This stage, Employee Status will changed as **LeftNotReturn-OutSideKingdom**.

     - **Retirement** Process will start with **Left Not Return** Category, to clear The Employee settlement.


- ### **Completed:**

     - Completed Request is moved to **Completed** Stage, After the Vacation Return process is completed.
     
     - And Use this Data for Tracking the status of  Request.

| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#vacation-return) |


<br>

## **[Leave Reject Request:](#leave-management)**

If the Employee reject the Leave Request, That Rejection process will start in before to **Waiting for Travel** stage only.

| [Vacation Settlement](#vacation-settlement-1) > [Visa Request](#visa-request) > [Travel Request](#travel-request) > [Completed](#completed-2) |

<br>

- ### **Vacation Settlement:**

    - In This stage, Waiting to cancel the settlement process, If settlement process begins, Then User will reject the settlement request in this stage.
    
    - Once Rejection completed then it will move to **Visa Request** stage.

     - **User can move the request to next stage**

       - *In The action field is following to,*

          **1-[Complete](#visa-request)** - User complete the request and refer to [Visa Request](#visa-request) stage.

- ### **Visa Request:**

    - In This stage, Waiting to cancel the **Visa Request** in the Leave request, If Visa Request is begins, Then User will reject the Visa request in this stage.
    
    -  Once Rejection completed then it will move to **Travel Request** stage.

    - **User can move the request to next stage**

      - *In The action field is following to,*

        **1- [Complete](#travel-request)** - User complete the request and Moved to [Travel Request](#travel-request) stage.

- ### **Travel Request:**

     - In This stage, Waiting to Cancel the Travel Request in leave request, If Travel Request begins, Then User will reject **Travel Request** in this stage.
     
     - Once Rejection completed the stage, then it will move to Completed stage.

       - *In The action field is following to,*

         **1-[Complete](#completed-2)** - User complete the request and moved to [Completed](#completed-2) stage.

- ### **Completed:**

   - Completed Request is moved to **Completed** Stage.

   -  After Leave Reject process is completed, These completed request is use Tracking the status of Request.

| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#leave-reject-request) |

