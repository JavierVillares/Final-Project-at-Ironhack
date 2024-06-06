# Final-Project-at-Ironhack 2024

In this project I have been adressing my concern of whether Overpopulation is going to be a problem. After some reasearch and finding some good CSV o give me an overview of the world state and the trend in the last 40 years... This was my reaction looking at Birth rates:
![text]([https://www.google.com/url?sa%3Di%26url%3Dhttps%3A%2F%2Fgiphy.com%2Fexplore%2Fbaby%26psig%3DAOvVaw1WQ3PhCwg5AzARWX6t8Seo%26ust%3D1717770628894000%26source%3Dimages%26cd%3Dvfe%26opi%3D89978449%26ved%3D0CBQQjRxqFwoTCPj9wrSYx4YDFQAAAAAdAAAAABAQ](https://media3.giphy.com/media/ph6ewybUlGbW8/giphy.gif?cid=6c09b9525y2i9mppzez3mhd41caskj4g8pxyjctaakurta5b&ep=v1_gifs_search&rid=giphy.gif&ct=g))

And then I asked myself...
![text](https://www.google.com/url?sa%3Di%26url%3Dhttps%3A%2F%2Fgiphy.com%2Fexplore%2Fbut-why%26psig%3DAOvVaw3BFruPpNLzAWejFrCosMJm%26ust%3D1717771291040000%26source%3Dimages%26cd%3Dvfe%26opi%3D89978449%26ved%3D0CBQQjRxqFwoTCLDJv--ax4YDFQAAAAAdAAAAABAX)

After some thinking I have to go on a quest for answers... And here is my story. 

I first started to look for reasons of commonalities with countries that have a low birthrate. I found that most of them were quite westernized. So i looked into GPD per capita, Average Age, Growth Rates, Death rates AND Education level. 

![text](https://www.google.com/url?sa%3Di%26url%3Dhttps%3A%2F%2Fgiphy.com%2Fexplore%2Ffast-typing%26psig%3DAOvVaw1K4QydxgBydkmSBmwxub7F%26ust%3D1717771587894000%26source%3Dimages%26cd%3Dvfe%26opi%3D89978449%26ved%3D0CBQQjRxqFwoTCMiV9Pubx4YDFQAAAAAdAAAAABAE)


It worked wonders afte making sure all countries were accounted for. Data was clean working perfecly and with Nulls values. I started to do machine learning and finding the best options that had the highest R^2 score and lowest MSE scores. Found the one (linear regression with a standard scaler). Predicted 20 years into the future and did another prediction of WHEN we would reach a negatavice growth rate. We are just 43 years from getting to a negative growth rate. But That is just pure speculation since it's quite far away into the future and we can't really know for sure...
Only time will tell. 

The results are presented in Tableau. 



CREDITS and Licences: 

https://data.worldbank.org/indicator/SP.DYN.CDRT.IN?end=2021&start=1960&view=chart

The Creative Commons Attribution 4.0 International license allows users to copy, modify and distribute data in any format for any purpose, including commercial use. Users are only obligated to give appropriate credit (attribution) and indicate if they have made any changes, including translations. CC-BY 4.0, with the additional terms below, is the default license for all Datasets produced by the World Bank itself and distributed as open data.

All users of these Datasets under the CC-BY 4.0 License also agree to the following mandatory terms: Any and all disputes arising under this License that cannot be settled amicably shall be resolved in accordance with the following procedure:

Pursuant to a notice of mediation communicated by reasonable means by either You or the Licensor to the other, the dispute shall be submitted to non-binding mediation conducted in accordance with rules designated by the Licensor in the copyright notice published with the Work, or if none then in accordance with those communicated in the notice of mediation. The language used in the mediation proceedings shall be English unless otherwise agreed.
If any such dispute has not been settled within 45 days following the date on which the notice of mediation is provided, either You or the Licensor may, pursuant to a notice of arbitration communicated by reasonable means to the other, elect to have the dispute referred to and finally determined by arbitration. The arbitration shall be conducted in accordance with the rules designated by the Licensor in the copyright notice published with the Work, or if none then in accordance with the UNCITRAL Arbitration Rules as then in force. The arbitral tribunal shall consist of a sole arbitrator and the language of the proceedings shall be English unless otherwise agreed. The place of arbitration shall be where the Licensor has its headquarters. The arbitral proceedings shall be conducted remotely (e.g., via telephone conference or written submissions) whenever practicable

https://ourworldindata.org/explorers/population-and-demography?facet=none&Metric=Birth+rate&Sex=Both+sexes&Age+group=Total&Projection+Scenario=None&country=CHN~IND~USA~IDN~PAK~NGA~BRA~JPN

ATTRIBUTION 4.0 INTERNATIONAL
  CC BY 4.0
Deed

United Nations, World Population Prospects (2022) – processed by Our World in Data

United Nations, World Population Prospects (2022) – processed by Our World in Data. “Birth rate” [dataset]. United Nations, World Population Prospects (2022) [original data].

https://ourworldindata.org/grapher/gender-gap-education-levels?country=~JPN

Multiple sources compiled by World Bank (2024); Lee and Lee (2016) – with major processing by Our World in Data

Multiple sources compiled by World Bank (2024); Lee and Lee (2016) – with major processing by Our World in Data. “Boys in primary education” [dataset]. UNESCO (via World Bank), “World Development Indicators”; Lee and Lee, “Human Capital in the Long Run” [original data].

ATTRIBUTION 4.0 INTERNATIONAL
  CC BY 4.0
Deed


https://ourworldindata.org/age-structure

Data source: United Nations, World Population Prospects (2022)

ATTRIBUTION 4.0 INTERNATIONAL
  CC BY 4.0
Deed

https://ourworldindata.org/economic-growth

Data source: Feenstra et al. (2015), Penn World Table (2021)

ATTRIBUTION 4.0 INTERNATIONAL
  CC BY 4.0
Deed
