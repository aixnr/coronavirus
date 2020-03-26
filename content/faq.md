---
date: "2020-03-24T10:15:00-04:00"
title: "Frequently Asked Questions"
last: "2020-03-24T10:15:00-04:00"
---

This page is for frequently asked questions (FAQ). I realized that it would be useful to cover basic concepts here to complement information on the main page.

**■ Detection of subgenomic viral RNA**  
Detection of subgenomic viral RNA (vRNA) typically involves isolation & purification of RNA from collected biological samples. The samples could be from nasopharyngeal, oropharyngeal swab, etc. These days it is common to use kit to isolate & purify RNA. However, keep in mind that the supply chain for commercial kits could be disrupted by the outbreak. With that in mind, head over to Addgene Blog to learn about [RNA Extraction Without A Kit](https://blog.addgene.org/rna-extraction-without-a-kit). RNA can degrade easily, hence the samples must be handled delicately.

{{<block-note>}}
**Note:**  
I use the term *subgenomic viral RNA* here specifically because when performing qRT-PCR for quantifying viral load, we often amplify a small genomic region, not the whole genome. For example, the full genomic length of SARS-CoV-2 is about 29 kilobases. It would take a serious amount of time to amplify the whole thing, if at all possible. Usually the product size would be around ~100--150 bases, targeting conserved genomic regions but unique enough to accurately identify the virus.

Oh by the way, please handle guanidinium thiocyanate very, very carefully.
{{</block-note>}}

Next, we synthesize RNA into complementary DNA (**cDNA**). This step is known as the reverse-transcription (**RT**), i.e. reversing the RNA (the transcript) back into its DNA form. Having them in the form of cDNA is useful since cDNA is much more stable than RNA, which makes handling in subsequent steps easier. After that, a quantitative polymerase chain reaction (**qPCR**) is performed with primer pair (forward and reverse primers) on the cDNA. I would not discuss the minutiae of the technique/protocol here, but if you are curious here is a video by New England Biolabs on the [Overview of qPCR](https://www.youtube.com/watch?v=1kvy17ugI4w).

{{<block-note>}}
**Note:**  
There are more than "just RT-qPCR it!". This requires knowledge of the detection method (intercalating dye-based or fluorescent probe-based), quality control (melt curve, Cq, dot plot), quantification metrics (ΔCt or standard curve), etc. Please talk to experts. Otherwise, RT-pPCR is a fun technique. Head over to the [MIQE Guidelines](https://doi.org/10.1373/clinchem.2008.112797) to learn more about RT-qPCR. Here is another good paper on qPCR by [Schmittgen & Livak (2008)](https://doi.org/10.1038/nprot.2008.73). For a step-by-step analysis of qPCR result by using the ΔΔCt method by using Excel spreadsheet, [Top Tip Bio got you covered](https://www.youtube.com/watch?v=Kkle8T7aXjk).
{{</block-note>}}

Usually, the result is reported either as Ct value (Ct = threshold cycle) or using standards of known RNA concentration. Designation of Ct value is contingent upon the number of cycles required for the fluorescent signal to cross the threshold. In other words, low Ct value means the threshold is crossed sooner, which then suggests that the amount of starting target cDNA is high. In contrast, high Ct value means the threshold is crossed later (if at all), which then suggests that the amount of starting target cDNA is low. Ct below 29 indicates strong positive reactions, whereas Ct above 40 indicates negative reaction.

**■ Airborne and airbone *precautions***  
By strict definition, SARS-CoV-2 is not classified to transmit via airborne. The route of transmission for SARS-CoV-2 is through **droplet infection**, where large droplet (> 5 µm in diameter) could carry live infectious virus particles. This droplet could travel as far 2 meters ([Xie et al. 2007](https://doi.org/10.1111/j.1600-0668.2007.00469.x)). Moreoever, inanimate objects (e.g. door knob, solid surface, etc.) could be contaminated with live infectious virus. Contaminated inanimate object is known as **fomites**. This is one of the main reasons why it is crucial to wash your hands frequently.

In a hospital settings where healthcare workers have to interact with infected individuals to provide treatments, extra precautions are taken to protect themselves from being infected. Given the uncertainty surrounding the transmissibility of SARS-CoV-2, [healthcare workers are recommended to follow airborne precautions](https://www.uptodate.com/contents/coronavirus-disease-2019-covid-19).

**■ Serology**  
RT-qPCR is a great method to identify individuals that are infected, it has high sensitivity, and it is a generally-accessible laboratory technique to perform, as long as there is sufficient access to essential lab equipments (centrifuge, thermocycler, etc). However, this method could only detect the presence of virus when it is present in infected individuals. A serological technique could complement in a way that it could detect the presence of antibody specific against the infecting antigen. This technique could also help to identify infected individuals that were *asymptomatic*.

Serological technique relies on the detection of circulating antibodies in the blood. Usually, we would look at the presence of immunoglobulin G (IgG) or M (IgM). The presence of either or both would indicate that the infected host was able to *process* the virus and started making antibodies to clear the infection. Usually, the metric for successful production of neutralizing antibody is the increase of antibody titer by four-fold. This phenomenon is specifically known as the **seroconversion**. For example, an increase of neutralizing antibody titer from 1:4 (before or at illness onset) to 1:320 (post-recovery, ~28 days after being infected) is above four-fold, therefore this individual has seroconverted.

**■ Fatality Rates**  
Numbers reported in most publications typically refer to the **case fatality rate**, defined as death per total cases reported. However, since we are having issues with tracking the actual number of infected subjects (some say we are off by 60--70% percent), the **crude fatality rate** (death per actual total number of infected individuals) might be lower than the **case fatality rate**.


**■ Basic reproductive number, R<sub>0</sub>**  
I saw this number being thrown a lot at the beginning of the outbreak. The correct pronunciation is "R naught", it is intended to be an indicator of the contagiousness and transmissibility of parasitic agents. 

First, let's discuss what this number is not. A high R<sub>0</sub> does not mean a disease with serious health implication, rather a high number indicates it could spread quickly. Even an R<sub>0</sub> of 3 would be really hard to contain since an infected person could transmit to 3 more other person. Anything above 2, the spread is exponential, making containment harder if the world does not take it seriously.

The R<sub>0</sub> is not static. A proper control measure could lower it down. However, when the spread is not taken seriously, the number could balloon up especially in the face of overwhelmed healthcare system and incompetent local leadership.

While R<sub>0</sub> is a useful metric especially when communicating the transmissibility of the disease, it is not the only metric that we need to care about. R<sub>0</sub> is just an average, it is hard to calculate, and it does not take into account the possibility of a super-spreading event, and it does not incorporate asymptomatic cases. It is definitely useful, but it does not tell everything. 
