# Data and code for Stewart, Reimers, and Harris (2015)

Stewart, N., Reimers, S., & Harris, A. J. L. (2015). On the origin of utility, weighting, and discounting functions: How they get their shapes and how to change their shapes. Management Science, 61, 687-705. [doi: 10.1287/mnsc.2013.1853](http://dx.doi.org/10.1287/mnsc.2013.1853)

Thank you to the Decision Analysis Society for awarding this paper the [2017 Decision Analysis Publication Award!](https://www.informs.org/Recognizing-Excellence/Community-Prizes/Decision-Analysis-Society/Decision-Analysis-Publication-Award)

## Column headings

* order: A unique identifier for each participant

* sub_no: The number handed out by the server against which cond was set. Not guaranteed unique because a timed out sub_no might still get submitted after that sub_no has been remarked as free.

* cond: 0 = positive skew condition; 1 = other condition

* trial: The ordering of trials

* id: A unique identifier for each choice

* p, x, q, and y: For a choice of (p, x) vs. (q, y). p < q and x > y in the non-catch choices without dominance

or 

* t, x, y, and u: For an intertemporal choice between x at time t or y at time u. x > y and t > u for non-catch trials

* choice: 1 = qy/uy chosen, 0 = px/tx chosen

## Sample sizes

We chose a number of subjects for an experiment, scheduled sessions, tested those who arrived, and only then looked at the data. We anticipated a large effect size for our first experiment, Experiment 1A, as range-frequency like effects tend to be quite robust. The effect size estimated from Experiment 1A (by using the random effects to give estimates of alpha for each participant) was Cohen's d = 1.5, which is indeed "large" by Cohen's labelling. A power calculation gives a sample size of 16 for a power of .8 or 26 for a power of .95. So we aimed for about 30 participants in each study. For Experiment 1C, which was the only on-line and non-incentivised study, we used a larger sample size.

[It is probably a foolish to power studies based on observed effect size.](http://datacolada.org/4)

## Erratum

Thank you to Despoina Alempaki for pointing out an error in the description of the analysis for Experiment 2B. In the Method section for Experiment 2B it states that "No participant violated dominance in more than 10% of catch trials, so all data were retained." This is wrong. In the analysis in the paper, three participants (ids 12, 17 and 18) were deleted for violating dominance on more than 10% of catch trials. A fourth participant (id 23) also violated dominance but was not deleted because I failed to see his or her rate was above 10%.

Deleting Participant 23 makes very little difference to the results. Differences between conditions remain significant. Here is a revised Section 6.5.2, with differences in red.

6.5.2. Results and Discussion. [Figure 5(b)](Figure_5b.pdf) shows that the weighting function in the positive-skew condition is more concave than the negative-skew condition. Modeling using power law weighting functions reveals a significant difference between conditions (χ2(1) = 119.6, p < 0.0001). Modeling with free weightings tested whether the weighting for the common probability 50% differed across conditions. The weighting of 50% is significantly higher in the positive-skew condition (χ2(1) = 22.7, p < 0.0001), consistent with the rank hypothesis.

Here is a revised [Figure B.1](Figure_B_1.pdf) where the confidence intervals in the Experiment 2B columns are slightly moved.


