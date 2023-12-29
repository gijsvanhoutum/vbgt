# Vision Based Deposition Geometry Detection

Using a camera and a line laser to detect the geometry of 3D printing deposition
geometries. In a period of 3.5 Months I created computer vision software, algorithms and
[documentation](https://github.com/gijsvanhoutum/vbgt/blob/master/report/0872274-VisionBasedDepositionGeometryDetection.pdf). 
Hardware selection (Camera,Line Laser), CAD bracket modelling and 3D printing as well as experiments were 
all parts I created myself as well. 

<p align="center">
  <img alt="Light" src="https://github.com/gijsvanhoutum/vbgt/blob/master/icons/setup.png?raw=true" width="45%">
  <img alt="Dark" src="https://github.com/gijsvanhoutum/vbgt/blob/master/icons/dinolite.png?raw=true" width="45%">
</p>

<p align="center">
  <img alt="Light" src="https://github.com/gijsvanhoutum/vbgt/blob/master/icons/line.png?raw=true" width="55%">
  <img alt="Dark" src="https://github.com/gijsvanhoutum/vbgt/blob/master/icons/algo.png?raw=true" width="35%">
</p>

During this specific project there was a need for a fast video recording application that could talk with the
DinoLite Edge camera. Since I could not find one, I decided to write one myself, [TREC: Threaded Video Player and Recorder](https://github.com/gijsvanhoutum/trec). 
It is often hard to see what computer vision algorithms do when you change certain parameters. I therefore created another 
application named [ALAN: Algorithm Analyzer](https://github.com/gijsvanhoutum/alan) that could visualize and run camera footage alongside different 
computer vision algorithms in real-time as well as use pre-recorded videos. 

## TODO

- Add all information related to this project. Currently saved on MSAM NAS.