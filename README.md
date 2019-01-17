# puzzles

## Puzzle 1 | (How to Measure 45 minutes using two identical wires?)

How do we measure forty-five minutes using two identical wires, each of which takes an hour to burn. We have matchsticks with us. The wires burn non-uniformly. So, for example, the two halves of a wire might burn in 10 minute and 50 minutes respectively

Answer:
Light up three of the four ends of the two wires. Once one wire is completely burnt, light up the fourth end. At 45 minutes, both wires are burnt completely.

## Puzzle 2 | (Find ages of daughters)

Alok has three daughters. His friend Shyam wants to know the ages of his daughters. Alok gives him first hint.
1) The product of their ages is 72.

Shyam says this is not enough information Alok gives him a second hint.

2) The sum of their ages is equal to my house number.

Shyam goes out and look at the house number and tells “I still do not have enough information to determine the ages”.

Alok admits that Shyam can not guess and gives him the third hint

3) The oldest of the girls likes strawberry ice-cream.

Shyam is able to guess after the third hint. Can you guess what are the ages of three daughters?

Answer:
1) Product of ages is 72

Below are all possibilities to get 72 from product of three different ages:

1 * 1 * 72 = 72
1 * 2 * 36 = 72
1 * 3 * 24 = 72
1 * 4 * 18 = 72
1 * 6 * 12 = 72
1 * 8 * 9 = 72
2 * 2 * 18 = 72
2 * 3 * 12 = 72
2 * 4 * 9 = 72
2 * 6 * 6 = 72
3 * 3 * 8 = 72
3 * 4 * 6 = 72

2) Sum of the ages is given

1 + 1 + 72 = 74
1 + 2 + 36 = 39
1 + 3 + 24 = 28
1 + 4 + 18 = 23
1 + 6 + 12 = 19
1 + 8 + 9 = 18
2 + 2 + 18 = 22
2 + 3 + 12 = 17
2 + 4 + 9 = 15
2 + 6 + 6 = 14
3 + 3 + 8 = 14
3 + 4 + 6 = 13

All sums are unique except 14. So the age sum must have been 14, otherwise Shyam would have guessed the ages from hint 1 only.

So we have two possible combination to get sum 14

2 + 6 + 6 = 14
3 + 3 + 8 = 14

3) Alok has an oldest girl (not two!!). So the ages must be 3, 3 and 8.

## Puzzle 3 | (Calculate total distance travelled by bee)

Two trains are on same track and they are coming toward each other. The speed of first train is 50 KMs/h and the speed of second train is 70 KMs/h. A bee starts flying between the trains when the distance between two trains is 100 KMs. The bee first flies from first train to second train. Once it reaches the second train, it immediately flies back to the second train... and so on until trains collide. Calculate the total distance traveled by the bee. Speed of bee is 80 KMs/h.

Solution:
Let the first train moves at u km/h
second train moves at v km/h

distance betweem trains be d km
speed of bee is b km/h

time taken by trains to collide,t = d/(u+v)

distance travelled by bee in time t = b*t = 80 * (100/(50+70)) = 66.67(approx.)

## Puzzle 4 | (Pay an employee using a 7 units gold rod?)

An employee works for an employer for 7 days. The employer has a gold rod of 7 units. How does the employer pays to the employee so that the employee gets 1 unit at the end of everyday. The employer can make at most 2 cuts in rod.

Solution:
Employer can pay for seven days by making 2 cuts in a way that he has 3 rods of size 1, 2 and 4.

1st Day: Employer gives 1 unit cut.
2nd day: Takes back 1 unit cut from employee given on first day and gives 2 unit cut.
3rd Day: Gives both 1 unit and 2 unit cuts.
4th Day: Takes back cuts of 1 and 2 units. Gives the cut of 4 units.
5th Day: Gives cut of 1 unit.
6th Day: Takes back cut of 1 unit and gives cut of 2 units.
7th Day: Gives cut of 1 unit.

## Puzzle 5 | (Finding the poisoned wine)

You have 240 barrels of wine, one of which has been poisoned. After drinking the poisoned wine, one dies exactly 24 hours. You have 5 slaves whom you are willing to sacrifice in order to determine which barrel contains the poisoned wine. How do you achieve this in 48 hours?

