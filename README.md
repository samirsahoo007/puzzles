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
