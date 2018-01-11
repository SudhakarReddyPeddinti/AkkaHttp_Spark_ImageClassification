# AkkaHttp Spark ImageClassification
Akka Http based Spark program to perform image classification

#### Problem: Provide api capabilities for spark programs which can accept http request and send response.
This code contains:
- AkkaHttp server implementation to receive image and run spark classification to predict the test image class.
- Simple UI code to visualize and send the image to server and display the result.

Usage: 

To start Server
- Clone the git repository
- Import project in IntelliJ IDE
- Run SimpleServer under `ImageClassification/image_classification/src/main/scala/SimpleServer.scala`

To start UI Client 
- Go to `ImageClassification` folder in terminal
- execute `npm install superstatic`
- run superstatic using - `superstatic -p 8081`
- Open `localhost:8081` in any web browser to see the UI.
- Select any image and click predict

![ImgClasfy](http://i65.tinypic.com/2drevsl.jpg)
