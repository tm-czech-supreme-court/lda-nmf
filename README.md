# lda-nmf
Dear visitor,

This is **"Topic Modelling of Czech Supreme Court Decisions"** repository containing all the relevant data and code for topic modelling of the Czech Supreme Court decisions with latent Dirichlet allocation (LDA) and non-negative matrix factorization (NMF) methods.
This repository contains 5 Jupyter notebooks with all the relevant code for preprocessing of documents, training the models and their topics visualization via pyLDAvis using LDA and NMF methods. 
The Czech Supreme Court decisions from the Czech Court Decisions Corpus 1.0 are used for experimental LDA and NMF models training with the goal of better legal information retrieval. The methodology of the project contains 10 models training for each method with number of topics *k = {10, 20, 30, 40, 50, 60, 70, 80, 90, 100}*. Coherence score *CV* is used for models coherence comparison.

Data and methodology of this experiment is described in: NOVOTNÁ, Tereza, Jakub HARAŠTA a Jakub KÓL. Topic Modelling of the Czech Supreme Court Decisions. In Kevin D. Ashley, Katie Atkinson, L. Karl Branting, Enrico Francesconi, Matthias Grabmair, Vern R. Walker, Bernhard Waltl, Adam Zachary Wyner. Proceedings of the Fourth Workshop on Automated Semantic Analysis of Information in Legal Text held online in conjunction with the 33rd International Conference on Legal Knowledge and Information Systems (JURIX 2020). CEUR WS, vol. 2764. Aachen, Německo: CEUR Workshop Proceedings, 2020. s. 1-5. ISSN 1613-0073. Available at: http://ceur-ws.org/Vol-2764/paper3.pdf

This experiment was prepared at Masaryk university as part of the project ”Automatic processing of court decisions: user experiment” number MUNI/A/1454/2019 with the support of the Specific University Research Grant, as provided by the Ministry of Education, Youth and Sports of the Czech Republic in the year 2020. Available at: https://www.muni.cz/en/research/projects/54168

##Useful relevant links:
Czech Court Decisions Corpus 1.0 is freely available at: https://lindat.mff.cuni.cz/repository/xmlui/handle/11372/LRT-3052#
All the topics visualizations for all the models are available at: https://github.com/tm-czech-supreme-court/lda-nmf-models

All the codes are available under the MIT License (available at: https://opensource.org/licenses/MIT).

##License terms and contacts
In the case of any further questions, please contact Tereza Novotná: tereza.novotna@mail.muni.cz.
Tereza Novotná, Jakub Harašta (Institute of Law and Technology, Masaryk University, Brno, CZ)
Jakub Kól (Atlas Consulting, s.r.o., Ostrava, CZ)
