# OSTENSIBLE-PAINTING-USING-HAND-MOTION-AND-COMPUTER-VISION-BASED-ON-OPENCV
MADE BY : VAISAKH SRIRAM

> Based on OpenCV

> paint.py tracks the object its color will be set and enables the painting

> set_color_range.py allows to set the color range required to detect the object to be tracked

## Contents
- [Features](#features)
  - [Set Color Range](#rocket-set-color-range)
  - [Paint Tools](#rocket-paint-tools)
  - [Paint](#rocket-paint)
  - [Eraser & Clear](#rocket-eraser--clear)
  - [Discrete Writing](#rocket-discrete-writing)
- [How to use?](#how-to-use)

## Features

:white_check_mark: 3 different marker thicknesses (small, medium, large)

:white_check_mark: 5 different colors (🟣purple, 🔵blue, 🟢green, 🔴red, 🟡yellow)

:white_check_mark: paints can be erased and the entire page can be cleaned

:white_check_mark: possible to write discrete (with a little trick)

### :rocket: Set Color Range
:white_check_mark: _Color range can be adjusted with trackbars_

:white_check_mark: _After determining the color range, save by pressing the 'S' key, it will save a numpy array as `hsvVal.npy`_

:white_check_mark: _Press 'Q' to exit_

![Set Color Range](/images/set-color-range.gif)


### :rocket: Paint Tools
:white_check_mark: _3 thickness options (small, medium, large), 5 color options (purple, blue, green, red, yellow)_

![Paint Tools](/images/paint-tools.gif)


### :rocket: Paint
:white_check_mark: _Draw whatever you want!_

![Paint](/images/paint.gif)


### :rocket: Eraser & Clear
:white_check_mark: _**Eraser** for area cleaning, **Clear** for whole page cleaning_

![Eraser & Clear](/images/paint-eraser.gif)


### :rocket: Discrete Writing
:white_check_mark: _There is a little trick, flip the other side of the tracked object to write discretely_

:white_check_mark: _Press 'Q' to exit_

![Marker Enable/Disable](/images/marker-enable-disable.gif)


## How to use?
:one: Run the `set_color_range.py` file to set the color range (just make sure the object is detected)

:two: Save the adjusted values by pressing the 'S' key, values will be saved as `hsvVal.npy` file

:three: Run the `paint.py` file, it will automatically open the `hsvVal.npy` file

:100: Enjoy painting!


# Collaborators
  | |  |  |  |  |
  | ------------- | ------------- | ------------- | ------------- | ------------- |
  | VAISAKH | [GitHub](github.com/PROMETHEUS-THEGHOST) | [Email](mailto:vaisakhs2255@gmail.com) | [LinkedIn](https://www.linkedin.com/in/vaisakh-sriram-860992213) | [Instagram](https://www.instagram.com/_vaisakhsriram?igshid=ZDdkNTZiNTM=) |
  | RITHESH | [Github] | [Email](ritheshparameswaran3@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rithesh-parameswaran-651935260) | [Instagram] |
  | KARUN | [GitHub] | [Email] | [LinkedIn](https://www.linkedin.com/in/karun-krishnan-9ab74b245) | Instagram |
  
