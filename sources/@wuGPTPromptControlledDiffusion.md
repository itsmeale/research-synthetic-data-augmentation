>[!Cite] [1]

W. Wu, T. Dai, X. Huang, F. Ma, e J. Xiao, “GPT-Prompt Controlled Diffusion for Weakly-Supervised Semantic Segmentation”.

>[!Synthesize]
>**Contribution**::

>[!Metadata]
> **Author**:: Wu, Wangyu</br> **Author**:: Dai, Tianhong</br> **Author**:: Huang, Xiaowei</br> **Author**:: Ma, Fei</br> **Author**:: Xiao, Jimin</br>
>**Title**:: GPT-Prompt Controlled Diffusion for Weakly-Supervised Semantic Segmentation
>**Year**:: Error: `format` can only be applied to dates. Tried for format object
>**Citekey**:: @wuGPTPromptControlledDiffusion
>**itemType**:: journalArticle
>**Journal**:: **
>
>
>
>
>
>
>
>

>[!LINK]
>
>[Wu et al. - GPT-Prompt Controlled Diffusion for Weakly-Supervi.pdf](file://C:\Users\maila\Zotero\storage\YVH9XUL5\Wu%20et%20al.%20-%20GPT-Prompt%20Controlled%20Diffusion%20for%20Weakly-Supervi.pdf).

>[!Abstract]
Weakly supervised semantic segmentation (WSSS), aiming to train segmentation models solely using image-level labels, has received significant attention. Existing approaches mainly concentrate on creating high-quality pseudo labels by utilizing existing images and their corresponding image-level labels. However, the quality of pseudo labels degrades significantly when the size of available dataset is limited. Thus, in this paper, we tackle this problem from a different view by introducing a novel approach called GPT-Prompt Controlled Diffusion (GPCD) for data augmentation. This approach enhances the current labeled datasets by augmenting with a variety of images, achieved through controlled diffusion guided by GPT prompts. In this process, the existing images and image-level labels provide the necessary control information, where GPT is employed to enrich the prompts, leading to the generation of diverse backgrounds. Moreover, we integrate data source information as tokens into the Vision Transformer (ViT) framework. These tokens are specifically designed to improve the ability of downstream WSSS framework to recognize the origins of augmented images. Our proposed GPCD approach clearly surpasses existing state-of-the-art methods. This effect is more obvious when the amount of available data is small, demonstrating the effectiveness of our method. Our source code will be released.

> [!important]
## Annotations

%% begin annotations %%

### Exported: 2024-05-19 21:59
>[!Note]
></br></br>
>![[sources/images/wuGPTPromptControlledDiffusion/image-4-x49-y525.png]]
>[page 4](file://C:\Users\maila\Zotero\storage\YVH9XUL5\Wu%20et%20al.%20-%20GPT-Prompt%20Controlled%20Diffusion%20for%20Weakly-Supervi.pdf) [[2024-05-19 21:55]]

>[!Note]
><mark style="background-color: #2ea8e5">Highlight</mark></br></br>> WSSS
>[page 6](file://C:\Users\maila\Zotero\storage\YVH9XUL5\Wu%20et%20al.%20-%20GPT-Prompt%20Controlled%20Diffusion%20for%20Weakly-Supervi.pdf) [[2024-05-19 21:57]]

>[!Note]
><mark style="background-color: #ffd400">Highlight</mark></br></br>> Comparison of Different Data Percentages. Our proposed GPCD method can effectively increase the effective size of the original training dataset. As reported in Table 1, this enhancement notably enhances the segmentation performances of the downstream WSSS framework. Particularly noteworthy is the amplified impact observed when the training data is limited, such as in the case of only 5% of the dataset, where we achieved a 5.3% performance boost on PASCAL VOC 2012
>[page 7](file://C:\Users\maila\Zotero\storage\YVH9XUL5\Wu%20et%20al.%20-%20GPT-Prompt%20Controlled%20Diffusion%20for%20Weakly-Supervi.pdf) [[2024-05-19 21:58]]

>[!Note]
><mark style="background-color: #5fb236">Highlight</mark></br></br>> By combining these components, our approach demonstrates superior performance compared to other state-of-the-art methods on the PASCAL VOC 2012 and MS COCO 2014 datasets
>[page 7](file://C:\Users\maila\Zotero\storage\YVH9XUL5\Wu%20et%20al.%20-%20GPT-Prompt%20Controlled%20Diffusion%20for%20Weakly-Supervi.pdf) [[2024-05-19 21:59]]

%% end annotations %%

%% Import Date: 2024-05-19T21:59:36.022-03:00 %%
