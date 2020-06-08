# Vehicle Damage Detection Project
As a part of ISB's AMPBA program, a capstone project was undertaken. The business objective was to use modern data science techniques (deep learning in this case) to automate or semi-automate insurance claim process so that following objectives can be met.

* Model helps surveyor or claim settlement team in assessing the claim faster
* The insurance claim process time get reduced
* Model can help in making process more customer friendly

# Methodology
Following stepwise approach was taken to create a model
* Create an object detection model that can detect whether there is a car in the given picture (A Sanity Check Model)
* Create another object detection model that can detect which part of the car is visible in the picture
* Create an image segmentation model that can detect whether there is a damage(scratch, dent, breakage) on the detected part
* Create a cost estimation model that can give approximate repair cost for the given claim

Above approach helped in successfully detecting the part and damage that can help in estimating the cost of repair. The project resulted in a succesful PoC which later on went to production to be a scalable solution in the market.
All the models were created in Python using Keras and Tensorflow libraries. Entire project has been shared here in this repo for educational purpose.
You can connect with me [here](https://grvsrm.github.io/)
