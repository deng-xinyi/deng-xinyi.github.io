---
permalink: /research/
title: "Research"
author_profile: true
---

I remember the moment in 2014 when, as a graduate student in statistics who was working with rat hippocampal data but knew zero about the brain, I thought I discovered reverse replay. Having just finished the last line of MATLAB code for the clusterless decoder I was developing, I rushed to try it on an example sharp wave-ripple event to see what content it replayed. Puzzled by the paradoxicality of the decoded trajectory at first, suddenly I understood, "the rat was imagining itself running tail first!"

I also remember the moment when I learned I didn't "discover" reverse replay; [David Foster did](https://www.nature.com/articles/nature04587), eight years earlier. As I was reading that 4-page paper he and Matt Wilson co-authored, I was in awe of its Figure 3 that sprawled an entire page, so plainly yet so powerfully laying out 101 (yes, I counted) panels of raw spike rasters, and I was astounded by the absence of any fancy, complex analyses.

It was in that moment I realized that, in scientific discovery, advanced techniques and methods matter, but good data and intelligent observation matter more. Since then, I have started significantly broadening my survey of experimental literature, attending neuroscience seminars covering diverse topics, and making annual pilgrimage to SfN. 

Below outlines my motivated iteration between developing new statistical methodology and applying them to make interesting scientific observations.

Statistical Methodology: how phenomena observed by neuroscientists can be analyzed from a rigorous, statistical perspective?
======

Clusterless methods: decoding without spike sorting
------
A continuing theme from the end of my graduate research into my postdoctoral work is the development of clusterless decoding methods, which extract information from spiking data that have traditionally been discarded during a preprocessing step called spike sorting, because their spike waveforms recorded extracellularly, for instrumental and physiological reasons, are challenging to cluster into putative single neurons. I proposed a novel algorithm for adaptive decoding of spiking data that avoids the clustering problem of spike sorting entirely by defining a joint model for the spike waveform and receptive field structure and uses a state-space model to incorporate knowledge of the properties of the signal to decode. I later extended this algorithm to include a discrete, decision state, which can make experimental decision in real-time (for example, to stimulate the neurons or not) based on various sources of information present in population spiking data. An additional benefit of this clusterless algorithm by using previously-discarded spiking information is the high temporal decoding resolution (1 millisecond). 

State-space methods for monitoring and improving cognitive flexibility
------
Deficits in cognitive flexibility have been linked to autism, obsessive-compulsive disorders and schizophrenia. Investigations of these deficits have led to new multi-faceted experimental design and have generated behavioral data with growing complexity. In addition, technological advances now allow for recording of large quantities of information from the brain at multiple spatial and temporal scales, includes multi-channel electrode arrays, EEG, MEG and fMRI. Access to this type of high-dimensional data, both behavioral and neural, has also presented a challenge for statistical data analysis and modeling: What is an adequate representation of the relation between features of the behavioral task and structures in the neural activity? I developed a general state-space method to model and fit a low-dimensional cognitive state process that allows us to relate behavioral outcomes of various tasks to simultaneously recorded neural activity across multiple brain areas. I applied this model to data recorded by a team of neurosurgeons and engineers from Harvard Medical School and MIT in the lateral prefrontal cortex and caudate nucleus of non-human primates as they perform learning and adaptation in a rule-switching task. This state-space method allows my collaborators to identify and manipulate a low-dimensional correlate of cognitive influence in a content-specific way, altering neural activity related to certain cognitive features to modulate behavior. This is an important step towards treating mental diseases such as post-traumatic stress disorder and obsessive-compulsive disorders clinically.

A statistically-principled approach to optimizing placement of deep brain stimulation electrode
------
Deep brain stimulation (DBS) is a highly promising therapy for Parkinson's disease. Yet most patients do not get full therapeutic benefit from DBS due to its critical dependence on electrode location in the sub-thalamic nucleus (STN) for therapeutic efficacy. Previously, many methods have been proposed and used to study rhythmic dynamics in continuous-valued recordings such as EEG and LFP, but methods suitable for the discrete, single unit spiking activity that are typically recorded from STN neurons in Parkinson's disease patients are needed to address a number of critical statistical challenges. In my graduate work, under the mentorship of my doctoral advisor Dr. Uri Eden, I developed a statistically-principled inferential approach that describes neural rhythms by predicting the probability of a spike at any instant, given the recent past spiking history. This approach allows models to adapt in time to track changes in rhythmic spiking dynamics and can successfully characterized the neurophysiology of the stimulation location in a closed-loop system. This modeling and estimation framework enables the development of a new surgical tool---an automated intraoperative closed-loop DBS localization system---that will standardize DBS placement.


Neuroscience
======

Event-to-event variability in structural organization in internally generated hippocampal sequences
------


