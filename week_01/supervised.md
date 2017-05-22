## Supervised Learning

Supervised learning problems are categorized into "**regression**" and
"**classification**" problems.
In a regression problem, we are trying to predict results within a continuous
output, meaning that we are trying to map input variables to some continuous
function. In a classification problem, we are instead trying to predict results
in a discrete output. In other words, we are trying to map input variables into
discrete categories.

One of the first things we'll want to decide when writing a learning algorithm
is to determine whether to use a `linear` (straight-line) function of a `quadratic`.

Both of these refer to a type of **_Supervised_** learning.

In the _cancer diagnosis_ example, we are first given one variable: tumor size.
Later on, we look at an example with two variables: Age of person and tumor size.

Researchers who use Machine Learning in practice will often have a large number
of variables upon which the algorithms may act upon. Soon, we'll be introduced
to kinds of algorithms which can handle an _infinite_ number of features.

**"Support Vector Machine"**
- a mathematical trick which will allow computers
to deal with an infinite number of features.


## Unsupervised Learning

The other major category of learning algorithms. The basic premise is:
> Given this dataset, can you (the learning algorithm) find some structure
that can be used to derive a hypothesis about the data.

One such category are called **Clustering Algorithms**, which deal with
clustering datum into types which we do not know in advance.

#### Some real-world examples:
- Data centers (for increasing efficiency of communication between machines)
- Social network analysis
- Market segmentation
- Astronomical data analysis

