# Deep Q Network
Deep Q learning on Atari in Pytorch.
```
env = 'Breakout-v0'
```
## Credit
This project reuses most of the code in: https://www.youtube.com/playlist?list=PLZeihsNsdQdRdhni8U5KIdxsRIicW498s
## Requirement
* numpy
* gym==0.23.1
* gym[atari]
* opencv-python
* torch --extra-index-url https://download.pytorch.org/whl/cu113
* msgpack==1.0.2
* tensorboard
* matplotlib
* pygame
* gym[accept-rom-license]
## Usage
To train model:
```
 python dqn.py
```
Observe result:
```
 python observe.py
```
Visualization through Experiment graphs:
```
python -m tensorboard.main --logdir=logs
```