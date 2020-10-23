# Predicting COVID-19 distribution in Morocco
## Abstract
The current epidemic of coronavirus disease (COVID-19) has become a global crisis due to its rapid and widespread contamination worldwide. A good understanding of disease dynamics would significantly improve the control and prevention of COVID19. The unique features of this pandemic have limited the applications of all existing models We used, for the Moroccan context, a Markov chain system and a SIR modelfor predicting the distribution of the disease. The same stochasticmodel was used in Mexico, it characterizes the probabilitydistribution and the estimation of cases through a differentialequation (modified SIR model). With this model, we will be ableto characterize the disease and its evolution in order to be moreprepared and to promote more logical actions on the part ofpolicy makers than on the part of the general population.
## SIR Model
An SIR model is an epidemiological mathematical modelused to model and predict the spread of infectious diseases(here we have as COVID-19 case), it divides the population to three compartments: S, I, R, (Susceptible, Infectious, or Recovered/Removed). Each member of the population typically progresses from susceptible to infectious to removed. This can be shown as a flow diagram in which the boxes represent the different compartments and the arrows the transition between compartments.
## Discrete Markov Chain
This chain consists of 12 states which correspond to the regions in the territory division of Morocco.
### Stochastic matrix (HEATMAP)
<p align="center">
  <img src="https://user-images.githubusercontent.com/63251172/97018010-85b41e00-1546-11eb-99ba-6731f9ba29ea.png">
</p>

### Probability distribution simulation of COVID-19 till last measurement made at 14/12/2020
<p align="center">
  <img src="https://user-images.githubusercontent.com/63251172/97018236-d297f480-1546-11eb-940b-6c3973878d22.png">
</p>

### Graph showing the probability distribution of COVID-19 in a temporal perspective until 14/12/2020
<p align="center">
  <img src="https://user-images.githubusercontent.com/63251172/97018883-8ef1ba80-1547-11eb-9b9e-ea57c74f8e0f.png">
</p>

### Graph comparing the probability distribution of COVID-19 in Moroccan population between 21/03/2020 and the last measurement made at 04/12/2021
<p align="center">
  <img src="https://user-images.githubusercontent.com/63251172/97018999-b3e62d80-1547-11eb-8e91-a28ae1c707cd.png">
</p>

### Probability distribution of every state at 04/12/2021
<p align="center">
  <img src="https://user-images.githubusercontent.com/63251172/97019014-b8124b00-1547-11eb-92d3-42d50b657238.png">
</p>

## Conclusion
To sum up, our research was based on a Mexican research that predicts COVID-19 distribution in Mexico through a discrete and time-dependent Markov chain and an SIR-likemodel. We attempt to show stochastic model characterizing the probability distribution of cases in Morocco by regions and the estimated number of cases in Morocco through a differential equation model (modified SIR model), thus characterized the disease and its course in Morocco in order to display more preparedness and promote more logical actions by both the policy makers as well as the general population. By analyzing our models that we produces, the results were significant besides there is a small difference between predictions and reality of COVID19 evolution in Morocco due to Moroccan government decisions applied to reduce the spread of the epidemic that explains the importance of prediction researches in order to avoid very big loss in society.

## REFERENCES
<ul>
  <li>[1] Herman Scheepers, Markov Chain Analysis and Simulation usingPython, towardsdatascience Blog.</li>
  <li>[2] Alfonso Vivanco-Lira and Leon Guanajuato, Predicting COVID-19distribution in Mexico through a discrete and time-dependent Markovchain and an SIR-like model, Mexico.</li>
  <li>[3] https://www.bbc.com/news/world-africa-52801190.</li>
  <li>[4] https://ledesk.ma/datadesk/covid-19-le-maroc-evite-6-000-morts-le-picprevu-fin-avril-debut-mai-avec-800-deces-cumules</li>
  <li>[5] https://www.doctorsfornutrition.org/post/nutrition-in-the-time-of-covid-19</li>
  <li>[6] https://ourworldindata.org/coronavirus</li>
  <li>[7] https://infogram.com/evolution-du-covid-19-au-maroc-1h7j4drq7dlv2nr</li>
  <li>[8] https://scipython.com/book/chapter-8-scipy/additional-examples/the-sirepidemic-model</li>
  <li>[9] https://en.wikipedia.org/wiki/Compartmentalmodelsinepidemiology#TheSIRmodel</li>
  <li>[10] https://medium.com/@djconnel14663/seird-model-of-covid-19-596e6754c2c4</li>
</ul>
