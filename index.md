## Abstract

Knowledge graph embeddings are supervised learning models that learn vector representations of nodes and edges of labeled, directed multigraphs. We describe their design rationale, and explain why they are receiving growing attention within the burgeoning graph representation learning community. We highlight their limitations, open research directions, and real-world applicative scenarios. Besides a theoretical overview, we also provide a hands-on session, where we show how to use such models in practice.


## Outline

- **Introduction.** Gentle introduction to knowledge graphs, and why graph-based knowledge representation matters in knowledge discovery tasks. Motivations for learning representations of nodes and edges, by describing the task of predicting missing links in graphs and presenting why such problem is hard to solve and requires ad-hoc machine learning models. In this part we also summarize the prerequisites for the remainder of the tutorial
- **Anatomy of a Knowledge Graph Embedding Models** Description and walk-through of a dissected knowledge graph embedding model, including a detailed description of the most popular varieties of components published in literature. Overview of training and best practices to optimize hyper-parameters.
- **Evaluation Protocol and Metrics.** The core of this section is the analysis of quality metrics for link prediction with knowledge graph embedding models. We will also describe the differences in evaluation protocols in literature, and present the problem of fair evaluation and reproducibility.
- **Comparison With Other Paradigms.** Comparison with traditional statistical relational learning, node embeddings, graph neural networks (GNN): supported data modalities, underlying intuitions, tasks, architectures, scalability.
- **Open Research Questions.** Discussion of recent research directions in the field: support for multi-modal knowledge graphs, more challenging datasets and benchmarks, reproducibility, time-awareness, interpretability and explanations, integration of symbolic reasoning, adversarial robustness.
- **Applications** Description of downstream machine learning tasks that benefit from KGE (link prediction (for knowledge discovery and knowledge base completion), link-based clustering, entity linking, enhanced classification with background knowledge. We show real-world examples of applied KGE models. We focus on anumber of use cases: i) drug side-effect prediction from a protein network, ii) employee-jobs matching, iii) flight delay prediction,iv) generation of flavour compounds for the food industry.
- **Software Ecosystem and Hands-On Session.** Overview and comparison of most popular software libraries for KGE models:OpenKE [5], AmpliGraph [4], PyTorch-biggraph [7]. Hands-on session where we will learn how to generate and visualize knowledge graph embeddings by learning from a real-world knowledge graph. We will also learn how to use such embeddings in downstream machine learning tasks such as link prediction andcluster analysis. This hands-on session will be carried out with the Apache-2 licensed, open source AmpliGraph library[4] that the authors of the tutorial designed, develop and currently maintain.


## Goal

The goal of the tutorial is to provide answers to the following questions:

- ***(What is it?)*** What are knowledge graph embedding models(KGE), Which machine learning paradigm do they belong to? How do they stand against prior art?
- ***(Why is it relevant?)*** Why are knowledge graph embeddings important? What are the motivations to adopt such paradigm in - applicative projects or research activities?
- ***(Where is it critical?)*** What are the real-world applications that benefit from learning and leveraging KGE at scale?
- ***(How does it work?)*** What are the most popular KGE architectures? How are they trained? How are they evaluated?
- ***(How to use KGE models in practice?)*** What are the existing software libraries? How to train and use embeddings? What are the best practices?
- ***(What did we learn?)*** What are the lessons learned and limitations in designing, implementing, evaluating, and adopting KGE architectures?
- ***(What next?)*** What are some of the promising future directions inKGE research?


## Target Audience

The target audience is the general ECAI audience who is interested in knowledge representation and reasoning, machine learning, and natural language processing.

That includes artificial intelligence scientists, engineers, and students familiar with neural networks fundamentals and eager to know insights of graph representation learning for knowledge graphs. Researchers from graph-based knowledge representation (e.g. SemanticWeb, Linked Data) and NLP also qualify as target audience.

The tutorial is of interest for either academic research and industry practitioners.


## Other Details

**Proposed Format:** Standard (Half-day)

**Estimated Audience:** 50-70 participants

**Presentation Style:** Slide deck presentation and Jupyter notebook/Colab tutorials for thehands-on session.

**Requirements:** Projector, Wireless Internet connection. Attendees interested in actively following the hands-on session should be equipped with a laptop.



## Presenters

  a|b
--|--
pci|**Luca Costabello** is research scientist in Accenture Labs Dublin, where he leads the knowledge discovery and explainable AI research streams. His research interests span knowledge graphs applications, machine learning for graphs, and explainable AI. He is the creator of AmpliGraph, a Python library for knowledge graph embedding models. He led the organization of the first edition of the Explainable AI tutorial at AAAI-19, an event with over 200 attendees. Before joining Accenture, Luca worked as research scientist in Fujitsu Ireland, where he focused on knowledge discovery from graph-based knowledge bases in various industry scenarios. He obtained a PhD in computer science from the University of Nice Sophia Antipolis (France), during a stint at the French Institute for Research in Computer Science (Inria), wherehe focused on context-aware consumption of Linked Data. He previously worked as research engineer at Telecom Italia in Turin(Italy), mostly on data mining for location-based services. He received an MSc and a BSc in computer engineering from the Polytechnic University in Turin. Luca is the author of publications inacademic conferences, such as ICLR, ISWC, ECAI, WWW, Hypertext, and ESWC, and serves as program committee member for conferences (ECAI, IJCAI, WWW, ISWC, ESWC, EKAW) and journals (Semantic Web Journal - SWJ). His updated publication list is available here.|
pic|**Sumit Pai** is a research engineer at Accenture Labs Dublin. His research interests include knowledge graphs, representational learning, computer vision and its applications. Sumit has also worked as an engineer (Computer Vision) at Robert Bosch, India. He has done his Masters in Neural Information Processing from University of Tübingen, Germany|
pic|**Nicholas McCarthy** is a research scientist at Accenture Labs. He holds a Bachelors in Computer Science and a PhD in Medical Imaging from University College Dublin. Prior to joining Accenture Labs Nicholas worked at the INSIGHT Research Center and the Complex and Adaptive Systems Laboratory in UCD, where he was a Teaching Assistant for a number of BSc and MSc Courses including: Intro. to A.I., Intro. to Image Analysis, Compiler Construction, and Software Engineering. He is a contributor to the open source AmpliGraph library for knowledge graph embeddings, and has significant experience applying these methods in industrial applications. His research interests include computer vision, and graph representation learning. Recent work has been published at SIGGRAPH and IAAI.|
