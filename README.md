# AUTONUMERIC-ACCORDING-A-ATRIBUTE-DTM

The output of Mineable Shape Optimizer(MSO) give us stopes with a STOPENUM atribute as code of them. In the practices a Planning - Mining Engineer only select a part of all stopes to evaluate reserves, in this point the engineer needs to sort the selected stopes in a order, easer to report. This Java code attemp to give ordered atribute according with a other atribute that identify the interesting zone. 

# OVERVIEW

 . Insight of output of MSO.
 
 . Issue of STOPENUM in a interesting zone.
 
 . Script View in Datamine Software
 
 . Comparation between before and after stope identification.
 
 # INSIGHT OF OUTPUT OF MSO
 
 Mineable Shape Optimizer allow join many block into a stopes that accomplish the cut off. Theses Stopes have measures according to given setup previously.
 
![image](https://user-images.githubusercontent.com/67855447/120093694-7ea74c80-c0e1-11eb-928c-c2901fbfce98.png)
#####  NOTE: THOSES NUMBERS IDENTIFY THE STOPENUM OF EACH STOPES

 # ISSUE OF STOPENUM IN A INTERESTING ZONE

To report reserve, mining engineer needs to give a code each stope accomplish a numeric order of interesting zone. The STOPENUM CODE doesn't this requirement because of STOPENUM identify all stopes and not the interesting zone.

![image](https://user-images.githubusercontent.com/67855447/120093725-a8607380-c0e1-11eb-8d25-e267093882c3.png)

# SCRIPT VIEW IN DATAMINE SOFTWARE

According the style we code in our code file(SCRIPT ORDEN), give a interface where we setup our input and names of columns we want to add and the column we reference to autonumeric.

![image](https://user-images.githubusercontent.com/67855447/120093643-3e47ce80-c0e1-11eb-9c6e-89b93d0135cd.png)






