
# Strawberry picking point localisation ripeness and weight estimation

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Usage](#usage)
  * [Annotations](#annotations)
  * [Images](#images)
* [Contact](#contact)


## About The Project

This repository is related to the paper "Strawberry picking point localisation ripeness and weight estimation" accepted for ICRA 2022, PA. 
In particular it contains the 2 novel datasets presented in the paper.

![table](table.png)


## Usage

### Annotations

In the folder ```annotations/``` the annotations for the 2 datasets are present. They splitted into ```dyson_annotations.zip``` and ```SDI_annotations/```. Every image has its corresponding json file. In each json file the bounding box, the keypoints and the category (ripe/unripe) for each berry present in the image are annotated.

### Images 

- **Dataset #1**:  The Dyson dataset can be downloaded from [this link.](https://drive.google.com/file/d/1XaAbR8ahnRvkDXMSHy7LEzYiuyBum-KE/view?usp=sharing) It is divded into 4 sub-folders. It is composed of 
   * raw depth, 
   * color depth,
   * RGB and
   * point clouds of strawberries in the farm.
   * Addtionally the are numpy files containing the annotations of the **weights of the berries**.

- **Dataset #2**: The SDI dataset of images can be instead downloaded from [this link.](https://strawdi.github.io)

## Contact 

- aghalamzanesfahani@lincoln.ac.uk
- alessandra.tafuro@mail.polimi.it
- debnathb@edgehill.ac.uk

## License

The materials in this repo can be used under CC-BY-NC-SA license. All data, labels, code and models belong to the Intelligent Manipulation Lab and are freely available for free non-commercial use. 
