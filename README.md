![](images/0-ctd-banner.png)
## Digital Assistant - Building a Digital Assistant for your business ##

In this lab, you'll learn how to work with skills and digital assistants in Oracle Digital Assistant;
-	A **skill** is an individual chatbot that is focused on a specific set of capabilities (e.g. helping customers order food from a specific restaurant).
- **A digital assistant** is a master chatbot containing multiple specialized skills. When a user engages with the digital assistant, the digital assistant evaluates the user input and routes the conversation to the appropriate skill. You can populate your digital assistant with skills from the Skill Store and with skills you have designed yourself.

## Before you start ##

To complete this lab you need to;

- Download these files
  - [PizzaSkill_starter.zip](https://github.com/KaddeOucif/CTD-Digital-Assistant/blob/master/files/PizzaSkill_starter.zip?raw=true)
  - [PizzaSkill_BotML.json](https://github.com/KaddeOucif/CTD-Digital-Assistant/blob/master/files/PizzaSkill_BotML.json?raw=true)
  - [ODA_HOL2019](https://github.com/KaddeOucif/CTD-Digital-Assistant/blob/master/files/ODA_HOL2019.zip?raw=true)
  - <details><summary> <b>Optional: Download NodeJS & the Web Client SDK to host your Digital Assistant in your machine</b> </summary>      <a href="https://nodejs.org/en/download/">Download NodeJS here</a> <br>
     <a href="http://bit.ly/amcedownloads">Download the Web Client SDK here</a> <br>
     <img src="/images/0.1-oda-sample-download.png">
     </details>
 
## Get on crackin'! ##
### Clone the skill ###

1. With the Oracle Digital Assistant UI open in your browser, click ![](images/1-hamburger-menu.png) main menu icon to open the side menu.
2. Click **Development** and select **Skills**.
3. Click ![](images/1-hamburger-menu.png) again to collapse side menu.
4. In the skills dashboard, find the tile for **PizzaSkill**.
5. Click PizzaSkill's **Options** menu (![](images/2-options-menu.png)) and select **Clone**.
6. In the **Create Clone** dialog, enter a value for **Display Name** using the form *<your_initials>_PizzaSkill*.
For example, if your initials are AB, you'd name the skill **AB_PizzaSkill**.
7. On the Skills dashboard page, select *<your_initials>_PizzaSkill* to open it up in the designer.
