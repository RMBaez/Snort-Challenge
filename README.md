<h1>Snort Challenge-Live Attack</h1>


<h2>Description</h2>
J&Y Enterprise is one of the top coffee retails in the world. They are known as tech-coffee shops and serve millions of coffee lover tech geeks and IT specialists every day. 
They are famous for specific coffee recipes for the IT community and unique names for these products. Their top five recipe names are;
WannaWhite, ZeroSleep, MacDown, BerryKeep and CryptoY.
J&Y's latest recipe, "Shot4J", attracted great attention at the global coffee festival. J&Y officials promised that the product will hit the stores in the coming months. 
The super-secret of this recipe is hidden in a digital safe. Attackers are after this recipe, and J&Y enterprises are having difficulties protecting their digital assets. 
Last week, they received multiple attacks and decided to work with you to help them improve their security level and protect their recipe secrets. Hours after starting shift, a brute-force attack is underway.

<h2>Task</h2>

- <b>Figure out the attack source, service and port</b>
- <b>Write an IPS rule and run Snort in IPS mode to stop the brute-force attack. Once you stop the attack properly, you will have the flag on the desktop. </b>


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
Entered command observing ssh exploit: <br/>
<img width="1440" alt="Screenshot 2025-03-21 at 2 12 48 PM" src="https://github.com/user-attachments/assets/b2ba9338-9872-4e4d-a7b4-3c29d714cdd0" />
<img width="1440" alt="Screenshot 2025-03-21 at 2 07 17 PM" src="https://github.com/user-attachments/assets/d887c794-c40d-4392-aa78-15fc5cecee89" />
<img width="1440" alt="Screenshot 2025-03-21 at 2 13 43 PM" src="https://github.com/user-attachments/assets/ea529d8f-dc75-4074-9434-b678d2232269" />


<br />
<br />
Creating Snort rule:  <br/>
<img width="1440" alt="Screenshot 2025-03-21 at 2 17 18 PM" src="https://github.com/user-attachments/assets/fe28e8c4-c7de-4f9c-bc26-38ddc3610e73" />
<img width="1440" alt="Screenshot 2025-03-21 at 2 29 01 PM" src="https://github.com/user-attachments/assets/7bb6cdbe-1fa1-4227-a0e3-5884b4c8aade" />


<br />
<br />
IPS mode and dropping packets:  <br/>
<img width="1440" alt="Screenshot 2025-03-21 at 2 34 15 PM" src="https://github.com/user-attachments/assets/153c8ed7-2a75-4907-be23-39458fe18c07" />

<br />
<br />
Waiting for process to complete (may take some time). Receiving acknowledgment of task completion:  <br/>
<img width="1440" alt="Screenshot 2025-03-21 at 2 34 48 PM" src="https://github.com/user-attachments/assets/81531b5d-e874-4c3a-91d3-3814f669ac29" />

