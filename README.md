# CaloriAI - AI-Powered Calorie Tracker

## Overview
Welcome to **CaloriAI**, a personal project aimed at simplifying calorie tracking and nutritional awareness using AI and image recognition. This app is currently in **active development**, and new features are on the way!

## My Inspiration
Maintaining a healthy lifestyle can be overwhelming. Counting calories and tracking macronutrients often feels like a chore. That's why I created **CaloriAI**—an app that makes this process easier. By leveraging AI and image recognition, my goal is to build a tool that provides instant insights, empowering users to make healthier food choices effortlessly.

## What It Does
CaloriAI uses TensorFlow's object detection model to recognize food items in a meal. By simply taking a photo, the app provides a breakdown of the calories, macronutrients, and ingredients in each dish. The goal is to offer users a fast and accurate analysis of their meals, helping them better understand their nutritional intake.

## Tech Stack
Here’s a breakdown of the core technologies I’m using to develop CaloriAI:

- **React**: A powerful JavaScript library for building dynamic and responsive user interfaces.
- **TensorFlow.js**: For real-time object detection and analysis of food items.
- **Material-UI**: A popular UI framework for creating sleek and modern app designs.
- **Chart.js**: For visualizing data like nutritional breakdowns in graphs and charts.

## Development Process
Building CaloriAI has involved several important steps, and the app is still evolving. Here's how I approached the development so far:

1. **Planning and Design**: Outlining core features, including image-based food recognition, nutritional analysis, and a user-friendly interface. Careful planning guided the development roadmap and design decisions.
  
2. **React & JavaScript Development**: Using React for its flexibility and component-based architecture allowed me to build a scalable interface. The JavaScript ecosystem made it easy to integrate TensorFlow and other libraries for a seamless user experience.

3. **TensorFlow Model Integration**: Integrating TensorFlow’s object detection model (trained on the COCO-SSD dataset) was a major focus. This required research and testing to ensure the model’s compatibility with a React-based frontend and smooth performance, particularly on mobile devices.

4. **Material-UI Framework**: I used Material-UI to create a visually appealing and responsive user interface. It provided pre-built components that saved time in development while ensuring a professional design.

5. **Data and Nutrition Analysis**: I integrated a JSON dataset containing nutritional information to analyze and display the data from recognized food items. The results are shown in tables and visualized with Chart.js graphs.

6. **Testing and Iteration**: Continuous testing has been essential to refining the app. I’ve performed numerous iterations based on feedback and testing to improve performance and user experience.

## Challenges I Faced
- **TensorFlow Integration**: Ensuring compatibility between TensorFlow’s object detection model and the React frontend was complex and required significant testing and adjustments.
- **Performance Optimization**: Optimizing the app for mobile devices, especially ensuring the AI model ran efficiently, was a key challenge.

## Accomplishments
- Successfully integrated AI for real-time food recognition.
- Optimized performance for mobile devices.
- Learned about TensorFlow and React integration.
- Built a clean, intuitive UI using Material-UI.