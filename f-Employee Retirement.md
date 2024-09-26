
# **[Employee Retirement](#human-resource-management)**

| [Retirement Request](#retirement-request) | [Final Settlement](#final-settlement) |


<br>


> ## **[Retirement Request:](#employee-retirement)**

<br>


- **Retirement** Request is initiated from **Case and Task Management**.

- Employee Should not be pending in **Vacation** or **Retirement** process.

- If Employee have **ERP access,** It should **De-activate** before Request.

- Employee should not be in **Outside Kingdom**.

- Employee should not be **Iqama Renewal** Process.

- **(Employee Status will change based on EOS Category:**

    - **--If Category is End of Service, employee status will change as "Terminated".**

   - **--If Category is Escaped, employee status will change as "Terminated_Escaped".**

   - **--If Category is Transferred, employee status will change as "Transferred".**

   - **--If Category is LeftNotReturn, employee status will change as "Terminated_LeftNotReturn".**

   - **--If Category is Dead, employee status will change as "  ".)**

* ### _Mandatory field to update while Request for Retirement:_

    **1- Labour ID,**

    - Unique **Identification Number** provided by organization to Employee.

    **2- Request Date,**

    - Required the **Date of Request** for Retirement process.

    **3- Expected Date of Leaving,**

    - Expected Date of Leaving from Organization.(Particular Leaving Date)

    **4- EOS Category,**

   - _End of Service,_
   - _Escaped,_
   - _Deport,_
   - _Transfered,_
   - _Left Not Return,_
   - _Dead._

   **5- Settlement Paid by,**

     * Settlement is optional to receive from Employer or Customer-

       - _ARCO_ -
       - _Customer_ -

   **6- Need Settlement,**

   - **Final Settlement** is Settle from Organization in Retirement to Employee.

   **7- Need Travel Arrangements,**

   - Travel is **Optional** request from Organization in Retirement process to Employee.

   **8- Need Exit,**

   - **Final Exit Visa** is Afford from Organization in Retirement process to Employee.

   **9- Need Clearance,**

  - Clearance process is **Optional** to request from Organization in the Retirement process to Employee.



*

| [New Request](#new-request) > [Arco Approval](#arco-approval-1) > [Customer Approval](#customer-approval-1) > [Under Processing](#under-processing-2) > [Customer Clearance](#customer-clearance-1) > [Arco Clearance](#arco-clearance-1) > [Waiting for Travel](#waiting-for-travel-1) > [RejectedRequest](#rejectedrequest) > [Complete](#complete-4) |

<br>

## *Retirment-Workflow:*

- ### **New Request:**

    - New request created and initiated from Case and Task Management.
    
    - And User will moved to **ARCO Approval** from **Case and Task Management**.

    - **User can move the request to next stage,**

       - *In The Action field is following to,*

         **1-[Complete](#arco-approval-1)** - User Complete the Request and refer to [Arco Approval](#arco-approval-1) stage.


- ### **Arco Approval:**

    -  In This stage, Waiting for get **ARCO Approval** for Employee Retirement, Once Arco Approval is completed, Then It will moved to **Customer Approval** stage.

    - **In Case and Task Management**, Waiting to get **ARCO Approval**, and User will **Approve** from HRM.
    
    - In Case and Task Management, It will moved to **Customer Approval** Stage, Once the ARCO Approval is completed.

    - **User can move the request to required stage,**

       - *In The Action field is following to,*

         **1-[Complete](#customer-approval-1)** - User Complete the Request in this Arco Approval stage and then refer to [Customer Approval](#customer-approval-1) Stage.

         **2-[Reject](#rejectedrequest)** - User Reject the request and moved to [Rejected Request](#rejectedrequest) stage.

- ### **Customer Approval:**

    - In This stage, Waiting for Customer Approval in Case and Task Management. Once the Customer Approved in Case and Task Mangement, Then it will moved to **UnderProcessing** stage in HRM.

    - **In Case and Task Management**, Retirement Process will move to **Customer Approval** stage, Customer will **Approve** from Case and Task Management.
    
    - Once Approved in Case and Task Management, Then it will moved to **UnderProcess** Stage in Case and Task Management.

    - **User can move the request to required stage,**

      - *In The Action field is following to,*

        **1-[Reject](#rejectedrequest)** - User Reject complete the request and refer to [RejectedRequest](#rejectedrequest) stage.

        **2-[Complete](#under-processing-2)** - User Complete the request and refer to [Under Processing](#under-processing-2) Stage.

- ### **Under Processing:**

    - In This stage, Waiting to Process the Final Settlement in **Finance Portal**.

    -  In Case and Task Management, waiting to process the request in **Under Process** stage.

    - **Once the Final Settlement is completed in Finance Portal**.
    
       * In HRM, The Request moved to **Customer Clearance** stage.

       * In Case and Task Management, The Request moved to **Customer Confirmation** stage.

    - And Then **[Final Settlement](#Final-settlement)** process will begins and create from this **Under Processing** stage with System Integration. when the "customer request for Settlement" in Retirement Request from **Case and Task Management**.

    - If Employee request, for **Final Exit-Visa** and **Travel request** from ARCO, Then Final Exit-Visa and Travel request process will start for employee. When **Final Settlement** is completed to Employee.

    - If Customer not request for Clearance, then **Customer Clearance** process will **skipped** and moved to **Waiting for Travel** stage.

    - **User can move the request to required stage,**

       - *In The Action field is following to,*

         **1-[Reject](#rejectedrequest)** - User reject the request and moved to [RejectedRequest](#rejectedrequest) stage.

         **2-[Complete](#customer-clearance-1)** - User complete the requsest and then refer to [Customer Clearance](#customer-clearance-1) stage.



- ### **Customer Clearance:**


    - In This stage, Waiting to process the customer clearance on Final settlement, Once customer clearance completed on Final settlement, Then it will move to **ARCO Clearance** stage.

    - In Case and Task Management, Retirement request process will move to **Customer Confirmation** stage, then Customer will Approve the request from Case and Task Management.
    
    -  In Case and Task Management, Once Customer Approved in customer confirmation stage , then it will moved to **Approved for payment** Stage.

    -  In **Case and Task Management**, Clearance is optional for employee in **Retirement Request**, and it will process who requested the Clearance on Final settlement.

    - Otherwise this Clearance stage will be **skipped** and moved to **completed** stage.

    - **User can move the request to required stage,**

       - *In The Action field is following to,*

         **1-[Complete](#arco-clearance-1)** - User complete and refer the request to [Arco Clearance](#arco-clearance-1) stage.

         **2-[Reject](#rejectedrequest)** - User Reject the request to [RejectedRequest](#rejectedrequest) stage.

- ### **Arco Clearance:**


    - In This stage, waiting to get **ARCO Clearance** on Final Settlement, Once ARCO complete the Clearance on Settlement, then it will moved to Required stage.

      - In **ARCO Clearance**, Waiting to complete the process in **Finance Department** Approval, If The Finance Depart complete the process, then it will move to **Waiting for Travel** stage

    -  **In Case and Task Management**, Retirement Request will move to **"Approved for Payment"** stage.

       -  Once User Approved from Finance Department, Then it will moved to **Visa Issuance** in Case and Task Management.


    - ARCO Clearance is **Optional** for Employee, it will process who requested the Clearance for settlement in Case and Task Management.

    - Otherwise This Clearance stage will be **Skipped** and moved completed stage.

    - **User can move the request to required stage,**

       - *In the Action field is Following to,*

          **1-[Complete](#waiting-for-travel-1)** -  User complete the request and refer to [Waiting for Travel](#waiting-for-travel-1) stage.

          **2-[Reject](#rejectedrequest)** - User reject and complete the request to [Rejected request](#rejectedrequest) stage.

- ### **Waiting for Travel:**

   - If Employee completes service, Retired and Returned, Then **Muqueem Status** will change as **OutSideKingdom** in **Muqueem Portal**.

   - By system schedule will Check, if **Muqueem status** is **Terminated-OutSideKingdom**, and Complete the **Retirment Process** with **Travel Date**.

   - **User can move the request to required stage,**

      - *In the Action field is Following to,*

        **1-[Complete](#complete-4)** - User complete the request and then refer to [Complete](#complete-4) stage.

        **2-[Reject](#rejectedrequest)** - User Reject and complete the request then moved to [Rejected Request](#rejectedrequest) stage.

- ### **RejectedRequest:**

    - In this stage, rejected request is moved to **"complete"** stage.

   - **User can move the request to next stage,**

       - *In the Action field is Following to,*

          **1-Reject** - reject the request and moved to **"Complete"** stage.

- ### **Complete:**

     - Completed request is moved to **"complete"** stage.
     
     - And Use to track the status of request.

     - Then Retirement process will complete with **"Final Exit Visa**" and **"Final Settlement"** for Employee.

     - If Employee requests for **Travel Request** from ARCO, Then It will start to Employee, Once **Final Settlement** process is completed.

| [Home](#human-resource-management) | [Main](#employee-retirement) | [Back](#retirement-request) |



<br>

> ## **[Final Settlement](#employee-retirement):**

- Final Settlement is initiated by **User** or **Customer** from **Case and Task Management.**

- And **Payment** process will start in **Finance Portal**, Once Payment is completed in Finance Portal, Then Final Settlement process will be complete to **Employee Retirement**.


| [Requested](#requested-4)  > [Clearance Process](#clearance-process) > [Approval](#approval-3) > [Client _ Confirmation](#client_confirmation-1) > [Payment](#payment-3) > [Client Rejection](#client-rejection-1) > [Complete](#complete-3) |

<br>

- ### **Requested:**

    - New request initiated by user or customer from Case and Task Management, And this Request is waiting to process.

    - Then User will move the request to **Clearance_Process** stage.

    -  In Case and Task Management, Retirement Process will move to **Finance Approval** stage.

   - **User can move the request to next stage,**

        - *In The Action field is following to,*

           **1-[Move to Clearance](#clearance-process)** - User complete the request and *refer for [Clearance process](#clearance-process) stage.

- ### **Clearance Process:**

    - In This stage, Clearance Process will start for Employee, and waiting to complete the Clearance in **Clearance Module**, Once Clearance completed, Then it will send Approval to **Finance Department Approval**.

    - In Case of Customer required settlement, Then it will send for approval to **Client Confirmation**, Otherwise it will move and **Complete Without Payment**.


    - **User can move the request to next stage,**

      - *In The Action field is following to,*

          **1-[Complete](#approval-3)** - User complete the request and refer to [Approval](#approval-3) stage. for **Final Settlement** Clearance.

- ### **Approval:**

     - In This stage, Waiting to get Finance Approval from Finanace Department for **Final Settlement**, Once **Finance Department** Approved, Then User will complete the request.

     - Then it will send for **Approval** to **Client Confirmation** stage.

     - If Do not have any **Final Settlement** Payment for Employee, Then this request complete with **Move without Payment**.

     - **User can move the request to next stage,**

        - *In The Action field is following to,*

          **1-[Complete](#client_confirmation-1)** - Complete this request and moved For [Client_Confirmation](#client_confirmation-1) stage.

           **2-[Re Calculate Clearance](#clearance-process)** - User reject and return the request [Clearance Process](#clearance-process) stage. for Re Calculate Clearance amount.

           **3-[Move Without Payment](#complete-3)** - User complete this request and **Move Without Payment** to [Complete](#complete-3) Stage.

- ### **Client_Confirmation:**

    - In This stage, Waiting to complete for Client Confirmation.

    - User Complete the request with **Client_Confirmation** from **Case and Task Management**.

    - Once Client_Confirmation is completed, Then it will moved to **Finance Department** with **Payment** stage.

    - **In Case and Task Management**, Retirement Process will move to **Customer Confirmation** stage, Customer or User will Approve from Case and Task Management.

    -  Once Approved in Case and Task Management, Then it will moved to **Payment** Stage in HRM.

    - If Customer Reject in Casa and Task Management, Then process will moved to **Client Rejection** stage.

    - **User can move the request to next stage,**

       - *In The Action field is following to,*

         **1-[Confirm](#payment-3)** - User Complete the request and refer to the [Payment](#payment-3) stage.

         **2-[Move to Clearance](#clearance-process)** - User complete and refer the request to [Clearance Process](#clearance-process) stage. for Recalculate the clearance.

- ### **Payment:**

    - In This stage, Waiting to complete the payment, The payment will process in Finance Department, Once **Payment** is **Completed** in **Finance Department** then it will moved to completed stage.

    - After Payment is completed in Finance Department, Then request has been moved to **Completed** stage.

    - User can compare the **Payment Status** of Vacation Settlement in between the **[Final Settlement](#Final-settlement)** and  **Finance Department**.

      Payment have settled to Employee in Finace Department.

    - In Case and Task Management, Retirment Process will move to **Approved For Payment** stage.

    - **User can move the request to next stage,**


      - *In The Action field is following to,*

        **1-[Complete](#complete-3)** -  complete the request and moved to [Complete](#complete-3) stage.

        **2-[ReCalculate](#clearance-process)** - User reject and return the request to [Clearance Process](#clearance-process) stage. for Recalculate the Clearance.

- ### **Client Rejection:**


     - Pending Requests are reject and moved to **Client Rejection** stage, and holding the request for review and **Resend for Client Confirmation** stage.

     - In Case and Task Management, Retirment Process will move to **Customer Rejection** stage.

    - **User can move the request to required stage**,

      - *In The Action field is following to,*

        **[Resend Customer Confirmation](#client_confirmation-1)** - User Resend the Request to Customer for [Client confirmation](#client_confirmation-1) stage.

- ### **Complete:**

     - Completed Request is moved to **"Complete"** Stage, After the **Final Settltment** process is completed.
     
     - And use to Track the status of Request.

    - Once Final Settlement is Completed, If Employee Requests for **"Travel Request"**, Then Travel request process will start to Employee once **Final Exit visa** process is completed.
    
    - And If Employee request in Retirement request for **"Travel"** Ticket, Then **Travel Ticket** process will start to Employee once **Final Exit visa** process is completed.

| [Home](#human-resource-management) | [Main](#employee-retirement) | [Back](#final-settlement) |

<br>
