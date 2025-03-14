## pdf1_t0
|    | Component              | Company          |
|---:|:-----------------------|:-----------------|
|  0 | Ethanol (96%)          | Mojallaly (Iran) |
|  1 | Sulfuric acid (72%)    | Mojallaly        |
|  2 | Acetic acid (98%)      | Merck            |
|  3 | Nitric acid (65%)      | Mojallaly        |
|  4 | Sodium hydroxide (99%) | Merck            |
|  5 | Montmorillonite        | Merck            |
|  6 | Methylene blue         | Mojallaly        |
|  7 | Urea (99%)             | Merck            |

## pdf1_t1
|    | ('Factor', 'Complete name')         | ('Factor', 'Coded name')   | ('Levels', 'Range')   |   ('Levels', '−1') |   ('Levels', '0') |   ('Levels', '1') |
|---:|:------------------------------------|:---------------------------|:----------------------|-------------------:|------------------:|------------------:|
|  0 | Temperature (°C)                    | x1                         | 25–35                 |                 25 |                30 |                35 |
|  1 | pH                                  | x2                         | 4–8                   |                  4 |                 6 |                 8 |
|  2 | Initial dye concen￾tration (mg L−1) | x3                         | 4–8                   |                  4 |                 6 |                 8 |
|  3 | Mesh size                           | x4                         | 50–150                |                 50 |               100 |               150 |

## pdf1_t2
|    | Adsorbent   |   Specifc surface area (m2 g−1) |   Total pore vol￾ume (cm3 g−1) |   Average particle size (nm) |
|---:|:------------|--------------------------------:|-------------------------------:|-----------------------------:|
|  0 | HCMM        |                          25.147 |                          8.635 |                       84.172 |

## pdf1_t3
|    |   Run |   x1: T (°C) |   x2: pH |   x3: MB initial concen￾tration (mg L−1) |   x4: Mesh size |   MB removal (%) |
|---:|------:|-------------:|---------:|-----------------------------------------:|----------------:|-----------------:|
|  0 |     1 |           25 |        8 |                                        4 |             150 |            84.9  |
|  1 |     2 |           30 |        6 |                                        6 |             100 |            89.31 |
|  2 |     3 |           30 |        6 |                                        4 |             100 |            90.71 |
|  3 |     4 |           30 |        6 |                                        6 |              50 |            91.09 |
|  4 |     5 |           30 |        6 |                                        6 |             100 |            89.34 |
|  5 |     6 |           25 |        8 |                                        8 |              50 |            87.38 |
|  6 |     7 |           30 |        8 |                                        6 |             100 |            92.12 |
|  7 |     8 |           30 |        4 |                                        6 |             100 |            87.16 |
|  8 |     9 |           35 |        8 |                                        4 |              50 |            92.14 |
|  9 |    10 |           35 |        4 |                                        8 |              50 |            85.56 |
| 10 |    11 |           30 |        6 |                                        6 |             150 |            85.15 |
| 11 |    12 |           35 |        6 |                                        6 |             100 |            88.86 |
| 12 |    13 |           35 |        8 |                                        4 |             150 |            91.16 |
| 13 |    14 |           35 |        8 |                                        8 |             150 |            87.57 |
| 14 |    15 |           25 |        4 |                                        8 |             150 |            77.24 |
| 15 |    16 |           35 |        4 |                                        4 |             150 |            84.04 |
| 16 |    17 |           30 |        6 |                                        6 |             100 |            89.61 |
| 17 |    18 |           35 |        4 |                                        8 |             150 |            80.9  |
| 18 |    19 |           25 |        8 |                                        8 |             150 |            80.34 |
| 19 |    20 |           35 |        4 |                                        4 |              50 |            87.16 |
| 20 |    21 |           25 |        6 |                                        6 |             100 |            85.77 |
| 21 |    22 |           30 |        6 |                                        6 |             100 |            89.31 |
| 22 |    23 |           35 |        8 |                                        8 |              50 |            90.82 |
| 23 |    24 |           25 |        4 |                                        4 |              50 |            89.43 |
| 24 |    25 |           30 |        6 |                                        8 |             100 |            86.87 |
| 25 |    26 |           30 |        6 |                                        6 |             100 |            89.14 |
| 26 |    27 |           25 |        8 |                                        4 |              50 |            91.03 |
| 27 |    28 |           30 |        6 |                                        6 |             100 |            90.14 |
| 28 |    29 |           25 |        4 |                                        4 |             150 |            81.58 |
| 29 |    30 |           25 |        4 |                                        8 |              50 |            85.48 |

## pdf1_t4
|    | Source     | DF       |   Adjusted SS |   Adj MS |   F value |   p value |
|---:|:-----------|:---------|--------------:|---------:|----------:|----------:|
|  0 | Model      | 14       |       401.025 |  28.6446 |    218.33 |     0     |
|  1 | x1         | 1        |         6.457 |   6.4568 |     49.21 |     0     |
|  2 | x2         | 1        |         2.068 |   2.068  |     15.76 |     0.001 |
|  3 | x3         | 1        |         0.014 |   0.0141 |      0.11 |     0.748 |
|  4 | x4         | 1        |         2.209 |   2.209  |     16.84 |     0.001 |
|  5 | x2 1       | 1        |        10.26  |  10.2603 |     78.2  |     0     |
|  6 | x2 2       | 1        |         0.291 |   0.2908 |      2.22 |     0.157 |
|  7 | x2 3       | 1        |         0.687 |   0.6872 |      5.24 |     0.037 |
|  8 | x2 4       | 1        |         3.638 |   3.6382 |     27.73 |     0     |
|  9 | x1x2       | 1        |        12.443 |  12.4433 |     94.84 |     0     |
| 10 | x1x3       | 1        |         2.933 |   2.9327 |     22.35 |     0     |
| 11 | x1x4       | 1        |        18.598 |  18.5977 |    141.75 |     0     |
| 12 | x2x3       | 1        |         0.001 |   0.0005 |      0    |     0.951 |
| 13 | x2x4       | 1        |         2.616 |   2.6163 |     19.94 |     0     |
| 14 | x3x4       | 1        |         1.632 |   1.632  |     12.44 |     0.003 |
| 15 | Error      | 15       |         1.968 |   0.1312 |           |           |
| 16 | Lack-of-ft | 10       |         1.323 |   0.1323 |      1.02 |     0.523 |
| 17 | Pure error | 5        |         0.645 |   0.1291 |           |           |
| 18 | Total      | 29       |       402.993 |          |           |           |
| 19 | R2= 99.51% | Adj R2   |               |          |           |           |
| 20 | R2= 99.51% | = 99.06% |               |          |           |           |

## pdf1_t5
|    | Adsorbent(s)                                                                          | Adsorbent dosage (g/L)   | Removal percentage   | Reference                   |
|---:|:--------------------------------------------------------------------------------------|:-------------------------|:---------------------|:----------------------------|
|  0 | HCMM                                                                                  | 1                        | 77.24–95.14          | This work                   |
|  1 | Activated carbon from Rumex abyssinicus plant                                         | 0.2–0.6                  | 82.16–99.96          | Fito et al. (2023)          |
|  2 | Barley straw and corn stalks modifed by citric acid                                   | 6–14                     | 48–97                | Soldatkina & Yanar (2023)   |
|  3 | Activated carbon from Scrap Tire                                                      | 2.5                      | 89.18–90.48          | Kassahun et al. (2022)      |
|  4 | Barley Bran and Enset Midrib Leaf                                                     | 2.5                      | 96–98                | Mekuria et al. (2022)       |
|  5 | Raspberry (Rubus idaeus) leaves powder                                                | 1–5                      | 30–44                | Mosoarca et al. (2022)      |
|  6 | Activated carbon from grape leaves waste                                              | 0.25–12.25               | 0–97.4               | Mousavi et al. (2022a)      |
|  7 | Activated carbon from grape wood wastes                                               | 0.25–12.25               | 0–95.66              | Mousavi et al. (2022b)      |
|  8 | Black tea wastes                                                                      | 13.3                     | 30–72                | Ullah et al. (2022)         |
|  9 | Carboxymethyl cellulose grafted by polyacrylic acid and decorated with graphene oxide | 100                      | 38–97                | Hosseini et al. (2022)      |
| 10 | Activated carbon from Parthenium hysterophorus                                        | 20                       | 86–94                | Fito et al. (2020)          |
| 11 | Kaolin                                                                                | 1                        | 67–97                | Mouni et al. (2018)         |
| 12 | Modifed sawdust                                                                       | 1.5–5                    | 34.4–96.6            | Zou et al. (2013)           |
| 13 | Raw and modifed mango seed                                                            | 0.1–1.2                  | 68–99.8              | Senthil Kumar et al. (2014) |
| 14 | Montmorillonite modifed with iron oxide                                               | 0.1                      | 26.78–60.98          | Cottet et al. (2014)        |
| 15 | Activated carbon from barley straw                                                    | 0.1                      | 5–70                 | Husseien et al. (2007)      |
| 16 | Fly ash                                                                               | 8–20                     | 45.16–96             | Kumar et al. (2005)         |

## pdf1_t6
|    | Variable                                               |   Optimum value |
|---:|:-------------------------------------------------------|----------------:|
|  0 | Initial concentration of dye (mg L−1)                  |            4    |
|  1 | Temperature (°C)                                       |           32    |
|  2 | pH                                                     |            8    |
|  3 | Adsorbent mesh size                                    |           70    |
|  4 | Predicted removal percentage                           |           93.91 |
|  5 | Experimental removal percentage at optimal condi￾tions |           95.14 |

