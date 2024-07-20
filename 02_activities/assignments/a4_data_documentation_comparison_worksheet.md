# Assignment: Data Documentation Comparison Worksheet

For each of the three sources listed, find any and all available documentation for the data gathered and identify and describe the survey features indicated in the table below. Some may not be available for all sources.

Sources: - Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33), conducted by Statistics Canada - Canadian Election Study Online Survey, 2019, conducted by Laura Stephenson, Allison Harell, Daniel Rubenson and Peter Loewen - Trophic niche flexibility in Glossophaga soricina: how nectar seeker sneaks an insect snack, conducted by Elizabeth Clare et al.

Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33) 
 Sample type :  cross-sectional design.
 Sample size :  Approximately 50,000 units 
 Target population : The target population for the GSS Giving, volunteering and participating includes all persons 15 years of age and older living 
                     in the ten provinces of Canada. It excludes full-time (residing for more than six months) residents of institutions.
 Sampling frame : Combines landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling frame.
 Survey mode(s) : Electronic Questionnaire: Respondents can complete the survey online using an electronic questionnaire.
                  Computer-Assisted Telephone Interviewing (CATI): Respondents can complete the survey through telephone interviews conducted by trained interviewers using CATI.
 Timeline : Reference Period: The past 12 months preceding the interview date.
            Collection Period: Every 5 years, from September to December.
            For 2018: Data collection occurred from September 4, 2018, to December 28, 2018.
            Data Release: January 26, 2021.
            This structured timeline allows for periodic collection and release of data to monitor and analyze social trends and behaviors over time.
 Response rate : 41.9%.
 Weights :  Basic Weighting Factor: WGHT_PER: This is the primary weighting factor used for analysis at the person level, allowing estimates to reflect the 
            number of persons (non-institutionalized and aged 15 or over) having specific characteristics.
            Adjustments: The weights are adjusted to account for non-response and ensure that the sample accurately represents the target population.
            Adjustments are also made to match the weighted income distribution of GVP to the 2017 CIS distribution by province.
            Bootstrap Weights: Created for design-based variance estimation, these weights help to estimate the sampling variability of survey estimates using the bootstrap method. This method allows for precise estimation of the variability and reliability of the survey results.
