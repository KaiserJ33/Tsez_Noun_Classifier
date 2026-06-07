# Tsez_Noun_Classifier
This project investigates how learners acquire noun class distinctions in Tsez, a Northeast Caucasian language spoken in Dagestan. The study uses probabilistic learning models to examine how phonological and semantic cues contribute to the acquisition of noun class membership.
Please note--the shell and some parameters were provided by the instructor.

The project was developed as part of graduate coursework in Computational Linguistics and explores computational approaches to language learning and category acquisition.

Research Question

How do learners use phonological and semantic information to acquire noun class distinctions in Tsez?

More specifically:

Which combination of linguistic cues best predicts noun class membership during learning?

Background

Tsez contains a complex noun class system in which nouns belong to grammatical categories that influence agreement patterns throughout the language.

Unlike grammatical gender systems found in many European languages, Tsez noun classes are only partially predictable from semantic meaning. Learners must therefore rely on multiple sources of information when determining class membership.

This project models the acquisition process using probabilistic learning algorithms.

Data

The dataset consists of Tsez nouns annotated for:

Noun class membership
Semantic category information
Phonological features
Lexical properties

These features serve as cues that a learner may use when predicting noun class.

Methodology

The project implements Naive Bayes learning models that estimate noun class membership from available linguistic cues.

Several learning conditions were examined:

Semantic information only
Phonological information only
Combined semantic and phonological information
Weighted cue integration models

Model performance was evaluated by comparing predicted noun classes against known classifications.

Models

The project includes multiple probabilistic learning models, including:

Phonology-Only Model

Uses phonological features as the sole predictor of noun class.

Semantics-Only Model

Uses semantic information without phonological cues.

Combined Model

Integrates both semantic and phonological information.

Weighted Cue Integration Model

Explores how varying the relative importance of semantic and phonological cues affects learning outcomes.

Evaluation

Model performance was assessed through:

Prediction accuracy
Error analysis
Sum of Squared Error (SSE)
Comparison across learning conditions

The results allow direct comparison of different cue types and their contribution to noun class acquisition.

Technologies Used
Python
NumPy
Pandas
Naive Bayes Classification
Probabilistic Modeling
Computational Linguistics
Google Colab
Repository Structure
├── tsez_noun_class_learning.ipynb
├── data/
├── results/
├── README.md
Results

The experiments demonstrate that combining multiple linguistic cues improves noun class prediction relative to single-cue models.

The findings support the view that language learners integrate both phonological and semantic information when acquiring grammatical categories.

Skills Demonstrated
Computational Linguistics
Natural Language Processing
Probabilistic Modeling
Naive Bayes Classification
Data Analysis
Python Programming
Cognitive Modeling
Language Acquisition Research
Linguistic Significance

This project contributes to the study of language acquisition by examining how learners acquire complex grammatical classification systems. The results provide insight into how multiple sources of linguistic information can be integrated during learning.

Author

Joseph Kaiser

M.S. Computational Linguistics, Montclair State University

M.A. Forensic Linguistics, Aston University
