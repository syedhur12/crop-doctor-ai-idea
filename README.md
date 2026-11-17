# Crop Doctor - AI for Pakistani Farmers

Final project for the Building AI course project

## Summary

Crop Doctor is an AI idea that helps small farmers in Pakistan detect crop diseases from a photo of a leaf. The farmer takes a photo, the AI predicts the disease, and the app shows treatment in simple Urdu and English. This is my Building AI course project.

## Background

Which problems does your idea solve? How common is it?

* Farmers in Pakistan lose a big part of their crop because diseases are found too late.
* Most small farmers cannot afford an agriculture expert.
* Farmers often ask a local shopkeeper, who gives the wrong spray just to sell his product.
* Wrong spray wastes money, damages the crop, and harms the soil.

This problem happens every season in Punjab and Sindh, and it directly affects food, income, and poverty.

## How is it used?

Describe the process of using the solution.

1. Farmer opens the app and takes a photo of the damaged leaf.
2. AI checks the photo and predicts the disease, for example: 92% Leaf Rust.
3. App shows the disease name in Urdu + English.
4. App shows treatment, prevention, and which spray to use.
5. Farmer can save the result and show it to an expert.

The app will work offline for basic predictions, because many villages have weak internet.

## Data sources and AI methods

Where does your data come from? Do you collect it yourself or do you use data collected by someone else?

| Data Source | Description |
| --- | --- |
| PlantVillage Dataset | Public photos of healthy and diseased leaves |
| Local Farm Photos | Photos collected from farms in Lahore and Punjab |
| Expert Labels | Labels checked by agriculture experts |

**AI method:** This is an image classification problem. We will use supervised learning and a Convolutional Neural Network (CNN).

The model learns patterns from thousands of labelled leaf photos. For a new photo, it predicts the most likely disease with a probability.

## Challenges

What does your project _not_ solve? Which limitations does it have?

* The AI can make mistakes. A wrong prediction can damage a crop.
* The model may work less well on new diseases it has not seen before.
* Many farmers have low literacy and old phones.
* Farmers' photos and location data must stay private.

So the app will always show confidence and say "Please confirm with an expert" for serious cases. We will not promote any specific pesticide brand.

## What next?

How could your project grow and become something real?

* Weather-based early warning: "Next week rust ka khatra hai"
* Voice assistant in Urdu and Punjabi
* Connection with local agriculture officers
* Market price prediction for crops

The goal is to make it a free tool for every small farmer in Pakistan.

## Acknowledgments

* Inspiration from Elements of AI course by University of Helsinki and Reaktor.
* PlantVillage dataset - open dataset for plant diseases.
* TensorFlow and Teachable Machine - open-source tools.
* This idea is created for learning and community benefit.
