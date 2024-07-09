# Soil Analysis and Farmer Advisory System

This project aims to streamline the process of soil analysis and provide actionable insights to farmers. By leveraging modern web technologies and robust backend systems, this platform enables farmers to upload soil reports and receive detailed analysis and expert advice to enhance their agricultural practices.

### Features

- **Web Interface Development**: User-friendly interface built with Flask and React.js where farmers can submit their soil reports.
- **Expert Analysis**: Experts analyze the submitted soil data and provide detailed reports, enhancing the decision-making process for farmers.
- **Data Management**: Backend system developed using Python and MySQL to manage and process large datasets efficiently.
- **Deployment**: Application containerized with Docker and hosted on AWS, ensuring high availability and performance.
- **Real-time Communication**: Seamless communication between farmers and experts, allowing farmers to ask questions and get timely responses.

### Additional Features

- **Explore Weather Details**: Discover the latest weather information relevant to your location.
- **Predict Crop Diseases**: Click the button to predict possible diseases affecting your crops based on soil reports.
- **Talk to Expert**: Use the form to submit inquiries and receive expert advice.


![Project Screenshot](https://github.com/Shubham-Kumar-Sahoo/Soil-Analysis-and-Farmer-Advisory-System/blob/main/Img/img2.jpeg)


## To Run

### Backend Setup

1. Navigate to the project directory:
   ```bash
   cd soil-analysis-advisory-system
   ```
2. Set up the virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Set up the MySQL database and configure the connection settings in `config.py`.
4. Run the backend server:
   ```bash
   python app.py
   ```

### Frontend Setup

1. Navigate to the frontend directory and install dependencies:
   ```bash
   cd frontend
   npm install
   ```
2. Start the frontend development server:
   ```bash
   npm start
   ```
3. Access the application at `http://localhost:3000`.
