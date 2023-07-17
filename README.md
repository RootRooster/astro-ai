# Horoscope Prediction Website

This is a web application that generates daily horoscope predictions for users based on their 
zodiac sign, utilizing the power of Chat GPT. It provides personalized predictions in three 
major categories: money, love, and health. The application is built with Angular and Spring 
Boot as the frontend and backend technologies, respectively.
<hr>
Note that this is a proof of concept webside and is not yet ready for production.

## Features

- User-friendly interface for entering and submitting personal information, including email, 
horoscope, and date of birth.
- Secure data handling with server-side validation and protection.
- Chat GPT integration to generate accurate and engaging horoscope predictions.
- Daily horoscope predictions tailored to the user's zodiac sign.
- Prediction categories include money, love, and health, providing comprehensive insights.
- Responsive design for optimal user experience across different devices.

## Installation

To run this application locally, follow these steps:

### Prerequisites

- Node.js and npm should be installed on your system.
- Java Development Kit (JDK) version 11 or higher is required.
- Apache Maven for building the Spring Boot backend.

### Frontend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/horoscope-prediction-website.git
   ```

2. Navigate to the frontend directory:

   ```bash
   cd horoscope-prediction-website/frontend
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the frontend development server:

   ```bash
   ng serve
   ```

   The application will be accessible at `http://localhost:4200` in your web browser.

### Backend Setup

1. Open a new terminal window and navigate to the backend directory:

   ```bash
   cd horoscope-prediction-website/backend
   ```

2. Build the backend application using Maven:

   ```bash
   mvn clean install
   ```

3. Start the Spring Boot server:

   ```bash
   java -jar target/horoscope-prediction-website.jar
   ```

   The backend server will start on `http://localhost:8080`.

## Usage

1. Open your web browser and access `http://localhost:4200` to load the application.

2. Fill in the required information, including your email, horoscope, and date of birth.

3. Click the "Generate Predictions" button to receive personalized horoscope predictions.

4. The application will display three separate predictions for money, love, and health, based 
on your zodiac sign.

5. Enjoy reading your daily horoscope predictions!

## Contributing

Contributions are welcome! If you want to enhance the application or fix any issues, please 
follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and test thoroughly.

4. Commit your changes with a descriptive commit message:

   ```bash
   git commit -m "Add feature or fix bug"
   ```

5. Push your branch to your forked repository:

   ```bash
   git push origin feature/your-feature-name
   ```

6. Open a pull request on the main repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- This application utilizes the power of Chat GPT, powered by OpenAI's GPT-3.5 model.
- Thanks to the Angular and Spring Boot communities for their excellent frameworks.
- Special thanks to OpenAI for providing cutting-edge natural language processing capabilities.
