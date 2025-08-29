<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Augmentative-and-Alternative-Communication-with-AI
using NLP to assist people with disabilities in generating and interpreting speech

Final project for the Building AI course

## Summary

The purpose of this project is to use AI to augment existing AAC (augmentative and alternative communication) devices/applications for people with disabilities affecting communication. This project would take simplified inputs from users and would generate multiple predictions of the user's intended message. Additionally, this application would take complex pieces of text or speech and rewrite it in simplified language to make it easier for the user to understand without requiring excess time or effort.


## Background

AAC is probably most widely known for its use by nonspeaking autistic people. However, there is a wide range of other disabilities that can also affect communication and which may be supported with AAC, including:

* dementia
* strokes
* traumatic brain injuries
* brain cancers
* motor neuron diseases
* cerebral palsy
* and more

Despite AAC's association with autism, non-autistic people also have a good reason to be invested in quality AAC-- not only can anyone become affected by communication disorders at any time in their lives, but non-autistic people may still meet, work with, or become the relative of a nonspeaking autistic person at some point in their lives. Therefore everyone would benefit from expanding communication options for people with disabilities affecting communication. 

For disabled users, being able to quickly express themselves in language that is easy for others to understand helps reduce dangerous communication challenges (such as reporting abuse, dealing with law enforcement/security personnel, or describing medical problems) and also helps users live with more dignity and respect from their communities.


## How is it used?

AAC devices/applications can take many different forms depending on the user's limitations and support needs. 

Some users may have no trouble understanding language or explicitly planning what they mean to say, but may mainly struggle with the motor control needed to produce speech or write text. These users may use a letterboard, eye tracking, or hunt-and-peck typing to produce text. These users may be able to produce grammatically correct and easy-to-understand text, but it's often time-consuming to produce and may require physical support from another person. This can cause doubts about whether the support person is inserting their own influence into the generated text (see the Derrick Johnson/Anna Stubblefield case).

<img src="https://i.ytimg.com/vi/9teZwNf8dP0/hq720.jpg?sqp=-oaymwEhCK4FEIIDSFryq4qpAxMIARUAAAAAGAElAADIQj0AgKJD&rs=AOn4CLAqYCRKy7Ts1-TFNVYzJOHfXT_UjA" width="300">

<img src="" width="300">

Other users may struggle with understanding language, such as understanding/remembering words without pictoral representations, understanding correct grammar usage, etc. These users may use apps or devices that break words down by category/frequency and labels word buttons with a corresponding image/icon to make them easier for the user to identify.

<img src="https://i.shgcdn.com/fe0ce32e-fbce-4086-a985-8c08b3578634/" width="300">

<img src="https://images.ctfassets.net/67wivm6jm6qo/6nsSi8g3CBam4kpnNfCyMx/e45e3acdf8d8e10cfa154b5697579dff/FOF-Incorportaing-AAC-3.jpg?w=1000&q=100" width="300">


%Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)


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

This project would employ an NLP like ChatGPT to make predictions about the user's intended message based on a very limited/simplified input. 
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
