# Contrast Sets

## Descriptions:

Our contrast learner will examine each pair of nodes in the decision tree and report the delta and effect between each node in a pair:

+ The delta is the difference in the branch path between each node
+ The effect is the mean difference in the performance score those nodes

Note that if the delta is:

+ positive then the contrast is a plan (something to do).
+ negative then the contrast is a monitor (something to watch for).

Note also that is statistically there is no difference between the population of instances in each node, then there is no point printing that contrast. 

### Files: 

_ `contrast_set.py`: python file to execute the work for this assignment 

_ `contrasts_test.py`: python file to test readData 

_ `auto.csv`: given original csv data table file 

### How to run:

- Assuming that you have installed python 2.7
- Execute the command line as below in the terminal within the `contrast_s` folder:

```
python contrasts_test.py <file_name>
```

## Test: 

Using `auto.csv`, print the plans and monitors separately. Note that for the leaves with best scores, there should be no plans generated. Similarly, for the leaves with worst scores, there should be monitors generated.
