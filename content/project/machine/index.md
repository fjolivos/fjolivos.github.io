---
date: "2021-02-02T00:00:00Z"
external_link: ""
featured: false
image:
  caption: 'Image credit: [kamanda242](https://www.flickr.com/photos/kamanda/357424778/in/photolist-xzTWb-gjF5R-4MpLsE-2id24EY-558Dhx-dTJeVv-55RW3h-h4B5UD-4Mkw1k-8SvhN9-ruCtb9-nwboET-pMuud4-6N8vPw-2iYQms3-29MUwS-izxM-5uYZ2v-eM52mA-tG4fMb-pNhk3t-pw53Bj-YpMc-52M5yz-88s3gk-fD4tLx-arDvqa-6o4dyB-688S9U-zFTBmK-2iYNMHm-r2dV8A-7YwmgD-8xfxEq-9hNL97-52GVJ3-jhbfV-4JbSZN-abWB85-4QTxRb-31d6as-88)'
  focal_point: Smart
links:
- icon: researchgate
  icon_pack: fab
  name: Follow
  url: 
#slides: example
summary: This study addresses two substantive research questions using machine learning: Does cultural capital increases students' cognitive skills in China? Does the effect of cultural capital on cognitive skills vary by school resources? 
tags:
- Papers
title: Uncovering the Heterogeneity of Cultural Capital Effect on Cognitive Skills using Tree-Based Machine Learning
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Human and cultural capital approaches are suggested as two explanations of educational achievement. The first approach maintains that certain cognitive abilities or technical skills are the most important determinants of success in the educational system. In the cultural capital approach, students' outcomes are mainly affected by a set of subtle cultural conventions. However, scholars argue that cognitive performance is also one of the pathways linking cultural capital and school success (Breinholt and Jæger 2020; Hu and Wu 2019). Different cultural capital dimensions foster the development of cognitive skills and abilities, having crucial consequences throughout the life course. Thus, the analytical distinction between cultural capital and cognitive skills, and their relationship, are of primary importance. 

Although the relationship between cultural capital and cognitive skills has been studied for Western countries (e.g., Coulangeon, 2018; Graaf, Graaf, & Kraaykamp, 2000; Kisida, Greene, & Bowen, 2014), it has been less examined in China's case (an exception is Hu & Wu, 2019). Previous studies in other East Asian countries -characterized by exam-oriented educational systems where performance depends heavily on the mastery of basic subjects- suggest that cultural capital operates primarily by enhancing students' cognitive skills (Yamamoto and Brinton 2010). We contribute to this literature by discussing whether the effect of cultural capital on cognitive skills may depend on the school context and resources. Students bring unequal degrees of cultural capital to school, where differences are amplified or ameliorated by school characteristics (Marteleto and Andrade 2014). Thus, empirical evidence has suggested that school resources are important for converting cultural capital into educational achievement. School resources could include facilities, teachers' training, class size, school socioeconomic composition, and student-teacher ratio, among others. 

This proposed article applies a novel computational method to address this sociological question in Chinese society: Tree-based machine learning. Causal trees are a data-driven computational method to explore sources of effect heterogeneity. Although machine learning (ML) tools have "yet to have its watershed moment within sociology" (Edelmann et al. 2020:73), they could provide solutions to long-standing sociological problems (Molina and Garip 2019). "Causal trees" are a specific ML method (Athey and Imbens 2016; Brand et al., forthcoming) to uncover population heterogeneity in observational data and more transparently depict the analyses that lead to a focus on particular subgroups (Brand et al., forthcoming). This method enables us to identify sources of variation that sociologists may not have previously considered or envisaged. To illustrate the causal tree algorithm's sociological utility, we examine how school context shapes the cultural capital effect on cognitive skills in China. Besides the methodological contribution, the study addresses two substantive research questions: Does cultural capital increases students' cognitive skills? Does the effect of cultural capital on cognitive skills vary by school resources?  

Our analysis will proceed as follows. First, we will report descriptive statistics of the key explanatory variables and covariates. Second, we will estimate the average effect of cultural capital on cognitive skills using covariate balancing propensity score for a continuous treatment (Fong, Hazlett, and Imai 2018). Third, we will examine the heterogeneous effects of cultural capital on cognitive skills for defined subgroups using CBPS and causal forest. In the CBPS, theoretically motivated covariates affecting both cultural capital and cognitive development. Fourth, we will assess the heterogeneous effects for subgroups identified by the selected causal tree. Although the literature suggests the relevance of school-level variables, we do not which particular characteristics or resources interact substantively with cultural capital. Finally, the sensitivity of partition-specific effect estimates to unobserved confounding will be evaluated.   

To study our questions, we will use the China Educational Panel Survey (CEPS). It is a unique longitudinal dataset that provides a rich set of cultural capital measurements in tandem with a cognitive skills test for a representative sample of middle-school students surveyed in 7th and 8th grades. We propose a 9-item Cultural Capital Index using an IRT GRM model to capture cultural capital as a latent variable. It combines three important dimensions suggested by previous studies (Jæger and Karlson 2018): familiarity with the legitimate culture, reading behavior, and extracurricular activities. In CEPS, cognitive skills are measured based on a test assessing students' aptitudes over 22 items on reasoning and problem-solving (Zhao et al. 2017). The test is unrelated to the school curriculum. To facilitate the comparability across students, scores were estimated using an item response theory model and z-scores. For assessing the heterogeneity of the cultural capital effect, a large set of theoretically relevant indicators of school quality and resources will be included.  




**Coauthor**: 

*Pablo Geraldo*, University of California, Los Angeles. 

*Jiahiu Xu*, The Pennsylvania State University. 
