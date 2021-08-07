# Real-time object detection in the browser using TensorFlow.js

A Kangaroo detector was trained as a demo, but any object can be recognized following the [tutorial steps](https://medium.com/@zaninihugo/custom-real-time-object-detection-in-the-browser-using-tensorflow-js-5ca90538eace) and it will produce results similar to the shown below:


## Getting started

The model saved at `models/kangaroo-detector` was trained using the [kangaroo-dataset](https://www.kaggle.com/hugozanini1/kangaroodataset) available on kaggle:

You can train your own model, upload it in the `model` folder and load as well.


#### Running locally
To run the app locally, install the required packages:

```
npm install
```

And start:

```
npm start
```

The application is going to run at `[http://localhost:3000](http://localhost:3000)` and you should see something similar to this:

The model takes from 1 to 2 seconds to load and, after that, you can show the objects images to the camera and the application is going to draw bounding boxes around them.

