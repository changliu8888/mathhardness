# mathhardness
Exploring hardness of math problems (AMC10, AMC 12 and Math Olympiad). This repo contains both documents and codes.

Can someone quantify the hardness of competition math problems/questions?  One idea is to use known AMC competition questions and Math Olympiad questions, with known level of difficulty/hardness lable.  

The fundamental challenge is to do personalized STEM education.  The technical challenge is to evaluate student and then evaluate the teaching material.  If a good way to match exist, then on paper a student can self learn with machine generated contents.  However, evaluating the "hardness" is challenging.  If this can be done, education would be different.  Schools would become unnecessary, as teachers are basically curators of teaching materials.

# dataset with lable

The AMC 12 past problems https://artofproblemsolving.com/wiki/index.php/AMC_12_Problems_and_Solutions? 
Generally speaking the first 10 problems are considered easy.  Problems 10-20 are mid.  Problems 21-25 are harder.  However there are exceptions and the hardness is also dependant on individuals.  Some may find a "hard" problem easy.  Some may find a "easy" problem hard.  Nonetheless, the general positinos are correct on average.

Problems after 2012 are harder than ones before.

Olympics problems arranged by hardness rating is here. https://9f5ed0d0-7e72-472f-ade8-1021e63aa3e1.usrfiles.com/ugd/9f5ed0_e0fea50ba36c497081d745158ae2af5d.pdf 
The creator of this hardness level later commented on this method. https://blog.evanchen.cc/mohs/ 
Here is the pdf file for defining the hardness https://web.evanchen.cc/upload/MOHS-hardness.pdf 

# the AI pipeline proposal
The proposed AI pipeline is as follows.
1. Using LLM or image-to-text translation, turn problems into a dataset with label.
2. Unify hardness level according to test types.  For example, a "easy" plympiad level question would be considered very hard by AMC12 test takers.
3. Build a CNN/deep learning model to learn the hardness level.
4. Build a colab interface to allow someone to input a test problem and output degree of difficulty estimate.
5. Provide validation of estimates.
