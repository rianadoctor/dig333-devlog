[<](README.md)

# Week 04 - DevLog




## Outcomes 

<!-- 
Using the backslash preserves the list number 
https://stackoverflow.com/a/50916345/441878 
-->



1\. 📚Read Philip K. Dick Pay for the Printer (1956) and The Preserving Machine (1953). Write a reflection below:

- I liked both stories because they show how fake comfort falls apart when you don’t know how to build anything yourself. In “Pay for the Printer,” the “puddinged” objects make it obvious that their whole civilization is just copies of copies, and once the printer fails, they’re helpless. The wooden cup matters more than the perfect glass because it represents real skill instead of dependence. In “The Preserving Machine,” Labyrinth thinks he is saving music, but once it turns into animals, it stops being music and starts being something that just wants to survive. When the Bach creature turns back into distorted, ugly noise, it proves that you cannot preserve meaning by changing its form, and that survival is not the same thing as beauty.



2\. Connect a concept from [Synthesizing with Moog | Lesson 4: Resonance](https://www.youtube.com/watch?v=6spVzRqOsVw) to an aspect of the interface in the [Learning Synth Playground](https://learningsynths.ableton.com/en/playground) by Ableton 

- The video explains how the Voltage-Controlled Filter lets you sculpt sound by removing or emphasizing certain harmonics from an oscillator. In the Ableton Learning Synth Playground, the Filter section does exactly this by letting you adjust the cutoff frequency and resonance to shape the tone. When you raise the cutoff, more harmonics pass through and the sound becomes brighter. When you increase resonance, it emphasizes the frequencies around the cutoff point, making the sound more sharp and expressive. This directly reflects the Moog concept that the filter is not just reducing sound, but actively shaping and defining it.


3\. 📚Read Chapter 1 Get to know your  Raspberry Pi Pico (8-19) in [Get Started with MicroPython on Raspberry Pi Pico](https://www.mclibre.org/descargar/docs/revistas/hackspace-books/hackspace-get-started-with-micropython-on-pico-01-202101.pdf). Read and follow tutorial to install the MicroPython firmware on Pico.

p.20–25 - Read and follow tutorial to install Thonny and run the "Hello, World!" Add documentation below to show you can save and run python code on the Pico.

I followed the tutorial to install MicroPython by:
1. Openning Thonny
2. Selecing MicroPython as the interperatort
3. Creating a simple HelloWord.py file
4. Typing print("Hello World!")
5. Running my Python scirpt
6. Looking for the output in the shell



4\. What is the difference between a microcontroller and a regular computer? (Chapter 1)

- A microcontroller is built to do one main job over and over again, usually controlling hardware like sensors, LEDs, or motors. A regular computer runs a full operating system and can handle lots of different programs at once. Microcontrollers are smaller, simpler, and use very little power, which is why they’re built into everyday devices. Regular computers are much more powerful and meant for things like browsing the internet, gaming, and running complex software.


5\. 📚Read Chapter 2 (20–33) Programming with MicroPython. Summarize steps to program the Pico from your computer.

1. Connect Pico to laptop (USB) 
2. Open Thonny
3. Select MicroPython (Raspberry Pi Pico) as the interpreter
4. Write Python code in Thonny
5. Save the file to the Pico
6. Run the program and view output in the Shell


6\. 📚Read Chapter 2: "Challenge: New Message" (26) - You can display programming code in a markdown file using three backticks, a new line, and then three more backticks on the following line. 

```python
print("Hello I'm Riana!")
print("I'm adding more messages!")
```

You use script mode if you want to save and run the same program again, while you would use interactive mode for quicker tests. If you remove quotes or parentheses, then you would get an error. If you remove the quotes pythons thinks the words are variable names, and you'll get variable not found error (like NameError). If the parentheses are removed, then the print won't work, and you'll get a syntax error.

7\. Chapter 2: "Challenge: Loop the Loop" (26)

```python
# definite loop
for i in range(4):
    print("Loop running 4 times!")

# second definite loop 
for j in range(6):
    print("Loop running 6 times!")

# nested loop
for a in range(3):
    for b in range(2):
        print("Nested loop!")

```

A nested loop is when the inner loop runs all its repeats for each single repeat of the outer loop.

8\. Chapter 2: "Challenge: Add More Questions" (26)
```python

user_name = input("What is your name? ")

while user_name != "Clark Kent":
    print("You are not Superman - try again!")
    user_name = input("What is your name? ")

print("You are Superman!")

# Ask more questions
favorite_color = input("What is your favorite color? ")
city = input("What city do you live in? ")

print("Your favorite color is", favorite_color)
print("You live in", city)

# Number comparison challenge
num = int(input("Type a number: "))
if num > 5:
    print("Your number is higher than 5.")
elif num < 5:
    print("Your number is lower than 5.")
else:
    print("Your number is exactly 5.")
```

9\.  📚Read Chapter 3 (34–43) Physical Computing. How many Ground pins are on the Pico?

The Pico has 8 Ground (GND) pins.



10\. Post sketches for your musical instrument and a parts list.




## Other experiments

<!-- 
Share details about other electronic experiments you are working on this week?
-->

- Currently coming up with an idea for my musical instrument.



## Questions to bring up in class

<!-- 
Share questions you would like to bring up in class.
-->

- N/A