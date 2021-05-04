# Welcome to Laykin's Homepage!

[More About Me](https://github.com/LaykinK/LaykinK.github.io#more-about-me)

[Other Programs]()

[How I Learned](https://github.com/LaykinK/LaykinK.github.io/blob/main/How%20I%20Learned.md#how-i-learned)       

This is an excericise in working in GitHub and creating a personal site.

I'm an Information Technology major, working towards a Bachelor of Science degree at University of Missouri-Columbia. This page is part of my Final Project for one of my classes.


### More About Me

I have been working with different languages such as:
- Python
- HTML
- JavaScript

I recently switched to the Information Technology program, and I am very excited to learn more languages, more aspects of Software Engineering, as well as gain a certificate for Cyber Security. I'm looking forward to one of my future classes, learning how to make iOS apps, as I could utilize that and other things I will learn on my resume for my career.

I have created many different programs in Python, such as those with user input, those which read and open files, and many more.

*Here is an example of a code I have written*:

**FizzBuzz Challenge**
```markdown
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
		if (i % 3 == 0 && i % 5 == 0){
			displayHTML += "fizzbuzz" + "<p>";
		}
		else if (i % 3 == 0){
			displayHTML += "fizz" + "<p>";
		} 
		else if (i % 5 == 0) {
			displayHTML += "buzz" + "<p>";
		} 
		else {
			displayHTML += i + "<p>";
		}
	}
	display.innerHTML = displayHTML;
}

</script>

</head>

<body onload = "fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```

