Tips: You can get a better experience of this site in [Google chrome](https://www.google.com/chrome) browser.
# Abstract
&emsp;&emsp;Deep learning (DL) techniques have shown great potentials in robotic tactile sensing that is an essential component in human-robot interaction (HRI). Conventionally, DL algorithms are customized for off-the-shelf tactile sensors, whereas the structural design of sensors that contributes to the performance of the algorithm is less considered during the design phase. Here, this paper jointly designs an elaborately shaped piezoresistive tactile sensor and a novel DL-based algorithm with data augmentation, alleviating the tradeoff between tactile sensing performance and hardware simplicity. The tactile sensor was prototyped in a modularized design with the hexagonal geometry, promising its scalability to large areas. The proposed data self-augmentation strategy draws on the rotational symmetry of the regular hexagon structure. It provides a novel way to expanding the original training set by generating pseudo data, which in return reduces the required data for training a deep neural network (DNN). By leveraging a pre-trained DNN for computationally efficient nonlinear reconstruction, the sensor can estimate force and localize contact over the continuous sensor area, achieving high-resolution tactile sensation. The functionality of the sensor and the data self-augmentation strategy were also demonstrated by touch modality recognition tasks, illustrating a well-generalized performance and the promising application prospects in HRI.

<p align='center'>
  <img src="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/images/overview.png" width="900" height="480" alt="process overview"/>
</p>
<p align='center'>
  The proposed learning-based framework
</p>


# Supplementary Videos
## Supplementary Video 1 - Demonstration on touch position estimation
|<img src="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/images/position-estimation.png" width="" height="" alt="process overview"/>|<img src="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/images/position-estimation.png" width="" height="" alt="process overview"/>|
|---|---|
|Error distributions|Demonstration on position estimation|

<p align='center'>
  test supplementary video 1
</p>

## Supplementary Video 2 - Demonstration on touch modality recognition

<video id="video" src="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/videos/Video1.mp4" type="video/mp4" controls="controls" width="500" height="282"> 
  </videos>
  <video id="video" controls="" preload="none" poster="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/images/overview.png">
      <source id="mp4" src="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/videos/Video1.mp4" type="video/mp4">
  </videos>
<p align='center'>
  <video id="video" src="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/videos/Video2.mp4" type="video/mp4" controls="controls" width="500" height="282"> 
  </videos>
  <video id="video" controls="" preload="none" poster="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/images/overview.png">
      <source id="mp4" src="https://github.com/HonghaoLYU/Computation-sensor-Co-design/blob/gh-pages/videos/Video2.mp4" type="video/mp4">
  </videos>
</p>
