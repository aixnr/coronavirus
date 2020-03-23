---
date: "2020-03-21T20:00:00-04:00"
title: "SARS-CoV-2/COVID-19"
last: "2020-03-23T00:50:00-04:00"
---

Welcome to this page, a collection of my notes on the coronavirus disease 2019 (**COVID-19**) and severe acute respiratory syndrome coronavirus 2 (**SARS-CoV-2**). This virus was known by its provisional name 2019 novel coronavirus (2019-nCoV). It is also known as the human coronavirus 2019 (hCoV-19), which is the ID that is now being used on GISAID EpiCoV<sup>TM</sup> database.

First, let's make it clear what this site is not.

1. This page {{<disclaimer>}} DOES NOT {{</disclaimer>}} and {{<disclaimer>}} WILL NOT {{</disclaimer>}} provide advice on medical procedures. Please talk to your physician.
2. The content that I wrote here {{<disclaimer>}} SHOULD NOT {{</disclaimer>}} be used to inform policies. Please study references cited here and please talk to experts.
3. The content I wrote on this page {{<disclaimer>}} IS NOT {{</disclaimer>}} peer-reviewed.

I created this site for mainly two reasons:

1. It has been a challenge to keep track of scientific discussion surrounding this coronavirus and past coronaviruses as well.
2. By making this note page public, I hope this small project could benefit people.