Data processing : 1. Error Detection,
                     The processing of survey data used the SSPE set of generalized processing steps and utilities to ensure high-quality outputs.
                     A structured environment monitored data processing to ensure best practices and harmonized business processes.
                     Edits were performed both automatically and manually at various stages, including macro and micro-level checks.
                     Family edits ensured the integrity of matrix data.
                     Consistency edits checked data such as respondent age against birth date.
                     Flow edits ensured respondents followed the correct survey path.
                     CATI (Computer Assisted Telephone Interviewing) system edits checked for valid ranges and flow, resolving errors immediately with respondents when possible.
                     
                  2. Imputation, 
                     Imputation was used to handle missing data, with donor records selected through a scoring function based on similar characteristics.
                     If multiple donor records had the highest score, one was randomly selected.
                     Donor imputation ensured that imputed values were consistent with other non-imputed items on the recipient record.
                     Mean imputation among a pool of donors was used where donor imputation could not be applied.
                     Personal income questions were not asked; income data were obtained by linking to tax records for those who did not object to linkage.
                     Personal income data were available for 81.9% of respondents.
                     Family income data were available for 81.7% of households, with missing information imputed.
                  3. Estimation, 
                     Estimation accounted for the probability sample design, with each person in the sample representing several others in the population.
                     Weights were adjusted to account for 'rejective sampling' where non-volunteers were sub-sampled.
                     Final weights were adjusted so that the weighted income distribution matched the 2017 CIS distribution by province.
                  4. Quality Evaluation,
                     Validation and scrutiny by statisticians included:
                     Analysis of changes over time.
                     Verification of estimates through cross-tabulations.
                     Confrontation with other similar data sources.
                  5. Disclosure Control, 
                     Confidentiality rules and the Statistics Canada Generalized Disclosure Control System (G-Confid) were used to prevent direct or residual disclosure of identifiable data.
                     Data were suppressed where necessary to maintain confidentiality.
                  6. Non-sampling Error Handling, 
                     Coverage errors were minimized using a comprehensive frame combining multiple data sources.
                     Non-response was adjusted through weighting to account for household and individual-level non-response.
                     Non-response bias was reduced by using administrative data to model and adjust for non-responding households' basic characteristics.
                  7. Response Rate 
                     The overall response rate for the 2018 GSS was 41.9%
 Cleaning, imputation, etc.:
            Error Detection
            SSPE (Social Statistics Processing Environment): Used to monitor the processing of data, ensuring best practices and harmonized business processes.
            Edits: Performed at both macro and micro levels to check family relationships, consistency, and flow of data.
            CATI Edits: The CATI system performs real-time edits during the interview to ensure valid ranges and correct paths through the questionnaire.
            Head Office Edits: Additional checks and resolution of errors that interviewers could not address during data collection.
            Cleaning
            Consistency Checks: Ensuring data consistency, such as checking respondent age against birth date.
            Flow Edits: Ensuring respondents follow the correct paths in the questionnaire and fixing any off-path responses.
            Imputation
            Donor Imputation: Missing values are filled using donor records that are similar to the recipient records based on certain characteristics.
            A score function is used to find the nearest donor, with the highest score donor filling the missing information.
            Mean Imputation: Used when donor imputation is not feasible, involving averaging values from a pool of donors.
            Steps: Imputation is done in nine steps, starting with personal and family income, followed by volunteering variables, and finally, donation-related variables.
            Income Data: Personal income was primarily obtained from tax data (T1FF) for 81.9% of respondents. Family income data were also primarily obtained from tax data for 81.7% of households, with imputation used for missing cases.
            Quality Evaluation : Validation Measures: Include analysis of changes over time, verification of estimates through cross-tabulations, and confrontation with similar data sources.
 
 Sources of error : Sampling Error : Definition: Arises because the survey collects data from a sample rather than the entire population.
                    Variability: Estimates based on the sample may differ from those that would be obtained from a complete census.
                    Estimation: The bootstrap method is used to estimate sampling variability and provide confidence intervals for survey estimates.
                    Non-Sampling Error, Coverage Error: Undercoverage: Households without telephones or those not covered by the sampling frame are excluded.
                    Overcoverage: Inclusion of ineligible units or duplications in the sampling frame.
                    Bias: Differences between the surveyed population and the target population can introduce bias, although the biases are expected to be small due to the small proportion of excluded population.
                    Non-Response Error: Household Non-Response: Some households do not participate in the survey.
                    Individual Non-Response: Within participating households, some individuals may not respond.
                    Adjustment: Weights are adjusted to account for non-response, and administrative data are used to model and adjust for non-response bias.
                    Response Error: Definition: Errors occur when respondents provide inaccurate answers due to misunderstanding questions, recall issues, or social desirability bias.
                    Minimization: Use of well-tested questionnaires, trained interviewers, and strict quality controls help minimize response errors.
                    Processing Error:
                     Data Entry Errors: Mistakes during data entry or coding.
                     Error Detection: Automated and manual edits during data processing help identify and correct inconsistencies and errors.
                     Imputation Errors: Errors introduced during the imputation process to handle missing data. 
                    
 Limitations, known biases: Limitations
                            1. Sampling Frame Limitations:
                               Coverage Issues: Excludes households without telephones, which can lead to undercoverage. This limitation might affect the representativeness of the sample, especially in populations with lower telephone access.
                               Overcoverage: The sampling frame may include duplicates or incorrect entries, which can lead to inaccuracies.
                            2. Non-Response:
                               Response Rate: An overall response rate of 41.9% indicates that a significant portion of the sampled population did not participate, potentially leading to non-response bias.
                               Non-Response Adjustment: While weights and administrative data are used to adjust for non-response, not all biases may be fully corrected.
                            3. Data Collection Modes:
                               Electronic and Telephone Surveys: Different modes may result in variations in data quality and response rates. For instance, electronic surveys might not reach those less familiar with technology, and telephone interviews may have limitations related to respondent privacy or interviewer effects.
                            4. Imputation:
                               Accuracy of Imputation: While imputation helps fill in missing data, it can introduce errors if the imputed values do not accurately reflect the true values for all respondents.
                            5. Recall Bias:
                               Self-Reporting: Respondents’ recollections of past behaviors or attitudes may be inaccurate, leading to potential biases in reporting.
                            Known Biases
                            1. Non-Response Bias:
                               Demographic Differences: Certain groups may be less likely to respond, leading to biases in the data. For example, younger individuals or those with lower income may be underrepresented.
                            2. Coverage Bias:
                               Telephone Bias: Excluding households without telephones can result in bias, as this group might have different social behaviors compared to those with telephones.
                            3. Social Desirability Bias:
                               Reporting Bias: Respondents may provide answers they believe are socially acceptable or desirable rather than their true behaviors or attitudes, particularly in sensitive areas like volunteering and donating.
                            4. Recall Bias:
                               Past Behavior: Difficulty in accurately recalling past behaviors or attitudes can lead to inaccuracies in responses, especially for questions about activities over the past 12 months.
                            5. Geographic Bias:
                               Regional Differences: The stratified sampling approach aims to address regional differences, but variations in response rates and coverage across different provinces and CMAs might still introduce regional biases.
 Citation : General Social Survey - Giving, Volunteering and Participating (GSS GVP) from Statistics Canada                                                      
 Links to any documentation or additional sources used : https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234




