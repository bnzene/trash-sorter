<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# trash-sorter

Final project for the Building AI course

## Summary

Project proposal: use image recognition to help demystify recycling for consumers.


## Background

* Recycling labelling is highly irregular, and varies wildly from country to country, and often city to city.
* Many symbols are also unclear or misleading, leading well-meaning consumers to dispose of a product the wrong way.
* This leads to contamination of recycling loads, and recyclable items going to landfill.
* As a result, it is currently very challenging to know what's right. It's too easy to make mistakes, leading to recyclables going into landfill, and what's become known as "wishcycling" - putting non-recyclable or contaminated materials into recycling and thus spoiling the whole load.
* This problem doesn't need to exist. While I hope that recycling labelling is improved and regularised in the near future, right now I propose to solve this problem by using image recognition to help consumers find out what to do with their waste.


## How is it used?

Delivered via a user’s phone: use phone camera to take a photo of the symbols on packaging
Show the user the instructions for that item, could link to the source of the information


## Data sources and AI methods

### Data sources:
Sets of symbols used to classify what to do with rubbish and their meanings, derived from websites of each country’s government/municipal authorities

### AI techniques:
Image classification - train model to recognise various symbols, associate each with its meaning, so that it can be used to classify new images and return the meaning to a user

## Challenges

A potential risk is if this programme were to give users incorrect information. Since its purpose is to provide reliable answers when users themselves aren't sure what to do, users might be likely to trust the programme above their own judgement when it gives them incorrect answers, and do the wrong thing with their rubbish. This would potentially lead to more of the problem this project attempts to alleviate - incorrectly-sorted trash resulting in unnecessary waste.
Further challenges to be elaborated on an ongoing basis.

## What next?

## Acknowledgments

* [AI-Startup.org: Top 10 Startups developing AI for Waste Sorting](https://www.ai-startups.org/top/wastesorting/#:~:text=ZenRobotics%20Recycler%20is%20the%20world's,the%20next%20generation%20of%20recycling.)
* [SmarterX](https://www.smarterx.com/)
