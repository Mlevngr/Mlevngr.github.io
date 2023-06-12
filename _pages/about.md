---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I am studying at TU/e for my master degree.

I am interested in VLSI Design, AI Hardware Accelerator, Algorithm/Hardware co-design, NoC.


# 🔥 News
- *2023.07*: &nbsp;🎉🎉 I will be an intern in the **[Intrinsic ID](https://www.intrinsic-id.com/)** for 3.5 months, supervised by Rui Wang(Intrinsic ID) and [Manil Dev Gomony](https://www.tue.nl/en/research/researchers/manil-dev-gomony)(TU/e & Nokia Bell Labs).

<img src="images/IntrinsicID.png">

- *2022.09*: &nbsp;🎉🎉 I started my master's study in TU/e.
- *2022.07*: &nbsp;🎉🎉 I am graduated from Hefei University of Technology with a bachelor’s degree, supervised by [Zhenmin Li](https://wdzxy.hfut.edu.cn/2020/1231/c11547a249635/page.htm).  

# 📝 Skill & Publications 
- Verilog · FPGA · MS Office · Linux · Cadence Tool(Virtuoso,Incisive,Genus,Innovus)
- Python · C/C++ · SystemC · MATLAB · LaTex · CUDA · Pytorch · Perl/TCL/Shell
- Mandarian(Native), TOEFL(iBT) 92
- Publication:
	- ICPECA'21:[Design of Lightweight System Based on SystemC](https://ieeexplore.ieee.org/document/9362651)

# 📖 Educations
- *2022.09 - now*, Master in Eletrical Engneering(track:Electronic System), **Eindhoven University of Technology**, Netherlands

	*GPA*: 7/10

	*Relevant Course*: Digital integrated circuit design, Embedded computer architecture, Electronic design automation,
					Applied combinatorial algorithms, Intelligent architectures(focus on DNN/Hardware co-design), 
					Systems on silicon(focus on SoC backend), Neuro computation(focus on Neuromorphic computing).

	<img src="images/TUe_logo.png">
- *2018.09 - 2022.07*, Bachelor in Integrated Circuit Design and Integrated Systems, **Hefei University of Technology**, Hefei, China
	
	*GPA*: 83.1/100 (TOP 22%)
	
	*Relevant Class*: Analysis and Design of Integrated Digital Circuit, Microprocessor architecture and design,
					Introduction to SoC design, Verilog HDL and FPGA implementation and so on.

# 💻 Internships
- *2023.07 - 2023.10, Digital IC Intern*, **Intrinsic ID**, Eindhoven
	- Study and develop a trellis-based Reed-Muller code structure as a digital IP module and compare it with the existing Reed-Muller implementation based on traditional algorithms in terms of complexity and efficiency.
- *2021.10 - 2022.05, Research Intern*, **Institute of VLSI Design of HFUT**
	
	- Investigate the background of Network on Chip router, and improve the [Packet Connected Circuit(PCC)-based NoC router](https://github.com/BoChen-Ye/Network-on-Chip-Router-Based-on-Packet-Connected-Circuit) structure and routing algorithm.  Used Verilog HDL to design NoC router in RTL-level and implementated on FPGA to verify its functionality.
	- This project as my bachelor graduation project, it's thesis received A, and was submitted as part of the IEEE/ACM International Symposium on NOCS.

# 🔥 Project
- *2023.05 - Now*, **Low power design and synthesis of SOC based on MIPS and AES**
	
	- Used Verilog to design a SoC which include five-stage pipelined mMIPS processor core, AES encryption module, and AMBA bus. 
    - Cadence Incisive is used for simulation function verification, Cadence Genus is used for logic synthesis, and Cadence Innovus is used for place and route. Finally, the GDSII layout file of SOC is generated.

- *2023.02 - 2023.04,* **Inference acceleration of deep neural network based on TCU accelerator**

	- Train [a multilayer perceptron for handwritten digit classification(MNIST)](https://github.com/BoChen-Ye/MNIST-handwritten-digit-classification) using the PyTorch framework.
	- Optimize a VGG5 for image classification using various quantization and pruning techniques. Explore the impact of these techniques on both accuracy and compute cost.
	- Use open source [Tensil AI](https://www.tensil.ai/) for generating tensor computing units, compiling and running ML models on it. Accelerating matrix-multiplication for machine learning, using systolic array architecture.

- *2023.02 - 2023.03,* [**Five-stage pipelined RISC-V processor with full hazard handling**](https://github.com/BoChen-Ye/RISC-V-five-stage-CPU)

	- I have implemented a RISC-V five-stage pipeline processor with full hazard handling. The RTL level design
	using Verilog and simulated in Modelsim for simulation. The processor can run the basic RV32i instructions,
	solves data conflicts, structure conflicts, and control conflicts, and supports stalling, flushing and forwarding.

- *2022.11 - 2023.01,* **Full Custom 16-bit Brent-Kung Adder Design**

	- Completed CMOS circuit design and layout design for a 45nm full custom 16-bit Brent-Kung adder. 
	Circuit design and layout design via Cadence Virtuoso, DRC and LVS verification of the layout using Calibre. 
	The circuit design can be functionally verified by simulation at 500MHz, 90◦C with an output rise and fall time of less than 100ps, and the layout results can be functionally verified at a post-simulation of 500MHz.

- *2022.12 - 2023.01,* **Implementation of image processing kernels on CUDA**

	- Mapping Grayscale processing and convolution 2D kernels from C to CUDA and optimaize the loop, then running on the Nvidia GPU.
	The result is that the processing time of 13 images is accelerated from 4872ms to 27ms.

- *2021.04 - 2021.06,* **A single-cycle CPU compatible with Microchip PIC16F54 microprocessor**	

	- The CPU is designed in modules, and each module uses Verilog HDL to design, which is implemented on the Basys3 after being verified by Modelsim pre-imitation. The complex C language load can run, and UART serial communication function controlled by softcore can be realized.

- *2020.10 - 2020.11,* **VLSI Simulation and Synthesis**	

	- Use VCS to verify the function of Tinycore based on RISC-V on the test platform.
	- Use DC compiler to synthesize four different hardware description ALUs, and analyze the comprehensive report
	to compare and analyze different parameters.

# 🎖 Honors and Awards
- *2022,* My bachelor thesis of NoC get A grade.
- *2021/2022,* Unergraduate Scholarship. 