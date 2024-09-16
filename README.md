# CMS Data Analytic case study
I designed a Power BI based potential customer identification tool that I would like to share with the sales team.<br /> It has built-in filters with 4 key metrics  
![image](https://github.com/user-attachments/assets/d381ec8a-8523-45dc-a21a-74954780f6ad)

## Introduction
I started the case study by learning about Clipboard from open-source research and experimented with the app. I understood Clipboard aims to provide better solutions to the staffing problem in the healthcare system. Clipboard serves as a platform to connect supply (healthcare workers, like RN) to demand (healthcare providers). <br />
So, I reached a conclusion that the main responsibility of the sales team at Clipboard is to promote this application to healthcare providers and ask them to post their contractor needs on the platform. 

## Recommendation
I wanted to give one very simple recommendation: a short list of 5 potential customers.
| Provider Name                                | Phone Number  | Number of Certified Beds | Bed Utilization Rate | Contract Percentage |
|----------------------------------------------|---------------|--------------------------|----------------------|---------------------|
| NORTHAMPTON COUNTY-GRACEDALE                 | 6107461900    | 688                      | 59%                  | 54%                 |
| PARKHOUSE REHABILITATION AND NURSING CENTER  | 6109488800    | 467                      | 62%                  | 34%                 |
| OHIO VETERANS HOME                           | 4196252454    | 427                      | 42%                  | 31%                 |
| JOHN J KANE REGIONAL CENTER-MC               | 4126758620    | 360                      | 55%                  | 38%                 |
| JOHN J KANE REGIONAL CENTER-SC               | 4124293020    | 311                      | 61%                  | 47%                 |


## Analysis
THREE METRICS: <br />
- **Hospital Size** = Number of Certified Beds
- **Bed Utilization Rate** =  (Average Number of Residents Per Day) / (Number of Certified Beds)
- **Contract Percentage** =  (Average Contract Work Hours) / (Average Total Work Hours) <br />

The higher the number of certified beds, the larger the provider, the more money Clipboard can charge.
The lower the bed utilization rate, either the local demand is low or the provider need more supply of workers, this is where Clipboard comes in.
The higher the contract percentage, the more likely the provider will be open to accept Clipboard.
 

Below are some visualization from the dataset during the initial exploration stage.<br />
Pie Chart 1: How much of the work is done by contract workers? <br />
![image](https://github.com/user-attachments/assets/fca30daa-7ace-4326-a6ee-282a360df5e0)
Pie Chart 2: How providers differentiate in their reliance on contract workers? <br />
![image](https://github.com/user-attachments/assets/df51499c-2423-43a3-ab47-9b244017c9e2)
 
Contract workers takes up about 7.5% of the market, and more than 75% of providers have contract-hour-percentage under 10%.<br />
I merged the provider detail dataset and generated two more metrics.
