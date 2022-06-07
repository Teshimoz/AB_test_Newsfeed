# A/A test, A/B test on Newsfeed application 
We have an application with newsfeed. There are users watching posts, users can like some post, so we have `views` and `likes`<br> 
Will measure the involvement of our users by CTR metric - likes divided by views.
The new recommendation algorithm was applied for part of our users.<br>
Gererally we have two main parts ansqering twose questions:

* A/A-test: If were our groups really the same before new algorithm?
* A/B-test: Is the group with new algo different from the control group?

Approaches used in this project:
* Simulation of 10000 A/A tests (subsets with replacing)
* Distribution of simulated p-values checking
* Poisson Bootstrap
* Smoothed metric
* Bucket transformation
* Linearized metric

<i>*The data we use generated as a part of Analyst Simulator from Karpov Cources, <br>
  avaliable for students on server</i>
