# MSE_Fall_2026
UTK MSE Fall 504/404 Course

Course Description:
	Machine Learning (ML) and Artificial Intelligence (AI) have become defining technologies of our era, transforming domains ranging from medicine and autonomous driving to image analysis, recommender systems, scientific computing, and large language models. Over the last decade, ML has achieved enormous success in primarily digital and in silico environments. The next decade will increasingly be shaped by ML acting in the real world: guiding experiments, optimizing materials and processes, controlling instruments, accelerating discovery, and becoming an integral part of automated and hybrid laboratories and manufacturing facilities.
	A central theme of this course is that modern ML for materials science is evolving along two complementary pathways. The first is the top-down agentic pathway, where AI systems are used to emulate aspects of high-level human decision-making: formulating goals, planning experiments, selecting tools, interpreting results, and deciding what to do next. The second is the bottom-up mathematical and optimization pathway, rooted in classical ML, statistical learning, Bayesian inference, reinforcement learning, surrogate modeling, and optimization. These methods provide the quantitative machinery for learning from data, making predictions, estimating uncertainty, and optimizing materials, processes, and experimental workflows.
	This course will introduce both pathways and show how they can be connected in practical scientific workflows. Students will learn the foundational concepts of ML and AI while also exploring how these methods are applied to real-world materials science problems, including structure-property relationships, imaging and spectroscopy, materials discovery, autonomous experimentation, and nanoscale physics. Special attention will be given to the interfaces between agentic and mathematical workflows, including the role of data representations, ontologies, knowledge graphs, literature-derived knowledge, laboratory metadata, and instrument-accessible tool functions. These elements are essential for connecting high-level scientific intent with executable experimental and computational actions. By the end of the course, students will understand not only individual ML algorithms, but also how they fit into the emerging ecosystem of AI-enabled science: from data analysis and prediction to decision-making, optimization, and autonomous experimental control. The course is designed to provide both conceptual foundations and practical intuition for using ML in materials science, preparing students to operate at the interface of materials, data, instruments, and AI-driven workflows.
	The instructor, Sergei V. Kalinin, has worked on ML applications in imaging, microscopy, and materials science for more than 15 years at Oak Ridge National Laboratory and the University of Tennessee, Knoxville, and spent a year at Amazon working on special projects. This background brings direct experience in deploying ML for real-world scientific and experimental problems.

