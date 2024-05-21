>[!Cite] [1]

J.-H. Kim e Y. Hwang, “GAN-Based Synthetic Data Augmentation for Infrared Small Target Detection”, _IEEE Trans. Geosci. Remote Sensing_, vol. 60, p. 1–12, 2022, doi: [10.1109/TGRS.2022.3179891](https://doi.org/10.1109/TGRS.2022.3179891).

>[!Synthesize]
>**Contribution**::

>[!Metadata]
> **Author**:: Kim, Jun-Hyung</br> **Author**:: Hwang, Youngbae</br>
>**Title**:: GAN-Based Synthetic Data Augmentation for Infrared Small Target Detection
>**Year**:: 2022
>**Citekey**:: @kimGANBasedSyntheticData2022
>**itemType**:: journalArticle
>**Journal**:: *IEEE Transactions on Geoscience and Remote Sensing*
>**Volume**:: 60
>
>
>
>
> **Pages**:: 1-12
>**DOI**:: 10.1109/TGRS.2022.3179891
>

>[!LINK]
>
>[Kim and Hwang - 2022 - GAN-Based Synthetic Data Augmentation for Infrared.pdf](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf).

>[!Abstract]
Recently, convolutional neural networks (CNNs) have achieved state-of-the-art performance in infrared small target detection. However, the limited number of public training data restricts the performance improvement of CNN-based methods. To handle the scarcity of training data, we propose a method that can generate synthetic training data for infrared small target detection. We adopt the generative adversarial network framework where synthetic background images and infrared small targets are generated in two independent processes. In the ﬁrst stage, we synthesize infrared images by transforming visible images into infrared ones. In the second stage, target masks are implanted on the transformed images. Then, the proposed intensity modulation network synthesizes realistic target objects that can be diversely generated from further image processing. Experimental results on the recent public dataset show that, when we train various detection networks using the dataset composed of both real and synthetic images, detection networks yield better performance than using real data only.

> [!important]
## Annotations

%% begin annotations %%

### Exported: 2024-05-19 21:29
>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> Experimental results on the recent public dataset show that, when we train various detection networks using the dataset composed of both real and synthetic images, detection networks yield better performance than using real data only
>[page 1](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:22]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> BicycleGAN
>[page 3](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:23]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> Pix2pix
>[page 4](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:23]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> CycleGAN
>[page 4](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:23]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> By inspecting the quality of translated images subjectively and objectively, they concluded that Pix2pix that uses the paired training dataset is superior to CycleGAN that uses the unpaired training dataset. Based on this result, we utilize BicycleGAN [30] that is an extension of Pix2pix with the capability of producing multimodal outputs
>[page 4](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:24]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> The baseline detection network is based on the original U-Net [33]. First, U-Net was designed for automatic biomedical image segmentation. Due to its excellent performance on many vision-related problems, U-Net has become the preferred starting point for designing new network architectures
>[page 6](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:25]]

>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> As noted before, our final goal is to improve the performance of CNN-based detection network trained with limited samples
>[page 7](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:25]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> SIRST
>[page 7](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:26]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> KAIST multispectral pedestrian
>[page 7](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:26]]

>[!Note]
><mark style="background-color: #ff6666">Highlight</mark></br></br>> CVC-14 dataset
>[page 7](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:26]]

>[!Note]
></br></br>
>![[sources/images/kimGANBasedSyntheticData2022/image-7-x310-y201.png]]
>[page 7](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:27]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> We also adopt the probability of detection (Pd )andthefalse alarm rate (Fa) to evaluate the effectiveness of the proposed data augmentation process
>[page 7](file://C:\Users\maila\Zotero\storage\8DTY48IF\Kim%20and%20Hwang%20-%202022%20-%20GAN-Based%20Synthetic%20Data%20Augmentation%20for%20Infrared.pdf) [[2024-05-19 21:28]]

%% end annotations %%

%% Import Date: 2024-05-19T21:30:01.774-03:00 %%
