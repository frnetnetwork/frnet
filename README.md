# Contrastive Learning for Click-Through Prediction
This is our implement for CL4CTR

### How to run the code.
1. Download corresponding datasets. 
   - [Criteo](https://labs.criteo.com/2014/02/download-kaggle-display-advertising-challenge-dataset/)
   - [Frappe](https://github.com/hexiangnan/neural_factorization_machine)
   - [Ml-tag](https://github.com/hexiangnan/neural_factorization_machine)
   - [Malware](https://www.kaggle.com/competitions/microsoft-malware-prediction/data)

2. For example, put the Frappe or Ml-tag data in the corresponding folder.
3. Run the code with GPU:

    ```CUDA_VISIBLE_DEVICES=0 python main_ml_base.py --choice 0```

###  You can cite this article:
 Fangye Wang, Yingxu Wang, Dongsheng Li, Hansu Gu, Tun Lu, Peng Zhang,and Ning Gu. 2022. Enhancing CTR Prediction with Context Aware FeatureRepresentation Learning. In Proceedings of the 44th International ACM SIGIRConference on Research and Development in Inform
````
@inproceedings{wang2021enhancing,
  title={Enhancing CTR Prediction with Context-Aware Feature Representation Learning},
  author={Wang, Fangye and Wang, Yingxu and Li, Dongsheng and Gu, Hansu and Lu, Tun and Zhang, Peng and Gu, Ning},
  booktitle={Proceedings of the 43th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  year={2021}
}
````