Course Outline
1.	Introduction 
o	Machine Learning for Materials Science 
o	History of ML and Scientific Data 
o	Python Ecosystem, Data Structures, and Scientific Computing 
o	From In Silico ML to Real-World ML for Materials, Instruments, and Laboratories 
2.	Descriptions, Representations, and Agentic Systems 
o	Representing the World for Machine Learning 
o	Data, Metadata, Semantics, and Scientific Context 
o	Ontologies and Knowledge Graphs 
o	Literature, Laboratory Records, and Multimodal Scientific Knowledge 
o	LLMs as Interfaces to Scientific Knowledge and Workflows 
o	Agentic Systems: Tools, Actions, Planning, and Human-Level Decision Support 
o	Connecting High-Level Scientific Intent to Executable ML and Experimental Workflows 
3.	Classification 
o	Representing Objects, Labels, and Classes 
o	Classification and Decision Trees 
o	Decision Trees, Random Forests, and “Flowers” 
o	Simple Perceptron, Adaline, and Logistic Regression 
o	More Classifiers and Performance Metrics: ROC, AUC, Precision, Recall 
o	Training Classifiers: Ensembles and Boosting 
o	Classification Problems in Materials Discovery and Characterization 
4.	Clustering 
o	Fundamentals of Clustering 
o	Distance Metrics, Similarity, and Feature Spaces 
o	Clustering of Imaging and Spectroscopic Data 
o	Clustering for Materials Libraries, Microstructures, and Defect Populations 
5.	Dimensionality Reduction 
o	Linear Dimensionality Reduction Methods 
o	PCA, LDA, and QDA for Spectra and Images 
o	Linear Dimensionality Reduction for Imaging Data 
o	Other Techniques: CCA, ICA, NMF, Manifold Learning 
o	Dimensionality Reduction as Representation Learning 
6.	Deep Learning 
o	Multilayer Perceptrons 
o	Deep Convolutional Neural Networks 
o	CNNs for Images, Spectra, and Microscopy Data 
o	Autoencoders and Variational Autoencoders 
o	Invariant and Physics-Aware Variational Autoencoders 
o	Explainable ML and Interpretable Deep Learning 
o	Deep Learning as Feature Extraction, Representation Learning, and Surrogate Modeling 
7.	Decision Making 
o	From Prediction to Decisions 
o	Rewards, Objectives, and Utility Functions 
o	A/B Testing and Bandits 
o	Bayesian Optimization and Active Learning 
o	Contextual Bandits and Experimental Agents 
o	Decision-Making in Materials Discovery, Instrument Control, and Process Optimization 
8.	Multistep Decision Processes 
o	Sequential Decisions and Planning 
o	Tree-Based Methods: Search, Planning, and A* 
o	Heuristics in Multistep Decisions 
o	Dynamic Programming 
o	Rollouts, Lookahead Policies, and Model-Based Planning 
o	Connecting Agentic Planning with Bottom-Up Optimization 
9.	Reinforcement Learning 
o	Markov Processes and Markov Decision Processes 
o	Reinforcement Learning Fundamentals 
o	Value Functions, Policies, and Q-Learning 
o	Exploration, Exploitation, and Sparse Rewards 
o	Reinforcement Learning for Automated Experiments and Laboratory Workflows 
o	Practical Limits of RL in Scientific Discovery 
10.	Causality 
o	Why Prediction Is Not Enough 
o	Causal Inference Methods 
o	Interventions, Counterfactuals, and Directed Graphs 
o	Causality in Materials Science and Experimental Design 
o	Connecting Causal Models, Knowledge Graphs, and Agentic Decision-Making

The case studies throughout the course will be:

•	ML for imaging and characterization: using ML to analyze microscopy, spectroscopy, and diffraction data, from post-acquisition analysis to real-time and automated microscope workflows.

•	Agentic workflows for science: introducing ML agents that can use tools, follow workflows, assist with planning, and connect scientific goals to executable actions.

•	Automated synthesis and characterization: exploring how automated instruments, workflow design, and feedback loops enable automated labs and user facilities.

•	Materials informatics resources: learning how databases such as Materials Project, JARVIS, and AFLOW can be used for materials screening, property prediction, and ML-ready datasets.

•	Theory-based datasets: using QM9 as an example of how molecular structure can be connected to quantum-mechanical properties through ML.

•	LLMs for scientific text: using large language models to extract information from papers, reports, and lab records, and to connect text-based knowledge with structured data and workflows.


Prerequisites:
To be successful in this course you will need a general background in materials science, chemistry, or condensed matter physics. Homeworks, midterms, and finals will allow flexibility in choosing the problems that match your domain expertise. Python or similar programming experience, while not essential, will be extremely useful. Students without any prior programming experience should expect to spend extra time outside of class learning basic skills (but ChatGPT will help!). 

