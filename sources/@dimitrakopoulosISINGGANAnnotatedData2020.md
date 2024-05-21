>[!Cite] [1]

P. Dimitrakopoulos, G. Sfikas, e C. Nikou, “ISING-GAN: Annotated Data Augmentation with a Spatially Constrained Generative Adversarial Network”, em _2020 IEEE 17th International Symposium on Biomedical Imaging (ISBI)_, Iowa City, IA, USA: IEEE, abr. 2020, p. 1600–1603. doi: [10.1109/ISBI45749.2020.9098618](https://doi.org/10.1109/ISBI45749.2020.9098618).

>[!Synthesize]
>**Contribution**::

>[!Metadata]
> **Author**:: Dimitrakopoulos, P.</br> **Author**:: Sfikas, G.</br> **Author**:: Nikou, C.</br>
>**Title**:: ISING-GAN: Annotated Data Augmentation with a Spatially Constrained Generative Adversarial Network
>**Year**:: 2020
>**Citekey**:: @dimitrakopoulosISINGGANAnnotatedData2020
>**itemType**:: conferencePaper
>
>
>
>
>**Publisher**:: IEEE
>**Location**:: Iowa City, IA, USA
> **Pages**:: 1600-1603
>**DOI**:: 10.1109/ISBI45749.2020.9098618
>**ISBN**:: 978-1-5386-9330-8

>[!LINK]
>
>[Dimitrakopoulos et al. - 2020 - ISING-GAN Annotated Data Augmentation with a Spat.pdf](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf).

>[!Abstract]
Data augmentation is a popular technique with which new dataset samples are artiﬁcially synthesized to the end of assisting training of learning-based algorithms and avoiding overﬁtting. Methods based on generative adversarial networks (GANs) have recently rekindled interest in research on new techniques for data augmentation. With the current paper we propose a new GAN-based model for data augmentation, comprising a suitable Markov random ﬁeld-based spatial constraint that encourages synthesis of spatially smooth outputs. Oriented towards use with medical imaging sets where a localization/segmentation annotation is available, our model can simultaneously also produce artiﬁcial annotations. We gauge performance numerically by measuring performance through U-Net trained to detect cells on microscopy images, by taking into account the produced augmented dataset. Numerical trials, as well as qualitative results validate the contribution of our model.

> [!important]
## Annotations

%% begin annotations %%

### Exported: 2024-05-19 18:38
>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> In this work, a method for data augmentation is presented and tested succesfully in the context of augmenting sets of microscopy images
>[page 1](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf) [[2024-05-19 17:36]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> BBBC038v1
>[page 2](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf) [[2024-05-19 17:38]]

>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> Treating the whole set at once would have been possible with a conditional GAN; however, as shown in [7], training k separate GANs for k modes gives better results than a single conditional GAN, and we have chosen to follow this approach as well
>>- Treinar uma GAN para cada "classe" performa melhor do que utilizar GANs condicionais, verificar literatura.
>[page 3](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf) [[2024-05-19 18:27]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> We also compare our model against classical, non GAN-based data augmentation methods
>>- Baseline de técnicas de data augmentation não baseadas em GANs
>[page 3](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf) [[2024-05-19 18:31]]

>[!Note]
><mark style="background-color: #e56eee">Highlight</mark></br></br>> We have furthermore used the Fr ́ echet Inception distance (FID) to gauge numerically the effectiveness of the proposed model
>>- Métrica para performance da GAN
>[page 3](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf) [[2024-05-19 18:31]]

>[!Note]
><mark style="background-color: #e56eee">Highlight</mark></br></br>> IoU segmentation accuracy
>>- Métrica de avaliação de performance
>[page 3](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf) [[2024-05-19 18:31]]

>[!Note]
></br></br>
>![[sources/images/dimitrakopoulosISINGGANAnnotatedData2020/image-3-x316-y367.png]]
>[page 3](file://C:\Users\maila\Zotero\storage\TZPTM7P5\Dimitrakopoulos%20et%20al.%20-%202020%20-%20ISING-GAN%20Annotated%20Data%20Augmentation%20with%20a%20Spat.pdf) [[2024-05-19 18:33]]

%% end annotations %%

%% Import Date: 2024-05-19T18:38:56.239-03:00 %%