Let us number the barrels with 5 digit numbers consisting of 0, 1 and 2. Let us number the slaves as 1, 10, 100, 1000, 10000.

Number 0 on a barrel represents the wine in the barrel will not be taken by the slave.

Number 1 on a barrel represents the wine in the barrel will taken by the slave on 1st day.

Number 2 on a barrel represents the wine in the barrel will be taken by the slave on 2nd day(after 24 hours).

The action corresponding to the digit in the unit place will be executed by slave numbered 1.

The action corresponding to the digit in the tenth place will be executed by slave numbered 10.

The action corresponding to the digit in the 100th place will be executed by slave numbered 100.

The action corresponding to the digit in the 1000th place will be executed by slave numbered 1000.

The action corresponding to the digit in the 10000th place will be executed by slave numbered 10000.

Example: Let us say the barrel is numbered 11201. The wine in this barrel is taken on the first day by the slave numbered 10000, 1000 and 1. It is taken on the second day by slave numbered 100. And it is not taken by the slave numbered 10.

So if the slave numbered 10000, 1000 and 1 die within first 24 hours, slave numbered 100 dies in the next 24 hours and the slave numbered 10 does not die, then the poisoned barrel has to be 11201.

This way total number possible is 3 * 3 * 3 * 3 * 3 = 3^5 = 243 barrels!! So with the help of 5 slaves and within 48 hours we will be able to find a poisoned barrel among 243 barrels.

## Puzzle 6 | (Monty Hall problem)

Suppose you’re on a game show, and you’re given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what’s behind the doors, opens another door, say No. 3, which has a goat. He then says to you, “Do you want to pick door No. 2?” Is it to your advantage to switch your choice?

https://cdncontribute.geeksforgeeks.org/wp-content/uploads/MontyHall.png

Source: http://en.wikipedia.org/wiki/Monty_Hall_problem

