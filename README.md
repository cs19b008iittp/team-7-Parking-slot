# team-7-Parking-slot
case study-1 team 7 : Teeam members
.CS19B004-GREESHMITHA : contributed on working out floor, customer ,and spots classes
.CS19B021 -HARSHITHA :contributed on working out display board method (displaying the no. free spots in each floor)
.CS19B008 -ROOPA SREE : contributed on working out farecontroller , entry and exit panels classes
.CS19BO33-SANDEEP : contributed nothing
-> description of each class 
classes description
1.	  Entry panel : here we take input of the  basic details like vehicle number,customers        
                                   Mobile number,assign him an id , and show him the free spots available 
                                   In each floor respectively based on the vehicle type he can select 
                                  Wherever he wants to park nearest to him.
2.	  Customer :  so in customer class we consider vehicle type and write functions to         
                                 Assign them and  here we can also see the number of hours the customer 
                                Customer parks his vehicle(outgoing time - incoming time).
3.	 Spot      :  * we take a note of timings when the vehicle is parked and also when the 
                               Vehicle is removed to calculate bill.
                             *we divide the each floor into 15 spots (5 small , 5 compact , 5 large)
                             *we consider 2 cases for the display method : 1.incoming (here if customer 
                              Wants to park his vehicle we will allot a nearest slot to him)
                              2.outgoing (if customer wants to leave then we will mark the place reserved 
                                For him as free for allocation for the next coming customers)
4.	Farecontoller: *here we calculate the bill based on number of hurs the vehicle has been 
                                   Parked ,and we if the vehicle type is electrical we consider an extra fare 
                            Of  rupees 10 or electricharge that is included in bill.
                             * we display the bill and we also provide the mode of payment like through 
                              Cash or even through credit card .
                            *in case of credit card we check whether the entered creit card is valid or not 
                            And return successful transaction incase of valid transaction or else it will 
                            Return try again , in case of cash it will show like this much of amount of bill is 
                            To be paid.
5.	Exit panel : here we show total bill paid , paid status , no.of parking hours, and ask for 
                    reviews.
6.	So this the basic layout of our program we have discussed all the possibilities and worked it out.
7.	We had 2 meetings extra other than the discussion during lab hours to sort out the things
8. running the program : .*open the parkingslot_wholeprogram.txt file .
                           *it is already verified in eclipse ide so just copy paste the code and run the main method  in any text editor 
                            *we have also  submitted the various classes as .txt files so incase of any doubts or any verification refer the seperate the classes submitted for 
                            more clarity .
