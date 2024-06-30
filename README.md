# Quality Analysis of Additive Manufacturing using Deep Belief Network

***Additive Manufacturing*** (AM), commonly known as 3D printing, has emerged as a transformative technology in various industrial sectors, offering unprecedented flexibility and efficiency in production processes.
However, despite its potential, the widespread adoption of AM is hindered by challenges related to quality control, process optimization, and material characterization. 

One of the critical factors influencing the quality and reliability of AM processes is the ability to accurately classify and identify defects in manufactured components. Traditional approaches to defect detection often rely on manual inspection or rule-based systems, which are time-consuming, labor-intensive.


The primary objective of this research is to develop ***Deep Belief Network*** model from scratch, 
followed by an investigation of the feasibility and effectiveness of using DBNs 
for data augmentation in AM datasets and an evaluation of the impact of dataset 
size on the classification performance of DBN models. We aim to demonstrate 
the potential of our approach in overcoming the challenges of limited data and 
improving the reliability of defect detection systems in AM. 

In this study, we utilize an image dataset sourced from 
https://data.mendeley.com/datasets/zyz6cznm5h/3, which comprises a diverse 
collection of Artifact images AM through Fused Deposition Modelling.

The architecture of the DBN model utilized in this research was developed using 
the PyTorch framework. The implementation incorporates various techniques, 
including **Contrastive Divergence** (CD), **Gibbs sampling**, and **cross-entropy 
optimization**, to train the DBN model effectively. CD and Gibbs sampling are 
used to approximate the intractable posterior distribution of the model's 
parameters, while cross-entropy optimization is employed to minimize the 
reconstruction error and fine-tune the model parameters. 