## pdf1_t7
|    | Model                | Parameters        | Parameters   |
|---:|:---------------------|:------------------|:-------------|
|  0 | Langmuir             | qm(mg g−1)        | 159          |
|  1 | Langmuir             | kL(L mg−1)        | 0.0956       |
|  2 | Langmuir             | R2                | 0.984        |
|  3 | Freundlich           | n                 | 2.52         |
|  4 | Freundlich           | kF(mg g−1)        | 26.42        |
|  5 | Freundlich           | R2                | 0.891        |
|  6 | Temkin               | B                 | 29.245       |
|  7 | Temkin               | kT(L mg−1)        | 1.518        |
|  8 | Temkin               | b(J g mg−1 mol−1) | 87           |
|  9 | Temkin               | R2                | 0.970        |
| 10 | Dubinin–Radushkevich | kD                | 3.71×10−9    |
| 11 | Dubinin–Radushkevich | qD(mg g−1)        | 420.0        |
| 12 | Dubinin–Radushkevich | E (kJ mol−1)      | 11.60        |
| 13 | Dubinin–Radushkevich | R2                | 0.910        |

## pdf1_t8
|    | Kinetic model           | Parameters           |   Parameters |
|---:|:------------------------|:---------------------|-------------:|
|  0 | Linear driving force    | k1(min−1)            |       0.0604 |
|  1 | Linear driving force    | qe,calc(mg g−1)      |      22.39   |
|  2 | Linear driving force    | qe,exp(mg g−1)       |      54.28   |
|  3 | Linear driving force    | R2                   |       0.927  |
|  4 | Pseudo-second-order     | qe,calc(mg g−1)      |      55.57   |
|  5 | Pseudo-second-order     | k2(g.mg−1 min−1)     |       0.018  |
|  6 | Pseudo-second-order     | R2                   |       0.999  |
|  7 | Intra-particle difusion | k3,1(mg g−1 min−0.5) |       1.766  |
|  8 | Intra-particle difusion | I1(mg g−1)           |      39.36   |
|  9 | Intra-particle difusion | R2 1                 |       0.992  |
| 10 | Intra-particle difusion | k3,2(mg g−1 min−0.5) |       0.131  |
| 11 | Intra-particle difusion | I2(mg g−1)           |      52.96   |
| 12 | Intra-particle difusion | R2 2                 |       1      |

## pdf1_t9
|    |                                                                                                                                                                                                                                                                                  |
|---:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  0 | cel￾lulose nanofbril-based composites. J Colloid Interface                                                                                                                                                                                                                       |
|  1 | 555:104–114                                                                                                                                                                                                                                                                      |
|  2 | Ludueña LN, Vecchio A, Stefani PM, Alvarez VA (2013) Extraction                                                                                                                                                                                                                  |
|  3 | of cellulose nanowhiskers from natural fbers and agricultural                                                                                                                                                                                                                    |
|  4 | byproducts. Fibers Polym 14(7):1118–1127                                                                                                                                                                                                                                         |
|  5 | Macfarlane C, Warren CR, White DA, Adams MA (1999) A rapid                                                                                                                                                                                                                       |
|  6 | and simple method for processing wood to crude cellulose                                                                                                                                                                                                                         |
|  7 | analysis of stable carbon isotopes in tree rings. Tree Physiol                                                                                                                                                                                                                   |
|  8 | 19(12):831–835                                                                                                                                                                                                                                                                   |
|  9 | Mahmoodi NM, Hayati B, Arami M (2012) Kinetic, equilibrium                                                                                                                                                                                                                       |
| 10 | thermodynamic studies of ternary system dye removal using                                                                                                                                                                                                                        |
| 11 | biopolymer. Ind Crops Prod 35(1):295–301                                                                                                                                                                                                                                         |
| 12 | Malyan SK, Singh R, Rawat M, Kumar M, Pugazhendhi A, Kumar                                                                                                                                                                                                                       |
| 13 | A, Kumar V, Kumar SS (2019) An overview of carcinogenic                                                                                                                                                                                                                          |
| 14 | pollutants in groundwater of India. Biocatal Agric Biotechnol                                                                                                                                                                                                                    |
| 15 | 21:101288 Mane VS, Deo Mall I, Chandra Srivastava V (2007) Kinetic and                                                                                                                                                                                                           |
| 16 | equi￾librium isotherm studies for the adsorptive removal of Brilliant Green dye from aqueous solution by rice husk ash. J Environ                                                                                                                                                |
| 17 | Manag 84(4):390–400 Mekuria D, Diro A, Melak F, Asere TG (2022) Adsorptive removal of blue biowaste materials: bran                                                                                                                                                              |
| 18 | methylene dye using barley enset midrib leaf. J Chem 2022:4849758 Melgoza D, Hernández-Ramírez A, Peralta-Hernández JM (2009)                                                                                                                                                    |
| 19 | Comparative efciencies of the decolourisation of Methylene Blue using Fenton’s and photo-Fenton’s reactions. Photochem Photobiol Sci 8(5):596–599                                                                                                                                |
| 20 | Mills A, Hazafy D, Parkinson J, Tuttle T, Hutchings MG (2011) Efect of alkali on methylene blue (C.I. Basic Blue 9) and other thiazine                                                                                                                                           |
| 21 | dyes. Dyes Pigm 88(2):149–155 Mohamed RR (2022) Applications of nanocomposites in environmental remediation. In: Shalan AE, Hamdy Makhlouf AS, Lanceros￾Méndez                                                                                                                   |
| 22 | S (eds) Advances in nanocomposite materials for envi￾ronmental and energy harvesting applications. Springer Interna￾tional Publishing, Cham, pp 453–471 Monash P, Pugazhenthi G (2009) Adsorption of crystal violet from aqueous solution using mesoporous materials synthesized |
| 23 | at room temperature. Adsorption 15(4):390–405                                                                                                                                                                                                                                    |
| 24 | Mosoarca G, Popa S, Vancea C, Dan M, Boran S (2022) Removal of methylene blue from solutions using a new natural                                                                                                                                                                 |
| 25 | aqueous lignocellulosic adsorbent—Raspberry (Rubus idaeus) leaves powder. Polymers 14(10):1966                                                                                                                                                                                   |
| 26 | Mostafa NA, Farouk SM, Abdelhamid SMS, Monazie AM (2021)                                                                                                                                                                                                                         |
| 27 | Opti￾misation and characterisation of bio-adsorbent based on barley straw and coconut shell. J Environ Eng Sci 17(2):89–98                                                                                                                                                       |
| 28 | Mouni L, Belkhiri L, Bollinger J-C, Bouzaza A, Assadi A, Tirri                                                                                                                                                                                                                   |
| 29 | Dahmoune F, Madani K, Remini H (2018) Removal of                                                                                                                                                                                                                                 |
| 30 | Methyl￾ene Blue from aqueous solutions by adsorption on Kaolin: kinetic and equilibrium studies. Appl Clay Sci 153:38–45                                                                                                                                                         |
| 31 | Mousavi SA, Mahmoudi A, Amiri S, Darvishi P, Noori E (2022a)                                                                                                                                                                                                                     |
| 32 | Methylene blue removal using grape leaves waste: optimization                                                                                                                                                                                                                    |
| 33 | and modeling. Appl Water Sci 12(5):112                                                                                                                                                                                                                                           |
| 34 | Mousavi SA, Shahbazi D, Mahmoudi A, Darvishi P (2022b) Methylene                                                                                                                                                                                                                 |
| 35 | blue removal using prepared activated carbon from grape wood wastes: and Water                                                                                                                                                                                                   |
| 36 | adsorption process analysis modeling. Qual Res J 57(1):1–19                                                                                                                                                                                                                      |
| 37 | Mulushewa Z, Dinbore WT, Ayele Y (2021) Removal of methylene                                                                                                                                                                                                                     |
| 38 | blue from textile waste water using kaolin and zeolite-x syn￾thesized from Ethiopian kaolin. Environ Anal Health Toxicol                                                                                                                                                         |
| 39 | 36(1):e2021007                                                                                                                                                                                                                                                                   |

## pdf2_t0
|    | Stage of phar￾macokinetic modeling   | Data utilized                                                                                                                                             | Modeling activities                                                                                                                            |
|---:|:-------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------|
|  0 | Stage 1                              | ManNAc single dose pharmacokinetic data (Study 12-HG￾0207)                                                                                                | Design of structural pharmacokinetic model Explore absorption models                                                                           |
|  1 | Stage 2                              | ManNAc BID pharmacokinetic data (Study 15-HG-0068)                                                                                                        | Covariate analysis Determination of non-linear and stationary pharmacokinetic                                                                  |
|  2 | Stage 3                              | Stage 2 population pharmacokinetic model for ManNAc and Neu5Ac                                                                                            | Monte Carlo simulations of dosing regimens Recommendation for evaluation of additional TID dosing regimens in an extension of Study 15-HG-0068 |
|  3 | Stage 4                              | All available data, including the additional TID dosing phar￾macokinetic data generated during extension conducted in same patients from Study 15-HG-0068 | Finalize pharmacokinetic model                                                                                                                 |

