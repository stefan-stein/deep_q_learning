# Reinforcement Learning with openAI gym

In this notebook we explore how to train an agent to play the "CartPole"-game, i.e. they are given a cart with a pole attached to it and it is their task to balance the pole for as long as possible. The code is largely inspired by [this](https://github.com/keon/deep-q-learning) repository. The accompanying [blogpost](https://keon.io/deep-q-learning/) explains some of the mathematical background.

We build a *Deep Q Learning agent*, i.e. our agent will be a deep neural network. It is constructed with keras. For the training environment, we use openAI's [gym](https://github.com/openai/gym) library. openAI also has a good introduction to gym that can be found [here](https://gym.openai.com/docs/).

To try out the model yourself just run
```
git clone  https://github.com/stefan-stein/deep_q_learning.git
```

and open up the jupyter notebook.

The included video shows a the 24th training episode. This is already reasonably stable for the most part, although the agent will still sometimes drift off to the side.

`dqn.h5` is the trained model after 40 episodes.
