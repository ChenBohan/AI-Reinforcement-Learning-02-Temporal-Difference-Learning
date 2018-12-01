# AI-Reinforcement-Learning-02-Temporal-Difference-Learning
Reinforcement Learning Course Offered at Georgia Tech as CS 8803 on Udacity

## Ref

[Reinforcement Learning 第四周课程笔记](https://www.jianshu.com/p/881ab7e41adb)

## Overview

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/what_have_we_learned_3.png" width = "70%" height = "70%" div align=center />

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

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/TD(1) Rule.png" width = "70%" height = "70%" div align=center />

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/TD(1) Example.png" width = "70%" height = "70%" div align=center />

## TD(0)

First of all, if we have infinite data, TD(1) will also do the right thing.

When we have finite data, we can repeatedly infinitely sample the data to figure out all the ML. This is what TD(0) do.

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/TD(0) Rule.png" width = "70%" height = "70%" div align=center />

## TD(Lambda) Rule

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/TD(Lambda) Rule.png" width = "70%" height = "70%" div align=center />

## K-Step Estimators

- E1 is one-step estimator (one-step look up) TD(0)

- E2 is two-step estimator, and Ek is k-step lookup.

- When K goes to infinity, we got TD(1)

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/K-Step Estimators.png" width = "70%" height = "70%" div align=center />

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/K-Step Estimators and TD(Lambda).png" width = "70%" height = "70%" div align=center />

<img src="https://github.com/ChenBohan/AI-Reinforcement-Learning-02-Temporal-Difference-Learning/blob/master/readme_img/TD(Lambda) Empirical Performance.png" width = "70%" height = "70%" div align=center />

