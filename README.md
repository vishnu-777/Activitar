# ACTIVITAR: Diet and Fitness Recommendation System

## Overview
ACTIVITAR is a comprehensive diet and fitness recommendation system designed to assist users in achieving optimal well-being through personalized health guidance. The system leverages machine learning algorithms to predict users' body type, diet, and workout plans based on their physical attributes and lifestyle.

## Modules
ACTIVITAR comprises three primary modules:

### Admin Module
- **Employee Management**: Register, update, and delete employee (gym instructor) details.
- **Batch Management**: Add time allotment batches and assign employees to each batch.
- **Payment Verification**: View and verify user payments.
- **Feedback Management**: Receive and manage complaints and feedback from users.

### Employee Module
- **User Management**: View details of users in their assigned batch, including height, weight, gender, and age.
- **Workout Management**: View predicted workout details for users and add personalized workouts.
- **Equipment Management**: Manage details of gym equipment.
- **Attendance Management**: Mark attendance for users.

### User Module
- **Registration**: Register by providing height, weight, gender, age, mobile number, email, username, password, and preferred batch.
- **Login and Payment**: Log in and make payments, which need to be verified by the admin.
- **Batch and Employee Info**: View assigned batch and the responsible employee upon payment verification.
- **BMI Tracking**: View BMI in a bar graph format.
- **Prediction**: Enter details like height, weight, calorie intake, exercise frequency, and job type to predict body type, diet, and workout plans.
- **Workout Details**: View workouts added by the employee.
- **Feedback**: Send feedback about the app to the admin.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/activitar.git
    ```
2. Navigate to the project directory:
    ```bash
    cd activitar
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    python app.py
    ```

## Usage
1. **Admin Module**: Access via `/admin` endpoint.
2. **Employee Module**: Access via `/employee` endpoint.
3. **User Module**: Access via `/user` endpoint.

## Features
- **Personalized Recommendations**: Tailored diet and workout plans using machine learning.
- **Real-Time Management**: Efficient management of employees, batches, and user attendance.
- **User Feedback**: Collect and manage user feedback to improve service quality.

## Machine Learning Model
- **Algorithm**: K-Nearest Neighbors (KNN)
- **Dataset**: Manually entered Indian dataset with 500 rows and 10 attributes.
- **Accuracy**: 55% with the Indian dataset, potentially up to 80% with foreign datasets.

## Future Enhancements
- **Real-Time Data Monitoring**: Implement more sophisticated machine learning algorithms to improve personalization.
- **Integration of Wearable Devices**: Incorporate fitness trackers or smartwatches for real-time data collection.
- **Social Features**: Introduce user communities, challenges, or leaderboards to foster engagement.
- **Expanded Services**: Partner with nutritionists and fitness experts for additional content and services.

## Contribution
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit:
    ```bash
    git commit -m "Description of changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Create a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, please contact us at support@activitar.com.

