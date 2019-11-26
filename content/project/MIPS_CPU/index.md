+++
# Date this page was created.
date = 2018-11-10T00:00:00
layout = "project"

# Project title.
title = "Pipelined CPU implemented on FPGA"

# Project summary to display on homepage.
summary = """
 This is the curriculum design for our computer achitecture course.<br>
 I'm responsible for the ALU and pipeline design
 """
 
# image_preview = "MIPS_CPU/FPGA.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["School","AI","Web"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# [header]
# image = "MIPS_CPU/FPGA.png"

+++

# Overview
Based on gate-level circuit design, we implemented a 32 bits CPU in Verilog. It contains the main parts of a fully
functional pipelined CPU. Then we embedded deep pipeline into the ALU. <br>
We ran 100 8-point
FFT algorithm on it, And tested the project on FPGA (We used Basys, which is specifically designed for Vivado Design Suite). It is proved to be efficient 
and reliable. <br>

The main work for the project is as follows: <br>
- The eight-staged pipelined CPU design and implementation, including the control part as well as data path. <br>
- High efficiency assembly language of FFT. <br>
- Hazard detection and the test of FFT on the simulated CPU.

# Main Module Design
## ALU (mainly on Multiplexer)
## Datapath and Control
### Control
### Pipeline and Datapath
## Test
### FFT
### Test on FPGA

# Final Words
## Future Work
## Acknowledgement
It's really a great project, thank you for Prof. Jianhao Hu, Prof. Shang Ma and Associate Professor Jienan Chen, they provided us with amazing materials.
And it was great time work with Zhongyao Cao and Sufang Yang, they both are young researchers and partners.

![Digital Circuit](https://upload-images.jianshu.io/upload_images/20282999-98c9f5b101a0f623.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
