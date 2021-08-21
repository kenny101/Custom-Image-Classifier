# Custom-Image-Classifier

Train and test a deep learning image classifier in minutes! [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)

## How it works

1. Specify how many classes you would like to classify and what images to download. Images are downloaded using https://github.com/Joeclinton1/google-images-download.
   ![user input]("./screenshots/user-input.jpg")

2. Using FastAI's library we can train and clean the downloaded data for better results
   ![cleaning data]("./screenshots/cleaning.jpg")

3. Input image urls and receive predictions
   ![predictions]("./screenshots/predictions.jpg")
