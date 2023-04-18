---
layout: post
title: Assignment 2-Working with a Corpus

# theme: simple
transition: convex
tags: [presentation]
category: blog
---
# Working with a corpus

## Guideline of the assignment
The Corpus Assignment, otherwise known as Assignment 2, will be completed in one step. It builds on work we did in the textual portion of the class, particularly with Voyant Tools and R Markdown files in Posit Cloud. This assignment can be done alone or in pairs.

## Pick a corpus. 
I decided to pick the corpus of [writings of Sir Arthur Conan Doyle]. I'm especially interested in his work "the Adventure of Sherlock Holmes". I saw that there are different version of the release of this book, so I was wondering if I could do a textual analysis of the different issues and compare them. 

## Introduction to Arthur Conan Doyle, and his fictional characteer Sherlock Holmes
Conan Doyle had a multifaceted career as a writer, journalist, and public figure, despite being most renowned as the creator of Sherlock Holmes. He was born in 1859 in Edinburgh and received a medical degree from Edinburgh University in 1881. He worked as a surgeon on a whaling ship and a medical officer on a steamer before settling in Portsmouth, where he split his time between writing and medicine.
Sherlock Holmes first appeared in "A Study of Scarlet" in 1887, which was successful enough to motivate Conan Doyle to write more stories. However, he killed off Holmes in 1893 to focus on more serious writing, causing a public uproar that led him to bring the detective back to life. Conan Doyle also authored other novels, such as "The Lost World," and non-fiction works, including a pamphlet justifying Britain's involvement in the Boer War, for which he received a knighthood. He also wrote histories of World War One, in which his family members perished, and ran unsuccessfully for parliament twice. In his later years, he became deeply interested in spiritualism before passing away from a heart attack on July 7, 1930.

## Choice of tools and focus and analysis
You can also break the corpus down into subcorpuses that focuses mainly on SHerlock Holmes. I found text files of The Adventure of Sherlock Holmes issued in 1892, 1893, 1908, 1910 and 1911. I wanted to find out if there are seeming differences in the frequency of texts and phrases. Suppose there aren't much changes done, then the frequency of each word should be very similar between different versions of issues. 

I used Voyant tools to analyze and compare the 5 subcorpus. Here's a screenshot of the overview of the analysis. 
![General](/images/general.png "General")


## The wordcloud
I first looked at the word cloud. The word that shows as the most frequent is "holmes" and "mr", following which is a bunch of verbs like "said", "think", "know" and stuff like that. 
![wordcloud](/images/wordcloud.png "wordcloud")

## Frequencies comparison
I then looked at the differences of frequency of the most frquent words in each issue. It turns out that each word has different frequencies in different version. This might be casued from multiple reasons.
1. the times that a word is used is indeed different from differnt issues.
2. the length of each version is different(considering acknowledge page, copyright and something like that), thus the denominator changes rather than the numerator.
![Relative frequencies](/images/relative frequencies.png "Relative frequencies")