Solution:
If you switch, you get the car with probability 2/3. So switching is always a good choice. Refer this(https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-18-probability-introduction/) MIT video lecture for great explanation. Refer online editable Monty hall simulation(http://www.simulateanything.com/simulation?id=monty_hall&v=20#) to play with how things change with multiple doors, prizes etc.

## Puzzle 7 | (3 Bulbs and 3 Switches)

There is a room with a door (closed) and three light bulbs. Outside the room there are three switches, connected to the bulbs. You may manipulate the switches as you wish, but once you open the door you can’t change them. Identify each switch with its bulb.

Solution:
Let the bulbs be X, Y and Z

Turn on switch X for 5 to 10 minutes. Turn it off and turn on switch Y. Open the door and touch the light bulb.

1. if the light is on, it is Y
2. if the light is off and hot, it is X
3. if the light is off and cold, it is Z

## Puzzle 8 | (Find the Jar with contaminated pills)

You have 5 jars of pills. Each pill weighs 10 grams, except for contaminated pills contained in one jar, where each pill weighs 9 grams. Given a scale, how could you tell which jar had the contaminated pills in just one measurement?

Solution:
Take out 1 pill from jar 1, 2 pills from jar 2, 3 pills from jar 3, 4 pills from jar 4 and 5 pills from jar 5. Put all these 15 pills on scale. The correct wight is 150 (15*10). But one of the jars has contaminated pills. So the wight will definitely less than 150. If the wight is 149 then jar 1 has contaminated pills because the there is only one contaminated pill. If the wight is 148 then jar 2, if the wight is 147 then jar 3, if 146 then jar 4, if 145 then jar 5.

## Puzzle 9 | (Find the fastest 3 horses)

There are 25 horses among which you need to find out the fastest 3 horses. You can conduct race among at most 5 to find out their relative speed. At no point you can find out the actual speed of the horse in a race. Find out how many races are required to get the top 3 horses.

The solution is 7.

First, we group the horses into groups of 5 and race each group in the race course. This gives us 5 races (see image below).

horspuzzle1

In the image, each row represents one race of 5 horses. For convenience, let us name the horses using row and column index. Therefore, the first race(row 1) was contested between the horses R1C1, R1C2, R1C3, R1C4 and R1C5. The second race (row 2) was contested between the horses R2C1, R2C2 and so on. Let us assume that the fifth member of each row won the race (R1C5 won the first race, R2C5 won the second race and so on), the fourth member of each row came second (R1C4 came second in the first race, R2C4 came second in the second race and so on) and the third member of each group came third (R1C3 came third in the first race, R2C3 came third in the second race and so on).

horsepuzzle2

Next, we race the 5 level 1 winners (R1C5, R2C5, R3C5, R4C5 and R5C5). Let’s say R1C5 wins this race, R2C5 comes second and R3C5 comes third.

horspicture3

The winner of this race (R1C5) is the fastest horse of the entire group. Now, the horse which is second in the entire group can either be R2C5 or R1C4. The horse which is third in the entire group can either be R3C5, R2C4 or R1C3. Therefore, we race these 5 horses.

horspicture4

Therefore, the horse R1C5 is the fastest horse. The horses which come second and third in the last race are the horses which are second and third in the entire group respectively. in this way, the minimum number of races required to determine the first, second and third horses in the entire group is 7.

This explanation is provided by Feroz Baig

Alternate Explanation:
Make group of 5 horses and run 5 races. Suppose five groups are a,b,c,d,e and next alphabet is its individual rank in tis group(of 5 horses).for eg. d3 means horse in group d and has rank 3rd in his group. [ 5 RACES DONE ]
a1 b1 c1 d1 e1
a2 b2 c2 d2 e2
a3 b3 c3 d3 e3
a4 b4 c4 d4 e4
a5 b5 c5 d5 e5

Now make a race of (a1,b1,c1,d1,e1).[RACE 6 DONE] suppose result is a1>b1>c1>d1>e1
which implies a1 must be FIRST.
b1 and c1 MAY BE(but not must be) 2nd and 3rd.
FOR II position, horse will be either b1 or a2
(we have to find top 3 horse therefore we choose horses b1,b2,a2,a3,c1 do racing among them [RACE 7 DONE].
The only possibilities are :
c1 may be third
b1 may be second or third
b2 may be third
a2 may be second or third
a3 may be third
The final result will give ANSWER. suppose result is a2>a3>b1>c1>b2
then answer is a1,a2,a3,b1,c1.
HENCE ANSWER is 7 RACES

Please note that the 7 races work for the case also when all top 3 horses are same group or any top two horses are in same group. The group which has top 3 horses would always have winner in 6th race. In 7th race, we consider 2nd and 3rd horses of the group whose horse is overall winner. We also consider 2nd horse of the group whose horse came 2nd in 6th race.

## Puzzle 10 | (A Man with Medical Condition and 2 Pills)

A man has a medical condition that requires him to take two kinds of pills, call them A and B. The man must take exactly one A pill and exactly one B pill each day, or he will die. The pills are taken by first dissolving them in water.
The man has a jar of A pills and a jar of B pills. One day, as he is about to take his pills, he takes out one A pill from the A jar and puts it in a glass of water. Then he accidentally takes out two B pills from the B jar and puts them in the water. Now, he is in the situation of having a glass of water with three dissolved pills, one A pill and two B pills. Unfortunately, the pills are very expensive, so the thought of throwing out the water with the 3 pills and starting over is out of the question. How should the man proceed in order to get the right quantity of A and B while not wasting any pills?

Solution:
Add one more A pill to the glass and let it dissolve. Take half of the water today and half tomorrow. It works under following assumptions.

The dissolved Pills can be used next day.

The man has to take pills at least for one more day.

## Puzzle 11 | (1000 Coins and 10 Bags)

A dealer has 1000 coins and 10 bags. He has to divide the coins over the ten bags, so that he can make any number of coins simply by handing over a few bags. How must divide his money into the ten bags?

Solution:
We can represent any decimal number as weights of binary system. For example, if we want to measure upto 7, first three bags are sufficient.

1 = 2^0

2 = 2^1

3 = 2^0 + 2^1

4 = 2^2

5 = 2^2 + 2^0

6 = 2^2 + 2^1

7 = 2^2 + 2^1 + 2^0

It can be easily generalized. We can measure upto 2^n – 1.

Fun is, we can also measure the same using powers of 3. For example, we have bags with 1, 3 and 9 coins,

1 = 1

2 = 3-1

3 = 3

4 = 3+1

5 = 9-3-1

6 = 9-3

7 = 9+1-3

8 = 9 -1

9 = 9

10 = 9+1

11 = 9+3-1

12 = 9+3

13 = 9+3+1

From 14 onwards next bag comes into picture.

Factorization algorithms other than powers of 2 are costly on computer systems. Please share any other information. Any person working on cryptography can share more details.

## Puzzle 12 | (Maximize probability of White Ball)

There are two empty bowls in a room. You have 50 white balls and 50 black balls. After you place the balls in the bowls, a random ball will be picked from a random bowl. Distribute the balls (all of them) into the bowls to maximize the chance of picking a white ball.

Explanation:
First, let us assume that we divided the balls into jars equally so each jar will contain 50 balls.
So the probability of selecting a white ball will be=probability of selecting the first jar*probability of white ball in the first jar + probability of selecting the second jar*probability of white ball in the second jar
=(1/2)*(0/50)+(1/2)*(50/50)=0.5
Since we have to maximize the probability so we will increase the probability of white ball in the first jar and keep the second probability same mean equal to 1
so we add 49 white balls with 50 black balls in the first jar and only one white ball in the second jar
so the probability will be now=

(1/2)*(49/99)+(1/2)*(1/1)=0.747
Therefore, probability of getting white ball becomes 1/2*1 + 1/2*49/99 which is approximately 3/4.

## Puzzle 13 | (100 Prisoners with Red/Black Hats)

100 prisoners in jail are standing in a queue facing in one direction. Each prisoner is wearing a hat of color either black or red. A prisoner can see hats of all prisoners in front of him in the queue, but cannot see his hat and hats of prisoners standing behind him.
The jailer is going to ask color of each prisoner’s hat starting from the last prisoner in queue. If a prisoner tells the correct color, then is saved, otherwise executed. How many prisoners can be saved at most if they are allowed to discuss a strategy before the jailer starts asking colors of their hats.

Answer:
At-most 99 prisoners can be saved and the 100th prisoner has 50-50 chances of being executed.
The idea is that every prisoner counts number of red hats in front of him.

100th prisoner says red if the number of red hats is even. He may or may not be saved, but he coneys enough information to save 99th prisoner.

The 99’th prisoner decides his answer on the basis of answer of 100’th prisoner’s answer. There are following possibilities and 99’th prisoner can figure out color of his hat in every case.

If 100’th prisoner said ‘Red’ (There must have been even number of red hats in front of him)
a) If 99’th prisoner sees even number of red hats in front of him, then his color is black.
b) If 99’th prisoner sees odd number of red hats in front of him, then his color is red.

