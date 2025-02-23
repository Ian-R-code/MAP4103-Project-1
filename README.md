# MAP4103-Project-1
Instructions to run code:

Questions are we answering: Sleep deprivation–can I track my mood,stress, or productivity score based upon sleep amount and caffeine? 
Can I accurately predict my level of productivity/mood based upon sleep and caffeine? 

Discussion:
How often do you wake up not feeeling fully rested? If you're among the 35% (1) of Americans who are defined by the CDC as sleep deprived (getting less than 7 hours of efficient sleep). The true amount maay be even higher than 35%. One common coping mechanism that people fall back on is caffeine consumption, typically through coffee. Caffeine blocks adenosine receptors, and lessens/lowers REM/Deep sleep levels (2, Bagheri, et. al. ). Caffeine is only a temporay solution therefore, blocking the recognition of the problem, but not solving the root of the issue (lack of sleep). Not only does caffeine hide the true issue, it can negatively affect health. In a study by Burke et. al (ref. 3), it's affects on the circadian rythm only solidified the common instruction to avoid it before bed time (caffeine's half-life is 6 hours). In a side note however, it may be useful to decrease jet lag, because of its effect on circadian rythms. 

References:
1) https://www.cdc.gov/sleep/data-research/facts-stats/adults-sleep-facts-and-stats.html
2) Bagheri Davisaraei, Y., Nateghi, S., Rashidipour, H., Raise-Abdullahi, P., & Rashidy-Pour, A. (2024). Coffee and sleep: Benefits and risks. Progress in Brain Research, 81–114. https://doi.org/10.1016/bs.pbr.2024.06.014
3) Burke, T. M., Markwald, R. R., McHill, A. W., Chinoy, E. D., Snider, J. A., Bessman, S. C., Jung, C. M., O’Neill, J. S., & Wright, K. P. (2015). Effects of caffeine on the human circadian clock in vivo and in vitro. Science Translational Medicine, 7(305). https://doi.org/10.1126/scitranslmed.aac5125 

Data Documentation:

Analysis:
Based on the three linear regression lines for Productivity score, Mood score, and Stress score, the biggest impacts on each are the time spent sleeping where bot hthe Productivity and Mood scores go up, which is good, and the stress score goes down, which is good. The start and end times for sleeping were opposite for Stress and Productivity which makes sense because oversleeping leads to being late for activities and work and less time to perform tasks. Moving to the K-Nearest Neighbors visualization, two criteria can be compared with the predicted result of either Productivity, Mood, or Stress score being shown. So both Mood and Producitvity are predicted to be lowerer when taking caffeine but Stress goes down. KNN was used because we had a large data set but a relatively small amount of criteria that needed looking at. Using K-Fold Cross-Validation the accuracy of our KNN model for Productivity, Mood, and Stress scores were around 50 percent for all three. Then a Neural Network was created for Productivity, Mood, and Stress, which is applicable becsue of the large data set to train it on, and it had an average accuracy of 52.3 percent. So both models are about as accurate as a coin flip which is not great. If we had more time we would have created a KNN model for more criteria at the same time and spent more time testing different k values to produce a more accurate model. Similarly with the Neural Network, spend more time improving its accuracy. 

Credits:
Ian-References 1 & 2, Analysis
Drew-Code
Jonathan-Problem statement and references 3 & 4
