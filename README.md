# CS8395-Project-3

CS8395  
Project 3 Part 1: Project Description  
Dr. Bodenheimer  


For this project, I plan to explore a digital scavenger hunt experience enhanced by augmented reality. A regular scavenger hunt game involves exploring the physical space and interacting with pre-arranged physical items (riddles written on a piece of paper, a key to the next treasure enclosed in an envelope, etc.). It should be natural to extend such physical interactive elements with virtual elements. 

I plan to enable such virtual interactions by creating custom image targets and fiducials and placing them at points of interest throughout the physical space of the game. At each point of interest, text-based instructions along with visual flairs are presented to the user if it is purely informative, and virtual buttons will be provided to the user if it is interactive. For example, an informative point of interest could be a hint for the next prize, and an interactive point of interest could be a multiple-choice trivia question or a prize for collection. 

Besides points of interest, I also plan on placing virtual elements across the physical space to enable virtual guidance that can be conditionally activated. For example, arrows hinting for the next point of interest are activated only after the user has correctly answered a trivia question. 

I plan to implement this project on the Unity platform and use the Vuforia package. I plan on implementing the logic by creating C# scripts for the Vuforia objects. For non-textual objects such as flairs, sprites, prizes, and guidance elements, I plan on using models included in the Vuforia package or from the Unity Asset Store.
