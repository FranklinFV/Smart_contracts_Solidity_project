# Smart Contracts - Solidity - Joint Savings Account
## By Franklin Vaca
<p>The program/code can be found in the joint_savings.sol file which was written using Remix IDE. 
The images that were included in this analysis that display the execution of the contract can be found in the Execution_Results folder.</p>
<p></p>

## **Application screenshot:**

*Overall screenshot* 

![image](Execution_Results/0_Overall.PNG)
<p></p><br>



<p>The contract was created and compiled. It compiled without any issues as indicated by the check mark next to the compiling icon (on the left). The contract was deployed and no errors were found.</p>

## **Interactions with the Deployed Smart Contract**

### **Setting Accounts**
*Accounts one and two were set:* 

![image](Execution_Results/1_Set_accts.PNG)
<p></p><br>


### **Contract's Deposit Functionality**
### **Transaction 1: Send 1 ether as wei.**
<p>The initial contract balance was zero.</p>

*Initial Contract balance:*

![image](Execution_Results/Trans_0_Initial_balance.PNG)
<p></p><br>


<p> 1 eth was deposited in the contract:</p>


![image](Execution_Results/Trans_1_Send_1_eth_a.PNG)
<p></p><br>

<p> new contract Balance (including 1 eth expressed in wei 1x10e18):</p>


![image](Execution_Results/Trans_1_Send_1_eth_b.PNG)
<p></p><br>


### **Transaction 2: Send 10 ether as wei.**

<p> 10 eth deposited in the contract:</p>

![image](Execution_Results/Trans_2_Send_10_eth_a.PNG)
<p></p><br>

<p> new contract Balance (including (10+1) = 11 eth expressed in wei 11x10e18):</p>


![image](Execution_Results/Trans_2_Send_10_eth_b.PNG)
<p></p><br>


### **Transaction 3: Send 5 ether as wei.**

<p> 5 eth deposited in the contract:</p>

![image](Execution_Results/Trans_3_Send_5_eth_a.PNG)
<p></p><br>

<p> new contract Balance:  (11+1  = 16 eth expressed in wei 16x10e18):</p>


![image](Execution_Results/Trans_3_Send_5_eth_b.PNG)
<p></p><br>



### **Contract's Withdrawal Functionality**
### **Transaction 4: Withdraw 5 ether into accountOne.**

<p> 5 eth sent into accountOne, as indicated by the new contract balance, lastToWithdraw and lastWithdrawAmount of the contract:</p>

![image](Execution_Results/Trans_4_Withdraw_5_eth_to_Acc_1_a.PNG)
<p></p><br>

<p> The new contract balance decreased from 16 eth (16x10e18 wei) to 11 eth. accountOne received those 5 eth as indicated by the last to Withdraw address and amount.</p>





### **Transaction 5: Withdraw 10 ether into accountTwo.**

<p> 10 eth sent into accountTwo as indicated by the new contract balance, lastToWithdraw and lastWithdrawAmount of the contract:</p>

![image](Execution_Results/Trans_5_Withdraw_10_eth_to_Acc_2_a.PNG)
<p></p><br>

<p> The new contract balance decreased from 11 eth to 1 eth. accountTwo received those 10 eth as indicated by the last to Withdraw address and amount.</p>


<p> The full screen images of each transaction were also included in the Execution_Results folder to show that no bugs/errors occurred while testing the functions of the contract.</p>