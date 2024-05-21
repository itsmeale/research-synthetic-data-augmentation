>[!Cite] [1]

Y.-J. Lin e I.-F. Chung, “Medical Data Augmentation Using Generative Adversarial Networks : X-ray Image Generation for Transfer Learning of Hip Fracture Detection”, em _2019 International Conference on Technologies and Applications of Artiﬁcial Intelligence (TAAI)_, Kaohsiung, Taiwan: IEEE, nov. 2019, p. 1–5. doi: [10.1109/TAAI48200.2019.8959908](https://doi.org/10.1109/TAAI48200.2019.8959908).

>[!Synthesize]
>**Contribution**::

>[!Metadata]
> **Author**:: Lin, Ying-Jia</br> **Author**:: Chung, I-Fang</br>
>**Title**:: Medical Data Augmentation Using Generative Adversarial Networks : X-ray Image Generation for Transfer Learning of Hip Fracture Detection
>**Year**:: 2019
>**Citekey**:: @linMedicalDataAugmentation2019
>**itemType**:: conferencePaper
>
>
>
>
>**Publisher**:: IEEE
>**Location**:: Kaohsiung, Taiwan
> **Pages**:: 1-5
>**DOI**:: 10.1109/TAAI48200.2019.8959908
>**ISBN**:: 978-1-72814-666-9

>[!LINK]
>
>[Lin and Chung - 2019 - Medical Data Augmentation Using Generative Adversa.pdf](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf).

>[!Abstract]
In the medical domain, it is difficult to retrieve large datasets. Classic data augmentation methods such as flipping, rotating, and scaling, are helpful in classification tasks, but these methods usually are not good enough to increase diversities and variances in small datasets. In this study, we applied AC-GAN (Auxiliary Classifier GANs) for data augmentation of our Limb X-ray dataset. We pre-trained the model for hip fracture detection of our Pelvic X-ray dataset by utilizing transfer learning with the augmented Limb X-ray dataset, which contained both the original dataset and realistic synthetic images made by the AC-GAN. The final hip fracture classification results of the Pelvic X-ray dataset showed that our generative model not only succeeded in producing realistic Limb X-ray data but also helped improve the performance of the transfer learning model for hip fracture detection.

> [!important]
## Annotations

%% begin annotations %%

### Exported: 2024-05-19 21:41
>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> —In the medical domain, it is difficult to retrieve large datasets. Classic data augmentation methods such as flipping, rotating, and scaling, are helpful in classification tasks, but these methods usually are not good enough to increase diversities and variances in small datasets
>>- Métodos clássicos não são suficientes em alguns casos para ganhos de desempenho.
>[page 1](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:37]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> AC-GAN
>[page 1](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:37]]

>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> The final hip fracture classification results of the Pelvic X-ray dataset showed that our generative model not only succeeded in producing realistic Limb X-ray data but also helped improve the performance of the transfer learning model for hip fracture detection
>[page 1](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:37]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> Limb X-ray
>[page 2](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:38]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> Pelvic X-ray
>[page 2](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:38]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> The datasets are both from Dr. Chi-Tung Cheng, an attending physician at the Linkou Chang-Gung Memorial Hospital, and both of the datasets have been de-identified
>[page 2](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:38]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> As the flowchart illustrates in Figure 2, we used VGG-16 model [18] for classification tasks. Beside the training of AC-GAN, we also trained the VGG-16 CNN model with the Limb X-ray dataset for the selection of images with the best qualities. Then we made the synthetic images as input for the trained VGG-16 CNN model to let the model make predictions for every synthetic image, for automatic selection of realistic images
>[page 3](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:39]]

>[!Note]
></br></br>
>![[sources/images/linMedicalDataAugmentation2019/image-5-x43-y631.png]]
>[page 5](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:40]]

>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> In our approach using transfer learning, the hip fracture model of the “with GAN” group has better performance in hip fracture classification than the model of the “without GAN” group
>[page 5](file://C:\Users\maila\Zotero\storage\965HCJYD\Lin%20and%20Chung%20-%202019%20-%20Medical%20Data%20Augmentation%20Using%20Generative%20Adversa.pdf) [[2024-05-19 21:40]]

%% end annotations %%

%% Import Date: 2024-05-19T21:41:27.764-03:00 %%
