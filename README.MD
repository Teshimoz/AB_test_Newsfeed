# Newsfeed application. A/A testing, A/B testing.
<b>Rendered notebook:</b><br>
https://nbviewer.org/github/Teshimoz/AB_test_Newsfeed/blob/e503e6398a177c02156a8b6ccf7a8ad577537da8/AB_test_Newsfeed.ipynb
<br><br>
<b>Project description:</b><br>
We have the application with a newsfeed. 
There are users watching posts, users can like some post, so we have `views` and `likes`<br>
The new recommendation algorithms were applied for part of our users.<br>
Will measure the involvement of our users by **CTR** metric - likes divided by views (individually and in groups).

Generally there are two main parts, ansqering next questions:

* A/A test: If were our groups really the same before new algorithm?
* A/B test: Is the group with new algo different from the control group?

Approaches used in this project:
* Simulation of many A/A tests (subsets with random sampeling with replacing)
* Distribution of simulated p-values checking
* Poisson Bootstrap
* Smoothed metric
* Bucket transformation
* Linearized metric

There are also screenshots from **Superset** [dashboards](dashboards) completed for this project. Include visualizations of DAU, CTR, Stickiness and more.<br><br>
<i>*The data generated as a part of Analyst Simulator from Karpov Cources, <br>
  avaliable for students on server</i>
