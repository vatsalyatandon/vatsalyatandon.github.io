+++
title = "Experience"
slug = "experience"
thumbnail = "images/tn.png"
description = "experience"
+++

### Predicitng Polio recurrence with Rotary International

I worked with team as a part of IITK Consulting Group, in a collaboration with Rotary International to develop a novel approach that predicts the probability of re-occurence of Polio in a specific region based on the following parameters :-

* Cleanliness
* Healthcare Facilities
* Santitation
* Weather/Temperature
* Migration

We used a semi-supervised learning algorithm to divide cities into cohorts and then used predict probabilities. These probabilities were then used to generate insights about effective resource and manpower distribution and the costs associated with it for an overall outlook for the problem.

### Automatic Parking Lot Detection

This project was part of the Round 2 submission of the Techgig Code Gladiators 2019 : Artificial Intelligence Challenge, in association with Jio. For this first we collected 12,417 images (1280x720) captured from 2 lot cameras on sunny, overcast and rainy days as our primary database called [PKLOT](https://web.inf.ufpr.br/vri/databases/parking-lot-database/) from UFPR. Each lot image was further segmented and rotationally transformed to create 6,95,900 segmented individual images of spaces that were either filled or empty. We then created the following models :-

* A regular Convolutional Neural Network for binary classification of segmented images. We used only 3 convolutional and fully connected layers and acieved an accuracy of 99.97% on the test set. The algorithm is also generalizable for various segmented spot detections.

* "Space Counter", a multinomial classifier for detecting number of available parking spots in an image upto a predetermined maximum number. It depicted an accuracy of 80.83% on the test set, with higher accuracy for the cohort of "19 or more available spaces".

The complete analysis of architecture, implementation, results and further improvements can be found [here](../files/Aviato-Presentation.pdf)
