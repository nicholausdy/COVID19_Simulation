# COVID-HACKATHON 2020
## SARS-COV-2 Simulation of Indonesia
### Overview
A system is developed to predict the on-going pandemic that is currently experienced by the world.
The system is using a Monte-Carlo mathematical model, in order to reduce 
data overfit, the obtained data is then applied to RNN data learning. 
This will lead to more accurate system to predict Indonesia's current projectory of casualties to help local authorities to prepare measurement that would prevent the spreading of the pandemic.
<br>This system is created in event of COVID-HACKATHON 2020 dating 27 March to 29 March.
### Creator
- Cindy A.
- G. Gilbert
- Nicholaus D.Y.
### Data Source
- [Corona Virus World-Wide](https://www.worldometers.info/coronavirus/ "Corona Virus Cases World-wide")
- [Japanese Corona Case Per Day](https://corona.lmao.ninja/v2/historical/japan)
- [Italy Corona Case](https://pomber.github.io/covid19/timeseries.json)
- [Parameter Source_1](https://www.who.int/docs/default-source/coronaviruse/who-china-joint-mission-on-covid-19-final-report.pdf)
- [Parameter Source_2](https://www.cdc.gov/mmwr/volumes/69/wr/mm6912e2.htm)
### Main Function
1. The Monte-Carlo system will make a projection of cases from the parameters given.
2. The RNN system will then make use of the data generated from Monte-Carlo system and then use it as template.
3. The RNN system will also take account of historical data from other countries to project the prediction.
### Usage
1. To predict which country needs more preparation.
2. To alarm countries of the potential risk of pandemic.
3. To inform the citizen of the expected range of pandemic so they may remain calm that it is in the prediction range.
### Note/Justification
1. The RNN uses historical data that has decreasing amount of daily case to a newly infected country.<br>
2. This way, the country that has decreasing amount of daily case can be assumed to had reached the shaped of the pandemic event.<br>
3. The policy regarding the handling of COVID-19 of Japanese government is observed to be similar with that of Indonesia's.
4. The death and recovery rate were picked from the country that has the similar rate with Indonesia, in this case Italy was chosen.
