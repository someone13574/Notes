[[fromassemblertoaai.pdf]]

---

- Prof
	- Civil engineering
	- Aerospace engineering
	- Mechanical engineering
	- PHD
	- Worked on early GPS
- Flight management systems and avionics
	- Worked on this too
	- Put in start (runway, airport) and destination and the system will calculate the route and fly it
- Canadian Marconi Company
	- Worked on software for gps constellaton
	- 20200 km altitudes, 55 degrees
	- You need 3 satellites to know where you are
	- 4 to get exact position
	- Accurate to 20 ns
		- Timing is important for accurate triangulation
- The Control Display Unit Assembler Software
	- CDU 
	- He wrote this assembly for GPS
	- Talked about interrupts
		- Interrupt is a singal into a cpu which triggers some action
	- When button is hit, an interrupt is triggered and something is written into the hardware address 170100 (in octal)
	- Had different queues for interrupts based on priority
		- Clock interrupt was most important
	- Columns in assembly page (left to right)
		1. Memory location in octal
		2. Opcode
			- The different instructions which the computer can execute
	- Fortran Queue
- Robot to solve rubix cube
	- Made from parts of an old photocopy
	- Connected laptop via parallel port
		- Pins control motors
	- Camera
	- Made from wood
	- Steps to solve
		- Camera scans each side
		- Laptop computes solution
		- Robot executes solution
- March Networks, 2001
	- Built DVRs
		- Used to record video for security applications
	- Hired when on sabatical for year
		- Hired to come up with system for improving speed and people tracking
		- Had to do it on a TMS320C21
		- He wrote code to track people
			- Averages chunks of 32 pixels
				- Mitigates noisy images
				- Used 32 for fast division
			- Converts pixels to either on or off to save memory
			- Looks at which pixels change
			- Video plots number of pixels on each axis in two histograms
				- Used to create bounding box
- Worked at company from Espial/Enghouse
	- Writing code for TV Set Top Box
	- Add 800,000 lines of code written by many people over many years
	- Javascript/HTML
	- Used new things like Eclipse IDE, Jenkins, Jira, Codereview, and SVN
		- Talked about how companies without vsc died
	- Went over javascript and c code
- Reinforcement learning brief tutorial
	- Value functions $V^\pi (s)$ and $Q^\pi (s)$ 
	- Grid World Example
		- Robot in 3x3 grid can move in one of four directions
		- When it moves to cell 1, it immediately moves to cell 9 and gets a reward of +10. If the agent hits a wall, it remains in its current cell and gets a punishment of -1.
	- Don't need to understand equations
	- Pursuer Evader Game
		- Car tries to hit pedestrian
	- Most reinforcement learning these days is neural networks
	- Guarding A territory game
		- Invador tries to get as cloes as possible to territory
		- Guard tries to stop them
		- Vincent made simulations using RL
		- Hashem made actual robots follow the paths made in the simulation
	- The adaption laws (not much time spend)
	- Guarding a Territory with Deception
		- Several goal
		- Invader has one true goal
		- Defender must protect all goals
	- Robots learning to leave a room
- Drones
	- 3 drones follow small robot all controlled by neural networks
	- Connected via 5g
	- Map out area
- CNN's and GAN's
	- Image generation and classification