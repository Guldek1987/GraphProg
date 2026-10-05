# Data sources

The repository includes the compressed RoboMission source CSVs and the three small source tables used to describe the school data. Derived features and expanded event tables are created by notebooks 01–02.

| Source | Included input | Use |
| :--- | :--- | :--- |
| RoboMission, 2019-12-10 | `raw/robomission/robomission-2019-12-10.zip` | Edit/execution events, attempts, task descriptions |
| School study, January–June 2021 | `raw/zenodo_7489244/student_test_janjune_2021.csv` | Paired pre/post cCTt regression |
| School study, November 2021 | `raw/zenodo_7489244/student_surveytest_nov_2021.csv` | Source-population description |
| School study, May 2022 | `raw/zenodo_7489244/student_survey_may_2022.csv` | Source-population description |

School data: Laila El-Hamamsy, Barbara Bruno, Jessica Dehler Zufferey, and Francesco Mondada, *Dataset for the evaluation of student-level outcomes of a primary school Computer Science curricular reform*, [Zenodo 7489244](https://doi.org/10.5281/zenodo.7489244), CC BY 4.0. The upstream README, record metadata, and unmodified source CSVs are retained. The notebooks select an analytical subset; no individual cross-source linkage is assumed.

RoboMission: [official data description](https://github.com/adaptive-learning/adaptive-learning-research/tree/master/data/robomission-2019-02-09) and [public archive](https://drive.google.com/file/d/1iKgMZFcKy5J1Ry9K7sUVeLAHK1fq-xJV/view). The research-repository folder is named February 2019, while this experiment uses the December 2019 archive. The source descriptions are retained in `raw/robomission/`. No new dataset license is assigned by this repository.

Notebook 01 extracts `events.csv`, `attempts.csv`, and `problems.csv` automatically. The archive is repacked to contain only these three byte-identical source CSVs; an upstream editor swap file is omitted. Expanded CSVs and derived arrays are ignored by Git. `protocol/` holds the frozen evaluation configuration and source fingerprints needed to reproduce the recorded evaluation; generated feature contracts and split assignments are written there during execution.
