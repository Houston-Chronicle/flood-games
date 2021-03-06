# Flood Games 
Officials in Houston and across the country are failing to enforce a central pillar of the taxpayer-subsidized National Flood Insurance Program: [Making sure severely damaged properties are elevated or removed from flood plains.](https://www.houstonchronicle.com/business/article/Flood-Games-How-victims-local-officials-and-an-13031069.php)  

Thousands of such homes get rebuilt and then flood again, often for more than they are worth, costing taxpayers more than $1 billion in repeat losses.  

The deeply indebted program is set to lapse July 31 without congressional reauthorization, and lawmakers have put forward a host of potential reforms to tie to that vote, but none directly address the costly problem of poorly enforced elevation requirements.  

Using FEMA data on repetitive loss, the Houston Chronicle identified thousands of losses that could have been avoided if the NFIP's requirements were followed.     
## What we were looking for? 

The goal was to determine which of the most repetitively flooded properties had been paid building damage claims worth more than 50 percent of the building's value, and then went on to flood again. Under the operating principles of the flood insurance program, such buildings should have been elevated or removed from the flood plain after the first instance of substantial damage, and therefore should have had fewer or less severe subsequent claims.   

## How did we do it? 
The Chronicle considered a building to have evidence of substantial damage if all of the following conditions were met: The property was in an "A," "V," or "EMG" flood zone when the claim was made, the amount of money paid to the claimant for building damage was 50 percent or more of the building's value, and the building had not been paid a damage claim that exceeded the building value supplied by FEMA. (Such instances suggest either that the claim payment was too high or that the supplied building value is too low to be accurate.) FEMA's building values are derived from insurance adjusters who inspected the properties. They may vary from the values used by local officials in determining substantial damage.  

The Chronicle did substantial clean up work on the raw files before we got to this point. We'll add how we did the clean up to this repository soon.

## Are there limits to this analysis? 
The analysis likely undercounts the lack of substantial damage enforcement because:

*The data is limited to the universe of severe repeat loss properties and therefore captures a fraction of properties that have been substantially damaged.  

*Many flooded properties do not carry flood insurance and therefore do not appear in databases of insurance claims, but are still required to adhere to substantial damage rules. For example, about 70 to 80 percent of Harvey victims did not have insurance, according to the Consumer Federation of America, CoreLogic, and government estimates. But in Houston, which participates in the flood insurance program, they would still have to meet elevation requirements.      

*Properties in the database that were substantially damaged one time may have flooded again, but those subsequent losses may not appear in the database if the building owner did not continue to carry insurance.   

*Some communities choose to set a lower bar for substantial damage, meaning that properties with less than 50 percent damage could get the designation. Or they may count substantial damage cumulatively across multiple floods, so that a home with 10 percent damage in one flood and 40 percent damage in the next flood reaches the substantial damage threshold. The analysis does not capture these instances. 

## Contributors and Sources 
Reporter Mark Collette did the data clean up and analysis for this project. Data editor Matt Dempsey checked the analysis used in the story and helped set up this repository. Source of the data is the Federal Emergency Management Agency. Chronicle staff removed addresses if FEMA accidentally included them. 
