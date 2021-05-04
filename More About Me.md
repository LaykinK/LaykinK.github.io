### More About Me

I have been working with different languages such as:
- Python
- HTML
- JavaScript

I recently switched to the Information Technology program, and I am very excited to learn more languages, more aspects of Software Engineering, as well as gain a certificate for Cyber Security. I'm looking forward to one of my future classes, learning how to make iOS apps, as I could utilize that and other things I will learn on my resume for my career.

I have created many different programs in Python, such as those with user input, those which read and open files, and many more.

#### *Here is an example of a code I have written*:

**FizzBuzz Challenge**

The FizzBuzz Challenge is a known programming step, but the most common is the "Hello World" excercise. Fizz buzz is a number game where when counting to one hundred, a number divisible by 3 or 5 is replaced by Fizz or Buzz. Here is an article explaining more in detail how FizzBuzz works: [FizzBuzz](https://en.wikipedia.org/wiki/Fizz_buzz).

```
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

When the program is ran, the result looks like this:
![Fizz Buzz Result](/Documents/FizzBuzzResult.jpg)

