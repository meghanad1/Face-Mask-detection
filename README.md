# Face-Mask-detection using Multi task learning

## Overview
We implement an approach to predict two objectives in the multitask set up -

i) The primary task to detect faces that have their masks worn correctly or incorrectly

ii) The secondary task to detect faces that have their mask only covering the nose and mouth; masks only covering mouth and chin and mask under the mouth (i.e three cases of mask incorrectly worn)

## Code Structure

## Dataset
MaskedFace-Net that consists of 133,783 synthetically generated images belonging to below categories was used

1. Mask Correctly worn

3. Mask incorrectly worn

    i) Chin exposed
    
    ii) Nose exposed
    
    iii) Nose & mouth exposed
    
The data is accessible at https://github.com/cabani/MaskedFace-Net


## Environment requirements


## Contributors
Swasthi Chittoor Shetty

Sanjana Vijay Ganesh

Samarth Varshney

Meghana Deepak

Isha Dilipkumar Shah

This work was done as part of CS6220 Big Data Systems and Analytics project requirements at Georgia Tech

## References
The following papers and code were used for this project
https://github.com/truongnmt/multi-task-learning
