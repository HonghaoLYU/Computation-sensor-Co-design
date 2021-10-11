Tips: You can get a better experience of this site in [Google chrome](https://www.google.com/chrome) browser.

# Computation-Sensor Co-Design for Robotic Tactile Sensing with Training Data Augmentation
## Abstract
&emsp;&emsp;Deep learning (DL) techniques have shown great potentials in robotic tactile sensing that is an essential component in human-robot interaction (HRI). Conventionally, DL algorithms are customized for off-the-shelf tactile sensors, whereas the structural design of sensors that contributes to the performance of the algorithm is less considered during the design phase. Here, this paper jointly designs an elaborately shaped piezoresistive tactile sensor and a novel DL-based algorithm with data augmentation, alleviating the tradeoff between tactile sensing performance and hardware simplicity. The tactile sensor was prototyped in a modularized design with the hexagonal geometry, promising its scalability to large areas. The proposed data self-augmentation strategy draws on the rotational symmetry of the regular hexagon structure. It provides a novel way to expanding the original training set by generating pseudo data, which in return reduces the required data for training a deep neural network (DNN). By leveraging a pre-trained DNN for computationally efficient nonlinear reconstruction, the sensor can estimate force and localize contact over the continuous sensor area, achieving high-resolution tactile sensation. The functionality of the sensor and the data self-augmentation strategy were also demonstrated by touch modality recognition tasks, illustrating a well-generalized performance and the promising application prospects in HRI.

<p align='center'>
  <img src="https://honghaolyu.github.io/Computation-sensor-Co-design/images/overview.png" width="900" height="" alt="process overview"/>
</p>
<p align='center'>
  The proposed learning-based framework
</p>

### Contact: 
[Depeng Kong](http://fsie-zju.com/team/) (kongdepeng [at] zju.edu.cn)

## Supplementary Videos
### Supplementary Video 1 - Demonstration on touch position estimation
Real-time demonstration of the application on estimating the contact position.

<table align='center'>
<tr>
<td align='center' valign="middle"> &emsp;&emsp;&nbsp;&nbsp; <img src="https://honghaolyu.github.io/Computation-sensor-Co-design/images/position-estimation.png" width="" height="350" alt="error distributions"/> &emsp;&emsp;&nbsp;&nbsp; </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/Computation-sensor-Co-design/videos/Video1.mp4" type="video/mp4" controls="controls" width="" height="350"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> Error distributions </td>
<td align='center'> Demonstration on position estimation </td>
</tr>
</table>

### Supplementary Video 2 - Demonstration on touch modality recognition
Real-time demonstration of the application on touch modality recognition.

<table align='center'>
<tr>
<td align='center' valign="middle"> <img src="https://honghaolyu.github.io/Computation-sensor-Co-design/images/confusion matrix.png" width="" height="350" alt="confusion matrix"/> </td>
<td align='center' valign="middle"> <video src="https://honghaolyu.github.io/Computation-sensor-Co-design/videos/Video2.mp4" type="video/mp4" controls="controls" width="" height="350"> 您的浏览器不支持播放该视频！</video> </td>
</tr>
<tr>
<td align='center'> Confusion matrix results </td>
<td align='center'> Demonstration on touch modality recognition </td>
</tr>
</table>
