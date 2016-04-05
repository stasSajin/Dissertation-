## LANGUAGE-VISION INTERACTIONS IN THE VISUAL WORLD PARADIGM: EXAMINING THE EFFECTS OF DISPLAY AND WORKING MEMORY ##


**Objective**: the following report aims to provide a very high level overview for all five experiments in the dissertation. I'll generally try to do the following for each experiment:

	*Summarize the objective
	*Provide a brief description of the procedure
	*Cover briefly the results, mainly though visualizations
	*Summarize the novel contributions and knowledge
Note that more detailed info can be found in the dissertation document. The report presented below is very sparse in detail, but it provides a quick and dirty look at what each experiment examines. 

----------

# Experiment 1 #
#### Objective ####
Experiment 1 aims to test if phonological competition effects can be observed during the preview period in the VWP, when participants don't have to engage in auditory processing. In other words, if I give you the display with four words (see below) and I let you process it for about 1.9s (which is enough time to read all the words), will you start looking at the two words that are similar because they have some phonological/orthographic overlap? Or will you look at all four words with equal likelihood and only when the auditory signal is presented, your looks will start to converge to the target and competitor? 

![Word Display](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/pngs/ItemDisplay.PNG)

In the display above participants are presented with the Target=Bank, Competitor=band, Distractor=mist; Distractor=salt

If we find that participants look at target and competitor more, then this would be problematic for the linking hypothesis theory, since it posits that processing during visual preview plays no role in how fixations are being mapped. On the other hand, if we find each words gets about the same number of fixations over time, then we can conclude that spoken word processing drives competition effects in the VWP. 

#### Procedure ####
Experimental procedure was very simple. Participants were seated in front of a display. They wore headphones and their eye-movements were recorded. At the start of a trial, they were presented with a fixation cross at the center of the screen for about 1s. After that, the display switched to a display of four words and they were told to start looking immediately at the words on the screen. About 1.9s later they heard, the spoken target which referred to one of the words on the screen (e.g., "Click on bank"). Once they heard the spoken target, they had to use the mouse and select it. See the figure below for trial structure.

![Exp1Proc](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/pngs/Exp1Procedure.PNG)


#### Results ####
Participants had to make responses for three types of trials. The focus will be mainly on Experimental trials.

The graph below shows the fixation proportions for all trial types (again, focus only on the Experimental trials).

![Exp1Results](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/GCA/Exp1/plot3Experiment1.png)

Experimental trials essentially show that nothing is happening during the preview period. Once participants hear the auditory target, they start looking at the target and the matching competitor more than they look at the two distractors. 


#### Novel Contribution and Knowledge ####
The results of this experiment provide some good news for the linking hypothesis. The results show that during the 1.9s preview, even if participants read the words extract orthographic and phonological codes from those words, they don't use that information to look more at the target and the competitor. Note also that in this experiment, the competitor and the target diverge from the distractors at about 200ms mark. This will prove important later, when I examine how fast the divergence occurs in Experiment 2.  



----------

# Experiment 2 #
#### Objective ####
Experiment 1 showed phonological competition effects that are regularly observed in other VWP studies. Nonetheless, an examination of visual search literature  points out that distractors that are similar to the search template disrupt the speed of visual search. In other words, you get interference from distractors in visual search.

 The visual search task and VWP are uncannily similar paradigms, except that VWP involves looking at data in the form of fixation proportions that are examined over time. 

In Experiment 2, I predicted that if we plot fixation proportions over time using a visual search version of the task in Experiment 1, then we will observe the same exact competition effects that are reported in Experiment 1. 

#### Procedure ####
Procedure was very similar to that in Experiment 1, except that in this experiment participants were presented with the auditory target first, and then they had to search it in the display of four words. See figure below for trial structure.

![Exp2Procedure](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/pngs/Exp2Procedure.PNG)


#### Results ####
As you can see in the figure below, there is a clear competition effect, even though the speech is not presented concomitantly with the display.

![Exp2Results](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/GCA/Exp2/plot1Experiment2.png)

In the plot below, I have the divergence analyses from cluster-based permutation tests. The highlighted region in the left panel shows the timebins (25ms) where the there is a significant difference between the competitor and average distractor curve. You can see that fixations start to diverge around 300ms mark. The right panel shows how significant is the t-sum associated with the time-cluster based on 10000 permutation tests.   


![Divergence Exp 2](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/Divergence%20Analyses/Experiment2/CompvsDistractorExp1.png)

#### Novel Contribution and Knowledge ####
I'm not the one in favor of using Trumpisms, but the results of this experiments are HYUUUUGE. First, this experiment shows that we can use fixation proportion analyses, which tend to be more sensitive measures of processing compared to dwell times or first fixations, in typical visual search tasks. Researchers doing visual work should be made aware about the beauty of fixation curves! Second, these results bring into question that the typical proportion measures are a sign of continuous measures of processing or a sign of continuous lexical competition.  

These results and the similarity between the VWP and visual search led me to believe that competition effects could be an artifact for how we collapse proportions over time. This would have important implication for how we interpret VWP data. I propose that fixations are not necessarily a continuous measure of processing but rather measure the strength of attention capture on the part of the visual stimulus. 

