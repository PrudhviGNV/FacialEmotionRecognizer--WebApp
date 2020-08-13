
## Facial Emotion Detector
- Web app that detects your face emotions using AI and matches them with emojis.
- Built using ReactJS and face-API.js
- Face-API.js is a JavaScript API for face detection and face recognition in the browser implemented on top of the tensorflow.js core API.
- Version 1.0

## URL / Live demo
- [louiejancevski.github.io/FacialEmotionDetector/](https://louiejancevski.github.io/FacialEmotionDetector/)

## About this project
The main objective was very simple, to display emojis based on the facial expressions that we make in front of our camera.

Once the app detects your face, it will do two things:
- Change the background color.
- Replace the default emoji with the one that it thinks is the best match to your expression.

Face-API.js was used to faciliate this process. You can read more about it [here](https://justadudewhohacks.github.io/face-api.js/docs/).

**Note**: You are not being recorded at any point, it all happens in your own browser!

## Taking a look inside
I'm going to take Dwayne Johnson, The Rock, as an example to showcase the site. 

Very straightforward. 

Whenever he smiles, the emoji turns into a lauging emoji, and the background color changes to gree.

![App demo image](https://github.com/louiejancevski/FacialEmotionDetector/blob/master/public/demo.png)

On the other side,

If he looks a bit angry, the app will also catch that and display the right emoji and background color. 

![App demo image](https://github.com/louiejancevski/FacialEmotionDetector/blob/master/public/demo1.png)

Same thing happens whenever the expression might look a bit neutral. 

The emoji gets changed, and the background color gets updated as well.

![App demo image](https://github.com/louiejancevski/FacialEmotionDetector/blob/master/public/demo2.png)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
 
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
