## Welcome to Laykin's Homepage!

[More About Me](https://github.com/LaykinK/LaykinK.github.io#more-about-me)	[How I Learned](https://github.com/LaykinK/LaykinK.github.io#how-i-learned)	[]

This is an excericise in working in GitHub and creating a personal site.

I'm an Information Technology major, working towards a Bachelor of Science degree. This page is part of my Final Project for one of my classes.

### More About Me

I have been working with different languages such as Python, HTML, and JavaScript throughout the past year as part of my program.

I have created many different programs, such as those with user input, those which read and open files, and many more.

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

### How I Learned!

I learned Python through utilizing websites such as [pythonprogramming.net](https://pythonprogramming.net/introduction-to-python-programming/) and [w3schools.com](https://www.w3schools.com/python/default.asp), as well as practicing using the code through different challenges and excercises.  I learned JavaScript and HTML trhough using the website [codeacademy.com](https://www.codecademy.com/learn/learn-html), and also through practicing using excercises and challenges to put the knowledge of the code into practice and see personally how the code functioned and worked.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
