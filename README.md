# Pymaceuticals

<h2>DESCRIPTIONS OF OBSERVATIONS</h2>

<p>The original animal study treated 250 mice with 9 drug regimes (altogether 10 plus placebo) over the course of 45 days and documented parameters such as tumor volume and metastatic sites to predict anti-tumor potentials of the drugs. Data from Capomulin-, Infubinol-, Ketapril-, as well as Placebo-treated mice were analyzed in particular for this homework. Overall, mice given Infubinol or Ketapril endured similar increase of tumor volume (> 45%) as compared to those taking Placebo, whereas the cohorts with Capomulin exhibited a 19% reduction. Detailed observations and analysis were summarized and elucidated as follows:</p>

<p><strong>1. Tumor Response to Treatment:</strong></p>

<p>Two distinct patterns were observed while analyzing tumor responses upon different drug treatments: Infubinol and Ketapril fired almost the same direction as Placebo did towards the upper right corner on the chart of “Tumor Response to Treatment”. A follow up t-test analysis confirmed that there is no difference in tumor volumes among them (“Tumor response to treatment – Analysis”). Such steady increases in tumor volumes indicates that Infubinol and Ketapril has no beneficial effect in controlling tumor growth. As verified by t-test, Capomulin, starting from the earliest timepoint documented (5d), consistently suppressed tumor growth over time by shrinking its volume.</p>
<img src="./Figures/Tumor Response to Treatment.png" alt="Tumor Response">

<p><strong>2. Metastatic Response to Treatment:</strong></p>

<p>Metastasis is another important parameter observed in this study. Mice in all groups developed a gradual increase in the number of metastatic sites over time, regardless of which drug they took. Ketapril appeared to be ineffective in controlling tumor metastasis as it was stuck with Placebo at every timepoint for t-test (“Metastatic response to treatment – Analysis”). Infubinol showed some beneficial effects to alleviate tumor metastasis starting from day 30 as compared to Placebo (1.59 vs 2.27). Again, Capomulin gave the best performance in controlling tumor metastasis in terms of time (as early as day 10) and extent (45% of that from Placebo on day 45).</p>
<img src="./Figures/Metastatic Response to Treatment.png" alt="Metastatic Response">

<p><strong>3. Survival Rates:</strong></p>

<p>By counting the alive mice at each timepoint from Placebo group, we get an idea that the survival rate of mice used for this study should be around 80% on day 15 and around 60% at day 30. Eventually, it will drop below 50% at day 45.</p>

<p>The survival curve of Ketapril was slightly lower than that of Placebo before day 20 but remained approximately 20% higher after that. On day 45, the two curves met again. Even though Ketapril failed in improving either the tumor growth or metastasis, since there is no clue on the chemical properties, pharmaceutical kinetics, solubility and metabolic stability, and most importantly optimized concentration for tumor study, the only conclusion we can draw here is that Ketapril, at current concentration, in current solvent and with current route of administration, exhibit no anti-tumor effect.</p>

<p>The curve of Infubinol pretty much twisted with that of Placebo. After day 30, the survival rates of mice in Infubinol group is around 85% of that given Placebo, indicating that it might not be a sound option to further increase the concentration of Infubinol for anti-tumor study due to potential toxicity. Notably, this period largely covered its anti-metastasis region. Therefore, we conclude that Infubinol has no effect in controlling tumor growth. It can only alleviate tumor metastasis after 30 days, which, as illustrated by the survival curve, might be due to its toxicity.</p>

<p>Capomulin remarkably distinguished itself from the rest in sustaining an over 80% survival rate across 45 days. On day 45, the figure is twice of that from Placebo. We are happy to see that Capomulin efficiently suppressed tumor growth as well as alleviated tumor metastasis. Treating with Capomulin greatly improved the survival rates of mice. Capomulin is a potential anti-tumor drug that worthy of further investigation.</p>
<img src="./Figures/Survival Rates (K-M Estimator).png" alt="Survival Rates">
