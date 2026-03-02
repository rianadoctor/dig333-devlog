[<](README.md)

# DevLog 06




## Outcomes 

<!-- 
Using the backslash preserves the list number 
https://stackoverflow.com/a/50916345/441878 
-->




omundy/learn-computing/command-line 


1\. Follow the [Command Line tutorial](https://omundy.github.io/learn-computing/slides/command-line.html). Watch [
Basic Terminal Usage](https://www.youtube.com/watch?v=jDINUSK7rXE). Describe in your own words what each of the following commands will do ✏️ 

```python
cd ~/
mkdir test && cd test
touch hello.py
echo "print(Hello World)" > hello.py
python hello.py
```

- The "cd ~/" command moves you to your home directory. The ~ is just shorthand for your personal folder on the computer. The "mkdir test && cd test" creates a new folder called test, and then immediately moves into that folder. The && just means “run the second command only if the first one works.” The "touch hello.py" command creates a new empty file called hello.py. The "echo "print(Hello World)" > hello.py" writes the text print(Hello World) into the file hello.py, replacing anything that was in it before. The "python hello.py" command runs the Python file, so it executes whatever code is inside hello.py.


2\. Share 3 differences between the Raspberry Pi and Raspberry Pi Pico ✏️

1. A Raspberry Pi is a full single-board computer that can run an operating system, while a Raspberry Pi Pico is just a microcontroller.
2. The Raspberry Pi can connect to a monitor, keyboard, WiFi, etc., but the Pico usually just runs one program and interacts with hardware.
3. The Raspberry Pi uses an SD card and runs Linux, while the Pico stores code directly on the board and doesn’t run a full OS.


3\. Why shouldn't you power your Raspberry Pi from your computer USB? ✏️

- Because your computer’s USB port might not provide enough power. That can cause unstable behavior, random shutdowns, or even damage the board. It’s safer to use a proper power supply that provides enough current.


4\. Of the ways to destroy a Raspberry Pi, which are you most likely to do? How will you keep from doing it? ✏️

- I’d probably mess it up by shorting something with wires or plugging something into the wrong GPIO pin. To prevent that, I’d double-check wiring before powering it on and avoid touching components while it’s powered.


5\. Raspberry Pi OS is based on what Linux distribution? What does that even mean? ✏️

- Raspberry Pi OS is based on Debian Linux. That means it’s built from the Debian operating system, so it uses the same core system structure and package manager. It’s basically a customized version of Debian made to run well on Raspberry Pi hardware.


6\. What does it mean to "Flash" your SD Card? ✏️

- Flashing an SD card means writing an operating system image onto it so the Raspberry Pi can boot from it. It’s like installing the OS onto the card.


7\. What does it mean if you see a red light and a flashing green light on your powered Raspberry Pi? ✏️

- The red light means the Pi is getting power. The flashing green light usually means it’s reading from the SD card and booting. If the green light keeps flashing in a strange pattern, it can mean there’s a problem with the SD card or boot files.


8\. What does a package manager do? ✏️

- A package manager installs, updates, and removes software. It keeps track of dependencies and makes sure programs get the files they need to run.


9\. Describe how you might use Git with a Raspberry Pi? ✏️

-  You could use Git to clone repositories onto the Pi, track changes in your code, push updates to GitHub, and manage different versions of your projects. It’s helpful if you’re coding directly on the Pi.


10\. What are two things your personal computer and a linux OS like Raspberry Pi have in common?

1. They both run an operating system that manages hardware and software.
2. They both can run programs, store files, and connect to networks.







## Other experiments

<!-- 
Share details about other electronic experiments you are working on this week?
-->

- 



## Questions to bring up in class

<!-- 
Share questions you would like to bring up in class.
-->

- 