Canadian Election Study Online Survey, 2019, conducted by Laura Stephenson, Allison Harell, Daniel Rubenson and Peter Loewen

Sample type : Non-Probability Online Survey
Sample size : Pre-election survey: 37,822, Post-election survey: 10,337
Target population : Canadian citizens and permanent residents, aged 18 or older
Sampling frame : Non-Probability Online Survey:
                 Sampling Frame: This frame likely consisted of an online panel or a network of respondents recruited through various digital channels.
                 Participants might have been recruited via email invitations, social media, or through partnerships with online platforms.
                 As a non-probability sample, it wasn’t drawn from a random or comprehensive list of the Canadian population but aimed to include a broad representation of demographics.
Survey mode(s) : Online survey , Conducted over the internet.
Timeline : 1.Pre-Election Preparation:
             Survey Design and Development: Before the election, the team designed the survey instruments and developed the sampling and data collection strategies.
          2. Campaign Period Survey (CPS):
             Fielding Period: Conducted during the Canadian federal election campaign.
             Sample Size: 37,822 respondents for the online survey and 4,021 for the telephone survey.
          3. Post-Election Survey (PES): 
             Fielding Period: Conducted shortly after the federal election to capture post-election opinions and behaviors.
             Sample Size: 10,337 respondents for the online survey and 2,889 for the telephone survey.
          4. Data Collection and Processing:
             Data Collection: For both CPS and PES, the surveys were administered, and data were collected over the specified periods.
             Data Processing: Included data cleaning, coding, and initial analysis.
          5. Weighting and Analysis:
             Weighting: Adjustments were made to ensure the data were representative of the Canadian population.
             Analysis: The collected data were analyzed to address various research questions and objectives.
          6. Publication and Dissemination: 
             Reports and Papers: Results and findings were published in academic journals and made available through data repositories.
             Data Availability: Data were made accessible through platforms like Harvard Dataverse.         

Response rate : not mentioned in the study
Weights  : Weighting Method: Iterative Raking:
           Weight Variables : cps19_weight_general_all: Description: Weights for all respondents from the campaign period survey (CPS).
                              cps19_weight_general_restricted: Description: Weights for high-quality respondents from the CPS only.
                              pes19_weight_general_all: Description: Weights for all respondents from the post-election survey (PES).
                              pes19_weight_general_restricted: Description: Weights for high-quality respondents from the PES only.

Data processing : 1. Data Import, 2. Data Cleaning, 3. Weighting, 4. Exploratory Data Analysis (EDA), 5. Variable Transformation, 6. Subsetting Data, 7. Handling 
                  Specific Data Quality Issues, 8. Save Processed Data, 9. Analysis
