# coling18-multimodalSurvey

> **Abstract:** This survey discusses how recent developments in multimodal processing facilitate conceptual grounding of language. We categorize the information flow in multimodal processing with respect to cognitive models of human information processing and analyze different methods for combining multimodal representations. Based on this methodological inventory, we discuss the benefit of multimodal grounding for a variety of language processing tasks and the challenges that arise. We particularly focus on multimodal grounding of verbs which play a crucial role for multimodal compositionality.

Please use the following citation:

```
@InProceedings{beinborn2018multimodal,
  title = {{Multimodal Grounding for Language Processing}},
	author = {Beinborn, Lisa and Botschen, Teresa and Gurevych, Iryna},
	publisher = {Association for Computational Linguistics},
	booktitle = {Proceedings of COLING 2018, the 27th International Conference on Computational Linguistics: Technical Papers},
	pages = {to appear},
	month = {aug},
	year = {2018},
	location = {Santa Fe, USA},
}
```

Contact person: Lisa Beinborn, Lisa.Beinborn@gmx.de ; Teresa Botschen, botschen@aiphes.tu-darmstadt.de 

https://www.ukp.tu-darmstadt.de/

https://www.tu-darmstadt.de/


Don't hesitate to send us an e-mail or report an issue, if something is broken (and it shouldn't be) or if you have further questions.

> This repository contains experimental software and is published for the sole purpose of giving additional background details on the respective publication. 


## Data
### visual datasets for images for verbs: 
the Google dataset Kiela et al. (2016) https://aclweb.org/anthology/D/D16/D16-1043.pdf , data: http://www.cl.cam.ac.uk/~dk427/cnnexpts.html
	--> contains verb similarity ratings from SimVerb dataset (Gerz et al., 2016) http://www.aclweb.org/anthology/D16-1235
imSitu dataset Yatskar et al. (2016) https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Yatskar_Situation_Recognition_Visual_CVPR_2016_paper.pdf , data: http://imsitu.org/
	--> contain embodiment ratings for verbs from (Sidhu et al., 2014) http://iranarze.ir/wp-content/uploads/2017/08/7298-English-IranArze.pdf

## Embeddings
### methods for obtaining pre-trained embeddings:
Textual embeddings
	--> openly available pre-trained Glove representations (Pennington et al., 2014) http://aclweb.org/anthology/D14-1162
Visual embeddings
	--> applying pre-trained VGG19 neural network for image classification (Simonyan and Zisserman, 2014) https://arxiv.org/pdf/1409.1556.pdf
	--> Visual embeddings for Google dataset (1024 dim)
	--> Visual embeddings for imSitu dataset (4096 dim)
Mapped embeddings
	--> applying imagined method by Collell et al. (2017) to Textual and Visual embeddings http://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14811/14042
	--> Mapped embeddings for Google dataset (1024 dim)
	--> Mapped embeddings for imSitu dataset (4096 dim)

## Dataset and Embeddings
This project uses different pretrained word embeddings which can be found here:
https://fileserver.ukp.informatik.tu-darmstadt.de/coling18-multimodalSurvey

## Code
Run the script 'coling18-multimodalSurvey_experiments.py' to reproduce results reported in paper. Use the datasets and embeddings mentioned above.

