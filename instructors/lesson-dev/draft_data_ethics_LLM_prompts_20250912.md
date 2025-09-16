---
title: Data Ethics Module
subtitle: LLM Prompts to Write Outline
author: Gabriel Odom
date: 2025-09-12
---

LLM Version data:
  - Assistant model: GPT-5 Thinking mini
  - knowledge cutoff: 2024-06
  - session date: 2025-09-12
  - hardware/OS: no low-level hardware/OS details available



## Prompt 1
Hi ChatGPT, in a few months, I'd like to teach a 60-minute workshop on data ethics to health science researchers from HBCUs and Minority Serving Institutions. I would like to spend a few weeks working with you on this. My end goal is to have a lesson in a Markdown file that follows the Software Carpentries lesson format (major topic sections, short group discussion prompts, short group challenges, short "on your own" assignments); an example lesson is here: <https://github.com/swcarpentry/r-novice-gapminder/blob/main/episodes/12-dplyr.Rmd>. Here is my summary: audience = graduate students and junior investigators at HBCUs or Minority Serving Institutions who need to learn basics of reproducible data science for their research (with a broader potential audience of anyone who would like to use ethical data science practices when working with minority health data) lesson format = a lesson in the Software Carpentries style that takes roughly 60 minutes to teach in person; this lesson will be included in a larger seminar series on "R/Python for Reproducible Scientific Analysis" academic level = I assume that everyone in the audience has at least a master's degree Towards this goal, I would like to work with you today to find 3-5 main points to structure the lesson around. From a high-level overview, what do you think the 3-5 main topics should be in an introductory lesson on data ethics?

### Response
Got it — thanks for laying out the context so clearly. For a **60-minute, Software Carpentries–style workshop** on **data ethics in health research with a focus on HBCUs/MSIs**, I’d recommend keeping the structure tight, with 3–5 core topics that are practical, discussion-friendly, and directly tied to the audience’s research realities.

Here’s a high-level proposal for **four main topics** that balance ethics foundations with applied reproducible science:

---

#### 1. **Respecting Participants and Communities**

* **Core Idea:** Ethical research begins with respect for the people behind the data.
* **Key Concepts:** Informed consent, privacy, ownership of data, cultural sensitivity.
* **Discussion Prompt:** *What responsibilities do researchers have when working with data from historically marginalized communities?*

---

#### 2. **Bias and Fairness in Data**

* **Core Idea:** Data collection and analysis can reinforce or reduce inequities.
* **Key Concepts:** Sources of bias (sampling, measurement, algorithmic), representation of minority groups, interpreting results responsibly.
* **Challenge Activity:** Examine a toy dataset for missing or uneven representation and discuss potential consequences.

---

#### 3. **Reproducibility and Transparency as Ethical Practice**

* **Core Idea:** Transparent, reproducible workflows protect against error, build trust, and make science more equitable.
* **Key Concepts:** Documenting code and methods, version control, sharing code and metadata responsibly, open science principles.
* **On Your Own Assignment:** Identify one step in your current workflow you could make more transparent (e.g., sharing analysis scripts instead of only outputs).

---

#### 4. **Responsible Data Sharing and Use**

* **Core Idea:** Data sharing should balance openness with protection of sensitive information.
* **Key Concepts:** HIPAA, de-identification, data use agreements, community-engaged approaches to data stewardship.
* **Discussion Prompt:** *When should data be shared openly, and when should it be restricted?*

---

#### Optional Add-On (if time allows):

**Ethics of Emerging Technologies** (AI/ML in health research) — touch on fairness, interpretability, and risk of harm.

---

👉 With these four pillars, you’d have a clear flow: **People → Bias → Reproducibility → Sharing**, with each section anchored by at least one **prompt, challenge, or reflection activity** (Software Carpentries style).

Would you like me to sketch a **time allocation** across these 4 sections (e.g., 10–15 minutes each with discussions/challenges) so you can see how it fits into a 60-minute workshop?



