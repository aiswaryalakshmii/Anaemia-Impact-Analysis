# Anaemia-Impact-Analysis
Causal analysis of anaemia reduction using Difference-in-Differences on district-level nutrition data, with interactive visualizations.

The file `fortification_dataset.xlsx` is a synthetic, district-level nutrition and health outcomes dataset across selected states of India, namely, Maharashtra, Rajasthan, Uttar Pradesh, Madhya Pradesh, and Bihar. It is designed to evaluate the impact of a wheat flour fortification programme implemented in the states. 
The data spans from 2021 to 2024 quarterly and includes both pre- and post-intervention periods, making it suitable for causal analysis techniques such as Difference-in-Differences (DiD). It covers 5 States and 40 Districts with a total of 640 observations.  
Variable Description
Programme Design Variables:
- Treatment: Classified based on intervened or not.
  - 1 = District received fortification intervention
  - 0 = Control district
- Post Intervention:
  - 1 = After programme rollout (from 2022-Q3 onward)
  - 0 = Before intervention
- Health & Nutrition Outcomes:
  - Anaemia Prevalence Pct: Percentage of population with anaemia in the district.
  - Avg Hb Level Gdl: Average haemoglobin level (g/dL), indicating nutritional status.
  - Child Stunting Rate Pct: Percentage of children with stunted growth (chronic malnutrition).
- Programme Implementation Indicators:
  - Fortified Flour Coverage Pct: Percentage of population consuming fortified wheat flour.
  - Compliant Mills Count: Number of mills adhering to fortification standards.
  - Awareness Score: Composite score (0–100) measuring community awareness about nutrition and fortification.
- Programme Reach Beneficiaries: Estimated number of individuals reached by the intervention in a given district-quarter. 

The file `Dashboard.html` is the visualization that explains the variablity across states and pre- and post-intervention through Difference-in-Differneces. It subtly shows the effectiveness and impact of the implemented programme.

_N.B: This is a synthetic dataset created for analytical and demonstration purposes. Values are generated to reflect realistic trends but do not represent actual field data._
