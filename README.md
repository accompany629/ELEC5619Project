# Group12 - PoemCraft
PoemCraft is a web-based AI chatbot designed to inspire poetry creation. The project uses Spring Boot for the backend and Vue.js for the frontend.


This application should use Java for backend development and integrate one or more third-party large model APIs to tackle complex real-world issues, ultimately providing users with a web application solution.


## Project Structure

/poemcraft-backend # Spring Boot backend 
/poemcraft-frontend # Vue.js frontend

## Setup Instructions

### Backend
0. Use Mysql to create a new Schema poemcraft
1. Run src/sql/poemcraft.sql under the poemcraft Schema to inital the database
2. Navigate to the `poemcraft-backend` directory.
3. Build the project:
   ```bash
   mvn clean install
4. Run the application:
    ```bash
    mvn spring-boot:run

### Frontend
1. Navigate to the poemcraft-frontend directory.
2. Install dependencies:
    ```bash
    yarn add all
3. Start the development server:
    ```bash
    npm run serve

## Usage
Access the frontend at http://localhost:8080.
Interact with the chatbot by entering your text and receive poetic responses generated by AI.

## Contributing
### Group 12 Tue 05-08:
Renjie Yao, Jinyuan Liu, Shuxin Zhu, Ce Wang, Leyao Lu

## License
This project is licensed under the MIT License.
