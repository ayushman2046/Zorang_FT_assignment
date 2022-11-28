I have solved this problem with binary search whose steps are written below-

1. First we'll retrieve data from a given url with the help of request module in variable ‘p’.

2. Then we'll store the given location of the store in variables ‘initx, inity’.

3. Now, I have taken the value of latitude, longitude, and id in an array ‘arr’.

4. Then we’ll perform binary search in which l’ll take ‘mid’ as minimum of maximum distance covered by delivery agents (‘lo’ as lowest possible distance covered by delivery agents, and ‘hi’ as some maximum value).

5. We’ll check if it is possible to deliver all the orders by the delivery agents on covering that ‘mid’ distance.

6. If yes, then we’ll store the order in which delivery agents will do the deliveries in array ‘ans’ and try to minimise ‘mid’ by decreasing ‘hi’ value otherwise we’ll increase ‘mid’ by increasing ‘lo’.

7. At the end, we’ll print the ‘ans’ array.
