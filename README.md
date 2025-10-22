# DU-Item-Dispenser-screen
Screen for MyDU Item Dispensers  

Link a screen to the programming board and continue.  
Can also attach lights as well, will turn green if it contains items or red if empty.  

**Requirements**
Programming Board
At leats one screen
Can add lights and databank

**The Parameters:**  
Sale Header: Item name  
Sale Valume: How many items you want to sell in one batch. If 1, text will show Each, otherwise it will show Per ## that was specified.  
Tier: Tier of item, 1-5. This will adjust the text color of the Sale header as well as the craft section.  

Tired of people asking how many you can produce or how long it takes? Add information into the craft section, otherwise just put 0s.  

numberOfLines: Number of Production lines you are running for this item.  
craftDays: Number of days in 1 production line(if 0 it will not Days)  
craftHours: Number of hours in 1 production line  
craftMins: Number of minutess in 1 production line  
craftSecs: Number of seconds in 1 production line(if days is enabled this will not show)  

autoCalc: Default set to True. If you do not want the 5 above selections to auto-calculate how many you can make, uncheck it and enter a value in craftsPerDay  
craftsPerDay: Only used if the autoCalc is set to false.  

Supports all screen sizes.  

![examples](https://github.com/AnaneRex/DU-Item-Dispenser-screen/blob/main/examples.png)