If 100’th prisoner said ‘Black’ (There must have been odd number of red hats in front of him)
a) If 99’th prisoner sees even number of red hats in front of him, then his color is Red.
b) If 99’th prisoner sees odd number of red hats in front of him, then his color is Black.

The 98’th prisoner decides his answer on the basis of answer of 99’th prisoner’s answer and uses same logic.

Similarly other prisoners from 97 to 1 are saved.

## Puzzle 14 | (Strategy for a 2 Player Coin Game)

Consider a two player coin game where each player gets turn one by one. There is a row of even number of coins, and a player on his/her turn can pick a coin from any of the two corners of the row. The player that collects coins with more value wins the game. Develop a strategy for the player making the first turn, such he/she never looses the game.

Note that the strategy to pick maximum of two corners may not work. In the following example, first player looses the game when he/she uses strategy to pick maximum of two corners.

Example
  18 20 15 30 10 14
First Player picks 18, now row of coins is
  20 15 30 10 14
Second player picks 20, now row of coins is
  15 30 10 14
First Player picks 15, now row of coins is
  30 10 14
Second player picks 30, now row of coins is
  10 14
First Player picks 14, now row of coins is
  10 
Second player picks 10, game over.

The total value collected by second player is more (20 + 
30 + 10) compared to first player (18 + 15 + 14).
So the second player wins. 