If you found anything (error, suggestion, papers, etc.) that you think I should include on this page, send me email `aizanfahri(at)gmail(dot)com` or tweet/dm me `@aixnr` or create a GitHub issue on `aixnr/coronavirus` ([link to repo here](https://github.com/aixnr/coronavirus)). Note that for the GitHub repo, I will not accept any pull requests. 

**Table of contents**:

1. [Key Facts](#key-facts)
2. [Virology](#virology)
3. [Immunology](#immunology)
4. [Pathology, Diagnostics, and Treatments](#pathology-diagnostics-and-treatments)
5. [Epidemiology](#epidemiology)
6. [Portals](#portals)
7. [Clinical Trials](#clinical-trials)
8. [Reagents](#reagents)
9. [Twitter Conversations](#twitter-conversations)

## Key Facts

| Topic | Description
| :---- | :----------
| Disease agent | Severe acute respiratory syndrome (SARS) coronavirus (CoV) 2, a coronavirus belonging to the betacoronavirus genus (Group 2 CoV). It is an enveloped, positive-sense, single-stranded RNA virus of zoonotic origin.
| Pandemic status | SARS-CoV-2 is the first coronavirus that reached the pandemic level. Previously, pandemics were mostly caused by influenza A virus (1918, 1957, 1968, and 2009).
| Treatment availability | Gilead Sciences’ **remdesivir** (adenosine nucleotide analog, interferes with vRNA pol), Abbvie's **lopinavir/ritonavir** (protease inhibitors). Both antiviral regiments were first designed for HIV/AIDS treatment, now being repurposed for SARS-CoV-2 treatment. An initial trial in China on lopinavir/ritonavir found that this regiment did not improve clinical outcomes, see Cao et al. 2020. An unofficial report from China claimed that a new drug developed by Japanese company, **favipiravir** (selective inhibition of vRNA polymerase) was effective against the SARS-CoV-2.
| Vaccine availability | See section [Clinical Trials](#clinical-trials)
| Official pandemic declaration | WHO declared pandemic on March 11th, 2020, 3 months after initial reports in Wuhan. Prior to that, WHO declared public health emergency on 30 Jan 2020.
| Date 100,000 cases reached | March 6th, 2020.
| Comparison: SARS-CoV (2003) | 8,098 cases were recorded globally, resulted in 774 deaths, and reported in 17 countries. Case fatality rate was 9.6%. It was not declared as pandemic.
| Comparison: H1N1 (2009) | Infected 11-21% of global population (700 million - 1.4 billion out of 6.8 billion), estimated to have caused 150-575k fatalities. 
| Average incubation period | Approximately 5 days.

## Virology

**■ Genomic organization**  
Positive-sense, single-stranded RNA. As for SARS-CoV-2, the genomic length is around 29 kilobases. The genome size of known coronaviruses ranges from 27 to 34 kilobases. For most coronaviruses, the first two open reading frames (ORFs), Orf1a and Orf1b encode for for viral replicase, while downstream mRNAs encode for structural proteins S, E, M, and N. They can also produce several accessory genes that are essential during replication ([Kopecky-Bromberg et al. 2006][vir_7]; [Fung & Liu 2019][vir_19]).

**■ Known animal reservoir**  
Coronaviruses are known to infect many species ([Lim et al. 2016][vir_1]), including bats, civets, cattle, and mice. The intermediate host for SARS-CoV (2003) was palm civet ([Wang et al. 2005][vir_6]). 

**■ Zoonotic origin of SARS-CoV-2**  
Currently, the scientific community suspects that the intermediate host for SARS-CoV-2 was either bat or pangolin ([Xiao et al. 2020][vir_8], preprint).

**■ Discovery of coronaviruses**  
The first coronavirus was discovered in late 1960s; HCoV-**229E** (1966) & HCoV-**OC43** (1967), see [Lim et al. (2016)][vir_1], **Table 1**. Seven CoVs are known to infect human; in addition to two strains above and the new SARS-CoV-2, there are **NL63** (2004) & **HKU1** (2005), only causing mild disease ([Fung & Liu 2019][vir_19]). MERS-CoV and SARS-CoV could result in severe disease.

**■ Host receptor(s)**  
Similar to SARS-CoV (2003), SARS-CoV-2 uses angiotensin-converting enzyme 2 (ACE2) human receptor to gain entry, as demonstrated in studies by [Hoffmann et al. (2020)][vir_2] and [Matsuyama et al. (2020)][vir_3]. Furthermore, both studies provided evidence that proteolytic maturation by transmembrane protease TMPRSS2 is crucial for maturation. Note that not all human coronaviruses use the same host receptor; HCoV-229E uses CD13 ([Yeager et al. 1992][vir_4]), MERS-CoV uses DPP4/CD26 ([Mou et al. 2013][vir_5]).

ACE2 is known to be expressed on ciliated epithelial cells in the upper and lower airway, as well as in type II pneumocytes ([Lukassen et al. 2020][vir_11], preprint). A study shows that ACE2 is expressed on mucosa of oral cavity ([Xu et al. 2020][vir_12]) and other organs (see **Table 1**).

**■ *In vitro* culture of SARS-CoV-2**  
Both Hoffmann et al. (2020) and Matsuyama et al. (2020) demonstrated high viral titer in Vero E6 cell line that expresses high level of TMPRSS2 (VeroE6/TMPRSS, ~10-fold higher RNA expression level of TMPRSS2). These studies, along with others in the past with SARS-CoV (2003) also demonstrated the use of Calu-3 cell line to culture the virus ([Tseng et al. 2005][vir_16])

**■ Viral life cycle**  
After host receptor recognition, binding, fusion, and uncoating into the host cell, coronavirus translates the replicase gene from the virion genomic RNA. The replicase polyproteins, pp1a and pp1b, are cleaved by internal proteases. Coronavirus viral proteins (including a number of the non-structural proteins) form replication-transcription complex (RTC) in the cytosol, proximal to the perinuclear region. See review by [de Wilde (2017)][vir_14] and [Fehr & Perlman (2015)][vir_15].

**■ Antigenic determinant**  
Protective antibodies are usually directed against viral protein that mediates entry into target host cell. For coronaviruses, that is the spike (S) protein. S protein is a trimeric protein. Before binding to host receptor (e.g. ACE2), it adopts metastable prefusion and undergoes dramatic structural rearrangement to fuse the viral membrane to the host cell membrane. S protein has two domains after proteolytic maturation: the **S1** domain which has the receptor-binding domain (RBD) and the **S2** domain which has the fusion peptide ([Walls et al. 2017][vir_9]). 

The crystal structure of SARS-CoV-2 spike protein has been solved through cryo-EM (SARS-CoV-2 reference genome Wuhan-Hu-1 at GenBank `MN908947`, resolution: 3.5 Å), see [Wrapp et al. (2020)][vir_10]. The authors mention that SARS-CoV-2 has higher binding affinity to ACE2 compared to the SARS-CoV (2003), about ~10--20 higher at ~ 15 nM affinity.

Concerning binding affinity, a recent study claims that the circulating SARS-CoV-2 is undergoing positive selection that could have increased its binding affinity to the ACE2 receptor by two magnitude (~ 0.11--0.13 nM, see **Figure 3** from [Ou et al. 2020][vir_13], preprint). Note that this claim is based on analytical model (molecular dynamics simulation), thus must be further tested by appropriate biological experiments.

**■ Antagonizing innate immunity**  
A study by [Kopecky-Bromberg et al. (2006)][vir_7] shows that the SARS-CoV N, Orf3b, and Orf6  proteins can interfere with interferon (IFN) activity. The authors show the mechanisms of interference through inhibition of IFN-β synthesis, inhibition of IRF-3 and NF-kB functions, blocking the ISRE promoter, and blocking the translocation of STAT1. For a more detailed review, see [Fung & Liu (2019)][vir_19], **Figure 8**.

**■ Proteolytic processing**  
Proteolytic processing is required for the S protein to become infectious, resulting in two domains after cleavage: S1 (bulb) and S2 (stalk). Studies suggest that this process happens prior to or during the entry of coronavirus into target host cell ([Matsuyama et al. 2010][vir_17]), in contrast to majority of class I viral fusion proteins that are processed during virus assembly or following release from infected host. A study ([Belouzard et al. 2009][vir_18]) looking at the SARS-CoV suggests that proteolytic processing of SARS-CoV happens at 2 sites: at the boundary of S1 and S2 domains (S1/S2 site) and also within the S2 domain (S2').

**■ *In vivo* animal model**  
A recent study established an *in vivo* animal model for studying the diseased caused by SARS-CoV-2 infection ([Munster et al. 2020][vir_20], preprint). To establish an animal model, the disease in said animal has to recapitulate the phenotype as observed in human. The authors inoculated a total dose of 2.6x10<sup>6</sup> TCID<sub>50</sub> of SARS-CoV-2 (WA1-2020 isolate) via combination of intratracheal, intranasal, ocular, and oral routes. They detected high viral loads in respiratory samples, but noted some inconsistencies between sampling days and tissues being sampled. The authors conclude that this animal model recapitulates COVID-19 based on their observation of viral replication, shedding, histological features, and serology.

**■ Incubation period**  
To be added later.

**■ Persistence outside host**  
To be added later.

**■ Shedding routes**  
To be added later, see Wu et al. (2020, The Lancet)

[vir_1]:https://doi.org/10.3390/diseases4030026
[vir_2]:https://doi.org/10.1016/j.cell.2020.02.052
[vir_3]:https://doi.org/10.1073/pnas.2002589117 
[vir_4]:https://doi.org/10.1038/357420a0
[vir_5]:https://doi.org/10.1128/JVI.01277-13
[vir_6]:https://dx.doi.org/10.3201/eid1112.041293
[vir_7]:https://doi.org/10.1128/JVI.01782-06
[vir_8]:https://doi.org/10.1101/2020.02.17.951335
[vir_9]:https://doi.org/10.1073/pnas.1708727114
[vir_10]:http://doi.org/10.1126/science.abb2507
[vir_11]:https://doi.org/10.1101/2020.03.13.991455
[vir_12]:https://doi.org/10.1038/s41368-020-0074-x
[vir_13]:https://doi.org/10.1101/2020.03.15.991844
[vir_14]:https://doi.org/10.1007/82_2017_25
[vir_15]:https://doi.org/10.1007/978-1-4939-2438-7_1
[vir_16]:https://doi.org/10.1128/JVI.79.15.9470-9479.2005
[vir_17]:https://doi.org/10.1128/JVI.01542-10
[vir_18]:https://doi.org/10.1073/pnas.0809524106
[vir_19]:https://doi.org/10.1146/annurev-micro-020518-115759
[vir_20]:https://doi.org/10.1101/2020.03.21.001628

## Immunology

**■ Antibody response**  
Initial report from [Zhao et al. (2020, preprint)][imm_1] indicates that the plasma IgM peaked, on average, around day 8--14. **Figure 2** shows concomitant decrease in detected vRNA as the samples tested positive for total Abs went up. [Zhang et al. (2020, preprint)][imm_2] reported peak plasma IgM in week 2 (consistent with Zhao et al. 2020), with plasma IgG peaked in week 4. Another study noted in non-human primate noted that the animals had seroconverted to SARS-CoV-2 spike protein by day 10, and the neutralizing responses started to appear on day 10 as well ([Munster et al. 2020][vir_20], preprint).

A study to look at the possibility of re-infection was carried out in non-human primate rhesus macaques ([Bao et al. 2020][imm_6], preprint). In this study, four monkeys were challenged with 1x10<sup>6</sup> TCID<sub>50</sub> SARS-CoV-2 via intratracheal route and re-challenge was done via the same route with the same dose on day 28 after the primary infection. The authors show that in re-challenged animals, no viral replication was detected in tissues, therefore providing the evidence that primary exposure (in the case of infection) to SARS-CoV-2 could protect from subsequent exposure.

**■ ASCs/PBs response**  
A study suggests the peak antibody-secreting cells (ASCs, also termed plasmablasts, PBs; gated on CD27<sup>+</sup>CD38<sup>+</sup>) on day 8 following symptom onset ([Thevarajan et al. 2020][imm_3]).

**■ Antibody cross-reactivity**  
To be added later.

**■ Durability of antibody levels**  
A study from previous SARS-CoV (2003) outbreak provided evidence that the antigen-specific IgG antibodies against the SARS-CoV (ELISA with inactivated preparation of whole-virus lysate) were maintained for an average of 2 years ([Wu et al. 2007][imm_4]). Another study looked at the profile of IgG, IgM, and IgA antibodies againt SARS-CoV (2003) nucleocapsid protein ([Woo et al. 2004][imm_5], **Figure 1**)

**■ ADE pattern**  
The involvement of antibody-dependent enhancement (ADE) has not yet been thoroughly studied yet.

**■ OAS pattern**  
The involvement of original antigenic sin (OAS) has not yet been thoroughly studied yet. 

[imm_1]:https://doi.org/10.1101/2020.03.02.20030189
[imm_2]:https://doi.org/10.1101/2020.03.12.20035048
[imm_3]:https://doi.org/10.1038/s41591-020-0819-2
[imm_4]:https://doi.org/10.3201/eid1310.070576
[imm_5]:https://doi.org/10.1128/CDLI.11.4.665-668.2004
[imm_6]:https://doi.org/10.1101/2020.03.13.990226

## Pathology, Diagnostics, and Treatments

**■ Symptoms**  
To be added later.

**■ Disease phenotype & physiology**  
To be added later.

**■ Dynamics of viral load in infected individuals**  
As of writing (23 Mar 2020), I found two observations that do not quite agree to one another. An observation on 76 of infected individuals in China (First Affiliated Hospital of Nanchang University) looked at the viral load from nasopharyngeal swabs ([Liu et al. 2020][path_01], **Figure A**). The authors mention that the mean viral load of severe cases was ~60x higher than that of mild cases. Further, they noted that in severe cases the patients had detectable viral load at or beyond day 10 post-onset.

However, another observation that looked at 5,830 of infected individuals in Lombardy demonstrated that the viral load (nasal swabs) between symptomatic and asymptomatic individuals were not statistically different ([Cereda et al. 2020][path_02], preprint, **Figure 4**).

**■ Typical disease progression**  
To be added later.

**■ Common diagnostic procedure**  
To be added later.

**■ Treatment**  
To be added later, see Gordon et al (2020, bioRxiv), and editorial on Science AAAS.

**■ Collection of guidelines**  
I received a list of links to clinical guidelines from a friend who is currently working as a physician. These resources would be most useful for people in the frontline.

| Type | Author(s) | Date | Description and link
| ---- | :-------- | ---- | :-------------------
| Presentation file | Dr. Suresh Kumar | 19 Mar 2020 | [Clinical Updates on COVID-19 No.1/2020](https://docs.google.com/presentation/d/10cx6fLSggvyIX9SjyiG2I9yNEU99oBFmsB8d_SzJyM8)
| Training materials | WHO | -- | [Coronavirus disease (COVID-19) training: Online training](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/training/online-training)
| Handbook | Zhejiang University School of Medicine | -- | [Handbook of COVID-19 Prevention and Treatment](https://covid-19.alibabacloud.com/)
| Handbook | ISID | Feb 2020 | [Guide to Infection Control in the Healthcare Setting](https://isid.org/guide/pathogens/covid19/)
| Journal article | Dr. Srinivas Murthy | 11 Mar 2020 | [Care for Critically Ill Patients With COVID-19](https://jamanetwork.com/journals/jama/fullarticle/2762996)
| Presentation file | McKenna | 14 Mar 2020 | [Royal London Hospital COVID Intubation SOP](https://www.dropbox.com/s/t4oqkak40m5s717/COVIDintubationSOP2.2.pptx)
| Handbook | European Society of Cardiology | -- | [COVID-19 and Cardiology](https://www.escardio.org/Education/COVID-19-and-Cardiology)
| Handbook | American College of Cardiology | -- | [COVID-19 Clinical Guidance For the Cardiovascular Care Team](https://www.acc.org/~/media/Non-Clinical/Files-PDFs-Excel-MS-Word-etc/2020/02/S20028-ACC-Clinical-Bulletin-Coronavirus.pdf)
| Journal article | Matthay et al. | 20 Mar 2020 | [Treatment for severe acute respiratory distress syndrome from COVID-19](https://doi.org/10.1016/S2213-2600(20)30127-2)

If you are qualified and certified medical personnel, please discuss with your advisor. I hope the resources listed here could help.

[path_01]:https://doi.org/10.1016/S1473-3099(20)30232-2
[path_02]:https://arxiv.org/abs/2003.09320

## Epidemiology

**■ Seasonality of human coronaviruses**  
A study on the seasonality of hCoVs (OC43, NL63, 229E, and HKU1) in the United States found evidence of seasonality of human coronaviruses in human circulation, generally peaking in January ([Killerby et al. 2018][epi_1], **Figure 1**; see also [Gaunt et al. 2010][epi_2]). This is the expected trend for respiratory viruses where they tend to cluster in period known as the winter respiratory season (November--March). To learn more about seasonality of infectious diseases, head over to this story on Science AAAS: [Why do dozens of diseases wax and wane with the seasons—and will COVID-19?](https://www.sciencemag.org/news/2020/03/why-do-dozens-diseases-wax-and-wane-seasons-and-will-covid-19)

**■ Serial interval**  
To be added later.

**■ Basic reproductive number**  
To be added later.

**■ Infection Modeling**  
To be added later.

**■ How social distancing would help**  
To be added later.

[epi_1]:https://doi.org/10.1016/j.jcv.2018.01.019
[epi_2]:https://doi.org/10.1128/JCM.00636-10

## Portals

| Portal | Description
| ------ | :---------
| [Nextstrain Narratives][p_1] | Narratives are a method of data-driven storytelling. They allow authoring of content which is displayed alongside a view into the data.
| [Our World In Data: COVID-19][p_2] | The purpose of this article on COVID-19 is to aggregate existing research, bring together the relevant data and allow readers to make sense of the published data and early research on the coronavirus outbreak.
| [WHO COVID-19 Technical Guidelines][p_3] | Guides for testing SARS-CoV-2 in suspected human cases and all related biological assays.
| [SARS-CoV-2/COVID-19 Global Cases][p_4] | An interactive web-based map to track cases of the virus around the world, developed at the John Hopkins University.
| [Nextstrain / ncov][p_5] | Nextstrain portal for the SARS-CoV-2/COVID-19, developed by the Bedford lab.
| [Worldometers][p_6] | Confirmed Cases and Deaths by Country, Territory, or Conveyance. 
| [NCBI LitCovid][p_7] | LitCovid is a curated literature hub for tracking up-to-date scientific information about the 2019 novel Coronavirus.

[p_1]:https://nextstrain.org/#narratives
[p_2]:https://ourworldindata.org/coronavirus
[p_3]:https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance/laboratory-guidance
[p_4]:https://coronavirus.jhu.edu/map.html
[p_5]:https://nextstrain.org/ncov
[p_6]:https://www.worldometers.info/coronavirus/#countries
[p_7]:https://www.ncbi.nlm.nih.gov/research/coronavirus/


## Clinical Trials

| Type | Location | Sponsor | Intervention/Treatment | Study Identifier
| ----- | -------- | ------- | ---------------------- | ----------------
| Interventional | Washington, USA  | NIAID | mRNA-based vaccine of SARS-CoV-2 (2019-nCoV) spike protein, intramuscular route | [NCT04283461][sid_1]
| Observational | Shanghai, China | Shanghai Public Health Clinical Center | SARS-CoV-2 inactivated convalescent plasma | [NCT04292340][sid_2]
| Interventional | Hong Kong | The University of Hong Kong | RCT on lopinavir/ritonavir, ribavirin, and IFN-1β against 2019n-CoV infection | [NCT04276688][sid_3]
| Interventional | United States (multi-center trial) | NIAID | RCT on remdesivir; a single diastereomer monophosphoramidate prodrug designed for the intracellular delivery of a modified adenine nucleoside analog GS-441524 | [NCT04280705][sid_4]

[sid_1]:https://clinicaltrials.gov/ct2/show/NCT04283461
[sid_2]:https://clinicaltrials.gov/ct2/show/NCT04292340
[sid_3]:https://clinicaltrials.gov/ct2/show/NCT04276688
[sid_4]:https://clinicaltrials.gov/ct2/show/NCT04280705


## Reagents

| Type | Vendor | Item | BSL | Cat ID 
| ---- | ------ | ---- | --- | -----
| Cell line | ATCC | VERO clone E6 grivet kidney epithelial | 1 | [CRL-1586][r_2]
| Protein Ag | The Native Antigen Company | SARS-CoV-2 spike glycoprotein (S1), HEK293 | 1 | [REC31806-100-HRP][r_3]
| Protein Ag | The Native Antigen Company | SARS-CoV-2 spike glycoprotein (S2), HEK293 | 1 | [REC31807-100-HRP][r_4]
| Kit | Sino Biological | SARS-CoV-2 antigen detection kit | 1 | [SARS-CoV-2][r_5]

[r_1]:https://www.atcc.org/products/all/CRL-4051.aspx
[r_2]:https://www.atcc.org/Products/All/CRL-1586.aspx
[r_3]:https://thenativeantigencompany.com/products/sars-cov-2-spike-glycoprotein-s1-sheep-fc-tag-hek293/
[r_4]:https://thenativeantigencompany.com/products/sars-cov-2-spike-glycoprotein-s2-sheep-fc-tag-hek293/
[r_5]:https://www.sinobiological.com/sars-cov-2-antigen-detection-assay.html

## Twitter Conversations

* Prof. Akiko Iwasaki on [the differences between coronaviruses and flu](https://twitter.com/VirusesImmunity/status/1238475009712160769).
* Dr. Patrick Wyman on [the fall of Roman Empire](https://twitter.com/Patrick_Wyman/status/1238138473124524033), which may have been caused by smallpox but no one knows for sure.
* Zining Wang on the [relationship between Italy and China and why China is sending their healthcare workers to Italy to help with the SARS-CoV-2 outbreak](https://twitter.com/ZiningRW/status/1238334806821224449).
* Dr. Trevor Bedford on [modeling the surge of SARS-CoV-2/COVID-19 cases in the United States](https://twitter.com/trvrb/status/1238643280679563265).
* Prof. Carl Bergstrom [discussing "flatten the curve" dataviz](https://twitter.com/CT_Bergstrom/status/1235865328074153986).
* Dr. Francois Balloux on [pandemic response modeling](https://twitter.com/BallouxFrancois/status/1238837158007447558).
* Dr. Florian Krammer on [the possibility of re-infection and why tests after recovery does not mean what you think](https://twitter.com/florian_krammer/status/1233338746789036032).
* Nvidia GeForce [calling games to support folding@home project](https://twitter.com/NVIDIAGeForce/status/1238496311776653312). More information [on this Reddit thread at r/pcmasterrace](https://www.reddit.com/r/pcmasterrace/comments/fhb5e4/coronavirus_specific_gpu_projects_are_now/).
* Dr. Florian Krammer, [with his tweetorial on serology paper his lab recently published on MedRxiv](https://twitter.com/florian_krammer/status/1240432285184405505).
* Dr. Kristian G. Andersen on [rapid diagnostic tests (RDTs) and serology tests for COVID-19](https://twitter.com/K_G_Andersen/status/1241919845945368577).
* Dr. Elisabeth Bik on [the study claiming hydroxychloroquine is effective to treat COVID-19](https://twitter.com/MicrobiomDigest/status/1241429544847863808).