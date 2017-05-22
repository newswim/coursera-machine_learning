## Vocabulary and Concepts


**"Supervised Learning"**
- Given: the "Right" answer for a problem

**"Regression Problem"**
- Predict "real-valued" output

**"Classification Problem"**
- Predict "discreet value outputs" [0 or 1]

#### Training Set


| Notation    | Meaning                                    |
| :---------- | :----------------------------------------- |
| `m`         | Number of training examples / training set |
| `x`'s       | "input" variables / features               |
| `y`'s       | "output" variable / target variable        |
| `(x, y)`    | one training example                       |
| `xⁱ` / `ⁱ`  | Index into training example                |
| `h`         | hypothesis, a learning algorithm's output  |


**Hypothesis**
- A function which maps X's to Y's.
- Question: How do we represent `h`?

```
hθ(x) = θ₀ + θ₁x
```

Oftentimes, we'll just use h(x), but really we mean hθ(x)

The equation above represents a **Linear Regression with one variable (x)**.
It is also called a **Univariate Linear Regression**.



## Greek Symbols and their meaning in ML

#### θ (Theta)