Solution:
The idea is to count sum of values of all even coins and odd coins, compare the two values. The player that makes the first move can always make sure that the other player is never able to choose an even coin if sum of even coins is higher. Similarly, he/she can make sure that the other player is never able to choose an odd coin if sum of odd coins is higher.

Example
18 20 15 30 10 14
Sum of odd coins = 18 + 15 + 10 = 43
Sum of even coins = 20 + 30 + 14 = 64.
Since the sum of even coins is more, the first
player decides to collect all even coins. He first
picks 14, now the other player can only pick a coin
(10 or 18). Whichever is picked the other player,
the first player again gets an opportunity to pick
an even coin and block all even coins.

## Puzzle 15 | (Camel and Banana Puzzle)

A person has 3000 bananas and a camel. The person wants to transport maximum number of bananas to a destination which is 1000 KMs away, using only the camel as a mode of transportation. The camel cannot carry more than 1000 bananas at a time and eats a banana every km it travels. What is the maximum number of bananas that can be transferred to the destination using only camel (no other mode of transportation is allowed).

Solution:
The solution: 533 1/3 bananas. https://puzzle.dse.nl/math/bananas_us.html

Explanation: since there are 3000 bananas and the camel can carry at most 1000 bananas, at least five trips are needed to carry away all bananas from the plantation P (3 trips away from the plantation and 2 return trips):

 
 
P (plantation)
 
 	===forth===>
<===back====
===forth===>
<===back====
===forth===>	 
 
A
 
 
Point A in the above picture cannot be the market. This is because the camel can never travel more than 500 kilometers into the desert if it should return to the plantation (the camel eats a banana every kilometer it travels!). So point A lies somewhere in the desert between the plantation and the market. From point A to the next point, less than five trips must be used to transport the bananas to that next point. We arrive at the following global solution to the problem (P denotes the plantation, M denotes the market):

 
 
P (plantation)
 
 	===forth===>
<===back====
===forth===>
<===back====
===forth===>	 
 
A
 
 	 
===forth===>
<===back====
===forth===>
 	 
 
B
 
 	 
 
===forth===>
 
 	 
 
M (market)
 
 
Note that section PA must be in the solution (as explained above), but section AB or section BM might have a length of 0. Let us now look at the costs of each part of the route. One kilometer on section PA costs 5 bananas. One kilometer on section AB costs 3 bananas. One kilometer on section BM costs 1 banana. To save bananas, we should make sure that the length of PA is less than the length of AB and that the length of AB is less than the length of BM. Since PA is greater than 0, we conclude that AB is greater than 0 and that BM is greater than 0.

The camel can carry away at most 2000 bananas from point A. This means the distance between P and A must be chosen such that exactly 2000 bananas arrive in point A. When PA would be chosen smaller, more than 2000 bananas would arrive in A, but the surplus cannot be transported further. When PA would be chosen larger, we are losing more bananas to the camel than necessary. Now we can calculate the length of PA: 3000-5*PA=2000, so PA=200 kilometers. Note that this distance is less than 500 kilometers, so the camel can travel back from A to P.

The situation in point B is similar to that in point A. The camel cannot transport more than 1000 bananas from point B to the market M. Therefore, the distance between A and B must be chosen such that exactly 1000 bananas arrive in point B. Now we can calculate the length of AB: 2000-3*AB=1000, so AB=333 1/3. Note that this distance is less than 500 kilometers, so the camel can travel back from B to A. It follows that BM=1000-200-333 1/3=466 2/3 kilometers. As a result, the camel arrives at the market with 1000-466 2/3=533 1/3 bananas.

The full scenario looks as follows: first, the camel takes 1000 bananas to point A. There it drops 600 bananas and returns with 200 bananas. Then the camel takes again 1000 bananas to point A. Again, it drops 600 bananas and returns with 200 bananas. After this, the camel takes the last 1000 bananas from the plantation to point A. From point A, it leaves with 1000 bananas to point B. In point B, it drops 333 1/3 bananas and returns with 333 1/3 bananas. Then it takes the second load of 1000 bananas from point A to point B. Finally, it carries the 1000 bananas from point B to the market, where it arrives with 533 1/3 bananas.


https://www.geeksforgeeks.org/puzzle-16-100-doors/
