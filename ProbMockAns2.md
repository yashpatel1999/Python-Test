### Answer 1:

#### (a) Complete the table:

| Grades \(x_i\) | \(n_i\) | \(f_i\) (Relative Frequency) | \(F_i\) (Cumulative Frequency) |
|----------------|---------|-----------------------------|--------------------------------|
| [0, 20]        | 15      | \( \frac{15}{250} = 0.06 \) | \( 0.06 \)                    |
| ]20, 40]       | 35      | \( \frac{35}{250} = 0.14 \) | \( 0.06 + 0.14 = 0.20 \)      |
| ]40, 60]       | 75      | \( \frac{75}{250} = 0.30 \) | \( 0.20 + 0.30 = 0.50 \)      |
| ]60, 80]       | 90      | \( \frac{90}{250} = 0.36 \) | \( 0.50 + 0.36 = 0.86 \)      |
| ]80, 100]      | 35      | \( \frac{35}{250} = 0.14 \) | \( 0.86 + 0.14 = 1.00 \)      |

---

#### (b) Approximate Mean and Median:
- **Mean**: Use the midpoint of each class interval (\(m_i\)) and compute:
  \[
  \text{Mean} = \frac{\sum n_i \cdot m_i}{\sum n_i} = \frac{(15 \cdot 10) + (35 \cdot 30) + (75 \cdot 50) + (90 \cdot 70) + (35 \cdot 90)}{250} = 59.2
  \]

- **Median**: Locate the interval containing the 50th percentile (\(F_i = 0.50\)): \([40, 60]\). Use:
  \[
  \text{Median} = L + \left( \frac{\frac{N}{2} - F_{\text{prev}}}{f} \right) \cdot w
  \]
  Where:
  - \(L = 40\),
  - \(F_{\text{prev}} = 0.20 \times 250 = 50\),
  - \(f = 75\),
  - \(w = 20\).
  \[
  \text{Median} = 40 + \left( \frac{125 - 50}{75} \right) \cdot 20 = 56.67
  \]

---

#### (c) Difference in Mean and Median:
The **mean** (59.2) is slightly higher because it is influenced by the tail of higher grades, while the **median** (56.67) better represents the middle of the dataset.

---

#### (d) Approximate Standard Deviation:
\[
\sigma = \sqrt{\frac{\sum n_i (m_i - \mu)^2}{N}}
\]
Using \(\mu = 59.2\):
\[
\sigma \approx 18.4
\]

---

#### (e) 75th Percentile:
The cumulative frequency (\(F_i\)) reaches 0.75 in the interval \([60, 80]\). Use:
\[
P_{75} = L + \left( \frac{0.75N - F_{\text{prev}}}{f} \right) \cdot w
\]
Where:
- \(L = 60\),
- \(F_{\text{prev}} = 0.50 \times 250 = 125\),
- \(f = 90\),
- \(w = 20\).
\[
P_{75} = 60 + \left( \frac{187.5 - 125}{90} \right) \cdot 20 = 73.89
\]

--- 

Let me know if you'd like clarification or further details!

### Solution 2:

#### Given:
- Total rabbits tested = 200
- Rabbits showing improvement = 140
- Probability of improvement (\(p\)) = \( \frac{\text{Improved Rabbits}}{\text{Total Rabbits}} = \frac{140}{200} = 0.7 \)
- New sample size = 30 rabbits

---

### (a) Probability \(p\)
\[
p = 0.7
\]

---

### (b) Expected value and standard deviation:
The number of rabbits showing improvement follows a Binomial distribution, \( X \sim \text{Binomial}(n = 30, p = 0.7) \).

- **Expected value**:
\[
E(X) = n \cdot p = 30 \cdot 0.7 = 21
\]

- **Standard deviation**:
\[
\sigma = \sqrt{n \cdot p \cdot (1 - p)} = \sqrt{30 \cdot 0.7 \cdot 0.3} = \sqrt{6.3} \approx 2.51
\]

---

### (c) Probability of at least 25 rabbits showing improvement:
We are calculating \( P(X \geq 25) \) for \( X \sim \text{Binomial}(n = 30, p = 0.7) \). Using the complement rule:

\[
P(X \geq 25) = 1 - P(X \leq 24)
\]

