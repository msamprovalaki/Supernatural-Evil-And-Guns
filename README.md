# How the belief in supernatural evil has anything to do with the gun possession?

## Q1: Belief in Supernatural Evil Metric
In order to measure the belief in supernatural evil, we will use the answers to three questions asked by the participants in the survey:

1. Whether the respondent believes in the devil.
2. Whether the respondent believes in hell.
3. Whether the respondent believes in demons.

We will investigate how the answers to these three questions can be combined to a single metric,called SuperNaturalEvil.

## Q2: Variables Selection
Apart from the belief in supernatural evil metric, you will use several other variables to control your estimates. The variables are (see Appendix B of the original publication):

### Dependent Variables

- Ban on Semi-Auto Guns
- Ban on High-Capacity Ammo Clips
- Banning Civilian Handguns
- Support for Concealed Carry Laws
- More Armed Security at Schools
- More Teachers/Faculty having Guns
- More Gun Safety Programs
- Expanded Mental Health Screening
  
### Independent Variables

- Religious Variables
     - Attendance
  - Bible (Human Error, History and Fables)
  - Biblical Inerrancy
  - Biblical Literalism
- Religious Affiliation
  - Conservative Protestant
  - Mainline Protestant
  - Black Protestant
  - Catholic
  - Other
- No Affiliation
- Political Ideology
- Age
- Sex
  - Female
  - Male
- Race
    - White
    - Hispanic
    - African American/Black
    - Other
-Education
    - Less Than High School
    - High School or Equivalent
    - Some College
    - College Degree
    - Post-graduate Degree
- Household Income
- Marital Status
    - Not Partnered/Single
    - Married/Cohabitating
- Children
    - No kids under 18 in home
    - Kids under 18 in home
- Area Demographics
    - Small Town/Rural
    - Urban Area
- Region
    - South
    - Other Region

In the end, we should use the variables as shown in Table 1 and Table 2 of the original publication.

## Q3: Predict Support for Various Gun Policies

The gun policies are:
- Semi-Auto Weapons Ban
- High-Capacity Magazine Ban
- Cilivian Hand Gun Possession Ban
- Support for Concealed Carry
- More Armed Security at Schools
- More Teachers / Faculty with Guns
- Required Gun Safety Programs
- Expanded Mental Health Screening

Discussed the effects and the strengths of the various predictors (metric of supernatural evil, which is our focal variable, plus any others that you see significant) and cross-checked with Table 1 and Table 2 of the original publication.

The research was reported in The Economist, on November 6, 2021, under the title "Belief in supernatural evil is a strong predictor of pro-gun beliefs" (United States section), available at https://www.economist.com/united-states/2021/11/06/belief-in-supernatural-evil-is-a-strong-predictor-of-pro-gun-beliefs (you may access it after a free registration).

## Q4: Additional Estimations of the Strength of Predictors
In addition to logistic regression, we will run a complementary series of linear regressions to estimate the strength of the various predictors. In this way we will obtain standardized coefficients that are easier to interpret than the coefficients of logistic regression. For more on this approach, see:

Von Hippel, Paul, 2015. “Linear vs. Logistic models: which is better, and when?” Statistical horizons. July 5. Retrieved on December 3, 2021. https://statisticalhorizons.com/linear-vs-logistic.

## Q5: Compare with Decision Trees / Random Forest Estimators
Having worked with logistic and linear regression models, we carried out predictions by using Decision Trees / Random Forests of your choice; we might have to try different ones and picked up the best. Then, we checked if the predictors, primarily the belief in supernatural evil, make also a strong showing with the best model you have found.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.






