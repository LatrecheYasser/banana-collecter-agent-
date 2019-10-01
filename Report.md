# banana-collecter-agent
 ## how the Qnetwork works:
 the Qnetwork consiste of 2 networks of the same architecteur, used in parallel in the learning phase. the first one is the local network which is the principal one that used to predict the Q(s,a) and the other one used to predict the target Q value, we train the local network and at some point we update the other one by coping the paramaters of the first one to the other one.  

and we use the **MSE** function to calculate the difference between the target and the predicted Q value and based on that we improve the networks

 ## network description <br/>

in the first of this challange i tried with a big architecteur with 6 layers and a big number of unites, after more 1000 episode i found out that this architector donesn't help the agent to learn at all. so after different networks, i found out that a small one can give much better resautls, so i ended up with 3 layer NN.

## the training and the results 
in my project i used this paramaters 
> BUFFER_SIZE = int(1e5)   : i used a buffer of a big size to collect as many simples as i can

> BATCH_SIZE = 256   : a big batch size gave a good values in this case, it alows the network to lean from a lot of expeincies in one time  

> GAMMA = 0.99  : it's some how a big value to let the network focus on all the actions.
> TAU = 0.003              

> LR = 4e-5               

> UPDATE_EVERY = 4 

and i got an avrege of rewards equal to 15.03 just after 607 episodes.

<p align="center">
  <img src="./Images/episodes.png"/>
</p>

and the plot of rewards is 

<p align="center">
  <img src="./Images/plot.png"/>
</p>

## future work
this project can be improved in many sides.
- 1 - use images as the input.
- 2 - parameter tuning.

and other improvemnts 