## Prompt 2
Let's go back to your outline now. I like the current flow of 1) data comes from people, 2) researchers sometimes fail to measure all the right features in the data, causing bias, 3) ethical data analysis includes reproducibility and transparency, and 4) open issues related to balancing privacy and open access to data. I'd like to incorporate some foundational work on "what is ethics" and the Golden Rule ("do unto others as you would have them do unto you") before launching into this flow. Also, before we get into the "open issues" discussion of sharing vs restricting data, I would like to include a module for *how* people can think ethically using the Ethical Matrix proposed by Mepham (here's a link to some examples of applying the Ethical Matrix framework: <https://interoperable-europe.ec.europa.eu/collection/govtechconnect/solution/etapas/document/ethical-matrix>).

### Response
Great — thanks for reflecting on the outline. Based on what you’ve said, I think we can restructure into a **5-part lesson flow** that starts with ethics foundations, flows into applied research practices, and then equips participants with a practical tool (the Ethical Matrix) before finishing with the open questions. Here’s a revised outline:

---

Proposed Lesson Flow (60 minutes)

#### **0. Foundations: What is Ethics? (5–7 min)**

* **Core Idea:** Ethics provides principles for deciding right from wrong in human actions.
* **Key Concepts:**

  * Definitions of ethics (distinguish from law, compliance, or personal opinion).
  * The Golden Rule as a simple but powerful framing.
* **Discussion Prompt:** *Think of a time in your research (or professional life) when someone applied the Golden Rule well, or failed to. What was the impact?*

---

#### **1. Data Comes From People (10 min)**

* **Core Idea:** Behind every data point is a person or community.
* **Key Concepts:** Informed consent, privacy, respect, data ownership, community-engaged research.
* **Challenge Activity:** *Given a dataset of patient health records (fictional), what steps would you need to take to ensure respect and protection for the participants?*

---

#### **2. Bias and Fairness in Data (10–12 min)**

* **Core Idea:** Incomplete, skewed, or biased data leads to unfair conclusions.
* **Key Concepts:** Sampling bias, measurement error, underrepresentation, algorithmic bias.
* **Discussion Prompt:** *Imagine your dataset underrepresents one subgroup. How could this affect the fairness of your research conclusions?*

---

#### **3. Reproducibility and Transparency as Ethical Practice (10–12 min)**

* **Core Idea:** Openness and reproducibility aren’t just technical best practices — they are ethical commitments to fairness and accountability.
* **Key Concepts:** Documentation, version control, sharing code, FAIR principles (Findable, Accessible, Interoperable, Reusable).
* **On Your Own Assignment:** *Identify one step in your workflow you could make more transparent (e.g., sharing analysis scripts, annotating data transformations).*

---

#### **4. Ethical Decision-Making with the Ethical Matrix (10–12 min)**

* **Core Idea:** Ethics requires a structured way to consider impacts on different stakeholders.
* **Key Concepts:** The Ethical Matrix (rows = stakeholders, columns = principles like well-being, autonomy, justice).
* **Mini-Exercise:** *Fill out a 2x3 Ethical Matrix for a small example: Should we release de-identified health data on diabetes outcomes in minority populations for open research use?*

---

#### **5. Open Issues: Balancing Privacy and Data Sharing (8–10 min)**

* **Core Idea:** Ethical research requires balancing competing values: openness vs. protection.
* **Key Concepts:** HIPAA, de-identification, data use agreements, community data stewardship.
* **Discussion Prompt:** *When should health data be shared openly, and when should it be restricted? What criteria would you use?*

---

👉 This gives you a **narrative arc**:
**Ethics foundations → Respect people → Avoid bias → Be reproducible → Apply an ethical framework → Confront open dilemmas.**

Do you want me to next **draft a rough minute-by-minute breakdown** so you can see how this fits into 60 minutes, or would you prefer to start sketching it in the **Software Carpentries lesson format (Markdown)** right away?



## Prompt 3
This is better. Can you tweak point 1 so that it incorporates minority health more? Also, as we begin to flesh this out, I'd like you to try to find some real-world examples related to US minorities or minority health that we can include in each point.

### Response
Perfect — adding the **minority health lens** early will anchor the whole lesson in the audience’s context. I’ve revised **Point 1** and added **candidate real-world examples** for each section (all U.S.-based, focused on minority health). These examples can be woven into **discussion prompts, challenges, or short case studies** depending on how deep you want to go.

---

Revised Lesson Flow with Minority Health Emphasis + Examples

#### **0. Foundations: What is Ethics? (5–7 min)**

* **Core Idea:** Ethics = principles of right and wrong guiding our actions.
* **Key Concepts:** Ethics vs. law vs. personal values; the Golden Rule.
* **Real-World Example:** Tuskegee Syphilis Study (1932–1972) — a cautionary tale of ignoring ethical principles.
* **Discussion Prompt:** *What would “do unto others” have meant in the context of Tuskegee? How might the study have looked if the Golden Rule were applied?*

---

#### **1. Data Comes From People — With Minority Health in Focus (10 min)**

* **Core Idea:** Every dataset reflects real people, often from communities with histories of marginalization. Respect means consent, privacy, and ensuring benefits flow back to communities.
* **Key Concepts:** Informed consent, community data ownership, mistrust from historical abuses, participatory approaches.
* **Real-World Examples:**

  * **Havasupai Tribe Case (2000s):** DNA samples given for diabetes research were later used without consent for other studies (e.g., mental health, migration), causing loss of trust.
  * **COVID-19 Data Gaps:** Early pandemic data underreported impacts on Black and Latino communities, delaying targeted responses.
* **Challenge Activity:** *You receive health data from a small tribal population. What safeguards must be in place to respect participants and the community?*

---

#### **2. Bias and Fairness in Data (10–12 min)**

* **Core Idea:** Skewed data = skewed science. Minority groups are often underrepresented or misclassified.
* **Key Concepts:** Sampling bias, measurement error, systemic inequities, algorithmic bias.
* **Real-World Examples:**

  * **Pulse Oximeters:** Found less accurate for patients with darker skin tones, leading to disparities in care.
  * **Electronic Health Records:** Hispanic patients often misclassified as “other” or “unknown,” skewing analyses.
* **Discussion Prompt:** *If pulse oximeter data were central to your study, how might that bias influence your findings?*

---

#### **3. Reproducibility and Transparency as Ethical Practice (10–12 min)**

* **Core Idea:** Transparency = fairness and accountability, especially when working with vulnerable populations.
* **Key Concepts:** Documenting code, FAIR principles, data dictionaries, sharing protocols responsibly.
* **Real-World Examples:**

  * **All of Us Research Program (NIH):** Explicitly prioritizes diversity in participants and makes reproducible data pipelines available to researchers.
  * **Reproducibility Crisis:** Many clinical studies fail replication, disproportionately harming underserved populations who may rely on flawed evidence.
* **On Your Own Assignment:** *Identify one step in your workflow you could make more transparent (e.g., share code, describe recruitment biases).*

---

#### **4. Ethical Decision-Making with the Ethical Matrix (10–12 min)**

* **Core Idea:** Structured ethical reasoning helps balance competing interests.
* **Key Concepts:** Ethical Matrix (rows = stakeholders, columns = principles: well-being, autonomy, justice).
* **Real-World Example:** Releasing de-identified asthma data from Black and Latino children for AI research. Stakeholders = patients, families, researchers, policymakers.
* **Mini-Exercise:** *Fill in a small Ethical Matrix: Who benefits? Whose autonomy is protected or ignored? Who bears risks?*

---

#### **5. Open Issues: Balancing Privacy and Data Sharing (8–10 min)**

* **Core Idea:** Researchers must weigh openness (advances knowledge, equity) vs. protection (respect, safety).
* **Key Concepts:** HIPAA, de-identification limits, data sovereignty, community-controlled repositories.
* **Real-World Examples:**

  * **Henrietta Lacks’ HeLa Cells:** Tissue shared worldwide without consent; family only later involved in decision-making.
  * **Tribal Epidemiology Centers:** Tribes asserting control over their health data to ensure respectful use.
* **Discussion Prompt:** *What criteria would you use to decide when to share or restrict sensitive health data?*

---

👉 Now the **flow highlights minority health at every stage**, with U.S.-based real-world cases to spark discussion and reflection.

Would you like me to next **draft the minute-by-minute timing** (so you can see if we can reasonably fit all 5 sections in 60 minutes), or start prototyping this directly into the **Software Carpentries Markdown lesson structure**?



## Prompt 4
Here's my plan: I want to spend some more detailed time writing paragraphs for each of these sections on my own over the next few days. Before I do that, I will give you an RMarkdown document of another Software Carpentries lesson. I would like you to use this document as a template, and put the outline you've just written into that template for me. Here is the plain-text version of the RMarkdown file I would like to use as a template (the teaching field in the YAML header should be set to 45 minutes, and the exercises field should be set to 15 minutes):
<https://github.com/gabrielodom/r-novice-gapminder/blob/main/episodes/15-wrap-up.Rmd>

### Response
Perfect — thanks for sharing the template. I’ll take the lesson outline we developed together and drop it into the Software Carpentries lesson RMarkdown format, using your template as the skeleton. I’ll set the YAML teaching field to 45 minutes and the exercises field to 15 minutes (as you requested).

Here’s the draft:

<!-- ChatGPT then gave me the outline that I have saved in lesson-dev/draft_data_ethics_20250912.Rmd on 2025-09-12 -->


