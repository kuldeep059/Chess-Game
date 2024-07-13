# PYTHON PROJECT FOR BEGINNERS

# Grandmaster Level Chess AI (Easy to access and play)

A tough Competetion for chess master it is !!

This is a chess AI and chess game built using python. 

The end goal is to have a trained convolutional net be used as an evaluation function to evaluate future states from the tree search.  Then, the optimal move will be determined using the minimax algorithm (with alpha beta pruning).


Use python virtual machine to run this:

```
brew install python@2
virtualenv -p /usr/local/bin/python2 venv 
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

To play the ai:
```
python2 play.py
```
You will be prompted to enter a starting and ending coordinate for your move.  I.e `a2` -> `a4`

### Appendix

#### Install Python2 ipython notebook environment
```
pip install ipython notebook
python2 -m pip install ipykernel #install python2 jupyter kernel
python2 -m ipykernel install --user
```
