---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Education
======
* BEng in Electronic Engineering, University of Central Lancashire, Preston, the United Kingdom, 2019

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work
======
* Spring 2020 ~ Now: Research Assistant
  * AIRS([Shenzhen Institute of Artificial Intelligence and Robotics for Society](https://airs.cuhk.edu.cn/en/)), Shenzhen, China.
  * Department: RCUS(Research Center on Unmanned Systems)
  * Group: Automatic throat swab collection robot & Unmanned Logistics System
  * Duties included: Research on oral image instance segmentation algorithm and pyqt application development.
  * Supervisor: Dr. Yongquan Chen

* Summer 2019 ~ Spring 2020: C++ Software Engineer
  * Shenzhen Zhixin Medical Biotechnology Co., Ltd, Shenzhen, China.
  * Department: Research and Development department
  * Group: Hand held endoscope
  * Duties included: Embedded Qt application development.
  * Supervisor: Mr. Wengang Wang

Open Source Project
======
* LabelOwl - Developing...
  * Introduction: A multi person online data annotation system.
  * Github:
    * [LabelOwl](https://github.com/a2824256/LabelOwl)
  * Works: This project uses the web front end Vue.js Framework, the server-side API is developed using PHP framework workerman. The JSON format of the annotation file is consistent with labelme
* Convolutional Neural Network Accelerator - B.S. Graduation Project
  * Introduction: Implementation of classification network LeNet-5 using FPGA.
  * Github:
      * [HLS-LetNet](https://github.com/a2824256/HLS-LeNet)
      * [LeNet-Weights-Exporter](https://github.com/a2824256/LeNet-Weights-Exporter)
  * Works: Implementation of LeNet-5 Neural Network computing with C++ in vivado HLS. Then the connection structure of Xilinx ZYNQ 7035 SOC is designed by Xilinx Vivado. Finally, use Soc's ARM(PS) module to control FPGA(PL) through block-level control protocol. The test images and weights are stored in the SD card. ARM reads and stores them in the public BRAM of Soc. When the FPGA starts, it first reads data from the public BRAM to the RAM inside the FPGA, and then starts the network for prediction.

Awards
======
* 2016-2017 Beijing Institute of Technology & University of Central Lancashire first class scholarship
* 2017-2018 Beijing Institute of Technology & University of Central Lancashire second class scholarship

Certificates
======
* Intel FPGA Engineer (Entry Level) Certificate - ID FPGA012020524LY0011
<br/>
<img src="https://a2824256.github.io/images/intel fpga engineer.jpg" width="534" height="377"/>
