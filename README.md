# tfjs-sandbox
Sandbox project about learning [TensorFlow.js](https://js.tensorflow.org/) - JavaScript library for training and deploying ML models in the browser and on Node.js 

Just run ```node index.js mobilenet/model.json panda.jpg``` to see the classification results with example ```panda.jpg.``` and see the result like below: 
```
classification results: 
  [ 
    { className: 'giant panda, panda, panda bear, coon bear, Ailuropoda melanoleuca',
      probability: 0.9993536472320557 },
    { className: 'American Staffordshire terrier, Staffordshire terrier, American pit bull terrier, pit bull terrier',
      probability: 0.0001296834961976856 },
    { className: 'Arctic fox, white fox, Alopex lagopus',
      probability: 0.00008463513950118795 
    } 
  ]
```
You can choose whatever image to test and replace ```panda.jpg``` to the corresponding image in the command line.
The only one restriction - in order to get a successful result, you have to use an image/object from top 1000 classes which are available here: 

https://github.com/tensorflow/tfjs-models/blob/master/mobilenet/src/imagenet_classes.ts
