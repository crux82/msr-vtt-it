# MSR-VTT-it Dataset
## A large scale dataset for Video Captioning in Italian

[MST-VTT](https://www.microsoft.com/en-us/research/publication/msr-vtt-a-large-video-description-dataset-for-bridging-video-and-language/) is a large-scale video benchmark for video understanding.
It contains 200K clip-sentence pairs. MSR-VTT provides 10K web video clips where 
every video has 20 human-written annotations in English.

**MSR-VTT-it** is derived from the MSR-VTT dataset and it is obtained through semi-automatic translation of the dataset 
into Italian. It represents a large-scale dataset for video understanding (captioning) in Italian. 
**The dataset contains 200K video-caption pairs derived from the original English dataset.** 
Following the standard data split in the Microsoft2016 challenge, we use 6,513 videos for training, 497 videos for validation and the remained 2,990 for testing.
Another version of the dataset contains only 100 test videos annotated manually.

The MSR-VTT-it dataset is composed of 2 files:

**DATASET UNVALIDATED**
* `videodatainfoITALIANO_2017_6513_497_2990.json`: it consists of the annotations for the video
from the original full MSR-VTT dataset annotations file, 6,513 videos for training, 497 videos for validation and the remained 2,990 for testing.

**DATASET VALIDATED**
* `videodatainfoITALIANO_2017_6513_497_100_TestValidati.json`: it consists of the annotations for the video
from the original not-full MSR-VTT dataset annotations file, 6,513 videos for training, 497 videos for validation and 100 for testing.


More details about MSR-VTT-it can be found in ??????




### How to cite MSR-VTT-it


If you find MSR-VTT-it useful for your research, please cite the following paper:

~~~~


DEFINIRE

~~~~


## Download

To download the MSR-VTT-it dataset, please refer to [this page](https://github.com/crux82/msr-vtt-it/tree/master/msr-vtt-it)

The resource is developed by the [Semantic Analytics Group](http://sag.art.uniroma2.it) of
the [University of Roma Tor Vergata](http://web.uniroma2.it/home). 


**Video**

Please refear to : https://drive.google.com/file/d/1Qi6Gn_l93SzrvmKQQu-drI90L-x8B0ly/view

## Release format

The same format used in the MSR-VTT dataset is adopted:

```
{
  "info" : {
    "year" : str,
    "version" : str,
    "description": str,
    "contributor": str,
    "data_created": str
  },
  "videos": {
    "id": int,
    "video_id": str,
    "category": int,
    "url": str,
    "start time": float,
    "end time": float,
    "split": str
  },
  "sentences": {
    "sen_id": int,
    "video_id": str,
    "caption": str
  }
}

```


## Size of MSR-VTT-it

The original MSR-VTT dataset contains the following elements:

|  | #videos	| #captions	| 
| --------- | :---------: | :-----: |
|	training 	|   6 513 | 130 260 |
|	development	| 497 | 9 940 |
|	test  | 2990 | 59 800   |


The NOT human validated MSR-VTT-it contains the following elements:

|  | #videos	| #captions	| 
| --------- | :---------: | :-----: |
|	training 	|   6 513 | 130 260 |
|	development	| 497 | 9 940 |
|	test  | 2990 | 59 800   |

The human validated MSR-VTT-it contains the following elements:

|  | #videos	| #captions	| 
| --------- | :---------: | :-----: |
|	training 	|   6 513 | 130 260 |
|	development	| 497 | 9 940 |
|	test  | 100 | 2 000   |


## References
J. Xu, T. Mei, T. Yao, and Y. Rui, \MSR-VTT: A large video description
dataset for bridging video and language," in 2016 IEEE Conference
on Computer Vision and Pattern Recognition, CVPR 2016, Las Vegas,
NV, USA, June 27-30, 2016, 2016, pp. 5288-5296. [Online]. Available:
https://doi.org/10.1109/CVPR.2016.571

## Contacts

For any questions or suggestions, you can send an e-mail to <croce@info.uniroma2.it>

More details will be also added to
