# -*- coding: utf-8 -*-

Created on Tue Dec 10 22:59:29 2013

@author: Julian


I want to create a learning chatbot!
The name stands for 'Learning Python Chatter'
Why start with easy projects if you can also do hard ones ;)!

The goal: I will ask a question, LePyC will not be able to answer or even understand this question.
Subsequently, LePyC will ask questions back in order to learn how to answer the original question.
I will answer every question until everything is clear to LePyC.
If a ask the original question again, I will get a satisfying answer. 


My thoughts on which steps are needed to accomplish this:
    1. Teach LePyC the english language (could be any language of course, but first keep it simple)
    2. Create algorithms that analyze the user's input (action);
    by this, I mean that LePyC splits the input string
    into the different words/numbers/symbols/etc
    3. These are somehow sorted into combinations (i.e. adjective + noun, subject + verb, imperative verbs, past tense)
    4. Difficult part: interpretate the action:
        * Must LePyC deliver information or take information?
        * Deliver / Take information
        * If deliver: Does LePyC already possess this information?
        * 

    5. Everything (actions + reactions) is saved in a logfile and in a database.


*The difference between them is, that the logfile is a list of all actions and reactions ever made,
listed chronologically,and that the database saves and assigns words/numbers/symbols/expression to 
different categories, sub-categories etc.
The database can be seen as a huge crosslinked Dictionary. My vision is, that the dictionary does not have a fixed structure
but is able to dynamically expand, add new (sub- or super-) categories etc.
The logfile is therefore LePyC's memory and the Dictionary is its intelligence.
