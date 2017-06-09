[I'm an inline-style link](https://www.google.com)

## Analysis 
Make an "autopilot" script for your analyses, so that figures (and even posters if you are feeling ambitious) are updated in real time while the data is collected. You can find some examples here (github/pbeukema/rsaRemap/autopilot.py). Whenever data is written to a particular folder, a cron job executes an autopilot.py script that updated imaging and behavioral analyses and then sends me an email at the end of the day with figures. By not intervening, and having your analyses pre-determined, you will save significant time. 

Use jupyter notebook for development and for analysis pipelines.
http://jupyter.readthedocs.io/en/latest/index.html

A very useful text editor that integrates seamlessly with github. 
https://atom.io/
Use it for writing experimental code, scanner code, bash scripts and so on. 
(Hint: Run scripts from atom with package "script")

Make a startup file for jupyter notebooks that preloads modules like numpy and scipy to save you time and also so that your figures always are publication quality, from the get go, without modification. The config file can specify font sizes, legends, color themes etc. Save your figures in svg, or eps. pngs do not scale and are impossible to modify if needed.

##  Programming 
Start using github. It is excellent for version control (instead of having a final_analysisv4p3_really_this_is_final_final.py in your folder you just have analysis.py) and for sharing. Other researchers can replicate exactly what you did. This will save you time, if someone emails you for example. 

Simulate data and make sure that your analysis works the way you think that it is working. 

Become a pro at bash syntax - it will seriously save you a lot of time. 
https://ss64.com/bash/syntax-keyboard.html

Use shell scripts when you must, but these days python is quite the shapeshifter. 

Hotkey things, get a mechanical keyboard so your labmates love you. Hotkey more things. 

##  Generating pub quality figures:
Data visualization has been made very easy with matplotlib and a library called seaborn http://seaborn.pydata.org/index.html

##  Doing statistics
Learn to love Bayes, if you don't already. 
This is an introduction on bayesian vs. frequentism
http://jakevdp.github.io/blog/2014/03/11/frequentism-and-bayesianism-a-practical-intro/

Beware of p-values. Stop using them if you can. Avoid null hypothesis significance testing (NHST). Read this paper for some of the problems with p-values if you are not familiar with the controversy.
http://ejwagenmakers.com/2007/pValueProblems.pdf

As soon as possible, understand bootstraping, cross validation and the permutation test. 
https://docs.google.com/presentation/d/11TozBxAaON1eFXeL6aK1USLtJyAbUaHhskcPkI0FLbc/edit#slide=id.g138cbbed1a_0_0 

##  Statistics blogs
While my MCMC gently samples:
http://twiecki.github.io/

Pythonic perambulations
http://jakevdp.github.io/


##  Twitter is your friend:
@KordingLab
@StatModeling
@Neuro_Skeptic 
@tdverstynen (el patron)
@NKriegeskorte
@jakevdp

##  Conducting research
Before you start down some major project that you will be committed to for years, understand the current literature in your topic. Understand very clearly why you are going to do what you are going to do. 

Find articles before they are officially published on arxiv
http://biorxiv.org/

Don't discount social media, like twitter!

Pubmed

Google-scholar

PaperPile (and its integration with Pubmed)


##  Writing papers
See these 10 rules for writing papers, grants etc. 
http://biorxiv.org/content/biorxiv/early/2016/11/28/088278.full.pdf

##  Meetings with your PI
Never show up empty handed to meetings with your PI.
Have a clear objective to the meeting.
Be able to show some evidence of your productivity. 

The rainy day folder. You will have some weeks where nothing worked and you will have to meet with your PI anyway without the thing you were supposed to have. I found that in those cases it is very useful to have a "rainy day" folder containing interesting analyses/figures your advisor has not yet seen. 


##  Doing statistics better
Rob Kass, CMU statistics faculty, has written guidelines on how to approach data analysis. They are extremely useful. 
http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004961

##  Share your work with your friends as well as your enemies. 
The latter might give you even better criticism.



