<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# HSEAI

Final project for the Building AI course

## Summary

This project is being prepared to analyze images or videos of an office environment with AI and to make an HSE assessment of the given office environment.

Images or videos will be used as input. The entered data will be analyzed with an AI model and the elements that pose a risk in terms of HSE will be marked on the images and given as a list.

## Background

Not every small business has the economic power to employ HSE personnel. However, employee safety is also a very important requirement. Therefore, determining the significant risks in the work environment by making a basic HSE assessment and taking precautions against them will make a significant contribution to the safety of employees.

## How is it used?

Images or videos will be used as input. Ideally, this data should include 360-degree information about the office environment to be evaluated. It is of great importance for the accuracy of the analysis to also display the areas behind the materials in the office.

The entered data will be analyzed with an AI model and the elements that pose a risk in terms of HSE will be marked on the images and given as a list.

## Data sources and AI methods

The information obtained from open sources will be used as training data for the model to be prepared here. First, a classification will be made according to risk types, then the artificial intelligence model will be trained with images corresponding to these classes. Images belonging to a work area whose HSE assessment was made by experts will be used as test data. A new assessment will be made on the test data with the trained model, and the identified risk factors will be compared with those identified by the expert.

## Acknowledgments

> [!CAUTION]
> The model to be prepared within the scope of this project is aimed to detect the maximum level of risk elements. However, it may not detect all risk elements. Therefore, the use of this model in real environments is the responsibility of the users. Those who contribute to the project cannot be held responsible in this regard.
