<style type="text/css">
.image-left {
  display: block;
  margin-right: 10px;
  float: left;
}
  .btn {
  background-color: #4CAF50;
  border: 2px solid #4CAF50;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  display: flex; 
  justify-content: center;
}
.btn:hover {
  background-color: white;
  border: 2px solid #4CAF50;  
  color: black;
}
</style>


## Tutorial Material and Recording

### [Watch the Tutorial Recording [3h:30m] - You must first register to underline.io (Free of charge)](https://underline.io/events/24/sessions/292/lecture/2332-knowledge-graph-embeddings-from-theory-to-practice){: .btn}

:file_folder: **[Slides [PDF]](https://kge-tutorial-ecai2020.github.io/ECAI-20_KGE_tutorial.pdf)**

:pencil2: **[Jupyter notebook/Colab Hands-On Session](http://bit.ly/kge-tutorial)**

:pencil2: **[Check out additional KGE tutorial material](https://docs.ampligraph.org/en/1.3.2/tutorials.html)**


[![](./img/outline.jpg)](img/outline.jpg)

## Abstract

Knowledge graph embeddings are supervised learning models that learn vector representations of nodes and edges of labeled, directed multigraphs. We describe their design rationale, and explain why they are receiving growing attention within the burgeoning graph representation learning community. We highlight their limitations, open research directions, and real-world applicative scenarios. Besides a theoretical overview, we also provide a hands-on session, where we show how to use such models in practice.

## Goal

The goal of the tutorial is to provide answers to the following questions:

- What are knowledge graph embedding models(KGE), Which machine learning paradigm do they belong to? How do they stand against prior art?
- Why are knowledge graph embeddings important? What are the motivations to adopt such paradigm in - applicative projects or research activities?
- What are the real-world applications that benefit from learning and leveraging KGE at scale?
- What are the most popular KGE architectures? How are they trained? How are they evaluated?
- What are the existing software libraries? How to train and use embeddings? What are the best practices?
- What are the lessons learned and limitations in designing, implementing, evaluating, and adopting KGE architectures?
- What are some of the promising future directions in KGE research?

## Outline

**[Slides available here](https://kge-tutorial-ecai2020.github.io/ECAI-20_KGE_tutorial.pdf)**

- **Introduction.** Gentle introduction to knowledge graphs, and why graph-based knowledge representation matters in knowledge discovery tasks. Motivations for learning representations of nodes and edges, by describing the task of predicting missing links in graphs and presenting why such problem is hard to solve and requires ad-hoc machine learning models. In this part we also summarize the prerequisites for the remainder of the tutorial
- **Anatomy of a Knowledge Graph Embedding Models** Description and walk-through of a dissected knowledge graph embedding model, including a detailed description of the most popular varieties of components published in literature. Overview of training and best practices to optimize hyper-parameters.
- **Evaluation Protocol and Metrics.** The core of this section is the analysis of quality metrics for link prediction with knowledge graph embedding models. We will also describe the differences in evaluation protocols in literature, and present the problem of fair evaluation and reproducibility.
- **Comparison With Other Paradigms.** Comparison with traditional statistical relational learning, node embeddings, graph neural networks (GNN): supported data modalities, underlying intuitions, tasks, architectures, scalability.
- **Open Research Questions.** Discussion of recent research directions in the field: support for multi-modal knowledge graphs, more challenging datasets and benchmarks, reproducibility, time-awareness, interpretability and explanations, integration of symbolic reasoning, adversarial robustness.
- **Applications** Description of downstream machine learning tasks that benefit from KGE (link prediction (for knowledge discovery and knowledge base completion), link-based clustering, entity linking, enhanced classification with background knowledge. We show real-world examples of applied KGE models. We focus on a number of use cases: i) drug side-effect prediction from a protein network, ii) employee-jobs matching, iii) flight delay prediction,iv) generation of flavour compounds for the food industry.
- **Software Ecosystem and [Hands-On Session](http://bit.ly/kge-tutorial).** Overview and comparison of most popular software libraries for KGE models. Hands-on session where we will learn how to generate and visualize knowledge graph embeddings by learning from a real-world knowledge graph. We will also learn how to use such embeddings in downstream machine learning tasks such as link prediction and cluster analysis. This hands-on session will be carried out with the Apache-2 licensed, open source [AmpliGraph library](https://github.com/Accenture/AmpliGraph).


## Target Audience

The target audience is the general ECAI audience who is interested in knowledge representation and reasoning, machine learning, and natural language processing.

That includes artificial intelligence scientists, engineers, and students familiar with neural networks fundamentals and eager to know insights of graph representation learning for knowledge graphs. Researchers from graph-based knowledge representation (e.g. Semantic Web, Linked Data) and NLP also qualify as target audience.

The tutorial is of interest for either academic research and industry practitioners.


## Tutorial Material

**[Slides](https://kge-tutorial-ecai2020.github.io/ECAI-20_KGE_tutorial.pdf)**

**[Jupyter notebook/Colab Hands-On Session](http://bit.ly/kge-tutorial)**

**[Recording (3h:30m)](https://digital.ecai2020.eu/session/knowledge-graph-embeddings-from-theory-to-practice/)**. Sign up and login to ECAI-20 first.

## Organizers


[![](./img/luca.jpg)](img/luca.jpg){: .image-left} [**Luca Costabello** ](https://luca.costabello.info/) is research scientist in Accenture Labs Dublin. His research interests span knowledge graphs applications, machine learning for graphs, and explainable AI.

<br/>

[![](./img/sumit.jpg)](img/sumit.jpg){: .image-left} [**Sumit Pai**](https://www.linkedin.com/in/sumitppai/?originalSubdomain=in) is a research engineer at Accenture Labs Dublin. His research interests include knowledge graphs, representational learning, computer vision and its applications. Sumit has also worked as an engineer (Computer Vision) at Robert Bosch, India. He has done his Masters in Neural Information Processing from University of Tübingen, Germany.

<br/>

[![](./img/nick.jpg)](img/nick.jpg){: .image-left} [**Nicholas McCarthy**](https://www.linkedin.com/in/nicholas-mccarthy-5a678a34/?originalSubdomain=ie) is a research scientist at Accenture Labs. His reseearch interests include computer vision, graph representation learning, data privacy and medical imaging. Prior to joining Accenture Labs Nicholas worked at the INSIGHT Research Center and the Complex and Adaptive Systems Laboratory in University College Dublin, Ireland. 

<br/>

[![](./img/adrianna.jpg)](img/adrianna.jpg){: .image-left} [**Adrianna Janik**](https://adrijanik.github.io/) is a research engineer at Accenture Labs Dublin. Her research interests are interpretability in machine learning, deep learning, and recently knowledge graphs. She has double Masters in Data Science with a minor in entrepreneurship from the European Institute of Innovation and Technology (EIT), at the University of Nice - Sophia Antipolis and at the Royal Institute of Technology, Stockholm. During studies, she did her thesis internship at the Montreal Institute for Learning Algorithms. She also has a Bachelors in Control Engineering and Robotics from the Wroclaw University of Technology and used to work as a software engineer at Nokia.

