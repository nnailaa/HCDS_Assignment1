# HCDS_Assignment1

The goal of this project is to plot correlations and interesting findings from the State of Texas's data on coronavirus (vaccinations and cases) as compared to median household income, all on a county leve.

Here are the links to the datasets I used:
1. https://dshs.texas.gov/coronavirus/AdditionalData.aspx > https://dshs.texas.gov/coronavirus/TexasCOVID19CaseCountData.xlsx (the dataset)
2. https://dshs.texas.gov/immunize/covid19/COVID-19-Vaccine-Data-by-County.xls (the dataset)
3. https://www.census.gov/data-tools/demo/saipe/#/?s_state=48&s_county=&s_district=&s_measures=mhi

DataTypes/Description:  
For Vaccination File:  
- County Name <class 'str'>. All Texa Counties in alphabetical order.
- Public Health Region (PHR) <class 'str'>. PHR information on what region the county falls into.
- Total Doses Allocated <class 'str'> How many doses of the vaccine were allocated to the county by the federal government.
- Vaccine Doses Administered <class 'str'> How many vaccine Doses were administered in the county.
- People Vaccinated with at least One Dose <class 'str'> How many people received at least 1 shot of the covid vaccine.
- People Fully Vaccinated <class 'str'> How many people received at least 2 shots of the covid vaccine.
- People Vaccinated with at least One Booster Dose <class 'str'> How many people received the 3rd or even 4th shot of the covid vaccine.
- Population 6Mo+ <class 'str'> Population in the county that is over 6 months old. Will be considered as total population for the purpose of this data collection.
- Population 5+ <class 'str'> Population in the county that is over 5 years old.
- Population 12+ <class 'str'> Population in the county that is over 12 years old.
- Population, 16+ <class 'str'> Population in the county that is over 16 years old.
- Population, 65+ <class 'str'> Population in the county that is over 65 yearss old.
- Population, Phase 1A Healthcare Workers <class 'str'> Number of Healthcare workers in the county.
- Population, Phase 1A Long-term Care Residents <class 'str'> Number of Long-term Care Residents in the county.
- Population, 16-64 Any Medical Condition <class 'str'> Number of people aged 16-64 with a medical condition in the county
- Population, Education and Child Care Personnel <class 'str'> Number of people that work in Education or Childcare in the county
- Unnamed: 16 <class 'numpy.float64'> N/A
- Unnamed: 17 <class 'numpy.float64'> N/A
- Unnamed: 18 <class 'numpy.float64'> N/A
- Unnamed: 19 <class 'numpy.float64'> N/A
- Unnamed: 20 <class 'numpy.float64'> N/A
- Unnamed: 21 <class 'numpy.float64'> N/A
- Unnamed: 22 <class 'numpy.float64'> N/A
- Unnamed: 23 <class 'numpy.float64'> N/A
- Unnamed: 24 <class 'numpy.float64'> N/A
- Unnamed: 25 <class 'numpy.float64'> N/A

For Covid Cases Data:
- County <class 'str'> List of all counties in Texas
- Confirmed Cases <class 'numpy.int64'> Number of confirmed covid cases in the county.
- Probable Cases <class 'numpy.int64'> Number of likely covid cases in the county.
- Fatalities <class 'numpy.int64'> Number of covid related fatalities in the county.

For Census Income Data:
- Year <class 'numpy.int64'> Year of the information collected (all 2020)
- ID <class 'numpy.int64'> ID of the county
- County <class 'str'> Name of the County
- Median Income <class 'numpy.int64'> The value for the median income in the county
- 90% Confidence Interval <class 'str'> 90% confidence interval for the median income in the county.

### Potential issues or sources of bias:
There is always a posibility that some of the reported data is false. The number of cases are likely to be underrepresented and the vaccination records don't always coincide with general population, so there is also a chance that the Population Data is from 2020, not 2022.

