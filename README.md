<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title
MindMate: AI-Powered Mental Health Support Companion
Final project for the Building AI course


## Summary
Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length! 

MindMate is an AI-powered digital companion that provides personalized mental wellness support, daily mood tracking, and early detection of mental health issues using natural language processing and sentiment analysis.

## Background
Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

Mental health issues such as depression, anxiety, and burnout are rising globally. Many people struggle to access timely professional help due to stigma, cost, or lack of awareness.

Over 280 million people globally suffer from depression (WHO)

Suicide is the 4th leading cause of death among 15-29-year-olds

Early intervention is key, but often delayed due to lack of tools

My motivation stems from seeing friends and colleagues struggle silently. Mental wellness is deeply personal and yet socially neglected. This project aims to create a supportive, AI-driven tool that helps users monitor and manage their emotional wellbeing before issues escalate.
This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Users interact with MindMate through a mobile app or web interface, where they can:

Have short, daily conversations with the AI

Log their mood and sleep patterns

Receive reflections, insights, or coping exercises

Get alerts or encouragement to seek help when necessary

Target users:

Students and young adults under stress

Remote workers facing burnout

Individuals who are reluctant to seek therapy due to stigma

Use context:

Used daily in personal environments (at home, during breaks)

Can optionally connect to professionals or helplines if crisis indicators are detected

<img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Mental_health_awareness_ribbon.png" width="200">
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

Data Sources:

Public datasets like DAIC-WOZ and CLPsych Shared Tasks

Anonymized user conversations (with consent)

Sleep/mood logs and journal entries

AI Techniques:

Natural Language Processing (NLP) for understanding journal entries and user inputs

Sentiment analysis and emotion classification

Time-series models for detecting mood trends and risk patterns

Optional integration with LLMs for empathetic dialogue



| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

MindMate does not replace professional help. It cannot:

Diagnose mental illnesses

Intervene in emergencies (though it can suggest hotlines)

Limitations:

Requires careful handling of sensitive data

Risk of over-reliance or inaccurate suggestions

Bias in training data may misinterpret cultural nuances in emotion expression

Ethical considerations:

Transparency in how data is used

Strong privacy and encryption

User control over data and opting out
## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 

To evolve MindMate:

Collaborate with psychologists for content validation

Expand multilingual support for global use

Collect more diverse and representative training data

Develop a prototype using Streamlit or Gradio

Needs:

Frontend and backend developers

NLP and clinical psychology experts

Funding for cloud infrastructure and user testing
## Acknowledgments
Inspired by mental health chatbots like Woebot and Wysa

Data sources: DAIC-WOZ, CLPsych, Kaggle depression detection datasets

Emotions analysis guidance from Stanford NLP

“Mental Health Awareness Ribbon” image by Wikimedia Commons / CC BY-SA 4.0
* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
