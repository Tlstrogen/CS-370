# Brief Explanation of My Work on the Project

For this project, I had the exciting challenge of developing an intelligent pirate agent capable of navigating a maze to find a treasure before the player. The core problem was a classic pathfinding scenario, and the solution required leveraging reinforcement learning—in this case, deep Q-learning.
The project came with some foundational code already in place, providing a solid framework to build upon. Specifically, I was given the following:

1.	Environment Setup: The TreasureMaze.py file defined the environment as a matrix, representing the maze layout, including pathways and obstacles.

2.	Game Experience Management: The GameExperience.py file provided the structure to store game episodes, which was critical for training the reinforcement learning algorithm.

3.	Starter Notebook: The TreasureHuntGame.ipynb file included starter code for setting up the pirate agent and integrating it with the environment.

My work focused on creating the deep Q-learning component and ensuring the agent could successfully learn and adapt to the maze environment. Specifically, I:

•	Developed the Q-Training Algorithm: I implemented a deep Q-learning approach using a neural network to approximate the Q-values. This required defining the reward function, setting up the neural network 
architecture, and creating the training loop.

•	Fine-Tuned Exploration vs. Exploitation: Balancing these aspects was essential. I implemented an epsilon-greedy strategy to ensure the agent could both explore new paths and exploit known ones.

•	Debugged and Optimized Code: Ensuring the agent's performance met the project goals required testing, tweaking parameters (like learning rate and discount factor), and refining the reward system to improve efficiency.

•	Commented Code for Clarity: To maintain industry standards, I included in-line comments to make the code readable and understandable for future users or developers.



# What do computer scientists do, and why does it matter?
A computer scientist, at their core, is a kind of problem solver who dances between abstraction and reality. It used to be that they worked strictly with the internals of computers—logic gates, binary math, and code that felt like writing instructions for a particularly stubborn robot. But today, being a computer scientist is more like being a technologist or innovator. It's about finding ways to use technology to improve the world—or at least make it faster, shinier, or a little more fun.

Why does it matter? Because we live in a world increasingly defined by technology. Whether it's making sense of mountains of data, designing algorithms to recommend your next favorite song, or creating tools that help doctors diagnose diseases faster, computer scientists shape the tools that shape society. Done well, it creates opportunity, connection, and maybe even a little magic. Done poorly? It reinforces inequality, invades privacy, or amplifies bias. The stakes are high, which makes this work both thrilling and terrifying.

# How do I approach a problem as a computer scientist?

The secret is to think systematically but stay playful. First, define the problem. (Sounds obvious, but you'd be amazed at how many people skip this step!) What are the constraints? What does success look like? Then, break it down. Big problems are just a stack of smaller problems waiting to be solved.

Think critically about tools and tradeoffs—do you brute force your way through, or is there an elegant solution hiding in the mess? Don’t be afraid to try something, fail, and learn why it didn’t work. That’s where the fun happens! And keep a beginner’s curiosity. Ask stupid questions. Look for ideas in unexpected places. Sometimes the best solution to a technical problem comes from a conversation about art or biology or how your grandma organizes her spice rack.

# What are my ethical responsibilities to the end user and the organization?

Ethics in technology is like walking a tightrope—only the rope is made of shifting sand. As a computer scientist, your primary loyalty should be to the end user. Why? Because they’re the ones who live with the consequences of your work. If your product doesn’t serve them—or worse, harms them—you’ve failed.

But there’s a twist. Ethical responsibilities aren’t always black and white. Take large language models, for example. Some universities ban their use, saying they undermine academic integrity. Fair enough, but here’s the question: What about the student with schizophrenia who struggles with cognitive load? Shouldn’t they be allowed to use such tools as a sort of cognitive hearing aid? We let people use prosthetics for their limbs and glasses for their eyes—why not tools for the mind? Sometimes what looks like a shortcut is actually a lifeline.

And about this fear of “overreliance on technology”: It’s a double standard. Nobody complains that pacemakers make hearts “lazy,” so why worry that tools like AI make brains soft? It’s not about avoiding technology—it’s about teaching people to wield it wisely.

As for organizations, their ethics can be...let’s say, flexible. Look at how universities handled grading during COVID. Pass/fail systems were implemented to help students during tough times. Practical? Yes. Consistent with their usual notions of "academic integrity"? Maybe not. The lesson? Organizational ethics often follow the path of least resistance. That doesn’t mean you should ignore them, but you shouldn’t treat them as sacred, either.

# Why does all this matter to me?

Because it’s not just about building something cool—it’s about building something right. Technology should give people unfair advantages, but the right kind: the kind that help level the playing field for those who’ve always been at a disadvantage. If we’re going to navigate a world where the odds are disproportionately stacked against some people, then the least we can do as technologists is tilt the odds in their favor.

End users deserve tools that make their lives better, even if it makes organizations squirm. So, I don’t see ethics as a set of red lines to avoid. I see them as boundaries to challenge—carefully, thoughtfully, and always with the goal of helping people thrive in a world that’s still catching up with its own technology.

