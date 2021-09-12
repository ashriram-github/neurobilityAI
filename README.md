# neurobilityAI

### Inspiration
I love working with AI and neural networks, but there is no real application for them if people are not able to easily reap their benefits. The AbilityHacks hackathon, one designed to promote innovations that support people with disabilities, provided the push to develop an application that incorporated AI. 

I have a lot of close relationships with people with learning disablities, and as such I wanted to create someething to help them. The goal of this project was to write a neural network that would benefit either an individual with a learning disability (most specifically dysgraphia or dyslexia), or an educator working with people with learning disabilities, and create a web app based on that.

### Overview
NeurobilityAI uses a basic deep neural network trained off of the MNIST dataset to recognize handwritten digits. Essentially, my web app can take in a 'png' image of a handwritten digit, and then predict what that digit is. 

There are two pathways I see this assisting those with disabilities. 

1. Many people with dyslexia and dysgraphia find an issue with non-uniformity in text and other writing materials. Though it is not the perfect solution, converting handwritten learning materials into uniform, computer generated, digits would help in understanding material.
2. Educators working with people who have dysgraphia can find analyzing work and providing feedback difficult. By converting unclear handwritten information into clear computer generated text can help teachers with this issue.

### How it works
I used TensorFlow and Keras libraries to assist me with my deep learning model.

Flask - Microframework for python (a very minimal web application framework, or software that supports web app development)
Relation between 'Web App' and 'Web Service'
Web application (the web page) gets data, then it sends the data to the web service (backend), which then uses that information for whatever processes it needs to complete, then it sends it back to the frontend application.

Used flask to host both the web app and web service
