# assignment2-PATI
# Usha reddy Pati
######  Favorite Place

My favorite place to buy food is : Hyderabad biryani
Hyderabad its is there in Telangana **Husen Sagar, Ramoji City are around it**Peaceful weather with **nice scenario** is also there.
***
### Route Map from Airport

1. The nearest airport is rajiv Gandhi International airport
2. It is in Hyderabad
3. Go right from the airport for 20kms
4. we will reach paradise signal
5. for right its paradise hotel to eat biryani

* Food Items
* Main Menu
    * Biryani
    * curries
    * Meals
* Starters
    * chiken lolipop
    * chiken popcorn
    * chiken drumsticks

 **[AboutMe Link](AboutMe.md)**

   ***
    ### Sports
    The table consists of details of 4 sports which I would like to recommed. It includes Sport name, location of sport and amount to be paid for the equipment

   |name|location|amount|
   |----|--------|------|
   |football|UAE|$20|
   |vollyball|hyderabad|$210|
   |trowball|khammam|$250|
   |cricket|USA|$20|

***
 ### pithy quotes

>Never let the fear of striking out keep you from playing the game.   -*Babe Ruth*


>Money and success don’t change people; they merely amplify what is already there.   -*Will Smith*

***

### Binary Exponentiation

In mathematics and computer programming, exponentiating by squaring is a general method for fast computation of large positive integer powers of a number, or more generally of an element of a semigroup, like a polynomial or a square matrix. Some variants are commonly referred to as square-and-multiply algorithms or binary exponentiation. These can be of quite general use, for example in modular arithmetic or powering of matrices. For semigroups for which additive notation is commonly used, like elliptic curves used in cryptography, this method is also referred to as double-and-add.

<https://en.wikipedia.org/wiki/Exponentiation_by_squaring>
```
long long binpow(long long a, long long b) {
    if (b == 0)
        return 1;
    long long res = binpow(a, b / 2);
    if (b % 2)
        return res * res * a;
    else
        return res * res;
}
```
<https://cp-algorithms.com/algebra/binary-exp.html>
