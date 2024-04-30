# Mortality Patterns Analysis in Tennessee Counties (2019-2021) 📊

🔍 **Welcome to the Mortality Patterns Analysis repository! Here, we delve into the complexity of mortality rates across Tennessee counties from 2019 to 2021. Our goal is to uncover insights into mortality patterns and identify key factors driving these variations. We employ a range of advanced predictive models to shed light on this critical public health issue.**

## Project Overview 📋
Mortality rates are a crucial indicator of a region's overall health and well-being. In this project, we explore mortality patterns in Tennessee counties over a three-year period, aiming to understand the underlying factors contributing to variations in mortality rates. By leveraging extensive datasets on mortality rates and demographics, we seek to provide actionable insights for healthcare policymakers and practitioners to inform targeted interventions and resource allocation strategies.

## Interactive Visualizations 📊
- **TN County Map:** Explore an interactive map of Tennessee counties, showcasing life expectancy for each county. This visualization provides valuable insights into regional disparities in mortality rates.
- **3D Plot:** Dive into an interactive 3D plot showcasing mortality rates across Tennessee counties over time. This visualization offers a unique perspective on temporal trends in mortality patterns.

## Key Results 📈
We've uncovered fascinating insights through our predictive modeling efforts. Here are the Mean Squared Error (MSE) values for some of our key models:

- **Linear Regression**
  - MSE: 0.9538
- **Gradient Boosting**
  - MSE: 0.4456
- **Random Forest**
  - MSE: 0.5510

These values serve as a testament to the predictive power of our models in capturing and understanding mortality patterns in Tennessee counties.

---

## How to Use 🛠️
1. **Clone the Repository:** Begin by cloning this repository to your local machine.
2. **Install Dependencies:** Ensure you have the required dependencies installed as specified in requirements.txt.
3. **Explore the Code:** Dive into the Jupyter notebooks within the Code directory to explore data preprocessing steps, model training, and evaluation.
4. **Analyze Results:** Take a deep dive into the visualizations and analysis results presented in the Results directory.
5. **Contribute:** Feel inspired? Contribute to the project by opening issues, proposing enhancements, or submitting pull requests.

## Future Directions 🔍
- **Model Refinement:** Continuously refine and optimize our predictive models to improve accuracy and robustness.
- **Data Expansion:** Explore additional datasets and variables to enrich our understanding of mortality patterns.
- **Policy Implications:** Translate our findings into actionable policy recommendations to address public health challenges effectively.

## Data Sources 📦
The data used in this analysis were sourced from the following sources:
- [County Health Rankings & Roadmaps](https://www.countyhealthrankings.org/health-data/tennessee/data-and-resources)
- [Tennessee Department of Health - Death Statistics](https://www.tn.gov/health/health-program-areas/statistics/health-data/death-statistics.html)

## Literature Review 📚
1. **Woolf, S. H., & Schoomaker, H. (2019).** Life expectancy and mortality rates in the United States, 1959-2017. *Jama, 322(20), 1996-2016.*
2. **Marmot, M., & Bell, R. (2011).** Social determinants and dental health. *Advances in dental research, 23(2), 201-206.*
3. **Wilkinson, R. G. (1992).** Income distribution and life expectancy. *BMJ: British Medical Journal, 304(6820), 165.*
4. **Judge, K. (1995).** Income distribution and life expectancy: a critical appraisal. *Bmj, 311(7015), 1282-1285.*
5. **Dwyer-Lindgren, L., et al. (2022).** Life expectancy by county, race, and ethnicity in the USA, 2000–19: a systematic analysis of health disparities. *The Lancet, 400(10345), 25-38.*
6. **Johnson, C. O., et al. (2022).** Life expectancy for White, Black, and Hispanic race/ethnicity in US states: trends and disparities, 1990 to 2019. *Annals of internal medicine, 175(8), 1057-1064.*
7. **Singh, G. K., & Lee, H. (2021).** Marked disparities in life expectancy by education, poverty level, occupation, and housing tenure in the United States, 1997-2014. *International Journal of Maternal and Child Health and AIDS, 10(1), 7.*
8. **Rohe, W. M., et al. (2013).** The social benefits and costs of homeownership: A critical assessment of the research. *The affordable housing reader, 40(1), 145-192.*
9. **Singh, G. K., & Siahpush, M. (2014).** Widening rural–urban disparities in life expectancy, US, 1969–2009. *American journal of preventive medicine, 46(2), e19-e29.*
10. **Terashima, M., et al. (2014).** What type of rural? Assessing the variations in life expectancy at birth at small area-level for a small population province using classes of locally defined settlement types. *BMC Public Health, 14, 1-10.*
11. **Michel, J. P., et al. (2010).** Vaccination and healthy ageing: how to make life-course vaccination a successful public health strategy. *European Geriatric Medicine, 1(3), 155-165.*
12. **Ozawa, S., et al. (2017).** Estimated economic impact of vaccinations in 73 low-and middle-income countries, 2001–2020. *Bulletin of the World Health Organization, 95(9), 629.*

## Key Correlations to Life Expectancy 📈
After cleaning and preprocessing the data, we identified the following top correlations to life expectancy in Tennessee counties:
- 80th Percentile Income
- 20th Percentile Income
- % Some College
- % Asian
- Dentist Rate
- # Non-Hispanic White
- % Vaccinated
- # Rural
- # Homeowners
- Labor Force
- # Primary Care Physicians
- # Associations
- % Excessive Drinking
- # Dentists
