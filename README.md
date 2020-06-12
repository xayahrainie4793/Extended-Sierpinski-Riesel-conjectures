This research is from http://www.noprimeleftbehind.net/crus/Sierp-conjectures.htm and http://www.noprimeleftbehind.net/crus/Riesel-conjectures.htm, extended to the k such that gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) is not 1.

Sierpinski problem base b: (b>=2)
Finding and proving the smallest k>=1 such that gcd(k+1,b-1)=1 and k*b^n+1 is not prime for all integers n>=1.

Riesel problem base b: (b>=2)
Finding and proving the smallest k>=1 such that gcd(k-1,b-1)=1 and k*b^n-1 is not prime for all integers n>=1.

Extended Sierpinski problem base b: (b>=2)
Finding and proving the smallest k>=1 such that (k*b^n+1)/gcd(k+1,b-1) is not prime for all integers n>=1.

Extended Riesel problem base b: (b>=2)
Finding and proving the smallest k>=1 such that (k*b^n-1)/gcd(k-1,b-1) is not prime for all integers n>=1.

Notes:

All n must be >= 1.

k-values that make a full covering set with all or partial algebraic factors are excluded from the conjectures.

k-values that are a multiple of base (b) and where (k+-1)/gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) is not prime are included in the conjectures but excluded from testing.
Such k-values will have the same prime as k / b.

See "table of Riesel problems.txt" and "table of Sierpinski problems.txt" for:

* The covering set of the conjectured k for each Sierpinski/Riesel base.
* The k's that make a full covering set with all or partial algebraic factors for each Sierpinski/Riesel base.
* The remaining k's to find prime for each Sierpinski/Riesel base.
* The top 10 k's with largest first primes for each Sierpinski/Riesel base.

This project is to solve the Sierpinski/Riesel conjectures for bases b <= 128 and bases b = 256, 512, 1024.
