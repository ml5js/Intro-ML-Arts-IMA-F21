# What are data?

## Data Collection

### Objectives:

- Review the full story of building a ML model for classification or regression.
- Understand how data is formatted and downloaded including CSV and JSON.
- Review the terminology of the training process
  - Training
  - Learning Rate
  - Epochs
  - Batch size
  - Loss
- Consider how to frame the problem and collect data.
  - Understand critical questions to ask (e.g. Who is this for? What’s the context?)
  - Understand the questions to ask about sourcing and collecting data.
  - Learn how to prepare a data set, including how to normalize and properly format it.

### Tutorials

- Tabular Data (CSV)
  - [Tabular Data](https://youtu.be/RfMkdvN-23o) from Coding Train "Data + APIs" tutorial (lots of extra stuff here the first few minutes is probably most relevant?)
  - [Tabular Data](https://youtu.be/woaR-CJEwqc) Coding Train Processing tutorial (code is not JS!)
- JSON Data
  - [What is JSON Part 1](https://youtu.be/_NFkzw6oFtQ) - Coding Train p5.js tutorial
  - [What is JSON Part 2](https://youtu.be/118sDpLOClw) - Coding Train p5.js tutorial
  - [JSON Data](https://youtu.be/uxf0--uiX0I) from Coding Train "Data + APIs" tutorial (same as above, lots of extra unrelated stuff here).

### Color Classifier

- [Full Coding Train Video Series using TensorFlow.js](https://youtu.be/y59-frfKR58?list=PLRqwX-V7Uu6bmMRCIoTi72aNWHo7epX4L), 7.1-7.5 cover how the data was collected and cleaned
- [Crowdsourcing Colors website](https://codingtrain.github.io/CrowdSourceColorData/index.html), [Crowdsourcing Colors source code](https://github.com/CodingTrain/CrowdSourceColorData)

### ml5.js examples

- [Color Classifer JSON Data](https://editor.p5js.org/ima_ml/sketches/WOLz4pub3)
- [Color Classifier CSV Data](https://editor.p5js.org/ima_ml/sketches/8eskYqyhA)

## Assignment 5b

### Data Research

Select a dataset from class discussion and consider the following questions related to that dataset:

- Who collected and compiled it?
- Why was it collected?
- How was it collected?
- Describe the data: What are the dimensions? What are the variables and their data types?
- Is there missing, incorrect, or otherwise problematic data?
- For whom is this data accurate or useful? What is this data _unrepresentative_ of? (Who is missing and left out of the data?)
- Knowing what you know now about machine learning, what will a model trained on this data help you do? Are there are alternative (non-machine learning) uses of this data?

### Coding Exercise

For this assignment it's up to you to select an exercise building off of the multiple data collection and model training scenarios we've examined in weeks 4-6.

#### 1: Interactive Real-Time Gesture Data

Continue working on your sketch from [Assignment 4](https://github.com/ml5js/Intro-ML-Arts-IMA-F21/wiki/Assignment-4). What are your next steps? Maybe try breaking it into multiple sketches for saving / loading the trained model? Or try a regression model instead of classification?

#### 2: Working with Quick Draw, DoodleNet

Build off of one of the code examples (or invent your own) to develop you own creative use of Quick, Draw data.

- [Rendering Quick, Draw drawings](https://editor.p5js.org/ima_ml/sketches/vCfQL93k7)
- [Animating Quick, Draw! paths](https://editor.p5js.org/ima_ml/sketches/aT9zxHX7n)
- [Classifying Drawings with ml5's DoodleNet: output in DOM element](https://editor.p5js.org/ima_ml/sketches/IbXlN6voN) -- _Can you make this one work with webcam input instead of canvas?_
- [Classifying Drawings with ml5's DoodleNet: output in separate canvas](https://editor.p5js.org/ima_ml/sketches/XIZEoKBTL)

#### 3: Other Data Sources

Try loading JSON or tabular data into a p5.js sketch and train a model. Some suggestions:

- Augment Lydia Jessup's [311 Calls ml5.js example](https://editor.p5js.org/lydiajessup/sketches/NQ6iRoAM2). You could add an additional input field, customize the interface, or change other parameters of `ml5.neuralNetwork()`.
- Train a machine learning model in ml5.js with the dataset you picked for part 1 of the assignment.

Complete a blog post with your dataset report and code exercise. [Link from the homework wiki](https://github.com/ml5js/Intro-ML-Arts-IMA-F20/wiki/Assignment-5b).
