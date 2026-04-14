Question 1 — Digit Gatekeeper

Approach

Loop from L to R.
Check divisibility by K.
Verify number does not contain digit 0.
Calculate digit sum.
Check if digit sum is prime.
Count valid numbers.

Time Complexity:
O(N × D)
(N = range size, D = digits)

 Question 2 — Roll-Seed Lock

Approach

Repeat transformation 3 times.
Apply even/odd rule.
Check:
number between 100–999
middle digit equals seed.

Time Complexity:
O(1)

Question 3 — Mirror Corridor

Approach

Try values of X from 0 to 100000.
Check palindrome condition.
Check divisibility by K.
Return smallest valid X.

Time Complexity:
O(100000 × D)

Question 4 — Fare Calculator

Approach

Calculate initial fare.
Apply late penalty.
Apply distance bonus.
Modify using seed value.
Round to nearest multiple of 5.

Time Complexity:
O(1)

Question 5 — Skipping Numbers

Approach

Keep adding numbers from 1 onward.
Skip numbers divisible by (seed + 2).
Stop when sum ≥ N.

Time Complexity:
O(m)

 Question 6 — Contest Score Judge

Approach

Calculate score = 3a + b − 2c.
Replace negative score with 0.
Deduct 10 if total submissions > 50.
Determine PASS or FAIL.

Time Complexity:
O(1)
