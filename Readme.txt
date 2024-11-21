






An LLM programmer has asked me, if I know or can design an LLM GoF metric. 

As far I know, there is no GoF-metric for LLMs, that has been applied longer than 1 year. And there are many reasons why I think there still will not be in the near future.

However, I have noticed, that generative adversial networks (GANs) made the big step in image recognition and image generation. Especially, there has not been a new GoF metric for GANs, either. Instead the generator network and the recognition network have been plug into a game, where one network trys to overcome the other, but has to return heat map of its decision to the counterpart. 

So, I am returning the following very early adversial approach for mutual cross validation of two LLMs:

1. The first LLM is presented a certain question and is asked to return a very detailed answer.

2. The answer is presented to a second LLM based another learning algorithm. The second LLM is asked to condense the answer to 10 sentences and to order the sentences by their chracteristic strength regarding the answer.
strength. 

3. The first LLM is requested a revers lookup of the original article. The condensed sentences are presented iteratively to re-identify the original question/ thing.



A manual proof-of-concept reverse lookup has been performed one the AI Phind for twelve things. It has been necessary to tell phind, that the topic of a Wikipedia article of a searched thing is requested. Otherwise Phind did not understand the term "reverse lookup". (The author did not have a developer/ inference access one Phind. Maybe reverse lookups are blocked by default.) 
The performed 12 reverse lookup trials are presented.


Till yet, the concept is just an idea.