# bacterialGrowth
Simulates bacterial growth of arthrobacter globiformis with user changeable input fields(temperature, pH, nutrient availability, and initial bacterial population). 

The Problem:
This is meant to make it easier to visualize how a bacterial population will behave in a certain environment. The primary functions are to read in user input for said fields, calculate the bacterial growth, and then output the growth as a graph. The future steps are to make the whole user interactive environment more interesting to see, as well as a button to click to see the graph pop up. Python, pandas, and matplotlib will be used for this project.
How it Works:
The program takes in user input for temperature, pH, nutrient availability, and initial bacterial population. It uses a combination of mathematical models that simulate the growth in response to those changing values and has set values for what the optimal value would be for them. The optimal values set made it easier to detect how the bacteria would change in proportion to that. Then it sends out a graph of the bacteria population estimation at times from 0-48 hours.
<img width="328" height="470" alt="Screenshot 2026-11-27 at 1 51 35 PM" src="https://github.com/user-attachments/assets/460011c2-6424-4f69-aab5-33d73d3d8ba9" />

Tech Stack:
Python
Pandas
Matplotlib

Terminal Use:
Run these commands to run the program through your terminal-
git clone https://github.com/ysaC100/bacterialGrowth

cd bacterialGrowth

python bacterialGrowthPy.py

<img width="337" height="68" alt="Screenshot 2026-11-25 at 11 08 00 PM" src="https://github.com/user-attachments/assets/6bf07aac-3d85-4266-810e-cbeaacd60a3e" />

The above input and output should result in the graph below.
<img width="576" height="363" alt="Screenshot 2026-11-25 at 11 08 09 PM" src="https://github.com/user-attachments/assets/9d9eb31c-3e23-4856-9446-8c35c6b2d441" />

Roadmap:
Get user input and set calculations[x]
Make calculations function correctly[x]
Make basic graph appear[x]
Schedule Feature- Make graph appear fancy[x]
Schedule Feature- Make inputs appear fancy[x]
Schedule Feature- Use ipywidgets to make the program look like a website and be more interactive[-]

Demo: https://www.loom.com/share/8ea3e5c25aad4bfa91bf17929be60fae 

