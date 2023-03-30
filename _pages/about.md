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

I am looking for internship and Master thesis for my second year.

# 🔥 News
- *2022.07*: &nbsp;🎉🎉 I am graduated from Hefei University of Technology with a bachelor’s degree, supervised by Zhenmin Li.  

# 📝 Skill & Publications 
- Verilog · FPGA · MS Office · Linux · Cadence Tool
- Python · C++ · SystemC · MATLAB · LaTex · CUDA · Pytorch · Perl
- Mandarian(Native), TOEFL(iBT) 92

# 📖 Educations
- *2022.09 - now*, Master in Eletrical Engneering(track:Electric System), Eindhoven University of Technology, Netherlands
	
	*Relevant Course*: Digital integrated circuit design, Embedded computer architecture, Electronic design automation,
					Applied combinatorial algorithms, Intelligent architectures(focus on DNN/Hardware co-design), 
					Systems on silicon(focus on SoC backend), Neuro computation(focus on Neuromorphic computing).
- *2018.09 - 2022.06*, Bachelor in Integrated Circuit Design and Integrated Systems, Hefei University of Technology, Hefei, China
	
	*GPA*: 83.1/100 (TOP 22%)
	
	*Relevant Class*: Analysis and Design of Integrated Digital Circuit, Microprocessor architecture and design,
					Introduction to SoC design, Verilog HDL and FPGA implementation and so on.

# 🔥 Project
- *2022.11 - 2023.01,* **Full Custom 16-bit Brent-Kung Adder Design**

	Completed CMOS circuit design and layout design for a 45nm full custom 16-bit Brent-Kung adder. 
	Circuit design and layout design via Cadence Virtuoso, DRC and LVS verification of the layout using Calibre. 
	The circuit design can be functionally verified by simulation at 500MHz, 90◦C with an output rise and fall time of less than 100ps, and the layout results can be functionally verified at a post-simulation of 500MHz.

- *2023.02 - 2023.03,* [**Five-stage pipelined RISC-V processor with full hazard handling**](https://github.com/BoChen-Ye/RISC-V-five-stage-CPU)

	I have implemented a RISC-V five-stage pipeline processor with full hazard handling. The RTL level design
	using Verilog and simulated in Modelsim for simulation. The processor can run the basic RV32i instructions,
	solves data conflicts, structure conflicts, and control conflicts, and supports stalling, flushing and forwarding.

- *2020.10 - 2020.11,* **VLSI Simulation and Synthesis**	

	Use VCS to verify the function of Tinycore based on RISC-V on the test platform.
	Use DC compiler to synthesize four different hardware description ALUs, and analyze the comprehensive report
	to compare and analyze different parameters.

# 💻 Internships
- *2021.10 - 2022.05, Research Intern*, **Institute of VLSI Design of HFUT**
	
	Investigate the background of Network on Chip router, and improve the [Packet Connected Circuit(PCC)-based NoC router](https://github.com/BoChen-Ye/Network-on-Chip-Router-Based-on-Packet-Connected-Circuit) structure and routing algorithm. 
	The RTL level design of the router using Verilog and its implementation and verification on FPGA. My graduation thesis received A grade, and this project was continued to be improved by other student to prepare for publication.

# 🎖 Honors and Awards
- *2022,* My bachelor thesis of NoC get A grade.
- *2021/2022,* Unergraduate Scholarship. 