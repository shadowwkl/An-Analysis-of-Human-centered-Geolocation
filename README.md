# An-Analysis-of-Human-centered-Geolocation
WACV 2018 accepted

## Abstrcat
Online social networks contain a constantly increasing amount of images - most of them focusing on people. Due to cultural and climate factors, fashion trends and physical appearance of individuals differ from city to city. In this paper we investigate to what extent such cues can be exploited in order to infer the geographic location, i.e. the city, where a picture was taken. We conduct a user study, as well as an evaluation of automatic methods based on convolutional neural networks. Experiments on the Fashion 144k and a Pinterest-based dataset show that the automatic methods succeed at this task to a reasonable extent. As a matter of fact, our empirical results suggest that automatic methods can surpass human performance by a large margin. Further inspection of the trained models shows that human-centered characteristics, like clothing style, physical features, and accessories, are informative for the task at hand. Moreover, it reveals that also contextual features, e.g. wall type, natural environment, etc., are taken into account by the automatic methods.

## CNN Models
### Model info
These models are trained by MatConvNet 1.0 Beta16. If the version you are using is Beta 17 or higher, before use the model, add:
> 
`net = vl_simplenn_tidy(net)`
### Model link
You can download the models at my homepage. 
