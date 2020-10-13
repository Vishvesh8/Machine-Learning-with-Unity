# Machine-Learning-with-Unity
Path traversal using Machine Learning Agents release 6 and Unity 2020.1.6f1

# Usage
This Machine learning algorithm creates smooth and seamless path traversal that can be used in games for game object pursuit. Existing path traversal algorithms seem too robotic and are a bit too accurate to seem human like. This CNN model gives animated form of movement that is ideal for games, animated videos and related interactive media.

Note: For future versions of Unity, ML Agents requirements could be different. Please visit the official website to be up to date with the versions.

# Getting Started
1) Download ML Agents release 6 and install it into Unity using Package Manager. Download web page - https://github.com/Unity-Technologies/ml-agents
2) Enable ML Agents in your project from the Package Manager.
3) Git clone this package or download it manually. Import this package into your Unity Editor using Assets -> Import Package -> Custom Package
4) (Optional) Go to the folder where you have saved ml agents release 6 and go to config/ppo and open PlayerMaze.yaml. Make the required changes into the configurations.
5) Create a virtual environment and activate it in your terminal/command prompt.
6) cd into ml agents release 6 folder and type the following command-> mlagents-learn.exe config\ppo\PlayerMaze.yaml --run-id=PlayerModel
7) If the above command shows errors, run the following :
mlagents-learn.exe config\ppo\PlayerMaze.yaml --run-id=PlayerModel --force
8) Click play in Unity and let the cnn model train.
9) Obtain the saved model in results folder. Copy it into your assets and put it into your Player's Behavior parameters script.
10) Observe the results.

# What's next
Using the system of rewards and punishments used in this project, we can train the AI to perform a variety of tasks like driving a virtual car, throwing a ball through a hoop, shooting at the target, etc.
