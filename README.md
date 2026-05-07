
# Bouncing DVD logo simulation and trajectories logging

This case-study project basically started on a sunday in which my sleep deprived brain wondered "Would i be able to build a bouncing DVD logo simulation and log the trajectories?".

I soon realized i was just really trying to build a linear motion simulation that allowed the user to edit specific parameters for a given outcome, and show the trajectories over a defined time of execution.

This realization further developed into the wish to be able to not only understand if the bouncing DVD logo was capable of scoring a perfect corner like in the famous The Office episode, but also to run a random search in order to optimize the starting simulation in angle in order to find that starting condition who would maximize the amount of perfect_corners.

## Project Breakdown

The following project main goals are:

- Simulating the physics of linear motion into an enclosed space while logging trajectories;

- Building a physics simulation system that allows different engines to run on the established physics while a metrics logging function traces the overall results.

- Running a random search to optimize the starting angle in order to find the best angle condition to maximize the perfect corners count

- Different engines with different underlying logic should be somehow comparable

## Demo

![Bouncing DVD logo trajectories for 3600 seconds](images/image1.png)

## Content

The following content is in this repo:

- bouncing_dvd_logo_tracing.ipynb - .ipynb notebook file containing the whole project written in Python.

- logo.png - the DVD logo i used for charts plotting and visualization
## How to load and use the notebook

This was entirely developed in Google Colab. If you want full compatibility just download the notebook and upload it to your own Google Colab instance. To visualize the DVD logo correctly into the charts just upload it to your Google Colab /content/ directory.

## Requirements

The project uses Python and Python base libraries, no specific packages were downloaded and installed for this. 

The followings are imported at the beginning:

```
import numpy as np
from dataclasses import dataclass
import matplotlib as mpl
import matplotlib.pyplot as plt
from matplotlib.offsetbox import OffsetImage, AnnotationBbox
from matplotlib.patches import Rectangle
from PIL import Image
import os
```
## Credits and Contributions

This project was developed by Sandbox1115.

If you have any question, advice, or want to share your own findings and solution to this project please get in touch, i'd be glad to evaluate your work and grow up professionally toghether.

## License

You are allowed to share and adapt this project by copying, redistributing, remixing, transforming or building on the original content made by me through the Creative Commons Attribution-NonCommercial 4.0 International CC BY-NC 4.0 License. Please do not forget attrbituion the the original content creator.