# thesis
[![Open in gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ryancahildebrandt/thesis)
[![This project contains 0% LLM-generated content](https://brainmade.org/88x31-dark.png)](https://brainmade.org/)

Scripts from my graduate thesis looking at emotion word processing. I'll pop the abstract down below, but feel free to reach out if you'd like the full paper or presentation posters! (update: it's [here!](https://scholarworks.rit.edu/theses/10346/))

## Abstract

Current literature suggests emotion-label words (e.g., sad) and emotion-laden words (e.g., funeral) are processed differently. The central focus of the present study was to investigate how valence and emotion word type influence how words are processed. A satiation paradigm was used to characterize the relationship between the processing of emotion-label and emotion-laden words of positive and negative valence. It was hypothesized that, in addition to the standard slowed response times to satiated words, emotion-label words would exhibit greater satiation and priming effects than emotion-laden words. Analyses indicated expected priming and satiation effects across a range of other stimulus characteristics. Neutral words, which were included as a comparison stimulus type for both valence and word type variables, were shown to elicit much slower reaction times than either emotion word type. The results of the present study indicate the importance of valence in word processing, even when other word characteristics and experimental variables are at play. Current models of word processing do not sufficiently account for emotional characteristics of words, and implications for word processing models are discussed.

*Keywords: word processing, emotion words, satiation, priming, attention, emotion-laden words*

## Code & Analyses

[**Here**](http://htmlpreview.github.io/?https://github.com/ryancahildebrandt/thesis/blob/master/Thesis-Code-Github.html) is the knit output of [**this**](/Thesis-Code-Github.Rmd) R code, containing most data processing, analyses, and graphics for the study. 

## Outputs

### The main repeated measures ANOVAs are included here:

- [Excluding neutral & mood state](http://htmlpreview.github.io/?https://github.com/ryancahildebrandt/thesis/blob/master/rm.noneu.nomood.html)

- [Excluding neutral, including mood state](http://htmlpreview.github.io/?https://github.com/ryancahildebrandt/thesis/blob/master//rm.noneu.mood.html)

- [Including neutral, excluding mood state](http://htmlpreview.github.io/?https://github.com/ryancahildebrandt/thesis/blob/master//rm.neu.nomood.html)

- [Including neutral & mood state](http://htmlpreview.github.io/?https://github.com/ryancahildebrandt/thesis/blob/master//rm.neu.mood.html)

### And some plots showing the main findings of interest:

![Mean Reaction Time by Primed/Satiated](/Thesis-Code-Github_files/figure-html/Graphics-3.png)

![Mean Reaction Time by Word Type](/Thesis-Code-Github_files/figure-html/Graphics-8.png)

![Mean Reaction Time by Word Type & Primed/Satiated](/Thesis-Code-Github_files/figure-html/Graphics-9.png)

![Mean Reaction Time by Word Type, Primed/Satiated, and Valence](/Thesis-Code-Github_files/figure-html/Graphics-10.png)

## Summary of Findings

- **Slower** RT’s for **negative** targets may be a result of negative words’ increased **attention capture**, impairing disengagement from the target in order to complete subsequent task
- Conversely, the **lack of observed satiation** for **negative emotion-label** targets may relate to the **salience** of negative stimuli, making their meanings **more difficult to satiate** in the first place
- While **neutral** targets also elicited slower RT’s, this may instead be due to the **ambiguity** inherent in categorizing their valence, as they are not immediately recognized as positive or negatively valenced
- Compared to tasks commonly used in the semantic satiation literature, the task in the current study resulted in **lower accuracy** rates, potentially indicating that the present task was **exceptionally difficult**. This may have obscured expected effects from the IVs
