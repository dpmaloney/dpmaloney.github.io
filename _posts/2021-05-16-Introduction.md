---
layout: post
title: Introducing the DanAnalytics Blog
---

Hello everyone! My name is Daniel, and this is the start of my journey down the soccer analytics rabbit hole. To get started, I'd love to start with a basic introduction to the research I have done in the past, along with where this blog will be going.

### Why Soccer?

Although I am a fan of many sports, soccer is the most interesting because of two reasons, 1. the lack of serious analytical developments in the sport, and 2. the lack of good analysis surrounding the core of what happens in the game. Because of these two factors, soccer is the perfect field for spatial and machine learning analysis to try to parse why good players are good, and why the best players are the best.

To do this, there are a number of good frameworks, but VAEP, and xT are two of the most intriguing because of their basis in serious probability theory and their approach to the game that doesn't rely solely on valuing scoring-related actions.

### What is VAEP?

To paraphrase the original paper from which this framework comes, which can be found [here](https://www.ijcai.org/proceedings/2020/648), we can assume that any player's actions are either trying to increase their teams scoring chances, or decrease the other teams scoring chances. With this as our baseline assumption, we can estimate the probability that an action leads to scoring and use that to create a more accurate understanding of what good passes are good, and why bad passes are bad.

### What does VAEP look like in practice?

For this, we can look at some real world examples from games that Leo Messi has played in the last 15ish seasons. First, we can look at the highest valued action by my VAEP model from these games which is illustrated below:

![Vaep1](/assets/Vaep.png)

From this we can see that the dribble, which was right in-front of an open goal is most valuable for this, as well as Neymar's contribution to the goal being highly valued. While this is obvious to anyone watching the game, building an analytical framework for valuing these actions is extremely valuable for beginning to understand actions that don't directly create goals, or prevent them.

That's all for the introduction to my blog, please look out for more posts in the future!
