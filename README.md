
# Hospital Outreach Analytics: Yatharth Super Specialty Hospital

**A Business Data Management (BDM) Project**

## Project Overview
Data-driven spatial and demographic analysis of patient registration data to optimize outreach strategies and drive revenue growth for a 200-bed multi-specialty hospital in Faridabad, India.

Data Collection Period: July 2024 - May 2025 (11 months)

Dataset: 10,319 patient records from Faridabad

Code Link: [Click here](https://colab.research.google.com/drive/1po9ECYvxywYR8Ilu_k4CnccUk9hBcYlj?usp=sharing)

## Objectives
- Analyse regional patient footfall over time
- Identify high, moderate and low contributing regions
- Study age-gender distribution of patients
- Identify seasonal variations in the patient footfall
- Provide actionable insights to enhance hospital outreach

## Key Insights

### SPATIAL TRENDS:
1. High-Performing Areas

- Sector 88 and nearby sectors (84, 87, 89) contribute 61.7% of patients
- Expected since hospital is located in Sector 88
- Shows strong local presence within 2-3 km radius

2. Underperforming Areas

- Ballabgarh, Palwal, Old Faridabad, NIT, Nuh contribute only 30% combined
- Gap suggests low awareness, weak referral networks, or competition
- Distance doesn't explain it: Palwal (40 km) performs better than Old Faridabad (12 km)

3. Seasonal Patterns

- October 2024: Patient inflow drops during Diwali (opportunity for pre-festive campaigns)
- March 2025: Inflow increases due to seasonal illnesses (offsets Holi impact)
- Regional recovery varies: Palwal growing, Ballabgarh declining (needs targeted strategies)


### DEMOGRAPHIC TRENDS:
1. Adult/Elderly Focus

- Nearly 80% of patients are Young Adults, Adults, or Elders
- Strong positioning for chronic disease and geriatric care
- Over-reliance on this segment

2. Pediatric Gap

- Only 20% are children/teenagers
- Low even in nearby areas—not a distance issue
- Indicates poor awareness and weak pediatric referral networks

4. Gender Balance

- Overall balanced (51.6% female, 48.4% male)
- Shows inclusive, gender-sensitive service delivery

## Methodology

### Problem 1: Spatial Analysis

- Technique: Rule-based text matching with Keyword Filtering
- Process: Address parsing -> Keyword matching -> Region classification
- Output: Patients grouped into High (Greater Faridabad), Moderate, and Low contributing regions

### Problem 2: Demographic Analysis

- Technique: Age and Gender based categorical classification
- Groups: 6 age groups (Toddlers, Children, Teenagers, Young Adults, Adults and Elders)
- Cross-Analysis: Gender distribution with each demographics
- Output: Service utilization patterns by demographics

### Tools Used

- Python: Pandas, NumPy for data processing
- Visualization: Plotly Express, Plotly Graph Objects
- Environment: Google Colab

## Recommendations

1. Regional Outreach (Problem 1)

    - Health camps in underserved regions (bi-weekly rotation)
    - Referral network with local practitioners
    - Geo-targeted digital marketing (Facebook, Google Ads)
    - Seasonal campaign planning around festivals and disease cycles

2. Pediatric Enhancement (Problem 2)

    - Partnership with schools for health programs
    - Child-friendly hospital redesign (play areas, rewards)
    - Pediatric specialist marketing campaigns

3. Gender-Inclusive Programs (Problem 2)

    - Elderly women's health clinics
    - Mother-daughter wellness packages
    - Girl child healthcare equality campaigns
    - Women's wellness center establishment

4. Continuous Monitoring

- Real-time dashboard for patient flow tracking
- Quarterly strategic reviews
- Campaign ROI measurement
- Competitive intelligence monitoring

## Limitations

- Temporal Data: 11 months of data provides directional insights; 2-3 years of data is required for robust trend confirmation
- Address Quality: Text-based matching due to missing pin codes and city makes the classification less accurate
- Competition: Qualitative discussion or systematic competitive analysis is not included

## License

This project is for academic purposes. Patient data has been anonymized and access is restricted to authorized personnel only in compliance with healthcare data protection regulations.

## Acknowledgments

- Yatharth Super Specialty Hospital, Faridabad for providing access to anonymized patient data
- IIT Madras Online BS Degree Program faculty for guidance
