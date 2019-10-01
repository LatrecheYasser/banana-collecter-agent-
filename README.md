# banana-collecter-agent
train an agent in Unity Machine Learning Agents to collect yellow bananas and avoid blue ones

for this project i will train an agent to collect as many yellow bananas as it can using [**Unity ML-Agents**](https://github.com/Unity-Technologies/ml-agents), and the envirenment will be a large square world.

<p align="center">
  <img src="https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif"/>
</p>

A reward of **+1** is provided for collecting a yellow banana, and a reward of **-1** is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:
 - 1 - move forward 
 - 2 - move backword
 - 3 - turn left 
 - 4 - turn right

---
so how to run this project ?

the depepandencies that you need to install inorder to run this project are:

  - numpy
  - matplotlib
  - pytorch
  - pandas
  - jupyter
  - and the Unity ML-Agents (you find below the link to how install it page ) 

or you can install them in defrent ways, by derectly run the folowing scripit in the terminal ` pip install -r requirements.txt `

or you have to create a vertual python env and  install the dependencies . or you can simply follow the instractions below
 - 1 - clone this project 
 - 2 - move to it's folder and open the terminal there 
 - 3 - run `  conda env create -f DRLND-banana-collecter.yml ` this will create an envirenment and install the needed depandecies automaticly <br/


 and finaly now you will have to install the Unity ML-Agent, inorder to do that just [follow this link](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) <br/>

now if u did all this correctly you are able to run the code. in the same folder run this ` source activate DRLND-banana-collecter ` than `jupyter notebook`. and yfrom the notebook home page you can open `DRLND-banana-collecter.jpynb`.

