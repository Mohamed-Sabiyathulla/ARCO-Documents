# **Human Resource Management**

| [Employee](#employee) | [On Board](#on-board) | [Leave Management](#leave-management) | [Travel](#travel) | [Employee Retirement](#employee-retirement) | [Loan](#loan) | [Reissue](#reissue) | [Renewal](#renewal) | [Clearance](#clearance) |

<br>


# **[Leave Management](#human-resource-management)**

| [Leave Request](#leave-request) | [Vacation Settlement](#vacation-settlement) | [Vacation Return](#vacation-return) | [Leave Reject Request](#leave-reject-request) |

<br>

## **[Leave Request:](#leave-management)**

The Leave Request is initiated from Case and Task Management for Employee by User or Customer.

New request created in Case and Task Management and then it will moved to **ARCO Approval** from **Case and Task management**.




| [ARCO Approval](#arco-approval) > [Customer Approval](#customer-approval) > [Under Processing](#under-processing) > [Customer Clearance](#customer-clearance) > [ARCO Clearance](#arco-clearance) > [Travel Arrangement](#travel-arrangements) > [Waiting for Travel](#waiting-for-travel) > [Rejected Request](#rejected-request) > [Completed](#completed) |

<br>


- ### **ARCO Approval:**

    - In This stage, Initiated New Request is received from Case and Task Management to ARCO Approval.

    - And Waiting to get ARCO Approval for the Leave Request.

    - In ARCO Approval, Validate the residence status of Employee in this stage, Once ARCO Approved then it will move to **Customer Approval** stage in HRM.

    - If Employee escaped then it moved to **Escape** stage.

    - In Case and Task Management, process moved to **Customer Approval** Stage.



    - **User can move the request to required stage**,

      - *In The action field is following to,*

         **1-[Complete](#customer-approval)** - User complete this request and refer to [Customer Approval](#customer-approval) Stage.

        **2-[Reject](#rejected-request)** - User reject the request to [Rejected Request](#rejected-request) stage.

        **3-[Escape](#completed)** - User reject and complete the request as Escape to [completed](#completed) stage.

- ### **Customer Approval:**


    - In this stage, Waiting for the **Customer Approval** in Case and Task Management, Once customer approved in Case and Task Management, then it moved to **Under processing** Stage in HRM.

    - In **Case and Task Management**, Vacation Process will move to Customer Approval stage, then Customer Approve the request from Case and Task Management.

    - Once Customer Approved the Request, then it will moved to **"UnderProcessing"** Stage in **"Case and Task Management"**.



    - **User can move the request to required stage**,

      - *In The action field is following to,*

          **1-[Reject](#rejected-request)** -  complete and reject the request to [Rejected Request](#rejected-request) stage.

          **2-[Complete](#under-processing)** - User complete and refer this request to [Under Processing](#under-processing) stage. for Vacation process.


- ### **Under Processing:**

    - In This stage, Waiting to Process the Vacation Settlement in Finance portal.

    -  In Case and Task Management, waiting the request in **Under Process** stage.

    - **Once the Vacation Settlement is completed in Finance Portal**.
    
       * In HRM, The Request moved to **Customer Clearance** stage.

       * In Case and Task Management, The Request moved to **Customer Confirmation** stage.

    - **(Paid Vacation / Local Vacation / Vacation Encashment have to apply and proceed for Vacation settlement.)**

    - **(Unpaid vacation is not Applicable to apply for Vacation settlement.)**

    - The **[Vacation Settlement](#vacation-settlement)** process will begins and create from this **Under Processing** stage with System Integration. when the "customer request for Settlement" in Leave Request from **Case and Task Management**.

    - If Employee Request, Visa and Travel Request from ARCO, then Visa and Travel process will start for the employee After Vacation settlement is completed with system integration.


    - **User can move the request to required stage**,

       - *In The action field is following to,*

         **1-[Reject](#rejected-request)** - and reject the request and refer [Rejected Request](#rejected-request) stage.

         **2-[Complete](#customer-clearance)** - user complete the task and refer the request for [Customer Clearance](#customer-clearance) stage.

- ### **Customer Clearance:**

    - In This stage, Waiting to process the customer clearance on Vacation settlement, Once customer clearance completed on Vacation settlement, then it will move to **ARCO clearance** stage.

    - In Case and Task Management, Leave request process will move to **customer confirmation** stage, then Customer will Approve the request from Case and Task Management.
    
    - Once Customer Approved in customer confirmation stage , then it will moved to **Approved for payment** Stage in Case and Task Management.

    - Clearance is optional for employee in **Leave Request**, and it will process who requested the Clearance on Vacation settlement in **Case and Task Management**.

    - Otherwise this Clearance stage will be **skipped** and moved to **completed** stage.


    - **User can move the request to required stage**,

        - *In The action field is following to,*

            **1-[Complete](#arco-clearance)** -  complete the stage and refer the [ARCO Clearance](#arco-clearance) stage.

            **2-[Reject](#rejected-request)** - User reject the request and complete [Rejected Request](#rejected-request) stage.

- ### **Arco Clearance:**

    - In This stage, waiting to get **ARCO Clearance** on Vacation Settlement, Once ARCO complete the Clearance on Settlement, then it will moved to Required stage.

      - In **ARCO Clearance**, Waiting to complete the process in **Finance Department**, If The Finance Depart complete the process, then it will move to **Waiting for Travel** stage

    -  **In Case and Task Management**, Leave Request will move to **Approved for Payment** stage.

       -  Once User Approved from Finance Department in HRM, Then it will moved to **Visa Requested Stage** in Case and Task Management.


    - ARCO Clearance is **optional** for employee, it will process who requested the Clearance for settlement in Case and task management.

    - Otherwise this clearance stage will be **skipped** and moved completed stage.


    - **User can move the request to required stage**,

       - *In The action field is following to,*

          **1-[Complete](#waiting-for-travel)** - complete the request and refer [Waiting for Travel](#waiting-for-travel) stage.

          **2-[Reject](#rejected-request)**   - User reject the request to [Rejected Request](#rejected-request) stage.

- ### **Travel Arrangements:**

    - In This stage, Prepare the Employee to Travel, once Travel Preparation is completed and it will moved to **Waiting for Travel** stage.

    - Travel Arrangements is Applicable for who on accommodate in lodging.

    - Travel Arrangements is not applicable for who do not accommadate in Lodging.

     - Otherwise this stage **skipped** and moved to **Waiting for Travel** stage.

    - **User can move the request to next stage**,

       - *In The action field is following to,*

         **1-[Complete](#waiting-for-travel)** - User complete this task and refer the request into [Waiting for Travel](#waiting-for-travel) stage.

- ### **Waiting for Travel:**

    - In this stage, when employee went on vacation, Muqeem status will change as **OutsideKingdom** in **Muqeem portal**.

    - By **System schedule** will check, If **Muqeem status** is **On-Vacation_OutSide Kingdom**, Then *Complete the Vacation Process with Travel Date*.

    - **User can move the request to required stage**,

      - *In The action field is following to,*

        **1-[Complete](#completed)** - User complete the request and moved to [Completed](#completed) Stage.

        **2-[Reject](#rejected-request)**   - User reject the request to **[Rejected Request](#rejected-request)** stage. and holding for the requirements.

- ### **Rejected Request:**

    - In this stage, rejected request is reject and moved to completed stage.

    - **User can move the request to next stage**,

      - *In The action field is following to,*

        **1-[Reject](#completed)** - User reject and complete the Request to [Completed](#completed) stage.

- ### **Completed:**

    - Completed Request moved to **Completed** Stage, After Vacation Settlement, Visaand Travel Request is completed to Employee Vacation.

    - And System checking on **Muqeem status** on reqular time of period, then **Return process** will start with **Muqeem Status**.

    - Once Vacation Process Complete, Employee Status will change as **"On-Vacation_Out-SideKingdom"** and **"Vacation Return"** Process will Start.


| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#leave-request) |



<br>

## **[Vacation Settlement:](#leave-management)**

- Vacation Settlement is initiated in **Case and Task Management**, and Settlement will process in **Finance portal**.

-  Vacation settlement process will complete, If Vacation Settlement request is completed in Finance Portal.

- If The Employee not required the settlement in Leave Request, Then this stage will **Complete without Payment**.


| [Requested](#requested) > [Clearance Process](#clearance_process) > [Approval](#approval) > [Client_Confirmation](#client_confirmation) > [Payment](#payment) > [Client Rejection](#client-rejection) > [Complete](#complete) |

<br>

- ### **Requested:**

    - New request initiated from Case and Task management by user or customer. and then that Request is waiting for Action,

    - In Case and Task Management, Vacation Process will move to Finance Approval stage.


    - New Request is waiting for action from case and task management.

       - *In The action field is following to,*

         **1-[Move to Clearance](#clearance_process)** - User complete the request and refer into [Clearance_Process](#clearance_process) stage.

- ### **Clearance_Process:**

    - In this stage, waiting for clearance on settlement, once clearance completed then it will send Approval to Finance Departmet Approval.

    - In case of customer required settlement, then it will send for approval to client confirmation, otherwise it will moved to complete without payment.

      - *In The action field is following to,*

        **1-[Complete](#approval)** - User complete the task and refer the request for [Approval](#approval) stage.


- ### **Approval:**

    - In this stage, waiting for approval on settlement from finance department,
    
       Once Approved by finance department then it will moved to Client confirmation.

    - After Approval, user complete the request and refer to Client confirmation stage.


      - *In The action field is following to,*

        **1-[Approve](#client_confirmation)** - User complete the request and refer to [Client Confirmation](#client_confirmation) stage.

        **2-[Re-Calculate Clearance](#clearance_process)** - user reject the request and return to [Clearance_Process](#clearance_process) stage. for recalculation of clearance.

- ### **Client_Confirmation:**

    - In this stage, waiting for Client Confirmation on Clearance on settlement.

       Once Client confirmation completed then it will moved to Finance Department for Payment.

    - User complet the request after **Client_Confirmation** on Clearance and refer to Payment stage.

      - *In The action field is following to,*

        **1-[Complete](#payment)** - User complete the request and approve with **Client_Confirmation** then refer the [Payment](#payment) stage.

        2-Reject - reject the request and complete the stage.

- ### **Payment:**

    - In this stage waiting for payment, the payment is prcessing in Finance Department, Once payment is Completed in Finance Department then it will moved to completed stage.

    - After payment is completed in Finance Department, then this request has been moved to **Completed** stage.

    - User can compare the Payment status of Vacation Settlement in between the **[Vacation Settlement](#vacation-settlement)** and  **Finance Department**.

      Payment have settled to Employee in Finace Department.

       - *In The action field is following to,*

         **1-[Complete](#complete)** - User complete this request and move to [Complete](#complete) Stage.

         **2-[ReCalculate](#clearance_process)** - User reject the request and moved to [Clearance _Process](#clearance_process) stage. for Payment Clearance.

- ### **Client Rejection:**

     - Pending request is reject to **Client Rejection** and hold the  request,
     
        For Re-send to process the **Client Confirmation** and **Re Calculate Clearance** stage.

       - *In The action field is following to,*

         **1-[ReSend - CustomerConfirmation](#client_confirmation)** - User return the request, **Resend for Customer Confirmation** to [Client Confirmation](#client_confirmation) stage.

         **2-[Re Calculate Clearance](#clearance_process)** - User Return the request to [Clearance_Process](#clearance_process) stage. for **Re Calculate Clearance** on Vacation Settlement.

- ### **Complete:**

    - Completed Request is moved to Completed Stage, After the Vacation Settlement request completed. and use this all completed request for Tracking the status of the request.

| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#vacation-settlement) |







<br>

## **[Vacation Return:](#leave-management)**

System will change and update the vacation return process automatically based on muqeem status in reqular basis,

when employee **On Vacation**, muqeem status will be on-vacation Outside Kingdom status,

If Employee arrived, muqeem status will change to the valid then vacation return process will move to **Return from Vacation** stage.

If Exit Re Entry date is expired and muqeem is expired, then that request is moved to **Visa Expired** stage.

If iqama expiry date is less then 10 days, the request will move to **Iqama Approval cancellation** stage,

Then User will register "Left Not Return" in muqeem then move to the **Iqma Expiry** date.

| [On Vacation](#on-vacation) > [Waiting for Return](#waiting-for-return) > [Not Return](#not-return) > [Return from Vacation](#return-from-vacation) > [Visa Expired](#visa-expired) > [Iqama Approval Cancellation](#iqama-approval-cancellation) > [Iqama Expired](#iqama-expired) > [Left Not Return](#leftnotreturn) > [Completed](#completed-1) |

<br>


- ### **On Vacation:**

     - When the employee not return after requested return date, system will move to the **Waiting for Return stage**.

     -  In case of employee is on vacation, the Muqeem status will be update on-vacation **OutsideKingdom** status,

     - If Employee arrived, muqeem status will change to the valid then vacation return process will move to **Return from vacation** stage.

     - System will check the muqeem status requlary, until the employee return,

       if vacation end date is mentioned then moved to **Return from Vacation** stage.

       - *In The action field is following to,*

         **1-[Complete](#return-from-vacation)** - User Complete the Request and refer [Return From Vacation](#return-from-vacation) stage.

- ### **Waiting for Return:**

    - In this stage, waiting for employees who do not return on requested return date,
    
      And if the employee arrived then it will moved to **Return from Vacation** stage.

    - The system check the Muqeem status on reqularly.

    - If Employee arrived, muqeem status will change to the valid then vacation return process will move to **Return from Vacation** stage.

    - Either User complete the request manually with employee check-in process, vacation and refer to **Return from Vacation** stage.

      - *In The action field is following to,*

        **1-[Return](#return-from-vacation)** - User decide to complete this request and refer [Return from Vacation](#return-from-vacation) stage.

- ### **Not Return:**

    - System integration is scheduled the Employee who didn’t arrive on the Date of Return into Lodging is refer to [Waiting For Return](#waiting-for-return) stage.

      - *In The action field is following to,*

        **1-[Move to  Waiting for Return](#waiting-for-return)** - User dicided and refer to [Waiting for Return](#waiting-for-return) stage.

- ### **Return From Vacation:**

    - If employee returned, Muqeem status will change to the employee status as inside-kingdom status.

    - If does not complete the stage with muqeem integration, then it will process manually with validate muqeem status and employee status, and complete the request,

        - *In The action field is following to,*

          **1-[Complete](#completed-1)** - User Complete the request and refer to [Completed](#completed-1) Stage.

- ### **Visa Expired:**

    - In this stage, ERE Visa expired is received to extend the validation

    - If Exit Re Entry date is expired and muqeem is expired, then that request is moved to **Visa Expired** stage.

    - And then request moved Iqama Expiry.

        - *In The action field is following to,* decision

          **1-[Iqama Expired](#iqama-expired)** - User complete and refer the request with [Iqama Expiry](#iqama-expired) stage.

          **2-[Move_To_WaitingForReturn](#waiting-for-return)** - User decide to complete the request and refer the [Waiting For Return](#waiting-for-return) stage.


- ### **Iqama Approval Cancellation:**

     - If iqama expiry date is less then 10 days, the request will move to Iqama Approval cancellation stage.

     - User validate the Iqama validaty and moved to **Waiting For Return** stage.

        - *In The action field is following to,*

          **1-[Waiting for Return](#waiting-for-return)** - User complete the task and moved to [Waiting for Return](#waiting-for-return) stage.

- ### **Iqama Expired:**

    - User will register "Left Not Return" in muqeem then move to the **Iqma Expiry** date.

    - Validate the Iqama Expiry date and move to **Waiting for Return** stage. if the Iqama validation is expired.

       - *In The action field is following to,*

         **1-[Waiting for Return](#waiting-for-return)** - User complete the Task refer to [Waiting for Return](#waiting-for-return) stage.

- ### **LeftNotReturn:**

     - Employees who lefted and do not return from on vacation are Listed for Tracking purposes.

- ### **Completed:**

     - Completed Request is moved to Completed Stage, After the Vacation Return process is completed. And use this data for Tracking the status of the request.

| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#vacation-return) |


<br>

## **[Leave Reject Request:](#leave-management)**

If the Employee reject the leave request, that reject process will start in **Waiting for Travel** stage only.

| [Vacation Settlement](#vacation-settlement-1) > [Visa Request](#visa-request) > [Travel Request](#travel-request) > [Completed](#completed-2) |

<br>

- ### **Vacation Settlement:**

    - Waiting to cancel the settelement, and reject the settlement reqest in this stage. once completed the stage then it will move to Visa Request.

       - *In The action field is following to,*

          **1-[Complete](#visa-request)** - User complete the request and refer to [Visa Request](#visa-request) stage.

- ### **Visa Request:**

    - Waiting to reject and cancel the Visa Request in the Leave request, once completed the stage then it will move to Travel Request.

      - *In The action field is following to,*

        **1- [Complete](#travel-request)** - User complete the request and Moved to [Travel Request](#travel-request) stage.

- ### **Travel Request:**

     - Waiting to reject and Cancel the Travel Request in leave request,  once completed the stage then it will move to Completed stage.

       - *In The action field is following to,*

         **1-[Complete](#completed-2)** - User complete the request and moved to [Completed](#completed-2) stage.

- ### **Completed:**

   - Completed Request is moved to Completed Stage, After Leave Reject process is completed. and use this data for Tracking the status of the Request.

| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#leave-reject-request) |

