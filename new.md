(8).
To demonstrate that the extent of repeated independent testing by different teams can reduce the probability of the research being true, we can expand the PPV formula given, considering both the true positive rate (1-β) and the false positive rate (α).

The PPV formula given is:

PPV = \frac{P(\text{relation exists, at least one of the n repetitions finds significant})}{P(\text{at least one of the n repetitions finds significant})}

Expanding this, we can write it in terms of \( \alpha \) and \( \beta \), and \( R \):

\[
PPV = \frac{R \cdot (1-\beta) + R \cdot \beta \cdot (1-\beta)^{n-1}}{R \cdot (1-\beta) + R \cdot \beta \cdot (1-\beta)^{n-1} + (1-R) \cdot (1 - (1-\alpha)^n)}
\]

As the number of repeated independent tests (n) increases, the probability that at least one of them will find a significant result by chance (false positive) increases, which is represented by the term \(1 - (1-\alpha)^n\).

When \(n\) is large, \(1 - (1-\alpha)^n\) approaches 1, meaning that the denominator grows faster than the numerator, consequently reducing the PPV and hence reducing the probability that the research finding is true.

(9).
For the bias not to decrease the PPV, the following conditions should be true:

a) Bias: If the bias is towards not finding a significant result when there is one (i.e., increasing \( \beta \)), it would not decrease the PPV. Essentially, a conservative bias that errs towards not declaring significance unless there is substantial evidence would ensure that the PPV does not decrease.

b) Increasing teams testing the same hypothesis: Increasing the number of teams testing the same hypothesis would not decrease the PPV if the pre-study odds (\( R \)) are very high or if the true effect being studied is very large, to begin with. A large true effect would mean that the power (1-β) of the studies would be high, thus mitigating the potential increase in false positives that comes with repeated independent testing.

In both cases, maintaining a stringent level of control over \( \alpha \) (keeping it low) would help in not decreasing the PPV, despite the introduction of bias or an increase in the number of teams testing the same hypothesis.
