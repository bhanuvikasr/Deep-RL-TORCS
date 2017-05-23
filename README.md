# Using Keras and Deep Deterministic Policy Gradient to play TORCS
## Abstract


## Simulation Environment
We use TORCS([gym_torcs](https://github.com/ugo-nama-kun/gym_torcs)) simulation environment for this task.  
![](fast.gif)

## Installation Dependencies:

* Python 2.7
* Keras 1.1.0
* Tensorflow r0.10
* [gym_torcs](https://github.com/ugo-nama-kun/gym_torcs)

## How to Run?

```
git clone https://github.com/bhanuvikasr/Deep-RL-TORCS.git
cd DDPG-Keras-Torcs
cp *.* ~/gym_torcs
cd ~/gym_torcs
python ddpg.py 
```

(Change the flag **train_indicator**=1 in ddpg.py if you want to train the network)

## Credits
Thanks to [Yanpanlau](https://github.com/yanpanlau/DDPG-Keras-Torcs.git)
