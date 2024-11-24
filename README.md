# AMDA-Net
>📋  The title of research is "AMDA-Net: Adaptive Multi-scale Deformable Attention U-Net for Enhanced Medical Image Segmentation".This is the open source code about this article, and you can reproduce it by following the instructions below.Please note that this is a pre-published article. 
## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```

## Datasets

1. Synapse Dataset:
   You can directly download this dataset following this link.http://synapse.apache.org/download.html or you can use the Synapse datasets from other projects by TransUnet's authors. (https://drive.google.com/drive/folders/1ACJEoTp-uqfFJ73qS3eUObQh52nGuzCd).
   
2. ACDC Dataset:
   You can directly download this dataset following this link.https://www.creatis.insa-lyon.fr/Challenge/acdc/
   
## Training

>📋 Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.You need to download the pretrained-model by this link and put it into the folder of "pretrained_ckpt/" :https://1drv.ms/u/s!ApI0vb6wPqmtgrl-pI8MPFoll-ueNQ?e=bpdieu
To train the model(s) in the paper, run this command:

```train
python train.py --cfg [config_file in configs]
```

>📋  Describe how to train the models, with example commands on how to train the models in your paper, including the full training procedure and appropriate hyperparameters.

## Evaluation

To evaluate my model on ImageNet, run:

```eval
python test.py --cfg [pretrained_config_file in configs]
```

>📋  Describe how to evaluate the trained models on benchmarks reported in the paper, give commands that produce the results (section below).

## Results

Our model achieves the following performance on :

### [Image Segmentation on Synapse Dataset]

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it.
>![Synapse_results](https://github.com/user-attachments/assets/ae9bfef8-65ac-4e32-911b-385bce2b5809)

### [Image Segmentation on ACDC Dataset]

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it.
![ACDC_results](https://github.com/user-attachments/assets/5a8cf7a9-2ffa-4cc7-b39f-552a2d9b327c)

If you have any questions, please feel free to contact us, this is my email: songlianjun2021@163.com