This experiment also indicates that the VWP could be adapted to study semantic priming, memory recognition, and categorization learning. For instance, one could use fixation proportions to examine more covert forms of learning or memorization, without relying on participants making an overt response (i.e., button push) to a stimulus. 

This experiment also shows that the competitor effect emerges around the 300ms mark (if we measure time from display onset). In Experiment 1, the divergence between competitor and distractors comes around 100ms. Nonetheless, in Experiment 1 fixations are measured from stimulus onset, when the participants are already fixating on one of the words in the display. In Experiment 2, participants' fixations start at the center of the screen, so we need to account for an extra saccade in order to compare divergences between the two experiments. If we account for a 200ms period to initiate a saccade to a word, it means that in reality the divergence for Experiment 2 occurs at about 100ms mark. Both experiments thus show divergences that occur at the same point, which suggests that participants in Experiment 1 do not store in working memory the visual representations of the targets, and instead engage in memory-less visual search when the auditory input is presented.  
 
----------
# Experiment 3 #
#### Objective ####
Experiment 2 shows that we can observe competition effect simply by storing a linguistic representation of the target in working memory. This experiment aims to see if it is possible to interfere with the storing of linguistic knowledge in working memory.

#### Procedure ####
This experiment is similar to Experiment 2, except that I asked participants to solve a math problem when they process the auditory input. Essentially, the auditory target and the math problem is presented at the same time. They have to solve the problem and store the solution in working memory. Later they need to find the target among the words in the display, followed by a question quizzing them on whether the answer provided on the screen is the correct solution to the math problem they saw previously. See procedure in figure below:

![Exp3 Procedure](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/pngs/Exp3Procedure.PNG)

#### Results ####
You can find the results of this Experiment below. The results essentially indicate that the competitor effect becomes much smaller relative to what was observed in Experiment 2 (note that triangles and squares for Experimental trials overlap in confidence intervals).

![Experiment 3 results](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/GCA/Exp3/plot1Experiment2.png)

#### Novel Contribution and Knowledge ####
This experiment indicates that competition effect is lessened under a cognitive load condition. There are couple of reasons why the effect goes away. First, it is possible that increased cognitive load affects the storage of the linguistic representation in working memory. A second explanation is that cognitive load doesn't affect with how the target representation is stored in working memory, but rather affects cognitive inhibition. In other words, cognitive load affects the ability to disengage fast from distractors and more on to find the correct target. 



----------
# Experiment 4 #
#### Objective ####
Experiment 4 will investigate how a non-linguistic representation stored in working memory (i.e., color features) affects the mapping between representations activated from processing the speech signal and possible targets on the screen. Essentially, we expect to observe that color disrupts will disrupt the mapping processes happening in the VWP. If disruption occurs, then this will bring into question just how automatic is the mapping in the VWP. 

#### Procedure ####
In this experiment, participants are first presented with a small color patch at the center of the screen (colors could be red, green, blue, or yellow). They are asked to remember the color of the patch. After that the color patch goes away and the display with the four words appears. 200ms later, the spoken target is presented. Participants have to press the button yes if the target they hear is in the same color as the color of the patch or no if it is in a different color. You can see below that in some trials the target was in the same color as the patch (congruous), in some trials the competitor shared the same color as the patch (incongruous competitor) and in some cases one of the distractors had the same color as the patch (incongruous distractors). 

![Exp4 Procedure](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/pngs/Exp4Procedure.PNG)

#### Results ####
For these results, focus on Experimental trials. You can notice that when the target shared the color with the color patch, there was no competition effect. When the competitor shared the color (left-middle panel), the effect of competition was very large. Similar patter was observed for incongruous distractors trials. 

![](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/GCA/Exp4/plot2Experiment4.png)

#### Novel Contribution and Knowledge ####
Essentially, these results suggest that participants adopt a serial search strategy, where their initial fixations are driven primarily by the color feature, and lexical information is used as a way to confirm if the current target they are fixated on is the correct one or if they should move to the next target. 

This experiment also shows that the mapping of eye-movements in the VWP is not entirely an automatic process. Participants have a choice in terms of which information to use in order to find the target. 


----------
# Experiment 5 #
#### Objective ####
The objective in this experiment was to examine how display size affects the competition effect. Based on a brief conference report by Sorensen & Bailey (2005) and on visual search literature indicating that we have very poor visual working memory, I expected to see a delay in where the competition effect emerges for displays with larger set sizes.

#### Procedure ####
There were two groups of participants. One group was presented with displays having 4 words in them. The second group had displays with 6 words in them. 

You can see the procedure in the figure below:
![Exp5 Procedure](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/pngs/Exp5Procedure.PNG)

#### Results ####
There was no difference between the two groups in terms of where the competitor effect started to emerge. You can see the fixation curves for the two groups below. 

**Group1 (6 words):**

![Group1](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/GCA/Exp5/Group1/plot1Experiment5G1.png)

**Group2 (4 words):**

![Group2](https://raw.githubusercontent.com/stasSajin/Dissertation-/master/GCA/Exp5/Group2/plot1Experiment5G2.png)

#### Novel Contribution and Knowledge ####
The results were fairly surprising, since I expected search times to decrease with larger set sizes. One limitation might have been that the preview was too long (about 2.9s). Future experiments should either decrease the set sizes or limit the preview times.  