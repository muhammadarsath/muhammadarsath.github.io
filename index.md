## Portfolio

---

### Interests
- Hardware Security
- Power Side-channel Analysis
- Learning Algorithms

--- 

### Education
- M.S (by Research) at Indian Institute of Technology Madras
- B.E (CSE) at Sri Krishna College of Engineering and Technology, Coimbatore

--- 

### Publications
1.[PARAM: A Microprocessor Hardened for Power Side-Channel Attack Resistance (HOST2020-Accepted)]()
<p style="font-size:13px">  
  The power consumption of a microprocessor is a huge channel for information leakage. While the most popular exploitation of this channel is to recover cryptographic keys from embedded devices, other applications such as mobile app fingerprinting, reverse engineering of firmware, and password recovery are fast growing threats. Countermeasures proposed so far are tuned to specific applications, such as crypto-implementations. They are not scalable to the large number and variety of applications that typically run on a general purpose microprocessor. We investigate the design of a microprocessor, called PARAM with increased resistance to power based side-channel attacks. To design PARAM, we start with identifying the most leaking modules in an open-source RISC V processor. We evaluate the leakage in these modules and then add suitable countermeasures. The countermeasures depend on the cause of leakage in each module and can vary from simple modifications of the HDL code ensuring secure translation by the EDA tools, to obfuscating data and address lines thus breaking correlation with the processor's power consumption. The resultant processor is instantiated on the SASEBO-GIII FPGA board and found to resist Differential Power Analysis even after one million power traces. Compared to contemporary countermeasures for power side-channel attacks, overheads in area and frequency are minimal.
  
---

### Projects
1.[Framework for Comprehensive Side-channel Evaluation of a Microprocessor](/pdf/1000-19.07.18-Muhammad-Arsath-Chester-Rebeiro-IIT-Madras(2).pdf)
<p style="font-size:13px">  
This work proposes a framework for evaluating data-leaks on SHAKTI C-Class (a RISC-V based microprocessor) through power-consumption side-channels. The work provides a comprehensive analysis of various metrics and techniques that have been proposed in literature to analyze data leaks due to such side-channels. The evaluation is done using a novel framework based on a Hamming Distance metric for modeling power patterns on binary data. The work further explores the cause of such data leaks and identifies architectural designs and practices which lead to such data leakages in the context of SHAKTI C-Class processor.<br>
</p>
<iframe width="450px" height="300px" src="https://www.youtube.com/embed/3oYC9le-jAc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<p style="font-size:13px">Tags: Power Side-channel, Microprocessor Security, Leakage Estimation </p><br>

2.[Bifrost: Covert Data Exfiltration from an Air-gapped Network via Smart Bulbs](/pdf/final_csaw.pdf)
<p style="font-size:13px">  
Proposed an attack model to transfer the information from an air-gapped network to an outside world through smart bulbs using Bluetooth communication in a smart home or smart office setup. Developed an end-to-end application uses the android platform to transmit the data from sender side and the receiver can be a light sensor or a webcam that monitor the bulb from distance to decode the information by varying colors or intensity of the light bulb. It uses ASCII encoding/decoding, support synchronization of data, it uses Word2Vec tool for predicting missing words in the message. Effects such as noise intrusion and the attacker distance are studied.<br><br>
Tags: Covert Channel, Smart Bulb Reverse Engineering, Image processing, NLP Error Correction
</p>

---