## pdf2_t1
|    | Variable                 | N (%)     |    Mean |      SD |   Median |    Min |    Max |
|---:|:-------------------------|:----------|--------:|--------:|---------:|-------:|-------:|
|  0 | Age (years)              | 34        |  41.3   |  10.4   |    39.5  |  25    |  65    |
|  1 | Weight (kg)              | 34        |  83.5   |  20.2   |    84.6  |  49.3  | 115    |
|  2 | Height (cm)              | 34        | 173     |  13.3   |   172    | 151    | 197    |
|  3 | BMI (kg/m2 )             | 34        |  27.6   |   4.7   |    27.2  |  19.1  |  39.8  |
|  4 | BSA (m2 )                | 34        |   2.01  |   0.31  |     2.06 |   1.45 |   2.5  |
|  5 | eGFR (mL/min)a           | 34        | 123     |  22.2   |   120    |  85    | 170    |
|  6 | Albumin (g/dL)           | 34        |   3.83  |   0.403 |     3.8  |   3.2  |   4.8  |
|  7 | Serum creatinine (mg/dL) | 34        |   0.499 |   0.223 |     0.49 |   0.12 |   0.95 |
|  8 | Creatine kinase (U/L)    | 34        | 236     | 124     |   220    |  44    | 556    |
|  9 | Sex                      |           |         |         |          |        |        |
| 10 | Male                     | 16 (47.1) |         |         |          |        |        |
| 11 | Female                   | 18 (52.9) |         |         |          |        |        |
| 12 | Race                     |           |         |         |          |        |        |
| 13 | Caucasian                | 24 (70.6) |         |         |          |        |        |
| 14 | Asian                    | 8 (26.5)  |         |         |          |        |        |
| 15 | Other                    | 2 (2.94)  |         |         |          |        |        |
| 16 | GNE domain mutations     |           |         |         |          |        |        |
| 17 | Epimerase/kinase         | 23 (67.6) |         |         |          |        |        |
| 18 | Kinase/kinase            | 8 (23.5)  |         |         |          |        |        |
| 19 | Deletion/kinase          | 2 (5.88)  |         |         |          |        |        |
| 20 | Epimerase/epimerase      | 1 (2.94)  |         |         |          |        |        |

## pdf2_t2
|    | ('ManNAc dose', nan)   | ('Q8H for 30 days', 'Median')   | ('Q8H for 30 days', '5th–95th percentiles')   |   ('Q12H for 30 days', 'Median') | ('Q12H for 30 days', '5th–95th percentiles')   |   ('Q24H for 30 days', 'Median') | ('Q24H for 30 days', '5th–95th percentiles')   |
|---:|:-----------------------|:--------------------------------|:----------------------------------------------|---------------------------------:|:-----------------------------------------------|---------------------------------:|:-----------------------------------------------|
|  0 | Plasma ManNAc          | Css,ave (ng/mL)                 |                                               |                                  |                                                |                                  |                                                |
|  1 | 3 g                    | 922                             | 501–1550                                      |                              642 | 359–1060                                       |                              365 | 223–570                                        |
|  2 | 4 g                    | 1060                            | 573–1790                                      |                              729 | 404–1220                                       |                              411 | 246–650                                        |
|  3 | 6 g                    | 1290                            | 692–2180                                      |                              881 | 480–1480                                       |                              483 | 281–780                                        |
|  4 | 10 g                   | 1650                            | 883–2810                                      |                             1120 | 607–1900                                       |                              603 | 340–989                                        |
|  5 | Plasma Neu5Ac          | Css,ave (ng/mL)                 |                                               |                                  |                                                |                                  |                                                |
|  6 | 3 g                    | 633                             | 247–2010                                      |                              484 | 209–1420                                       |                              338 | 174–825                                        |
|  7 | 4 g                    | 702                             | 265–2300                                      |                              533 | 222–1610                                       |                              364 | 181–921                                        |
|  8 | 6 g                    | 818                             | 296–2780                                      |                              612 | 242–1930                                       |                              405 | 190–1080                                       |
|  9 | 10 g                   | 1020                            | 344–3540                                      |                              735 | 274–2440                                       |                              464 | 204–1330                                       |

## pdf2_t3
|    | Parameter                            | Final typical value estimate   | %SEM   |
|---:|:-------------------------------------|:-------------------------------|:-------|
|  0 | ka (h−1)                             | 0.256                          | 15.2   |
|  1 | CLM/F (L/h)                          | 631                            | 14.8   |
|  2 | VM/F (L)                             | 506                            | 29.4   |
|  3 | M0 (ng/mL)                           | 61.1                           | 12.0   |
|  4 | N0 (ng/mL)                           | 150                            | 5.71   |
|  5 | kout (h−1)                           | 0.283                          | 5.65   |
|  6 | SLP0 (ng/mL)−1                       | 0.000619                       | 29.1   |
|  7 | SLPSS (ng/mL)−1                      | 0.00334                        | 35.0   |
|  8 | kinc (h−1)                           | 0.0287                         | 45.3   |
|  9 | tlag (h)                             | 0.254                          | 26.4   |
| 10 | ksyn (μg/h)a                         | 38,554                         | N/A    |
| 11 | kpro (ng/mL·h)a                      | 40.9                           | N/A    |
| 12 | Relative ManNAc bio￾availability (F) |                                |        |
| 13 | F for 6 g dose                       | 1                              | Fixed  |
| 14 | F-Dose slope                         | −0.405                         | 39.0   |
| 15 | ω2 for ka                            | 0.0697 (26.4% CV)              | 91.4   |
| 16 | ω2 for CLM/F                         | 0.0636 (25.2% CV)              | 93.2   |
| 17 | ω2 for VM/F                          | 0.120 (34.6% CV)               | 170    |
| 18 | ω2 for M0                            | 0.0966 (31.1% CV)              | 43.5   |
| 19 | ω2 for N0                            | 0.0439 (21.0% CV)              | 55.4   |
| 20 | ω2 for SLPSS                         | 0.383 (61.9% CV)               | 130    |
| 21 | IOV on CLM/F                         | 0.0580 (24.1% CV)              | 63.6   |
| 22 | σ2 CCV component                     | 0.102 (31.9% CV)               | 8.13   |
| 23 | Additive component                   | 0.0370 (19.2% CV)              | 5.68   |

## pdf3_t0
|    | ('Received: 26 January 2023', 'Accepted: 8 May 2023')   | ('Pau Ferri1,4, Chengeng Li 1,4, Daniel Schwalbe-Koda2 , Mingrou Xie3 ,', 'Manuel Moliner 1 , Rafael Gómez-Bombarelli 2 , Mercedes Boronat 1 & Avelino Corma 1')                                  |
|---:|:--------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  0 | Check for updates                                       | Approaching the level of molecular recognition of enzymes with solid catalysts                                                                                                                    |
|  1 | Check for updates                                       | is a challenging goal, achieved in this work for the competing transalkylation and disproportionation of diethylbenzene catalyzed by acid zeolites. The key                                       |
|  2 | Check for updates                                       | diaryl intermediates for the two competing reactions only differ in the number                                                                                                                    |
|  3 | Check for updates                                       | of ethyl substituents in the aromatic rings, and therefore finding a selective                                                                                                                    |
|  4 | Check for updates                                       | zeolite able to recognize this subtle difference requires an accurate balance of                                                                                                                  |
|  5 | Check for updates                                       | the stabilization of reaction intermediates and transition states inside the                                                                                                                      |
|  6 | Check for updates                                       | zeolite microporous voids. In this work we present a computational                                                                                                                                |
|  7 | Check for updates                                       | metho￾dology that, by combining a fast high-throughput screeening of all zeolite                                                                                                                  |
|  8 | Check for updates                                       | structures able to stabilize the key intermediates with a more computationally                                                                                                                    |
|  9 | Check for updates                                       | demanding mechanistic study only on the most promising candidates, guides                                                                                                                         |
| 10 | Check for updates                                       | the selection of the zeolite structures to be synthesized. The methodology presented is validated experimentally and allows to go beyond the conven￾tional criteria of zeolite shape-selectivity. |

## pdf3_t1
|    |     | Channels system   |   n | Itrans (kJ/mol)   | Idisp (kJ/mol)   |   Idisp /Itrans |
|---:|:----|:------------------|----:|:------------------|:-----------------|----------------:|
|  0 | BEA | 12 × 12 × 12      |   3 | −148              | −129             |            0.87 |
|  1 | BEC | 12 × 12 × 12      |   1 | −123              | −151             |            1.22 |
|  2 | BOG | 12 × 10 × 10      |   4 | −140              | −140             |            1    |
|  3 | CON | 12 × 10 × 10      |   2 | −132              | −149             |            1.14 |
|  4 | FAU | 12 × 12 × 12      |   7 | −104              | −106             |            1.02 |
|  5 | ITT | 18 × 10 × 10      |   4 | −110              | −155             |            1.41 |
|  6 | IWR | 12 × 10 × 10      |   1 | −145              | −174             |            1.2  |
|  7 | IWV | 12 × 12           |   2 | −102              | −90              |            0.88 |
|  8 | MOR | 12 × 8            |   2 | −141              | −104             |            0.74 |
|  9 | SEW | 12 × 10           |   2 | −160              | −188             |            1.18 |
| 10 | USI | 12 × 10           |   2 | −128              | −157             |            1.22 |
| 11 | UTL | 14 × 12           |   2 | −105              | −137             |            1.31 |

