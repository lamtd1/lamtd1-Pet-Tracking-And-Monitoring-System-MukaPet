# Pet Monitoring System

## Overview
The Pet Monitoring System is an AI-powered solution designed to track and analyze pet activities in real time. It utilizes advanced image recognition technology to detect abnormal behaviors and alert pet owners promptly. The system also provides historical behavior reports, remote control features, and valuable pet care information.

## Features

### 1. Real-Time Pet Monitoring
- Uses AI-powered camera (YOLOv10) to track pet movements and activities.
- Live video streaming via a web application built with ReactJS and AntDesign.
- Video data is processed and stored in MySQL for fast retrieval and stable performance.

### 2. Behavior Recognition & Danger Alerts
- Detects abnormal behaviors such as excessive barking, scratching furniture, or interacting with dangerous objects.
- Sends instant alerts to the owner's phone or email when a dangerous situation is identified.
- All behavior analysis data is stored in MySQL and can be accessed via the web application.

### 3. Behavior History & Reports
- Records pet activity and health data, generating weekly and monthly reports.
- Displays insights in visual charts using ChartJS to help owners track trends and make informed decisions.

### 4. Customizable Alerts
- Owners can set alert thresholds according to their pet's habits, reducing false alarms.
- AI continuously learns and optimizes detection algorithms to improve accuracy.

### 5. Shared Monitoring Access
- Allows owners to share monitoring access with family members while away.
- Secure access management with JWT authentication to ensure data privacy and security.

### 6. Pet Care Guidance
- Provides useful information on pet health, nutrition, and care tips to help owners improve pet well-being.

### 7. Flexible Deployment & High Security
- Backend built with Java Spring Boot and MySQL for high performance and scalability.
- Docker containerization for seamless deployment across multiple environments.
- API testing performed using Postman to ensure accuracy, security, and efficiency before deployment.

## Technologies Used
- **AI & Image Recognition:** YOLOv10 for behavior detection.
- **Frontend:** ReactJS, AntDesign, ChartJS.
- **Backend:** Java Spring Boot, MySQL.
- **Security:** JWT authentication.
- **Deployment:** Docker for containerization.
- **API Testing:** Postman.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/pet-monitoring-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pet-monitoring-system
   ```
3. Set up and run the backend:
   ```bash
   cd backend
   mvn spring-boot:run
   ```
4. Set up and run the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```
5. (Optional) Use Docker for deployment:
   ```bash
   docker-compose up -d
   ```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the system.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or support, please contact: [your-email@example.com]

