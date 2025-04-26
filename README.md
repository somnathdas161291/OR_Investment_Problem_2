# OR_Investment_Problem_2

**Tech Used:** <br />
-- Pyomo <br />
-- Gurobi <br />
<br />
<br />

**Problem Statement:** <br />
Mayke wish to define the best investments that he should make
with his money. He has a total of 100,000 USD and the
following options for investment. <br />
A)Low risk fund with historical gains of 5% per year <br />
B)Medium risk fund with historical gains 10% per year <br />
C)High risk fund with historical gains of 12% per year <br />
D)Especial fund: 10−6∗𝐶𝐷2 <br />
Mayke wish to control the risk of his investments with
maximum of 10% of his money in the investment with high risk,
20% in the investment with medium risk, and 30% in the
especial fund. <br />
Which is the decision of investments in A, B, and C that
maximize the return of investment for Mayke? <br />
<br />
<br />
<br />

**Constraints:** <br />
Objective Function <br />
max (𝑅𝐴 + 𝑅𝐵 + 𝑅𝐶 + 𝑅𝐷) <br />
Constraints rules <br />
𝐶𝐴 + 𝐶𝐵 + 𝐶𝐶 + 𝐶𝐷 = 100,000 <br />
𝑅𝐴 = 0.05𝐶𝐴 <br />
𝑅𝐵 = 0.10𝐶𝐵 <br />
𝑅𝐶 = 0.12𝐶𝐶 <br />
𝑅𝐷 = 10 − 6𝐶𝐷2 <br />
0 ≤ 𝐶𝐵 ≤ 0.2 ∗ 100,000
0 ≤ 𝐶𝐶 ≤ 0.1 ∗ 100,000
0 ≤ 𝐶𝐷 ≤ 0.3 ∗ 100,000
