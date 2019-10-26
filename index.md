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
<html lang="en">
<head>
<meta charset="utf-8">
<title>jQuery Add Read More Link</title>
<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
<script>
$(document).ready(function(){
	var maxLength = 300;
	$(".show-read-more").each(function(){
		var myStr = $(this).text();
		if($.trim(myStr).length > maxLength){
			var newStr = myStr.substring(0, maxLength);
			var removedStr = myStr.substring(maxLength, $.trim(myStr).length);
			$(this).empty().html(newStr);
			$(this).append(' <a href="javascript:void(0);" class="read-more">read more...</a>');
			$(this).append('<span class="more-text">' + removedStr + '</span>');
		}
	});
	$(".read-more").click(function(){
		$(this).siblings(".more-text").contents().unwrap();
		$(this).remove();
	});
});
</script>
<style>
    .show-read-more .more-text{
        display: none;
    }
</style>
</head>
<body>
    <p class="show-read-more">Ut auctor velit sed consectetur rhoncus. Nunc dictum facilisis felis nec facilisis. Integer nec justo vitae orci cursus fermentum. Fusce semper, mi non tempus congue, velit leo efficitur quam, laoreet venenatis libero felis et lacus. Pellentesque mattis hendrerit nisi gravida hendrerit. Mauris sagittis tincidunt scelerisque. Vivamus lectus erat, dictum et magna quis, iaculis finibus nisl. Aliquam quis ante odio. Etiam tincidunt tellus tristique turpis tincidunt, eget condimentum urna rutrum. Donec maximus consequat dolor, sit amet condimentum ipsum gravida ac. Etiam posuere tellus mauris, et dignissim nisl rutrum quis. Mauris tincidunt ante sed velit maximus, vel tincidunt leo imperdiet. Morbi nec lacus et metus semper porttitor. Sed pellentesque ex at pellentesque scelerisque. Aliquam placerat gravida tortor, in fermentum ante commodo quis. Etiam vehicula elementum quam. Aliquam eu augue eu lacus dignissim efficitur. Proin ex metus, ornare placerat nisi at, porta lobortis turpis. Praesent euismod nec nulla ultrices maximus. Vivamus imperdiet quam ac lobortis cursus. Nam dapibus ullamcorper magna vehicula aliquam. Vivamus hendrerit molestie neque. Ut interdum diam a purus ultrices facilisis. Suspendisse molestie tempor dolor, sed tristique enim sagittis vitae. Integer eu dignissim lectus, commodo efficitur metus. Morbi quis justo finibus, interdum sem quis, imperdiet tellus. Curabitur blandit vel magna nec elementum. Vivamus tempor, urna pharetra euismod euismod, elit elit tincidunt sem, ut consectetur arcu massa non diam. Etiam scelerisque nisi magna. Nulla facilisi. Sed pharetra nunc lectus, in maximus dolor ornare sit amet.</p>
    <p>Etiam posuere tellus mauris, et dignissim nisl rutrum quis. Mauris tincidunt ante sed velit maximus, vel tincidunt leo imperdiet. Morbi nec lacus et metus semper porttitor. Sed pellentesque ex at pellentesque scelerisque. Aliquam placerat gravida tortor, in fermentum ante commodo quis. Etiam vehicula elementum quam. Aliquam eu augue eu lacus dignissim efficitur. Proin ex metus, ornare placerat nisi at, porta lobortis turpis.</p>
    <p>Praesent euismod nec nulla ultrices maximus. Vivamus imperdiet quam ac lobortis cursus. Nam dapibus ullamcorper magna vehicula aliquam. Vivamus hendrerit molestie neque. Ut interdum diam a purus ultrices facilisis. Suspendisse molestie tempor dolor, sed tristique enim sagittis vitae. Integer eu dignissim lectus, commodo efficitur metus. Morbi quis justo finibus, interdum sem quis, imperdiet tellus. Curabitur blandit vel magna nec elementum. Vivamus tempor, urna pharetra euismod euismod, elit elit tincidunt sem, ut consectetur arcu massa non diam. Etiam scelerisque nisi magna. Nulla facilisi. Sed pharetra nunc lectus, in maximus dolor ornare sit amet.</p>
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
