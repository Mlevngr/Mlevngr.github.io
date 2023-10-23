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
I am studying at TU/e for my master degree. I got my bachelor degree from Hefei University of Technology(HFUT), China.

I am interested in VLSI/ASIC Design, Neuromorphic Hardware, Effient AI Hardware Accelerator and NoC.

Here is my [CV](https://BoChen-Ye.github.io/files/CV_graduation.pdf).


# 📯 News
- *2023.10*: &nbsp;🎉🎉 I finished my internship at Intrinsic ID.
- *2023.07*: &nbsp;🎉🎉 I will be an intern at **[Intrinsic ID](https://www.intrinsic-id.com/)** for 3.5 months, supervised by Rui Wang(Intrinsic ID), Roel Maes(Intrinsic ID) and [Manil Dev Gomony](https://www.tue.nl/en/research/researchers/manil-dev-gomony)(TU/e & Nokia Bell Labs).
- *2022.09*: &nbsp;🎉🎉 I started my master's study at TU/e.
- *2022.07*: &nbsp;🎉🎉 I am graduated from Hefei University of Technology with a bachelor’s degree, supervised by [Zhenmin Li](https://wdzxy.hfut.edu.cn/2020/1231/c11547a249635/page.htm).  

# 📝 Skill & Publications 
- Verilog/SystemVerilog/VHDL · FPGA · MS Office · Linux · Cadence Tool(Virtuoso,Incisive,Genus,Innovus)
- Python · C/C++ · SystemC · MATLAB · LaTex · CUDA · Pytorch · Perl/TCL/Shell
- Mandarian(Native), TOEFL(iBT) 92


# 🏫 Educations
- *2022.09 - now*, Master in Eletrical Engneering(track:Electronic System), **Eindhoven University of Technology**, Netherlands

	*GPA*: [7/10](https://BoChen-Ye.github.io/files/transcript_Master.pdf)

	*Relevant Course*: Digital integrated circuit design, Embedded computer architecture, Electronic design automation,
					Applied combinatorial algorithms, Intelligent architectures(focus on DNN/Hardware co-design), 
					Systems on silicon(focus on SoC backend), Neuro computation(focus on Neuromorphic computing).

- *2018.09 - 2022.07*, Bachelor in Integrated Circuit Design and Integrated Systems, **Hefei University of Technology**, Hefei, China
	
	*GPA*: [83.1/100](https://BoChen-Ye.github.io/files/Transcript-Ye-Bochen.pdf) (TOP 22%)
	
	*Relevant Class*: Analysis and Design of Integrated Digital Circuit, Microprocessor architecture and design,
					Introduction to SoC design, Verilog HDL and FPGA implementation and so on.

# 💻 Internships
- *2023.07 - 2023.10, IP Modeling and Digital IC Design Intern*, **Intrinsic ID**, Eindhoven NL

	I am working in Research and Security Department. My work as follow:
	- Study on a trellis-based Reed-Muller codec. 
	- Use Python modeling it as a digital IP module.(software)
	- Design the architecture of codec and implementation by VHDL.(harware)
	- Verify on Arty-z7 FPGA(zynq) with vivado and vitis.(Embeded System)
	- Compare it with the existing Reed-Muller implementation based on traditional algorithms in terms of complexity and efficiency. This internship supervised by Manil Dev Gomony(Bell Lab & TU/e) and Rui Wang(Intrinsic ID).

- *2021.10 - 2022.05, Research Intern*, **Institute of VLSI Design of HFUT**, China
	
	- Study the knowledge of [Network-on-Chip(NoC) Router Based on Packet Connected Circuit(PCC)](https://github.com/BoChen-Ye/Network-on-Chip-Router-Based-on-Packet-Connected-Circuit).
	- Implementate the router and routing algorithm of PCC-NoC by using VerilogHDL.
	- Verify it on FPGA and use UART(with FIFO) to communicate with PC.
	- Use Python to verify result automatically.
	- This project as my bachelor graduation project got A and advised by Zhenmin Li(HFUT).

# 📖Self-Studying
- **[TinyML and Efficient Deep Learning Computing](https://efficientml.ai)**, MIT HAN LAB.
	
	- Current progress: Neural Architecture Search part I.
	- Content: Basics of Deep Learning, Pruning and Sparsity, Quantization, Neural Architecture Search

- **[一生一芯ysyx](https://ysyx.oscc.cc/)**, Institute of Computing technology, CAS.

	- Current progress: Prestudy->Stop.

- **Asynchronous VLSI Design**, USC.
	- beignner.

- **[Digital Design and Computer Architecture](https://safari.ethz.ch/digitaltechnik/doku.php)**, ETH.
	- beignner.

# 🔥 Project
- *2023.05 - 2023.06*, **Low power design and synthesis of SOC based on MIPS and AES**
	
	- Used Verilog to design a SoC which include five-stage pipelined mMIPS processor core, AES encryption module, and AMBA bus and Used Cadence Incisive to simulation and functional verification.
    - Used Cadence Genus for logic synthesis with low power strategies which is reduce 3% power consumption under 125MHz.
    - Used Cadence Innovus for place and route with two power domain which is reduce 8% power consumption under 200MHz.

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

- *2020.12 - 2021.01,* **Design of Lightweight System Based on SystemC**

	- Studying the structural design of soc, and use SystemC to write Bus and UART serial interface, function processing module, arbiter module, data receiving and sending module to form a lightweight system and verify it. Drive data enters two processing modules, and one of the results is selected by the arbiter in the bus and sent to the receiving module through UART interface and displayed.

- *2020.10 - 2020.11,* **VLSI Simulation and Synthesis**	

	- Use VCS to verify the function of Tinycore based on RISC-V on the test platform.
	- Use DC compiler to synthesize four different hardware description ALUs, and analyze the comprehensive report
	to compare and analyze different parameters.

# 🎖 Honors and Awards
- *2022,* My bachelor thesis of NoC get A grade.
- *2021/2022,* Unergraduate Scholarship. 

# 🖊️Extracurricular Activities 
- *2019.03 - 2020.07,* **HFUT Innovation and Entrepreneurship @ Big Data Center**

	Director, External Relations Department

	- Participated in writing the introduction of the center. Led the Computer Science College's party branch in visiting and introducing the Big Data Center and led high school students from Hefei to visit the center.
	-  Organized and planned the Innovation and Entrepreneurship Forum at the Big Data Center. Invited teachers from various colleges to give lectures. Attracted active participation from 500 students across the university.
    - Participated in editing the WeChat official account of INOW Creators.

- *2019.09 - 2020.07,* **Hefei University of Technology Electronics Science Association**

	Director, Organizing Department

	- Responsible for the Organization Department of the new District's daily work, organized and planned the new district association recruitment activities, thus the association became the largest association at our university.
    - Coordinated the students' Union and other departments, carried out targeted basic teaching work, held "no innovation, not young" electronic science and technology exchange lectures and other activities, the association was rated as the annual model association.

- *2019.09 - 2020.07,* **Microelectronics College Student Union**

	Director, Innovation and Entrepreneurship Department
	
	- Responsible for organizing and promoting the Microelectronics College Innovation and Entrepreneurship Competition and the National College Student Electronics Design Competition training.
	- Actively collaborated with the Big Data Center to facilitate the entry of Microelectronics College's innovation teams into the center.
