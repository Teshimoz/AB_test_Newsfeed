# A/A test, A/B test on Newsfeed application 
<b>Rendered notebook:</b><br>
https://nbviewer.org/github/Teshimoz/AB_test_Newsfeed/blob/c76746ef7e78ba16608d81a1b7f5a1628b18f6bd/AB_test_Newsfeed.ipynb
<br><br>
<b>Project description:</b><br>
We have an application with newsfeed. There are users watching posts, users can like some post, so we have `views` and `likes`<br> 
Will measure the involvement of our users by CTR metric - likes divided by views.
The new recommendation algorithm was applied for part of our users.<br>
Gererally we have two main parts ansqering twose questions:

* A/A-test: If were our groups really the same before new algorithm?
* A/B-test: Is the group with new algo different from the control group?

Approaches used in this project:
* Simulation of many A/A tests (subsets with random sampeling with replacing)
* Distribution of simulated p-values checking
* Poisson Bootstrap
* Smoothed metric
* Bucket transformation
* Linearized metric

There are also screenshots from Superset [dashboards](dashboards) completed for this project.<br><br>
<i>*The data generated as a part of Analyst Simulator from Karpov Cources, <br>
  avaliable for students on server</i>
