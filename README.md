# S2SNet
S2SNet ‐ Sequence to Star Network software

Sequence to Star Network (S2SNet) is a free Python application using wxPython for the GUI and Graphviz as plotting back-end. S2SNet helps you to transform the character sequences/strings into Star Network (SN) topological indices (TIs) and visualize the resulted graphs. These indices are the input data for the statistical analysis. Some examples of sequences are protein amino acid chains, DNA/RNA strands, mass spectra or electroencephalograms (EEG), social or legal sciences texts or code, etc.

# Algorithm origin:

S2SNET is based on MARCH-INSIDE: Markov Chain Invariants for Networks Simulation and Design MARCH-INSIDE (MI), a well-known method introduced by Prof. Humbert G Díaz (Gonzaléz-Díaz et al.) as early as 2002 for the calculation of Markov Invariants (Moments, Shanon entropies, Mean Markov values) of molecular graphs and complext netxorks using a Markov chain stchastic approach. MINODES extend MI algorithms ideas in order to calculate MI node centralities of complex networks. Some of these MI node centralities are Markov kth-node degrees, Markov kth-node clossenes, etc.; which are kth higher order analogues of classic node centralities now re-calculated and extended to higher order analogues using a MI approach. MINODES is able to read multiple files of complex networks (protein interaction networks, metabolic networks, social networks, etc.) in .mat, .net, and other formats and return MI node centralities of all nodes in the network. In case you want to develop new collaborations, applications, etc. related to MI algorith please do not hesitate to contact us at Linkedin: Prof. C.R. Munteanu https://www.linkedin.com/in/muntisa/ and/or Prof. Humbert G. Díaz https://www.linkedin.com/in/humbertgdiaz/.

# S2SNET Related Algorithms:

MARCH-INSIDE (MI) algorithm is the original algorithm https://github.com/glezdiazh/MARCH-INSIDE on which MINODES is based. Other algorithms based also on MI and then related to MINDOES somehow are: Sequence to Stars Networks (S2SNET) by C.R. Munteanu and González-Díaz H. https://github.com/muntisa/S2SNet); R-Markov Topological Indices (RMARKOVTI) by C.R. Munteanu https://github.com/muntisa/RMarkovTI, S2SNET Phyton (PyS2SNET) by C.R. Munteanu https://github.com/muntisa/pyS2SNet, etc.

# S2SNET Main authors contributions:

C.R. munteanu (algorithm and software design, software programing, AI/ML applications, main author of papers, https://github.com/muntisa/).

H. Gónzalez-Díaz (algorithm and software design, AI/ML applications, main author of papers, https://github.com/glezdiazh),

A. Duardo-Sánches (assistance with intellectual proprty issues and co-author of papers for social and legal networks analysis, https://github.com/aliuskaduardo)

# What S2SNet can do

* Transform 1-character sequences in topological Star Networks indices
* Transform number data in 1-character sequences (No2Seq)
* Transform N-character sequence in 1-character sequence by changing the codification
* Edit/View your input and output TXT files
* Create DOT language files
* Plot and display networks as PNG images

### Extra scripts

* Transform FASTA format into S2SNet format
* Scripts for different FASTA formats (Chembl, original FASTA, etc.)

# Publications with S2SNet

* S2SNet: A Tool for Transforming Characters and Numeric Sequences into Star Network Topological Indices in Chemoinformatics, Bioinformatics, Biomedical, and Social-Legal sciences, Current Bioinformatics 8(4), 429-437 (2013) | Cristian R. Munteanu, Alexandre L Magalhães, Aliuska Duardo Sánchez, Alejandro Pazos, Humberto González-Díaz
* Classification of signaling proteins based on molecular star graph descriptors using Machine Learning models, Journal of Theoretical Biology 384, 50-58, DOI: 10.1016/j.jtbi.2015.07.038 (2015) | Carlos Fernandez-Lozano, Rubén F. Cuiñas, José A. Seoane, Enrique Fernández-Blanco, Julian Dorado, Cristian R. Munteanu
* Prediction of Nucleotide Binding Peptides using Star Graph Topological Indices, Molecular Informatics Volume 34(11-12), 736–741, DOI: 10.1002/minf.201500064 (2015) | Yong Liu, Cristian R. Munteanu, Enrique Fernández Blanco, Zhiliang Tan, Antonino Santos del Riego, Alejandro Pazos
* Kernel-Based Feature Selection Techniques for Transport Proteins Based on Star Graph Topological Indices, Current Topics in Medicinal Chemistry 13(14), 1681-1691 (2013) | Carlos Fernandez-Lozano, Marcos Gestal, Nieves Pedreira-Souto, Lucian Postelnicu, Julián Dorado, Cristian R. Munteanu
* Random Forest Classification based on Star Graph Topological Indices for Antioxidant Proteins, Journal of Theoretical Biology 317, 331-337 (2013) | Enrique Fernandez-Blanco, Vanessa Aguiar-Pulido, Cristian R Munteanu, Julian Dorado
* Automatic Seizure Detection Based on Star Graph Topological Indices,  Journal of Neuroscience Methods 209(2), 410–419 (2012) | Enrique Fernandez-Blanco, Daniel Rivero, Juan Rabuñal, Julián Dorado, Alejandro Pazos, Cristian Robert Munteanu
* Star Graphs of Protein Sequences and Proteome Mass Spectra in Cancer Prediction, Current Proteomics 6(4), 275-288 (2009) | José M. Vázquez, Vanessa Aguiar, Jose A. Seoane, Ana Freire, José A. Serantes, Julián Dorado, Alejandro Pazos, Cristian R. Munteanu
* Alignment-free prediction of Mycobacterial DNA promoters based on Pseudo-folding Lattice Network or Star-Graph Topological Indices, Journal of Theoretical Biology 256(3), 458–466 (2009) | Alcides Perez-Bello, Cristian R. Munteanu, Florencio M. Ubeira, Alexandre Lopes De Magalhães, Eugenio Uriarte and Humberto González-Díaz
* Multi-Target QPDR Classification Model for Human Breast and Colon Cancer-Related Proteins using Star Graph Topological Indices, Journal of Theoretical Biology 257(2), 303–311 (2009) | Cristian R Munteanu, Alexandre L Magalhães, Eugenio Uriarte,  Humberto González-Díaz
* Stochastic molecular descriptors for polymers. 4. Study of complex mixtures with topological indices of mass spectra spiral and star networks: the blood proteome case, Polymer 49(25),  5575–5587 (2008) | Maykel Cruz-Monteagudo, Cristian R. Munteanu, Fernanda Borges, M. Natália D.S. Cordeiro, Eugenio Uriarte, Kuo-Chen Chou and Humberto González-Díaz
* Natural/random protein classification models based on star network topological indices, Journal of Theoretical Biology 254(4), 775–783 (2008) | Cristian R Munteanu, Humberto González-Díaz, Fernanda Borges, Alexandre L Magalhães
