+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Machine Learning Algorithm Intern"
  company = "ByteDance"
  company_url = "https://bytedance.com/"
  location = "Beijing"
  date_start = "2020-06-10"
  date_end = "2020-08-31"
  description = """
  **Live Streams Recommendation, Graph Embedding**: 

  ∗ Improved the performance of the internal ML trainer (C++) by reducing communication overhead. Reduced the mini-batch forward latency by over 100% in certain training circumstances that involve graph embedding. 

  ∗ Extracted relations from Petabyte log data to build distributed user-author graphs using MapReduce and designed graph encoders to train an embedding of graph nodes using Tensorﬂow and ByteDance ML API. 

  ∗ Integrated end-to-end embedding to CTR prediction and signiﬁcantly increased online user staytime (+3.5%), comment rate (+3.8%), and other metrics in AB tests for Douyin and TikTok. 

  **Systems for Engineering Eﬃciency**: 

  ∗ Designed and developed a system from scratch in Django with RESTful APIs that creates and manages alerts for 100+ online models of 5 products and presents model health status on a dashboard. Attracted 70+ internal users and developers. Reduced the usual day-long response time to less than an hour in a recent dataﬂow accident. 

  ∗ Developed a pipeline that analyzes the importance of 300+ features in a Monte Carlo fashion and performs feature modiﬁcation on Terabyte model checkpoints on clusters based on the results. Saved 2hr+ manual labor per iteration and 35k+ core-hour computing resources in total than hand-tuning.
  """

[[experience]]
  title = "Machine Learning Intern"
  company = "Nuctech"
  company_url = "http://www.nuctech.com/"
  location = "Beijing"
  date_start = "2019-05-20"
  date_end = "2019-07-20"
  description = """
  **Baggage Re-Identification for Smart Security Inspection**: Extensively investigated past architectures for
  person and vehicle re-identification (re-ID) tasks. Implemented multiple architectures and evaluated their
  performance for baggage re-ID. Achieved a 0.76 accuracy of CMC rank-1 (improving the baseline by a 0.34 margin
  in accuracy and about 100x in speed) on the overall re-ID task (image retrieval from the 500-baggage gallery) on
  the Multi-View Baggage dataset.

  **Testing Framework Development**: Developed a fork upon the open-source deep-person-reid framework for the
  team’s future research and deployment workflow, including features such as activation visualization, training
  checkpoint management, Comet.ml integration, and CLI tools.
  """

[[experience]]
  title = "Head Academic Staff"
  company = "TechX Academy"
  company_url = "https://www.techx.academy/"
  location = "Shanghai"
  date_start = "2018-05-01"
  date_end = "2019-08-20"
  description = """
  **Instructor of Theory of Computation**: Co-taught the 5-day seminar on theoretical computer science, covering
  topics such as discrete math fundamentals, computability (DFA and TM), and efficiency (polynomial reduction and
  P vs. NP). Designed slides, handouts, and assignments.

  **TA for AI Courses**: TA-ed 10-day main courses. Designed homework and assessments for neural net basics,
  Markov Decision Process, Q-learning in Deep Reinforcement Learning (2018), and feature extraction, SVM, DP &
  Seam Carving in Computer Vision (2019). Led Q&A sessions and graded homework.

  **Academy Experience Design**: Directed the Academic Team of TechX 2019. Led the processes of course design,
  staff search, and infrastructure setup for 5 courses.
  """

[[experience]]
  title = "Co-founder"
  company = "Fintern"
  company_url = ""
  location = "Beijing"
  date_start = "2018-04-01"
  date_end = "2019-04-01"
  description = """
  **Product Management**: Assisted the development of the platform from scratch using TypeScript and Node.js; generated user experience reports and feature addition proposals; beta-tested the platform with 100 users.
  
  **Business Operations**: Drafted business plans and pitched to Tsinghua alumni investors, ZhenFund, and various other VCs; Invited 15+ Chinese corporations and organizations to enter Fintern.
  """
+++
