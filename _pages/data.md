---
layout: single
title: Data Description
permalink: /data/
date: 2021-06-01T00:00:00+09:00
---
The dataset was recorded in the Smart Life Care Unit of the Kyushu Institute of Technology in Japan. A motion capture system from Motion Analysis Company is used for this experiment. It has 29 body markers.4 subjects (men) in their 20’ and 30’s participated in this experiment. Each of the subjects is instructed to put three types of food in the bento box.

- [Download the training data (TBD)]()

Here they were instructed to perform 5 different scenarios:

*(Video will come)*

- Normal
- Forgot to put ingredients
- Failed to put ingredients
- Turn over bento-box and
- Fix/rearranging ingredients

Actions are done in two different patterns inward and outward. Participants were asked to repeat each work 5 times. 20 infrared cameras are used to track the markers. The three-dimensional position of each marker is recorded. The markers may be labeled incorrectly in some cases due to the complex setting.


- Length of each activity segment:  50~70 s.
- Position of the markers:

![Position of th markers](/bento2021/assets/images/marker_position.png)

- Frequency: 100Hz
- Preprocessing: No preprocessing method is applied to this data
- Training and Testing data:

## Data structure
TBD

__Test data sent to participants:__ July 1, 2021

[Make a submission](/bento2021/submit/)
