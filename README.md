# Who is the entertainer?

This repository provide korean entertainer recognition by using openCV and CNN model.

And also provide captured entertainer's information with chrome driver.

<br />

## Process

1. Data Crawling
2. Data processing (we want only entertainer's face)
3. Data Augmentation
4. Model Learning
5. Video Capture with model
6. Provide entertainer's information

<br />

## Example of Data

![image](https://user-images.githubusercontent.com/59254578/72586061-b3bf5e80-3933-11ea-8f79-c98010572e3d.png)

There was a lack of image data. So I used [imgaug](https://github.com/aleju/imgaug) and could make a lot of image data.

<br />

## Our Model

![image](https://user-images.githubusercontent.com/59254578/72585351-18c58500-3931-11ea-88ea-62ee651b868c.png)

We made our model by using [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network) for image classification.

<br />

## Result

<iframe src="https://giphy.com/embed/lq9s9QHRGdQGQfbMHB" width="480" height="252" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

In running video if you press 'enter' key, it shows the captured entertainer's information.