## pdf3_t2
|    | Channels system    | Channels system   | Ea1   | Ea2   | Ea3   | Ea4   | Ea5   | Ea6   |
|---:|:-------------------|:------------------|:------|:------|:------|:------|:------|:------|
|  0 | transalkylation    |                   | Ea1   | Ea2   | Ea3   | Ea4   | Ea5   | Ea6   |
|  1 | BEC                | 12 × 12 × 12      | 98    | 35    | 44    | 48    | 85    | 98    |
|  2 | BOG                | 12 × 10 × 10      | 75    | 29    | 65    | 50    | 88    | 96    |
|  3 | IWR                | 12 × 10 × 10      | 71    | 31    | 60    | 44    | 91    | 90    |
|  4 | IWV                | 12 × 12           | 56    | 21    | 52    | 47    | 60    | 86    |
|  5 | MOR                | 12 × 8            | 95    | 33    | 78    | 50    | 84    | 87    |
|  6 | UTL(int)           | 14 × 12           | 59    | 29    | 49    | 49    | 82    | 97    |
|  7 | UTL(cha)           | 14 × 12           | 64    | 28    | 57    | 45    | 68    | 80    |
|  8 | disproportionation |                   |       |       |       |       |       |       |
|  9 | BEC                | 12 × 12 × 12      | 113   | 30    | 56    | 55    | 78    | 118   |
| 10 | IWV                | 12 × 12           | 72    | 30    | 75    | 59    | 67    | 104   |
| 11 | UTL(int)           | 14 × 12           | 90    | 29    | 69    | 58    | 71    | 98    |
| 12 | UTL(cha)           | 14 × 12           | 80    | 22    | 73    | 46    | 82    | 97    |

## pdf3_t3
|    | zeolite   | IZA code   |   DEB conv. (%) |   rtrans (molEB/molacidh) |   EB (%) |   TEB (%) |   C2H4 (%) |   HP (%) |   Eaa (kJ/mol) |
|---:|:----------|:-----------|----------------:|--------------------------:|---------:|----------:|-----------:|---------:|---------------:|
|  0 | ITQ-33    | ITT        |            11.9 |                       717 |     76.4 |      20.8 |        0.6 |      2.1 |           75.2 |
|  1 | ITQ-15    | UTL        |            17.7 |                      1599 |     85.7 |      12   |        0   |      2.3 |           56.1 |
|  2 | USY       | FAU        |            14.7 |                      1075 |     90.1 |       2.7 |        2.7 |      4.5 |           66.5 |
|  3 | ITQ-17    | BEC        |            20.8 |                       628 |     88.8 |       8.3 |        0.5 |      2.3 |           59.5 |
|  4 | ITQ-27    | IWV        |            14.9 |                      1926 |     94.1 |       0.5 |        2.3 |      3   |           58.3 |
|  5 | ITQ-24    | IWR        |            15.2 |                       676 |     95.1 |       2.5 |        0.4 |      2   |           69.4 |
|  6 | ITQ-47    | BOG        |            14.4 |                       349 |     90.4 |       4.4 |        4.8 |      0.4 |           66.2 |
|  7 | mordenite | MOR        |             9.6 |                       279 |     88.6 |       2.5 |        4.6 |      4.2 |           74.2 |

## pdf4_t0
|    |    |    |    |    |    |    |
|----|----|----|----|----|----|----|

## pdf4_t1
|    | Data Platform                    | Number of Features          |    | Number of tumors   |
|---:|:---------------------------------|:----------------------------|:---|:-------------------|
|  0 | Number of features and tumors in | different data platforms    |    |                    |
|  1 | Radiomics                        | 38                          |    | 91                 |
|  2 | Gene expressions                 | 20531 genes (186 pathways)  |    | 91                 |
|  3 | Copy number variations           | 19950 genes (186 pathways)  |    | 91                 |
|  4 | miRNA expressions                | 1046                        |    | 91                 |
|  5 | Protein expressions              | 142                         |    | 62                 |
|  6 | Mutated genes                    | 3734                        |    | 91                 |
|  7 | Number of tumors with different  | pathological stages         |    |                    |
|  8 | Pathological Stage               | T M                         | N  | Overall            |
|  9 | 0                                | 91                          | 46 |                    |
| 10 | I                                | 38                          | 34 | 22                 |
| 11 | II                               | 50                          | 6  | 58                 |
| 12 | III                              | 3                           | 4  | 11                 |
| 13 | X                                |                             | 1  |                    |
| 14 | Number of tumors with different  | molecular receptor statuses |    |                    |
| 15 | Receptor Status                  | ER                          | PR | HER2               |
| 16 | Negative                         | 14                          | 19 | 72                 |
| 17 | Positive                         | 77                          | 72 | 19                 |

## pdf5_t0
|    |                           | SF-ROXOX      | SF-ROXNIT     | SF-ROXRED     |
|---:|:--------------------------|:--------------|:--------------|:--------------|
|  0 | No. of crystals           | 75            | 62            | 33            |
|  1 | Images collected          | 1867          | 1257          | 581           |
|  2 | Images merged             | 1377          | 1039          | 410           |
|  3 | Data collection           |               |               |               |
|  4 | Space group               | P213          | P213          | P213          |
|  5 | a = b = c (A˚ )           | 94.95         | 94.92         | 94.61         |
|  6 |  =  =  ( )                           | 90            | 90            | 90            |
|  7 | Resolution (A˚ )          | 54.82–1.50    | 54.80–1.50    | 54.62–1.60    |
|  8 |                           | (1.54–1.50)   | (1.54–1.50)   | (1.64–1.60)   |
|  9 | Rsplit† (%)               | 11.5 (90.4)   | 10.6 (85.3)   | 15.8 (70.8)   |
| 10 | hI/(I)i                           | 6.3 (2.0)     | 6.6 (2.3)     | 5.4 (2.7)     |
| 11 | CC1/2‡                    | 0.980 (0.157) | 0.984 (0.288) | 0.957 (0.384) |
| 12 | Completeness (%)          | 100.0 (100.0) | 100.0 (100.0) | 100.0 (100.0) |
| 13 | Multiplicity              | 220.9 (77.2)  | 154.7 (50.8)  | 66.1 (44.3)   |
| 14 | Wilson B factor (A˚ 2 )   | 14.9          | 14.5          | 17.5          |
| 15 | Refinement                |               |               |               |
| 16 | No. of unique reflections | 45883 (2276)  | 45846 (2275)  | 37489 (1858)  |
| 17 | Rwork/Rfree (%)           | 14.4/17.7     | 14.3/17.1     | 16.7/19.9     |
| 18 | No. of atoms              |               |               |               |
| 19 | Protein                   | 2608          | 2595          | 2580          |
| 20 | Ligand/ion                | 37            | 34            | 59            |
| 21 | Water                     | 425           | 418           | 279           |
| 22 | B factors (A˚ 2 )         |               |               |               |
| 23 | Protein                   | 18.9          | 18.7          | 21.9          |
| 24 | Cu                        | 16.5          | 16.2          | 19.5          |
| 25 | SO4 2                     | 33.2          | 41.5          |               |
| 26 | NO2                       | 18.5          |               |               |
| 27 | Malonate                  |               | 37.2          | 30.1          |
| 28 | Water                     | 30.0          | 30.0          | 32.7          |
| 29 | R.m.s. deviations         |               |               |               |
| 30 | Bond lengths (A˚ )        | 0.013         | 0.013         | 0.015         |
| 31 | Bond angles ()                           | 1.612         | 1.594         | 1.534         |
| 32 | PDB code                  | 6gsq          | 6gt0          | 6gt2          |

## pdf5_t1
|    |                           |                     |
|---:|:--------------------------|:--------------------|
|  0 | Data collection           |                     |
|  1 | Wavelength range (A˚ )    | 3.05–4.00           |
|  2 | No. of images             | 20                  |
|  3 | Setting spacing ()                           | 7                   |
|  4 | Average exposure time (h) | 18                  |
|  5 | Space group               | P213                |
|  6 | a = b = c (A˚ )           | 97.98               |
|  7 |  =  =  ( )                           | 90                  |
|  8 | Resolution (A˚ )          | 40–1.80 (1.90–1.80) |
|  9 | Rp.i.m. (%)               | 6.3 (12.7)          |
| 10 | hI/(I)i                           | 7.9 (3.7)           |
| 11 | Completeness (%)          | 85.5 (69.8)         |
| 12 | Multiplicity              | 6.5 (2.9)           |
| 13 | Refinement                |                     |
| 14 | No. of unique reflections | 24728               |
| 15 | Rwork/Rfree (%)           | 23.17/27.64         |
| 16 | No. of atoms              |                     |
| 17 | Total                     | 5659                |
| 18 | Protein                   | 5109                |
| 19 | Cu                        | 2                   |
| 20 | D2O                       | 182 D2O [546 atoms] |
| 21 | O                         | 2                   |
| 22 | B factors (A˚ 2 )         |                     |
| 23 | Protein                   | 15.2                |
| 24 | Cu                        | 8.6                 |
| 25 | Water                     | 20.2                |
| 26 | R.m.s. deviations         |                     |
| 27 | Bond lengths (A˚ )        | 0.004               |
| 28 | Bond angles ()                           | 0.884               |
| 29 | PDB code                  | 6gtj                |

