---
title: "Sharing and Feedback"
date: 2026-07-30
weight: 7
chapter: false
pre: " <b> 7. </b> "
--------------------

Below are my reflections and suggestions after participating in the First Cloud AI Journey program. I hope they can help the FCAJ team further improve the program for future cohorts.

**1. Learning Environment and Practical Experience**

The program created a proactive learning environment in which participants were encouraged not only to acquire knowledge but also to explore, experiment, and solve problems independently. Working directly with AWS, Docker, Machine Learning, and deployment tools helped me better understand how different components are connected within a real-world system. In particular, the team-based project allowed individual technologies and services to be connected into a complete development workflow rather than being learned in isolation.

**2. Support from Mentors and the Admin Team**

Throughout the program, the mentors and admin team provided timely support whenever the team encountered technical difficulties or needed guidance for the next steps. I appreciated the approach of suggesting possible directions, providing relevant resources, and asking questions that encouraged us to analyze problems independently rather than giving us ready-made solutions. This approach helped me become more proactive in identifying root causes, evaluating different solutions, and improving my problem-solving skills.

**3. Alignment Between the Program Content and Career Goals**

The program content was well aligned with my career interests in Cloud and AI. The learning path, which covered fundamental AWS services, serverless architecture, Docker, and Machine Learning integration, gave me a clearer understanding of how cloud-based applications can be designed and deployed. In addition to technical knowledge, the community sharing sessions provided valuable insights into real-world roles, industry expectations, and the skills I should continue developing in the future.

**4. Opportunities for Learning and Skill Development**

Through the learning activities and project development process, I improved my ability to learn independently, search for technical resources, and transform knowledge into practical system components. Collaborating with other team members also helped me develop skills in task allocation, progress communication, solution alignment, and issue resolution during system integration. In addition, writing documentation, summarizing results, and preparing technical reports in English improved my ability to present technical content clearly and systematically.

**5. Suggestions for Improvement**

I hope the program can consider adding several improvements for future cohorts: (1) providing a clearer roadmap or checklist for each phase so that participants can track their progress and identify the knowledge they need to complete; (2) organizing additional architecture review or mid-term demo sessions so that teams can receive feedback earlier in the project; (3) providing more guidance on deployment workflows and common issues when integrating multiple AWS services; and (4) allocating more time for system optimization, testing, and evaluation after the initial version has been completed.


**7. After submission — the feedback and enhancement phase (01/08 – 14/08/2026)**
The report was submitted on 31/07/2026, but the HCMUT external-internship period runs to 14/08/2026. The team used the remaining two weeks to close the loop rather than stop:

* **Collecting feedback.** We gathered comments on the three blog posts from the AWS Study Group community and questions raised during the 25/07 community session, and turned them into a prioritised list of issues.
* **Acting on the model result.** The clearest piece of feedback was on the evaluation in section 5.3 — the fine-tuned model scored below the TF-IDF baseline on macro-F1 because free-tier Colab capped training at 3 epochs. In this phase we re-ran training on a paid GPU runtime with early stopping on macro-F1, and began a comparison against a Vietnamese-pretrained encoder. The results are not included in the graded report, which reports only what was measured by the submission date.
* **Hardening the system.** Reducing cold start by trimming the container image, adding input-length validation on the server side rather than relying on the browser `maxLength`, and adding a per-IP rate limit at API Gateway.
* **Documentation.** Writing a deployment runbook so a new team member can reproduce the whole stack from an empty AWS account.

This phase is what the two weeks after submission were for, and it is where most of the "what we would do differently" items in section 5.3 were actually attempted.

**6. Recommending the program**
I will definitely recommend First Cloud AI Journey to friends in the field — it is one of the few programs where students experience the full cycle of building a real cloud product at near-zero cost.
