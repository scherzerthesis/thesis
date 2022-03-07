---
title: Dissertation
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2022-03-07'
author-meta:
- Michael
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Dissertation" />
  <meta name="citation_title" content="Dissertation" />
  <meta property="og:title" content="Dissertation" />
  <meta property="twitter:title" content="Dissertation" />
  <meta name="dc.date" content="2022-03-07" />
  <meta name="citation_publication_date" content="2022-03-07" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Michael" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <link rel="canonical" href="https://scherzerthesis.github.io/thesis/" />
  <meta property="og:url" content="https://scherzerthesis.github.io/thesis/" />
  <meta property="twitter:url" content="https://scherzerthesis.github.io/thesis/" />
  <meta name="citation_fulltext_html_url" content="https://scherzerthesis.github.io/thesis/" />
  <meta name="citation_pdf_url" content="https://scherzerthesis.github.io/thesis/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://scherzerthesis.github.io/thesis/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://scherzerthesis.github.io/thesis/v/852523248b1b0d8eaf8ca6a0e57ff961b5320e2e/" />
  <meta name="manubot_html_url_versioned" content="https://scherzerthesis.github.io/thesis/v/852523248b1b0d8eaf8ca6a0e57ff961b5320e2e/" />
  <meta name="manubot_pdf_url_versioned" content="https://scherzerthesis.github.io/thesis/v/852523248b1b0d8eaf8ca6a0e57ff961b5320e2e/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://scherzerthesis.github.io/thesis/v/852523248b1b0d8eaf8ca6a0e57ff961b5320e2e/))
