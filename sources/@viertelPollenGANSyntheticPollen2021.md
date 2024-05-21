>[!Cite] [1]

P. Viertel, M. Konig, e J. Rexilius, “PollenGAN: Synthetic Pollen Grain Image Generation for Data Augmentation”, em _2021 20th IEEE International Conference on Machine Learning and Applications (ICMLA)_, Pasadena, CA, USA: IEEE, dez. 2021, p. 44–49. doi: [10.1109/ICMLA52953.2021.00015](https://doi.org/10.1109/ICMLA52953.2021.00015).

>[!Synthesize]
>**Contribution**::

>[!Metadata]
> **Author**:: Viertel, Philipp</br> **Author**:: Konig, Matthias</br> **Author**:: Rexilius, Jan</br>
>**Title**:: PollenGAN: Synthetic Pollen Grain Image Generation for Data Augmentation
>**Year**:: 2021
>**Citekey**:: @viertelPollenGANSyntheticPollen2021
>**itemType**:: conferencePaper
>
>
>
>
>**Publisher**:: IEEE
>**Location**:: Pasadena, CA, USA
> **Pages**:: 44-49
>**DOI**:: 10.1109/ICMLA52953.2021.00015
>**ISBN**:: 978-1-66544-337-1

>[!LINK]
>
>[Viertel et al. - 2021 - PollenGAN Synthetic Pollen Grain Image Generation.pdf](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf).

>[!Abstract]
Palynology, the study of pollen, is becoming the focus of attention in computer vision in recent years. Various proposed automated classiﬁcation and segmentation methods have been evaluated on a number of data sets. However, as of 2021 most data sets are sparse; they either contain only a small number of pollen classes, images in total or are imbalanced overall. In this work, we explore the possibility of creating synthetic pollen grain images from less than 2,000 images per pollen class via a Generative Adversarial Network (GAN). For that purpose, we selected two distinct pollen classes from a state of the art pollen data set and evaluated the data set with and without synthetic data on a Convolutional Neural Network (CNN). The enriched data set performed better overall (+1.4%) and speciﬁcally for the two pollen classes (+2%). We also drastically reduced the no. of real images and were still able to achieve a score of 60% to 80%. The experiments show, that our synthesized pollen images are visually close to real-life pollen grains and can be used to enrich imbalanced data sets as an addition to traditional data augmentation methods.

> [!important]
## Annotations

%% begin annotations %%

### Exported: 2024-05-19 21:22
>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> The experiments show, that our synthesized pollen images are visually close to real-life pollen grains and can be used to enrich imbalanced data sets as an addition to traditional data augmentation methods
>[page 1](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:16]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> POLEN23E
>[page 2](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:17]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> POLLEN13K
>[page 2](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:17]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> NzPollen
>[page 2](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:17]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> cDCGAN
>[page 3](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:18]]

>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> The evaluation of the performance quality of GANs via specific metrics is a challenging task and there exists no definitive method as of 2021
>[page 3](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:18]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> Therefore, we used a CNN, consisting of three Convolutional layers with Max Pooling, ReLU activation functions and an additional Dropout Layer at the end
>[page 4](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:19]]

>[!Note]
></br></br>
>![[sources/images/viertelPollenGANSyntheticPollen2021/image-5-x52-y421.png]]
>[page 5](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:21]]

>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> The average score for all folds on the regular set was 93.2%, and on the enhanced data with synthetic images 94.6% (+1.4%
>[page 5](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:19]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> We utilized precision and especially F1-score for the individual classes
>[page 5](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:20]]

>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> In this work, we showed that it is possible to utilize a GAN to create low-resolution pollen grain images with less than 2,000 images
>[page 5](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:20]]

>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> Although pollen with a large variety of visual characteristics are problematic with such little data, our experiments showed that the same data set performed overall better with added synthetic images by 2% average accuracy
>[page 5](file://C:\Users\maila\Zotero\storage\TBB68ESX\Viertel%20et%20al.%20-%202021%20-%20PollenGAN%20Synthetic%20Pollen%20Grain%20Image%20Generation.pdf) [[2024-05-19 21:20]]

%% end annotations %%

%% Import Date: 2024-05-19T21:22:15.640-03:00 %%
