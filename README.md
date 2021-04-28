# hyponym_based_skill_clustering
An approach of finding Hyponyms and Hypernyms of a given proper noun using NLP.

One of the biggest problems out there in industry, is that there is no automated way of mapping a given skill to other skills in a sample space. we need to manually map each skill and find whether it is a parent to another skill, child of another skill or none.
for example. Lets take these 4 skills Python, Web development, Django, Business Developement.
we can clearly say that Business Developement is not at all related to the other three skills, while python and django can be part of web development, and django is built of python. however a person unfamiliar with above terminologies, would have to first do their research in order to conclude with the relations. This can be easily done for lesser number of skills, but there are more than millions of skills out there and mapping them manually would be a very tedious task.

In this project, i have tried to incorporate the concepts of hyponyms and hypernyms, building rule based NLTK grammar regex for extracting hyponyms from any given sentence. Any technical article/pdf/blog containing the information of a set of skills can be supplied as an input data, and output data can either be dataset marked with hyponyms and hypernyms mapped with given sentence or the skill hierarchy tree itself. the former can be used to train, deep learning models which is currently work in progress. 
