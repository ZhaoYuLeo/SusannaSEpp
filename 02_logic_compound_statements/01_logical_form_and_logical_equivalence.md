### Test Yourself

1. An $and$ statement is true if, and only if, both components are  **true**.
2. An $or$ statement is false if, and only if, both components are **false**.
3. Two statement forms are logically equivalent if, and only if, they always have **the same truth values**.
4. De Morgan’s laws say (1) that the negation of an $and$ statement is logically equivalent to the $or$ statement in which each component is $negated$, and (2) that the negation of an $or$ statement is logically equivalent to the $and$ statement in which each component is $negated$.
5. A tautology is a statement that is always **true**.
6. A contradiction is a statement that is always **false**.

### Exercise Set 2.1

1. a. If all integers are rational, then the number 1 is rational. All integers are rational. Therefore, the number 1 is rational.

   **Common form**: If p then q. p. Therefore, q.

   b. If all algebraic expressions can be written in prefix notation, then **$(a + 2b)(a^2 - b)$ can be written in prefix notation. All algebraic expressions can be written in prefix notation.** Therefore, $(a + 2b)(a^2 - b)$ can be written in prefix notation. 

2. a. If all computer programs contain errors, then this program contains an error. 

   This program does not contain an error. 

   Therefore, it is not the case that all computer programs contain errors.

   **Common form**: if $p$, then $q$. $\sim q$. Therefore, $\sim p$. 

   b. If  **all prime numbers are odd**, then **2 is odd**. 

   2 is not odd.

   Therefore, it is not the case that all prime numbers are odd.

3. a. This number is even or this number is odd.

   This number is not even.

   Therefore, this number is odd.

   **Common form**: $p \lor q$. $\sim p$. Therefore, $q$.

   b. **My mind is not shot** or logic is confusing.

   My mind is not shot.

   Therefore, **logic is confusing**.

4. a. If n is divisible by 6, then n is divisible by 3.

   If n is divisible by 3, then the sum of the digits of n is divisible by 3.

   Therefore, if n is divisible by 6, then the sum of the digits of n is divisible by 3.

   (Assume that n is a particular, ﬁxed integer.)

   **Common form**: If p, then q. If q, then r. Therefore, if p, then r.

   b. If this function is **a polynomial**, then this function is differentiable.

   If this function is **differentiable**, then this function is continuous. 

   Therefore, if this function is a polynomial, then this function **is continuous**.

5. Indicate which of the following sentences are statements.

   a. 1,024 is the smallest four-digit number that is a perfect square.

   b. She is a mathematics major.

   c. $128 = 2^6$

   d. $x = 2^6$

   (a) Statement (also a true statement: 900, 961, 1024, 1089)

   (b) Not a statement

   (c) Statement

   (d) Not a statement

6. Let s = “stocks are increasing” and i = “interest rates are steady.”

   a. Stocks are increasing <u>but</u> interest rates are steady. ("but" implies "and")

   $$s \land i$$

   b. Neither are stocks increasing nor are interest rates steady. (both of them are false)

   $$\sim s \land \sim i$$

7. Juan is a math major but not a computer science major. (m = “Juan is a math major,” c = “Juan is a computer science major”).

   $$m \land \sim c$$

8. Let h = “John is healthy,” w = “John is wealthy,” and s = “John is wise.”

   a. John is healthy and wealthy but not wise.

   $$(h \land w) \land \sim s$$

   b. John is not wealthy but he is healthy and wise.

   $$\sim w \land (h \land s)$$

   c. John is neither healthy, wealthy, nor wise.

   $$\sim h \land \sim w \land \sim s$$

   d. John is neither wealthy nor wise, but he is healthy.

   $$(\sim w \land \sim s) \land h$$

   e. John is wealthy, but he is not both healthy and wise.

   $$w \land (h \lor s)$$

   $$w \land \sim (h \land s)$$

9. Either this polynomial has degree 2 or it has degree 3 but not both. (n = “This polynomial has degree 2,” k = “This polynomial has degree 3”)

   $$(n \land \sim k) \lor (\sim n \land k)$$

   $$(n \lor k) \land \sim (n \land k)$$

10. Let p be the statement “DATAENDFLAG is off,” q the statement “ERROR equals 0,” and r the statement “SUM is less than 1,000.” Express the following sentences in symbolic notation.

  a. DATAENDFLAG is off, ERROR equals 0, and SUM is less than 1,000.

  $$p \land q \land r$$

  b. DATAENDFLAG is off but ERROR is not equal to 0.

  $$p \land \sim q$$

  c. DATAENDFLAG is off; however, ERROR is not 0 or SUM is greater than or equal to 1,000.

  $$p \land (\sim q \lor \sim r)$$

  $$p \land \sim (q \land r)$$

  d. DATAENDFLAG is on and ERROR equals 0 but SUM is greater than or equal to 1,000.

  $$\sim p \land q \land \sim r$$

  e. Either DATAENDFLAG is on or it is the case that both ERROR equals 0 and SUM is less than 1,000.

  $$\sim p  \lor (q \land r)$$

