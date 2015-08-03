# cloudbrain
A realtime evolving spheroid wordcloud

# Description

A spheroid wordcloud that can be fed feeds of data (RSS streams or content sources that regularly produce new articles) that grows and shrinks in real time. 

Interval to poll for new content can be configured, as well as the thresholds for the evaporation time of a word and the word size ratio. For example, a tick of 5 minutes would mean the size of the word gets reduced to 0 down from X if the word was not seen again within the last 5 minute window.

The most used words will survive the longest naturally, as a result of this behavior. Every time the word is seen, it grows in size according to the growth ratio/factor variable.

# Purpose

Useful to notice trends in world events from news sources, changes in patterns from mainstream media, viral content, and economic engines like Bitcoin. 

# Other ideas

Strengthened words can be linked to form syntactically accurate sentences similar to a neural network. Words may be able to link to other words in some fashion to notice association trends. 