Cleaning, imputation, etc. : 1. Data Cleaning :
                                Error Checking: Identifying and correcting errors in the data, such as inconsistencies or 
                                                out-of-range values.
                                                Missing Data: Addressing missing responses or incomplete records. This might involve checking for patterns of missing data and ensuring that missing values do not bias the results.
                                                Data Validation: Verifying that the data entries are valid and within expected ranges or categories. For example, checking that age values fall within reasonable ranges.
                              2. Data Imputation : Handling Missing Values: Imputation methods were likely used to fill in missing values. This 
                                                   might include techniques such as:
                                                   Mean Imputation: Replacing missing values with the mean of the available values.
                                                   Multiple Imputation: Using statistical models to estimate missing values based on other available data.
                                                   Hot-Deck Imputation: Replacing missing values with responses from similar respondents.
Sources of error : 1. Sampling Error
                      Sampling Frame: Even with a well-defined sampling frame, the sample size and method can still introduce variability. If the sample size is not sufficient or if certain groups are not adequately represented, it can affect the precision of estimates.
                      Sample Selection: Although efforts were made to stratify and balance the sample, any imperfections in achieving the target sample size or demographic quotas can introduce sampling error.
                    2. Non-Sampling Error
                       Measurement Error:
                       Question Wording: Ambiguities or leading questions could lead to inaccurate or biased responses.
                       Response Bias: Social desirability or self-reporting biases can affect how respondents answer questions.
                       Data Processing Errors:
                       Data Entry and Coding: Errors can occur during data entry or coding, impacting the accuracy of the dataset.
                       Data Cleaning: Inadequate handling of missing data or outliers can introduce inaccuracies.
                       Non-Response Bias:
                       Incomplete Data: Differences between those who respond and those who do not can lead to biases. For instance, certain demographic groups may be underrepresented among non-respondents.
                       Response Rates: Variability in response rates across different groups or regions can affect the representativeness of the sample.
                      Limitations, known biases
                    3. Coverage Error
                       Sampling Frame Limitations:
                       Online Panel Limitations: The online nature of the survey may exclude individuals without internet access, potentially leading to coverage error.
                      Territorial Exclusion: Excluding respondents from Canadian territories due to sparse data collection could lead to a lack of representativeness for those regions.
                      Geographic Quotas: While the sample was stratified by region, any imbalance in achieving the target regional quotas could affect regional representation.
                    4. Processing Error
                       Weighting Errors:
                       Weight Calculation: Errors in the iterative raking process or improper application of weights can lead to biases in the adjusted data.
                       Imputation Errors: Errors introduced when handling missing values or incomplete responses.
                    5. Respondent Error
                       Misunderstanding Questions: Respondents may misinterpret questions or provide inaccurate responses due to lack of clarity.
                       Recall Bias: Difficulty in accurately recalling past events or behaviors can affect the validity of responses.
                    6. Operational Errors
                       Survey Mode Effects:
                       Online vs. Telephone: Differences in how responses are obtained via online surveys compared to telephone surveys can introduce variations.
                       Fieldwork Issues:
                       Interviewer Effects: Variability in how interviews are conducted or potential interviewer bias can affect data collection.
Citation: Canadian Election Study 2019 Online Survey Codebook
Links to any documentation or additional sources use : https://dimension.usherbrooke.ca/documents/CES2019Codebook.pdf





Trophic niche flexibility in Glossophaga soricina: how nectar seeker sneaks an insect snack, conducted by Elizabeth Clare et al.

Sample type : Dietary Samples, Acoustic Data, Behavioral Observations, Modeling Data
Sample size : The sample sizes reported in the study are:
              1. Dietary Analysis: Bats Captured: 112 G. soricina (73 females, 39 males). Fecal Samples: 38 samples collected from these bats.
              2. Behavioral Observations:Attacks on Mealworms: 23 attacks had synchronized video and call recordings. Specific Attacks Analyzed: 16 attacks 
                 classified as ‘insect-like’, and 7 as ‘flower-like’. Consumption Observations: 5 instances of mealworm consumption were observed visually, and 2 were recorded on video.
              3. Acoustic Measurements: Echolocation Call Measurements: Data collected from 7 individual bats.