11. In the following sentence, is the word $or$ used in its inclusive or exclusive sense? A team wins the playoffs if it wins two games in a row or a total of three games.

    **Inclusive**: the two statement could both happen.

    **exclusive**: the two statement doesn't occur at the same time.

    It's inclusive $or$.

12. omit

13. omit

14. omit

15. omit

16. $p \lor (p \land q)\ and\ p$

    $$\equiv$$

    is true when p is true or when p is true and q is true. Logically equivalent.

17. $\sim(p \land q)\ and\ \sim p \land \sim q $

    Not logically equivalent. De Morgan's Law

18. $p \lor t\ and\ t$ (t represents a tautology which is always true).

    $$p \lor t \equiv t$$

    $$p \land c \equiv c$$

19. $p \land t\ and\ p$

    $$p \land t \equiv p$$

    $$p \lor c \equiv p$$

20. $p \land c\ and\ p \lor c$ (c represents a contradiction and a contradiction is always false).

    c and  p are not logically equivalent.

21. $(p \land q)\land r\ and\ p \land(q \land r)$

    $$(p \land q)\land r\ \equiv \ p \land(q \land r)$$

22. $p\land(q\lor r)\ and\ (p \land q)\lor(p \land r)$

    $$p\land(q\lor r)\ \equiv \ (p \land q)\lor(q \land r)$$

    true when and only when p is true and at least one of q and r is true.

23. $(p\land q)\lor r\ and\ p \land(q\lor r)$
    $$(p\land q)\lor r \equiv (p \lor r)\land (q \or r)$$

    $$p \land (q \lor r) \equiv (p \land q) \lor (p \land r)$$

24. $(p\lor q)\lor(p\land r)\ and\ (p\lor q)\land r$

    $$(p\lor q)\land r \equiv (r \land p) \lor (r \land q)$$

25. Hal is a math major and Hal’s sister is a computer science major.

    $$\neg(p \land q) \equiv (\neg p \lor \neg q)$$

    Negation: Hal is **not** a math major **or** Hal’s sister is **not**  a computer science major.

26. Sam is an orange belt and Kate is a red belt.

    Sam is **not** an orange belt **or** Kate is **not** a red belt.

27. The connector is loose or the machine is unplugged.

    $$\neg(p \lor q) \equiv (\neg p \land \neg q)$$

    The connector is **not** loose **and** the machine is **and** unplugged.

28. The units digit of $4^{67}$ is 4 or it is 6.

    The units digit of $4^{67}$ is  neither 4 nor 6.

29. This computer program has a logical error in the ﬁrst ten lines or it is being run with an incomplete data set.

    This computer program **doesn't have** a logical error in the ﬁrst ten lines **and** it is being run with an **complete data set**.

30. The dollar is at an all-time high and the stock market is at a record low.

    The dollar is **not** at an all-time high **or** the stock market is **not** at a record low.

31. The train is late or my watch is fast

    The train is **not** late **and** my watch is **not** fast

Assume $x \in R$, write negation using De Margan's laws:

32. $-2 < x < 7$

    $$(x \leq -2) \lor (x \geq 7)$$

33. $-10 < x < 2$

    $$(x \leq -10) \lor (x \geq 2)$$

34. $x < 2\ \lor\ x > 5$

    $$2 \leq x \leq 5$$

35. $x \leq -1\ \or\ x > 1$

    $$-1 < x \leq 1$$

36. $1 > x \geq -3$

    $$(x < -3) \lor (x \geq 1)$$

37. $0 > x \geq -7$

    $$(x < -7) \lor (x \geq 0)$$

38. (num_orders > 100 and num_instock ≤ 500) or num_instock < 200

    **Negations**:

    (num_orders $\leq$ 100 or num_instock > 500) and num_instock $\geq$ 200

39. (num_orders < 50 and num_instock > 300) or (50 ≤ num_orders < 75 and num_instock > 500)

    **Negations**:

    (num_orders $\geq$ 50 or num_instock $\leq$ 300) and (num_orders < 50 or 75 $\leq$ num_instock $\leq$ 500)

    num_orders < 50 or 75 $\leq$ num_instock $\leq$ 500

40. $(p ∧ q) ∨ (∼p ∨ (p ∧ ∼q))$

    $$\neg p \lor (p \land \neg q) \equiv \neg p \lor \neg q$$

    True when p is not true or q is not true.

    $$m \lor \neg m$$

    Always true. Tautologies.

41. $(p ∧ ∼q) ∧ (∼p ∨ q)$

    $$m \land \neg m$$

    Always false. Contradictions.

42. $((∼p ∧ q) ∧ (q ∧ r)) ∧ ∼q$

    $$m \land \neg m$$

    Always false. Contradictions.

43. $(∼p ∨ q) ∨ (p ∧ ∼q)$

    $$m \lor \neg m$$

    Always true. Tautologies.
    

