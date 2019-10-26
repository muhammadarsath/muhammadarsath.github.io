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
1.PARAM: A Microprocessor Hardened for Power Side-Channel Attack Resistance (HOST2020-Accepted)
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#more {display: none;}
</style>
</head>
<body>

<h2>Read More Read Less Button</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scel<span id="dots">...</span><span id="more">erisque enim ligula venenatis dolor. Maecenas nisl est, ultrices nec congue eget, auctor vitae massa. Fusce luctus vestibulum augue ut aliquet. Nunc sagittis dictum nisi, sed ullamcorper ipsum dignissim ac. In at libero sed nunc venenatis imperdiet sed ornare turpis. Donec vitae dui eget tellus gravida venenatis. Integer fringilla congue eros non fermentum. Sed dapibus pulvinar nibh tempor porta.</span></p>
<button onclick="myFunction()" id="myBtn">Read more</button>

<script>
function myFunction() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Read more"; 
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Read less"; 
    moreText.style.display = "inline";
  }
}
</script>

</body>
</html>                    


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
