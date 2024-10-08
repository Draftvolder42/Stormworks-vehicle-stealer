# [Stormworks vehicle stealer]
**Program for saving vehicles from multiplayer server in game [Stormworks](https://store.steampowered.com/app/573090/Stormworks_Build_and_Rescue/).**
### **[ABOUT PROGRAM]** ###
---
**$\textcolor{red}{\text{THIS PROGRAM IS MADE TO DEMONSTRATE THE CURRENT GAME}}$**
**$\textcolor{red}{\text{VULNERABILITY TO THE GAME DEVELOPERS AND TO DRAFT THEIR}}$**
**$\textcolor{red}{\text{ATTENTION TO THE PROBLEM.}}$**
---
### This program uses memory replacement using pymem to activate the save world button in multiplayer mode. ###
### Next, the program can restore some file structure of the saved world and make changes to scene.xml for further spawning of vehicles and their theft. ###
---
![alt text](img/image5.png)

### **[ Options ]**

This program makes a new save with vehicles that spawned above the start Island in coordinates 0, 0.

<ul>
<li><h3>1. ''Open save menu'' switch button.</h3> - This button switch the save menu.</li>
</ul>

![alt text](img/image.png)

<ul>
<li><h3>1. ''Save vehicle from last save'' button.</h3> - This button makes world with spawned vehicles from last saved world (<b>The last world must be saved by this program</b>).</li>
</ul>

![alt text](img/image2.png)

<ul>
<li><h3>1. ''Save vehicle from selected save'' button.</h3> - This button makes world with spawned vehicles from selected world (<b>The selected world must be saved by this program</b>).</li>
</ul>

![alt text](img/image3.png)

<ul>
<li><h3>1. ''Change saves folder'' button.</h3> - This button Change saves folder of Stormworks (<b>This folder is detected automatically</b> you can see it in "Saves folder" field).</li>
</ul>

![alt text](img/image4.png)

### **[WARNING]** ###
This program can create additional file and directory (```Roaming\xml_stealer\xml_stealer.cfg```).

### P.S. ###
<p>A possible solution to the problem for developers, in my opinion, is to remove the ability to save the world in multiplayer programmatically.</p>