## pdf6_t0
|    | Year   | Variety   | Treatment   | Spikelets per panicle   | 1000-grain weight (g)   | Seed setting (%) rate   | Seed setting (%) rate   |
|---:|:-------|:----------|:------------|:------------------------|:------------------------|:------------------------|:------------------------|
|  0 | 2019   | CJ03      | T0          | 267.67a                 | 21.87c                  | 87.67c                  |                         |
|  1 | 2019   | CJ03      | T1          | 91.17b                  | 20.10d                  | 93.00b                  |                         |
|  2 | 2019   | W1844     | T0          | 275.67a                 | 22.91b                  | 84.92d                  |                         |
|  3 | 2019   | W1844     | T1          | 97.92b                  | 25.95a                  | 95.58a                  |                         |
|  4 | 2020   | CJ03      | T0          | 259.75a                 | 22.38c                  | 92.25b                  |                         |
|  5 | 2020   | CJ03      | T1          | 77.50c                  | 20.97d                  | 94.17a                  |                         |
|  6 | 2020   | W1844     | T0          | 273.67a                 | 24.35b                  | 85.17c                  |                         |
|  7 | 2020   | W1844     | T1          | 92.58b                  | 25.19a                  | 94.67a                  |                         |
|  8 | Year   | Variety   | Treatment   | SG per panicle          | IG per panicle          | SG rate (%)             | IG rate (%)             |
|  9 | 2019   | CJ03      | T0          | 104.65a                 | 163.02b                 | 39.10a                  | 60.90b                  |
| 10 | 2019   | W1844     | T1          | 31.04c                  | 60.13d                  | 34.05a                  | 65.95b                  |
| 11 | 2019   | W1844     | T0          | 68.31b                  | 207.36a                 | 24.78b                  | 75.22a                  |
| 12 | 2019   | W1844     | T1          | 24.15d                  | 73.77c                  | 24.67b                  | 75.33a                  |
| 13 | 2020   | CJ03      | T0          | 80.83a                  | 178.92b                 | 31.12a                  | 68.88b                  |
| 14 | 2020   | CJ03      | T1          | 23.25c                  | 54.25d                  | 30.00a                  | 70.00b                  |
| 15 | 2020   | W1844     | T0          | 67.33b                  | 206.34a                 | 24.60b                  | 75.40a                  |
| 16 | 2020   | W1844     | T1          | 22.42c                  | 70.16c                  | 24.21b                  | 75.79a                  |

## pdf6_t1
|    |   Year | Variety   | Treatment   | Net photosynthetic rate (umol·m−2 s−1 )   | Stomatal conductance (mmol·m−2 s−1 )   | Intercellular CO2 concentration (μmol·mol−1 )   | Trmmol rate (mmol·m−2 s−1 )   |
|---:|-------:|:----------|:------------|:------------------------------------------|:---------------------------------------|:------------------------------------------------|:------------------------------|
|  0 |   2019 | CJ03      | T0          | 22.51a                                    | 0.65b                                  | 285.30b                                         | 6.53a                         |
|  1 |   2019 | CJ03      | T1          | 20.06c                                    | 0.52c                                  | 268.55c                                         | 5.32c                         |
|  2 |   2019 | W1844     | T0          | 21.91a                                    | 0.74a                                  | 305.32a                                         | 6.28a                         |
|  3 |   2019 | W1844     | T1          | 20.72b                                    | 0.60bc                                 | 274.15b                                         | 5.68b                         |
|  4 |   2020 | CJ03      | T0          | 25.40a                                    | 0.86a                                  | 225.50ab                                        | 13.73a                        |
|  5 |   2020 | CJ03      | T1          | 20.92c                                    | 0.54c                                  | 210.57c                                         | 11.72c                        |
|  6 |   2020 | W1844     | T0          | 24.91a                                    | 0.89a                                  | 233.63a                                         | 13.78a                        |
|  7 |   2020 | W1844     | T1          | 21.92b                                    | 0.75b                                  | 220.72b                                         | 12.71b                        |

## pdf6_t2
|    | IS         | Inferior spikelets                |                                    |      |
|---:|:-----------|:----------------------------------|:-----------------------------------|:-----|
|  0 | SS         | Superior spiklelets               |                                    |      |
|  1 | OsSWEET11  | Oryza sativa Sugar will           | eventually be exported transporter | 11   |
|  2 | OsSUTs     | Oryza sativa Sucrose transporters |                                    |      |
|  3 | SPS        | Sucrose-phosphate synthase        |                                    |      |
|  4 | SuSase     | Sucrose synthase                  |                                    |      |
|  5 | AGPase     | ADP-glucose pyrophosphorylase     |                                    |      |
|  6 | T6P        | Trehalose-6-phosphate             |                                    |      |
|  7 | SnRK1      | Snf1-related protein kinase-1     |                                    |      |
|  8 | TPS        | Trehalose-6-phosphate             | synthase                           |      |
|  9 | TPP        | Trehalsoe-6-phosphate             | phosphatase                        |      |
| 10 | ABA        | Abscisic acid                     |                                    |      |
| 11 | CKs        | Cytokinins                        |                                    |      |
| 12 | ZT         | Zeatin                            |                                    |      |
| 13 | IAA        | Auxin                             |                                    |      |
| 14 | SG         | Superior spikelets                |                                    |      |
| 15 | IG         | Inferior spikelets                |                                    |      |
| 16 | DPA        | Days post anthesis                |                                    |      |
| 17 | HPLC–MS/MS | High-performance liquid           | chromatography–tandem              | mass |
| 18 |            | spectrometry                      |                                    |      |
| 19 | ANOVA      | Analysis of variance              |                                    |      |

## pdf7_t0
|    | (nan, 'Patient no')   | (nan, 'Genotype')   | (nan, 'Viral load (106 IU/ml)')   | (nan, 'Sex')   | (nan, 'Age (years)')   | ('Core amino acid', '70')   | ('Core amino acid', '91')   | (nan, 'rs12979860')   | (nan, 'End of treatment response a')   |
|---:|:----------------------|:--------------------|:----------------------------------|:---------------|:-----------------------|:----------------------------|:----------------------------|:----------------------|:---------------------------------------|
|  0 | R1                    | 1a                  | 4.36                              | M              | 52.6                   | R                           | C                           | CC                    | SVR                                    |
|  1 | R2                    | 1a                  | 6.37                              | M              | 34.9                   | R                           | C                           | CC                    | SVR                                    |
|  2 | R3                    | 1a                  | 7.84                              | M              | 45.8                   | R                           | C                           | CC                    | SVR                                    |
|  3 | R4                    | 1a                  | 7.77                              | F              | 42.3                   | R                           | C                           | CC                    | SVR                                    |
|  4 | R5                    | 1a                  | 7.05                              | M              | 45.3                   | R                           | C                           | CC                    | SVR                                    |
|  5 | R6                    | 1a                  | 7.19                              | F              | 45.5                   | R                           | C                           | CC                    | SVR                                    |
|  6 | R7                    | 1a                  | 5.54                              | F              | 46.9                   | R                           | C                           | CC                    | SVR                                    |
|  7 | R8                    | 1a                  | 5.46                              | M              | 29.1                   | R                           | C                           | CT                    | SVR                                    |
|  8 | R9                    | 1a                  | 6.18                              | M              | 50.7                   | R                           | C                           | CC                    | SVR                                    |
|  9 | R10                   | 1a                  | 6.42                              | M              | 59.9                   | R                           | C                           | CC                    | SVR                                    |
| 10 | R11                   | 1a                  | 5.85                              | M              | 46.4                   | R                           | C                           | CC                    | SVR                                    |
| 11 | R12                   | 1a                  | 7.25                              | M              | 36.4                   | R                           | C                           | CT                    | SVR                                    |
| 12 | R13                   | 1a                  | 6.43                              | M              | 57.5                   | R                           | C                           | CC                    | SVR                                    |
| 13 | R14                   | 1a                  | 6.06                              | M              | 39.2                   | R                           | C                           | CT                    | SVR                                    |
| 14 | R15                   | 1a                  | 6.63                              | F              | 47.1                   | R                           | C                           | CT                    | SVR                                    |
| 15 | R21                   | 1a                  | 5.36                              | F              | 29.6                   | R                           | C                           | CT                    | SVR                                    |
| 16 | R22                   | 1a                  | 5.55                              | F              | 28.7                   | R                           | C                           | CT                    | SVR                                    |
| 17 | R23                   | 1a                  | 6.43                              | F              | 41.2                   | R                           | C                           | CC                    | SVR                                    |
| 18 | R24                   | 1a                  | 6.10                              | M              | 51.3                   | R                           | C                           | CC                    | SVR                                    |
| 19 | R25 R28               | 1a 1a               | 7.49 7.79                         | F M            | 55.7 41.5              | R R                         | C C                         | CC CT                 | SVR SVR                                |
| 20 | N1                    | 1a                  | 6.28                              | M              | 40.5                   | R                           | C                           | CT                    | non-SVR                                |
| 21 | N2                    | 1a                  | 6.25                              | M              | 50.3                   | R                           | C                           | CT                    | non-SVR                                |
| 22 | N3                    | 1a                  | 6.10                              | M              | 55.9                   | R                           | C                           | TT                    | non-SVR                                |
| 23 | N4                    | 1a                  | 7.05                              | M              | 47.9                   | R                           | C                           | TT                    | non-SVR                                |
| 24 | N5                    | 1a                  | 5.89                              | M              | 50.8                   | R                           | C                           | CT                    | non-SVR                                |
| 25 | N6                    | 1a                  | 6.42                              | F              | 48.1                   | P                           | C                           | CT                    | non-SVR                                |
| 26 | N7                    | 1a                  | 6.72                              | M              | 48.9                   | R                           | C                           | TT                    | non-SVR                                |
| 27 | N8 N9                 | 1a 1a               | 7.35 6.13                         | M F            | 54.6 57.8              | R R                         | C C                         | TT TT                 | non-SVR non-SVR                        |
| 28 | N10                   | 1a                  | 6.72                              | M              | 54.6                   | R                           | C                           | TT                    | non-SVR                                |
| 29 | N11                   | 1a                  | 6.42                              | M              | 48.0                   | R                           | C                           | CT                    | non-SVR                                |
| 30 | N12 N13               | 1a 1a               | 7.32 6.09                         | F M            | 48.4 24.3              | R R                         | C C                         | CT TT                 | non-SVR non-SVR                        |
| 31 | N14 N20               | 1a 1a               | 6.31 6.73                         | M F            | 35.0 35.0              | R R                         | C C                         | CT CC                 | non-SVR non-SVR                        |
| 32 | N21                   | 1a                  | 7.15                              | F              | 45.0                   | R                           | C                           | CC                    | non-SVR                                |
| 33 | R16                   | 1b                  | 4.13                              | F              | 46.5                   | R                           | M                           | CC                    | SVR                                    |
| 34 | R17                   | 1b                  | 4.94                              | M              | 31.5                   | R                           | M                           | CC                    | SVR                                    |
| 35 | R18                   | 1b                  | 5.40                              | F              | 58.7                   | R                           | M                           | CT                    | SVR                                    |
| 36 | R19                   | 1b                  | 6.23                              | F              | 38.4                   | R                           | L                           | CT                    | SVR                                    |
| 37 | R20                   | 1b                  | 7.39                              | F              | 47.8                   | R                           | M                           | CT                    | SVR                                    |
| 38 | R26                   | 1b                  | 7.17                              | M              | 46.6                   | R                           | L                           | CT                    | SVR                                    |
| 39 | R27                   | 1b                  | 6.81                              | M              | 56.8                   | R                           | M                           | CT                    | SVR                                    |
| 40 | R29                   | 1b                  | 7.55                              | M              | 57.0                   | Q                           | M                           | CT                    | SVR                                    |
| 41 | N15                   | 1b                  | 6.08                              | F              | 56.5                   | Q                           | M                           | CT                    | non-SVR                                |
| 42 | N16                   | 1b                  | 6.57                              | F              | 58.5                   | Q                           | M                           | TT                    | non-SVR                                |
| 43 | N17                   | 1b                  | 7.37                              | M              | 48.9                   | Q                           | L                           | CT                    | non-SVR                                |
| 44 | N18                   | 1b                  | 6.69                              | M              | 62.8                   | Q                           | L                           | CT                    | non-SVR                                |
| 45 | N19                   | 1b                  | 6.70                              | F              | 54.2                   | Q                           | M                           | CT                    | non-SVR                                |

