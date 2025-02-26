This code accompanies the paper <em>[Medical Profile Model: Scientific and Practical Applications in Healthcare](https://arxiv.org/abs/2107.03913)</em> by Pavel Blinov and Vladimir Kokh.

![model](./model_arch.png)

Some data preprocessing code is from https://github.com/xueping/MusaNet

### To run
- Check / install the dependencies:
```bash
pip install -r requirements.txt
```
- Open the ```mimic3.profile.ipynb``` notebook:
	- Set variable MIMIC_PATH;
	- Run all the cells.

### BibTeX reference
```
@ARTICLE{10268588,
  author={Blinov, Pavel and Kokh, Vladimir},
  journal={IEEE Journal of Biomedical and Health Informatics}, 
  title={Medical Profile Model: Scientific and Practical Applications in Healthcare}, 
  year={2024},
  volume={28},
  number={1},
  pages={450-458},
  keywords={Medical diagnostic imaging;Task analysis;Data models;Codes;
Predictive models;Diseases;Transformers;Electronic Health Record (EHR);
representation learning;medical knowledge mining;transformer neural network;
Medical Information Mart for Intensive Care (MIMIC)-III},
  doi={10.1109/JBHI.2023.3321132}}
```

