Definition 1: A set of numbers arranged in rows and columns to form a rectangular array. The numbers are called the elements, or entries, of the matrix.

Definition 2: A matrix is a rectangular arrangement of numbers into rows and columns.

For example; matrix A has two rows and three columns.
              -2  5  6
               5  2  7

The above matrix says 2 by 3 (two rows, and three columns)

Matrix dimension:
The dimension of a matrix tells its size; the number of rows and columns of the matrix, in that order.
Since matrix A has two rows and three columns, we write its dimensions as 2 x 3, pronounced “two by three”.

In contrast, matrix B has three rows and two columns, so it is a 3 x 2 matrix. 
              -8  -4  
              23  12
              18  10

When working with matrix dimensions, remember rows x columns.

Matrix elements:
A matrix element is simply a matrix entry. Each element in a matrix is identified by naming the row and column in which it appears.

For example; consider matrix G:
					4	14	-7
				G =	18	5	13
					-20	4	22

The element g2,1 is the entry in the second row and the first column.
					  4	14	-7
				G =	18	5	13
					  -20	4	22

In this case g2,1 = 18.

In general, the element in row i and column j of matrix A is denoted as ai,j.


Adding Matrices:
	A = 	2	   3				B = 	 7	  4
		    5	  -4					    -3	  5

A + B =    2 + 7		   3 + 4
	         5 + (-3)		-4 + 5

A + B = 	9	  7
		      2	  1



Multiplying Matrix

A =	2	3
		5	-4


4A = 	4(2)		4(3)
		  4(5)		4(-4)

4A = 	8	12
		  20	-16


Subtract Matrix

A = 	2	3		B = 	7	4
		  5	-4			-3	5

A-B =	2 - 7		     3 - 4
		  5 - (-3)		-4 - 5

A – B =	-5	-1
		     8	-9


Multiplying Matrix

A = 	2	5	6			B =	3
								    4
							     -5
A x B
AB = 	2(3) + 5(4) + 6(-5)
AB = 	6 + 9 – 30
AB =	26    -30
AB =	-4

B x A = column x row
			  6	15	18
BA = 		8	20	24
			-10	-25	-30

A = 	1	4	-2			B =	5	  2  	8  	-1
		  3	5	-6				  3	  6	  4	  5
								     -2	  9	  7  	-3

For this, we have to multiply row 1 with column 1, then row 1 with column 2, row 1 with column 3, then row 1 with column 4. Similarly, after that row 2 with column 1, row 2 with column 2, and so on. I already calculated and the result are as below.
A x B
AB =	21	8	10	25
  		42	-18	2	40

How to divide 3 x 3 matrices?
		  .	.	.				  .	.	.
A =  	.	.	.			B =	.	.	.
		  .	.	.				  .	.	.

A / B
Simply the division is the inverse of multiplication. There is no direct way of dividing matrices, so we will do an inverse of multiplication.

		  . . .	 1	0  	0		        1	0	0	.  .  .
B = 	. . .	 0	1	  0  => B-1	  0	1	0	.  .  .
		  . . .  0	0	  1		        0	0	1	.  .  .

A.B-1
A / B = A.B-1