Target population : Bats, Insects, Moths for Acoustic Modeling
Sampling frame : For Bats: Geographic Range: The study is likely focused on G. soricina populations within its geographic range from southern Mexico to northern
                           South America. This range includes various habitats where the species is known to be abundant.
                           Captive Colony: For behavioral and echolocation experiments, a captive colony of G. soricina was used. This captive colony represents a controlled subset of the broader wild population.
                 For Insects: Insect Prey: The sampling frame for insect analysis includes the insects consumed by G. soricina, specifically beetles, flies, and
                              noctuid moths. The insects sampled from fecal material and dietary analysis represent those that are available in the bat's natural foraging areas.
                 For Acoustic Measurements: Noctuid Moths: For modeling the detection distances, the sampling frame consists of noctuid moths that are commonly 
                                             preyed upon by G. soricina. The moths used for acoustic modeling are selected to match the types of prey observed in the bat’s diet.
                 For Fecal Samples: Fecal Material: The sampling frame for fecal samples includes the material collected from G. soricina in its natural habitat, 
                                    providing a snapshot of its diet.
Survey mode(s) : 1. Field Surveys:
                    Bat Capture: Fieldwork involved capturing G. soricina bats from their natural habitat. This likely included using mist nets or other trapping methods to obtain a sample of the population.
                    Fecal Sample Collection: During or after the capture of bats, fecal samples were collected to analyze the diet of G. soricina.
                 2. Captive Observations:
                    Behavioral Experiments: A captive colony of G. soricina was used to observe and record echolocation calls and feeding behavior. This included video recordings and synchronized acoustic measurements during feeding trials.
                    Consumption Observation: Observations were made of the bats consuming prey in captivity, with video recordings used to document feeding behavior and prey manipulation.
                 3. Molecular and Acoustic Analysis:
                    DNA Barcoding: Molecular techniques were used to identify insect species from fecal samples.
                    Acoustic Measurements: Echolocation calls of G. soricina were recorded and analyzed to study their echolocation behavior. Additionally, acoustic models were created to understand detection distances for moths and bats.
                 4. Neural Measurements:
                    Moth Auditory Response: Measurements of auditory responses in noctuid moths were used to model detection distances and evaluate the effectiveness of G. soricina’s echolocation calls.
Timeline : not mentioned in the study
Response rate :  not found it in the study
Weights : 1. Dietary Analysis Weights: Insect Fragments: The study analyzed guano samples to identify insect fragments. The weight of individual insect fragments 
            isn’t specified, but the analysis focuses on identifying insect species through molecular techniques.
          2. Behavioural Experiments Weights: Mealworms: The weight of the mealworms used in the experiments is not provided. However, the study mentions that
             mealworms were presented to bats as a food source during behavioural trials.
          3. Echolocation Weights:Acoustic Measurements: The study uses the concept of "target strength" (TS) for prey items to model detection distances. TS is
             calculated from surface area measurements rather than physical weights.
          4. Statistical Weights: Data Analysis: The study uses various statistical methods to analyze echolocation call parameters and prey detection distances, 
             but specific weights are not mentioned in the statistical analysis.
Data processing : Dietary Analysis
                  1. Sample Preparation:
                  2. DNA Extraction and Amplification
                  3. Sequencing and Identification
                  4. Prey Surface Area Measurement

               Behavioural Experiments
                  1. Experimental Setup:
                  2. Recording and Analysis
                  3. Data Synchronization 
               Echolocation Call Parameters
                  1. Call Measurement
                  2. Flight Path Tracking
               Model of Maximum Detection Distances
                  1. Detection Distance Modeling:
                  2. Error Analysis
               Statistical Analysis
                  1. Comparative Analysis:
Cleaning, imputation, etc. :1. Data Cleaning
                                Guano and DNA Samples:
                                Fragment Removal: Insect fragments were carefully removed from guano samples, ensuring no contamination from other fragments or materials.
                                Ethanol Evaporation: The ethanol was evaporated completely from the samples to avoid any residual ethanol affecting the lysis and DNA extraction processes.
                                Sequence Data: 
                                Sequence Editing: Sequencing data was edited using Sequencher to remove any low-quality sequences or artifacts.
                                Manual Alignment: Sequences were manually aligned in BioEdit to correct any alignment errors and ensure accuracy in phylogenetic analysis.
                                Prey Surface Area Measurement:
                                Image Quality: Photographs of pinned specimens were checked for clarity and accuracy before measuring surface areas.
                                Manual Outlining: Surface area measurements in ImageJ required careful manual outlining to avoid measurement errors.
                               Behavioural Data: 
                               Synchronization: Audio and video recordings were synchronized carefully to ensure that the timing of echolocation calls and bat behaviors were accurately matched.
                               Attack Classification: Attacks were classified as ‘flower-like’ or ‘insect-like’ based on visual and audio cues, requiring consistent criteria to avoid subjective bias.
                            2. Imputation and Handling Missing Data
                               Handling Missing Values:
                               Missing Sequences: If any sequences were missing or failed during the sequencing process, they were excluded from the final analysis. This was noted in the data processing documentation.
                               Incomplete Behavioral Data: In cases where behavioral data were incomplete (e.g., due to equipment malfunction), the missing data points were noted, and statistical analyses accounted for the potential gaps.
                               Statistical Imputation:
                               Surface Area Measurements: If any surface area measurements were missing or could not be obtained, imputation methods such as mean substitution or regression-based imputation (if justified) could be used, though the study primarily relied on complete data
Sources of error : 1. Sampling Errors
                  **1.1. Guano Collection:
                     Sample Contamination: Contamination of guano samples with non-target insect fragments could lead to inaccurate dietary analysis.
                    Sampling Bias: The timing and method of guano collection may not fully represent the diet of the bats over the study period.
                  **1.2. Species Identification:
                    Misidentification: Incorrect identification of insect fragments due to sequencing errors or incomplete reference databases could lead to erroneous dietary conclusions.
                  2. Technical Errors
                   **2.1. Sequencing Errors:
                     Low-Quality Sequences: Poor-quality sequences or errors in sequencing could result in inaccurate species identification or missing data.
                   **2.2. Data Processing:
                    Editing and Alignment Errors: Errors during the sequence editing and alignment process could affect the accuracy of phylogenetic analysis.
                    Measurement Errors: Inaccuracies in measuring prey surface area or call parameters could impact the results.
                  3. Behavioral Experiment Errors
                    **3.1. Experimental Setup:
                      Equipment Malfunction: Failures in recording equipment (e.g., microphones, cameras) could result in incomplete or inaccurate data.
                      Synchronization Issues: Errors in synchronizing video and audio recordings could affect the accuracy of behavioral analysis.
                    **3.2. Subject Variability:
                      Captive Conditions: The behavior of captive bats may differ from wild bats, potentially impacting the relevance of the findings to natural behaviors.
                      Individual Differences: Variability in individual bat responses could introduce noise into the behavioral data.
                  4. Modeling Errors
                    **4.1. Assumptions and Simplifications:
                      Model Assumptions: The model for detecting prey and bat calls relies on several assumptions (e.g., fixed hearing thresholds, environmental conditions) that may not fully capture real-world variability.
                      Thresholds and Target Strengths: Using average values or assumptions for auditory thresholds and target strengths may not account for the full range of variability among moth species.
                    **4.2. Data Normalization:
                      Inaccurate Normalization: Errors in normalizing data for target strength and detection distances could affect the model's predictions.
                   5. Data Handling Errors
                      **5.1. Missing Data:
                      Exclusion Bias: Excluding missing or incomplete data might introduce bias if the missing data are not randomly distributed.
                      Imputation Errors: Imputing missing values (if done) may introduce inaccuracies or bias if not handled correctly.
                      **5.2. Data Processing:
                     Data Transformation Errors: Errors in transforming or correcting data (e.g., attenuation correction) could impact the final results.
                   6. Human Errors
                      **6.1. Subjective Judgments: 
                      Behavioral Classification: Subjective judgments in classifying bat attacks (e.g., ‘flower-like’ vs. ‘insect-like’) could introduce bias.
                      **6.2. Data Entry and Analysis:
                        Manual Data Entry: Errors during manual entry of data or during statistical analysis could affect results and interpretations.