## pdf7_t1
|    |                                     | SVR n = 29           | non-SVR n = 21      | Univariate p value   |
|---:|:------------------------------------|:---------------------|:--------------------|:---------------------|
|  0 | Age (mean)                          | 45.2                 | 48.8                | 0.09a                |
|  1 | Number of patients < 45 / > 45 yrs  | 11 / 18              | 4 / 17              | 0.21b                |
|  2 | Gender (m/f)                        | 17 / 12              | 13 / 8              | 1.0b                 |
|  3 | Baseline HCV RNA (mean log IU/mL)   | 6.37                 | 6.59                | 0.56a                |
|  4 | Number with < 5.6 / > 5.6 log IU/mL | 8 / 21               | 0 / 21              | 0.01b                |
|  5 | Genotype 1a/1b                      | 21 / 8               | 16 / 5              | 1.0b                 |
|  6 | Fibrosis (F0/F1/F2/F3/F4)c          | 0 / 10 / 13 / 4 / 0  | 2 / 4 / 4 / 7 / 2   | 0.19d                |
|  7 | Core aa 70                          | 28 R / 1 Q           | 15 R / 5 Q & 1 P    | 0.03b                |
|  8 | Core aa 91                          | 21 C / 6 M / 2 L     | 16 C / 3 M / 2 L    | 0.82e                |
|  9 | rs12979860                          | 16 CC / 13 CT / 0 TT | 2 CC / 11 CT / 8 TT | 0.0001e              |

## pdf7_t2
|    | (nan, 'Genotype')   | ('Amino acid 70', 'Q')   | ('Amino acid 70', 'R')   | ('Amino acid 70', 'P')   | ('Amino acid 70', 'H')   | ('Amino acid 91', 'C')   | ('Amino acid 91', 'M')   | ('Amino acid 91', 'L')   |   (nan, 'Total') |
|---:|:--------------------|:-------------------------|:-------------------------|:-------------------------|:-------------------------|:-------------------------|:-------------------------|:-------------------------|-----------------:|
|  0 | 1a                  | 2%                       | 98%                      | -                        | -                        | 100%                     | -                        | -                        |              920 |
|  1 | 1b                  | 60%                      | 35%                      | -                        | 4%                       | 1%                       | 71%                      | 28%                      |             2022 |
|  2 | 2                   | -                        | 100%                     | -                        | -                        | 39%                      | 4%                       | 58%                      |               83 |
|  3 | 3                   | -                        | 93%                      | 6%                       | -                        | 99%                      | -                        | -                        |              204 |
|  4 | 4                   | 5%                       | 95%                      | -                        | -                        | 100%                     | -                        | -                        |               19 |
|  5 | 5                   | 86%                      | 14%                      | -                        | -                        | -                        | -                        | 100%                     |               14 |
|  6 | 6                   | 60%                      | 13%                      | 13%                      | 15%                      | 100%                     | -                        | -                        |               55 |

## pdf8_t0
|    | Sample   | Temperature (K)   |   Time (s) | IWa   |   f H2 (bar) |   f H2O (bar) |   # of points |   Fit 1 Absorbance |   Fit 2 Absorbance |   Fit 3 Absorbance | Mean ε = 6.3 m2/mol   |   1σ | Mean ε = 5.1 m2/mol   |   1σ | Corrected Mean ε = 6.3 m2/mol   | Corrected ε = 5.1 m2/mol   |
|---:|:---------|:------------------|-----------:|:------|-------------:|--------------:|--------------:|-------------------:|-------------------:|-------------------:|:----------------------|-----:|:----------------------|-----:|:--------------------------------|:---------------------------|
|  0 |          |                   |            |       |              |               |               |                    |                    |                    | (ppmw)                |      | (ppmw)                |      | (ppmw)                          | (ppmw)                     |
|  1 | Per-1    | 2173 ± 21         |         30 | 5.97  |     0        |      0        |             3 |              0.036 |              0.037 |              0.038 | 35.4                  |  2   | 43.7                  |  3   | 2.9                             | 3.5                        |
|  2 | Per-2    | 2166 ± 40         |         40 | 3.46  |     0        |      0        |             7 |              0.039 |              0.04  |              0.039 | 37.6                  |  2   | 46.5                  |  3.1 | 5.1                             | 6.3                        |
|  3 | Per-3    | 2134 ± 29         |         32 | 3.42  |     1.28e-05 |      0.00071  |             7 |              0.053 |              0.054 |              0.05  | 50.0                  |  3.2 | 61.8                  |  4.6 | 17.5                            | 21.7                       |
|  4 | Per-4    | 2197 ± 59         |         60 | 3.46  |     9.88e-07 |      5.74e-05 |             7 |              0.041 |              0.04  |              0.039 | 38.2                  |  2.2 | 47.2                  |  3.2 | 5.7                             | 7.1                        |
|  5 | Per-5    | 2239 ± 25         |         36 | 3.46  |     5.17e-08 |      3.02e-06 |             6 |              0.036 |              0.033 |              0.033 | 32.5                  |  2.3 | 40.2                  |  3.2 | 0.0                             | 0.0                        |
|  6 | Per-6    | 2151 ± 23         |         25 | 3.37  |     2.77e-05 |      0.0015   |             8 |              0.053 |              0.055 |              0.057 | 52.6                  |  3.2 | 65.0                  |  4.7 | 20.1                            | 24.8                       |
|  7 | Per-7    | 2139 ± 13         |         27 | 3.23  |     8.41e-05 |      0.0038   |             7 |              0.069 |              0.07  |              0.072 | 67.2                  |  3.8 | 83.1                  |  5.6 | 34.7                            | 42.9                       |
|  8 | Per-8    | 2197 ± 13         |         31 | 2.94  |     0.00024  |      0.0076   |             8 |              0.088 |              0.09  |              0.094 | 86.7                  |  5.2 | 107.1                 |  7.6 | 54.2                            | 66.9                       |
|  9 | Per-9    | 2175 ± 15         |         30 | 2.03  |     0.0016   |      0.018    |             9 |              0.115 |              0.12  |              0.118 | 112.5                 |  6.3 | 139.0                 |  9.4 | 80.0                            | 98.8                       |
| 10 | Per-10   | 2173 ± 21         |         30 | 0.64  |     0.012    |      0.027    |             9 |              0.141 |              0.142 |              0.143 | 135.8                 |  7.1 | 167.7                 | 10.9 | 103.3                           | 127.5                      |
| 11 | Per-11   | 2169 ± 16         |         28 | −0.77 |     0.041    |      0.018    |            10 |              0.145 |              0.142 |              0.144 | 137.4                 |  7.3 | 169.7                 | 11.1 | 104.8                           | 129.5                      |
| 12 | Per-12   | 2112 ± 17         |         33 | −1.90 |     0.064    |      0.0078   |            10 |              0.133 |              0.132 |              0.138 | 128.4                 |  7.3 | 158.6                 | 10.8 | 95.9                            | 118.5                      |
| 13 | Per-TS1  | 2124 ± 13         |         10 | 3.23  |     8.41e-05 |      0.0038   |             8 |              0.066 |              0.066 |              0.068 | 63.7                  |  3.5 | 78.7                  |  5.2 | 31.2                            | 38.6                       |

