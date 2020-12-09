# NLP_project
Question answering (QA) is a computer science discipline within the fields of information retrieval and natural language processing (NLP), which is concerned with building systems that automatically answer questions posed by humans in a natural language. A question answering implementation, usually a computer program, may construct its answers by querying a structured database of knowledge or information, usually a knowledge base. More commonly, question answering systems can pull answers from an unstructured collection of natural language documents.
Some examples of natural language document collections used for question answering systems include: a local collection of reference texts, internal organization documents and web pages, compiled newswire reports, a set of Wikipedia pages, a subset of World Wide Web pages etc. Question answering research attempts to deal with a wide range of question types including: fact, list, definition, How, Why, hypothetical, semantically constrained, and cross-lingual questions.
Closed-domain question answering deals with questions under a specific domain (for example, medicine or automotive maintenance), and can exploit domain-specific knowledge frequently formalized in ontologies. Alternatively, closed-domain might refer to a situation where only a limited type of questions are accepted, such as questions asking fordescriptiverather than procedural information. Question answering systems in the context of machine reading applications have also been constructed in the medical domain, for instance related to Alzheimer's disease.
Open-domain question answering deals with questions about nearly anything and can only rely on general ontologies and world knowledge. On the other hand, these systems usually have much more data available from which to extract the answer. Multimodal question answering uses multiple modalities of user input to answer questions, such as text and images.

# Question-Answer-Generation
Question answering (QA) is a computer science discipline within the fields of information retrieval and natural language processing (NLP), which is concerned with building systems that automatically answer questions posed by humans in a natural language.

In this project, two question anaswer generation models are implemented. They are:

# Dense Passage Retrieval (DPR)
Answer-Clue-Style-aware Question Generation (ACS-QG)
Dataset Details
The dataset for this work is the Stanford Question Answering Dataset (SQuAD), a new reading comprehension dataset consisting of 100,000+ questions posed by crowdworkers on a set of Wikipedia articles, where the answer to each question is a segment of text from the corresponding reading passage.

# Number of Instances: 87599 Features:

title: Name of the University
context: Context of the question
question: Asked Question
answer: Given Answer
answer_start: Answer start
answer_end: Answer End
