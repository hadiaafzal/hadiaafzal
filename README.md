**Project Title**:
**Weather Forecast App using 7Timer API**

**Project Overview**:
This project, created by Hadia, is a simple weather forecasting app that retrieves and displays 7-day weather forecasts for major European cities using the 7Timer API. Built using HTML, CSS, and JavaScript, the app allows users to view accurate weather data effortlessly. The project was developed using Postman for API testing and Visual Studio for code development.

**Motivation**:
The goal of this project is to help users easily access weather forecasts. Inspired by the need to present weather data in a visually appealing and straightforward way, this app addresses the issue of complex weather applications by offering a simplified alternative.

This project was guided by a course on Coursera.


**Installation Instructions**:

**Prerequisites**

Basic understanding of HTML, CSS, and JavaScript
Visual Studio Code
Postman
Web browser (for testing)


**Cloning**:
To clone this repository, use the following command:

```bash
git clone https://github.com/hadiaafzal/weather-app.git


**Setup**:

1)Clone the repository using the command above.

2)Open the project folder in Visual Studio Code.

3)Run the app by opening index.html in your browser.


**Usage**:

**Basic Usage**:

The app allows users to:

1)View 7-day weather forecasts by selecting a city from the provided options.

2)Display weather data visually with relevant icons for conditions like rain or clear skies.


**Examples**:


<!--- JAVASCRIPT CODE INITIALIZATION-->


fetch('http://www.7timer.info/bin/api.pl?...')

    .then(response => response.json())
    
    .then(data => {
    
        console.log(data); // Outputs weather forecast
        
    });
**Advanced Features**:
Customizable city options
Two-section layout for weather display, each with a different background color.

**Contributing**:


**Guidelines**:

1)Fork the repository.

2)Create a new branch for your feature (git checkout -b feature-branch).

3)Commit your changes (git commit -m 'Add new feature').


4)Push to the branch (git push origin feature-branch).

5)Open a pull request.


**Code of Conduct**:
Be respectful and kind to other contributors.

**License**:
This project is licensed under the MIT License.
Full License Text


**Contact Information**
Maintainer: Hadia
Email: [hadiaafzal1718@gmail.com]


**Acknowledgements**
Coursera for guidance throughout the development process.

