# Getting-Closer-Exploring-Pedestrian-Profiles-to-Predict-Crossing-Decisions

---

### **Exploratory Analysis**
1. **Demographics & Crossing**  
   Do certain age groups (*child, adult, senior*) have different probabilities of crossing?

2. **Gender Effect**  
   Does gender (*male, female*) affect the likelihood of crossing or waiting?

3. **Distraction Influence**  
   Are distracted pedestrians (*yes/no*) more likely to cross compared to attentive ones?

4. **Hand Signal Usage**  
   Does giving a hand signal increase the chance of crossing?

5. **Relative Position**  
   Are pedestrians closer to the road (*near, middle, far*) more likely to cross?

---

### **Behavioral & Contextual Factors**
6. **Dress Code & Crossing**  
   Does pedestrian dress style (*Casual vs Formal*) correlate with crossing behavior?

7. **Location Impact**  
   Are pedestrians on the sidewalk (*onSideWalk vs notOnSidewalk*) more likely to cross?

8. **Fashion Personality & Weight**  
   Do fashion personality or weight categories (even though some have limited values) show any relationship with crossing?

---

### **Behavioral & Demographic Analysis**



---

11. **Does distraction interact with age?**  
   Are *children* more likely to be distracted than *adults* or *seniors*, and how does that affect crossing?

12. **Gender & Hand Signal Interaction**  
   Do *males vs females* differ in their tendency to use a hand signal before crossing?

13. **Age & Relative Position**  
   Are *seniors* more likely to stand *far* from the curb while children stand *near*?

14. **Distracted vs Non-distracted Pedestrians**  
   Do distracted pedestrians have a higher chance of crossing without hand signals?

15. **Combined Risk Profiles**  
   What’s the crossing probability of a pedestrian who is *child + distracted + notOnSidewalk* compared to an *adult + attentive + onSidewalk*?

---

##  **Statistical & Hypothesis Testing**
16. **Chi-Square Tests**  
   Are categorical variables like *gender, distraction, location* significantly associated with crossing?

17. **Correlation Between Features**  
   Are some features correlated (e.g., *location* and *relative position*)?

18. **Conditional Probability**  
   What is the probability of crossing **given** distraction and hand signal presence?

19. **Bayesian Analysis**  
   Using Bayes’ theorem, how does the probability of crossing update when we know the pedestrian is distracted?

20. **Imbalance Check**  
   Is one class (*Crossed vs Waited*) dominating the dataset, and how does that affect prediction?

---

## **Modeling & Predictive Questions**
21. **Model Comparisons**  
   Which algorithm performs best at predicting crossing behavior? (Logistic Regression vs Random Forest vs XGBoost vs Neural Network)

22. **Feature Reduction**  
   If we drop low-variance features (like `weight` or `fashionPersonality`), does model accuracy improve?

23. **Interaction Effects in Models**  
   Do models perform better when we include interaction terms like *age × distraction*?

24. **Fairness & Bias**  
   Does the model treat males and females equally well in predictions (fairness evaluation)?

25. **Scenario Simulation**  
   Can we simulate “what-if” scenarios (e.g., *What if a distracted senior is near the curb?*) to estimate crossing likelihood?

---

## **Practical & Applied Questions**
26. **Safety-Oriented Profiles**  
   Which profiles of pedestrians are *least predictable* (high uncertainty in crossing behavior)?

27. **Critical Feature Combinations**  
   Which combination of features produces the **highest crossing probability**?

28. **Real-Time Prediction Feasibility**  
   Can the model predict crossing in real-time using only a subset of features (e.g., *age, gender, distraction, position*)?

29. **Explainability (SHAP/LIME)**  
   Which individual factors explain a specific prediction for one pedestrian?  

30. **Generalization**  
    If we train the model on one dataset (say, *urban pedestrians*), will it generalize to *suburban or rural pedestrians*?

---



---

### **Predictive & Modeling Questions**
9. **Profile-Based Prediction**  
   Can we build a **classification model** (e.g., Logistic Regression, Decision Tree, Random Forest) to predict if a pedestrian will cross based on their profile?

10. **Feature Importance**  
   Which features (age, gender, distraction, hand signals, location, etc.) are the **strongest predictors** of crossing behavior?

---

These questions cover **EDA**, **hypothesis testing**, and **predictive modeling**.  
You could start by answering the simpler **statistical questions** (1–8), then move to **machine learning** (9–10).  