Student Learning Outcomes:
1.	Preparation for the future job landscape: The ultimate goal of this course is to prepare students for a rapidly changing scientific and industrial workforce. Code assistants and AI tools are fundamentally changing many software-centered jobs, reducing the value of purely routine coding skills. At the same time, there is growing demand for people who can combine domain knowledge, machine learning, automated experimentation, and scientific tools. This course is designed to help students prepare for this future and become competitive for high-level internships and industry positions.
2.	Moving from data to decisions: Students will learn how machine learning can support decision-making in materials science, including materials discovery, property prediction, process optimization, imaging, characterization, and automated experimentation.
3.	Bottom-up machine learning and optimization skills: Students will gain foundational knowledge of classical machine learning, including supervised learning, unsupervised learning, dimensionality reduction, deep learning, active learning, optimization, and numerical decision-making methods. These tools provide the mathematical basis for learning from data, estimating uncertainty, and choosing actions.
4.	Top-down agentic and workflow-based reasoning: Students will be introduced to agentic systems that can use tools, follow workflows, assist with planning, and support high-level scientific decision-making. This includes understanding how agents and multi-agent workflows can be designed for specific scientific and engineering domains.
5.	Connecting ML, agents, and domain knowledge: Students will learn how to connect bottom-up ML models with top-down agentic workflows using data representations, metadata, ontologies, knowledge graphs, scientific databases, and executable tool functions. These interface layers are essential for translating scientific intent into computational or experimental actions.
6.	Practical application to materials science problems: Students will learn how to apply ML and AI methods to real-world materials science problems, including imaging and spectroscopy, materials informatics, structure-property relationships, autonomous characterization, automated laboratories, and advanced manufacturing workflows.

Value Proposition:

1.	You are interested in ML and AI and would like to try it hands-on on real world problems from materials science, chemistry, condensed matter physics, and microscopy

2.	Learn the basics of the ML methods and build upon this knowledge - from simple principal component analysis to large language models and causal analysis.

3.	Explore how ML is being adopted by industry - from IT leaders such as Amazon, Google, and Meta to instrumental, chemical, and materials companies. 

4.	Learn why the next decade of ML will be transition from purely in-silico to real-world materials and device applications, and be a part of this transition

5.	And learn to work backwards from real-world problems to solution.

Learning Environment:
The class will be delivered as in-person lectures and recorded by Zoom. The Jupyter notebooks, code libraries, and videos will be provided. Weekly programming exercises will be assigned via Google Colabs (please submit to sergei2vk@gmail.com ) and those students wishing to interact with the instructor in person should attend office hours (please set by e-mail sergei2@utk.edu ). 

Use of ChatGPT, agents, and code assistants:
Strongly encouraged both for programming and written assignments. However, the students have to be aware of the limitations of the generative models.

Canvas: 
All course details, assignments, lecture notes and announcements will be available on Canvas. You are required to be aware of anything posted to the course website. Please update your canvas notification settings. 

Reference Materials:
I will provide copies of lecture notes, presentations, and Colabs on GitHub and Canvas. There is no specific textbook for the course and we will take material from a variety of sources including: 

•	Andrew Bird et al, Python Workshop, https://www.packtpub.com/product/the-python-workshop/9781839218859

•	Sebastian Raschka, Machine Learning with PyTorch and Scikit-Learn, https://subscription.packtpub.com/book/data/9781801819312/1 

•	Rowel Atienza, Advanced Deep Learning with TensorFlow 2 and Keras - Second Edition, https://www.packtpub.com/product/advanced-deep-learning-with-tensorflow-2-and-keras-second-edition/9781838821654

•	(Optional) Alaa Khamis, Optimization Algorithms: AI Techniques for Design, Planning, and Control Problems, https://www.manning.com/books/optimization-algorithms 

•	(Optional)  Peter Norvig, Artificial Intelligence: A Modern Approach, Global Edition, https://www.amazon.com/Artificial-Intelligence-Modern-Approach-Global/dp/1292401133


Assignments:
•	All assignments will be submitted as Google Colabs to sergei2vk@gmail.com (using Gmail allows to avoid lengthy authorization process)
•	Late assignments will be accepted without penalty; however, keep in mind that the level of problems is increasing, and the UT final submission day is fixed
•	Students can work together to solve homework assignments. However, each student must turn in his/her own work in his/her own notebook. 
•	Instances of plagiarism will be addressed as stipulated by University guidelines. The use of ChatGPT or any other LLMs does not constitute plagiarism in this course. Please do not force me to have to deal with plagiarism cases. Remember, you are here to learn.