Determine whether the statements in a and b are logically equivalent.
44. Assume x is a particular real number.

    a. x < 2 or it is not the case that 1 < x < 3.

    b. $x \leq 1$ or either x < 2 or $x \geq 3$.

    Logically equivalent.

45. a. Bob is a double math and computer science major and Ann is a math major, but Ann is not a double math and computer science major.

    b. It is not the case that both Bob and Ann are double math and computer science majors, but it is the case that Ann is a math major and Bob is a double math and computer science major.

    Logically equivalent.

46. In Example 2.1.4, the symbol ⊕ was introduced to denote exclusive or, so p ⊕ q ≡ (p ∨ q)∧ ∼(p ∧ q). You know what the truth table look like.

    a. Find simpler statement forms that are logically equivalent to p ⊕ p and (p ⊕ p) ⊕ p.

    $$p \oplus p \equiv c$$ (c means contradiction)

    $$(p \oplus p) \oplus p \equiv p$$

    b. Is (p ⊕ q) ⊕ r ≡ p ⊕ (q ⊕ r)? Justify your answer.

    | $p$  | $q$  | $r$  | $p \oplus q$ | $q \oplus r$ | $(p \oplus q) \oplus r$ | $p \oplus (q \oplus r)$ |
    | ---- | ---- | ---- | ------------ | ------------ | ----------------------- | ----------------------- |
    | T    | T    | T    | F            | F            | T                       | T                       |
    | T    | F    | T    | T            | T            | F                       | F                       |
    | F    | T    | F    | T            | T            | T                       | T                       |
    | F    | F    | F    | F            | F            | F                       | F                       |
    | T    | T    | F    | F            | T            | F                       | F                       |
    | T    | F    | F    | T            | F            | T                       | T                       |
    | F    | T    | T    | T            | F            | F                       | F                       |
    | F    | F    | T    | F            | T            | T                       | T                       |

    $(p \oplus q) \oplus r \equiv p \oplus (q \oplus r)$

    c. Is (p ⊕ q) ∧ r ≡ (p ∧ r) ⊕ (q ∧ r)? Justify your answer.

    | $p$  | $q$  | $r$  | $p \oplus q$ | $p \land r$ | $q \land r$ | $(p \oplus q) \land r$ | $(p \land r) \oplus (q \land r)$ |
    | ---- | ---- | ---- | ------------ | ----------- | ----------- | ---------------------- | -------------------------------- |
    | T    | T    | T    | F            | T           | T           | F                      | F                                |
    | T    | F    | T    | T            | T           | F           | T                      | T                                |
    | F    | T    | F    | T            | F           | F           | F                      | F                                |
    | F    | F    | F    | F            | F           | F           | F                      | F                                |
    | T    | T    | F    | F            | F           | F           | F                      | F                                |
    | T    | F    | F    | T            | F           | F           | F                      | F                                |
    | F    | T    | T    | T            | F           | T           | T                      | T                                |
    | F    | F    | T    | F            | F           | F           | F                      | F                                |

    $(p \oplus q) \land r \equiv (p \land r) \oplus (q \land r)$

47. In logic and in standard English, a double negative is equivalent to a positive. There is one fairly common English usage in which a “double positive” is equivalent to a negative. What is it? Can you think of others?

    $\neg\neg t \equiv t $

    Sarcastically.

Supply a reason for each step.
48. (p ∧ ∼q) ∨ (p ∧ q) ≡ p ∧ (∼q ∨ q) by distributive

    ≡ p ∧ (q ∨ ∼q) by  commutative

    ≡ p∧t by negation

    ≡p by identity

    Therefore, (p ∧ ∼q) ∨ (p ∧ q) ≡ p.

49. (p ∨ ∼q) ∧ (∼p ∨ ∼q) ≡ (∼q ∨ p) ∧ (∼q ∨ ∼p) by distributive

    ≡ ∼q ∨ (p ∧ ∼p) by commutative

    ≡ ∼q ∨ c by negation

    ≡ ∼q by identity

    Therefore, (p ∨ ∼q) ∧ (∼p ∨ ∼q) ≡ ∼q.

50. (p ∧ ∼q) ∨ p ≡ p

    $$c \lor p \equiv p$$

51. p ∧ (∼q ∨ p) ≡ p

    $$p\land t \equiv p$$

52. ∼(p ∨ ∼q) ∨ (∼p ∧ ∼q) ≡ ∼p

    $$\neg p \land (p \lor \neg p) \equiv \neg p$$

53. ∼((∼p ∧ q) ∨ (∼p ∧ ∼q)) ∨ (p ∧ q) ≡ p

    $$p \lor (p \land q) \equiv p \land (c \lor q) \equiv p$$

54. (p ∧ (∼(∼p ∨ q))) ∨ (p ∧ q) ≡ p

    $$(p \land (p \land \neg q)) \lor (p \land q) \equiv p \land t \equiv t$$

    
