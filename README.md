In this repository, we published our pretrained XGBOOST model for age prediction from COVID-19 blood test (See [2]).



#### Publications:
Please cite one of our paper:

(1) Qomariyah, Nunung Nurul, et al. "A Tree-based Mortality Prediction Model of COVID-19 from Routine Blood Samples." 2021 International Conference on ICT for Smart Society (ICISS). IEEE, 2021.

(2) Qomariyah, Nunung Nurul, et al. "An XGBoost Model for Age Prediction from COVID-19 Blood Test." 2021 4th International Seminar on Research of Information Technology and Intelligent Systems (ISRITI). IEEE, 2021.

#### Blood Test Features 
The feature used in the dataset is as below:

| Biomarker                                        | Feature code | Normal level (adult) | Unit |
|-----------------------------------------------------------|-----------------------|-------------------------------|---------------|
| HEMATOLOGY                                                |                       |                               |               |
| 	Hemoglobin                                  | HB                    | 13.2 - 17.3                   | g/dL          |
| 	Hematocrit                                  | HCT                   | 40 - 52                       | %            |
| 	Leukocytes                                  | LEKO                  | 3.8 - 10.6                    | 10^3/uL     |
| 	Platelets                                   | PLT                   | 150 - 440                     | 10^3/uL     |
| 	Erythrocytes                                | ERI                   | 4.40 - 5.90                   | 10^6/uL     |
| 	Red Cell Distribution Width                 | RDW                   | 11.8 - 14.5                   | %            |
| AVERAGE ERYTHROCYTE VALUE                                 |                       |                               |               |
| 	Mean Corpuscular Volume                     | MCV                   | 80 - 100                      | fl            |
| 	Mean Corpuscular Hemoglobin                 | MCH                   | 27.5 - 33.2                   | pg            |
| 	Mean Corpuscular  Hemoglobin  Concentration | MCHC                  | 32 - 36                       | g/dL          |
| COUNT TYPE                                                |                       |                               |               |
| 	Basophils                                   | BASOFIL               | 0.0 - 1.0                     | %            |
| 	Eosinophils                                 | EOS                   | 1.0 - 5.0                     | %            |
| 	Stem Neutrophils                            | NEUTB                 | 3.0 - 5.0                     | %            |
| 	Segmented Neutrophils                       | SEGMEN                | 50 - 70                       | %            |
| 	Lymphocytes                                 | LIMFOSIT              | 25 - 50                       | %            |
| 	Monocytes                                   | MONOSIT               | 2.0 - 8.0                     | %            |
| 	Neutrophil-Lymphocyte Ratio                 | NLR1                  | <3.12               |               |
| 	Erythrocyte Sedimentation Rate              | LED                   | 0 - 20                        | mm/hour       |
| HEMOSTASIS                                                |                       |                               |               |
| 	D-Dimer                                     | DDIMER                | <0.5                | ug/mL         |
| 	prothrombin time                            | PTHSL                 | 10.80 - 14.40                 | second        |
| 	Activated Partial   Thromboplastin Time     | APTTHSL               | 25.00 - 35.00                 | second        |
| BLOOD   CHEMISTRY                                         |                       |                               |               |
| 	Arterial blood gas analysis                 |                       |                               |               |
| 		Partial pressure of oxygen                  | PO2\_N                | 71.0 - 104.0                  | mmHg          |
| 		Oxygen saturation                           | O2S\_N                | 94.0 - 100.0                  | %            |
| 	Liver function                              |                       |                               |               |
| 		Serum Glutamic Oxaloacetic   Transaminase   | SGOT                  | <50                 | U/L           |
| 		Serum Glutamic Pyruvic   Transaminase       | SGPT                  | <50                 | U/L           |
| 	Diabetes                                    |                       |                               |               |
| 		Random Plasma Glucose Test                  | GDSFULL               | 70 - 180                      | mg/dL         |
| 	Kidney Function                             |                       |                               |               |
| 		Urea                                        | UREUM                 | <48                 | mg/dl         |
| 		Creatinine                                  | CREAT                 | 0.70 - 1.30                   | mg/dL         |
| 	Cardiac enzymes                             |                       |                               |               |
| 		Lactate dehydrogenase                       | LDH                   | 50 - 150                      | U/L           |
