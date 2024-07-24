# SayNOtoCANCER
 
## Inspiration
Cancer is disease that claims about 10-15 millions lives per year, however numbers usually don't affect us till the time it isn't a close one who gets targeted by it. Last year, I lost my maternal grandfather to cancer, if his cyst near stomach was detected earlier he would be still be today with us

## What it does
My project takes in the image of a CT Scan and tells the possibility for chest cancer and its type.  

## How we built it
I trained an EffNetModel on kaggle's chest CT Scan dataset[link](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images), at first the accuracy wasn't good so I added a hint of data augmentation and a scheduler which improved my models performance.

## Challenges we ran into
Finding the right dataset for the model since too big would mean its trains slowly as I don't have access to GPUs while too small might be too biased<br>
Hosting on Hugging Face<br>
Learning Gradio

## Accomplishments that we're proud of
The validation acc is about 85% and test accuracy is about 78% so hopefully people with possible chest cancer might get early detection and hence early treatment
## What we learned
To host on Hugging Face<br>
How to tackle overfitting and underfitting<br>
## What's next for Cancer Detector for a Cancer Free World
To finetune on more datasets to help more people worlwide
