# covid_19
Here you find data about covid-19 in two different folders. In the folder `probability` you find an easy example on how to calculate some dependent probabilities, 
while in the folder `tests-cases-death` there is some information about the connection between tests done, new covid cases and number of death. 

The later folder was motivated by a discussion with the journalist Carina Rehberg. On her website https://www.zentrum-der-gesundheit.de/ she was mentioning the Corman-Drosten review report
(https://cormandrostenreview.com/).
But instead of doing research on the validity of the criticism of the Corman-Drosten review report, which would have lead to the conclusion that this review is full of wrong claims,
Carina Rehberg created the illusion that the Corman-Drosten review report is an accepted scientific fact and that the PCR tests are useless for fighting corona. 
Although there are multiple published studies about PRT tests for covid-19 and the Corman-Drosten review report has not been yet reviewed and published, the Carina Rehberg 
accepts all statements from the Corman-Drosten review report and rejects all scientific knowledge around PRC tests. 

Instead of acknowledging that PRC tests are used for various deseases like Hepatitis-B/C, Dengue, Malaria, Meningitis and all types of meningococcal diseases (
http://grcpk.com/diagnostics/pcr-for-infectious-diseases/
https://gpnotebook.com/simplepage.cfm?ID=x20101006110914162451#:~:text=Polymerase%20chain%20reaction%20%28PCR%29%20tests%20for%20bacterial%20meningitis,to%20avoid%20repeating%20the%20test%20Weitere%20Artikel...%20)
, she claimed that PCR tests can not detect a covid-19 infection. By this she means that with a positive PCR test we have no information whether this person will show sysmptoms
or can infect other persons. While this is not wrong, the tests are a very good proxy for the situation regarding covid-19 in a region or country. 

In my opinion the text of Carina Rehberg was aimed to cast doubt on the current scientifc view about covid-19. She also rejects the covid-19 measures like lockdowns,
using masks and getting vaccinated. Because there is no scientifc backup against masks, lockdowns (while it has shown positive effects, there is still discussion on the strictness of
applied lockdowns) and vaccinations (also here there is an ongoing discussion about possible long-term effects, while mainstream science is of the opinion that the positive effects
of the vaccination is by far bigger than possible risks), she is citing a letter from a reader of the Ärzteblatt Dr. med. Hans Jürgen Scheurle, who claims that:
- `Wir Ärzte sind verpflichtet, uns gegen unsinnige, schädliche Regierungsmassnahmen zu wenden und dem auf PCR-Tests gegründeten Shutdown, der kulturellen Isolation und dem wirtschaftlichen Niedergang zu begegnen.`

When I was writing her and sharing my concern that her text is bring accross a dangerous message to the reader, she was saying that her article aims 'to make the reader think'.
She was also sharing examples where people were tested positive first and then in a later run were tested negative. Instead of realizing that this is because these persons have had
a bigger amount of virus in the first test and a lower (not detectable) amount of virus in the second test, she claims that this shows that the test is unreliable (false positive in the first test). 

Carina Rehberge also claims that there is no connection between positive tests and death related to corona:
- `die Korrelation zwischen positiven Tests und Todesfällen ist nicht korrekt. Schauen Sie sich die Zahlen z. B. von Spanien an.`

As a data scientist I had to look at this data! Ofcourse there is a clear correlation between positive corona tests and people dying because of/with corona. So this claim, as many other
claims she made is wrong. 

Please have a look at the different plots I created. I also used the number of positive tests to predict the number of corona deaths using a simple linear regression model.
Therefore I used the number of positive corona tests in week=0 to predict the number of corona related deaths in week=2. While I am on a lower level than the observed one,
the trend can be very well predicted. Also the problem in this very simple model is that there are people dying after more than 2 weeks after their tests, so we have 
different lagged effects. Also I have no information about the age and general health situation of the different infected people.
But I showed that the number of positive tests can be a good proxy for the number of death and I think that the RKI and others have very advanced models that can predict the
hospital occupancy and the expected number of death very well!



 

