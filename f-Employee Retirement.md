
# **[Employee Retirement](#human-resource-management)**

| [Retirement Request](#retirement-request) | [Final Settlement](#final-settlement) |


<br>


> ## **[Retirement Request:](#employee-retirement)**

<br>


- The Retirement request is initiated from case and task management.

- Employee Should not be pending in Vacation or Retirement process.

- If employee have ERP access, it should deactivate before request.

- Employee should not in Outside Kingdom.

- Employee should not be Iqama Renewal Process.

- **(Employee Status will change based on EOS Category:**

    - **--If Category is End of Service, employee status will change as "Terminated".**

   - **--If Category is Escaped, employee status will change as "Terminated_Escaped".**

   - **--If Category is Transferred, employee status will change as "Transferred".**

   - **--If Category is LeftNotReturn, employee status will change as "Terminated_LeftNotReturn".**

   - **--If Category is Dead, employee status will change as "  ".)**

* ### _Mandatory field to update while request for Retirment:_

    **1- Labour ID,**

    - Unique Identification Number provided by organization to Employee.

    **2- Request Date,**

    - Required the Date of Retirement Request for Vacation.

    **3- Expected Date of Leaving,**

    - Expected Date of Leaving from Organization.

    **4- EOS Category,**

   - _End of Service,_
   - _Escaped,_
   - _Deport,_
   - _Transfered,_
   - _Left Not Return,_
   - _Dead._

   **5- Settlement Paid by,**

     * Settlement is optional to receive-

       - _ARCO_ -
       - _Customer_ -

   **6- Need Settlement,**

   - Settlement is Settle from Organization in Employee Retirement to Employee.

   **7- Need Travel Arrangements,**

   - Travel is Optional to request from Organization in the Retirement to Employee.

   **8- Need Exit,**

   - Final Exit Visa is Afford from Organization in the Retirement to Employee.

   **9- Need Clearance,**

  - Clearance is Optional to request from Organization in the Retirement process.



*

| [New Request](#new-request) > [Arco Approval](#arco-approval-1) > [Customer Approval](#customer-approval-1) > [Under Processing](#under-processing-2) > [Customer Clearance](#customer-clearance-1) > [Arco Clearance](#arco-clearance-1) > [Waiting for Travel](#waiting-for-travel-1) > [RejectedRequest](#rejectedrequest) > [Complete](#complete-4) |

<br>

- ### **New Request:**

    - New request created and initiated in case and task management, and then it will moved to ARCO Approval from case and task management.

    - Initiated New request is received from Case and task management for Retirement.

      - *In The Action field is following to,*

        **1-[Complete](#arco-approval-1)** - User Complete the Request and refer to [Arco Approval](#arco-approval-1) stage.


- ### **Arco Approval:**

    -  In this stage, Waiting for get ARCO approval for Employee Retirement. once Arco Approval is completed, then request moved to Customer Approval stage.

    - In Case and Task Management, Retirement Process will move to Customer Approval stage, Customer or User will Approve from Case and Task Management, Once Approved in Case and Task Management, it will moved to UnderProcessing Stage.

       - *In The Action field is following to,*

         **1-[Complete](#customer-approval-1)** - User Complete the Request in this Arco Approval stage and then refer to [Customer Approval](#customer-approval-1) Stage.

         **2-[Reject](#rejectedrequest)** - User Reject the request and moved to [Rejected Request](#rejectedrequest) stage.

- ### **Customer Approval:**

    - In this stage, Waiting for Customer Approval to process Retirement. Once the Customer Approved, then moved to under processing stage.

    - In Case and Task Management, Retirement Process will move to Customer Approval stage, Customer or User will Approve from Case and Task Management, Once Approved in Case and Task Management, it will moved to UnderProcessing Stage.

      - *In The Action field is following to,*

        **1-[Reject](#rejectedrequest)** - User Reject complete the request and refer to [RejectedRequest](#rejectedrequest) stage.

        **2-[Complete](#under-processing-2)** - User Complete the request and refer to [Under Processing](#under-processing-2) Stage.

- ### **Under Processing:**

    - The Final Settlement process will create and begins from this **Under Processing** stage with System Integration. when the customer request the Retirement request in Case and Task Management.

    - If the employee request, for Visa and travel from ARCO, and then Visa and Travel process will start for the employee from this stage with system integration.

    - If the Employee not requested for Visa and Travel from ARCO, Then it will moved directly to **Waiting for travel** stage.


       - *In The Action field is following to,*

         **1-[Reject](#rejectedrequest)** - User reject the request and moved to [RejectedRequest](#rejectedrequest) stage.

         **2-[Complete](#customer-clearance-1)** - User complete the requsest and then refer to [Customer Clearance](#customer-clearance-1) stage.



- ### **Customer Clearance:**

     - In this stage, Waiting for Customer Clerance, once clearance is completed by Customer then it will send for ARCO Clearance stage.

     -   In Case and Task Management, Retirement Process will move to Customer Confirmation stage, Customer or User will Approve from Case Management, Once Approved in Case Management, it will moved to Approved for payment Stage.

    - Customer Clearance is optional for employee, and it will process only who requested the Clearance for settlement in Case and task management. Otherwise this clearance stage will be skipped and moved to completed stage.


       - *In The Action field is following to,*

         **1-[Complete](#arco-clearance-1)** - User complete and refer the request to [Arco Clearance](#arco-clearance-1) stage.

         **2-[Reject](#rejectedrequest)** - User Reject the request to [RejectedRequest](#rejectedrequest) stage.

- ### **Arco Clearance:**

  - In this stage, Waiting For ARCO clearance for Retirement, once the ARCO clearance is completed then it will send for Waiting for travel stage.

  -  In Case and Task Management, Retirement Process will move to Approved for Payment stage, User will Approve from Finance Department, Once Approved in Finance Department, it will moved to Visa Issuance Stage in Case and Task Management.


   - ARCO Clearance is optional for employee, it will process only who requested the Clearance for settlement in Case and task management. Otherwise this clearance stage will be skipped and moved completed stage.

       - *In the Action field is Following to,*

          **1-[Complete](#waiting-for-travel-1)** -  User complete the request and refer to [Waiting for Travel](#waiting-for-travel-1) stage.

          **2-[Reject](#rejectedrequest)** - User reject and complete the request to [Rejected request](#rejectedrequest) stage.

- ### **Waiting for Travel:**

    - If Employee went on Vacation, Muqueem Status will change as OutSideKingdom in Muqueem Portal.

   - By system schedule will check if muqueem status is Terminated-OutSideKingdom, and Complete the Retirment Process with Travel Date.

      - *In the Action field is Following to,*

        **1-[Complete](#complete-4)** - User complete the request and then refer to [Complete](#complete-4) stage.

        **2-[Reject](#rejectedrequest)** - User Reject and complete the request then moved to [Rejected Request](#rejectedrequest) stage.

- ### **RejectedRequest:**

    - In this stage, rejected request is moved to **"complete"** the stage.

       - *In the Action field is Following to,*

          **1-Reject** - reject the request and moved to **"Complete"** stage.

- ### **Complete:**

     - Completed request is moved to this **"complete"** stage. and use this date for track the status of request.

     - Retirement process will complete with **"Final Exit Visa**" and **"Final Settlement"** for Employee.

| [Home](#human-resource-management) | [Main](#employee-retirement) | [Back](#retirement-request) |



<br>

> ## **[Final Settlement](#employee-retirement):**

Final settlement is initiated by user or customer from case and Task management, and then payment is completes in Finance portal. once the payment is completed in finance portal. then settlement process will be complete.


| [Requested](#requested-4)  > [Clearance Process](#clearance-process) > [Approval](#approval-3) > [Client _ Confirmation](#client_confirmation-1) > [Payment](#payment-3) > [Client Rejection](#client-rejection-1) > [Complete](#complete-3) |

<br>

- ### **Requested:**

    - New request initiated by user or customer from case and task management. and then that Request is waiting for Action,

    - Retirement Process will move to Finance Approval stage in Case and Task Management.

        - *In The Action field is following to,*

           **1-[Move to Clearance](#clearance-process)** - User complete the request and *refer for [Clearance process](#clearance-process) stage.

- ### **Clearance Process:**

    - In this stage, Clearance Process will start for employee in Clearance Module, once clearance completed then it will send Approval to Finance Department Approval.

      - *In The Action field is following to,*

          **1-[Complete](#approval-3)** - User complete the request and refer to [Approval](#approval-3) stage. for **Final Settlement** Clearance.

- ### **Approval:**

     - In this stage, Waiting for Finance Approval from Finanace Department for **Final Settlement**. after Finance Department approved, then user complete the request.

     - If do not have any Final Settlement payment for Employee, then the request complete with **Move without Payment**.

        - *In The Action field is following to,*

          **1-[Complete](#client_confirmation-1)** - Complete this request and moved For [Client_Confirmation](#client_confirmation-1) stage.

           **2-[Re Calculate Clearance](#clearance-process)** - User reject and return the request [Clearance Process](#clearance-process) stage. for Re Calculate Clearance amount.

           **3-[Move Without Payment](#complete-3)** - User complete this request and **Move Without Payment** to [Complete](#complete-3) Stage.

- ### **Client_Confirmation:**

    - Retirement Process will move to Client Confirmation stage in Case and Task Management, Customer or User will Approve from Case and Task Management.

    -  Once Approved in Case and Task Management, then it will moved to Payment Stage.


       - *In The Action field is following to,*

         **1-[Confirm](#payment-3)** - User Complete the request and refer to the [Payment](#payment-3) stage.

         **2-[Move to Clearance](#clearance-process)** - User complete and refer the request to [Clearance Process](#clearance-process) stage. for Recalculate the clearance.

- ### **Payment:**

   - In Case and Task Management, Retirement Process will move to Approval For Payment stage.

    - In this stage, waiting for complete the payment in Finance Department, Once payment is Completed in Finance Department, then it will moved to completed stage.

    - After payment is completed in Finance Department, then request moved to **Completed** stage.


      - *In The Action field is following to,*

        **1-[Complete](#complete-3)** -  complete the request and moved to [Complete](#complete-3) stage.

        **2-[ReCalculate](#clearance-process)** - User reject and return the request to [Clearance Process](#clearance-process) stage. for Recalculate the Clearance.

- ### **Client Rejection:**

     - In Case and Task Management, Retirement Process will move to Customer Rejection stage.

    - Rejeceted Request by Client is moved to this stage, and waiting for resend to customer confirmation.

      - *In The Action field is following to,*

        **[Resend Customer Confirmation](#client_confirmation-1)** - User Resend the Request to Customer for [Client confirmation](#client_confirmation-1) stage.

- ### **Complete:**

     - Completed Request is moved to **"Complete"** Stage, After the Final Settltment process is completed. for use and track the status of request.

    - Once Settlement Completed, if Employee request in Retirement request for **"Visa"**, then Visa process will start for Employee.
    
    - And If Employee request in Retirement request for **"Travel"** Ticket, then Travel Ticket process will start for Employee.

| [Home](#human-resource-management) | [Main](#employee-retirement) | [Back](#final-settlement) |

<br>
