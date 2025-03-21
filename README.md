<h1>Snort Challenge-Live Attack</h1>


<h2>Description</h2>
J&Y Enterprise is one of the top coffee retails in the world. They are known as tech-coffee shops and serve millions of coffee lover tech geeks and IT specialists every day. 
They are famous for specific coffee recipes for the IT community and unique names for these products. Their top five recipe names are;
WannaWhite, ZeroSleep, MacDown, BerryKeep and CryptoY.
J&Y's latest recipe, "Shot4J", attracted great attention at the global coffee festival. J&Y officials promised that the product will hit the stores in the coming months. 
The super-secret of this recipe is hidden in a digital safe. Attackers are after this recipe, and J&Y enterprises are having difficulties protecting their digital assets. 
Last week, they received multiple attacks and decided to work with you to help them improve their security level and protect their recipe secrets. Hours after starting shift, a brute-force attack is underway.

<h2>Task</h2>
Write an IPS rule and run Snort in IPS mode to stop the brute-force attack.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Command Line</b> 
- <b>Snort</b>

<h2>Environments Used </h2>

- <b>TryHackMe VM</b> 

<h2>Program walk-through:</h2>

<p align="center">
Configuration check: <br/>
<img width="1440" alt="Screenshot 2025-03-21 at 1 39 20 PM" src="https://github.com/user-attachments/assets/714d26a8-e57b-402a-9515-facfcc108bca" />

<br />
<br />
Display the TCP/IP output in the console. Logging output in Desktop directory:  <br/>
<img width="1440" alt="Screenshot 2025-03-21 at 1 48 53 PM" src="https://github.com/user-attachments/assets/1740b66f-5156-4af1-8388-748e30f282ff" />

<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
