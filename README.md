# 10910EECS204001-Data-Structure-HW4-Cheapest-Flights
10910EECS204001 Data Structure HW4-Cheapest Flights

**Download Link:https://programming.engineering/product/10910eecs204001-data-structure-hw4-cheapest-flights/**

Description
5/5 – (2 votes)
There are n cities connected by m flights. Each flight starts from city u and arrives at v with a price p. Several airliners provide the service for the cities, and there may be multiple flights operated by different airliners between the same pair of cities, also there may be multiple flights operated by same airliner between the same pair of cities.

Now given all the cities and flights, together with the starting city src and the destination dst, your task is to find the lowest cost from src to dst with up to cost w. If there is no such a route, output -1.

Note that you need to pay 5 more units of price for each transfer of flights with different airlines at one city (see the example below).

You should implement:

1. Add u v p a: Add a flight, which goes from u to v with cost p operated by airline a.

2. Delete u v a: Delete all the flights from u to v operated by airline a.

3. Request src dst w: A person wishes to book a ticket from src to dst with the overall cost at most w. Print the lowest cost from src to dst with up to cost w. If there is no such a route, output -1.

Input:

1. First line of input: n (number of cities)

2. Other line: instructions Add, Delete, Request

Note:

n (number of cities): Integer, 0<n<=100

City’s ID starts from 0

m (number of flights): integer, 0<m<=100000

p (cost of each flight): integer, 0<p<=100

a (number of airlines): integer, 0<a<=10

Output:

For instruction Request, print the lowest-cost route from src to dst with up to cost w. If there is no such a route, output -1. Each line ends with a newline character.

Sample I/O:

Input

3

Add 0 1 4 0

Add 1 2 8 0

Add 1 2 5 1

Request 0 2 20

Request 0 2 10

Delete 1 2 0

Request 0 2 20

Output

12

-1

14

Notice:

Your code needs to be submitted to NTHU OJ and iLMS before the deadline.

Please zip your code as studentID.zip and submit to iLMS HW4.(eg, 108062568.zip)

