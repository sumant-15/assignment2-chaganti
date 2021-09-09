# Sumant Chaganti
###### florida

Florida is the southeasternmost U.S. state, with the Atlantic **on one side and the Gulf of Mexico on the other**. It has hundreds of miles of beaches.**Florida is world-renowned for its beach resorts**, amusement parks, warm and sunny climate, and nautical recreation; attractions such as Walt Disney World, the Kennedy Space Center


-------
# Directions from Maryville to Florida
1. Turn right at the 1st cross street onto Maryville Centre Dr
2. Keep right at the fork, follow signs for I-64 E/US-40 E/US-61 S/S Outer Forty and merge onto S Outer Forty Rd
   1. Merge onto US-27 S
   2. Turn left onto W Sun Pure Rd Street View
3. Use the left 2 lanes to merge onto I-64 E/US-40 E/US-61 S via the ramp to St Louis
4. Take exit 267A toward Tampa
5. Use any lane to merge onto I-4 W toward Tampa
6. Follow US-27 S to Pittsburg Rd
-----

* Turn right at the 1st cross street onto Maryville Centre Dr
* Keep right at the fork, follow signs for I-64 E/US-40 E/US-61 S/S Outer Forty and merge onto S Outer Forty Rd
     * Merge onto US-27 S
     * Turn left onto W Sun Pure Rd Street View
* Use the left 2 lanes to merge onto I-64 E/US-40 E/US-61 S via the ramp to St Louis
* Take exit 267A toward Tampa
* Use any lane to merge onto I-4 W toward Tampa
* Follow US-27 S to Pittsburg Rd

[AboutMe](https://github.com/sumant-15/assignment2-chaganti/blob/main/AboutMe.md)

-------

The table describes about the information about 4 food items like pizza,burger,salad,ice cream and the location where these 4 food items someone can buy and amount of money someone should expect to pay for the item

| food item | location | amount of money | 
| ----------| ---------| ----------------|
|   pizza   | Englewood|     10$         |
|   burger  | overland |     5$          |
|   salad   | leakwood |     4$          |
| ice cream | baker st |     2$          |

-------
# quotes
> We write to taste life twice, in the moment and in retrospect 
* Anaïs Nin
> If there's a book that you want to read, but it hasn't been written yet, then you must write it
* Toni Morrison

---------

# algorithm
> A modular multiplicative inverse of an integer a is an integer x such that a⋅x is congruent to 1 modular some modulus m. To write it in a formal way: we want to find an integer x so that

a⋅x≡1modm.
We will also denote x simply with a−1.

We should note that the modular inverse does not always exist. For example, let m=4, a=2. By checking all possible values modulo m is should become clear that we cannot find a−1 satisfying the above equation. It can be proven that the modular inverse exists if and only if a and m are relatively prime (i.e. gcd(a,m)=1)

<https://planetcalc.com/3311/>

```
int x, y;
int g = extended_euclidean(a, m, x, y);
if (g != 1) {
    cout << "No solution!";
}
else {
    x = (x % m + m) % m;
    cout << x << endl;
}
```
<https://cp-algorithms.com/algebra/module-inverse.html>