was automatically generated
from [scherzerthesis/thesis@8525232](https://github.com/scherzerthesis/thesis/tree/852523248b1b0d8eaf8ca6a0e57ff961b5320e2e)
on March 7, 2022.
</em></small>

## Authors



+ **Michael**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [johndoe](https://twitter.com/johndoe)<br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>



## Chapter One: Introduction {.page_break_before}


**NSCLC**

Lung cancer is a global menace on human health. The historic consumption of cigarette smoke has caused lung cancer to be the most common and deadly form of cancer in both men and women. Fortunately, smoking-rates have decreased in the past 30 years with lung cancer rates also on the decline. However, even if cigarette consumption were eradicated, lung cancer would still significantly affect human health. It is estimated that approximately 25% of all lung cancer cases arise in never smokers [@pmid:23714547]. Secondary causes of lung cancer include Radon exposure, high-heat cooking, family history, air pollution [@pmid:27174888]. An individual's risk of lung cancer also increases with age due to a decreased ability of the immune system to combat early neoplasms[@pmid:22974775].

Lung cancer can be classified broadly into two major histological types that were named based on how the malignant cells look under a microscope: Non-small Cell Lung Cancer (NSCLC) and Small Cell Lung Cancer (SCLC). NSCLC is the most common type and represents 75% of lung cancer cases and is the most common subtype for patients who have never smoked cigarettes. Within NSCLC, tumors are further characterized based on histological architecture, anatomical location, cell-of-origin, as well as genomic alteration[@pmid:18815398]. For example, lung adenocarcinoma is the most common subtype and is characterized by glandular and papillary structures while squamous cell lung carcinoma characterized by keratin-pearls[@pmid:15059877] .Moreover, adenocarcinomas arise from alveolar-type-2 (AT2) cells in the distal lung and alveoli and are typified by genomic alterations throughout the MAPK pathway, such as EGFR, KRAS, BRAF, PI3K [@pmid:32747478; @pmid:11751630]. Squamous cells carcinoma likely arise from basal cells and typically harbor SOX2 gene amplification [@pmid:27308419; @pmid:30332632].

The 5-year survival rate for patients with lung cancer was 25% in 2020 but varies depending on stage of disease at time of diagnosis [@doi:10.3322/caac.21654]. Although patient survival has improved over the past few decades due to improved targeted and immune therapies, the still poor prognosis reflects a need to better understand the molecular mechanisms underlying lung tumor progression, maintenance and response to targeted- or immune-therapy (reword).

Currently, the standard of care for LUAD are combination of several conventional chemotherapeutic agents, such as Cisplatin, Carboplatin, Paclitaxel, or Pemetrexed[@pmid:32548736]. Fortunately for patients who have been identified to have EGFR, ALK, ROS, TRK, or BRAF (V600E) genetic alternations significantly benefit from pathway-targeted therapies[@pmid:27283860; @pmid:24651011]

Of the solid malignancies, lung cancer accounts for the greatest number of new cancer diagnoses worldwide with an estimated 2.1 million new cases in 2018 [@doi:10.3322/caac.21654]. It is the most commonly diagnosed cancer in men, and second most commonly diagnosed cancer in women after breast cancer. Unfortunately, this particularly insidious disease is the leading cause of cancer related death in men and often the leading cause of death in women each year, accounting for 1.8 million deaths last year. In the United States, these grim statistics have shown little improvement in the last decade. Kentucky bears the highest lung cancer incidence rate and this outcome is correlated with its top ranking smoking rate among the population. Lung cancer is a disease of aging and commonly affects people over the age of 60. Data provided by the National Cancer Institute and the Surveillance, Epidemiology, and End Results program indicate that patients in which their disease is detected early, while the tumor is confined to the primary location and has not disseminated to the adjacent lymph nodes have a five-year survival rate of approximately 57.4% [@pmid:27740970]. Once the cancer has spread to adjacent regional lymph nodes, this survival rate drops markedly to 30.8%. Tragically, those diagnosed with late stage and distant metastatic disease have only a 5.2% chance of survival past five years. It is a grim fact that a majority of new patients that will be diagnosed with lung cancer, around 80%, will be informed that they have regional or distant disease. Metastatic disease is the true killer in lung cancer~~. Non-small cell lung cancer is also subdivided into several histological subtypes including adenocarcinoma, a disease arising from the distal glandular epithelial lining of the bronchi, squamous cell carcinoma, arising from the more proximal squamous epithelium of the bronchus, and large cell carcinoma [@pmid:24163741].  This means that from the time of oncogenic transformation that results in a tumor cell able to continuously proliferate and evade immune detection to the time of a detectable tumor mass by chest radiograph can be over a decade. For the vast majority of this time, patients do not experience pain from the growing mass and do not experience other related symptoms specific to the 3 disease. Often the first symptoms experienced by the patient are associated with metastatic dissemination such as pain associated with tumor invasion into the chest wall, liver capsule, or bone structure, or a number of other paraneoplastic syndromes. This delays the critical time to diagnosis for the patient, leading to poor outcomes, but also allows ample time for mutated cells to adapt and modulate a local tumor microenvironment that is conducive to support tumor growth, progression, and metastasis.

**BRAF (V600E) signaling and cooperating genetic events to LUAD initiation and progression**

Due to the strong association between lung adenocarcinoma formation and mutational activation of the MAPK-pathway, many labs have generated genetically-engineered mouse models (GEMMs) that harbor conditionally-activated alleles of either KRAS (G12D) or BRAF(V600E). Expression on BRAF (V600E) in the Surfactant-Protein C expression cells (alveolar type 2 pneumocytes) elicits benign tumor formation that fail to progress to malignant lung adenocarcinoma. It is hypothesized that the cell cycle arrest is dependent on the tumor suppressors P53, and CDKN2A, as loss of either P53 or CDKN2A allows tumors to progress to malignant and deadly lung adenocarcinoma. Also, activation of WNT signaling and PI3K signaling similarly allow BRAF (V600E) adenomas to progress to adenocarcinoma. These observations are in concordance to the &quot;multiple-hit&quot; hypothesis. This hypothesis states that cancers do not arise from single mutagenic events, but are the consequence of sequential assaults on the genome that activate more than one oncogenic pathway. These multiple genetic hits allow cells to adopt traits to form cancer, which is coined by Bob Weinberg and Douglas Hanahan as the &quot;Hallmarks of Cancer&quot;. The traits include suppression of apoptosis, active proliferation, altered metabolism, changes in cell identity, and forming blood-vessels (latest Hanahan and Weinberg). BRAF(V600E) expression alone is sufficient to activate many of the hallmarks of cancer, but additional pathways need to be activated to form deadly metastasis.

Great effort has elucidated the proto-oncogenes that drive cancer formation when mutated, such as _MYC_, _RAS_, _PI3K_, and others. Yet we still do not fully understand the mechanistic details that determine how genes cooperate to drive cancer.

**MAPK Signaling**

Normal activation of the MAPK pathways begins with extracellular ligands binding to Receptor-Tyrosine Kinases (RTKs). This leads to the association of the G-protein coupled RAS with GTP, which activates RAS. GTP-loaded RAS recruits and activates RAF kinases (ARAF, BRAF, CRAF) which then phosphorylates and activates MEK kinases which then phosphorylates and activates ERK kinases. This ultimately leads to the activation of a suite of cellular processes that are required for proliferation, differentiation, and cell survival. Therefore, activating mutation in this pathway, from RTKs to kinases, serve to keep the pathway in a constitutively active state. This active state drives many of the hallmarks of cancer that is required for tumor formation. It is important to note that oncogenic activation of the MAPK pathway differs from normal ligand-mediated pathway activation. For example, mitogens, such as EGF, only transiently activate the pathway even with constant ligand stimulation. This immediate and strong spike in pathway activation is integrated by various biological processes in the cell that results in transcription of certain target genes. In contrast, oncogenic signaling thru mutational activation of BRAF(V600E) for example results in constant kinase signaling that is integrated differently than normal pathway stimulation. Thus, an oncogene-specific transcriptional program is activated.

The importance of this pathway is reflected in the strong anti-tumor responses that are seen when small molecule inhibitors are used to target various molecules involved in the MAPK pathway. For example, Dabrafenib and Trametinib, inhibitors of BRAF and MEK kinases, respectfully, are used in patients that harbor BRAF(V600E) melanomas and lung cancers, both offering a clinical benefit (refs). Although there is strong pre-clinical and clinical evidence that BRAF+MEK blockade can lead to tumor regression, not all patients respond to treatment (ref). Therefore, to see a complete response, multiple pathways need to be targeted.

**Genetically engineered mouse models (GEMMs)**

Genetically-Engineered mouse models (GEMMs) of human cancer have allowed for the reproducible analysis of cancer biology driven by specific mutations that are often found in cancer patients. These models are useful for understanding the molecular mechanisms that drive tumor formation but also serve as a platform for testing tumor responses to targeted- or immune- therapies. Early mouse models utilized either the inherent tumor susceptibility of inbred strains of mice, such as FVB , or carcinogen-induced models such as UV, Urethane, or DMBA treatment. With the ability to genetically manipulate embryonic stem-cells (ES cells) came the development of mice with mutations engineered to spontaneously form neoplasms without the need for carcinogen treatments. Genetic knockouts or over-expression can lead to embryonic lethality depending upon the specific role of the manipulated gene, therefore conditional gene manipulation was developed to allow for temporal control thus overcoming the issues with embryonic lethality or other developmental defects.

The most common conditional system relies on chemically inducible transcription factors, such as tetracycline-dependent regulatory system to relies on the inoculation of tetracycline into the body to bind to a tetracycline-trans-activator to turn on gene expression. More recently, Cre-Lox recombination strategies have been utilized to get more cell type specific control. In this system, genes of interested are constructed to contain LoxP-sites that flank a particular genetic element and upon delivery of Cre-recombinase the DNA sequence in between LoxP sites are excised. With this approach, one can knockout a gene by engineering LoxP sites around critical exons, or one could turn on gene transcription by flanking a strong stop signal such as a polyadenylation sequence upstream of a gene-of-interest sequence such as KRAS G12D.

Genetically engineered mouse models of human cancer are important preclinical models, because they resemble the physiological environment of tumor growth in which tumors arise as progeny from a single initiating cell. These tumors can approximate the genetic alterations, transcriptional landscape, histology, and responsive disposition or lack therefore, seen in human cancers(cite). However, these model often take months to develop tumors and compound genetic alterations take time to develop. Later in this thesis, we will utilize TUBA-SEQ to both quantify tumor burden and cooperation of BRAF(V600E) with other common alterations in lung cancer.

**Conditional mouse models of BRAF (V600E) lung cancer**

Our lab has previously developed a conditional mouse model of BRAF (V600E) human lung cancers. In the _Braf(CAT)_ model, normal BRAF is expressed from a conditional allele prior to Cre-mediated recombination . LoxP sites flank human _BRAF_ cDNA encoding normal _BRAF_ exons 15-18. Downstream of the LoxP sites is the mutant exon 15 that encodes the murine equivalent of the T1799A mutation that gives rise to the BRAF (V600E) onco-protein. Downstream of the mutant exon there is a P2A element and a CAAX-tagged _TdTomato_. Therefore, after Cre-mediated recombination, the BRAF (V600E) oncoprotein and fluorophore TdTomato is expressed at normal levels.

**Talk here about the prevalence of mutations in the egfr-ras-raf-mek-erk pathway**

**Identification of this pathway as central to luad tumorigenesis**

**Development of gemms to study BRAF^V600E^**

**Proliferation arrest by this model**

**How does p53 loss lead to sustained wnt-signalling? Do dominant negative recapitulate?**

RAS-RAF-MEK-ERK signaling

Talk about the details of raf activation and subsequent regulation of important cellular processes

**P53- mediated tumor suppression**

In biology, there are highly conserved pathways that control a bewildering amount of cellular processes that are both dependent and independent of each other, such as NOTCH- or WNT- signaling. The same could be said about P53. At the time of writing this dissertation, there are approximately 105,000 manuscripts on PUBMED that mention P53. P53 is so well studied because of both its apparent role in tumor suppression, but also because it is the most frequently altered gene in human cancer.

P53 is a transcriptional factor that has a DNA-binding domain that specifically recognizes two decameric half-sites. P53 also contains two N-terminal transactivation domains and a C-terminal oligomerization domain that are critical for P53-target gene activation. Central to the ability of P53 to induce transcriptional activation is tetramerization. Thus, if one or more P53 proteins in the complex is compromised in transactivation or DNA binding, transcriptional activity is compromised. Therefore, if one copy of P53 is mutated, the organism&#39;s ability to suppress tumor formation is compromised.

The importance of P53 is best demonstrated in people, and mice, that have just one mutated copy of P53. In humans with the familial- inherited Li-Fraumeni syndrome, in which they have one or more mutations in p53 are almost certain to develop cancer early on and throughout their life. Similarly, mice lacking two function P53 genes are prone to leukemias and lymphomas and have a shortened lifespan due to cancer incidence.

The most well-known cellular functions of P53 include its ability to induce cell-cycle arrest in response to DNA damage. Many stress signals, including oncogene activation has been shown to stimulate a reversible or irreversible cell cycle arrest. However, the strength of P53 induced cell cycle arrest or apoptosis is likely cell type- and cellular stress- specific.

Once a cell encounters a stressor such as DNA damage or oncogene activation, P53 is stabilized and accumulates in the nucleus to activate a suite of target genes that can lead to a number of cellular phenotypes, such as cell-cycle arrest or apoptosis.

P53 was originally thought to be an oncogene as P53 is accumulated in many human tumors which is not common in normal tissues. Moreover, ectopic expression of a P53 cDNA was found to aide in the transformation of primary cells induced by RAS. However, early studies erroneously used mutated P53 instead of wild-type leading to the misclassification of P53 as an oncogene. We known know P53 suppresses cell growth and transformation.

Often times, P53 is mutated in the DNA-binding domain at sites commonly referred to as &quot;hotspots&quot; due to there extraordinary frequency. These hotspot mutations poison the ability of p53 to bind DNA therefore blocking its function. Interestingly, since one mutated P53 can disrupt the entire P53 tetramer complex, a single mutation can exert dominant-negative effects by inhibiting the normal tumor suppressive functions of P53. Although one mutant P53 allele is enough to compromised transcriptional activity, there is still selective pressure to lose the other wild -type copy. Loss of hemizygosity implies there is still residual tumor suppression in the presence of a wild-type P53 allele.

Early on in P53 studies, there were reports of certain P53 mutations having a &quot;gain-of-function&quot; (GOF) effect. For example, Li-Fraumeni patients with certain missense mutations in P53 would develop tumors earlier than Li-Fraumeni patients with loss-of-function (LOF) mutations [@pmid:18511570]. Furthermore, there were experimental cell biology studies that would express mutant-p53 in P53-null cells and demonstrate enhanced tumorigenic potential [@pmid:32404993]. Further evidence for GOF mutant-P53 in mice indicated that missense mutant P53 induced different cancer types and enhanced metastasis than LOF P53 [@pmid:15607980]. Furthermore, many groups have shown mutant-p53 can alter signal transduction affecting chemoresistance and altering metabolism.

The cellular mechanisms that GOF P53 are involved in are also well-characterized but context-dependent. For example, in Pancreatic cancers driven by KRAS(G12D) Mutant P3 interacts with CREB to induce FOXA1 transcription which enhances Beta-Catenin signaling to augment liver metastasis [@pmid:33839689].



## Chapter Two {.page_break_before}


**Quantitative tumor burden and small library screen using TUBA-SEQ**

Genetic sequencing has allowed for the unbiased identification of genes that are mutated in human cancer. The wealth of knowledge gained from such large-scale sequencing endeavors has revealed actionable mutations that can be targeted with small molecules. However, in highly mutated cancers, such as melanoma and lung cancer, recurrent mutations are not necessarily predictive of biological importance. To better understand the importance of candidate tumor suppressors or oncogenes, researchers exploit tumor cell lines and GEMMs to identify bona-fide genetic drivers of cancer. However, these systems are suboptimal, as they are either not physiologically relevant (tissue culture) or are not scalable to determine the effect of many mutations (GEMMs).

Recently, Monte Winslow and his lab at Stanford University has developed **Tu** mor- **Ba** rcode **Seq** uencing (TUBA-SEQ), a rapid, multiplexed, quantitative assay for analyzing the contribution of tumor-suppressor loss _in vivo_. This technique works by delivering a uniquely barcoded lentiviral endoing Cre recombinase, to activate Cre-mediated oncogenes, and a guide RNA, to inactivate a single tumor suppressor gene. Therefore, each tumor will be driven by the same oncogene, but will have different tumor suppressors inactivated. After a period of time (6-24 weeks), tissue will be harvested for whole-lung DNA extraction and targeted DNA-sequencing performed to quantify relative tumor size to spike-in controls. Therefore, contribution of a single tumor suppressor can be quantified in single animal. Here, we explore the contribution of 11 tumor suppressor genes and 5 controls in the context of our BRAF (V600E)- driven lung tumor models.

The initiation of lung tumors with pools of barcoded Lenti-sgRNA/Cre viral vectors 96 enables the generation of many tumors of different genotypes in parallel. All neoplastic cells 97 within each clonal tumor have the same two-component barcode, in which an sgID region 98 identifies the sgRNA and a random barcode (BC) is unique to each tumor. Thus, high-throughput 99 sequencing of the sgID-BC region from bulk tumor-bearing lungs can quantify the number of 100 neoplastic cells in each tumor of each genotype(28). Previous Tuba-seq studies quantify tumor 101 suppressor effects and their interaction with other tumor suppressor genes, focusing only on 102 comparisons within mice(28-30). Comparisons of tumor distributions across mice are more 103 challenging and required improvements in accuracy as well as new analytical methods. Winslow 2021

Results

**TUBA-SEQ to uncover the contribution of tumor suppressor loss on BRAF (V600E) lung tumors**

Oncogenic BRAF (V600E) is a major driver in lung adenocarcinoma. However, mouse models with activation of BRAF (V600E) only lead to benign tumorigenesis (cite). Although it is well known that activation of WNT and PI3k signaling, as well as lost of _Trp53_ and _Cdkn2a_ genes allow BRAF (V600E) benign lung tumors to progress to malignant disease, we wanted to systematically test a variety of known tumor suppressors in lung adenocarcinoma. Furthermore, we do not know the size of BRAF(V600E) adenomas. Prior to TUBA-SEQ, it was very difficult to accurately determine the size of BRAF(V600E) adenomas. Based on population doublings, as well as cross sections of BRAF (V600E) tumors in histological sections, it is estimated that BRAF(V600E)-driven lung adenomas grow about 15-20 populations doublings and reaching a size of 1mm3. (cite) With TUBA-SEQ, we can more accurately discern the absolute size of BRAF(V600E) lung adenomas in almost every tumor in all animal subjects. Given the theory that BRAF-(V600) induces growth arrest after an initial burst of neoplastic growth, it would be of interest to know if all tumors grow to a predetermined and absolute size, or if there is a spectrum of tumor sizes that are determined by extrinsic factors such as proximity to blood vessels or certain stromal cells.

In determine the size of BRAF (V600E) tumors and the contribution of 11 tumor suppressor genes (_Trp53, Rb1, Cdkn2a, Apc, Rbm10, Stk11, Setd2, Arid1a, Atm, Keap1, Smad4)_ on BRAF (V600E) lung tumorigenesis, we obtained tittered barcoded-lentiviral plasmids that encode Cre-recombinase as well as a sgRNA that inactivates one of eleven tumor suppressors common in lung adenocarcinoma. All genes tested putative tumor suppressor genes commonly identified as lost in human lung cancer patients. Each lentiviral solution contained ~1000 individually barcoded lentiviruses. We infected both _LSL-Cas9_ and _CAS9-_deficient mice in order to determine the contribution of genetic manipulation and/or deletion of the targeted gene. Mice meant to be analyzed after 8 weeks received a viral titer of 1x10^5 while mice mean to be analyzed after 16 weeks received a viral titer of 1x10^4. After euthanasia, lungs were collected for genomic DNA extraction and barcode amplification and sequencing libraries were generated and sequenced. Before genomic extraction and library preparation, a known quantity of known-barcoded cells was added in order to benchmark sequencing reads to a known cell number.

Gross histologic images of experimental lungs are show an increase in tumor burden with both time (Figure xxx) and CAS9 status (figure xxx). Therefore, based on macroscopic inspection, at least one tumor suppressor appeared to cooperate with BRAF (V600E) to increase tumor burden. In order to determine the fitness landscape of any one particular tumor suppressor, we calculated the relative number of tumor cells in a given tumor using the TUBA-SEQ genomics pipeline. After 8 weeks post tumor initiation there no statistically significant contribution of tumor suppressor loss. SETD2 loss was trending towards statistical significance. However, 16 weeks post initiation revealed both SETD2 loss and APC loss cooperated with BRAF (V600E) to form larger, more malignant tumors. APC loss was a suspected hit as we have previously shown that activation of Wnt-beta-catenin signaling promoted BRAF(V600E) tumorigenesis. As APC loss is predicted to increase the activity of Beta-catenin signaling, this result was unsurprising to us. However, loss of SETD2 was a novel finding in the context of BRAF (V600E) lung tumorigenesis.

Given our findings of SETD2 loss increased tumor burden concurrent with BRAF(V600E) we next validated SETD2 in a new cohort of mice with single-guide RNAs targeting SETD2. Indeed, loss of SETD2 increased tumor burden from 5% to over 30% in some animals. Since SETD2 antibodies are unreliable in both western blots and immunohistochemistry we used H3K36me3 as a surrogate marker for SETD2 activity by immunohistochemistry. Whereas 90% of nuclei in BRAF (V600E) only tumors were H3K36me3, more than 60% tumors of mice infected with SETD2 CRISPR virus were negative for H3K36me3. Furthermore, when classified by H3K36me3-positive or -negative, there is even stronger evidence that SETD2 loss leads to larger tumor formation.

![**Differential BRAF^V600E^ lung tumorigenesis imparted by p53-Hotspot mutants.** **(A)** Genetically-engineered alleles of _Braf^v600E^_ and ^Trp53^ before and after Cre-Recombinase. **(B)** Tumor burden and *(C)*** Tumor size of BRAF(V600E) plus Trp53-wildtype, null, or mutant alleles 14 weeks post Cre-mediated recombination. *(D)*  Representative H&E images 14 weeks after Cre-recombination. **(E)** Survival of mice with Heterozygous _Trp53_ mutant alleles. **(F)** Survival of mice with homozygous _Trp53_ alleles.](images/tubaseq_figure1.svg){#fig:06 .white width="75%"}

## Chapter Three {.page_break_before}

## Abstract

^TP53^ missense BRAF^V600E^ mutations both frequently occur in lung adenocarcinoma. While genetically engineered mouse models (GEMMs) of lung adenocarcinoma are invaluable for understanding the initiation, progression, and response to therapeutics, little is known about how different hotspot point mutations in p53 affect disease progression and therapeutic responses. To this end, we use GEMMs, tumor-derived cell lines, and human lung cancer cell lines to test how  murine homologues of p53 hotspot mutants R172H and R245W compare to p53-deletion. We find that conformation mutation p53^R172H^ drives more aggressive lung adenocarcinomas and dedifferentiation. We also observe p53^R172H^ and p53^R245W^ accumulation in only high-grade tumors that have activated ARF expression. In vitro and in vivo studies demonstrate enhanced resistance to BRAF+MEK blockade with p53^R172H^ and p53^R245W^, a common treatment regimen for BRAF^V600E^ mutant patients. Mechanistically, mutant-p53 alters the transcriptome of cancer cells and enhances entry into the cell cycle. 

## Introduction

Lung adenocarcinoma (LUAD) remains deadliest form of cancer since 1987 (Siegel, Miller et al. 2021). It is characterized by alterations in the MAP kinase (MAPK) pathway, including activating mutations in the oncoproteins EGFR, KRAS (G12C, G12D, G12V) or BRAF^V600E^ [@pmid:25079552; @pmid:16705038; @pmid:11751630; @pmid:17299132]. The recognized predominant cell of origin for LUAD, lung alveolar type-2 pneumocyte cells (AT2), are exquisitely responsive to the transformative properties of constitutive activation of the MAPK pathway [@pmid:24586047; @pmid:31951518]. Indeed, conditionally genetically engineered mouse models (GEMMs) of mutationally activated EGFR, KRAS, or BRAF form lung tumors that strongly resemble key characteristics of human LUAD. However, tumors formed in all three models (KRAS:G12D, EGFR: Deletion 19 or L858R, or BRAF:V600E) develop only into histologically low- to mid-grade cancer and are growth arrested [@pmid:11751630; @pmid:16705038; @pmid:17299132]. Prior research has determined that oncogene-induced tumor growth arrest occurs through activation of several tumor suppression mechanisms, most notably, p53-mediated tumor suppression [@pmid:26001956].

Alterations in the _TP53_ tumor suppressor gene are common in all cancer types, including LUAD [@pmid:27328919]. P53 encodes a transcription factor that responds to a variety of cell stresses, such as DNA damage and oncogene activation. In response to stress, p53 is stabilized and induces anti-proliferative and genome-mending effects through trans-activation of a diverse set of P53-target genes [@pmid:33518400; @pmid:11099028]. p53 mutations observed in cancer frequently occur in the DNA binding domain where a single amino acid change results in dysfunctional DNA-binding and failed transcriptional activation [@pmid:20182602]. Therefore, mutated p53 that is defunct in p53 transcriptional regulation results in failed tumor suppression and cancer outgrowth. Furthermore, defective p53 signaling will permit future genomic insults to remain unchecked thus fostering an environment primed for malignant potential. Since mutant-p53 lacks transcriptional activity through its inability to bind DNA, it is unable to induce expression of its negative regulators, ARF, MDM2 and MDMX [@pmid:8265599; @pmid:8319905]. Lack of negative feedback results in mutant-p53 stabilization. Accumulation of mutant p53 has been reported to elicit gain-of-function p53 activity. Thus, any gain-of-function activity in mutant-p53 cannot be studied with p53-genetic deletion. Many research groups have characterized gain-of-function phenotypes of mutant-p53 in cancer. For instance, mice expressing mutant-p53 have altered disease phenotype compared to p53-null models [@pmid:15607980;@pmid:15607981]. Specifically in lung cancer model systems, mutant-p53 has been observed to modulate SMAD3, NF$\kappa$B, p63, TGF$\beta$, and others to drive various hallmarks of cancer such as invasion, chemoresistance, metabolism, and propagation of a stem cell fate [@pmid:34178628 ;@pmid:11238924;@pmid:19345189]. Although the mechanisms that leads to these altered processes are controversial, it is thought that the main affect is through mutant-p53 binding and sequestering known p53-associated proteins. This often leads to activation of transcription factors such as NF-Y [@pmid:33839689].

In BRAF^V600E^ GEMMs, when p53 function is abolished by _Trp53_ gene deletion or by _Cdkn2a_ deletion, lung tumors can escape growth arrest and undergo malignant transformation [@pmid:17299132; @pmid:26001956]. Furthermore, p53 pathway dysregulation allows a cell to sample diverse phenotypic landscapes that allow for enhanced cell fitness and tumor outgrowth [@pmid:32707077]. However, BRAF^V600E^ lung tumorigenesis and progression to malignant lung adenocarcinoma has only been studied in the context of p53 genetic deletion, not p53 mutation, which are more frequently seen in human lung cancer. Specifically, p53-R172H and p53-R245W are murine homologues of common hotspots in human cancer R175H and R245W, respectively.

Here, we characterize the differential impact of p53(null), as well as p53 hotspot mutations p53^R712H^ (R175H in humans) and p53^R245W^ (R248W in humans) on BRAF^V600E^ lung tumorigenesis. We observed significantly differential effects of p53-R172H on BRAF^V600E^-driven lung tumorigenesis that was not observed when p53 is deleted, such as enhanced tumor size and decreased survival. Our findings highlight functional differences in mutant-p53 biology, as well as the importance and the utility of clinically relevant mutant-p53 mouse models.

## Results

_**P53-mutant Alleles Differentially Alter BRAF (V600E) Lung Tumorigenesis**_

Expression of BRAF^V600E^ in the distal epithelium of the mouse lung elicits clonal tumorigenic outgrowths of alveolar type 2 (AT2) pneumocytes (Dankort et al. 2007).Prior work has shown that _Trp53^fl/fl^_ cooperates with BRAF(V600E) to form malignant lung tumors when Cre recombinase is activated [@pmid:17299132; @pmid:26001956]. Therefore, we compared the tumor burden of _Braf^Cat/+^_ mice with either p53 loss (_Trp53^fl/fl^_, p53^R172H^ (_Trp53^R172H/R172H^_), or p53^R245W^ (_Trp53^R245W/R245W^_) after infection with 106 pfu of adenovirus expressing surfactant protein C specific Cre (ad5-Spc-Cre) (Figure @fig:11 A). As expected, mice developed lung cancer, consistent with previous findings (Figure @fig:11 B-C). However, there was a striking, highly reproducible increase in the tumor size of tumors harboring _Trp53^R172H/R172H^_ and to a lesser extent _Trp53^R245W/R245W^_, compared to _Trp53^fl/fl^_ (Figure @fig:11 B-D). These data led us to hypothesize that p53^R172H^ and p53^R245W^ expression alters tumor progression uniquely from p53 deletion, and these differences may be potentially evident of gain-of-function effects imparted by mutant-53. Since lung cancer patients with mutations in _TP53_ often start only have one mutated _p53_ allele unless loss of heterozygosity (LOH) occurs. Therefore, we generated mice heterozygous for both _Braf^CAT^_ and either _Trp53^fl^_ , _Trp53^R172H^_, or _Trp53^ R245W^_ and observed their survival over time (Figure @fig:11 E). We noted that _Trp53^R172H/+^_ mice had diminished median overall survival compared to _Trp53^fl/+^_ mice (183 days and 216 days), with _Trp53^R245W/+^_ mice falling in between the two groups (median survival 212 days) (Figure @fig:11 E).

We observed a distinct separation of survival between mice harboring lung tumors that are either _Trp53^fl/+^_, _Trp53^R172H/+^_, and _Trp53^R245W/+^_, this separation is diminished when altered p53 alleles are homozygous (Figure @fig:11 F). _Trp53^R172H/R172H^_ mice have a median survival of 120 days while _Trp53^fl/fl^_ mice have a median survival of 136 days. Importantly, this observed difference in survival is statistically significant (Log-rank test p< 0.001) and is likely a reflection of worse diseased, characterized by enhanced tumor burden and tumor size.


_**Mutant-p53 Accumulation is Associated with Dedifferentiation and p19 Induction**_

Increased malignancy in lung adenocarcinoma is often associated with altered states of tumor cell identity and dedifferentiation [@pmid:31452510;@pmid:32707077]. Since LUADs often arise from AT2 cells, we surveyed the expression of AT2 cell identifiers, such as NKX2-1, a master regulator of AT2 transcriptional programs, and SPC, a marker of differentiated AT2 cells [@pmid:32707077]. Quantification of over 50 tumors from _Braf^V600E/+^_ mice with either _Trp53^ flfl^_, _Trp53^R172H/R172H^_, and _Trp53^R245W/R245W^_ revealed that _Trp53^R172H/R1722H^_ mice had significantly more tumors that stained negative for NKX2-1 and SPC (Figure @fig:12 A an B). This finding strongly indicates that mutant-p53 tumors are dedifferentiated. Since HMGA2 expression is associated with LUAD dedifferentiation and worse patient prognosis, we performed IHC for HMGA2 (Cite). We noted an increase in HMGA2-positive tumors in both _Trp53^R172H/R172H^_, and _Trp53^R245W/R245W^_ tumors compared to _Trp53^fl/fl^_ (Figure @fig:12 A,B). Thus, this data taken together reveals that Trp53R172H/R172H mice exhibit both a higher tumor burden and worse overall survival than _Trp53^fl/fl^_, but the tumors developed in these mice are more likely to exhibit malignant progression and dedifferentiation.

One striking feature of lung tumors in mice either heterozygous or homozygous for _Trp53 ^R172H^_ or _Trp53^R245W^_ is how few tumors and tumor cells have detectable levels of mutant-p53 protein as measured by Immunohistochemistry (IHC). One critical aspect of normal p53 function is self-regulation through transcriptional activation of its negative regulator MDM2 [@pmid:8319905]. Thus, we predicted that homozygous p53 mutant-cells would exhibit increased mutant-p53 protein. Interestingly, in our models, we observed mutant p53 protein accumulation is restricted to malignant cells exhibited by lack of papillary architecture and nuclear atypia (Figure @fig:12 C). Indeed, p53 immunostaining is correlated with increased phospho-ERK1/2 detection (Figure @fig:12 D). Moreover, immunofluorescence of p53 and its positive regulator, p19/ARF, reveal cells with high p19/ARF are also high in p53 accumulation (Figure @fig:12 D). This result suggests that even in homozygous mutant_Trp53_ mice, there is still a barrier to mutant-p53 accumulation, and our data suggests that elevated levels of p19/ARF is important for mutant-p53 accumulation, even with homozygous p53 mutations. Collectively, these data indicate that _Trp53^R172H^_ drives more aggressive lung adenocarcinoma formation in BRAF(V600E) driven mouse models of lung cancer.

_**P53^R172H^ and P53^R245W^ cell lines are refractory to BRAF/MEK inhibition**_

Given that previous research has determined that p53 mutations can confer resistance to both chemotherapies and pathway-targeted therapies [@pmid:7585548;@pmid:22068033], we next questioned whether our p53 alterations would be sufficient to drive therapeutic resistance in BRAF^V600E^-driven cell lines exposed to pathway-targeted therapeutics commonly administered to BRAF^V600E^ mutant patients, such as the combination of dabrafenib (BRAFi) plus trametinib (MEKi) [@pmid:27283860]. Cell lines were derived from _Braf^CAT/+^_ murine tumors expressing either _Trp53^flfl^_, _Trp53^R172H/R172H^_, or _Trp53^R245W/R245W^_) 14 weeks after infection with ad5-Spc-Cre. Cell lines expressing either _Trp53^R172H/R172H^_ or _Trp53^R245W/R245W^_ were completely resistant to single agent dabrafenib and resistant to the combination of dabrafenib plus trametinib (Figure @fig:13 A,B). Of note, _Trp53^R172H/R172H^_ and _Trp53^R245W/R245W^_ cell lines express increased ERK1/2 activity, as evidenced by increased phosphorylated ERK1/2, both with and without Dabrafenib and Trametinib (Figure @fig:13 E). Moreover, _Trp53^R172H/R172H^_ mice retain a larger tumor burden after a week 4 treatment of MAPK blockade _in vivo_ (Figure @fig:13 E). To gain relevance to human lung cancer, we infected BRAF(V600E) mutant HCC364 cells with lentivirus expressing human cancer hotspot mutant p53^R175H^. p53^R175H^ expressing cells were more proliferative and more refractory than parental HCC364 cells (Figure @fig:13 F and G).Collectively, these _in vitro_ and _in vivo_ data suggest missense mutant p53^R175H^ and its murine homologue p53^R172H^, as well as p53^R245W^ can support cancer cell viability in the face of BRAF+MEK blockade that cannot be achieved by p53-null mutations.


_**P53^R172H^ and P53^R245W^ alters the transcriptome of BRAF(V600E) lung tumor cell lines**_

Due to our observations that mutant p53^R172H^ drives more aggressive cancer phenotypes such as increased growth, dedifferentiation, and resistance to FDA-approved therapeutics, we reasoned that this would be reflected in a change in the transcriptional landscape. This is due in part, by the transcriptional trans-activation potential by mutant p53. RNA sequencing of cell lines generated from p53-mutant mouse lung tumors do reveal transcriptomic differences between both p53^R172H^ and p53^R245W^ cells compared to p53-null cell lines (Figure @fig:14 4 A). Interestingly, genes involved in cell cycle regulation, epithelial-to-mesenchymal transition (EMT), and MYC pathway are upregulated in both p53^R172H^ and p53^R2245W^ cell lines (Figure 4 @fig:14 B). These results suggest that mutant-p53 is affecting transcription of genes involved in pro-growth signaling pathways.


![**Differential BRAF^V600E^ lung tumorigenesis imparted by p53-Hotspot mutants.** **(A)** Genetically-engineered alleles of _Braf^v600E^_ and ^Trp53^ before and after Cre-Recombinase. **(B)** Tumor burden and *(C)*** Tumor size of BRAF(V600E) plus Trp53-wildtype, null, or mutant alleles 14 weeks post Cre-mediated recombination. *(D)*  Representative H&E images 14 weeks after Cre-recombination. **(E)** Survival of mice with Heterozygous _Trp53_ mutant alleles. **(F)** Survival of mice with homozygous _Trp53_ alleles.](images/figure1_021022.svg){#fig:11 .white width="75%"}

![**Missense mutant-p53 alters lung adenocarcinoma differentiation status and accumulation of mutant-p53 correlates with p19 ARF expression.** **(A)** Panel representative IHC sections stained with SPC,NKX2-1, p53 and HMGA2. **(B)** H-score of individual tumors. **(C)** Association between mutant-p53 R172H accumulation and increased malignancy and dedifferentiation. **(D)** serial section of P53-HI and pERK1/2-HI tumors compared to adjacent low. **(E)** Colocalization of p19/ARF and p53 in p53-mutant tumors](images/figure2_021722.svg){#fig:12 .white width="75%"}


![**Mutant-p53 cell lines are refractory to BRAFi+MEKi.** **(A)** Response of GEMMs to BRAFi+MEKi chow after four weeks **(B)** in vitro dose response to BRAFi single agent. **(C)** in vitro timecourse with dabrafenib (1000nm) plus trametinib (100nM). **(D)** Accumulation of dead cells in dabrafenib plus trametinib measured by CytotoxRed accumulation. **(E)** Immunoblotting of phospho-ERK1/2 in response to dabrafenib plus trametinib. **(F)** Ectopic expression of p53^R17H^ in human HCC364 cells. **(E)** Response of p53^R175H^ cells to dabrafenib plus trametinib. ](images/figure3_021722.svg){#fig:13 .white width="75%"}


![**Mutant-p53 expression cells have distinct transcriptome compared to p53-null cells.** **(A)** Volcano plot of differentially-expressed genes. **(B)** Upregulated pathways using GSEA with Hallmark gene sets.](images/figure4_021722.svg){#fig:14 .white width="75%"}

## Discussion

While lung adenocarcinomas primarily contain missense mutations in p53, most studies using mouse models of lung adenocarcinoma utilize a p53-null (_Trp53^fl/fl^_) allele instead of alleles encoding hotspot missense mutations [@pmid:23550210]. This is most likely because prior mutant-p53 alleles were null for _Trp53_ prior to Cre-mediated recombination, leaving every cell in the mouse sensitive to leukemias, lymphomas and sarcomas due to being partially p53-deficient [@pmid:16288016; @pmid:16166291; @pmid:15607980]. Our work has been made possible by newly described "wildtype to mutant" p53 alleles that allow for mice to be fully wildtype for p53 in all cells prior to Cre-mediated recombination[@pmid:30262850]. This strategy is crucial, as it allows for temporally extended experiments not confounded by separate malignancies. Here, we utilize &quot;wildtype to mutant&quot;_Trp53^R172H^_ and _Trp53^R245W^_ alleles R245W to determine how they alter tumor progression in a BRAF(V600E) model of lung cancer. We show that p53^R172H^ and p53^R245W^ accelerates lung tumor progression and increases the rate of dedifferentiation beyond complete loss of p53 expression.

Although point mutations in the _TP53_ gene can poison the natural tumor suppressive mechanisms of p53 protein, not all point mutations are equivalent in executing these functions. Mutations in the DNA-binding domain are most common and most potent at ablating normal p53 function. Taking advantage of a conditional BRAF^V600E^ lung tumor model where BRAF^V600E^ expression in AT2 cells drives benign tumor formation, we show that either p53^R172H^ or p53^R245W^ can bypass growth arrest and influence tumor progression and therapeutic sensitivity beyond how p53 loss can. Specifically, P53^R172H^ reduces survival and sensitivity to dabrafenib plus trametinib _in vivo_. Interestingly, a single allele of p53^R172H^ has a stronger tumor promoting phenotype than P53^R245W^. These findings further support a hierarchy model of p53 missense mutations, where conformation mutants such as p53^R175H^ have a stronger dominant-negative effect on wildtype p53, while mice with a single _trp53^fl^_ allele can still suppress tumorigenesis with one copy of wildtype but are prone to Loss of heterozygosity [@pmid:30262850; @pmid:27585860; @pmid:15607980].



In BRAF-driven lung adenocarcinoma, the repressive role of wild-type p53 is initiated by oncogenic stress brought about by increasing levels of MAPK-pathway activation[@pmid:17299132] . Hyperactivation of the MAPK pathway triggers p19/ARF to block MDM2, leading to p53 accumulation[@pmid:16957739; @pmid:21107428; @pmid:21107427]. Therefore, p53 acts late in lung adenocarcinoma, in contrast to pancreatic adenocarcinoma, where p53 is triggered early likely through PDAC-specific increases in p19/ARF through either increased PI3K, STAT3, or DMP1 [@pmid:27585860]. Our studies in BRAF(V600E) mutant lung adenocarcinomas reinforce this concept, as mutant-p53 does not accelerate growth in early tumors (supplemental figure). Furthermore, p53 is not detected until later stage tumor development and correlates with p19/ARF expression and increased phospho-ERK1/2 levels. Our studies indicate that mutant-p53 levels are associated with increased expression of p19/ARF. Therefore, any gain-of-function phenotype manifested by mutant-p53 must depend on accumulated p19/ARF. Thus, ablating the ARF tumor suppressor in human cancers with GOF _TP53_ mutants may paradoxically lead to tumor regression.

While most _TP53_ mutations observed in cancer result in an inability to bind DNA, they are often stable and preserve functional oligomerization and transcriptional transactivation domains[@pmid:24394915]. Thus, mutant-p53 can still interact with and affect the function of cellular processes. Supporting this rationale we observe altered transcriptomes with both p53^R172H^ and p53^R245W cell lines compared to p53-null. Consistent with previous mutant-p53 GOF studies, we observed enriched genes associated with EMT and cell-cycle entry with p53^R172H^ and p53^R245W^.

Many GOF phenotypes exhibited by mutant-p53 have centered around drug resistant mechanisms. Previous studies have shown that mutant-p53 can confer resistance to pathway targeted therapy and chemotherapies. Our studies highlight that p53^R172H^ and p53^R245W^ can confer resistance to BRAF-targeted therapy. Here, we show p53-R172H and p53-R245W cell lines are resistant to BRAF(V600E) inhibition and less sensitivity to the combination of BRAF+MEK inhibition. In pancreatic cancer models with LSL-p53-R172H expression, mutant-p53 regulates PDGFR-signaling to promote an invasive phenotype that is sensitive to Imatinib[@pmid:24725405]. Consistent with these findings, our transcriptional analysis and immunoblotting indicate p53-R172H and p53-R245W cells express PDGF-ligands and exhibit PDGFR-pathway activation.

In summary, we have compared the tumorigenic potential of three _^Trp53^_ alleles (_Trp53^fl/fl^_, _Trp53^R172H^_, and _Trp53^R245W^_) concurrently with _BRAF^V600E^_. _Trp53^R172H^_ and _Trp53^R245W^_ promoted more aggressive lung cancers exhibited by larger tumors and tumor dedifferentiation. However, only _Trp53^R172H^_ was observed to shorten survival compared to _Trp53^fl/fl^_. Moreover, _Trp53^R172H^_ and _Trp53^R245W^_ cell lines were refractory to dabrafenib and trametinib and were more proliferative. _Trp53^R172H^_ and _Trp53^R245W^_ cell lines had altered transcriptomes compared to p53-null cells and were highly enriched in genes involved in cell cycle proliferation. Our work highlights the importance of studying disease-relevant _TP53_ alleles in pre-clinical modeling systems.








## Chapter Four {.page_break_before}




## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
