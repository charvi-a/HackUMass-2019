## HackUMass-2019 

I participated in a hackathon at my university (University of Massachusetts, Amherst) where I worked with a team to create this project.  

### What is a Vine?
A vine is a short seven second looping video. 

### Description:
A gadget that randomly plays out the audio of some of the most iconic vines of our generation based on the three facets of human emotion: sad, happy, and neutral.

### What it does:
With our project, the user is given a choice to press one of the three buttons, each of which are meant to represent a certain emotion. The speaker connected to our project then randomly plays out the audio of one of the vines we chose to represent each emotion category. The user is able to repeat this as many times as desired.

### How it was built:
First, we got a raspberry pi in order to create a bridge from hardware to software. Then, we got some jumpers and wired the pi to the circuit. Buttons were added to the circuit along with the resistors to create an interactive piece. Afterward, we connected a speaker to the pi via an aux cord.

As for the software, we flashed Raspbian onto a micro SD card and inserted it into the Raspberry Pi. We then proceeded to connect it to a monitor and then opened Mu (Python editor and IDE) to code out the processes of our gadget in Python. We downloaded the vine audio in wav files to implement into our code. We then coded our software. After the coding and debugging was done, we ran the software to make sure the hardware and software were working properly together.

### Technologies used:
- Python  
- Raspberry Pi
