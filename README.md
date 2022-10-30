# Working With Data and Code A3 Git Repository 
## Table of Contents
* [Introduction](###Introduction)
* [Technologies](###Technologies)
* [Setup](###Setup)
### Introduction
This project was created in an attempt to visualise music. When an mp3 file is downloaded and added into the data folder, a live and moving piece of art will play and move according to the frequencies and other technical aspects of the song as it plays. The code used for this project was heavily inspired by who's blog and Git Repository can be found below:
* [Blog](https://www.generativehut.com/post/using-processing-for-music-visualization)
* [GitHub](https://github.com/kassianh/imperative_visualizer)

### Technologies
This project was created using:

* Processing 4.0.1
* Java
* Minim
* VideoExport
### Setup
It is crucial that all technologies and sketchbooks are installed and downloaded for the project to work. 
Minim and VideoExport are two libraries available on Processing and must be installed before clicking 'Run'.
To do so:
1. Click Sketch in the above toolbar on Processing
2. Click Import Library --> Manage Libraries
3. Search for Minim and Install
4. Search for VideoExport and Install

The top of the code should look like this:
```
import ddf.minim.*;
import ddf.minim.analysis.*;
import ddf.minim.effects.*;
import ddf.minim.signals.*;
import ddf.minim.spi.*;
import ddf.minim.ugens.*;

import com.hamoid.*;

VideoExport videoExport;
```
As well as this, the data folder must also be downloaded as it contains the mp3 file currently encoded in the project's code.
One thing I learnt while doing this project was that the titles of each file downloaded must align exactly with the sketchbooks and the datas used for the project to work as these are the pathways that will get it running. It is important to double check that the name of the folder downloaded is the same as the name of the sketch so it can be correctly located and run smoothly.
