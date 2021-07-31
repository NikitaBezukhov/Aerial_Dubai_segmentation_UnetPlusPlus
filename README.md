# Dubai Aerial photo segmentation with Unet++! (ResNet101 backbone)
####
### The data set is __[Semantic segmentation of aerial imagery from Kaggle](https://www.kaggle.com/humansintheloop/semantic-segmentation-of-aerial-imagery)__.
### Was built in __[Google Colab](https://colab.research.google.com/)__ environment, so make any adjustments needed for it to work on your machine.
### You can find code and detailed project analysis in __[aerial_semantic_segmentation.ipynb](https://github.com/NikitaBezukhov/Aerial_Dubai_segmentation_UnetPlusPlus/blob/main/aerial_semantic_segmentation.ipynb)__ notebook.
### The results of the training will be presented below.
## Dataset consists of 72 unique Dubai Aerial photos and corresponding ground truth masks consisting of 6 classes: 
### 1.Building
### 2.Land (unpaved area)
### 3.Road
### 4.Vegetation
### 5.Water
### 6.Unlabeled 
## Model trained for around 250 epocs (2.5 hours) with a batch size of 28 and fine tuned for couple more hours with a batch size of 56.
## Resulting training metrics were:
![Screenshot_1](https://user-images.githubusercontent.com/74721678/127753762-8a9d9de0-b742-42b7-9c5a-593daae33aa1.png)

![Screenshot_2](https://user-images.githubusercontent.com/74721678/127753763-3c101081-fea3-4d50-9f15-ffc991dc5533.png)

![Screenshot_3](https://user-images.githubusercontent.com/74721678/127753766-96c2911d-414a-4785-a13a-1c9b9ac668f6.png)
### Below you can see examples of model performance:
![prediction_1](https://user-images.githubusercontent.com/74721678/127753767-1ce890b6-65fa-4466-b7e1-95ac1b97bc00.png)
![prediction_2](https://user-images.githubusercontent.com/74721678/127753769-38558026-684c-40ef-ba9d-c7377144777b.png)
![prediction_3](https://user-images.githubusercontent.com/74721678/127753770-e7275c1a-2151-4f6d-a121-412d1e64b6cb.png)
![prediction_4](https://user-images.githubusercontent.com/74721678/127753773-4ce0f45b-bec1-4509-ae1a-f42f3030e8af.png)
![prediction_5](https://user-images.githubusercontent.com/74721678/127753777-e7a1091e-96c2-40bb-82b9-3c1a9eee3e22.png)
![prediction_6](https://user-images.githubusercontent.com/74721678/127753779-683d66b1-c72d-4f49-8252-b6794a7325fa.png)
![prediction_7](https://user-images.githubusercontent.com/74721678/127753780-055bc1b7-6001-440b-be0e-5a97ba47cff0.png)
![prediction_8](https://user-images.githubusercontent.com/74721678/127753781-b1e799ec-3138-4c66-abf9-153a66ab718e.png)
![prediction_9](https://user-images.githubusercontent.com/74721678/127753782-3d289787-11e8-4b7a-b0fc-c57eb6219732.png)
![prediction_10](https://user-images.githubusercontent.com/74721678/127753784-9180bed9-cb13-4590-82c3-95919aad6827.png)
![prediction_11](https://user-images.githubusercontent.com/74721678/127753786-0cf5a3f2-6b3a-4246-87a8-7822aeeabfc3.png)
![prediction_12](https://user-images.githubusercontent.com/74721678/127753787-bda59432-4293-442c-bd57-1d9e8bd26d7a.png)
![prediction_13](https://user-images.githubusercontent.com/74721678/127753788-78e232c3-2080-4ac4-a977-e0fe56f70aaa.png)
![prediction_14](https://user-images.githubusercontent.com/74721678/127753790-3ac53005-a26b-4115-b368-eb7174142ab8.png)
![prediction_15](https://user-images.githubusercontent.com/74721678/127753794-9a745754-16da-447a-8399-e7db4af1a527.png)
![prediction_16](https://user-images.githubusercontent.com/74721678/127753796-e21ecd60-92bb-43e2-92c5-0bb64ddca6b2.png)



