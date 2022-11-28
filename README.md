I have solved this problem with binary search whose steps are written below-

First we'll retrieve data from a given url with the help of request module in variable ‘p’.

Then we'll store the given location of the store in variables ‘initx, inity’.

Now, I have taken the value of latitude, longitude, and id in an array ‘arr’.

Then we’ll perform binary search in which l’ll take ‘mid’ as minimum of maximum distance covered by delivery agents (‘lo’ as lowest possible distance covered by delivery agents, and ‘hi’ as some maximum value).

We’ll check if it is possible to deliver all the orders by the delivery agents on covering that ‘mid’ distance.

If yes, then we’ll store the order in which delivery agents will do the deliveries in array ‘ans’ and try to minimise ‘mid’ by decreasing ‘hi’ value otherwise we’ll increase ‘mid’ by increasing ‘lo’.

At the end, we’ll print the ‘ans’ array.
