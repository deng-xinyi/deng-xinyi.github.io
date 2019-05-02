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
<img align="right" src="/images/sfn16.png" width="30%"> A continuing theme from the end of my graduate research into my postdoctoral work is the development of clusterless decoding methods, which extract information from spiking data that have traditionally been discarded during a preprocessing step called spike sorting, because their spike waveforms recorded extracellularly, for instrumental and physiological reasons, are challenging to cluster into putative single neurons.

State-space methods for monitoring and improving cognitive flexibility
------
Deficits in cognitive flexibility have been linked to autism, obsessive-compulsive disorders and schizophrenia. Investigations of these deficits have led to new multi-faceted experimental design and have generated behavioral data with growing complexity. In addition, technological advances now allow for recording of large quantities of information from the brain at multiple spatial and temporal scales, includes multi-channel electrode arrays, EEG, MEG and fMRI. Access to this type of high-dimensional data, both behavioral and neural, has also presented a challenge for statistical data analysis and modeling: What is an adequate representation of the relation between features of the behavioral task and structures in the neural activity?

A statistically-principled approach to optimizing placement of deep brain stimulation electrode
------
<img align="right" src="/images/sfn14.png" width="30%"> Deep brain stimulation (DBS) is a highly promising therapy for Parkinson's disease. Yet most patients do not get full therapeutic benefit from DBS due to its critical dependence on electrode location in the sub-thalamic nucleus (STN) for therapeutic efficacy. Previously, many methods have been proposed and used to study rhythmic dynamics in continuous-valued recordings such as EEG and LFP, but methods suitable for the discrete, single unit spiking activity that are typically recorded from STN neurons in Parkinson's disease patients are needed to address a number of critical statistical challenges.


Neuroscience
======

Event-to-event variability in structural organization of internally generated hippocampal sequences
------
<img align="right" src="/images/cosyne19.png" width="30%"> The ability to flexibly remember experiences at different levels of specificity is crucial to how we learn and howwe make decisions.  However, the underlying mechanisms involved in flexibly storing and retrieving memories invarying degrees of detail remain elusive. Current theories suggest that memories of past experiences are storedwhen specific patterns of neural activity cause changes in the connections among neurons, and they are retrievedwhen these patterns are reinstated. For example, when an animal moves through its environment, spiking activity of hippocampal place cells is paced by an underlying "clock" with a constant rate at theta frequency.  When theanimal slows down or pauses, place cell population is sequentially reactivated during sharp wave-ripples (SWRs),which often represents a replay of past trajectory on a compressed time scale.  Is the hippocampal clock alsoconstant during the SWR state?
