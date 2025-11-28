0. Make slides for the following:
    A. INTRODUCTION AND MOTIVATION 
        a. Describe your dataset (e.g. what are the observational data and how they were collected, in case there are interventional data, also what are they and how they were collected).
        b. Describe the causal questions you wish to answer (e.g. “we investigate the effect of X on Y”).
        c. Describe the assumptions of your dataset (causal sufficiency, no cycles in the causal graph, positivity, etc).
    B. EXPLORATORY DATA ANALYSIS
        a. Testing correlation / dependence for the variables in the dataset and show how they are dependent;
        b. Discuss the true causal graph of the dataset, if it’s known, and otherwise discuss a reasonable guess.
    C. IDENTIFYING ESTIMANDS 
        a. Here you should identify possible adjustment sets by HAND (showing that you understood the theory in the class) by using: Backdoor criterion, Frontdoor criterion, Instrumental variables as per Tutorials 3 and 4. Keep in mind that you should report what happens for these methods even if they don’t apply and explain why.
        b. You can also show the results you get for each of these estimands from doWhy and compare with the ones you found by hand.

1. ESTIMATING CAUSAL EFFECTS
    A. Understand the results 
    B. Make slides on this as well

2. CAUSAL DISCOVERY
    A. In this part you will try out the two types of algorithms for learning causal graphs that will be shown in Tutorials 5 and 6. You are also expected to explain why each methods works or doesn’t and what is identifiable in terms of the causal graph
    B. Run a constraint-based algorithm (e.g. PC) and a score-based algorithm (e.g. GES) on your data, and report back any iden- tifiable causal relations.
    C. Optional: If you cannot find any identifiable causal relation or just want to test the algorithms further, simulate some data that resemble your real data (but maybe with less edges).
    D. Make slides for this!

3. VALIDATION AND SENSITIVITY ANALYSIS
    A. In this part you will try out different ways to validate your results and do sensitivity analysis of the methods
    B. Report using some of the results of the refutation strategies implemented in DoWhy and interpret what they mean.
    C. Optional: If your dataset includes interventional data, check that the estimated causal effects from the observational data are reflected in the interventional data.
    D. Optional: Try experimenting with graphs in which some of the edges are dropped, and see how the results in Section 3 and 4 change.
    E. Optional: Try relaxing some of the assumptions you dis- cussed in the Introduction, e.g. try to see the effect on not observing a certain variable
    F. Make slides for this as well

4. DISCUSSION AND CONCLUSION 
    A. In this part you will discuss the results of the previous sections and explain if they do answer the causal questions you described in the Introduction. You can also elaborate on the results you observed in the validation and discuss if the assumptions you had made initially were realistic
    B. Make slidessss