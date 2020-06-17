This research is from http://www.noprimeleftbehind.net/crus/Sierp-conjectures.htm and http://www.noprimeleftbehind.net/crus/Riesel-conjectures.htm, extended to the k such that gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) is not 1.

Sierpinski problem base b:
Finding and proving the smallest k such that gcd(k+1,b-1)=1 and k*b^n+1 is not prime for all integers n>=1.

Riesel problem base b:
Finding and proving the smallest k such that gcd(k-1,b-1)=1 and k*b^n-1 is not prime for all integers n>=1.

Extended Sierpinski problem base b:
Finding and proving the smallest k such that (k*b^n+1)/gcd(k+1,b-1) is not prime for all integers n>=1.

Extended Riesel problem base b:
Finding and proving the smallest k such that (k*b^n-1)/gcd(k-1,b-1) is not prime for all integers n>=1.

With this effort, we aim to prove many of the Riesel and Sierpinski conjectures for bases <= 1030 that are not currently being worked on by other projects or efforts.

Project definition:

For every base (b) for the forms (k*b^n+1)/gcd(k+1,b-1) and (k*b^n-1)/gcd(k-1,b-1), there exists a unique value of k for each form that has been conjectured to be the lowest 'Sierpinski value' (+1 form) or 'Riesel value' (-1 form) that is composite for all values of n >= 1.

Goal:

Prove the conjectures by finding at least one (probable) prime (if only PRP, prove its primality) for all lower values of k. Many of the conjectures have already been proven but much more work is needed to prove additional bases. Proving them all is not possible but we aim to prove many of them.

* There are many conjectures where only ONE k needs a (probable) prime (and many more that need only two). If you find it, you could be the one to prove a conjecture! This is a big deal to us here.
* Algebraic factors have been found for many k's, which prove them composite for all n, allowing them to be removed from searches.

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
