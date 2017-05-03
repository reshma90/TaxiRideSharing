# TaxiRideSharing
CS581 - Database Management Systems (Taxi Ride Sharing effects on New York Taxi Data)

Algorithm:

List all the trip requests for every pool of 5 mins.
Order the trip requests by the earliest arrival time and save it in a list (LT).
For every Taxi request(Tr) in the ordered list.
Calculate the angle between Tr with all the other trip requests.
Take the ones with angle <= 30°.
Check capacity constraint.
Order the trips according to the nearest drop off distance from the pickup point (hotspot).
Check delay constraint.
If satisfied for Tr , list all the probable candidates:{Candidate 1,Candidate 2, ……}.
Find candidate with minimum increase in total distance and assign a Taxi.
Remove the match from the ordered list (LT).
Goto step 3 and repeat the algorithm for rest of the requests.
