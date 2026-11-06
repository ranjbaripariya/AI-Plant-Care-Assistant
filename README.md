# AI Plant Care Assistant

**Summary:** A mobile application that uses artificial intelligence to help people take care of their indoor plants by analyzing photos and providing personalized care instructions.

## Background
Many people love having plants at home but struggle to keep them alive. They often don't know if a plant needs water, more sunlight, or if it has a disease. This leads to frustration and wasted money. My motivation is to make plant care easy and accessible for everyone.

## How is it used?
The user opens the app and takes a picture of their plant. The AI model analyzes the image to detect the type of plant and check for signs of diseases, dry leaves, or pests. The app then gives specific instructions, such as "Water the plant today" or "Move it to a brighter spot."

## Data sources and AI methods
The AI model will be trained using a large dataset of plant images, such as the open-source PlantVillage dataset. 
I will use Convolutional Neural Networks (CNNs), which are highly effective for image classification tasks. The model will learn to differentiate between healthy and unhealthy leaves based on visual patterns.

## Challenges
The main challenge is image quality. If the user takes a blurry photo or the lighting is bad, the AI might give a wrong prediction. Also, distinguishing between similar-looking plant diseases requires a very large and diverse dataset. The model cannot replace professional botanists, but it serves as a helpful guide.

## What next?
If the project is successful, I could add a community feature where users share their plant care tips. In the future, the app could connect to smart watering devices (IoT) to automate the watering process based on the AI's recommendations.

## Acknowledgments
*   Inspiration and data from the PlantVillage dataset.
*   Elements of AI course by University of Helsinki for providing the knowledge to build this project.
