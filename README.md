# An-Analysis-of-Human-centered-Geolocation
[Kaili Wang](http://homes.esat.kuleuven.be/~kwang/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Yu-Hui Huang](http://homes.esat.kuleuven.be/~yhuang/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Jose Oramas](http://homes.esat.kuleuven.be/~joramas/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Luc Van Gool](https://www.kuleuven.be/wieiswie/en/person/00011315)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Tinne Tuytelaars](https://homes.esat.kuleuven.be/~tuytelaa/)
>  
To be presented @ WACV 2018.
> 
You can find the paper here:
[An-Analysis-of-Human-centered-Geolocation](https://arxiv.org/abs/1707.02905)
## Abstract
Online social networks contain a constantly increasing amount of images - most of them focusing on people. Due to cultural and climate factors, fashion trends and physical appearance of individuals differ from city to city. In this paper we investigate to what extent such cues can be exploited in order to infer the geographic location, i.e. the city, where a picture was taken. We conduct a user study, as well as an evaluation of automatic methods based on convolutional neural networks. Experiments on the Fashion 144k and a Pinterest-based dataset show that the automatic methods succeed at this task to a reasonable extent. As a matter of fact, our empirical results suggest that automatic methods can surpass human performance by a large margin. Further inspection of the trained models shows that human-centered characteristics, like clothing style, physical features, and accessories, are informative for the task at hand. Moreover, it reveals that also contextual features, e.g. wall type, natural environment, etc., are taken into account by the automatic methods.

<p align="center">
  <img src="https://github.com/shadowwkl/An-Analysis-of-Human-centered-Geolocation/blob/master/teaser.jpg" width="600">
</p>

## CNN Models
### Model info
These models are trained by MatConvNet 1.0 Beta16. If the version you are using is Beta 17 or higher, before use the model, add:
> 
`net = vl_simplenn_tidy(net)`
### Model link
You can download the models at my [home page](http://homes.esat.kuleuven.be/~kwang/). 

## Citation
If you use our models, or come up with some ideas from this paper, please cite as following:
> 
K. Wang, Y. Huang, J. Oramas, L. Van Gool, and T. Tuytelaars. An Analysis of Human centered Geolocation WACV’18 (arXiv:1707.02905, 2018).

```
@inproceedings{joramas:WACVHumanCenteredGeolocation,
  author    = {Kaili Wang and Yu-Hui Huang and Jos{\'e} {Oramas M} and Luc {Van Gool}  and Tinne Tuytelaars},             
  title     = {An Analysis of Human-centered Geolocation},
  booktitle = {WACV},
  year      = {2018}
} 
```


## Contact
If you have any question, please contact kwang@esat.kuleuven.be
