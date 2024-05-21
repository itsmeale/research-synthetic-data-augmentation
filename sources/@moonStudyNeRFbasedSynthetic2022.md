>[!Cite] [1]

S. Moon, J. Lee, J. Lee, D. Nam, e W. Yoo, “A Study on NeRF-based Synthetic Image Generation and Post-processing Method for Object Detection”, em _2022 13th International Conference on Information and Communication Technology Convergence (ICTC)_, out. 2022, p. 1560–1562. doi: [10.1109/ICTC55196.2022.9952798](https://doi.org/10.1109/ICTC55196.2022.9952798).

>[!Synthesize]
>**Contribution**::

>[!Metadata]
> **Author**:: Moon, SungWon</br> **Author**:: Lee, Jiwon</br> **Author**:: Lee, Jungsoo</br> **Author**:: Nam, Dowon</br> **Author**:: Yoo, Wonyoung</br>
>**Title**:: A Study on NeRF-based Synthetic Image Generation and Post-processing Method for Object Detection
>**Year**:: 2022
>**Citekey**:: @moonStudyNeRFbasedSynthetic2022
>**itemType**:: conferencePaper
>
>
>
>
>
>
> **Pages**:: 1560-1562
>**DOI**:: 10.1109/ICTC55196.2022.9952798
>

>[!LINK]
>
>[IEEE Xplore Full Text PDF](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf).

>[!Abstract]
Recently, the importance of securing data in the field of computer vision using machine learning is increasing. In this situation, research to use synthetic images as training data in fields where real images cannot be used for various reasons is ongoing. In particular, in the defense field, where it is difficult to know the characteristics of imaging devices, neural network learning using synthetic images is essential for the introduction of civilian technology. In this paper, we propose a method to use for object detection neural network training by generating synthetic images instead of real images and removing artifacts from the generated images.

> [!important]
## Annotations

%% begin annotations %%

### Exported: 2024-05-19 21:53
>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> Data augmentation using the Generative Adversarial Networks (GAN) technique showed the potential of using synthetic data for neural network learning [2]. However, data augmentation using GAN requires a data screening process due to the reliability problem of the generated data, and there is a problem in that it is difficult to control to directly generate the desired dat
>[page 1](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:50]]

>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> NeRF is a technology that receives 2D images as input and reproduces various viewpoints that are not input through a neural network. NeRF has the same effect as reproducing a 3D scene by providing photorealistic images for multiple viewpoints, and attempts to create high-quality 3D meshes based on this are also continuing. Data augmentation through NeRF has the disadvantage of requiring a large number of real images, but has the advantage of being able to generate the required camera pose data with high quality at the photo level
>[page 1](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:51]]

>[!Note]
></br></br>
>![[sources/images/moonStudyNeRFbasedSynthetic2022/image-2-x58-y675.png]]
>[page 2](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:51]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> NeRF-W
>[page 2](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:49]]

>[!Note]
></br></br>
>![[sources/images/moonStudyNeRFbasedSynthetic2022/image-2-x308-y551.png]]
>[page 2](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:51]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> YOLOX
>[page 2](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:50]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> mAP
>[page 2](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:52]]

>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> By applying image deblurring, it was confirmed that the learning effect using synthetic images greatly increased under the same conditions, showing almost the same performance as learning using real images.
>[page 3](file://C:\Users\maila\Zotero\storage\GS3P3Y7V\Moon%20et%20al.%20-%202022%20-%20A%20Study%20on%20NeRF-based%20Synthetic%20Image%20Generation%20a.pdf) [[2024-05-19 21:52]]

%% end annotations %%

%% Import Date: 2024-05-19T21:53:13.024-03:00 %%
