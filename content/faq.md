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
There are more than "just RT-qPCR it!". This requires knowledge of the detection method (intercalating dye-based or fluorescent probe-based), quality control (melt curve, Cq, dot plot), quantification metrics (ΔCt or standard curve), etc. Please talk to experts. Otherwise, RT-pPCR is a fun technique. Head over to the [MIQE Guidelines](https://doi.org/10.1373/clinchem.2008.112797) to learn more about RT-qPCR. Here is another good paper on RT-qPCR by [Schmittgen & Livak (2008)](https://doi.org/10.1038/nprot.2008.73).
{{</block-note>}}

Usually, the result is reported either as Ct value (Ct = threshold cycle) or using standards of known RNA concentration. Designation of Ct value is contingent upon the number of cycles required for the fluorescent signal to cross the threshold. In other words, low Ct value means the threshold is crossed sooner, which then suggests that the amount of starting target cDNA is high. In contrast, high Ct value means the threshold is crossed later (if at all), which then suggests that the amount of starting target cDNA is low. Ct below 29 indicates strong positive reactions, whereas Ct above 40 indicates negative reaction.

**■ Airborne and airbone *precaution***  
To be added later.

**■ Serology**  
To be added later.