This research is from http://www.noprimeleftbehind.net/crus/Sierp-conjectures.htm and http://www.noprimeleftbehind.net/crus/Riesel-conjectures.htm, extended to the k such that gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) is not 1.

Sierpinski problem base b (b>=2) in CRUS project:
Finding and proving the smallest k>=1 such that gcd(k+1,b-1)=1 and k\*b^n+1 is not prime for all integers n>=1.

Riesel problem base b (b>=2) in CRUS project:
Finding and proving the smallest k>=1 such that gcd(k-1,b-1)=1 and k\*b^n-1 is not prime for all integers n>=1.

Sierpinski problem base b (b>=2) in this project:
Finding and proving the smallest k>=1 such that (k\*b^n+1)/gcd(k+1,b-1) is not prime for all integers n>=1.

Riesel problem base b (b>=2) in this project:
Finding and proving the smallest k>=1 such that (k\*b^n-1)/gcd(k-1,b-1) is not prime for all integers n>=1.

With this effort, we aim to prove many of the Riesel and Sierpinski conjectures for bases <= 128 and bases 256, 512, 1024.

Project definition:

For every base (b) for the forms (k\*b^n+1)/gcd(k+1,b-1) and (k\*b^n-1)/gcd(k-1,b-1), there exists a unique value of k for each form that has been conjectured to be the lowest 'Sierpinski value' (+1 form) or 'Riesel value' (-1 form) that is composite for all values of n >= 1.

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

This project is to solve the Sierpinski/Riesel conjectures for bases b <= 128 and bases b = 256, 512, 1024. (this project will be extended to all bases b <= 1024 in future)

This page is for the status for all k's < CK for bases 2 <= b <= 128 and bases b = 256, 512, 1024.

The thread in mersenneforum for this project is https://mersenneforum.org/showthread.php?t=21839&page=99

For the k's > CK, see:

* https://github.com/xayahrainie4793/first-4-Sierpinski-Riesel-conjectures: k's < 4th CK for bases 2 <= b <= 64 (except 2, 3, 6, 15, 22, 24, 28, 30, 36, 40, 42, 46, 48, 52, 58, 60, 63 (which have larger conjectured k's)) and bases b = 100, 128, 256, 512, 1024.
* https://github.com/xayahrainie4793/all-k-1024: k's <= 1024 for bases 2 <= b <= 32 and bases b = 64, 256.
* https://github.com/xayahrainie4793/Sierpinski-Riesel-for-fixed-k-and-variable-base: all bases <= 1024 for fixed k <= 12

Files read as:

* "k,n": the smallest value n such that (k\*b^n+-1)/gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) is (probable) prime.
* "k,NA": (k\*b^n+-1)/gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) possibly has prime, but no (probable) primes of this form are known.
* "k,algebra": (k\*b^n+-1)/gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) proven to be composite for all n (or only be prime for very small n), by all or partial algebraic factors.
