java c
AMATH242 Computational mathematics
5. (Computational, 4 points) Consider the following code used to approximate sin(x) based on the Taylor series expansion of sin(x), i.e.,

1 function s=sin_Taylor(x)
2 S = x;
3 s_old=0.0;
4 k=1;
5 while abs(s-s_old)>0
6 s_old = s;
7 S = s+(-1)^(k)*x^(2*k+1)/factorial(2*k+1);
8 k=k+1;
9 end 
10 end 
(a) Modify this code to output 1) max value of, abs 2) the number of iterations,3) the absolute value of the relative error. For the values  make a table with 1) the value of x, 2) the exact value of sin(x), 3) the max term, 4) the number of iterations, and 5) the absolute value of the relative error. For what range of x is this algorithm well behaved and when does it start to break down? While the code above has no comments, dont forget to comment your own code well.
(b) How would you modify this code to make it behave better for large values of x (hint, consider the fact that sin(x) is periodic). Recreate the tables from part a with your new code.
(c) Produce tables for algorithms A and B with the following: 1) ith term in the series, ii) the ith partial sum, and iii) the relative error (use the table provided in the notes to check that your algorithm is working co代 写AMATH242 Computational mathematicsR
代做程序编程语言rrectly). Note that you will have two tables for algorithm A and two for algorithm B (i.e., for d = 3,8).
6. (Computational, 6 points) Consider the two algorithms covered in the course notes for approximating the exponential

In this question, vou will construct vour own versions of these two algorithms and apply itl in the context of a hypothetical computer that retains m digits in the mantissa for x = -3.3 and m = 3,8, where we will use the value of exp(-3.3) ≈ 0.036883167 as the true value.
(a) Digits and round function: Create a function that retains m non zero digits of any number and rounds the m +1 digit with the following rule i) if that digit is 2 5 then increment the m digit by one, ii) if it is < 5 truncate the number. Test your function on x=-1.23456789,-123456789,1.23456789,123456789 (for m=3 you should obtain-1.23000000,-123000000, 1.23000000, 123000000, and for m = 8,-1.23456790,-123456790,1.23456790, 123456790).
(b) Implement algorithms A and B carefully considering that you must use the digits and round function for any addition, subtraction, division, or multiplication that you perform. (dont forget to comment your code well).











         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
