## Welcome to Laykin's Homepage!

This is an excericise in working in GitHub and creating a personal site.

I'm an Information Technology major, working towards a Bachelor of Science degree. This page is part of my Final Project for one of my classes.

### More About Me!

I have been working with different languages such as Python, HTML, and Java throughout the past year as part of my program.

I have created many different programs, such as those with user input, those which read and open files, and many more.

*Here is an example of a code I have written*:

FizzBuzz Challenge
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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LaykinK/LaykinK.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
