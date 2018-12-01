# AI-Reinforcement-Learning-02-Temporal-Difference-Learning
Reinforcement Learning Course Offered at Georgia Tech as CS 8803 on Udacity

## Ref

[Reinforcement Learning 第四周课程笔记](https://www.jianshu.com/p/881ab7e41adb)

## Context

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/RL_context.png" width = "70%" height = "70%" div align=center />

1. Model based (more supervised)
2. Model free
3. Policy search (more direct learning)

## Value Computation

### Value Computation
In this case the model is known, the calculation is easy.

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/value_computation.png" width = "70%" height = "70%" div align=center />

### Estimating from Data

We need to get value from each episode and average over them.

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/estimating_from_data.png" width = "70%" height = "70%" div align=center />

## Update Value

### Computing Estimates Incrementally

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/Computing Estimates Incrementally.png" width = "70%" height = "70%" div align=center />

### Properties of Learning Rates

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/Properties of Learning Rates.png" width = "70%" height = "70%" div align=center />

## TD(1)
