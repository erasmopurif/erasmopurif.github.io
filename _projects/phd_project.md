---
layout: page
cover-title: Ph.D. project
cover-description: Beyond-Accuracy Perspectives on Graph Neural Network-Based Models for Behavioural User Profiling
title: Beyond-Accuracy Perspectives on Graph Neural Network-Based Models for Behavioural User Profiling
description: Ph.D. project
img: assets/img/phd_project/cover.jpg
importance: 1
category: Ph.D.
---

The focus of my doctoral project is to develop a *graph neural network-based model for behavioural user profiling* whose resulting user models are applied as the input of a recommender system, acting as a bridge with an *adaptive and personalised user interface* implemented to provide tailored explanations to the end-users depending on their specific user profiles.
Once the whole framework is implemented, evaluation of the behavioural user profiling models, as well as of the recommender system, will be carried out mainly on academic graph data, such as the [ORKG](https://www.orkg.org/orkg/) (Open Knowledge Research Graph). These sources include information about researchers, scientific papers they published and projects they are involved in, in order to develop specific use cases, such as creation of researcher user profiles or scientific paper or expert recommendation.

The intended framework resulting from this work, whose architecture is shown in the figure below, deals with three *beyond-accuracy* perspectives:
- **Privacy**, to study how to intervene on graph data structures of specific privacy-related contexts and provide methods to make that data available as input without neither exposing personal user information nor corrupting the profiles creation and system performances;
- **Fairness**, to build user representations that are free of any inherited discrimination which could affect the downstream recommendations by developing *debiasing* approaches to be applied on state-of-the-art GNN-based user profiling models;
- **Explainability**, to produce understandable descriptions of the framework results, both for user profiles and recommendations, mainly in terms of interaction importance; the explanations are not the same for all end-users, but tailored to the different profiles, in order to serve a concrete *human-centred* experience.

Around the outlined challenges, I formulate the following *research questions*, which define the main contributions of the doctoral research:
- **RQ1** How can we guarantee personal data protection on a graph data structure while avoiding to affect user models construction and retaining the performance of the recommender system built upon them?
- **RQ2** How do we build fair user representations from GNN-based user profiling models to keep the input of the downstream recommender debiased?
- **RQ3** How can we personalise user interfaces to adapt the explanations to the demands and requirements of different user profiles, considering their distinct knowledge, background and expertise?

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/phd_project/user_profiling_framework_RQ.jpg" title="user profiling framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overall architecture of the proposed framework
</div>


<h2 class="title mt-4 p-0 text-left">Results and contribution to date</h2>

In the initial two years of the doctoral studies, I started the research in all the three areas defined by the research questions previously described. In the following, I list the results and contributions to date (all the mentioned publications can are listed in the *Publication* page):
- For *privacy* perspective (**RQ1**), I developed a first *pseudonymisation* approach for privacy-preserving recommendations on academic graph data and evaluated the performance preservation in terms of precision. The paper has been published in [Computers Journal](https://www.mdpi.com/journal/computers) in 2021.
- For *fairness* perspective (**RQ2**), in close collaboration with [Dr. Ludovico Boratto](https://www.ludovicoboratto.com/) of the University of Cagliari, I conducted an assessment of fairness in state-of-the-art GNN-based models for behavioural user profiling tasks, in terms of both disparate impact and disparate mistreatment. The work will be submitted at [CIKM'22](https://www.cikm2022.org/).
- Concerning both *fairness* (**RQ2**) and *explainability* (**RQ3**), as a first attempt to embrace both the two perspectives together, I designed and implemented a system with the scope to show how the use of these techniques can lead to the growth of a domain expert’s trust and reliance on an AI system. A novel *"Trust&Reliance Scale"* to evaluate XAI systems has been proposed in the paper, which is at present in the rebuttal phase for the publication in [IJHCI Journal](https://www.tandfonline.com/journals/hihc20), after being accepted with minor revision.
- Regarding the study and investigation of *adaptive and personalised user interfaces* (**RQ3**), I carried out a user study among researchers belonging to various research fields to evaluate how two different explainable UIs, providing explanations for the outcomes of a recommender system for scientific papers, are perceived, in terms of understandability, trust and user satisfaction. This work has been presented at [IntRS Workshop 2021](https://intrs2021.wordpress.com/).
- Following the path of the work at the previous point, in order to extend to the community the line of research on designing adaptive and personalised explainable user interfaces (**RQ3**), we proposed and organised the [APEx-UI Workshop](https://sites.google.com/view/apex-ui-2022) at [IUI'22 conference](https://iui.acm.org/2022/), in collaboration with [Prof. Cataldo Musto](https://www.uniba.it/portal_memberdata/cataldo.musto) and [Prof. Pasquale Lops](https://www.uniba.it/docenti/lops-pasquale), both from the University of Bari. Held on March 21, 2022, we had around 30 participants and the pleasure to host keynotes by [Prof. Katrien Verbert](https://wms.cs.kuleuven.be/cs/onderzoek/augment/katrien-verbert) and [Prof. Denis Parra](https://dparra.sitios.ing.uc.cl/).
