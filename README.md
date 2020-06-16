# Thesis-KPMG
Code for my master thesis data science

1. Preprocessing consists of the code where the emails are parsed and tokenized into a useful dataframe. Furthermore, it contains the code where metadata-features are extracted from the email dataset.

2. Textclassifiers consists of the code that was used to train the text classification models. All steps described in the research paper are findable in the code. 

3. Metafeature integration consists of the code for the 3 scenarios described in the research paper. The stacking techniques are also described in a formula. There are many overlapping functions that are used for section 2 and in all three scenarios. 

4. Stuctural Correspondence Learning consists of code that was used to produce the simple baseline, compute the proxy alpha-distance and apply the SCL algorithm. The SCL class is an extended version from the original SCL algorithm by Blitzer et al (2006) https://dl.acm.org/doi/10.5555/1610075.1610094.
