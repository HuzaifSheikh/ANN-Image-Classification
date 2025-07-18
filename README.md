# Image Classification using ANN
This project is a Java-based simulation platform that integrates an Artificial Neural Network (ANN) to classify images through a web interface. It is hosted on an Apache Tomcat server and designed to demonstrate ANN-based image processing in a simulation environment.

## Features
- Web-based interface for uploading and classifying images
- Backend powered by an ANN image classification model
- Java Applet-based simulations for visualizing processing steps
- Local deployment using Apache Tomcat

## Requirements
- Apache Tomcat (Tested on version 7 or 8)
- Java Runtime Environment (Ensure Java is installed and configured)
- Internet Explorer 9 (Required due to Java Applet compatibility)

## Installation Instructions
- Place the Simulation folder inside:
```
\tomcat\webapps
```
- Open the Java Control Panel and add the following URLs to the Exception Site List:
```
http://localhost:8080/Simulation/ImageUpload
http://localhost:8080/Simulation/sim2D.jsp
http://localhost:8080/Simulation/simulate.jsp
```
- Open Internet Explorer and navigate to:
```
http://localhost:8080/Simulation/index.jsp
```
Accept all Java applet digital signatures when prompted. Due to modern browser security restrictions, Java applets may not run correctly on newer browsers. This project is intended for academic or legacy demonstration purposes only.

## Authors
Sheikh Huzaif
