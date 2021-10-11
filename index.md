Tips: You can get a better experience of this site in [Google chrome](https://www.google.com/chrome) browser.
# Abstract
&emsp;&emsp;Deep learning (DL) techniques have shown great potentials in robotic tactile sensing that is an essential component in human-robot interaction (HRI). Conventionally, DL algorithms are customized for off-the-shelf tactile sensors, whereas the structural design of sensors that contributes to the performance of the algorithm is less considered during the design phase. Here, this paper jointly designs an elaborately shaped piezoresistive tactile sensor and a novel DL-based algorithm with data augmentation, alleviating the tradeoff between tactile sensing performance and hardware simplicity. The tactile sensor was prototyped in a modularized design with the hexagonal geometry, promising its scalability to large areas. The proposed data self-augmentation strategy draws on the rotational symmetry of the regular hexagon structure. It provides a novel way to expanding the original training set by generating pseudo data, which in return reduces the required data for training a deep neural network (DNN). By leveraging a pre-trained DNN for computationally efficient nonlinear reconstruction, the sensor can estimate force and localize contact over the continuous sensor area, achieving high-resolution tactile sensation. The functionality of the sensor and the data self-augmentation strategy were also demonstrated by touch modality recognition tasks, illustrating a well-generalized performance and the promising application prospects in HRI.

<p align='center'>
<img src="https://github.com/DepengKong-zju/Computation-Sensor-Co-Design/tree/main/images/overview.png" width="800" height="480" alt="process overview"/>
</p>

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/HonghaoLYU/Computation-sensor-Co-design/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
