![RealFlightThings drawio](https://user-images.githubusercontent.com/10773482/193866560-a697f0d9-0db8-4112-9037-bb6c4433015e.png)

### Use the UML to answer the questions below in your main() method

-  Create 3 different type of FlightCrewJobs and name them flightCrewJob1, flightCrewJob2, and flightCrewJob3
-  Create 3 different CrewMembers but each MUST have a different job then name them crewMember1, crewMember2, crewMember3
-  Create two  tickets. one MUST be a Plane ticket and the other a Bus ticket
-  Create two passenger objects and name them passenger57 and passenger07
-  passenger57 should have only 3 luggages while passenger07 has only 2
-  Invoke the getAmtOfLuggage method on the passenger57 object. **Make sure you print out the result**
-  Invoke the printTicketMethod on passenger07
-  Invoke the serve method on crewMember3 and pass in passenger57
-  Invoke the printAmountForEachThingThatIsPayable method on all things that are Payable
-  Create a List of FlightCrewJobs and add 3 FlightCrewJobs to your List in this order. <flightCrewJob3, flightCrewJob1, flightCrewJob2>
-  Invoke  printEachFlightCrewJob method and pass in the List of FlightCrewJobs
-  Invoke the sortAndPrintFlightCrewJobsByJobTitle method with the same List of FlightCrewJobs
-  printAllFlightCrewJObsExceptThisCrewMemberJob method and pass in the same List of FlightCrewJobs as well as crewMember3.
>  PUSH TO GITHUB AND MAKE YOUR REPO PRIVATE. DM ME FOR A REVIEW!


### Facts
- crewMember1's salary is 100000.0, crewMember2's salary is 90000.0, crewMember3's salary is 70000.0
- PlaneTicket cost 100.0 while a BusTicket cost 50.0
- passenger57's crediCardLimit is 1000.0 cost while passenger07's is 800.0

## Expected output
3
======================
 Ticket Id: 2
 Origin: Brooklyn
 Destination: Germany
 seatNumber: 007A
 $50.0
======================
Now serving... Wesley Snipes
======================
100000.0
90000.0
70000.0
100.0
50.0
==========Before Sorting============
FLIGHT_ATTENDANT
PILOT
CO_PILOT
=============After Sorting==============
PILOT
CO_PILOT
FLIGHT_ATTENDANT
===========================
PILOT
CO_PILOT
