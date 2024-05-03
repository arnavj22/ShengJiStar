Here is the code for my CS 394R final project:

You can train the agent with 
```
python TrainLoop.py --model-folder <SAVE_PATH> --discount 0.95 --epsilon 0.015 --games 2000 --eval-size 300
```
You can add `--eval-agent DMC` if you want to evaluate vs the Deep Monte Carlo Agent.

Once again, big thanks to https://github.com/TheMoon2000/shengji_plus for providing the environment code to build this project off of.
