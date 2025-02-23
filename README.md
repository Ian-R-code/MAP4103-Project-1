# MAP4103-Project-1
Instructions to run code:

Questions: How does caffeine affect productivity? 
How does caffeine effect mood? 
How accurately can we predict the level at which mood is effected/raised? 
How does Exercise and Age affect mood? 

How does caffeine effect mood? How accurately can we predict the level at which mood is effected/raised? 
Source: https://www.ncbi.nlm.nih.gov/books/NBK209050/
Write up: 
The military is understandably interested in how troops could operate on low sleep, yet still effectively and without decreased levels of mood/alertness/performance. To study this, Penetar et al. Researched Effects of Caffeine on Cognitive Performance, Mood…, which looked at those three in particular. When it came to mood specifically, they found that “doses of 200 to 250 mg of caffeine elevate mood (Lieberman et al., 1987b)… and that these effects can last for up to 3 h.” 

How does caffeine affect productivity? 
Source: Jacobson and Edgley, 1987; Lieberman et al., 1987a,b; Roache and Griffiths, 1987 
•	Jacobson, B.H., and B.M.Edgley 1987. Effects of caffeine on simple reaction time and movement time. Aviat. Space Environ. Med. 58:1153–1156.
•	Lieberman, H.R., R.J.Wurtman, G.G.Emde, and I.L.G.Coviella 1987. a The effects of caffeine and aspirin on mood and performance. J. Clin. Pharmacol. 7:315–320
•	Roache, J.D., and R.R.Griffiths 1987. Interactions of diazepam and caffeine: Behavioral and subjective dose in humans. Pharmacol. Biochem. Behav. 26:801–812.
Write up: 
When it comes to decreased levels of sleep in military forces, common issues arise such as lack of alertness, finger shaking, and reaction times slowing. Research done on this typically considers reaction times as related to productivity/performance (since these are important military considerations). According to the above sources, caffeine decreased reaction times in auditory/visual tasks between 32-600 mg (Jacobson and Edgly, Lieberman et al., Roache and Griffiths). The tasks used in particular to look at productivity ranged from basic math skills to card sorting. Noted, however is that motor skills are not typically helped by caffeine (to the same level as auditory/visual tasks). 

How does Exercise and Age affect mood? 
Source: https://www.ncbi.nlm.nih.gov/books/NBK68187/
Write up:
When looking at individuals 60 years and up, SM Arent attempted to answer the question–does age and exercise affect mood? (Specifically in older adults). Groups that were considered ranged ages and lengths of exercise, from 1 to 6 weeks and 7 to 12 weeks. Based upon their examination, it was shown that increased exercise vs. lack of resulted in better moods. Important to note is that between fitness groups (i.e. increase in fitness, where both are working out, but one group more than the other) there was less of a difference. Therefore it appears that exercise does result in positive mood increases. 



Discussion:
How often do you wake up not feeeling fully rested? If you're among the 35% (1) of Americans who are defined by the CDC as sleep deprived (getting less than 7 hours of efficient sleep). The true amount maay be even higher than 35%. One common coping mechanism that people fall back on is caffeine consumption, typically through coffee. Caffeine blocks adenosine receptors, and lessens/lowers REM/Deep sleep levels (2, Bagheri, et. al. ). Caffeine is only a temporay solution therefore, blocking the recognition of the problem, but not solving the root of the issue (lack of sleep). Not only does caffeine hide the true issue, it can negatively affect health. However, it does positively affect performance. While caffeine does rasie mood in the short term, it only lasts a short amount of time (3 h. or so). Ways to counteract the negative affects of ill mood (if you rely on caffeine too deeply) could be exercise (studied in older individuals, was found to have a positive benefit). 

Other References:
1) https://www.cdc.gov/sleep/data-research/facts-stats/adults-sleep-facts-and-stats.html
2) Bagheri Davisaraei, Y., Nateghi, S., Rashidipour, H., Raise-Abdullahi, P., & Rashidy-Pour, A. (2024). Coffee and sleep: Benefits and risks. Progress in Brain Research, 81–114. https://doi.org/10.1016/bs.pbr.2024.06.014
3) Burke, T. M., Markwald, R. R., McHill, A. W., Chinoy, E. D., Snider, J. A., Bessman, S. C., Jung, C. M., O’Neill, J. S., & Wright, K. P. (2015). Effects of caffeine on the human circadian clock in vivo and in vitro. Science Translational Medicine, 7(305). https://doi.org/10.1126/scitranslmed.aac5125 

Data Documentation:

Analysis:
Based on the three linear regression lines for Productivity score, Mood score, and Stress score, the biggest impacts on each are the time spent sleeping where bot hthe Productivity and Mood scores go up, which is good, and the stress score goes down, which is good. The start and end times for sleeping were opposite for Stress and Productivity which makes sense because oversleeping leads to being late for activities and work and less time to perform tasks. Moving to the K-Nearest Neighbors visualization, two criteria can be compared with the predicted result of either Productivity, Mood, or Stress score being shown. So both Mood and Producitvity are predicted to be lowerer when taking caffeine but Stress goes down. When comparing Age to Exercise time, more exercise is predicted to have a better mood compared to less exercise but it not a great difference. KNN was used because we had a large data set but a relatively small amount of criteria that needed looking at. Using K-Fold Cross-Validation the accuracy of our KNN model for Productivity, Mood, and Stress scores were around 50 percent for all three. Then a Neural Network was created for Productivity, Mood, and Stress, which is applicable becsue of the large data set to train it on, and it had an average accuracy of 52.3 percent. So both models are about as accurate as a coin flip which is not great. If we had more time we would have created a KNN model for more criteria at the same time and spent more time testing different k values to produce a more accurate model. Similarly with the Neural Network, spend more time improving its accuracy. We would have spend more resources in trying to find better connections between the different criteria for each score.

Credits:
Ian-References 1 & 2, Analysis
Drew-Code
Jonathan-Question statements and write ups, reference 3 & in question reference
