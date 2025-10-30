Final Fruit Tree Pruning Project
================
Trenton Blais
2025-10-30

- [ABSTRACT](#abstract)
- [BACKGROUND](#background)
- [STUDY QUESTION and HYPOTHESIS](#study-question-and-hypothesis)
  - [Questions](#questions)
  - [Hypothesis](#hypothesis)
  - [Prediction](#prediction)
- [METHODS](#methods)
  - [Fill in first analysis](#fill-in-first-analysis)
  - [Fill in second analysis/plot](#fill-in-second-analysisplot)
- [DISCUSSION](#discussion)
  - [Interpretation -](#interpretation--)
  - [Interpretation - Linear model and
    p-value](#interpretation---linear-model-and-p-value)
- [CONCLUSION](#conclusion)
- [REFERENCES](#references)

# ABSTRACT

# BACKGROUND

# STUDY QUESTION and HYPOTHESIS

## Questions

Does pruning apple trees increase the likelihood of an adequate fruit
yield.

## Hypothesis

We hypothesize that due to the benefits pruning typically produces, the
trees that were pruned will lead to more adequate yields compared to the
non-pruned trees.

## Prediction

We predict that pruning apple trees will increase the likelihood of an
adequate yield for those trees.

# METHODS

## Fill in first analysis

``` r
Pruned <- c(1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,3,3,3,3)



Not  <- c(1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,1,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,2,3,3,3,3,3)

Tree <- data.frame(Pruned, Not)

boxplot(Tree)
```

![](Final-fruit-tree-pruning-project_files/figure-gfm/loading%20data-1.png)<!-- -->

## Fill in second analysis/plot

I will also do a linear regression model on Thursday to test the
relationship between the fruit trees’ pruned status and its growth.

# DISCUSSION

## Interpretation -

## Interpretation - Linear model and p-value

# CONCLUSION

# REFERENCES

3.  ChatGPT. OpenAI, version Jan 2025. Used as a reference for functions
    such as plot(viremia) and to correct syntax errors. Accessed
    2025-10-30.