Limitations, known biases: Limitations
                          **1. Sampling Limitations:
                              Temporal Bias: The study covers a specific period (late May to early July 2009). Seasonal variations in prey availability and bat behavior outside this period are not accounted for.
                              Geographic Limitation: The study is localized to the Area de Conservación de Guanacaste, Costa Rica. Findings may not be generalizable to other geographic regions with different ecological conditions.
                           **2. Technical Limitations:
                               Sequencing Resolution: The sequencing technique used (COI gene amplification) may not provide full resolution for species-level identification, particularly if reference sequences are incomplete or outdated.
                               Behavioral Observation Constraints: The behavioral experiments were conducted in a flight room with captive bats, which may not fully represent natural foraging behaviors or environmental conditions.
                           **3. Modeling Limitations: 
                               Simplified Assumptions: The model for detecting prey and bat calls relies on several assumptions (e.g., fixed hearing thresholds, environmental conditions) that may not capture real-world variability.
                               Prey Surface Area Measurement: Surface area measurements of prey items were based on a single specimen per species and photographs, which may not fully account for individual variability.
                           **4. Data Processing Limitations:
                                Sequence Editing and Alignment: Manual alignment of sequences may introduce errors or biases, affecting the accuracy of species identification.
                                Detection Distance Calculations: The model for maximum detection distances relies on several parameters (e.g., call intensity, target strength) that may be subject to measurement inaccuracies.
                         **5. Behavioral Experiment Limitations:
                              Captive Conditions: The captive bats may not exhibit the same foraging behaviors as wild bats, limiting the applicability of the findings to natural settings.
                              Behavioral Classification: Subjective classification of bat attacks (e.g., ‘flower-like’ vs. ‘insect-like’) could introduce bias into the behavioral analysis.
                       Known Biases
                            **1. Sampling Bias:
                             Guano Collection Bias: The guano samples may not represent all prey items consumed by the bats, potentially leading to an incomplete dietary profile.
                             Prey Size Bias: The study focused on measuring the surface area of certain prey species, which may not account for variations in prey size or target strength.
                           **2. Technical Bias:
                             Sequencing Bias: Potential biases in sequencing technology or reference databases could affect the accuracy of species identification and dietary analysis.
                           **3. Behavioral Bias:
                               Captive vs. Wild Behavior: Differences in behavior between captive and wild bats could introduce bias in the interpretation of foraging strategies and echolocation patterns.
                           **4. Modeling Bias:
                             Assumption Bias: The model for detecting prey and bat calls may be biased by simplifying assumptions, such as fixed hearing thresholds and environmental conditions, which may not fully reflect natural variability.
                           **5. Human Error:
                              Data Entry and Analysis: Manual data entry and subjective judgments during behavioral classification and data analysis may introduce errors or biases into the results.
Citation:Trophic niche flexibility in Glossophaga soricina: how a nectar seeker sneaks an insect snack
Elizabeth L. Clare, Holger R. Goerlitz, Violaine A. Drapeau, Marc W. Holderied, Amanda M. Adams, Juliet Nagel, Elizabeth R. Dumont, Paul D. N. Hebert, M. Brock Fenton
Links to any documentation or additional sources used:https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/1365-2435.12192









 
     |                                                                                             |
|                                                         |

## Criteria

|Criteria|Complete|Incomplete|
|--------|----|----|
|Population of the data table|The table has been correctly populated from the sources.|The table has been populated, but the information provided is incorrect.|

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `data-documentation`
* What to submit for this assignment:
     * This markdown file (data_documentation_comparison_worksheet.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
     * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `data-documentation`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
