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

Based on digital design and micro-processo, we implemented a 32 bits CPU in Verilog. It contains the main parts of a fully
functional pipelined CPU. Then we embedded deep pipeline into the ALU. We ran 100 8-point
FFT algorithm on it, And tested the project on FPGA. It is proved to be efficient 
and reliable. The following image is the digital design for this project.
![Digital Circuit](https://upload-images.jianshu.io/upload_images/20282999-98c9f5b101a0f623.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