## pdf8_t1
|    | This work 6.3 m2/mol)                   | Peridotite                  | (K) 2173    | (bar−0.5) 2.91 10−3       | (bar) 5.7 10−5 0.027   |   14 |
|---:|:----------------------------------------|:----------------------------|:------------|:--------------------------|:-----------------------|-----:|
|  0 | (ε3550 = This work (ε3550 = 5.1 m2/mol) | Peridotite                  | 2173        | × 3.59 × 10−3             | × – 5.7 × 10−5 – 0.027 |   14 |
|  1 | Newcombe et al. (2017)                  | Anorthite-Diopside eutectic | 1623        | 4.22 × 10−3               | 9.8 × 10−3 – 0.32      |   14 |
|  2 | Newcombe et al. (2017)                  | Lunar Green Glass           | 1623        | 4.04 × 10−3               | 9.8 × 10−3 – 0.32      |   11 |
|  3 | Dixon et al. (1995)                     | Mid-Ocean Ridge Basalt      | 1473        | 5.36 × 10−3               | 17 – 709               |   14 |
|  4 | Hamilton and Oxtoby (1986)              | NaAlSi3O8                   | 1123 – 1573 | 7.59 × 10−3 – 9.91 × 10−3 | 1685 – 2160            |   13 |

## pdf9_t4
|    | Electrode nanomodification   | Modification method   | ET   | Surface modification                | Surface functionality   | Measurement method   | pH and substrate concentration            | Current density (μAcm−2 )   | Reference                |
|---:|:-----------------------------|:----------------------|:-----|:------------------------------------|:------------------------|:---------------------|:------------------------------------------|:----------------------------|:-------------------------|
|  0 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | DET  | Co-immobilisation with CNTs         | Not studied             | LSV; 1 mV s−1        | 5.0, 100 mM lactose                       | 45                          | [93]                     |
|  1 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | DET  | Co-immobilisation with CNTs         | Not studied             | LSV; 1 mV s−1        | 5.5, 100 mM lactose                       | 30                          | [93]                     |
|  2 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | DET  | Co-immobilisation with CNTs         | Not studied             | LSV; 1 mV s−1        | 6.0, 100 mM lactose                       | 13                          | [93]                     |
|  3 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | MET  | Co-immobilisation with CNTs+ PEGDGE | Not studied             | LSV; 0.2 mV s−1      | 3.5, 100 mM lactose                       | 300                         | [93]                     |
|  4 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | MET  | Co-immobilisation with CNTs+ PEGDGE | Not studied             | LSV; 0.2 mV s−1      | 4.0, 100 mM lactose                       | 500                         | [93]                     |
|  5 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | MET  | Co-immobilisation with CNTs+ PEGDGE | Not studied             | LSV; 0.2 mV s−1      | 4.5, 100 mM lactose                       | 650                         | [93]                     |
|  6 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | MET  | Co-immobilisation with CNTs+ PEGDGE | Not studied             | LSV; 0.2 mV s−1      | 5.0, 100 mM lactose                       | 700                         | [93]                     |
|  7 | GE+SWCNT+CDH; PsCDH          | Drop-casting          | MET  | Co-immobilisation with CNTs+ PEGDGE | Not studied             | LSV; 0.2 mV s−1      | 6.0, 100 mM lactose                       | 700                         | [93]                     |
|  8 | Au+AuNP; CtCDH               | Drop-casting          | DET  | ATP/MBA+GA                          | OH                      | LSV; 2 mV s−1        | 7.4, 5 mM lactose; 100 mM glucose         | 40; 26                      | [49]                     |
|  9 | Au+AuNP; CtCDH               | Drop-casting          | DET  | ATP/MBA+GA                          | OH                      | LSV 2 mV s−1         | 7.4, 5 mM glucose                         | 7.5                         | [51]                     |
| 10 | SPCE+SWCNT; CtCDH            | Drop-casting          | DET  | PEDGDE                              | Not studied             | FIA                  | 7.4, 300 mM glucose                       | 18.41                       | [57]                     |
| 11 | SPCE+MWCNT; CtCDH            | Drop-casting          | DET  | PEDGDE                              | Not studied             | FIA                  | 7.4, 300 mM glucose                       | 15.58                       | [57]                     |
| 12 | GE+SWCNT; MtCDH              | Drop-casting          | DET  | PEGDGE                              | Not studied             | FIA                  | 5.3, 10 mM lactose                        | 6.16                        | [89]                     |
| 13 | GE+SWCNT; MtCDH              | Drop-casting          | DET  | PEGDGE                              | Not studied             | LSV; 1 mV s−1        | 4.5, 100 mM lactose                       | 5                           | [89]                     |
| 14 | GE+SWCNT; MtCDH              | Drop-casting          | MET  | Os-polymer+PEGDGE                   | Not studied             | LSV; 1 mV s−1        | 3.5, 100 mM lactose                       | 68.4                        | [89]                     |
| 15 | GE+SWCNT; MtCDH              | Drop-casting          | MET  | Os-polymer+PEGDGE                   | Not studied             | LSV; 1 mV s−1        | 4.5, 100 mM lactose                       | 102.6                       | [89]                     |
| 16 | GE+SWCNT; MtCDH              | Drop-casting          | MET  | Os-polymer+PEGDGE                   | Not studied             | LSV; 1 mV s−1        | 6.0, 100 mM lactose                       | 205                         | [89]                     |
| 17 | GE+SWCNT                     | Drop-casting          | MET  | Os-polymer+PEGDGE                   | Not studied             | LSV; 1 mV s−1        | 7.0, 100 mM lactose                       | 465                         | [89]                     |
| 18 | GE+SWCNT; MtCDH              | Drop-casting          | MET  | Os-polymer+PEGDGE                   | Not studied             | CV; 1 mV s−1         | 8.0, 100 mM lactose                       | 800                         | [89]                     |
| 19 | GE+SWCNT; MtCDH              | Drop-casting          | MET  | Os-polymer+PEGDGE                   | Not studied             | CV; 1 mV s−1         | 7.4, 100 mM lactose; 50 mM                | 450; 100                    | [89]                     |
| 20 | GC+SWCNTs; CtCDH             | Drop-casting          | DET  | p-Aminobenzoic acid                 | COOH                    | CV; 1 mV s−1         | glucose 7.4, 10 mM lactose; 50 mM glucose | 30; 15                      | (Ortiz et al. submitted) |
| 21 | GC+SWCNTs; CtCDH             | Drop-casting          | DET  | Aniline                             | None                    | CV; 1 mV s−1         | 7.4, 10 mM lactose; 50 mM glucose         | 21; 9                       | (Ortiz et al. submitted) |
| 22 | GC+SWCNTs; CtCDH             | Drop-casting          | DET  | p-Phenylenediamine                  | NH2                     | CV; 1 mV s−1         | 7.4, 10 mM lactose; 50 mM glucose         | 25; 13                      | (Ortiz et al. submitted) |
| 23 | GC+SWCNTs; CtCDH             | Drop-casting          | DET  | p-Phenylenediamine+GA               | NH2                     | CV; 1 mV s−1         | 7.4, 10 mM lactose; 50 mM glucose         | 43; 21                      | (Ortiz et al. submitted) |

## pubt_p4
|    | Dataset             | Input Modality   | # Tables   | Cell Topology   | Cell Content   | Cell Location   | Row & Column Location   | Canonical Structure   |
|---:|:--------------------|:-----------------|:-----------|:----------------|:---------------|:----------------|:------------------------|:----------------------|
|  0 | TableBank [9]       | Image            | 145K       | X               |                |                 |                         |                       |
|  1 | SciTSR [3]          | PDF∗             | 15K        | X               | X              |                 |                         |                       |
|  2 | PubTabNet [22, 23]  | Image            | 510K‡      | X               | X              | X†              |                         |                       |
|  3 | FinTabNet [22]      | PDF∗             | 113K       | X               | X              | X†              |                         |                       |
|  4 | PubTables-1M (ours) | PDF∗             | 948K       | X               | X              | X               | X                       | X                     |

## pubt_p6
|    | (nan, 'Dataset')           | (nan, 'Total Tables \\nInvestigated†')   | (nan, 'Total Tables \\nwith a PRH∗')   | ('Tables with an oversegmented PRH', 'Total')   | ('Tables with an oversegmented PRH', '% (of total with a PRH)')   | ('Tables with an oversegmented PRH', '% (of total investigated)')   |
|---:|:---------------------------|:-----------------------------------------|:---------------------------------------|:------------------------------------------------|:------------------------------------------------------------------|:--------------------------------------------------------------------|
|  0 | SciTSR PubTabNet FinTabNet | 10,431 422,491 70,028                    | 342 100,159 25,637                     | 54 58,747 25,348                                | 15.79% 58.65% 98.87%                                              | 0.52% 13.90% 36.20%                                                 |
|  1 | PubTables-1M (ours)        | 761,262                                  | 153,705                                | 0                                               | 0%                                                                | 0%                                                                  |

## pubt_p7
|    | Task     | Model        |    AP |   AP50 |   AP75 |    AR |
|---:|:---------|:-------------|------:|-------:|-------:|------:|
|  0 | TD       | Faster R-CNN | 0.825 |  0.985 |  0.927 | 0.866 |
|  1 | TD       | DETR         | 0.966 |  0.995 |  0.988 | 0.981 |
|  2 | TSR + FA | Faster R-CNN | 0.722 |  0.815 |  0.785 | 0.762 |
|  3 | TSR + FA | DETR         | 0.912 |  0.971 |  0.948 | 0.942 |

## pubt_p8
|    | Test Data     | Model        | Table Category   |   AccCont |   GriTSTop |   GriTSCont |   GriTSLoc |   AdjCont |
|---:|:--------------|:-------------|:-----------------|----------:|-----------:|------------:|-----------:|----------:|
|  0 | Non-Canonical | DETR-NC      | Simple           |    0.8678 |     0.9872 |      0.9859 |     0.9821 |    0.9801 |
|  1 | Non-Canonical | DETR-NC      | Complex          |    0.536  |     0.96   |      0.9618 |     0.9444 |    0.9505 |
|  2 | Non-Canonical | DETR-NC      | All              |    0.7336 |     0.9762 |      0.9761 |     0.9668 |    0.9681 |
|  3 | Canonical     | DETR-NC      | Simple           |    0.9349 |     0.9933 |      0.992  |     0.99   |    0.9865 |
|  4 | Canonical     | DETR-NC      | Complex          |    0.2712 |     0.9257 |      0.929  |     0.9044 |    0.9162 |
|  5 | Canonical     | DETR-NC      | All              |    0.5851 |     0.9576 |      0.9588 |     0.9449 |    0.9494 |
|  6 | Canonical     | Faster R-CNN | Simple           |    0.0867 |     0.8682 |      0.8571 |     0.6869 |    0.8024 |
|  7 | Canonical     | Faster R-CNN | Complex          |    0.1193 |     0.8556 |      0.8507 |     0.7518 |    0.7734 |
|  8 | Canonical     | Faster R-CNN | All              |    0.1039 |     0.8616 |      0.8538 |     0.7211 |    0.7871 |
|  9 | Canonical     | DETR         | Simple           |    0.9468 |     0.9949 |      0.9938 |     0.9922 |    0.9893 |
| 10 | Canonical     | DETR         | Complex          |    0.6944 |     0.9752 |      0.9763 |     0.9654 |    0.9667 |
| 11 | Canonical     | DETR         | All              |    0.8138 |     0.9845 |      0.9846 |     0.9781 |    0.9774 |

## attn0
|    |                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                     |                                                                                                                |                                                                                                                                                                                                                                             |                                                                                                                                                                    |
|---:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  0 | Ashish Vaswani∗ Google Brain avaswani@google.com                                                                                                                                                                                                                                                                  | Noam Shazeer∗ Google Brain noam@google.com                                                                                                                                                                                                                                                                                          | Niki Google                                                                                                    | Parmar∗ Research nikip@google.com                                                                                                                                                                                                           | Jakob Uszkoreit∗ Google Research usz@google.com                                                                                                                    |
|  1 | Llion Jones∗                                                                                                                                                                                                                                                                                                      | Aidan N. Gomez∗                                                                                                                                                                                                                                                                                                                     | †                                                                                                              | Łukasz                                                                                                                                                                                                                                      | Kaiser∗                                                                                                                                                            |
|  2 | Google Research                                                                                                                                                                                                                                                                                                   | University of Toronto aidan@cs.toronto.edu                                                                                                                                                                                                                                                                                          |                                                                                                                | Google                                                                                                                                                                                                                                      | Brain                                                                                                                                                              |
|  3 | llion@google.com                                                                                                                                                                                                                                                                                                  | University of Toronto aidan@cs.toronto.edu                                                                                                                                                                                                                                                                                          | ‡                                                                                                              |                                                                                                                                                                                                                                             | lukaszkaiser@google.com                                                                                                                                            |
|  4 |                                                                                                                                                                                                                                                                                                                   | Illia Polosukhin∗ illia.polosukhin@gmail.com                                                                                                                                                                                                                                                                                        |                                                                                                                |                                                                                                                                                                                                                                             |                                                                                                                                                                    |
|  5 |                                                                                                                                                                                                                                                                                                                   | Abstract                                                                                                                                                                                                                                                                                                                            |                                                                                                                |                                                                                                                                                                                                                                             |                                                                                                                                                                    |
|  6 | The dominant sequence convolutional neural performing models mechanism. We based solely on attention entirely. Experiments be superior in quality less time to train. translation ensembles, by over 2 our model establishes training for 3.5 days best models from the other tasks by applying large and limited | transduction models networks that include also connect the encoder propose a new simple mechanisms, dispensing on two machine while being more Our model achieves 28.4 English￾to-German task, improving over BLEU. On the WMT a new single-model on eight GPUs, a small literature. We show that it successfully to training data. | are an encoder and network with translation parallelizable BLEU the 2014 state-of-the-art fraction the English | based on complex and a decoder. decoder through architecture, the recurrence and tasks show these and requiring on the WMT existing best results, English-to-French BLEU score of the training Transformer generalizes constituency parsing | recurrent or The best an attention Transformer, convolutions models to significantly 2014 including translation task, of 41.8 after costs of the well to both with |

## attn1
|    | Layer Type                  | Complexity per Layer   | Sequential Operations   | Maximum Path Length   |
|---:|:----------------------------|:-----------------------|:------------------------|:----------------------|
|  0 | Self-Attention              | O(n 2 · d)             | O(1)                    | O(1)                  |
|  1 | Recurrent                   | O(n · d 2 )            | O(n)                    | O(n)                  |
|  2 | Convolutional               | O(k · n · d 2 )        | O(1)                    | O(logk(n))            |
|  3 | Self-Attention (restricted) | O(r · n · d)           | O(1)                    | O(n/r)                |

## attn2
|    | (nan, 'Model')                                                               | ('BLEU', 'EN-DE')   | ('BLEU', 'EN-FR')   | ('Training Cost (FLOPs)', 'EN-DE')   | ('Training Cost (FLOPs)', 'EN-FR')   |
|---:|:-----------------------------------------------------------------------------|:--------------------|:--------------------|:-------------------------------------|:-------------------------------------|
|  0 | ByteNet [18]                                                                 | 23.75               |                     |                                      |                                      |
|  1 | Deep-Att + PosUnk [39]                                                       |                     | 39.2                |                                      | 1.0 · 1020                           |
|  2 | GNMT + RL [38]                                                               | 24.6                | 39.92               | 2.3 · 1019                           | 1.4 · 1020                           |
|  3 | ConvS2S [9]                                                                  | 25.16               | 40.46               | 9.6 · 1018                           | 1.5 · 1020                           |
|  4 | MoE [32]                                                                     | 26.03               | 40.56               | 2.0 · 1019                           | 1.2 · 1020                           |
|  5 | Deep-Att + PosUnk Ensemble [39] GNMT + RL Ensemble [38] ConvS2S Ensemble [9] | 26.30 26.36         | 40.4 41.16 41.29    | 1.8 · 1020 7.7 · 1019                | 8.0 · 1020 1.1 · 1021 1.2 · 1021     |
|  6 | Transformer (base model) Transformer (big)                                   | 27.3 28.4           | 38.1 41.8           | 3.3 · 2.3 ·                          | 1018 1019                            |

## attn3
|    |      |   N |   dmodel | dff        | h         | dk    | dv         | Pdrop     | ϵls     | train steps   | PPL (dev)           | BLEU (dev)          | params ×106   |
|---:|:-----|----:|---------:|:-----------|:----------|:------|:-----------|:----------|:--------|:--------------|:--------------------|:--------------------|:--------------|
|  0 | base |   6 |      512 | 2048       | 8         | 64    | 64         | 0.1       | 0.1     | 100K          | 4.92                | 25.8                | 65            |
|  1 | (A)  |     |          |            | 1         | 512   | 512        |           |         |               | 5.29                | 24.9                |               |
|  2 | (A)  |     |          |            | 4         | 128   | 128        |           |         |               | 5.00                | 25.5                |               |
|  3 | (A)  |     |          |            | 16        | 32    | 32         |           |         |               | 4.91                | 25.8                |               |
|  4 | (A)  |     |          |            | 32        | 16    | 16         |           |         |               | 5.01                | 25.4                |               |
|  5 | (B)  |     |          |            |           | 16 32 |            |           |         |               | 5.16 5.01           | 25.1 25.4           | 58 60         |
|  6 |      |   2 |          |            |           |       |            |           |         |               | 6.11                | 23.7                | 36            |
|  7 |      |   4 |          |            |           |       |            |           |         |               | 5.19                | 25.3                | 50            |
|  8 |      |   8 |          |            |           |       |            |           |         |               | 4.88                | 25.5                | 80            |
|  9 | (C)  |     |      256 |            |           | 32    | 32         |           |         |               | 5.75                | 24.5                | 28            |
| 10 |      |     |     1024 |            |           | 128   | 128        |           |         |               | 4.66                | 26.0                | 168           |
| 11 |      |     |          | 1024       |           |       |            |           |         |               | 5.12                | 25.4                | 53            |
| 12 |      |     |          | 4096       |           |       |            |           |         |               | 4.75                | 26.2                | 90            |
| 13 | (D)  |     |          |            |           |       |            | 0.0 0.2   | 0.0 0.2 |               | 5.77 4.95 4.67 5.47 | 24.6 25.5 25.3 25.7 |               |
| 14 | (E)  |     |          | positional | embedding |       | instead of | sinusoids |         |               | 4.92                | 25.7                |               |
| 15 | big  |   6 |     1024 | 4096       | 16        |       |            | 0.3       |         | 300K          | 4.33                | 26.4                | 213           |

## attn4
|    | Parser                                                                                                      | Training                                                                                            | WSJ 23 F1           |
|---:|:------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------|:--------------------|
|  0 | Vinyals & Kaiser el al. (2014) [37] Petrov et al. (2006) [29] Zhu et al. (2013) [40] Dyer et al. (2016) [8] | WSJ only, discriminative WSJ only, discriminative WSJ only, discriminative WSJ only, discriminative | 88.3 90.4 90.4 91.7 |
|  1 | Transformer (4 layers) Zhu et al. (2013) [40]                                                               | WSJ only, discriminative semi-supervised                                                            | 91.3 91.3           |
|  2 | Huang & Harper (2009) [14]                                                                                  | semi-supervised                                                                                     | 91.3                |
|  3 | McClosky et al. (2006) [26] Vinyals & Kaiser el al. (2014) [37]                                             | semi-supervised semi-supervised                                                                     | 92.1 92.1           |
|  4 | Transformer (4 layers) Luong et al. (2015) [23] Dyer et al. (2016) [8]                                      | semi-supervised multi-task generative                                                               | 92.7 93.0 93.3      |

