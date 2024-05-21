>[!Cite] [1]

C. Han _et al._, “Combining Noise-to-Image and Image-to-Image GANs: Brain MR Image Augmentation for Tumor Detection”, _IEEE Access_, vol. 7, p. 156966–156977, 2019, doi: [10.1109/ACCESS.2019.2947606](https://doi.org/10.1109/ACCESS.2019.2947606).

>[!Synthesize]
>**Contribution**::

>[!Metadata]
> **Author**:: Han, Changhee</br> **Author**:: Rundo, Leonardo</br> **Author**:: Araki, Ryosuke</br> **Author**:: Nagano, Yudai</br> **Author**:: Furukawa, Yujiro</br> **Author**:: Mauri, Giancarlo</br> **Author**:: Nakayama, Hideki</br> **Author**:: Hayashi, Hideaki</br>
>**Title**:: Combining Noise-to-Image and Image-to-Image GANs: Brain MR Image Augmentation for Tumor Detection
>**Year**:: 2019
>**Citekey**:: @hanCombiningNoisetoImageImagetoImage2019
>**itemType**:: journalArticle
>**Journal**:: *IEEE Access*
>**Volume**:: 7
>
>
>
>
> **Pages**:: 156966-156977
>**DOI**:: 10.1109/ACCESS.2019.2947606
>

>[!LINK]
>
>[Han et al. - 2019 - Combining Noise-to-Image and Image-to-Image GANs .pdf](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf).

>[!Abstract]
Convolutional Neural Networks (CNNs) achieve excellent computer-assisted diagnosis with sufﬁcient annotated training data. However, most medical imaging datasets are small and fragmented. In this context, Generative Adversarial Networks (GANs) can synthesize realistic/diverse additional training images to ﬁll the data lack in the real image distribution; researchers have improved classiﬁcation by augmenting data with noise-to-image (e.g., random noise samples to diverse pathological images) or imageto-image GANs (e.g., a benign image to a malignant one). Yet, no research has reported results combining noise-to-image and image-to-image GANs for further performance boost. Therefore, to maximize the DA effect with the GAN combinations, we propose a two-step GAN-based DA that generates and reﬁnes brain Magnetic Resonance (MR) images with/without tumors separately: (i) Progressive Growing of GANs (PGGANs), multi-stage noise-to-image GAN for high-resolution MR image generation, ﬁrst generates realistic/diverse 256×256 images; (ii) Multimodal UNsupervised Image-to-image Translation (MUNIT) that combines GANs/Variational AutoEncoders or SimGAN that uses a DA-focused GAN loss, further reﬁnes the texture/shape of the PGGAN-generated images similarly to the real ones. We thoroughly investigate CNN-based tumor classiﬁcation results, also considering the inﬂuence of pre-training on ImageNet and discarding weird-looking GAN-generated images. The results show that, when combined with classic DA, our two-step GAN-based DA can signiﬁcantly outperform the classic DA alone, in tumor detection (i.e., boosting sensitivity 93.67% to 97.48%) and also in other medical imaging tasks.

> [!important]
## Annotations

%% begin annotations %%

### Exported: 2024-05-19 19:57
>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> However, most medical imaging datasets are small and fragmented
>[page 1](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:51]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> Multimodal Brain Tumor Image Segmentation Benchmark (BRATS) 2016
>[page 3](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:52]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> GAN/ResNet-50
>[page 3](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:52]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> PGGANs
>[page 3](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:52]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> MUNIT
>[page 4](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:52]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> SimGAN
>[page 4](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:52]]

>[!Note]
></br></br>
>![[sources/images/hanCombiningNoisetoImageImagetoImage2019/image-7-x28-y541.png]]
>[page 7](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:54]]

>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> MUNIT and SimGAN differently refine PGGAN-generated images—they render the texture and contours while maintaining the overall shape (Fig. 6). Non-tumor images change more remarkably than tumor images for both MUNIT and SimGAN
>[page 7](file://C:\Users\maila\Zotero\storage\MJU8RT2D\Han%20et%20al.%20-%202019%20-%20Combining%20Noise-to-Image%20and%20Image-to-Image%20GANs%20.pdf) [[2024-05-19 19:54]]

%% end annotations %%

%% Import Date: 2024-05-19T19:58:04.442-03:00 %%
