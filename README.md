# retail-clothing-recommender

In this project I am attempting to create a recommender system that will feed a user images of clothing, offer the ability to like or dislike, and then indicate new images of retail clothings based on learning the preferences indicated by the individual and returning clothing with similar characteristics, or more accurately, similar locations in vector-space, to those items the user preferred.  As a user increasingly indicates preferences, the algorithm might learn whether the user is say expressing a range of area in vector-space, or more like two/three small clusters in vector space, and will continue to supply new suggestions accordingly.  The system would be expected to notice fairly quickly that a user is only interested in black or dark clothing for instance; similarly the user might show preference for garish patterns, or particular types of patterns; a user might like paisley, but not floral print.  A user might like a certain cut of shirt, might like pockets versus not, etc etc.

Given the diversity of features in play, and the complexity of image analysis, a neural network does seem the most appropriate.

Currently I am searching for satisfactory databases to train on, preferably at least several thousand retail-style, front-on images of short or long sleeved collared shirts, for now.  I think limiting to one style of clothing to begin with will be more manageable.

The goal in a sense is to establish a sort of web of meaning for clothing analogous to what is achieved lexically with Words2Vec, something that exists independent of 'customers who bought this also bought this...'   I understand it's difficult to recreate the natural context variables available in text.  If there's time, I'd be interested in exploring a rudimentary Flask implementation to try and make the process visualizable.



