# team-7-Parking-slot
case study-1 team 7 : Teeam members
.CS19B004-GREESHMITHA : contributed on working out floor, customer ,and spots classes
.CS19B021 -HARSHITHA :contributed on working out display board method (displaying the no. free spots in each floor)
.CS19B008 -ROOPA SREE : contributed on working out farecontroller , entry and exit panels classes
.CS19BO33-SANDEEP : contributed nothing
CS19B032 -CHARAN  : contributed in giving ideas 
-> description of each class 
1.	  Customer :           .customer id
                           .set vehicle size
                            .set spottype
                            .get the number of parking hours
                            .assign a ticket to customer
2.	 Spot      :            .set reserved status
                             .return spotsize and spotype 
3.	Farecontoller:           *this is implemeted in floor class and this is displayed when the vehicle is about to exit.
                              *here we calculate the bill based on number of hurs the vehicle has been 
                                   Parked ,and we if the vehicle type is electrical we consider an extra fare 
                                Of  rupees 10 or electricharge that is included in bill.
4. Floor      :             . *we divide the each floor into 15 spots (5 small , 5 compact , 5 large)
                             *we consider 2 cases for the display method : 1.incoming (here if customer 
                              Wants to park his vehicle we will allot a nearest slot to him)
                              2.outgoing (if customer wants to leave then we will mark the place reserved 
                                For him as free for allocation for the next coming customers)
                              *display bill
                              * display number of free spots in each floor.                             
5.	So this the basic layout of our program we have discussed all the possibilities and worked it out.
6.	We had 2 meetings extra other than the discussion during lab hours to sort out the things
7. running the program : .*open the parkingslot_wholeprogram.txt file .
                           *it is already verified in eclipse ide so just copy paste the code and run the main method  in any text editor 
                            *we have also  submitted the various classes as .txt files so incase of any doubts or any verification refer the seperate the classes submitted for 
                            more clarity .
