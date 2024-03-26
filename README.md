# Evolutionary-Model-Merge
Unofficial Implementation of Evolutionary Model Merging
* Inspired by work from Sakana.AI [Evolutionary Optimization of Model Merging Recipes] (https://arxiv.org/abs/2403.13187)
* Built with reference on code from Maxime Labonne's code in AutoMerger, MergeKit, and of course, CLAUDE-3
* Computation done on @Modal

https://github.com/fangyuan-ksgk/Evolutionary-Model-Merge/assets/66006349/9750ba46-61ac-4605-9c67-ef1cfe8fc551

![image](https://github.com/fangyuan-ksgk/Evolutionary-Model-Merge/assets/66006349/2b758f02-b5d1-4a41-8897-217021b8fa50)

Firstly, one need to know how to evalute the fitness of a merged model. I use a instruction following dataset to score a model based on it's average complexity on providing the target answer. Feel free to change it to any other dataset you like. 




