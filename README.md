# Liooon / not a liooon classifier

An iOS app that tells you whether your camera is pointed at a lion, using apple's CoreML and Vision APIs.

<p align="center">
	<img src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/khaled_lion.jpg"/>
</p>

## Screenshots

<p align="center">
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/lion_detected_1.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/no_lion_detected_coke.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/no_lion_detected_burger.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/lion_detected_2.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/lion_detected_3.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/lion_detected_4.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/no_lion_detected_pen.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/no_lion_detected_candle.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/no_lion_detected_sunglasses.jpg"/>
	<img width="200" src="https://raw.githubusercontent.com/G2Jose/https://github.com/G2Jose/CoreMLVisionDJKhaled/master/screenshots/no_lion_detected_backpack.jpg"/>
</p>

## How to use

Make sure you have iOS 11 installed (currently in beta). [beta.applebetas.co](https://beta.applebetas.co/) hosts provisioning profiles for the latest betas for folks that are not signed up for the Apple Developer Program. Build and run the app using Xcode 9 (also currently in beta).

## How it works

The app uses [CoreML](https://developer.apple.com/documentation/coreml) and the inception v3 pre-trained neural network model to make predictions on a stream of images from your device's camera. A liooon is found when the model predicts it with a confidence of >= 30%.

The [Vision API](https://developer.apple.com/documentation/vision) is used in order to process images efficiently (scale & crop to input specs of the model).

## WTF is the liooon reference?

- https://www.youtube.com/watch?v=fEjgiLiaeFQ
- https://www.youtube.com/watch?v=BJXIY0QfvXY
- https://www.youtube.com/watch?v=AMHYBU1R3Nk
- https://www.youtube.com/watch?v=hgDmyA6yFUU
- https://www.youtube.com/watch?v=HqUQbKIZOzE
