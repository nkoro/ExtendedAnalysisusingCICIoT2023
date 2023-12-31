# Extended Analysis using CICIoT 2023 Dataset
![system model gif](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/32a41c22-4f1f-4356-a122-a22421406162)
![iciiotdataset](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/7547610f-f672-4357-aec6-900fe5aea43b)


Dataset Distribution of the CICCIoT dataset is provided in the diagram above.


This repository elucidates on the significance of the proposed Zero trust threat model on a larger volume of DDoS attacks appraised using the CICIoT2023 data set.
Specifically the consistence of the proposed DNN model within the original model prediction, adversarial perturbation, adversarial training and parameter protection using the CICIoT2023 dataset is provided for additional validation.



# Visual Threat Model Results using the CICIoT 2023 Dataset

## Original, Perturbed and Adversarial trained DNN model

A. _Confusion Matrix of the DNN model Results_:

The diagrams below shows the confusion matrix of the original, perturbed, and adversarial trained DNN models.
![conf orifinal](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/474b215d-4e99-4084-8a86-3b6fae3ce9cb)
![conf perturbed](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/82da4667-c0cf-4f63-bfeb-8b5b11bd0d26)
![conf adv](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/9cd47add-4b39-4a4b-862a-40c9ecf9e1e1)
1bd0d26)


B. _Training and Vallidation loss plot of the DNN model Results_:

The diagrams below shows the learning process path of the training and validation loss plot of the original, perturbed, and adversarial trained DNN.
models of the original, perturbed and adversarial trained DNN models.
![original crossval](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/b55b73dd-af03-4202-89d9-a14f8260f490)
![perturbation cross val](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/81521580-3330-4be4-a1dc-ba22cabaf3a6)
![adv crossval](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/28662697-e5bc-4118-adcb-03c23c0e6667)

C. _UMAP of the DNN model Results_:

The diagrams below shows the UMAP plot of the original, perturbed, and adversarial trained DNN models of the original, perturbed and adversarial trained DNN models.
![umap original](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/a364c571-e3c4-4e3a-aa8f-4ebd8e21c71a)
![umap perturbed](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/7441f9fe-412f-4936-847c-6e8fa2773366)
![umap adv](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/ec3e0e71-3572-4f42-8a9c-160650771f62)


## Parameter Protection of DNN model using the SAP and IR
The segment below contains the visual results of the Parameter protection methods using the Stochastic activation prunning (SAP) and Input Randomization (IR).

A. _Confusion Matrix of the SAP and IR DNN model Results_:

The diagrams below shows the confusion matrix of the original, perturbed, and adversarial trained DNN models.
![PP conf SAP](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/9d505a83-0221-42d1-9bf9-974b6204deee)
![PP conf IR](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/ade93790-533b-42bb-b036-026b157243c4).

B. _Training and Vallidation loss plot of the SAP and IR DNN model Results_:

The diagrams below shows the learning process path of the training and validation loss plot of the SAP and IR DNN.
models.
![IR crossval](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/2b63953e-06e6-4bc1-a684-db05e9db5213)
![sap cross val](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/39217a05-28d9-432a-bda8-01efb71d7024)

C. _UMAP of the SAP and IR DNN model Results_:

The diagrams below shows the UMAP plot of the SAP and IR DNN models.
![PP umap using SAP](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/f4c0710e-fc2c-46c0-aa15-25e663ede62f)
![umap IR](https://github.com/nkoro/ExtendedAnalysisusingCICIoT2023/assets/83587677/56ed3e7d-6897-4e61-8e01-bcac7d61088a)
