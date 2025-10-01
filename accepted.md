---
layout: page
title: "Accepted Papers"
permalink: /accepted_papers
order : 1
---

# Accepted Papers


## Camera-Ready Submission Guidelines

- __Deadline__: Camera-ready submissions are due by 17 October 2025 (extended).
- __Template link__: Since we will submit the papers to CEUR-WS, all accepted papers must be prepared using the CEUR-WS `ceurart` LaTeX template. Use the provided overleaf link to update your manuscript to the CEUR format: [LaTeX template (ShareLaTeX/Overleaf)](https://sharelatex.gwdg.de/read/rmmhkszmktpm#4301dc). More information on the template can be found [here](https://ceur-ws.org/HOWTOSUBMIT.html).
- __What to upload__: Submit the following as your camera-ready package via the camera-ready revision on Easychair:
  - Final paper PDF compiled from the CEUR `ceurart` template.
  - Signed author agreement as a PDF. The blank form is available in this repository at [agreement.pdf](/agreement.pdf). One signed agreement per paper is required.
- __Checklist before uploading__:
  - Verify authors, affiliations, title, and abstract are final and correct.
  - Ensure the paper compiles without errors and all fonts are embedded in the PDF.
  - Confirm figures/tables are legible and references are resolved.

If you have questions about the CEUR style, please refer to the official instructions above. For any workshop-specific questions, contact the organizers.

----

# Identity-Aware AI 2025 - Accepted Papers

## 1. How Can the Law Protect Human Uniqueness in the Age of Self-Replicating AI?

**Authors:** Giorgio Pedrazzi

**Abstract:**

As artificial intelligence advances, systems are increasingly capable of simulating the expressive, behavioral, and even emotional traits that define human identity. This paper examines the growing tension between the technological capacity to replicate these traits and the legal frameworks that attempt to protect the uniqueness of the human self. We begin by outlining how language, tone, memory, affective expression, and other dimensions of personhood are no longer uniquely embodied or ephemeral, but instead digitally captured, measured, and encoded into machine-readable formats such as embedding vectors. In this new paradigm, the human persona is no longer inviolable—it becomes replicable. Drawing on comparative legal analysis between the European Union and the United States, we explore how current regimes—particularly the GDPR, the AI Act, and biometric privacy statutes—provide fragmented and often inadequate protection. While certain data types, such as biometric identifiers and medical information, are recognized as sensitive, more elusive traits like emotional style, moral tone, or cognitive patterns remain legally underdefined. The emergence of neurodata—data that reflects internal mental states, such as attention or emotion—in AI systems challenges traditional data protection laws by blurring the line between personal data and subjective experience. The legal vacuum becomes even more pronounced in cases of posthumous digital replication, where AI-driven "deadbots" or memorial avatars simulate the traits of deceased individuals without clear governance over consent, dignity, or narrative integrity. We argue that legal systems must evolve beyond a static, attribute-based model of identity and begin to address the narrative, affective, and cognitive dimensions of personhood. This paper proposes normative and technical pathways for extending protection to these underregulated facets of identity, calling for a shift toward a legal understanding of uniqueness that is not merely informational, but experiential and relational.

---

## 2. A Fair and Personalized Dementia Prediction Framework Using Longitudinal and Demographic Data from South Korea

**Authors:** Hong-Woo Chun, Lee-Nam Kwon, Hyeonho Shin, Sungwha Hong and Jae-Min Lee

**Abstract:**

Early prediction of dementia is a critical public health challenge, yet conventional machine learning models often treat all patients as a single, uniform population. This approach overlooks subtle clinical differences between individuals and can lead to biased predictions that disproportionately affect specific demographic groups. This study proposes a novel framework that leverages the power of a Large Language Model (LLM) to build a fair and personalized dementia prediction system. While traditional methods required separate modeling for men and women, the LLM, thanks to its reasoning capabilities, can perform customized predictions using all data without the need for such separate modeling. We show that providing an LLM with specific demographic context, such as gender, leads to more nuanced and accurate predictive results than a generic, non-contextual prompt. This approach demonstrates that LLMs can be a powerful tool for developing personalized medical AI systems that respect individual differences and mitigate algorithmic bias.

---

## 3. From Perceived Effectiveness to Measured Impact: Identity-Aware Evaluation of Automated Counter-Stereotypes

**Authors:** Svetlana Kiritchenko, Anna Kerkhof, Isar Nejadgholi and Kathleen Fraser

**Abstract:**

We investigate the effect of automatically generated counter-stereotypes on gender bias held by users of various demographics on social media. Building on recent NLP advancements and social psychology literature, we evaluate two counter-stereotype strategies -- counter-facts and broadening universals (i.e., stating that anyone can have a trait regardless of group membership) -- which have been identified as the most potentially effective in previous studies. We assess the real-world impact of these strategies on mitigating gender bias across user demographics (gender and age), through the Implicit Association Test and the self-reported measures of explicit bias and perceived utility. Our findings reveal that actual effectiveness does not align with perceived effectiveness, and the former is a nuanced and sometimes divergent phenomenon across demographic groups. While overall bias reduction was limited, certain groups (e.g., older, male participants) exhibited measurable improvements in implicit bias in response to some interventions. Conversely, younger participants, especially women, showed increasing bias in response to the same interventions. These results highlight the complex and identity-sensitive nature of stereotype mitigation and call for dynamic and context-aware evaluation and mitigation strategies.

---

## 4. MetaRAG: Metamorphic Testing for Hallucination Detection in RAG Systems

**Authors:** Channdeth Sok, David Luz and Yacine Haddam

**Abstract:**

Large Language Models (LLMs) are increasingly deployed in enterprise applications, yet their reliability remains limited by hallucinations, i.e., confident but factually incorrect information. Existing detection approaches, such as SelfCheckGPT and MetaQA, primarily target standalone LLMs and do not address the unique challenges of Retrieval-Augmented Generation (RAG) systems, where responses must be consistent with retrieved evidence. We therefore present MetaRAG, a metamorphic testing framework for hallucination detection in Retrieval-Augmented Generation (RAG) systems. MetaRAG operates in a real-time, unsupervised, black-box setting, requiring neither ground-truth references nor access to model internals, making it suitable for proprietary and high-stakes domains. The framework proceeds in four stages: (1) decompose answers into atomic factoids, (2) generate controlled mutations of each factoid using synonym and antonym substitutions, (3) verify each variant against the retrieved context (synonyms are expected to be entailed and antonyms contradicted), and (4) aggregate penalties for inconsistencies into a response-level hallucination score. Experiments on a proprietary enterprise dataset illustrate the effectiveness of MetaRAG for detecting hallucinations and enabling trustworthy deployment of RAG-based conversational agents.

---

## 5. Who are you, ChatGPT? Personality and Demographic Style in LLM-Generated Content

**Authors:** Dana Sotto and Ella Rabinovich

**Abstract:**

Generative large language models (LLMs) have become central to everyday life, producing human-like text across diverse domains. A growing body of research investigates whether these models also exhibit personality- and demographic-like characteristics in their language. In this work, we introduce a novel, data-driven methodology for assessing LLM personality without relying on self-report questionnaires, applying instead automatic personality and gender classifiers to model replies on open-ended questions collected from Reddit. Comparing six widely used models to human-authored responses, we find that LLMs systematically express higher Agreeableness and lower Neuroticism, reflecting cooperative and stable conversational tendencies. Gendered language patterns in model text broadly resemble those of human writers, though with reduced variation, echoing prior findings on automated agents. We contribute a new dataset of human and model responses, along with large-scale comparative analyses, providing new insights on the topic of personality and demographic patterns of generative models.

---

## 6. On the Interplay between Musical Preferences and Personality through the Lens of Language

**Authors:** Eliran Shem Tov and Ella Rabinovich

**Abstract:**

Music serves as a powerful reflection of individual identity, often aligning with deeper psychological traits. Prior research has established correlations between musical preferences and personality, while separate studies have demonstrated that personality is detectable through linguistic analysis. Our study bridges these two research domains by investigating whether individuals' musical preferences are recognizable in their spontaneous language through the lens of the Big Five personality traits (Openness, Conscientiousness, Extroversion, Agreeableness, and Neuroticism). Using a carefully curated dataset of over 500,000 text samples from nearly 5,000 authors with reliably identified musical preferences, we build advanced models to assess personality characteristics. Our results reveal significant personality differences across fans of five musical genres. We release resources for future research at the intersection of computational linguistics, music psychology and personality analysis.

---

## 7. Political Bias in Large Language Models: A Case Study on the 2025 German Federal Election

**Authors:** Buket Kurtulus and Anna Kruspe

**Abstract:**

With the increased use of Large Language Models (LLMs) to generate responses to social and political topics, concerns about potential bias have grown. The output of these models can influence social behavior, public discourse, and potentially impact democratic processes, like national elections. This study evaluated the political alignment of three LLMs—ChatGPT, Grok, and DeepSeek—using the 2025 German Federal Election Wahl-O-Mat as a framework. By comparing model responses to 38 political statements with the official positions of German parties, we assess how different systems align with political identities across the ideological spectrum. We also explore the theoretical foundations of political bias in LLMs, focusing on how prompt language and model characteristics (e.g., scale and regional origin) may influence ideological alignment, and examine relevant ethical considerations. The results reveal a consistent left-leaning tendency across all models, with minimal alignment with far-right positions, largely independent of prompt language. By combining empirical findings with theoretical background, this work contributes to a deeper understanding of political bias in LLMs and highlights the importance of transparency in their public use.

---

## 8. Identity by Design? Evaluating Gender Conditioning in LLM-Generated Agent Identity Profiles

**Authors:** Mattia Rampazzo, Saba Ghanbari Haez, Patrizio Bellan, Simone Magnolini, Leonardo Sanna and Mauro Dragoni

**Abstract:**

In multi-agent reasoning frameworks powered by large language models (LLMs), agent roles are often instantiated through identity descriptions that condition their behavior. This paper investigates whether and how the gender assigned to the responsible for defining role-specific identity profiles affects the linguistic identity, sentiment, and gender expression of downstream agents. We introduce a large-scale corpus of agent identity descriptions generated under controlled combinations of frameworks, roles, models, and gender conditions. Through quantitative and qualitative linguistic analyses, we observe a consistent skew toward female identity across models and roles when gender is unspecified, along with varying degrees of polarity and subjectivity depending on the description framework. Notably, cognitively-oriented frameworks suppress affective expression, while trait-based frameworks amplify gender alignment. These results reveal that identity conditioning is not solely determined by prompt parameters but emerges through a layered interaction of model priors, framework semantics, and role-specific expressive constraints.

---

## 9. Testing LLMs' Sensitivity to Sociodemographics in Offensive Speech Detection

**Authors:** Lia Draetta, Soda Marem Lo, Samuele D'Avenia, Valerio Basile and Rossana Damiano

**Abstract:**

Recent research in text classification increasingly leverages generative Large Language Models (LLMs) to address a wide range of tasks, including those involving highly subjective linguistic phenomena, such as hate speech and offensive language detection, areas closely tied to semantics and pragmatics. A growing body of works in the NLP community is examining how annotators’ backgrounds influence labeling decisions, while also studying model biases and alignment with different social groups. A frequently used technique with generative models is sociodemographic prompting: where LLMs are asked to impersonate individuals based on their known demographic traits. In this work, we further explore this technique and its limitations on a disaggregated dataset of offensive speech detection. We selected five models of 7 to 8 billion parameters, and asked them to classify the sentences, providing all possible combinations of the available sociodemographic traits (gender, race and political leaning). Additionally, we asked the models to provide brief explanations of their choices to investigate their motivations. Through both a consistent quantitative and qualitative analysis, we observed limitations in their capacity to exploit demographic information. Results underscore the need for in-depth analysis going beyond performance metrics when this technique is adopted.

---

## 10. IntersectionRE: Mitigating Intersectional Bias in Relation Extraction Through Coverage-Driven Augmentation

**Authors:** Amirhossein Layegh, Amir H. Payberah and Mihhail Matskin

**Abstract:**

Relation Extraction (RE) models are crucial to many Natural Language Processing (NLP) applications, but often inherit and deepen biases in their training data. The underrepresentation of certain demographic groups can result in performance disparities, particularly when considering intersectional fairness, where biases intersect across attributes such as gender and ancestry. To address this issue, we present IntersectionRE, a framework to improve the representation of underrepresented groups by generating synthetic training data. IntersectionRE identifies gaps in demographic coverage and optimizes data generation, ensuring the quality of augmented data through Large Language Models (LLMs), perplexity scoring, and factual consistency validation. Experimental results on the NYT-10, and Wiki-ZSL datasets demonstrate that our approach effectively reduces intersectional representation and model performance disparities, particularly for historically underrepresented groups.

---

## 11. Identity-Aware Large Language Models require Cultural Reasoning

**Authors:** Alistair Plum, Anne-Marie Lutgen, Christoph Purschke and Achim Rettinger

**Abstract:**

Large language models have become the latest trend in natural language processing, heavily featuring in the digital tools we use every day. However, their replies often reflect a narrow cultural viewpoint that overlooks the diversity of global users. This missing capability could be referred to as cultural reasoning, which we define here as the capacity of a model to recognise culture-specific knowledge values and social norms, and to adjust its output so that it aligns with the expectations of individual users. Because culture shapes interpretation, emotional resonance, and acceptable behaviour, cultural reasoning is essential for identity-aware AI. When this capacity is limited or absent, models can sustain stereotypes, ignore minority perspectives, erode trust, and perpetuate hate. Recent empirical studies strongly suggest that current models default to Western norms when judging moral dilemmas, interpreting idioms, or offering advice, and that fine-tuning on survey data only partly reduces this tendency. The present evaluation methods mainly report static accuracy scores and thus fail to capture adaptive reasoning in context. Although broader datasets can help, they cannot alone ensure genuine cultural competence. Therefore, we argue that cultural reasoning must be treated as a foundational capability alongside factual accuracy and linguistic coherence. By clarifying the concept and outlining initial directions for its assessment, a foundation is laid for future systems to be able to respond with greater sensitivity to the complex fabric of human culture.

---

## 12. Neurodiversity Aware or Hyperaware AI? Visual Stereotypes of Autism Spectrum in Janus-Pro-7B, DALL-E, Stable Diffusion, SDXL, FLUX, and Midjourney

**Authors:** Maciej Wodziński, Marcin Rządeczka, Anastazja Szuła, Kacper Dudzic and Marcin Moskalewicz

**Abstract:**

Avoiding systemic discrimination of neurodiverse individuals is an ongoing challenge in training language models, which often propagate negative stereotypes. This study examined whether six text-to-image models (Janus-Pro-7B VL2 vs. VL3, DALL-E 3 v. April 2024 vs. August 2025, Stable Diffusion v. 1.6 vs. 3.5, SDXL v. April 2024 vs. FLUX.1 Pro, and Midjourney v. 5.1 vs. 7) perpetuate non-rational beliefs regarding autism by comparing images generated in 2024-2025 with controls. 53 prompts aimed at neutrally visualizing concrete objects and abstract concepts related to autism were used against 53 controls (baseline total N=302, follow-up experimental 280 images plus 265 controls). Expert assessment measuring the presence of common autism-related stereotypes employed a framework of 10 deductive codes followed by statistical analysis. Autistic individuals were depicted with striking homogeneity in skin color (white), gender (male), and age (young), often engaged in solitary activities, interacting with objects rather than people, and exhibiting stereotypical emotional expressions such as sadness, anger, or emotional flatness. In contrast, the images of neurotypical individuals were more diverse and lacked such traits. We found significant differences between the models; however, with a moderate effect size (baseline η2 = 0.05 and follow-up η2 = 0.08), and no differences between baseline and follow-up summary values, with the ratio of stereotypical themes to the number of images similar across all models. The control prompts showed a significantly lower degree of stereotyping with large size effects (DALL·E 3 η2  = 0.39; Midjourney η2  = 0.41; FLUX  η2  = 0.20; Stable Diffusion η2  = 0.34; DeepSeek-VL3  η2 = 0.45), confirming the hidden biases of the models. In summary, despite improvements in the technical aspects of image generation, the level of reproduction of potentially harmful autism-related stereotypes remained largely unaffected.

---

## 13. Trustworthy AI Through Dual-Role Reasoning: Ethical, Legal, and Psychological Internal Critique

**Authors:** Chengheng Li Chen, Antonio Lobo Santos, Marc Serramià Amorós and Maite López Sánchez

**Abstract:**

Despite advances in Large Language Model alignment, existing methods primarily optimize final outputs while neglecting internal reasoning processes. We introduce dual-role reasoning: models first produce responses as helpful assistants, then assume critical evaluator roles guided by legal, ethical, and psychological theories. Evaluation across six models reveals a fundamental paradox in this method. Theory-guided critique mechanisms exhibit pronounced task-specificity, where identical reasoning processes yield opposing outcomes across different contexts. Most critically, we observe systematic overcorrection where models abandon contextually-supported inferences in favor of inappropriate neutrality, where the same skeptical mechanisms that enhance factual accuracy by 6.12% on truthfulness simultaneously degrade contextual reasoning by 6.10% on bias detection. Adversarial robustness evaluations demonstrate consistent benefits, with theory-guided approaches reducing attack success rates by 15-25 percentage points relative to simple reflection. However, effectiveness varies across architectures, with the Llama 4 family showing particularly strong responsiveness. These findings indicate that dual-role reasoning may require task-conditional theory selection rather than universal application, though it shows consistent benefits for adversarial robustness across all conditions.

---