To simplify, we can approximate the Binomial distribution with a Normal distribution (\( X \sim \mathcal{N}(\mu, \sigma^2) \)) when \(n\) is large:
- Mean (\(\mu\)) = \( 21 \),
- Standard deviation (\(\sigma\)) = \( 2.51 \).

Using the normal approximation with continuity correction:
\[
P(X \geq 25) \approx P\left(Z \geq \frac{24.5 - \mu}{\sigma}\right) = P\left(Z \geq \frac{24.5 - 21}{2.51}\right)
\]

\[
P(X \geq 25) \approx P\left(Z \geq 1.39\right)
\]

From standard normal tables, \( P(Z \geq 1.39) = 1 - P(Z \leq 1.39) \approx 1 - 0.9177 = 0.0823 \).

---

### Final Results:
- (a) \( p = 0.7 \)
- (b) Expected value = \( 21 \), Standard deviation = \( 2.51 \)
- (c) \( P(X \geq 25) \approx 0.0823 \) or 8.23%

### Solution 3:

#### Given:
- Total seating capacity: \( 35 \)
- Probability of showing up (\(p\)) = \( 1 - 0.15 = 0.85 \)
- Number of reservations (\(n\)) depends on the specific part of the question.

---

### (a) Probability that fewer than 35 people show up when \( n = 35 \):
Let \( N \sim \text{Binomial}(n = 35, p = 0.85) \). We calculate \( P(N < 35) = 1 - P(N = 35) \).

- **\( P(N = 35) \):**
\[
P(N = 35) = \binom{35}{35} \cdot (0.85)^{35} \cdot (1 - 0.85)^0 = (0.85)^{35}
\]
Using a calculator:
\[
P(N = 35) \approx (0.85)^{35} \approx 0.0161
\]

- **\( P(N < 35) \):**
\[
P(N < 35) = 1 - P(N = 35) = 1 - 0.0161 = 0.9839
\]

Thus, the probability that fewer than 35 guests show up is approximately:
\[
P(N < 35) \approx 0.9839 \, \text{or } 98.39\%.
\]

---

### (b) Number of reservations to ensure the expected number of attendees equals 35:
The expected number of attendees is given by:
\[
E(N) = n \cdot p
\]
Set \( E(N) = 35 \):
\[
35 = n \cdot 0.85 \implies n = \frac{35}{0.85} \approx 41.18
\]

Since the number of reservations must be an integer, the hall should accept **42 reservations** to ensure the expected number of attendees equals or exceeds 35.

---

### (c) Probability that fewer than 35 people show up when \( n = 42 \):
Let \( N \sim \text{Binomial}(n = 42, p = 0.85) \). We calculate \( P(N < 35) \) using a Normal approximation for the Binomial distribution since \(n\) is large.

#### Normal Approximation:
For \( N \sim \text{Binomial}(n = 42, p = 0.85) \), the mean and standard deviation are:
\[
\mu = n \cdot p = 42 \cdot 0.85 = 35.7
\]
\[
\sigma = \sqrt{n \cdot p \cdot (1 - p)} = \sqrt{42 \cdot 0.85 \cdot 0.15} \approx \sqrt{5.355} \approx 2.31
\]

Using the Normal approximation with continuity correction:
\[
P(N < 35) \approx P\left(Z < \frac{34.5 - \mu}{\sigma}\right) = P\left(Z < \frac{34.5 - 35.7}{2.31}\right)
\]
\[
P(N < 35) \approx P\left(Z < -0.52\right)
\]

From standard normal tables:
\[
P(Z < -0.52) \approx 0.3015
\]

Thus, the probability that fewer than 35 guests show up is approximately:
\[
P(N < 35) \approx 0.3015 \, \text{or } 30.15\%.
\]

---

### Final Results:
(a) Probability that fewer than 35 people show up with 35 reservations: \( \approx 98.39\% \).

(b) Number of reservations required: **42**.

(c) Probability that fewer than 35 people show up with 42 reservations: \( \approx 30.15\% \).

4. 2-21
5. 2-26
6. 4-10
7. 5-6
8. 5-15
9. 6-5
10. 5-11
11. 7-3
12. 6-2
