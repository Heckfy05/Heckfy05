### List of assets needed to run a typical website (LAMP/LEMP) in a private data center for one year
#### Facility rent:  
 To increase reliability next options are required: 
* Proper electricity supply with 2 independent sources and groundings 
* Ventilation and cooling sistems
* Fire detection, and alarm system, extinguishers
* Physical access control system with security alarm
* Checked load on the floor for future scalability
##### Estimated cost for rent facilities - 6 000 $/year

#### Equipment:
* Host server -1 000 $
* Storage * additional for RAID1 - 300 $
* Network (switch and cables) - 100 $
* BCP Backup power supply UPS ~ 1 000 $
##### Estimated cost for equipment - 2400$

#### Services:
* Domain registration - 50 $ 
* IP rent - 60 $/year 
* Equipment maintenance and administration - 1 000 $/year 
* ISP corporate plan*2 independent for backup - 1 200 $/year
* TLS certificate - 60 $/year
##### Estimated cost for services - 2370 $/year
---
#### Total Cost 10 770 $/year
The solution covers the main risks that could have an impact on business continuity. The final cost could be revised based on the risk assessment.
___
[AWS calculation](https://calculator.aws/#/estimate?id=aec9339179da2876eca6632c24f980a704660159) of the same solution shows total cost 830   and  200 $/year administration.
In general, we could conclude that for a low-loaded website to cover all the risks it is preferable to use AWS.