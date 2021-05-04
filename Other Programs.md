## Other Programs

[Scalable Vector Graphics Challenge](https://github.com/LaykinK/LaykinK.github.io/blob/main/Other%20Programs.md#the-program-i-completed-using-html-only)

[Cylinder Volume Calculation Challenge](https://github.com/LaykinK/LaykinK.github.io/blob/main/Other%20Programs.md#the-program-i-completed-using-python)

I have created many different programs, some even in different languages.

I have programmed in:
- HTML
- Python
- JavaScript

The FizzBuzz Challenge on the homepage was completed utilizing JavaScript to create an HTML file.


#### *The program I completed using HTML only*:

**Scalable Vector Graphics Challenge**

Scalable Vector Graphics (SVG) is an XML-based vector image format for two-dimensional graphics with support for interactivity and animation. To know more about SVG's visit the following link: [SVG's](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics).

```
<!DOCTYPE html>
<html>
<body>

<h1>Welcome to Laykin Kennemer's INFOTC 1000 Project!</h1>

<p>Shown in this website will be a series of SVGs, also known as Scalable Vector Graphics. These SVGs are produced from my experimentation using the w3schools.com "Try it Yourself" editor.</p>

<h2>Laykin's first SVG</h2>

<svg width="475" height="475">
	<rect x="25" y="10" width="200" height="250" rx="10"
		stroke="green" stroke-width="12" fill="teal" />
		
	<rect x="75" y="60" width="200" height="250" rx="20"
		stroke="red" stroke-width="8" fill="maroon" 
		fill-opacity="0.80" />
		
	<rect x="125" y="110" width="200" height="250" rx="30"
		stroke="yellow" stroke-width="4" fill="lime"
		fill-opacity="0.60" />
	
	<rect x="175" y="160" width="200" height="250" rx="40"
		stroke="maroon" stroke-width="2" fill="purple"
		fill-opacity="0.40" />
		
	<rect x="225" y="210" width="200" height="250" rx="50"
		fill="blue"
		fill-opacity="0.20" />
</svg>

<h2>Laykin's second SVG</h2>

<svg width="500" height="800">
	<defs>
		<filter id="f1" cx="150" cy="250" rx="200%" ry="200%">
			<feOffset result="offOut" in="SourceGraphic" dcx="20" dcy="20" />
			<feColorMatrix result = "matrixOut" in = "offOut" type = "matrix" values = "0.2 0 0 0 0 0 0.2 0 0 0 0 0 0.2 0 0 0 0 0 1 0"/>
			<feGaussianBlur result="blurOut" in="matrixOut" stdDeviation="10" />
			<feBlend in="SourceGraphic" in2="blurOut" mode="normal" />
		</filter>
	</defs>
	<ellipse cx="150" cy="225" rx="100" ry="200"
style="fill:yellow" filter="url(#f1)" >
	<animate attributeName="cx" attributeType="XML" begin="5s" dur="15s" fill="freeze" from="100" to="0" />
	<animate attributeName="cy" attributeType="XML" begin="5s" dur="15s" fill="freeze" from="80" to="0" />
	<animate attributeName="cx" attributeType="XML" begin="5s" dur="15s" fill="freeze" from="150" to="345" />
	<animate attributeName="cy" attributeType="XML" begin="5s" dur="15s" fill="freeze" from="225" to="475" />
	<animate attributeName="fill" attributeType="CSS" from="yellow" to="purple" begin="5s" dur="13s" fill="freeze" />
	
	</ellipse>
</svg>
	
</body>
</html>
```

The completed program, when ran, looks like this:
![SVG Result](/Documents/SVGResult.jpg)


#### *The program I completed using Python*:

**Cylinder Volume Calculation Challenge**

This program is an excericise in creating a program that a user can interact with to provide values and perform calculations for.

```
def get_nonnegative_float_from_user(prompt):
    while True:
        try:
            value = float(input(prompt))
            if (value < 0):
                print("You entered a negative value. The value can not be negative. Please reenter.")
                continue
            break
        except ValueError:
            print("The input is not a valid number. Please re-enter.")
            continue
    return value

def perform_calculation():
    Cylinder_height = get_nonnegative_float_from_user("What is the height of the cylinder? ")
    Cylinder_radius = get_nonnegative_float_from_user("What is the radius of the cylinder? ")

    Cylinder_volume = 3.1415 * Cylinder_radius * Cylinder_radius * Cylinder_height

    print("The volume of the cylinder is", str(Cylinder_volume))

def main():
    while True:
        perform_calculation()
        do_again = input("Would you like to perform another calculation? (y/n) ")
        if (do_again != "y"):
            break

main()
```


[Go Back Home](https://github.com/LaykinK/LaykinK.github.io#welcome-to-laykins-homepage)
