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
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#more {display: none;}
</style>
</head>
<body>
  <h4> <a href="https://arxiv.org/abs/1911.08813">1.PARAM: A Microprocessor Hardened for Power Side-Channel Attack Resistance (HOST2020-Accepted)</a> </h4>
<p style="font-size:13px">The power consumption of a microprocessor is a huge channel for information leakage. While the most popular exploitation of this channel is to recover cryptographic keys from embedded devices, <span id="dots">...</span>
  <span id="more"> other applications such as mobile app fingerprinting, reverse engineering of firmware, and password recovery are fast growing threats. Countermeasures proposed so far are tuned to specific applications, such as crypto-implementations. They are not scalable to the large number and variety of applications that typically run on a general purpose microprocessor. We investigate the design of a microprocessor, called PARAM with increased resistance to power based side-channel attacks. To design PARAM, we start with identifying the most leaking modules in an open-source RISC V processor. We evaluate the leakage in these modules and then add suitable countermeasures. The countermeasures depend on the cause of leakage in each module and can vary from simple modifications of the HDL code ensuring secure translation by the EDA tools, to obfuscating data and address lines thus breaking correlation with the processor's power consumption. The resultant processor is instantiated on the SASEBO-GIII FPGA board and found to resist Differential Power Analysis even after one million power traces. Compared to contemporary countermeasures for power side-channel attacks, overheads in area and frequency are minimal.</span>
  <a href="javascript:myFunction()" id="myBtn"> More >></a>
  </p>

<script>
function myFunction() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = " More >>"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = " Less <<"; 
    moreText.style.display = "inline";
  }
}
</script>

</body>
</html>                 

---

### Projects
1.[Framework for Comprehensive Side-channel Evaluation of a Microprocessor](/pdf/1000-19.07.18-Muhammad-Arsath-Chester-Rebeiro-IIT-Madras(2).pdf)
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#more2 {display: none;}
</style>
</head>
<body>
<p style="font-size:13px">This work proposes a framework for evaluating data-leaks on SHAKTI C-Class (a RISC-V based microprocessor) through power-consumption side-channels. The work <span id="dots2">...</span>
  <span id="more2"> provides a comprehensive analysis of various metrics and techniques that have been proposed in literature to analyze data leaks due to such side-channels. The evaluation is done using a novel framework based on a Hamming Distance metric for modeling power patterns on binary data. The work further explores the cause of such data leaks and identifies architectural designs and practices which lead to such data leakages in the context of SHAKTI C-Class processor.</span>
  <a href="javascript:myFunction2()" id="myBtn2"> More >></a>
  <br>
  </p>

<script>
function myFunction2() {
  var dots = document.getElementById("dots2");
  var moreText = document.getElementById("more2");
  var btnText = document.getElementById("myBtn2");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = " More >>"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = " Less <<"; 
    moreText.style.display = "inline";
  }
}
</script>
</body>
</html>  

<iframe width="450px" height="300px" src="https://www.youtube.com/embed/3oYC9le-jAc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<p style="font-size:13px">Tags: Power Side-channel, Microprocessor Security, Leakage Estimation </p>

2.[Bifrost: Covert Data Exfiltration from an Air-gapped Network via Smart Bulbs](/pdf/final_csaw.pdf)
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#more3 {display: none;}
</style>
</head>
<body>
<p style="font-size:13px">Proposed an attack model to transfer the information from an air-gapped network to an outside world through smart bulbs using Bluetooth communication in a smart home<span id="dots3">...</span>
  <span id="more3"> or smart office setup. Developed an end-to-end application uses the android platform to transmit the data from sender side and the receiver can be a light sensor or a webcam that monitor the bulb from distance to decode the information by varying colors or intensity of the light bulb. It uses ASCII encoding/decoding, support synchronization of data, it uses Word2Vec tool for predicting missing words in the message. Effects such as noise intrusion and the attacker distance are studied.</span>
  <a href="javascript:myFunction3()" id="myBtn3"> More >></a>
  <br>
  </p>
<script>
function myFunction3() {
  var dots = document.getElementById("dots3");
  var moreText = document.getElementById("more3");
  var btnText = document.getElementById("myBtn3");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = " More >>"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = " Less <<"; 
    moreText.style.display = "inline";
  }
}
</script>
</body>
</html>  
<p style="font-size:13px">Tags: Covert Channel, Smart Bulb Reverse Engineering, Image processing, NLP Error Correction
</p>

---
### Seminar
<h4>PARAM: A Microprocessor Hardened for Power Side-Channel Attack Resistance</h4>
