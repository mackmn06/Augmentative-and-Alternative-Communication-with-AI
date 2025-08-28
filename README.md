<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Augmentative-and-Alternative-Communication-with-AI
using NLP to assist people with disabilities in generating and interpreting speech

Final project for the Building AI course

## Summary

% Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length!

The purpose of this project is to use AI to augment existing AAC (augmentative and alternative communication) devices for people with disabilities affecting communication.


## Background

AAC is probably most widely known for its use by nonspeaking autistic people. However, there is a wide range of other disabilities that can also affect communication and which may be supported with AAC, including:

* dementia
* strokes
* traumatic brain injuries
* brain cancers
* motor neuron diseases
* cerebral palsy
* and more

Despite AAC's association with autism, non-autistic people have a good reason to be invested in quality AAC-- on the one hand, they can be affected by the aforementioned communication disorders at any time in their lives, and on the other hand, they may meet, work with, or become the relative of a nonspeaking autistic person at some point in their lives and they would benefit from being able to communicate more effectively with one another.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

The AI-generated responses based on user input may not always accurately predict the user's intentions, leaving room for miscommunication. For some people with communication challenges, it can be difficult to determine if they have other impairments e.g. with comprehension or cognitive challenges that could make the app more difficult to use. 

## What next?

In order to implement this project I would need to learn more about app development or work with someone with experience in app development to actually create it. It may also be beneficial to consult with a nonspeaking autistic person about what they would find helpful.

## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
