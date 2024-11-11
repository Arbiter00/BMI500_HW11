# BMI500_HW11
BMI 500 Course Homework Week11

## Author Information
**Name**: Yuxiang Lai  
**Contact**: ylai76@emory.edu

## Question Selected
**Question**: Sensitivity Analysis of the SEIR Model with Births and Deaths (Section D and E)

## Key Insights
The SEIR model analysis provided critical insights into how introducing an exposed compartment and including birth and death rates influence the dynamics of a pandemic. The sensitivity analysis demonstrated:
- **Infection Peaks**: The timing and magnitude of peak infections are highly sensitive to changes in the transmission rate $(\beta)$ and recovery rate $(\gamma)$.
- **Total Infections**: Variations in $(\beta)$ and $(\gamma)$ affect the pandemic's total number of infected individuals.
- **Pandemic Waves**: The model indicated that multiple waves of infection could occur with certain parameter values, resembling real-world pandemic behavior.

## Comparative Model Performance
Comparisons between the SIR and SEIR models highlighted that:
- The SEIR model, which includes an exposed compartment, provides a more realistic simulation of disease dynamics by modeling the incubation period.
- Inclusion of birth and death rates adds complexity and realism, showing how population turnover impacts the long-term behavior of the disease.

## Relevance to Model-Based Machine Learning
This work underscores the importance of compartmental models in understanding and predicting the behavior of epidemics. In machine learning, such models:
- **Provide Structured Priors**: They inform the design of generative models that can be fitted to real-world data.
- **Support Simulations**: Allow testing of various "what-if" scenarios that guide public health policies.

By incorporating differential equations into model-based machine learning, predictive performance can be enhanced for problems involving temporal dynamics.

## Suggestions for Future Modeling Improvements
To improve upon the current SEIR model:
- **Heterogeneity in Contact Rates**: Introduce varying contact rates across different population subgroups.
- **Stochastic Elements**: Add randomness to model real-life uncertainties and fluctuations in disease spread.
- **Vaccination Strategies**: Incorporate vaccination to study its impact on infection control and herd immunity.
- **Agent-Based Modeling**: Transition to agent-based models for more granular simulations that capture individual behaviors.

These enhancements would make the model more adaptable for public health planning and more representative of complex real-world scenarios.
