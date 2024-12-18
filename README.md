<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
<p>This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.</p>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating Systems Used</h2>
<ul>
  <li>Windows 10 (21H2)</li>
</ul>

<h2>List of Prerequisites</h2>
<ul>
  <li>Azure Virtual Machine with Windows 10</li>
  <li>PHP Manager for IIS</li>
  <li>Rewrite Module</li>
  <li>PHP 7.3.8</li>
  <li>Visual C++ Redistributable</li>
  <li>MySQL 5.5.62</li>
  <li>osTicket v1.15.8</li>
  <li>HeidiSQL</li>
</ul>

<h2>Installation Steps</h2>

### Step 1: Prepare the Virtual Machine
<p>

https://github.com/user-attachments/assets/194b5916-6569-4b22-8016-1261cf50d938

</a>

### Step 2: Enable Internet Information Services with CGI - World Wide Web Services -> Application Development Features -> [X] CGI
<p>


https://github.com/user-attachments/assets/c5fe2561-1b40-455a-aae8-285e366c68a1


</a>

### Step 3: Install Required Software
<p>




https://github.com/user-attachments/assets/15f1e7ae-14d7-485a-8332-50fc1fcef7a2






</a>

### Step 4: Configure IIS
<p>
To avoid errors, it's always recommended to double-check if the rewrite module in IIS is installed, otherwise the localhost will display a config error.
  


https://github.com/user-attachments/assets/3a775a91-0cd9-4c12-91fd-5a87d3709eb3


</a>

### Step 5: Install osTicket
<p>


https://github.com/user-attachments/assets/afdba66a-19e2-469b-a3ec-5eccd71337b6



</a>

### Step 6: Finalize osTicket Configuration
<p>





https://github.com/user-attachments/assets/1284418a-54e4-4e62-bb44-f02de9b05e3c






</a>

### Step 7: Configure Database
<p>
1. Use HeidiSQL to create a new database named `osTicket`.
  
2. Enter database details during the osTicket setup: Database Name `osTicket`, Username `root`, Password `root`.
 
3. Click *Install Now!*
   
NOTE: Always make sure MySQL is installed and set with a standard configuration that has credentials so that it can communicate with HeidiSQL.



https://github.com/user-attachments/assets/0c280301-fba4-44cf-b13b-321ad920214f






</a>

<h2>Accessing osTicket</h2>
<ul>
  <li>Admin Panel: <a href="http://localhost/osTicket/scp/login.php" target="_blank">http://localhost/osTicket/scp/login.php</a> 🛠️</li>
  <li>End User Portal: <a href="http://localhost/osTicket/" target="_blank">http://localhost/osTicket/</a> 🌟</li>
</ul>

<h2>Conclusion 🎉</h2>
<p>
Congratulations! You have successfully installed and configured osTicket. With this powerful help desk tool, you can efficiently manage support tickets and improve customer service workflows. Happy troubleshooting! 🚀
</p>
