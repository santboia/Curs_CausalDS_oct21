# Causal Data Science workshop

[key details](#key) | [intended audience](#audience) | [learning goals](#ilos) | [keywords](#keywords) | [contents](#contents) | [further reading](#biblio)

## <a name="key"></a>Key details

- **Time:** 9:00 - 14:00, Friday 22 October 2021

- **Location:** Facultat de Matemàtiques i Informàtica, Universitat de Barcelona, Gran Via de les Corts Catalanes 585, Barcelona - [map](https://www.google.com/maps/place/Universitat+de+Barcelona/@41.3870742,2.1630907,17z/data=!4m5!3m4!1s0x0:0xba3e12058122ec95!8m2!3d41.386608!4d2.1640203?hl=ca)
- **Webpage:** http://www.ub.edu/datascience/cdsw

## <a name="audience"></a>Intended audience / Knowledge prerequisites

This workshop is addressed at practicing data scientists working in the industry or non-academic organisations interested in broadening their skillset with an introduction to causal data science and causal inference.

## <a name="ilos"></a>Intended Learning Outcomes

At the end of this workshop, attendees will be able to:

- distinguish prediction problems from counterfactual, **decision-making queries**;
- state the **fundamental problem of causal inference** and provide examples where it relates to their business;
- explain the issues raised by **confounding**, and discuss causal inference methods to deal with them;
- relate to business use cases the **added value** that causal data science can contribute in different business contexts  (e.g., product personalisation/recommenders, uplift modeling, customer segmentation);

## <a name="keywords"></a>Keywords

- causal inference; confounding; counterfactuals; 
- data-driven decision making; explainable AI; fairness in ML/AI;
- causal graphs, DAGs; do-calculus;
- potential outcomes; propensity scores;
- DoWhy, DoubleML, CausalML; 
- double machine learning; doubly robust learning;

## <a name="contents"></a>Contents

1. Basic concepts of Causal Inference
2. Potential outcomes. Matching and Propensity score methods. Business case 1 (customer segmentation).
3. Microsoft's DoWhy library. Double ML. Doubly Robust estimators. Business case 2 (preventing cancellations).
4. Hands-on practice / group work
5. Wrap up and closing remarks

## <a name="biblio"></a>Further reading / viewing

### Reference materials

- Neal, Brady: Introduction to Causal Inference [online course with videos](https://www.bradyneal.com/causal-inference-course)
- Cunningham, Scott (2021): [*Causal Inference: The Mixtape*](https://mixtape.scunning.com/): very recent reference textbook; includes learning materials on Github [in R](https://github.com/scunning1975/mixtape_learnr/), and [in Python](https://github.com/tomcaputo/mixtape_learnr) (by Tom Caputo).
- Riederer, Emily (2021): [*Causal design patterns for data analysts*](https://emilyriederer.netlify.app/post/causal-design-patterns/): a blog entry with a very good overview of propensity score weighting and other statistical methods to deal with biased samples.
- Pearl, Judea (2016): *Causal Inference in Statistics: A Primer* ([Amazon.es](https://www.amazon.es/Causal-Inference-Statistics-Judea-Pearl/dp/1119186846), [Fnac.es](https://www.fnac.es/livre-numerique/a5063828/Causal-Inference-in-Statistics)): textbook for those not scared by maths.
- Pearl, Judea (2018): *The Book of Why* ([Laie.es](https://www.laie.es/es/libro/el-libro-del-porque/9788412138320/930564), [Fnac.es](https://www.fnac.es/a7556139/Judea-Pearl-El-libro-del-porque), [Amazon.es](https://www.amazon.es/Book-Why-Science-Cause-Effect/dp/0141982411/)): introductory text to share with bossess or colleagues with an aversion for maths or computing.
- Microsoft: [EconML](https://econml.azurewebsites.net/), [DoWhy](https://microsoft.github.io/dowhy/index.html): modern Python libraries implementing a broad range of causal inference methods.

### Example business cases

- Netflix's testing of cover images [(Basilico, RecSys2020)](https://www.slideshare.net/justinbasilico/recent-trends-in-personalization-at-netflix)
- Customer segmentation at [DoorDash](http://medium.com/@DoorDash/switchback-tests-and-randomized-experimentation-under-network-effects-at-doordash-f1d938ab7c2a)

- Preventing churn like a bandit [(Oostra, 2021)](https://medium.com/bigdatarepublic/preventing-churn-like-a-bandit-49b7c51b4929): Good, detailed introduction. Uses propensity score weighting.

- Added-value of discount coupons:  Lift analytics at Kausa [(Klaput, 2021)](https://towardsdatascience.com/how-causal-inference-lifts-augmented-analytics-beyond-flatland-95648fe30055): "simple" customer segmentation with CATEs. *Good text as it contrasts prediction problems with business intelligence*; uses simple Python tools.

- Price elasticity [(Roemheld, 2021)](https://towardsdatascience.com/causal-inference-example-elasticity-de4a3e2e621b): advanced text. Introduces and uses double ML.

