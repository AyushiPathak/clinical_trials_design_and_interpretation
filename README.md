# Clinical Trials

PROJECTS: Courses (https://www.notion.so/Courses-9d179af0e5bd48478cb74e12279f7db2?pvs=21)

# WEEK 1

## 1. **Comparison Structure: Parallel, Crossover, and Group Allocation Designs**

## 2. **Extensions of the Parallel Design: Factorial and Large Simple Designs**

---

## Factorial Design:

- **Definition**: Testing two or more experimental interventions simultaneously. Test treatment A vs control treatment A and treatment B vs control treatment B
- **Purpose**: Economical testing (mostly) of multiple interventions, or testing for interaction between interventions.
- **Assumptions**: Usually assumes no interaction between treatments, each treatment has an independent mode of action. (that is why second purpose is not in application )
- **Representation**: Graphically depicted by a two by two table showing combinations of treatments and controls.
- **Comparison**:
    - **Main effects** are assessed assuming no interaction. margin of the cells
        - A vs no A regardless of B
        - B vs no B regardless of A
    - **Interaction** is assessed by comparing cell responses. (inside cells not margins)
    - More explained with diagram
- the sample size needs to be large to draw conclusions
- **Example**: Physicians' Health Study:
    - Tested beta carotene vs placebo for cancer and aspirin vs placebo for coronary artery disease.

> Placebo is a drug or treatment that is not active. 
Placebos help maintain blinding or masking in a study, which is important to minimize bias. Blinding refers to keeping both the participants and the researchers unaware of who is receiving the active treatment and who is receiving the placebo. This ensures that any observed differences in outcomes are not influenced by participants' or researchers' expectations or biases.
Placebos are often used as a control group against which the effects of the active treatment are compared. By administering placebos to a portion of the participants, researchers can establish a baseline against which they can measure the effectiveness of the experimental treatment. This helps in determining whether the observed effects are truly due to the treatment itself or simply placebo effects.
> 

![Factorial Design.png](Clinical%20Trials%20af8b41f4a6e34fa5b4f4e1d228781752/Factorial_Design.png)
https://github.com/AyushiPathak/clinical_trials_design_and_interpretation/blob/main/Images/Factorial%20Design.png

Graphically represented by a 2x2 table (pink)

> MARGIN RESPONSE
To access main effect of A : Compare the response people in margin V Row 1 ( A, w/wo B) to margin C Row 2 (No A, w/wo B) 
To access main effect of B : same with Margin H
> 

> CELL RESPONSE
To access the interaction: compare effect of 
- A vs not A and those with B 
- A vs not A with those not B
> 

![Untitled](Clinical%20Trials%20af8b41f4a6e34fa5b4f4e1d228781752/Untitled.png)

Source: ISIS-3 Collaborative Group (1992). *Lancet 399:753-770*

**EXAMPLE** ISIS-3 Trial (International Study of Infarct Survival-3):

- **Design**: Three by two factorial design.
- **Also considered large, simple design**
- **Treatments**:
    - Aspirin plus heparin vs aspirin alone.
        - Those treatments were presumed to act through an antithrombotic mechanism on the **outcomes of myocardial infarction and stroke in cardiovascular death.**
    - Streptokinase vs tPA vs APSAC.
        - These three treatments were presumed to act through a fibrinolytic mechanism
    - Common primary outcome but had two different proposed mechanisms of action on the outcome.
- **Outcome**: Myocardial infarction, stroke, cardiovascular death.
- **Participants**: Over 41,000 patients, 914 participating hospitals in 20 countries.
- **Representation**: Depicted by a three by two table showing combinations of treatments.

## Large, Simple Design:

1. **Nature of Large, Simple Designs:**
    - Large, simple designs involve a massive number of participants, often tens of thousands, recruited from numerous centers.
    - Broad eligibility
    - Minimal data collection is required for each participant.
2. **Rationale for Large Sample Size:**
    - These trials aim to detect modest benefits since groundbreaking effects like those of penicillin are rare.
    - Detecting small survival benefits, especially for conditions like heart disease, necessitates a large sample size.
    - Small advancements in treatment can result in notable improvements in survival time, given the prevalence of the condition.
3. **Assumption of Few Treatment Interactions:**
    - Large, simple designs assume minimal treatment interactions, meaning treatments have consistent effects across diverse patient populations.
    - Consequently, extensive data collection on baseline characteristics and interim response variables may not be essential.
4. **Tolerance for Less Precision:**
    - Due to the heterogeneous participant pool and limited control over treatment administration and outcome assessment, these trials tolerate less precision.
    - More error/ Increased variance in outcome measures is counteracted by the large sample size.
5. **Requirements for Implementation:**
    - Interventions must be easily administered, requiring minimal long-term adherence, dose adjustments, or ongoing monitoring for adverse events.
        - MAJOR LIMITATION:  number of interventions do require one if not all three of these activities
    - The outcome should be easily ascertained and not require complex follow-up procedures for diagnosis.
        - In ISIS-3 outcome were 35 day mortality, assessed by gov records
        - For diagnose Alzheimer's disease for a study that I work on, we require extensive neuro-psychological testing, detailed medical history. We do interviews with friends and family about changes in the participant's cognitive functioning. We also do lab work and imaging. It's a rather complicated outcome, and it would not be appropriate for a large simple study where you have thousands and thousands of patients for whom who have to readily assess the outcome.
    - Limited data collection at baseline is acceptable due to the assumption of few treatment interactions. Confidence that simple data is persuasive enough.
6. **Data Collection Procedures in ISIS-3:**
    - Eligibility documentation was simplified, completed through a phone call to a 24-hour service provided by the coordinating center.
    - Treatments were packaged conveniently for ease of use and were readily available at recruiting centers.
    - Ancillary treatments were not restricted, allowing them to be used alongside the study interventions.
    - Data on events during hospital stays were documented using a one-sided form at discharge.
    - Follow-up after discharge was conducted through searches of government records for vital status.

> Ancillary Treatment : Ancillary treatments refer to additional treatments or interventions provided to patients alongside the main intervention being studied or administered. These treatments are often necessary for the overall management of the patient's condition or symptoms but may not be the primary focus of the study or medical intervention.
> 

## 3. **Testing for Hypotheses Other than Superiority: Equivalency and Non-Inferiority Designs**

Superiority Hypothesis , if treat A in better than B or vice versa, is the most common type. 

Using other types of hypothesis/ designs helps to establish the same effectiveness of treat A as B, but A has better characteristics like easy administration, cost effectiveness. less adverse effects.

### **Equivalence Design:**

- Objective: Demonstrate equivalence between two treatments.
- Definition of Equivalence: Intervention response falls sufficiently close to the control response, within marginal range.

![SuperiorityVsEquivalence.png](Clinical%20Trials%20af8b41f4a6e34fa5b4f4e1d228781752/SuperiorityVsEquivalence.png)

- Setting Equivalence Margin: Determining how large the difference can be between treatments to still consider them equivalent.
- Sample Size Requirement: **Large sample size needed** for both ruling out large differences and ensuring high probability of detecting a difference.
- Hypothesis Framework: Null hypothesis asserts a difference between treatments; alternative hypothesis posits no difference. The Hypothesis and errors are flipped from superiority design
- EXAMPLE: Jaeb Center study comparing patching and atropine for amblyopia in children.
    - Objective: Assess equivalence between the two treatments.
    - Outcome: Visual acuity measured at follow-up visits.
    - Equivalence Limit: Set at five letters or one line on the ETDRS chart.
    

### **Non-inferiority Design:**

- Objective: Determine if a new treatment is at least as good as an established treatment.
- Hypothesis Setup: Null hypothesis states the new treatment is worse than the established one; alternative hypothesis seeks to reject this by demonstrating non-inferiority.
- **One-sided Test**: Focuses on showing that the new treatment is not significantly worse than the established treatment.

> One sided versus two sided test:
> 

- EXAMPLE: Apixaban compared to Enoxaparin for preventing venous thromboembolism post-total knee replacement surgery.
    - Enoxaparin is a low molecular weight heparin, and is frequently used for the prevention of venous thromboembolism after major joint replacement. However, Enoxaparin increases the risk of bleeding, and it can be cumbersome to use. So the investigators proposed that Apixaban, which is an orally active factor XA inhibitor might be as effective in preventing venous thromboembolism. But may have a lower bleeding risk and it might also be to easier to administer the Enoxaparin. In advance two the patients were allocated to receive oral Apixaban twice a day starting 12 to 24 hours after surgery or subcutaneous injections of Enoxaparin starting 12 hours before surgery. Both treatment groups had placebos or shams. The treatments were continued for 10 to 14 days after surgery. The patients were assessed for the main outcome which was a composite of asymptomatic and symptomatic DBT, non-fatal pulmonary embolism, and all-cause death.
    - Objective: Assess if Apixaban is not worse than Enoxaparin.
    - Outcome: Composite of thromboembolic events and all-cause death.
    - Non-inferiority Limit: Upper 95% confidence limit of risk ratio (A vs E not exceeding 1.25) and risk difference (A-E not exceeding 5.6% if difference).

![Untitled](Clinical%20Trials%20af8b41f4a6e34fa5b4f4e1d228781752/Untitled%201.png)

Source: CMPM/EWP/482/99; EMEA (2000)

A point estimate is a single value that estimates some population parameter based on our sample data. An example is the sample mean, which is the average of the values in our sample. And it's frequently used to estimate the unknown population mean. An interval estimate specifies a range within which the population parameter is estimated to lie based on the sample. How likely the interval is to contain the parameter is determined by the confidence level. And that's usually expressed as a percentage. The most commonly used confidence interval is the 95% confidence interval. For a 95% confidence interval, one can expect that if you sample repeatedly from the same population, 95% of the confidence intervals of the sample mean will contain the population mean of interest.

In this figure, we have several confidence intervals, and these are indicated by the blue and red horizontal lines. The point estimates are designated with the short vertical lines that you see in the middle of the confidence intervals 

These point estimates represent the sample estimate of the treatment difference between the experimental and the control groups. The solid black vertical line that runs from the top to the bottom, and ends above the zero, is the zero line. \

**And point estimates that are close to the zero line indicate that our best estimate is that there is not much difference between the treatment effects in the two groups.**

Point estimates that fall to the left of the solid zero line, favor the experimental treatment, and point estimates that fall to the right of the zero line favor the controlled treatment.

In this figure, in order to show superiority of the experimental treatment, we need the 95% confidence interval to fall entirely to the left of the zero line.

You'll notice that there's another long vertical line that is dashed and has a delta at the top. This is our **non-inferiority margin.** If the confidence interval crosses or falls to the right of the non-inferiority margin, then we cannot reject the null that the experimental is worse than the control.

**However, if the 95% confidence interval falls entirely to the left of the delta line, we can reject the hypothesis that the experimental treatment is worse than or inferior to the control.**

So in this figure, the confidence intervals that are shaded in blue fall entirely to the left of the delta line. So in those cases we can say that we have **shown non-inferiority.** The confidence intervals shaded in red, cross the delta line so we cannot say that we've shown non-inferiority. Only the bottom confidence interval falls to the left of the non-inferiority line and also entirely to the left of the zero line. **And so, in that scenario, we can say that we've shown non-inferiority, and we have also shown superiority.**

- Nested Hypotheses: Trials may be designed with nested non-inferiority and superiority hypotheses, allowing for sequential testing.  If non-inferiority is established when the study is finished, then they can go on and test for superiority. The more common situation is when investigators fail to show superiority, but they might then test if they can show non-inferiority.

# 4. Adaptive Design

---

**Introduction to Adaptive Designs:**

- Adaptive designs are becoming increasingly popular in clinical trials, particularly in the pharmaceutical industry, due to their potential for increased efficiency in demonstrating the effects of a drug.
- The FDA has started drafting guidance documents for industry regarding the use of adaptive trials in the drug development process.

**Definition of Adaptive Trials:**

- The FDA defines an adaptive trial as a study with prospectively planned opportunities for modifying specified aspects of the study design and hypotheses based on the analysis of data, usually interim data, from subjects in the study.
- Adaptive designs involve planned adaptations detailed **before data examination,** distinguishing them from changes in traditional fixed designs that occur in response to data examination.

**Potential Adaptations in Adaptive Designs:**

1. Changes in randomization probabilities: Adjusting the probability of assigning participants to treatment groups based on ongoing analysis of treatment response.
2. Changes in sample size: Adjusting sample size calculations based on accruing data to maintain original statistical power.
3. Group sequential methods: Stopping early due to benefit or harm of a treatment.
4. Changes in follow-up schedule: Adjusting the length or frequency of follow-up visits based on observed outcomes.
5. Changes in treatment groups: Adding, dropping, or modifying treatment arms based on interim analysis.
6. Changes in eligibility criteria: Modifying criteria based on subgroup responses or enrichment designs.
7. Changes in outcome measures or analysis methods: Adjusting endpoints or analytical techniques based on observed data.

**Principles of Adaptive Designs:**

- Adaptation triggers should be explicitly stated in the protocol.
- Adaptations themselves should be detailed in the protocol.

**Implementation of Adaptive Designs:**

- IRB submission and approval include planned adaptations; amendments are not required for planned adaptations.
- Extensive documentation of potential triggers and adaptations is necessary.

**Advantages of Adaptive Designs:**

- Potentially more efficient than traditional fixed designs.
- Certain adaptations can increase the likelihood of showing a treatment effect.

**Limitations of Adaptive Designs:**

- Interpretation of treatment effect estimates can be challenging due to changes in design parameters.
- Interim estimates of treatment effect may differ from final estimates, impacting trial outcomes.
- Practical implementation may be challenging due to delays in data availability and analysis.

**Example of an Adaptive Design: I-SPY 2 Study:**

- Collaborative effort involving academic, government, and pharmaceutical groups.
- Compares novel drugs in combination with standard chemotherapy to standard therapy alone for locally advanced breast cancer.
- Objective is to identify improved treatment regimens based on biomarker signatures of disease.
- Uses adaptive randomization and allows new experimental drugs to enter or exit the trial based on performance.
- Candidate drugs must have passed phase one clinical studies and show preliminary evidence of efficacy for breast cancer.

**Conclusion:**

- Adaptive designs offer flexibility and potential efficiency in clinical trial conduct.
- Understanding adaptive design features is crucial for interpreting trial results accurately.

---

# WEEK 2

# 1. Rationale for Randomization

**Introduction to Randomization**:

- Randomization is a core feature of randomized clinical trials (RCTs), along with standardized treatment and prospective data collection.
- It has historical roots and has been used in various contexts such as military drafts and resource allocation.

**Historical Context**:

- Proposed in the 17th century by Van Helmont for comparing different treatments objectively.
- Formally introduced into experimental design by Ronald Fisher, emphasizing its statistical properties.

**Introduction in Medical Science**:

- **Sir Austin Bradford Hill** introduced randomization to address confounding by indication and selection bias.
- The first properly randomized trial led by Bradford Hill tested streptomycin for tuberculosis in 1946.

**Rationale for Randomization**:

- Aims to avoid selection bias and confounding by ensuring comparable treatment groups.
- While it tends to produce balanced groups, it's not guaranteed due to the probabilistic nature of the process.
- Ensures statistical validity and defines trial entry points.
- Define time point for trial entry.

**Unequal Allocation Ratios**:

- Sometimes used to maximize experience with new treatments, recruitment incentives, cost considerations, and variance differences.
- Selection bias in clinical trials focuses on internal validity and eliminates bias associated with disease prognosis.

# 2. **Types of Schemes**

Simple Randomization:

- Analogous to a coin toss, ensuring complete randomness in treatment assignment.

Advantage

- Each assignment is independent of the last, maintaining a fixed probability for treatment allocation.
- Ensures unpredictability and, over time, balances treatment groups if the randomization process is scientifically designed.

Risks Associated with Simple Randomization:

- Imbalances lower the statistical power
    - in the number of patients assigned to each group may occur, affecting statistical power.
    - related to important confounding factors, such as disease severity or demographics, are possible.
- Diminish credibility
- Large numbers of patients can mitigate these risks, inversely related

Restricted Randomization:

- Imposes constraints on the randomization scheme to ensure balance across important factors.
- Common maneuvers include **blocking and stratification.**

Blocking:

Utilizes blocks of treatment assignments to achieve the desired allocation ratio. A:B=1:1 For a block size of 4 2As and 2Bs : list of permutation  is 6 ( )

- Size of smallest possible block is sum of integers defined in treatment allocation ratio.
    - For ratio 1:1 the smallest block size is 2
    - For ratio 2:1 it is 3
        - and the large block size is multiple of smallest one ie 6,9,12…..
- Blocks are randomly permuted, ensuring balance in treatment assignment over time.
    - randomly chooses 1 of X permuted blocks
- Ensure balance in treatment assignment over time.

How many blocks?

![Untitled](Clinical%20Trials%20af8b41f4a6e34fa5b4f4e1d228781752/Untitled%202.png)

> For a block size of 6 we have n=6 (block size) and r=3 (3 of each A and B) and k is the number of types (here 2 as A and B)
> 

Blocking Implementation

- Fixed allocation ration throughout the trial
- Info about the size and related info is on need to know basis, not mentioned in the protocol.
    - there should be separate documentation of the treatment assignment scheme and how it was generated, but generally, the details in the protocol should be limited to those that the clinician needs to know in order to execute the protocol, and be knowledgeable about the general experimental design.
- Use more than one block size
    - Use of the standard block size of two in the one to one allocation ratio let people figure that out that if the first assignment was an A, the next one's going to be a B.  This defeats the whole purpose of the Randomization and limited protocol.
    - In case of masked trail acts as a disadvantage : In unmasked it is still fine.

Benefits and Risks of Blocking:

- Advantages include
    - guaranteeing overall balance,
    - protect against time related changes: study pop, data collection, external forces (secular trends. chronological basis)
    - if trial stopped early, equal groups exist.
    - more powerful analysis
- Disadvantages include
    - the potential for predicting future assignments
    - more problematic in unmasked trials or poorly masked trials.

Stratification:

Ensures balance across important factors specified before randomization, such as **clinic, gender, or disease severity.**

- Requires separate treatment assignment schedules for each stratum.
- Should be limited to a few variables strongly related to outcomes and logistically feasible.

Benefits and Risks of Stratification:

- Ensures balance within subgroups, protecting against biases related to stratification variables.
- Too many stratification variables can lead to unbalanced allocation and logistical challenges.

Adaptive Randomization:

- The probability of treatment assignment varies based on the current balance of participants or outcomes.
- Common types include minimization and play the winner designs.
- Requires real-time decision-making and outcome assessment, impacting the treatment allocation process.

Conclusion:

- Explored Simple Randomization, Restricted Randomization, and Adaptive Randomization schemes.
- Each has its benefits and risks, impacting the design and credibility of clinical trials.
