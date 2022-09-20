# HCDS_Assignment1

The goal of this project is to plot correlations and interesting findings from the State of Texas's data on coronavirus (vaccinations and cases) as compared to median household income, all on a county leve.

Here are the links to the datasets I used:
1. https://dshs.texas.gov/coronavirus/AdditionalData.aspx > https://dshs.texas.gov/coronavirus/TexasCOVID19CaseCountData.xlsx (the dataset)
2. https://dshs.texas.gov/immunize/covid19/COVID-19-Vaccine-Data-by-County.xls (the dataset)
3. https://www.census.gov/data-tools/demo/saipe/#/?s_state=48&s_county=&s_district=&s_measures=mhi

DataTypes/Description:
For Vaccination File:
County Name <class 'str'>
Public Health Region (PHR) <class 'str'>
Total Doses Allocated <class 'str'>
Vaccine Doses Administered <class 'str'>
People Vaccinated with at least One Dose <class 'str'>
People Fully Vaccinated <class 'str'>
People Vaccinated with at least One Booster Dose <class 'str'>
Population 6Mo+ <class 'str'>
Population
5+ <class 'str'>
Population
12+ <class 'str'>
Population, 16+ <class 'str'>
Population, 65+ <class 'str'>
Population, Phase 1A Healthcare Workers <class 'str'>
Population, Phase 1A Long-term Care Residents <class 'str'>
Population, 16-64
 Any Medical Condition <class 'str'>
Population, Education and Child Care Personnel <class 'str'>
Unnamed: 16 <class 'numpy.float64'>
Unnamed: 17 <class 'numpy.float64'>
Unnamed: 18 <class 'numpy.float64'>
Unnamed: 19 <class 'numpy.float64'>
Unnamed: 20 <class 'numpy.float64'>
Unnamed: 21 <class 'numpy.float64'>
Unnamed: 22 <class 'numpy.float64'>
Unnamed: 23 <class 'numpy.float64'>
Unnamed: 24 <class 'numpy.float64'>
Unnamed: 25 <class 'numpy.float64'>

For Covid Cases Data:
County <class 'str'>
Confirmed Cases <class 'numpy.int64'>
Probable Cases <class 'numpy.int64'>
Fatalities <class 'numpy.int64'>

For Census Income Data:
Year <class 'numpy.int64'>
ID <class 'numpy.int64'>
County <class 'str'>
Median Income <class 'numpy.int64'>
90% Confidence Interval <class 'str'>

### Potential issues or sources of bias:
There is always a posibility that some of the reported data is false. The number of cases are likely to be underrepresented and the vaccination records don't always coincide with general population, so there is also a chance that the Population Data is from 2020, not 2022.

