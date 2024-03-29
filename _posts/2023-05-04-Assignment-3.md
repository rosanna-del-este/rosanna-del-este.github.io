---
layout: post
title: Assignment 3-Working with a Corpus of Images

# theme: simple
transition: convex
tags: [post]
category: blog
---
# Working with a corpus of images

## Step 1: Familiarize myself with an image corpus
I selected Wikiart image collection website. 

Wikiart is a "visual art encyclopedia", which provides searchable image database of images, paintings, photographies and other artworks. It also provides artist biographies of each artwork. In the database website, it includes sections like "Artwork by style", "Popular artworks", "Artist by art movement" and "Artwork by genre". Under each general category, there's also more detailed classifications of genre. 

## Step 2: Construct an image dataset of at least 30 images
I wanted to explore the collections of classic Chinese paintings in this database. As a result, I searched for "Shan Shui山水", which means "ink painting of the landscape of mountains and rivers", which is a style in classic Chinese painting. I collected several paintings of 5 artists. They have 30 images in total. Despite different styles(some more dim, others more colorful), they are different also in ways that some are pure landscape, while others have human figure within the frame. I'm curious to see how Orange is going to classify and organize the paintings. My assumption is that the outcome of the image categorization will be a mixture of "classification by artist" and "classification by different elements in the painting". 
![outcome5](/images/outcome5.png "outcome5")

I imported the 30 images to Orange, and built a dataset according to the instruction in video 14.
![outcome1](/images/outcome1.png "outcome1")

Here is the categorization by hierarchy and by mindmap: 
![outcome2](/images/outcome2.png "outcome2")

As is shown in the image, the image analysis tool does recognize paintings by the same artists in general. For example, the two works by Qiu were categorized under the same sub-branch. The same categorization also happened to 2 of Li's work, 5 of Ni's work, 2 of Tang's work, another 4 of Tang's work, and 2 of Guo's work. 

## stpe 3: Construct a 100-image dataset
I decided to collect images of different species, as well as different style sof birds. I named each images according to the specie of the bird. I also collected images that wre about bird but doesn't have a specific biological category. I named them as geometric shapes. 

Comparing the sequence of images in the image viewer vs the original ones in my file, I didn notice changes of image sequences, and its siaplacement is referred to how similar/different each image's color and style is compared to its neighboring images. 
![outcome7](/images/outcome7.png "outcome7")

I tried to use the "Test and Score" function in Orange, but failed. It seems that the train data lacks a target variable. I don't know how to set a variable in an image dataset, as a result, I didn't figure it out. I used the instructions in video 14 to complete step 3. 

## Step 4
Creating an image dataset of artworks related to birds is a good example of how cultural, political, social, and economic contexts can influence the framing of a dataset. The artworks I choose to include and the way Orange categorize them are reflecting the values, biases, and worldviews that are prevalent in the societies that produce them.

For instance, the Renaissance paintings that feature pigeons often depict them as symbols of peace and purity, reflecting the values of that period. In contrast, Chinese paintings frequently feature white birds and sparrows, which symbolize good fortune in Chinese culture. The cute and adorable portrayal of owls in some artworks suggests that these birds have been connected to gentle qualities, whereas the colorful and flamboyant portrayal of parrots has often been linked with wealth and luxury.

These associations between birds and cultural values influence how Orange frames my image dataset. It selects samples of a specific topic/object/style, and these samples are filtered through the cultural, political, social, and economic contexts. The categories it uses to organize the dataset, the labels that are assigned to each image, and the criteria to judge the quality and relevance of each sample are all shaped by these contexts.

In conclusion, creating an image dataset is a process that is embedded within specific cultural, political, social, and economic contexts. We choose samples of the world that represent the question we are investigating, and these samples are filtered through our biases and values. The way we categorize and label each image reflects our worldviews, and the criteria we use to evaluate the dataset reflect the values that are prevalent in our societies. As such, it is important to recognize the influence of these contexts on our datasets and strive to create datasets that are diverse and representative of different perspectives.

![outcome8](/images/outcome8.png "outcome8")

Based on the information provided, it seems that the machine was able to identify and group some images accurately, but there were also instances where it struggled. Specifically, it was able to identify a certain bird species, but it failed to group all the images of that species together, indicating that there might be some limitations to its clustering capabilities.
It is also interesting to note that the machine classified images based on color, which is a common technique used in clustering analysis. The fact that black and white paintings by Qi Baishi were grouped together and paintings of bluebirds were grouped together suggests that the machine was able to distinguish different color schemes and group them accordingly.
However, it is concerning that the machine identified identical images as one image when creating the hierarchy board. This suggests that the machine might be over-simplifying the clustering process and not taking into account subtle differences between images that could impact their grouping.

Overall, the machine's performance in this image database clustering analysis appears to have been mixed. While it demonstrated some ability to accurately identify and group images based on certain criteria, there were also some limitations and oversimplifications that could impact the reliability of its results.

In the context of distant reading, according to the blog by Lauren Klein, the issues of gender, sexuality, and race are often overlooked because these are non-dominant subject positions that require increased attention to be fully understood. Similarly, in the image database analysis of bird paintings, the interpretation of the images is complex and requires attention to be paid to various characteristics, including color and painting style. However, as the classification of the bird paintings is not primarily based on biological characteristics, such as the species of bird, there is a risk of oversimplification of certain aspects of the analysis.
Arnold and Tilton's definition of "distant viewing" as making explicit the interpretive nature of extracting semantic metadata from images is helpful in understanding the complexities involved in the analysis of bird paintings. By acknowledging the interpretive nature of the analysis, it becomes clear that the classification of the images is not a straightforward process, and that it is subject to interpretation and subjective biases. The fact that the classification is primarily based on color and painting style suggests that there is a risk of oversimplification and a lack of attention paid to other characteristics, such as the species of birds in the paintings.
Therefore, while Arnold and Tilton's definition of "distant viewing" is useful in understanding the interpretive nature of the analysis, it also highlights the need for careful consideration and attention to be paid to all aspects of the images being analyzed. In the case of bird paintings, this means paying close attention to the biological characteristics of the birds, as well as the visual aspects of the paintings themselves, in order to avoid oversimplification and ensure a more complete understanding of the images.

## Afterwards

![outcome9](/images/outcome9.png "outcome9")

I fixed the problem of Orange and had the softward analyze my classification of image. It turns out that the software's predicted classification is, in general, the same as my classification according to different species of birds and different drawing styles.
For images with more singular color, it is easier for the software to identify them and put them in the same classification. 
