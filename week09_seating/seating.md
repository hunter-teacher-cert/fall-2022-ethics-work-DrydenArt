## From Slack: 
- Q: What are ethical issues for this?
- Q: How might a ticketing policy like this pose questionable ethics?

Some possible ethical concerns:
passenger with:
an infant/small child
physical disabilities
exit row (maybe beyond the scope of this exercise)
service animal

## ***from Sueanne on Slack:*** 

- Creates a plane using a list on row, cols
- Allows economy_plus to choose and window seat or another available seat
- Economy seat is chosen for you
- If there are no more seats available the plane is full

## ***My pseudo code for the algorithm:***

When purchasing economy, for each ticket the algorithm is designed to ask:
+ Traveler age on date of travel:
  
  + if 16 years or older:
    + are you traveling with someone 15 years or younger?
      + if yes:
        + allow to be seated together and avoid exit row
  + if 15 years or younger and traveling alone:
    +  allow no exit row
          
  + are you traveling with someone with accessibility needs?
      + if yes:
        + allow to avoid exit row, allow to be seated with group, allow to choose seats based on accessibility needs. 
    
+ Do you have accessibility needs?
  + if yes:
    + allow to avoid exit row and/or allow to be seated with a group member/care giver, allow to choose seat based on accessibility needs.

## ***Some issues I can think of with this algorithm:***
+ People who don't need these services, and don't want to pay extra money will lie and take away flexibility from those who ***really*** need these options.
+ In cases of accessibility, if passengers need to produce medical notes to prove they need these options, it can create barriers to those trying to purchase tickets.  It may cause them to not follow through on the purchase, or, due to more time needed to complete the process, may lose access to the available seat.
+ The same could be true for families trying to purchase tickets together.  

