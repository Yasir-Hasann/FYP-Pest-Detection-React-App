<a name="readme-top"></a>

<div align="justify">
<p align="center">
  
<img src="https://github.com/Yasir-Rana/FYP-Pest-Detection-React-App/assets/99634661/d1b0ff24-b9b7-44f3-919c-0d0b5680a568" alt="Detect Pest" width="640" />

</p>


# Pest Detection, Classification, Pesticides Recommendation System

This project is a ReactJS application designed to detect and classify pests in images uploaded or captured by users using their smartphones. The system utilizes the YOLOv5 model for accurate and real-time pest detection and classification. It also incorporates a recommendation system to suggest appropriate pesticides based on the identified pests.


<details>
<summary><strong>Table of Contents</strong></summary>

- [Features](#features)
- [Pests Classes](#pests-classes)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Executing program](#executing-program)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)

</details>

## Features

- Image Upload and Capture: Users can select an image from their device or capture a real-time picture using their device's camera.
- Pest Detection and Classification: The selected or captured image is sent to a local server or API developed in Node.js. The server forwards the image to ROBOFLOW for processing using the YOLOv5 model. ROBOFLOW analyzes the image and provides a response containing the class and confidence level of the detected pests.
- Pesticides Recommendation: Based on the identified pests, the system generates recommendations for suitable pesticides that can be used to address the pest issue.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Pests Classes

The system is designed to identify and classify the following pest classes:

1. Aphids
1. Sawfly
1. Grasshopper
1. Green Leaf-hopper
1. Beetle
1. Armyworm

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

### Prerequisites

- Node.js installed on your machine


### Executing program

To run both the React app and the server using Visual Studio Code (VS Code), you can follow these steps:

**Frontend (ReactJS with Vite):**

1. Open Visual Studio Code.
   
1. Open the terminal in VS Code by going to View -> Terminal or using the keyboard shortcut Ctrl+backtick.
  
1. Navigate to the frontend project directory using the cd command in the terminal.
   
1. Run the following command to install the project dependencies:
   ```shell
   npm install
   ``` 
1. After the dependencies are installed, run the following command to start the development server:
   ```shell
   npm run dev
   ```
   
1. The Vite development server will start, and you can see the local development URL in the terminal (e.g., http://localhost:3000).

**Backend (NodeJS):**

1. Open a new terminal in Visual Studio Code by going to View -> Terminal or using the keyboard shortcut Ctrl+backtick.
   
1. Navigate to the backend project directory using the cd command in the terminal.
   
1. Run the following command to install the project dependencies:
   ```shell
   npm install
   ```
1. Once the installation is complete, start the server by running the following command:
   ```shell
   npm start
   ```

1. The server should now be running and ready to receive requests from the Flutter app.

By following these steps, you can simultaneously run the Flutter app and the backend server in VS Code. This allows you to test the app and interact with the server while having them both easily accessible within the same development environment.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
   

## Technologies Used

+ ReactJS: A JavaScript library for building user interfaces.
+ YOLOv5: A state-of-the-art object detection model used for pest detection and classification.
+ ROBOFLOW: A platform for training, deploying, and managing computer vision models.
+ Node.js: A JavaScript runtime used for creating a local server and API to handle image processing and communication with ROBOFLOW.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Future Enhancements

Here are some potential areas for future enhancements:

+ Integration of additional pest classes for a more comprehensive detection and classification system.
+ Implementation of user login/sign-up functionality to provide personalized experiences and access to saved pest detection records.
+ Integration of a database to store user data, historical pest detection records, and user preferences..
+ Implementation of real-time pest monitoring using the smartphone's camera feed.
+ Enhancement of the recommendation system with more sophisticated algorithms based on pest characteristics and pesticide effectiveness.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

</div>
