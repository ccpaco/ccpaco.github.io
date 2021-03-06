---
layout: post
title: Working with OpenAI Dall-E Part 1 
---

As listed on the Github repo's README.md file, 


"This is the official PyTorch package for the discrete VAE used for DALL·E. 
The transformer used to generate the images from the text is not part of this code release."


First things first, let's fork the repo from [the OpenAI github repo](https://github.com/openai/DALL-E)


I just downloaded the code, opened the zip in the same folder area as my other Python notebooks, and typed in 


`pip install DALL-E`


As per README file on the github repo. Since I'm on a Mac (using iterm2) I then type


`cd DALL-E-master`


![iTerm2 output success](../images/Screen Shot 2021-04-09 at 10.55.22 AM.png)


To get into the DALL-E folder on my Mac. Then 


`jupyter notebook`


to get our DALL-E clone up and running. Quite simple so far. Output shown below.


![Jupyter running in browser](../images/Screen Shot 2021-04-09 at 10.55.45 AM.png)


Then we navigate to the usage.ipynb notebook and see the following code output.


![usage notebook output](../images/Screen Shot 2021-04-09 at 10.56.15 AM.png)


But surprise! We get an error. _lzma module is missing!


![LZMA module missing? ](../images/Screen Shot 2021-04-09 at 12.09.43 PM.png)


And...missing module error strikes again. Installing it in the terminal in our folder area should help.


`brew install liblzma-dev`


`brew install xz` or `brew reinstall xz` to update. 



Good Afternoon from the Pacific


Chris
