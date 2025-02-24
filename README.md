Download link :https://programming.engineering/product/eecs-126-probability-and-random-processes-problem-set-3/


# EECS-126-Probability-and-Random-Processes-Problem-Set-3
EECS 126: Probability and Random Processes Problem Set 3
Graphical Density

Figure 1 shows the joint density fX;Y of the random variables X and Y .

Figure 1: Joint density of X and Y .

Find A and sketch fX , fY , and fXjX+Y 3.

Find E[X j Y = y] for 1 y 3 and E[Y j X = x] for 1 x 4.

Find cov(X; Y ).

2. Joint Density for Exponential Distribution

If X Exponential( ) and Y Exponential( ), X and Y independent, compute P(X <Y).

If Xk, 1 k n are independent and exponentially distributed with parameters

1; : : : ; n, show that min1 k n Xk Exponential(Pn j).

j=1

(c) Deduce that

P

(Xi =

min Xk) =

i

n

j

1 k n

Pj=1

3. Packet Routing

Packets arriving at a switch are routed to either destination A (with probability p) or destination B (with probability 1 p). The destination of each packet is chosen independently of each other. In the time interval [0; 1], the number of arriving packets is Poisson( ).

Show that the number of packets routed to A is Poisson distributed. With what parameter?

Are the number of packets routed to A and to B independent?


4. Gaussian Densities

Let X1 N (0; 1), X2 N (0; 1), where X1 and X2 are independent. Convolve the densities of X1 and X2 to show that X1 + X2 N (0; 2). Remark. Note that this property is similar to the one shared by independent Poisson random variables.

Let X N (0; 1). Compute E[Xn] for all integers n 1.

5. Moving Books Arround

You have N books on your shelf, labelled 1; 2; : : : ; N. You pick a book j with probability 1=N.

Then you place it on the left of all others on the shelf. You repeat the process, independently.

Construct a Markov chain which takes values in the set of all N! permutations of the books.

Find the transition probabilities of the Markov chain.

Find its stationary distribution.

Hint: You can guess the stationary distribution before computing it.
