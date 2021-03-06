[Click here to go back to the home page.](https://brainhack-zurich.github.io/)


# List of Projects


## Quality control in MRI data
*Franz Liem (franziskus.liem@uzh.ch)*

We will discuss approaches to check quality of structural and functional MRI data (T1w, diffusion and functional data; raw data and derivatives like FreeSurfer reconstructions). We will also look into tools that help to visually check data quality and extract metrics of data quality.


    
## Dynamical Functional Connectivity in the Brain Networks 
*Alessandro Crimi (alessandro.crimi@usz.ch)*

There is a growing conviction that the understanding of the brain function can come through a deeper knowledge of the network connectivity between different brain areas. This connectivity is usually described by graphs, where brain regions are nodes and functional correlation between them are weighted edges. The advent of this graphical interpretation of brain, often called connectomics, has changed the way to study brain functions. It is in fact common practice to exploit graph theory tools to characterize the brain functions with this graph-based perspective (Rubinov and Sporns 2010). Dynamic functional connectivity refers to the observed phenomenon that functional connectivity changes over a short time (Preti et al. 2016). In neuroscience a related question is on how neural units cluster into densely interconnected groups which provide coordinated activities such as perception, action, and adaptive behaviors (Khambhati et al. 2017). A study on how neural units (nodes on a graph) cluster over time is therefore attractive.  In this project we want to model fMRI signal as a graph changing in time. Investigating issues related to this graph construction and 
graph partitioning. Python implementations jointly with common issues of fMRI signals will be discussed.

Suggested reading: Preti, M. G., Bolton, T. A., & Van De Ville, D. (2016). The dynamic functional connectome: Stateof-the-art and perspectives. NeuroImage.


    
## [SAMRI (Small Animal Magnetic Resonance Imaging)](https://github.com/IBT-FMI/SAMRI)
*[Horea Christian](https://www.researchgate.net/profile/Horea_Christian)  (ioanas@biomed.ee.ethz.ch)*

SAMRI is a high-level toolkit, which automatically, transparently, and reproducibly takes you from raw scanner data to beautiful figures, and gives you access to numerous small-animal optimizations in data processing and analysis.

This sprint is a great opportunity for you to work together with us in bringing the power of SAMRI to your specific line of work - or for you to gain insight into the most common animal MRI workflows by helping us address existing issues.
We will have testing/validation data available, and we're happy to help you get acquainted with everything!


    
## Statistical methods for longitudinal data
*Jessica Oschwald ( jessica.oschwald@uzh.ch)*

We will discuss and compare different statistical methods suited to analyze longitudinal data, with a focus on modeling change processes over time (e.g., multilevel models, latent change models). Specifically, we will talk about the most common issues encountered when fitting these type of models, with the aim of identifying best practices. How can we compute a measure of effect size? How do we decide on the best fitting model? What are tools that can help with fitting and visualizing model outputs?


    
## Migraine Tiger
*Pieter De Bakker, Roy Morrison, Sébastien Guarnay (pieter_db@hotmail.com)*

1 out of 7 people’s lives are negatively impacted by migraine. We want to create an intelligent app to help patients manage their disease better than the current alternatives. We will do this by letting a smart watch track real-time health data which will give non-biased insights in the triggers of your migraine. In that way we want to help the patient avoid having migraine attacks.

Currently our idea is pre-seed phase and we do have a complete skill set on board except the neuroscientific background. Therefore we are looking for someone who can give input on the medical side of our value proposition.



    
## Pattern recognition on brain image
*Hongyu luo (Luo.hongyu@outlook.com)*

I would like to using machine learning algorithm on brain image data
Ideally, we could use python(pyMVPA, keras) or matlab(SPM, The Decoding Toolbox). But I’m also open to other packages if possible.
I’m open to talk about the method or work on project.

Hebart et al. (2014). http://doi.org/10.3389/fninf.2014.00088
Pereira et al. (2009). http://doi.org/10.1016/j.neuroimage.2008.11.007
Shirer et al. (2012). http://doi.org/10.1093/cercor/bhr099


    
## sweetData
*Ronald Sladky (ronald.sladky@uzh.ch)*

Organizing neuroimaging, behavioral, and psychometric data can be challenging. While there are standardized formats that help you to organize your processed data (e.g., BIDS), we could also use technologies that help us to manage our raw data, which sometimes (actually, too often!) need to be transferred using unreliable methods, such as USB drives.

Objectives:
- To test data integrity (Did I transfer all runs from my MR Scanner? Are the MR images exported correctly or did the export skip some of the volumes? Did I copy all the logfiles from the other computer(s)?)
- To monitor project status (Did I convert all the files on the server into the right format? What is the status of my backups?)
- To perform routine actions automatically (transferring files, file conversion, backups) and inform me if something goes wrong
- To develop a framework that is easily adaptable to many different lab setups and requirements
- To make this framework easy to setup and use for novice researchers and even PI's
- To allow for quick queries on your project status, which allow you to respond to missing data etc. quickly (e.g., before it is removed from your MR scanner image database)

In this project we would like to brainstorm the requirements and conceptualize possible implementations of this data organization tool.


    