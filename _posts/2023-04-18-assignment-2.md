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
#### Arthur Conan Doyle
Conan Doyle had a multifaceted career as a writer, journalist, and public figure, despite being most renowned as the creator of Sherlock Holmes. He was born in 1859 in Edinburgh and received a medical degree from Edinburgh University in 1881. He worked as a surgeon on a whaling ship and a medical officer on a steamer before settling in Portsmouth, where he split his time between writing and medicine.
Sherlock Holmes first appeared in "A Study of Scarlet" in 1887, which was successful enough to motivate Conan Doyle to write more stories. However, he killed off Holmes in 1893 to focus on more serious writing, causing a public uproar that led him to bring the detective back to life. Conan Doyle also authored other novels, such as "The Lost World," and non-fiction works, including a pamphlet justifying Britain's involvement in the Boer War, for which he received a knighthood. He also wrote histories of World War One, in which his family members perished, and ran unsuccessfully for parliament twice. In his later years, he became deeply interested in spiritualism before passing away from a heart attack on July 7, 1930.
#### Sherlock Holmes
Sherlock Holmes is a fictional character written by Arthur Conan Doyle in the late 1800s. He is widely recognized for his exceptional intellect, remarkable attention to detail, and uncanny ability to solve complicated cases that have left others stumped.
I would say he is a unique character whose analytical mind, outstanding observation skills, and almost supernatural aptitude for solving the toughest cases set him apart. He is frequently described as aloof and peculiar, employing a cold and logical approach to his work. In addition to being a brilliant detective, Holmes is also an accomplished fighter and marksman.
 Holmes is joined by his devoted friend and colleague Dr. John Watson, who chronicles his adventures and often provides a sounding board for his thoughts. Together, they tackle numerous cases that have become iconic in the detective genre, and (I believe) Sherlock developed a friendship with Watson.

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
![frequencies](/images/frequencies.png "frequencies")

## Linking back to the readings
In Taylor Arnold's "Distant Viewing: Analyzing Large Visual Corpora," distant viewing is defined as a framework for studying large collections of visual material that emphasizes the interpretive nature of extracting semantic metadata from images. By making a word cloud for The Adventures of Sherlock Holmes, we can apply distant viewing to gain a rough understanding of the book's contents at a glance.

For example, the word cloud may reveal that the most frequently used words in the book are "Mr. Sherlock Holmes" and "Watson," indicating that these are the main characters in the story. The size of these words in the word cloud would be larger than other less frequently used words, making them stand out and providing a visual representation of the importance of these characters.

Additionally, the word cloud may also reveal other important clues to the plot of the book, such as "room," "house," and "case.", suggesting that Sherlock's behavior is tightly connected to living places. These insights can be gained without reading the book in its entirety, providing a distant view of its contents. 

Therefore, the use of a word cloud for The Adventures of Sherlock Holmes falls within the distant viewing framework and provides a valuable tool for gaining a rough understanding of the book's contents. By identifying the most frequently used words in the book, the word cloud allows people to view the function and themes of the book in a distant position, making it a useful tool for analyzing large collections of visual material or text.

However, I would like to argue that we cannot blindly trust data. Just like before I wrote this post, I went online and did research about the context, aka Conana Doyle and Sherlock Holmes, so that I can better understand and decypher and textual analysis. Reading and wordcloud without having a context can be misleading, since data don't speak for themselves, yet our perception and be deceptive. 

The article "The Numbers Don’t Speak for Themselves" by Catherine D'Ignazio and Lauren F. Klein highlights the importance of conducting research and understanding the context in which data is collected in order to conduct accurate and unbiased data analysis. This is particularly relevant when conducting textual analysis, such as analyzing The Adventures of Sherlock Holmes.

While word clouds are a popular tool for textual analysis, they may not provide a complete understanding of the storyline. The authors of "Data Feminism" caution against solely relying on data analysis without considering the broader social and political structures that shape the data. Without conducting research and understanding the context of the text, the conclusions drawn from a word cloud analysis may be biased and inaccurate.

Therefore, when analyzing The Adventures of Sherlock Holmes, it is essential to conduct research to understand the social and historical context in which the story was written. Additionally, it is crucial to examine one's own assumptions and biases in order to conduct an unbiased analysis. By taking a critical and reflective approach, we can ensure that our analysis does not perpetuate harmful biases or reinforce oppressive structures, and that we gain a more nuanced and accurate understanding of the text beyond what a word cloud may suggest.
