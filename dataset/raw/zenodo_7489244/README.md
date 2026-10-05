Dataset for the evaluation of student-level outcomes of a primary school Computer Science curricular reform
=======================================================

• If you publish material based on this dataset, please cite the following :

​			• The Zenodo repository : Laila El-Hamamsy, Barbara Bruno, Jessica Dehler Zufferey, and Francesco Mondada (2023). Dataset for the evaluation of student-level outcomes of a primary school Computer Science curricular reform [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7489244

​			• The associated peer reviewed article that will appear in the International Journal of STEM education : El-Hamamsy, L., Bruno, B., Audrin, C., Chevalier, M., Avry S., Dehler Zufferey, J., and Mondada, F. (2023). How are Primary School Computer Science Curricular Reforms Contributing to Equity? Impact on Student Learning, Perception of the Discipline, and Gender Gaps. arXiv, to appear in the International Journal of STEM Education. https://doi.org/10.48550/arXiv.2306.00820

• License: This work is licensed under a Creative Commons Attribution 4.0 International license (CC-BY-4.0)

• Creator: El-Hamamsy, L., Bruno, B., Dehler Zufferey, J., and Mondada, F.

• Date: May 2nd 2023

• Subject: Computer Science; Curricular Reform; Elementary Education; Learning Achievement; Computational Thinking; Perception Survey; Equity; Gender Gaps

• Dataset format: CSV

• Dataset collection: January 2021 to May 2022

• Dataset size : < 100 kB

• Dataset content : three excel files. We provide the detailed description of each of the files below. The original questions are available in the associated publication [1]. Please note that these datasets contain missing values due to students either not being present for all data collections or not having the associated teacher-related data.

• Abbreviations :
  - CS : Computer Science
  - CT : Computational Thinking
  - PD : Professional Development

• Funding : This work was funded by the the NCCR Robotics, a National Centre of Competence in Research, funded by the Swiss National Science Foundation (grant number 51NF40_185543)

# 1. Student learning study in schools with access to CS education (study 1, spring 2021)

Filename : student_test_janjune_2021.csv

Each row of the table contains:
- a single students' score on the competent Computational Thinking test [2, 3, 4] in January 2021 (pre-test) and June 2021 (post-test). Please note that these students had access to CS education.
- their corresponding teachers' perception data acquired in January 2021 (prior to the pre-test)
- their corresponding teachers' adoption data acquired in June 2021 (after the post-test)

We describe each of the columns in the table below. Please note that :
- The corresponding teacher-training program and activities referred to in the Table are described in [5,6]
- We did not include teacher demographic data for anonymisation purposes

|                                                                                                                          | Values                       |   count | mean                 | std                 | min                 | 25%   | 50%   | 75%                 | max   |
|:-------------------------------------------------------------------------------------------------------------------------|:-----------------------------|--------:|:---------------------|:--------------------|:--------------------|:------|:------|:--------------------|:------|
| Students' gender                                                                                                         | Girl, Boy                    |    1463 |                      |                     |                     |       |       |                     |       |
| Pre-test cCTt score                                                                                                      | Numeric discrete [0, 24]     |    1463 | 13.442241968557758   | 5.011673748989311   | 1.0                 | 10.0  | 14.0  | 17.0                | 24.0  |
| Post-test cCTt score                                                                                                     | Numeric discrete [0, 24]     |    1463 | 15.602187286397813   | 4.767399050605883   | 2.0                 | 12.0  | 16.0  | 19.0                | 24.0  |
| Normalised change between the pre and post tests                                                                         | Numeric continuous [-1, 1]   |    1461 | 0.2122201551150944   | 0.31623871223288297 | -0.8571428571428571 | 0.0   | 0.2   | 0.42857142857142855 | 1.0   |
| Number of periods the teacher spent teaching the sorting machine                                                         | Numeric dicrete (>0)         |    1080 | 0.6314814814814815   | 1.2841551062882335  | 0.0                 | 0.0   | 0.0   | 0.0                 | 4.0   |
| Number of periods the teacher spent teaching the robot game                                                              | Numeric dicrete (>0)         |    1080 | 0.7972222222222223   | 1.8262303777583793  | 0.0                 | 0.0   | 0.0   | 1.0                 | 10.0  |
| Number of periods the teacher spent teaching the crane game                                                              | Numeric dicrete (>0)         |    1080 | 0.33796296296296297  | 0.9965852348044912  | 0.0                 | 0.0   | 0.0   | 0.0                 | 6.0   |
| Number of periods the teacher spent teaching the pixel game                                                              | Numeric dicrete (>0)         |    1080 | 0.3638888888888889   | 0.9223773865668665  | 0.0                 | 0.0   | 0.0   | 0.0                 | 4.0   |
| Number of periods the teacher spent teaching the treasure hunting game                                                   | Numeric dicrete (>0)         |    1080 | 0.1388888888888889   | 0.59435611430235    | 0.0                 | 0.0   | 0.0   | 0.0                 | 4.0   |
| Number of periods the teacher spent teaching the Bluebot                                                                 | Numeric dicrete (>0)         |    1080 | 2.7018518518518517   | 3.4342758343351947  | 0.0                 | 0.0   | 1.0   | 5.0                 | 12.0  |
| Number of periods the teacher spent teaching Thymio with pre-programmed behaviors                                        | Numeric dicrete (>0)         |    1080 | 2.7814814814814817   | 3.422169128986194   | 0.0                 | 0.0   | 2.0   | 6.0                 | 15.0  |
| Number of periods the teacher spent teaching Thymio with VPL                                                             | Numeric dicrete (>0)         |    1080 | 0.08148148148148149  | 0.5173806109609822  | 0.0                 | 0.0   | 0.0   | 0.0                 | 4.0   |
| Number of periods the teacher spent teaching the robot olympics                                                          | Numeric dicrete (>0)         |    1080 | 0.09074074074074075  | 0.5404040360295287  | 0.0                 | 0.0   | 0.0   | 0.0                 | 4.0   |
| Number of periods the teacher spent teaching algorithms                                                                  | Numeric dicrete (>0)         |    1080 | 0.6037037037037037   | 1.715217067240389   | 0.0                 | 0.0   | 0.0   | 0.0                 | 8.0   |
| Number of periods the teacher spent teaching salmon sorting                                                              | Numeric dicrete (>0)         |    1080 | 0.0                  | 0.0                 | 0.0                 | 0.0   | 0.0   | 0.0                 | 0.0   |
| Number of periods the teacher spent teaching networks                                                                    | Numeric dicrete (>0)         |    1080 | 0.15648148148148147  | 0.9454807534151255  | 0.0                 | 0.0   | 0.0   | 0.0                 | 7.0   |
| Number of periods the teacher spent teaching Scratch Jr                                                                  | Numeric dicrete (>0)         |    1080 | 1.5055555555555555   | 2.8574353308090714  | 0.0                 | 0.0   | 0.0   | 2.0                 | 10.0  |
| Number of periods the teacher spent teaching Cryptography                                                                | Numeric dicrete (>0)         |    1080 | 0.03333333333333333  | 0.256156810175806   | 0.0                 | 0.0   | 0.0   | 0.0                 | 2.0   |
| Number of periods the teacher spent teaching CS activities                                                               | Numeric dicrete (>0)         |    1080 | 2.596296296296296    | 2.0462640713864992  | 0.0                 | 1.0   | 2.0   | 4.0                 | 9.0   |
| The teachers' CS PD evaluation in terms of richness and interest                                                         | 7 Point Likert scale [-3, 3] |    1086 | 1.5989871086556169   | 1.1298663865460215  | -2.0                | 1.0   | 2.0   | 2.0                 | 3.0   |
| The teachers' CS PD evaluation with respect to the difficulty of the workshops                                           | 7 Point Likert scale [-3, 3] |    1086 | 1.232965009208103    | 1.2620150125343492  | -2.0                | 1.0   | 1.0   | 2.0                 | 3.0   |
| The teachers' CS PD evaluation with respect to equilibrium between theory and practice in the workshops                  | 7 Point Likert scale [-3, 3] |    1086 | 1.5400552486187846   | 1.155634402620835   | -1.0                | 1.0   | 2.0   | 2.75                | 3.0   |
| The teachers' CS PD evaluation with respect to the workshops                                                             | 7 Point Likert scale [-3, 3] |    1086 | 2.0285451197053406   | 1.0534626255792323  | -2.0                | 2.0   | 2.0   | 3.0                 | 3.0   |
| The teachers' CS PD evaluation with respect to the trainers                                                              | 7 Point Likert scale [-3, 3] |    1086 | 2.2642725598526705   | 0.7841481187801426  | 0.0                 | 2.0   | 2.0   | 3.0                 | 3.0   |
| The teachers' CS PD evaluation with respect to the exchanges with other participants                                     | 7 Point Likert scale [-3, 3] |    1086 | 1.736648250460405    | 1.0622042118533348  | -1.0                | 1.0   | 2.0   | 3.0                 | 3.0   |
| The teachers' perception of the utility of CS - is part of the school's missions                                         | 7 Point Likert scale [-3, 3] |    1176 | 0.7206632653061225   | 1.4290267131648644  | -3.0                | 0.0   | 1.0   | 2.0                 | 3.0   |
| The teachers' perception of the utility of CS - useful for learning in other disciplines                                 | 7 Point Likert scale [-3, 3] |    1176 | 1.0131802721088434   | 1.1918323835393265  | -2.5                | 0.0   | 1.0   | 2.0                 | 3.0   |
| The teachers' perception of the utility of CS - globally useful                                                          | 7 Point Likert scale [-3, 3] |    1176 | 0.9791666666666666   | 1.1316489882574514  | -2.5                | 1.0   | 1.0   | 2.0                 | 3.0   |
| The teachers' perception of the utility of CS - globally not worth it                                                    | 7 Point Likert scale [-3, 3] |    1176 | -1.3358843537414966  | 1.1985188306679309  | -3.0                | -2.0  | -1.0  | -1.0                | 2.0   |
| The teachers' perception of the utility of CS - useful for professional integration                                      | 7 Point Likert scale [-3, 3] |    1176 | 0.45875850340136054  | 1.1760915391406694  | -2.0                | 0.0   | 0.0   | 1.0                 | 3.0   |
| The teachers' perception of the utility of CS - useful to express creativity                                             | 7 Point Likert scale [-3, 3] |    1176 | -0.04039115646258504 | 1.3907999902300303  | -3.0                | -1.0  | 0.0   | 1.0                 | 3.0   |
| The teachers' perception of the utility of CS - not useful                                                               | 7 Point Likert scale [-3, 3] |    1176 | -0.9566326530612245  | 1.187447921476128   | -3.0                | -2.0  | -1.0  | 0.0                 | 2.0   |
| The teachers' perception of the utility of CS - useful to be active creators rather than passive consumers of technology | 7 Point Likert scale [-3, 3] |    1176 | 0.7253401360544217   | 1.2085809734210553  | -2.0                | 0.0   | 1.0   | 2.0                 | 3.0   |
| Autonomous motivation - The teachers' intrinsic motivation to teach CS (1)                                               | 7 Point Likert scale [-3, 3] |    1176 | 0.6420068027210885   | 1.2949278675205593  | -3.0                | 0.0   | 1.0   | 1.0                 | 3.0   |
| Autonomous motivation - The teachers' identified regulation to teach CS (1)                                              | 7 Point Likert scale [-3, 3] |    1176 | 0.8945578231292517   | 1.2366478953522593  | -2.0                | 0.0   | 1.0   | 2.0                 | 3.0   |
| Autonomous motivation - The teachers' external regulation to teach CS (1)                                                | 7 Point Likert scale [-3, 3] |    1176 | 0.70578231292517     | 1.6491650189735563  | -3.0                | 0.0   | 1.0   | 2.0                 | 3.0   |
| Autonomous motivation - The teachers' intrinsic motivation to teach CS (2)                                               | 7 Point Likert scale [-3, 3] |    1176 | 0.8907312925170068   | 1.1637097580266     | -3.0                | 0.0   | 1.0   | 2.0                 | 3.0   |
| Autonomous motivation - The teachers' identified regulation to teach CS (2)                                              | 7 Point Likert scale [-3, 3] |    1176 | 0.9400510204081632   | 1.201603041663564   | -2.5                | 0.0   | 1.0   | 2.0                 | 3.0   |
| Autonomous motivation - The teachers' external regulation to teach CS (2)                                                | 7 Point Likert scale [-3, 3] |    1176 | 0.6420068027210885   | 1.3769484806090442  | -3.0                | 0.0   | 1.0   | 2.0                 | 3.0   |
| Autonomous motivation - The teachers' introjected regulation to teach CS (1)                                             | 7 Point Likert scale [-3, 3] |    1176 | -1.3856292517006803  | 1.6260818681736737  | -3.0                | -3.0  | -2.0  | 0.0                 | 2.0   |
| Autonomous motivation - The teachers' introjected regulation to teach CS (2)                                             | 7 Point Likert scale [-3, 3] |    1176 | -1.6692176870748299  | 1.5208692028397695  | -3.0                | -3.0  | -2.0  | 0.0                 | 3.0   |

# 2. Student perception and performance study in schools with access to CS education (study 2, fall 2021)

Filename : student_surveytest_nov_2021.csv

All the data was collected around November 2021. Each row of the table contains :
- a single students' score on the competent Computational Thinking test [2, 3, 4]. Please note that the grade 3 students did the cCTt-17, while the grade 4 students did the cCTt-23 and the grades 5-6 students did the cCTt-25 [2]
- a single students' responses to the perception survey
- their corresponding teachers' adoption data

We describe each of the columns in the table below. Please note that :
- The corresponding teacher-training program and activities referred to in the Table are described in [5,6,7]
- We did not include teacher demographic data for anonymisation purposes

|                                                                                   | Values                                     |   count | mean                 | std                 | min   | 25%               | 50%   | 75%               | max   |
|:----------------------------------------------------------------------------------|:-------------------------------------------|--------:|:---------------------|:--------------------|:------|:------------------|:------|:------------------|:------|
| Gender                                                                            | Girl, Boy                                  |    1831 |                      |                     |       |                   |       |                   |       |
| Grade                                                                             | 3, 4, 5 or 6                               |    2456 | 4.5952768729641695   | 1.1119981120085338  | 3.0   | 4.0               | 5.0   | 6.0               | 6.0   |
| cCTt - total score                                                                | Numeric discrete [0, 25]                   |    2226 | 13.892183288409704   | 5.939550317379456   | 0.0   | 9.0               | 14.0  | 19.0              | 25.0  |
| cCTt - Number of cCTt questions the students answered                             | Ordinal (17, 23 or 25)                     |    2226 | 22.78436657681941    | 3.15306135932579    | 17.0  | 23.0              | 25.0  | 25.0              | 25.0  |
| cCTt - Proportion of correct responses                                            | Numeric continuous [0, 100]                |    2226 | 59.6495451338862     | 22.199677894504248  | 0.0   | 43.47826086956522 | 60.0  | 78.26086956521739 | 100.0 |
| Tablet-related interest                                                           | 5 Point Likert between -2 and +2           |    1825 | 1.7156164383561643   | 0.6990771373946354  | -2.0  | 2.0               | 2.0   | 2.0               | 2.0   |
| Robot-related utility                                                             | 5 Point Likert between -2 and +2           |    1828 | 1.460612691466083    | 0.9013048115482104  | -2.0  | 1.0               | 2.0   | 2.0               | 2.0   |
| Tablet-related utility                                                            | 5 Point Likert between -2 and +2           |    1825 | 1.6684931506849314   | 0.6787979394738778  | -2.0  | 2.0               | 2.0   | 2.0               | 2.0   |
| Tablet-related self-efficacy                                                      | 5 Point Likert between -2 and +2           |    1825 | 1.766027397260274    | 0.5854100089979188  | -2.0  | 2.0               | 2.0   | 2.0               | 2.0   |
| Robot-related interest                                                            | 5 Point Likert between -2 and +2           |    1828 | 1.473741794310722    | 1.006747788172984   | -2.0  | 1.0               | 2.0   | 2.0               | 2.0   |
| CS-related interest                                                               | 5 Point Likert between -2 and +2           |    1831 | 1.5182960131075915   | 0.7792167440361389  | -2.0  | 1.0               | 2.0   | 2.0               | 2.0   |
| CS-related utility                                                                | 5 Point Likert between -2 and +2           |    1831 | 1.5876570180229383   | 0.7256732500965145  | -2.0  | 1.0               | 2.0   | 2.0               | 2.0   |
| Robot-related self-efficacy                                                       | 5 Point Likert between -2 and +2           |    1828 | 1.3719912472647702   | 0.9586542839043396  | -2.0  | 1.0               | 2.0   | 2.0               | 2.0   |
| CS-related self-efficacy                                                          | 5 Point Likert between -2 and +2           |    1831 | 1.3828509011469143   | 0.8988825844948849  | -2.0  | 1.0               | 2.0   | 2.0               | 2.0   |
| School-related self-efficacy                                                      | 5 Point Likert between -2 and +2           |    1812 | 1.544701986754967    | 0.7524592990502134  | -2.0  | 1.0               | 2.0   | 2.0               | 2.0   |
| Teacher as a CS role model                                                        | 0: Not a CS role model, 1: a CS role model |    1831 | 0.4014199890770071   | 0.4903195723970524  | 0.0   | 0.0               | 0.0   | 1.0               | 1.0   |
| Mother as a CS role model                                                         | 0: Not a CS role model, 1: a CS role model |    1831 | 0.3113052976515565   | 0.4631538239785014  | 0.0   | 0.0               | 0.0   | 1.0               | 1.0   |
| Father as a CS role model                                                         | 0: Not a CS role model, 1: a CS role model |    1831 | 0.4625887493173129   | 0.49873464440978554 | 0.0   | 0.0               | 0.0   | 1.0               | 1.0   |
| A student as a CS role model                                                      | 0: Not a CS role model, 1: a CS role model |    1831 | 0.2097214636810486   | 0.40722099499972597 | 0.0   | 0.0               | 0.0   | 0.0               | 1.0   |
| Other person as a CS role model                                                   | 0: Not a CS role model, 1: a CS role model |    1831 | 0.3708356089568542   | 0.4831604862511821  | 0.0   | 0.0               | 0.0   | 1.0               | 1.0   |
| Nobody as a CS role model                                                         | 0: Not a CS role model, 1: a CS role model |    1831 | 0.1780447842708902   | 0.3826549475993154  | 0.0   | 0.0               | 0.0   | 0.0               | 1.0   |
| Number of periods the teacher spent teaching the robot game                       | Numeric dicrete (>0)                       |    1831 | 0.3140360458765702   | 1.1030086211685366  | 0.0   | 0.0               | 0.0   | 0.0               | 8.0   |
| Number of periods the teacher spent teaching the sorting machine                  | Numeric dicrete (>0)                       |    1831 | 0.2889131622064446   | 0.8212229109713496  | 0.0   | 0.0               | 0.0   | 0.0               | 4.0   |
| Number of periods the teacher spent teaching the treasure hunting game            | Numeric dicrete (>0)                       |    1831 | 0.15019115237575095  | 1.020472791180227   | 0.0   | 0.0               | 0.0   | 0.0               | 10.0  |
| Number of periods the teacher spent teaching the pixel game                       | Numeric dicrete (>0)                       |    1831 | 0.11141452758055707  | 0.6029397184041464  | 0.0   | 0.0               | 0.0   | 0.0               | 4.0   |
| Number of periods the teacher spent teaching salmon sorting                       | Numeric dicrete (>0)                       |    1831 | 0.005461496450027308 | 0.0737199880047509  | 0.0   | 0.0               | 0.0   | 0.0               | 1.0   |
| Number of periods the teacher spent teaching the crane game                       | Numeric dicrete (>0)                       |    1831 | 0.10704533042053523  | 0.5396918343704179  | 0.0   | 0.0               | 0.0   | 0.0               | 4.0   |
| Number of periods the teacher spent teaching the Bluebot                          | Numeric dicrete (>0)                       |    1831 | 0.3719279082468596   | 1.3825052682206542  | 0.0   | 0.0               | 0.0   | 0.0               | 10.0  |
| Number of periods the teacher spent teaching CS activities                        | Numeric dicrete (>0)                       |    1831 | 4.070999453850355    | 7.099633257325641   | 0.0   | 0.0               | 2.0   | 6.0               | 56.0  |
| Number of periods the teacher spent teaching Cryptography                         | Numeric dicrete (>0)                       |    1831 | 0.10922992900054615  | 1.039691530072674   | 0.0   | 0.0               | 0.0   | 0.0               | 10.0  |
| Number of periods the teacher spent teaching Caesar's code                        | Numeric dicrete (>0)                       |    1831 | 0.2293828509011469   | 0.906461083236117   | 0.0   | 0.0               | 0.0   | 0.0               | 6.0   |
| Number of periods the teacher spent teaching networks                             | Numeric dicrete (>0)                       |    1831 | 0.07209175314036045  | 0.6539012344105539  | 0.0   | 0.0               | 0.0   | 0.0               | 6.0   |
| Number of periods the teacher spent teaching Square CT                            | Numeric dicrete (>0)                       |    1831 | 0.5155652648825778   | 1.4823748465774402  | 0.0   | 0.0               | 0.0   | 0.0               | 8.0   |
| Number of periods the teacher spent teaching Thymio with VPL                      | Numeric dicrete (>0)                       |    1831 | 0.14090660841070454  | 0.9477168696629478  | 0.0   | 0.0               | 0.0   | 0.0               | 10.0  |
| Number of periods the teacher spent teaching Bebras challenges                    | Numeric dicrete (>0)                       |    1831 | 0.0                  | 0.0                 | 0.0   | 0.0               | 0.0   | 0.0               | 0.0   |
| Number of periods the teacher spent teaching about binary code                    | Numeric dicrete (>0)                       |    1831 | 0.09175314036045877  | 0.5613145541000201  | 0.0   | 0.0               | 0.0   | 0.0               | 4.0   |
| Number of periods the teacher spent teaching about sorting                        | Numeric dicrete (>0)                       |    1831 | 0.06444565811032223  | 0.3532792610004097  | 0.0   | 0.0               | 0.0   | 0.0               | 2.0   |
| Number of periods the teacher spent teaching Scratch Jr                           | Numeric dicrete (>0)                       |    1831 | 0.8973238667394866   | 3.274065743933598   | 0.0   | 0.0               | 0.0   | 0.0               | 30.0  |
| Number of periods the teacher spent teaching Thymio with pre-programmed behaviors | Numeric dicrete (>0)                       |    1831 | 0.4571272528672856   | 1.3905191249325999  | 0.0   | 0.0               | 0.0   | 0.0               | 10.0  |
| Number of periods the teacher spent teaching algorithms                           | Numeric dicrete (>0)                       |    1831 | 0.1441835062807209   | 0.5959496963871896  | 0.0   | 0.0               | 0.0   | 0.0               | 4.0   |
| Number of CS activities the teacher taught                                        | Numeric dicrete (>0)                       |    1831 | 1.6897870016384489   | 1.8990649146975787  | 0.0   | 0.0               | 2.0   | 3.0               | 8.0   |

# 3. Student perception study to compare between schools with and without access to CS education (study 3, spring 2022)

Filename : student_survey_may_2022.csv

Each row of the table corresponds to the a students' response to a CS perception survey in May 2022. We describe each of the columns in the table below.

|                      | Description                                                           | Values                                     |   count | mean                | std                 | min   | 25%   | 50%   | 75%   | max   |
|:---------------------|:----------------------------------------------------------------------|:-------------------------------------------|--------:|:--------------------|:--------------------|:------|:------|:------|:------|:------|
| CS Schools           | Whether the school has access to CS education or not                  | 0: No access, 1: Access                    |    1644 | 0.5054744525547445  |                     |       |       |       |       |       |
| City                 | Whether the school is in a city or a suburban area or the countryside | 0: Not in a city , 1: In a city            |    1644 | 0.44768856447688565 |                     |       |       |       |       |       |
| Grade                | The students' grade                                                   | 3, 4, 5 or 6                               |    1644 | 4.619829683698297   | 1.1217415249873612  | 3.0   | 4.0   | 5.0   | 6.0   | 6.0   |
| Math_selfefficacy    | Confidence in their capacity to do / learn about Math                 | 5 Point Likert between -2 and +2           |    1640 | 1.5445121951219511  | 0.8180210236994002  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| Tablets_utility      | Whether Tablets are perceived as useful                               | 5 Point Likert between -2 and +2           |    1644 | 1.610705596107056   | 0.7170863059929075  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| CS_utility           | Whether CS is perceived as useful                                     | 5 Point Likert between -2 and +2           |    1644 | 1.5772506082725062  | 0.7528356508520215  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| Tablets_selfefficacy | Confidence in their capacity to do / learn about Tablets              | 5 Point Likert between -2 and +2           |    1644 | 1.758515815085158   | 0.5906199114888641  | -2.0  | 2.0   | 2.0   | 2.0   | 2.0   |
| Robots_interest      | Confidence in their capacity to do / learn about Robots               | 5 Point Likert between -2 and +2           |    1644 | 1.3004866180048662  | 1.0325086040665485  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| Tablets_interest     | Confidence in their capacity to do / learn about Tablets              | 5 Point Likert between -2 and +2           |    1644 | 1.7141119221411192  | 0.6817473358577005  | -2.0  | 2.0   | 2.0   | 2.0   | 2.0   |
| CS_selfefficacy      | Confidence in their capacity to do / learn about CS                   | 5 Point Likert between -2 and +2           |    1644 | 1.4981751824817517  | 0.828947710341545   | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| General_selfefficacy | Confidence in their capacity to do well in school                     | 5 Point Likert between -2 and +2           |    1640 | 1.477439024390244   | 0.7729270704240399  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| Robots_utility       | Whether Robots are perceived as useful                                | 5 Point Likert between -2 and +2           |    1644 | 1.413625304136253   | 0.9246521588376798  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| Robots_selfefficacy  | Confidence in their capacity to do / learn about Robots               | 5 Point Likert between -2 and +2           |    1644 | 1.2694647201946472  | 1.0134899986936636  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| CS_interest          | Confidence in their capacity to do / learn about CS                   | 5 Point Likert between -2 and +2           |    1644 | 1.590632603406326   | 0.7257945221832399  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| Sport_selfefficacy   | Confidence in their capacity to do / learn about Sport                | 5 Point Likert between -2 and +2           |    1640 | 1.7652439024390243  | 0.6073672681643922  | -2.0  | 2.0   | 2.0   | 2.0   | 2.0   |
| French_selfefficacy  | Confidence in their capacity to do / learn about French               | 5 Point Likert between -2 and +2           |    1640 | 1.2493902439024391  | 0.9337412496619488  | -2.0  | 1.0   | 1.0   | 2.0   | 2.0   |
| Who_Teacher          | Whether their teacher is perceived as doing CS                        | 0: Not a CS role model, 1: a CS role model |    1644 | 0.46958637469586373 | 0.4992260100294787  | 0.0   | 0.0   | 0.0   | 1.0   | 1.0   |
| Who_Mom              | Whether their mom is perceived as doing CS                            | 0: Not a CS role model, 1: a CS role model |    1644 | 0.4957420924574209  | 0.500134001913969   | 0.0   | 0.0   | 0.0   | 1.0   | 1.0   |
| Who_Dad              | Whether their dad is perceived as doing CS                            | 0: Not a CS role model, 1: a CS role model |    1644 | 0.5991484184914841  | 0.49022012258315767 | 0.0   | 0.0   | 1.0   | 1.0   | 1.0   |
| Who_Student          | Whether another student is perceived as doing CS                      | 0: Not a CS role model, 1: a CS role model |    1644 | 0.3418491484184915  | 0.47447365115609147 | 0.0   | 0.0   | 0.0   | 1.0   | 1.0   |
| Who_Other            | Whether somebody else is perceived as doing CS                        | 0: Not a CS role model, 1: a CS role model |    1644 | 0.402676399026764   | 0.4905858868561135  | 0.0   | 0.0   | 0.0   | 1.0   | 1.0   |
| Who_Nobody           | Whether nobody is perceived as doing CS                               | 0: Not a CS role model, 1: a CS role model |    1644 | 0.11070559610705596 | 0.3138626895526017  | 0.0   | 0.0   | 0.0   | 0.0   | 1.0   |
| General_selfefficacy | Confidence in their capacity to do well in school                     | 5 Point Likert between -2 and +2           |    1640 | 1.477439024390244   | 0.7729270704240399  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| French_selfefficacy  | Confidence in their capacity to do / learn about French               | 5 Point Likert between -2 and +2           |    1640 | 1.2493902439024391  | 0.9337412496619488  | -2.0  | 1.0   | 1.0   | 2.0   | 2.0   |
| Sport_selfefficacy   | Confidence in their capacity to do / learn about Sport                | 5 Point Likert between -2 and +2           |    1640 | 1.7652439024390243  | 0.6073672681643922  | -2.0  | 2.0   | 2.0   | 2.0   | 2.0   |
| Math_selfefficacy    | Confidence in their capacity to do / learn about Math                 | 5 Point Likert between -2 and +2           |    1640 | 1.5445121951219511  | 0.8180210236994002  | -2.0  | 1.0   | 2.0   | 2.0   | 2.0   |
| Gender               | The students' gender                                                  | Girl, Boy                                  |    1644 |                     |                     |       |       |       |       |       |


# References

[1] El-Hamamsy, L., Bruno, B., Audrin, C., Chevalier, M., Avry S., Dehler Zufferey, J., and Mondada, F. (2023). How are Primary School Computer Science Curricular Reforms Contributing to Equity? Impact on Student Learning, Perception of the Discipline, and Gender Gaps. arXiv, to appear in the International Journal of STEM Education. https://doi.org/10.48550/arXiv.2306.00820

[2]	El-Hamamsy, L., Zapata-Cáceres, M., Barroso, E. M., Mondada, F., Zufferey, J. D., & Bruno, B. (2022). The competent Computational Thinking Test: Development and Validation of an Unplugged Computational Thinking Test for Upper Primary School. Journal of Educational Computing Research, 07356331221081753. https://doi.org/10.1177/07356331221081753

[3]	El-Hamamsy, L., Zapata-Cáceres, M., Marcelino, P., Bruno, B., Dehler Zufferey, J., Martín-Barroso, E., & Román-González, M. (2022). Comparing the psychometric properties of two primary school Computational Thinking (CT) assessments for grades 3 and 4: The Beginners’ CT test (BCTt) and the competent CT test (cCTt). Frontiers in Psychology, 13. https://www.frontiersin.org/articles/10.3389/fpsyg.2022.1082659

[4] El-Hamamsy, L., Zapata-Cáceres, M., Martín-Barroso, E., Mondada, F., Dehler Zufferey, J., Bruno, B., and Román-González, M. (2023). The competent computational thinking test (cCTt): a valid, reliable and gender-fair test for longitudinal CT studies in grades 3-6.  El-Hamamsy, L., Zapata-Cáceres, M., Martín-Barroso, E., Mondada, F., Zufferey, J. D., Bruno, B., & Román-González, M. arXiv. https://doi.org/10.48550/arXiv.2305.19526

[5] El-Hamamsy, L.* , Chessel-Lazzarotto, F.* , Bruno, B., Roy, D., Cahlikova, T., Chevalier, M., Parriaux, G., Pellet, J.-P., Lanarès, J., Zufferey, J. D., & Mondada, F. (2021). A computer science and robotics integration model for primary school: Evaluation of a large-scale in-service K-4 teacher-training program. Education and Information Technologies, 26(3), 2445–2475. https://doi.org/10.1007/s10639-020-10355-5

[6] El-Hamamsy, L., Bruno, B., Chessel-Lazzarotto, F., Chevalier, M., Roy, D., Zufferey, J. D., & Mondada, F. (2021). The symbiotic relationship between educational robotics and computer science in formal education. Education and Information Technologies, 26(5), 5077–5107. https://doi.org/10.1007/s10639-021-10494-3

[7] El-Hamamsy, L., Bruno, B., Avry, S., Chessel-Lazzarotto, F., Zufferey, J. D., & Mondada, F. (2022). The TACS Model: Understanding Primary School Teachers’ Adoption of Computer Science Pedagogical Content. ACM Transactions on Computing Education. https://doi.org/10.1145/3569587
