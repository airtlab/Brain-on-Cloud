# Brain-on-Cloud for automatic diagnosis of Alzheimer's disease from 3D structural magnetic resonance whole-brain scans
This repository contains the source code of the framework presented in the paper

>Selene Tomassini, Agnese Sbrollini, Giacomo Covella, Paolo Sernani, Nicola Falcionelli, Henning Müller, Micaela Morettini, Laura Burattini, Aldo Franco Dragoni, *Brain-on-Cloud for automatic diagnosis of Alzheimer’s disease from 3D structural magnetic resonance whole-brain scans*

available at https://doi.org/10.1016/j.cmpb.2022.107191.

# Abstract
Background and objective: Alzheimer’s disease accounts for approximately 70% of all dementia cases. Cortical and hippocampal atrophy caused by Alzheimer’s disease can be appreciated easily from a T1-weighted structural magnetic resonance scan. Since a timely therapeutic intervention during the initial stages of the syndrome has a positive impact on both disease progression and quality of life of affected subjects, Alzheimer’s disease diagnosis is crucial. Thus, this study relies on the development of a robust yet lightweight 3D framework, Brain-on-Cloud, dedicated to efficient learning of Alzheimer’s disease-related features from 3D structural magnetic resonance whole-brain scans by improving our recent convolutional long short-term memory-based framework with the integration of a set of data handling techniques in addition to the tuning of the model hyper-parameters and the evaluation of its diagnostic performance on independent test data.
Methods: For this objective, four serial experiments were conducted on a scalable GPU cloud service. They were compared and the hyper-parameters of the best experiment were tuned until reaching the best-performing configuration. In parallel, two branches were designed. In the first branch of Brain-on-Cloud, training, validation and testing were performed on OASIS-3. In the second branch, unenhanced data from ADNI-2 were employed as independent test set, and the diagnostic performance of Brain-on-Cloud was evaluated to prove its robustness and generalization capability. The prediction scores were computed for each subject and stratified according to age, sex and mini mental state examination.
Results: In its best guise, Brain-on-Cloud is able to discriminate Alzheimer’s disease with an accuracy of 92% and 76%, sensitivity of 94% and 82%, and area under the curve of 96% and 92% on OASIS-3 and independent ADNI-2 test data, respectively.
Conclusions: Brain-on-Cloud shows to be a reliable, lightweight and easily-reproducible framework for automatic diagnosis of Alzheimer’s disease from 3D structural magnetic resonance whole-brain scans, performing well without segmenting the brain into its portions. Preserving the brain anatomy, its application and diagnostic ability can be extended to other cognitive disorders. Due to its cloud nature, computational lightness and fast execution, it can also be applied in real-time diagnostic scenarios providing prompt clinical decision support.

# Citation
BibTeX entry:

	 @article{tomassini2022brain,
	 title={Brain-on-Cloud for automatic diagnosis of Alzheimer’s disease from 3D structural magnetic resonance whole-brain scans},
	 author={Tomassini, Selene and Sbrollini, Agnese and Covella, Giacomo and Sernani, Paolo and Falcionelli, Nicola and M{\"u}ller, Henning and Morettini, Micaela and Burattini, Laura and Dragoni, Aldo Franco}, 
	 journal={Computer Methods and Programs in Biomedicine},
	 pages={107191},
	 year={2022},
	 publisher={Elsevier},
	 doi={https://doi.org/10.1016/j.cmpb.2022.107191}
	 }