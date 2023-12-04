The inverse of a matrix is a matrix that, when multiplied with the original matrix, results in the identity matrix. It is denoted as A-1, where A is the original matrix. The inverse of a matrix can only be found for square matrices, which have an equal number of rows and columns.

To find the inverse of a matrix, follow these steps:
	(i)   Calculate the determinant of the matrix
	(ii)  Find the adjugate of the matrix by taking the transpose of the cofactors
	(iii) Divide the adjugate of the matrix by the determinant to obtain the inverse matrix.

Here is an example of finding the inverse of a 2 x 2 matrix.

		A = 	2	  3
			    1	  4
	
(i) Calculate the determinant:
    def (A) = ( 2 . 4) – ( 3 . 1) = 8 – 3 = 5

(ii) Find the adjugate:

  adj(A) = 	  4	-3
		         -1	 2

(iii) Divide the adjugate by the determinant to obtain the inverse:

  A-1 =   1/5	   4	-3	=	   4/5	    -3/5
	              -1	2		    -1/5	  2/5

To verify that A-1 is the inverse of A, we can multiply them together and check if the result is the identity matrix.

A . A-1 =     2  	3	.	 4/5	  -3/5	=	1	  0	=	I
	            1  	4		-1/5	   2/5		0	  1	

		A-1 . A =    4/5	-3/5	.	2	3	=	1	  0	=	I
			          -1/5	2/5		  1	4		0	  1
Since both products result in the identity matrix, we can conclude that A-1 is the inverse of A.
