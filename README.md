1-Constructing_brain_graphs_topological_metrics.ipynb contains the code and results for constructing
brain networks and computing topological metrics from the data file.

2-Microscopic__Macroscopic__Mesoscopic_Analysis.ipynb contains the code and visualization
of the Exploratory Data Analysis at the microscopic, mesoscopic, and macroscopic levels.

3-Saving_brain_networks.ipynb contains the code to save the brain networks for all subjects to
the local machine since the models need the brain networks to run.

4-Community_Detection_models_subject-wise.ipynb contains the code for the three models that
have been employed in this study.

5-Modularity_NMI_Community_Detection_Evaluation.ipynb contains the model evaluation in
terms of modularity scores and NMI scores mentioned in the results.

6-Jaccard_Similarity_Model_Evaluation.ipynb contains the computation of Jaccard similarity
scores for all the models in comparison with another study.

The ‘dataMSc.mat’ file is the data file containing the functional connectivity matrices for all
subjects, runs, and contrasts.

The ‘fNIRS_channels_anatomical_labels.csv’ file contains the anatomical locations of all the
nodes (channels) to conduct the study.

Packages and libraries required are outlined at the start of each notebook, but most are built into
the Anaconda distribution. All of the codes can be run on a CPU. Before executing the model
codes, the ‘3-Saving_brain_networks.ipynb’ code needs to be run to save the brain networks, and
the ‘dataMSc.mat’ and ‘fNIRS_channels_anatomical_labels.csv’ files need to be downloaded
as well.
